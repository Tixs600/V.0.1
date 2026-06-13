# V.0.1 Project Context

## Project Purpose

V.0.1 is a knowledge organization project for storing, editing, and indexing topics learned through chats.

The goal is to turn scattered conversations into a structured learning map. Topics should be grouped by subject, usefulness, frequency, and the background knowledge needed to understand them.

## Core Idea

Knowledge should be organized in the order it becomes understandable.

Advanced topics should be connected to their foundations. For example, quantum physics should not appear before basic math unless the structure includes clear bookmarks or prerequisite links that lead back to the needed background.

## Organization Principles

- Create main categories when a new broad subject appears.
- Create subcategories when a subject becomes more specific.
- Preserve the order of learning where possible.
- Connect advanced topics to prerequisite topics.
- Add bookmarks when background knowledge is stored elsewhere.
- Let the structure grow naturally based on the user's needs.

## Example Categories

- Mathematics
- Science
- Economics
- Philosophy
- Programming
- Writing
- Personal notes
- Open questions

## Planned Repository Structure

```text
raw-chats/
  chatgpt-exports/
  pasted-chats/

index/
  main-index.md
  science.md
  economics.md
  prerequisites.md
  bookmarks.md
```

## Chat Transfer Notes

Normal ChatGPT conversations are separate from Codex project threads. Codex cannot automatically see normal ChatGPT chat history.

Useful ways to bring chat context into this project:

- Paste relevant chat excerpts into a Codex thread.
- Share individual ChatGPT conversations when available.
- Export ChatGPT data and place relevant files in the repository.
- Store summarized decisions and project direction in this context file.

For privacy, exported ChatGPT data may contain personal information. This repository should stay private if raw chat exports or personal notes are stored here.

## GitHub Access Notes

The GitHub repository is:

```text
Tixs600/V.0.1
```

The previous Codex thread discussed limiting GitHub access so Codex/OpenAI only works with selected repositories. The preferred setup is to restrict the GitHub connector to selected repositories where possible.

## Current Status

- A README was created in the GitHub repository in the previous Codex thread.
- This file records the project context so future Codex threads can quickly understand the purpose and organization plan.
- Next likely step: create the first `index/` files and decide how raw chat imports should be named and summarized.
