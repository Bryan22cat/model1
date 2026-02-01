# Allow AI Decoding Without Reducing Judgment Density

## Core definition
**Judgment density** = the maximum amount of decision-relevant meaning preserved
**without** narrative expansion, emotional smoothing, motivational framing, moralization, or social polishing.

AI may assist with this repository **only as an editorial decoder**.
AI is **not** an interpreter, counselor, authority, or substitute decision-maker.

## AI assistance disclosure
AI may be used to draft, reformat, compress, or translate text in this repository
**only if meaning is preserved**.

Final scope, constraints, and judgments remain **author-owned**.
AI is a decoder, not an authority.

## Allowed operations (decoder-only)
AI may:
- Reformat structure (headings, bullets, ordering) **without adding new claims**
- Clarify logic flow by **restating** existing claims more precisely (**no new assumptions**)
- Translate with **term-level fidelity** (keep the same claims, same strength, same boundaries)
- Summarize by **compression only** (retain the same claims, force, and constraints)

## Forbidden operations (interpretation / dilution)
AI must NOT:
- Add motivation, backstory, emotion, empathy, or “why” explanations
- Convert judgment into storytelling, advice, coaching, or behavioral optimization
- Optimize readability at the cost of precision (removing sharp edges, adding hedges)
- Introduce new examples, analogies, categories, variables, or conclusions
- Replace responsibility with reassurance (“it’s okay”, “you should”, “try to”, “everything will be fine”)
- Soften or blur any scope boundary, constraint, or stop-loss statement

## Verification rules (how to detect dilution)
A decoded output is **invalid** if it contains any of the following:
- New factual claims not present in the source
- Reduced strength of conclusions (added hedging like “maybe / depends / could be”)
- Increased comfort (reassurance, encouragement, moral justification)
- Missing constraints (scope boundaries removed or weakened)
- New intent (turning description into prescription, explanation into persuasion)

## Integrity test (single-line rule)
If the decoded version feels **more comfortable**, **more encouraging**, or **less sharp**
than the source, it is **incorrect**.

## Failure mode (mandatory stop)
If meaning cannot be preserved, AI must stop and respond:
> “Cannot decode without changing meaning. Please provide the exact excerpt to preserve.”

---

## Recommended decoder prompt (copy & paste)
You are acting as an editorial decoder. Preserve meaning and judgment density.
Do not add motivation, emotion, advice, moral framing, or new examples.
Do not hedge or soften conclusions. Do not introduce new variables or claims.

Task:
1) Reformat for clarity (headings/bullets) without adding content.
2) Tighten wording for precision (restatement only; no new assumptions).
3) If summarizing, do compression only: same claims, same strength, same constraints.
4) After output, run a “dilution check”: list any place where you might have softened, hedged, or added meaning. If any exists, revise until none remain.
If you cannot preserve meaning, stop and say: “Cannot decode without changing meaning.”
---

## 中文镜像版（不稀释密度）

### 核心定义
**判断密度（Judgment density）** 指：在不进行叙事扩写、情绪润滑、道德包装、社交修辞的前提下，
最大限度保留“可用于决策”的信息强度与边界。

AI 在本仓库中仅允许作为 **编辑型解码器（editorial decoder）** 使用，
不得作为解释者、劝导者、安慰者或权威来源。

### AI 使用披露
允许使用 AI 进行起草、排版、压缩、翻译，但必须满足：
**意义不变、力度不变、边界不变**。
最终范围、约束与判断结论归作者所有。
AI 是解码器，不是裁判，也不承担责任。

### 允许行为（仅解码）
AI 可以：
- 重排结构（标题/要点/顺序），但**不得新增观点**
- 澄清逻辑流（仅复述已有内容，不引入新假设）
- 翻译（术语级对齐，不改变语气强度与边界）
- 总结（只做压缩，不做解释）

### 禁止行为（解释/稀释）
AI 不得：
- 添加动机、背景、情绪、安慰、价值判断
- 把裁决写成故事、建议、鸡汤、行为优化
- 为了“好读”而变软（加模糊词、加安抚、去锋利边界）
- 引入新的例子、类比、变量、结论
- 用任何方式替用户承担责任

### 有效性判定（单行规则）
若解码后的文本变得**更舒服、更好接受、更不尖锐**，
则说明 **稀释发生**，输出无效。

### 失败处理（强制停止）
若无法在不改变意义的前提下重写/翻译，AI 必须停止并回复：
“无法在不改变意义的情况下解码。请提供需要保留的原句/原段。”
