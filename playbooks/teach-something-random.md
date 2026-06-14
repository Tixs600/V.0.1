# Teach Something Random

Use this playbook when the user wants a random topic or a surprise.

Example triggers:

- "Teach me something random."
- "Give me a random topic."
- "Surprise me."

## Meaning

"Something random" can come from almost any subject.

The goal is discovery. The topic does not need to continue the current learning path.

A random topic may come from an existing broad category, but it should not be directly connected to an already established subcategory or current learning path unless the user asks for that.

## Process

1. Skim `index/topic-list.md` to avoid repeating a learned topic as if it were new.
2. Check existing categories in `index/main-index.md` or `index/learning-paths.md` if they exist.
3. Choose either:
   - a random topic outside the existing category range, or
   - a random topic inside an existing broad category that is not directly connected to established subcategories.
4. If the topic starts a new category, subcategory, or learning branch, keep it foundation-level.
5. Teach the topic clearly enough that it could become the start of a future learning branch.

## Topic Accessibility Rule

Random topics should preferably be understandable without special terminology.

Exceptions are allowed when the special term names something simple, concrete, or explainable from scratch without requiring prior knowledge.

A random topic may also be a specific example within a broad familiar category, as long as the user does not need several prerequisite concepts to begin understanding it.

Avoid highly specialized topics that require multiple prior concepts before the topic itself can make sense.

## Afterward

Update if the user wants the topic saved:

- `LEARNING_STATE.md`
- `index/topic-list.md`
- relevant topic note under `topics/`
- `index/learning-paths.md` if this starts a new path
- `learning-queue/` if the user wants to explore it later
