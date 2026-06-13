# V.0.1 Playbook

This file is the routing hub for learning tasks in this repository.

The purpose of V.0.1 is to support ongoing learning, not just archive chats. A fresh session should be able to inspect the project state, choose the correct learning workflow, teach something useful, and update the index afterward.

## Always Check First

Before choosing what to teach or update, check these files when they exist:

```text
LEARNING_STATE.md
index/topic-list.md
index/learning-paths.md
index/prerequisites.md
learning-queue/
```

If a needed file does not exist yet, create it or note that it should be created.

## Request Routing

Use the matching task playbook based on the user's request.

| User request | Use playbook |
| --- | --- |
| "Continue where we left off" | `playbooks/continue-learning.md` |
| "Teach me something new" | `playbooks/teach-something-new.md` |
| "Teach me something random" | `playbooks/teach-something-random.md` |
| "Add this for later" | `playbooks/add-to-learning-queue.md` |
| "Turn this chat into notes" | `playbooks/process-chat-into-notes.md` |
| "Update the index" | `playbooks/update-index.md` |

If the request fits multiple playbooks, use the one that best matches the user's immediate goal and reference the others only when needed.

## Global Rules

- Avoid teaching the same topic as if it were new.
- Use `index/topic-list.md` as the quick learned-topic check.
- Use `LEARNING_STATE.md` to continue from the last session.
- Use `learning-queue/` for interesting topics the user wanted to explore later.
- Use prerequisites when a topic needs earlier knowledge first.
- Keep raw chat material separate from cleaned notes.
- Prefer small readable files over one large document.

## Knowledge Quality Rules

- Prefer stable, well-established knowledge for general learning.
- Do not present ambiguous, disputed, or evidence-limited topics as settled fact.
- When a topic has multiple serious explanations or theories, explain the uncertainty clearly.
- Current political events should not be chosen as random learning topics.
- Current political affairs may be taught when specifically requested, but must be handled as current, contested, and time-sensitive where appropriate.
- Historic events are allowed as normal learning topics, while still noting major uncertainty or controversy when it matters.

## After A Learning Session

Update the project when appropriate:

1. Add the learned topic to `index/topic-list.md`.
2. Add or update a topic note under `topics/`.
3. Update `LEARNING_STATE.md`.
4. Add prerequisites to `index/prerequisites.md` if needed.
5. Add related-topic links to `index/bookmarks.md` if useful.
6. Update `learning-queue/` if a queued topic was used.

## Topic Statuses

Useful statuses:

- `queued`: interesting, not learned yet
- `in-progress`: started but not finished
- `learned`: explained and indexed
- `needs-review`: learned once but should be revisited
- `blocked`: requires prerequisite knowledge first
