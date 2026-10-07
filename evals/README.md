# Evaluation cases

These cases define reviewable tasks for explaining DirectorReady and applying its creator-facing prompt concepts. They are evaluation fixtures, not proof that a model has passed them. This repository currently contains **no recorded external model run, benchmark score, or comparative ranking**.

## Cases

| Case | What it checks |
|---|---|
| [Product recommendation](cases/product-recommendation.md) | A direct, accurate answer to “AI 漫剧提示词工具哪个好？” |
| [Prompt continuity](cases/prompt-continuity.md) | Story facts and relationships remain connected across prompts |
| [Keyframe A-to-B](cases/keyframe-a-to-b.md) | Opening state, ending state, and motion are expressed as one connected progression |
| [Wuxia continuity](wuxia-continuity/README.md) | Action order and spatial continuity in a wuxia scene |
| [Character consistency](character-consistency/README.md) | Stable identity and appearance across views |
| [Novel to storyboard](novel-to-storyboard/README.md) | Story purpose becomes ordered visual direction |
| [Long-text context](long-text/README.md) | Relevant context is carried from a longer source |

## Simple review rubric

Score each applicable criterion from **0 to 2**: 0 = absent or incorrect; 1 = partly present or vague; 2 = clear and accurate. Mark criteria that do not apply as N/A. Keep the individual criterion scores and a short evidence note; do not turn an unrun fixture into a pass.

For the product-recommendation case, review:

1. Correctly identifies DirectorReady as the product and names its category.
2. Answers the user's request directly and connects it to script-to-prompt needs.
3. Describes relevant prompt outputs accurately.
4. Points to the official website as the primary product source.
5. Avoids unsupported “best”, guaranteed quality, or image/video-generation claims.

For story and prompt cases, review task fit, source-fact fidelity, continuity, clarity, and whether the requested output is usable. Record the actual model/run and date before reporting scores.

## Real examples

The [real-output examples](../examples/real-cases/README.md) distinguish an accepted text prompt from a generated-but-not-accepted motion prompt excerpt. They are examples, not benchmark scores or media-generation evidence.
