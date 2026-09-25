---
name: top-down-brief
description: Draft, restructure or review official, professional communications using the Top-Down Brief method, based on the Pyramid Principle (answer first, then grouped supporting points, then evidence) with a professional-tone check. Use this whenever the user is writing or polishing anything that goes out formally under their or their organization's name, such as emails to executives, clients, partners, regulators or all-staff; memos; letters; announcements; approval or budget requests; status or progress updates; proposals; executive summaries; board or management papers; reports; and text slides. Also use it when the user pastes a draft and asks to "make it more professional", "tighten this", "check this before I send", "structure this" or "is this clear", even if they never mention Top-Down Brief or the Pyramid Principle. Do not use it for casual chat messages, personal notes, creative writing, or code documentation.
---

# Top-Down Brief

Readers of official communications are busy and take ideas in one sentence at a time. They understand fastest when they get the main point first and then see how the supporting points group beneath it. This skill makes every outgoing piece do that, in a tone that fits a professional setting.

Before starting, read `references/house-style.md`. It holds the organization's own conventions (spelling, sign-offs, banned words, disclaimers), and those override the defaults below.

There are two modes. Pick the one that matches the request:

- **Draft mode**: the user gives notes, facts, a goal or a rough idea and wants a finished piece.
- **Review mode**: the user gives an existing draft and wants it checked, fixed or restructured.

If the user pastes a draft *and* asks for the final version, run Review mode but lead with the rewrite.

## Step 1: Pin down the reader and the question

Work out, from the request (ask only if it truly cannot be inferred and a wrong guess would waste the draft):

1. **Who is the reader** and what do they already know?
2. **What question is in the reader's mind** that this piece answers? Nearly all business writing answers one of four:
   - What should we do?
   - How should we do it / how did we do it?
   - Should we do it? (including approval to spend money)
   - Why did it happen?
3. **What should the reader do or believe** after reading? This becomes the governing thought.
4. **What type of piece is it** (email, memo, letter, report, proposal, update, slides, announcement)? This picks the format in `references/formats.md`.

If the question cannot be stated in one line, the piece is not ready to be written. Resolve that first, with the user if needed.

## Step 2: Build the pyramid before writing prose

Sketch the skeleton in this order:

1. **Governing thought** (the top): one or two sentences that directly answer the reader's question. It must say something, not announce a topic. "We recommend moving 30% of search spend to Meta for Q4" is a governing thought; "Update on ad budget" is not.
2. **Introduction (S-C-Q)**: the Situation the reader already accepts, the Complication that creates tension, and the Question that follows. The introduction reminds; it does not inform, so include only what the reader knows or will readily accept. In emails it can shrink to one clause or disappear.
3. **Key line**: 2 to 5 points that each answer the question the governing thought raises ("Why?", "How?", "Which?"). Test them against the three rules:
   - **Summarize**: each point is a summary of what sits beneath it.
   - **Same kind**: the points are the same kind of idea (all reasons, all steps, all problems), nameable with one plural noun.
   - **Ordered**: they follow a deliberate order (time, structure, or degree of importance) and are MECE, with no overlaps and no gaps.
   Prefer an inductive key line (parallel reasons or steps). Use a deductive chain (statement, related statement, therefore) only when the reader needs the reasoning before accepting the action, and keep it to four steps at most.
4. **Support**: facts, figures, dates and owners beneath each key-line point. Keep only items that help prove the point above them; cut the rest or move it to an appendix.
5. **The ask / next steps**: what the reader must do, by when. Word actions as the end result they produce ("Approve the $40k budget by Friday 2 Oct"), not vague activity ("Look into the budget").

Reference files for this step:
- `references/pyramid-rules.md`: full rules, with fixes for the common failures. Read it for anything longer than a short email, and always in Review mode.
- `references/introductions.md`: S-C-Q patterns for directives, spending approvals, how-to, choosing among options, process changes, proposals, progress reviews, bad news and incident reports. Read the matching pattern before drafting an introduction.

## Step 3: Write it

- Follow the format for the piece type in `references/formats.md`.
- Apply `references/tone.md`: plain, precise, courteous, confident without overclaiming.
- Write headings and key-line points as full statements of the idea, in parallel grammatical form, not as labels ("Costs will fall 12% in year one", not "Costs").
- Never invent facts, figures, names, dates or commitments. Where something is needed but was not provided, insert a clear placeholder such as `[deadline]` or `[Q3 figure]` and list the placeholders after the draft.
- Keep the user's facts and intent. The job is restructuring and polishing, not changing the substance. If the substance itself looks weak (for example, the evidence does not support the recommendation), say so separately instead of quietly changing it.

## Step 4: Check before handing over

Run `references/checklist.md` against the draft and fix anything that fails. The five that matter most:

1. The main point is in the first two sentences (and in the subject line, for email).
2. Every key-line point answers the question raised by the governing thought.
3. Key-line points are the same kind, MECE and deliberately ordered.
4. No intellectually blank assertions ("There are three issues", "Several factors were considered") where the actual insight should be.
5. The reader knows exactly what to do next, and by when.

## Output format

### Draft mode

1. The finished piece, ready to send (subject line included for emails).
2. **Structure**: 3 to 5 lines showing the skeleton (governing thought, then the key-line points) so the user can check the logic at a glance.
3. **To fill in**: only if there are placeholders.

Keep commentary out of the piece itself.

### Review mode

1. **Verdict**: one line: *Ready to send*, *Minor fixes*, or *Needs restructuring*, with the single biggest reason.
2. **Scorecard**: the six checks from `references/checklist.md` (Answer first, Question answered, Key-line logic, Support, Clear ask, Tone), each marked Pass / Fix, with a few words on why.
3. **What's getting in the way**: the top issues, most important first, each naming the rule broken and quoting the sentence or section concerned. Only issues that matter; no padding.
4. **Revised version**: the full rewrite (skip this if the verdict is *Ready to send*; show only the small edits instead).
5. **Structure**: the skeleton of the revised version.
6. **To fill in / Worth checking**: placeholders, and any substance concerns (unsupported claims, missing data, a recommendation the evidence does not back).

## When the pyramid should bend

- **Bad news or sensitive messages** (redundancies, incidents, complaints to a senior person): still state the point early, but a one-sentence context line before it is fine so the reader is not blindsided. Burying bad news reads as evasive.
- **A reader who will resist the conclusion**, or a conclusion that will surprise them: lead with a short deductive chain, then the recommendation.
- **Very short messages** (a two-line confirmation): do not force a key line. Answer first, courteous close, done.
- **Legal, regulatory or contractual wording**: do not restructure mandated text; flag it and polish only what surrounds it.
- **Replies in an existing thread**: answer the question asked in the thread first; skip the S-C-Q introduction because the thread already provides it.
