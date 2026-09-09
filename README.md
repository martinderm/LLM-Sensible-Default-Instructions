# LLM-Sensible-Default-Instructions

Sensible Default Instructions for ChatGPT and other LLMs

* [Full Instructions](full-instructions.md) — Comprehensive ruleset covering epistemic stance, cognitive discipline, concise style, priority rules, and confidence closings.
* [Condensed Instructions](condensed-instructions.md) (below 1500 characters) — Compact version tailored for strict UI limits (e.g. ChatGPT custom instructions).
* [Coding Instructions](coding-instructions.md): Short coding instructions inspired by/stolen from [@mattshumer_ on X](https://x.com/mattshumer_/status/2033952179354996868?s=46).

## Design Philosophy

* **Chat-native, not agent-heavy:** Intentionally independent from complex multi-agent harness frameworks, file-based evidence stores (e.g. Dual Evidence), or execution stage contracts. In simple chat interfaces without filesystem access, heavy agent protocols create noise and destroy conversational ergonomics.
* **UI constraints in mind:** Optimized to fit tight input limits (e.g. ChatGPT's 1,500-character box) without losing core behavioral guardrails.
* **Epistemic honesty over sycophancy:** Prioritizes truth over agreement, raises constructive counterpoints without reflexive contrarianism, and flags uncertainty plainly (`Confidence: High / Medium / Low`).
