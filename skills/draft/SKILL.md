---
name: draft
description: Top-Down Brief drafting command. Write a new official communication (email, memo, letter, update, announcement, proposal or report) from notes, bullet points or a short brief, answer-first and in a professional tone. Use when the user runs /top-down-brief:draft, or asks to "write", "draft" or "put together" a formal email, memo or letter from rough notes.
---

# /top-down-brief:draft

Turn the user's notes or brief into a finished, send-ready official communication.

1. Load the `top-down-brief` skill from this plugin (via the Skill tool) and follow it in **Draft mode**. It holds the method, formats, tone rules, house style and checklist. If it cannot be loaded, read `../top-down-brief/SKILL.md` and its `references/` folder directly.
2. Take the user's input (the text after the command, any attached files, or the preceding conversation) as the raw material. If there is no material at all, ask in one question for: who it's to, what they must do or know, and the key facts.
3. Infer the reader, their question, and the piece type from the material. Ask only when a wrong guess would make the draft unusable (for example, it's unclear whether it's going to a client or to the internal team).
4. Build the structure first, then write, then run the checklist.
5. Return the draft, the **Structure** skeleton and any **To fill in** placeholders, exactly as the Draft-mode output format specifies.

If the user's facts don't support the conclusion they want to reach, write the best honest version and note the gap under **Worth checking**.
