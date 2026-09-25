---
name: review
description: Top-Down Brief review command. Check an existing official communication before it goes out, score it against the Top-Down Brief structure and professional-tone checklist, explain what's getting in the way, and return a restructured version. Use when the user runs /top-down-brief:review, or pastes or attaches a draft email, memo, letter, report or slide text and asks to check, review, tighten, fix or "make it more professional" before sending.
---

# /top-down-brief:review

Review a draft official communication and return a verdict, a scorecard and a fixed version.

1. Load the `top-down-brief` skill from this plugin (via the Skill tool) and follow it in **Review mode**. It holds the method, formats, tone rules, house style and checklist. If it cannot be loaded, read `../top-down-brief/SKILL.md` and its `references/` folder directly.
2. The draft is the text after the command, an attached file (read .docx, .pdf, .pptx or .eml attachments with the matching tools), or the most recent draft in the conversation. If there is none, ask the user to paste or attach it.
3. Before judging, identify the reader, the question the draft should answer, and the piece type. If the user said who it's for, use that.
4. Run every item in the checklist (`../top-down-brief/references/checklist.md`). Judge structure first (checks 1 to 3), because a well-worded piece with a buried point still fails the reader.
5. Return the Review-mode output: **Verdict**, **Scorecard**, **What's getting in the way**, **Revised version**, **Structure**, **To fill in / Worth checking**.

Keep the author's facts, commitments and intent. When the draft is already good, say so and make only the small edits needed.

If the user attached a file and wants the fixed version back in the same format (for example a .docx), deliver the revised text in that format as well.
