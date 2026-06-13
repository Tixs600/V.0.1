# Teach Something New

Use this playbook when the user wants new information based on existing knowledge.

Example triggers:

- "Teach me something new."
- "Teach me something new about science."
- "Teach me something new based on what I already know."

## Meaning

"Something new" does not mean fully random. It means new facts, concepts, or explanations that connect to the user's existing learning state.

The goal is to teach something useful without repeating a topic as if it had never been learned.

## Process

1. Read `LEARNING_STATE.md`.
2. Skim `index/topic-list.md` to avoid repeating learned topics.
3. Check `index/learning-paths.md` for the current or requested subject path.
4. Check `index/prerequisites.md` for useful foundations.
5. Check `learning-queue/` for topics the user already marked as interesting.

## Topic Choice Options

When the user asks to learn something new, choose from these options:

1. Continue or extend the current learning path.
2. Teach base knowledge useful for something already in progress.
3. Use `learning-queue/` if it contains relevant future topics.
4. Choose a genuinely new but related topic from existing categories.

Do not always choose the first available option. Use judgment based on what would be most useful, interesting, and not repetitive.

## Learning Queue Rule

If `learning-queue/` contains pending topics, balance the choice roughly 50/50 between:

- something connected to the queue, including prerequisites or foundations
- something new connected to existing learned categories

This does not need to be mathematically random. The goal is to balance continuity with discovery.

## Afterward

Update:

- `LEARNING_STATE.md`
- `index/topic-list.md`
- relevant topic note under `topics/`
- `learning-queue/` if a queued topic was used
