# Top-Down Brief

**By [Abraham](https://theabrahambrand.com)**

A Claude plugin that makes sure outgoing official communications lead with the answer, group their supporting points logically, and read in a consistent professional tone.

Every piece follows the same shape: state the main point first, support it with 2–5 distinct points of the same kind, back each with evidence, and end with a clear ask.

## What's included

| Skill | How it runs | What it does |
|---|---|---|
| **top-down-brief** | Automatically, whenever you write or polish a formal email, memo, letter, report, proposal, update, announcement or slide text | Builds the structure (main point, Situation–Complication–Question introduction, 2–5 non-overlapping key points, evidence, clear ask), writes in house style and runs a pre-send checklist |
| **/top-down-brief:draft** | You run it with notes or a brief | Produces a send-ready draft, a one-glance structure summary, and a list of placeholders to fill in |
| **/top-down-brief:review** | You run it with a pasted or attached draft | Gives a verdict (Ready to send / Minor fixes / Needs restructuring), a six-point scorecard, the key issues, and a restructured version |

## The six checks

1. **Answer first**: the main point or request is in the first two sentences and the subject line.
2. **Question answered**: the piece answers the one question the reader has.
3. **Key-point logic**: 2–5 supporting points, the same kind of idea, no overlaps or gaps, deliberately ordered.
4. **Support**: specific facts back each point; nothing irrelevant; nothing invented.
5. **Clear ask**: specific action, owner and deadline.
6. **Tone**: plain, precise, courteous and confident; matches the reader and house style.

## Example

**Before**: background first, request buried, "Let me know your thoughts."

**After**:

> **Subject:** Decision needed by Wed 30 Sep: Switch cloud hosting to CloudNova
>
> I recommend we give DataServe notice and move to CloudNova when our contract renews on 31 October. I need your approval by Wednesday 30 September, as the 30-day notice period ends on 1 October.
>
> 1. **Better reliability:** 99.95% uptime guarantee, against four DataServe outages in Q3.
> 2. **Lower cost:** AED 38,000 a month against AED 45,000, saving AED 84,000 a year.

## Installation

In Claude Code:

```
/plugin marketplace add the-abraham-brand/top-down-brief
/plugin install top-down-brief@top-down-brief
```

In the Claude app, install it from the plugin directory once it's listed.

## Customizing

Edit `skills/top-down-brief/references/house-style.md` to set your organization's spelling (default: British English), date format, sign-offs, signature block, required disclaimers, banned words and approved terminology.

## Structure

```
.claude-plugin/
  plugin.json
  marketplace.json
skills/
  top-down-brief/          core method (loads automatically)
    SKILL.md
    references/
      pyramid-rules.md     structure rules and common fixes
      introductions.md     Situation–Complication–Question patterns by document type
      formats.md           email, memo, letter, report, proposal, update, slides
      tone.md              professional tone rules and wording swaps
      checklist.md         pre-send checklist and verdict rules
      house-style.md       organization conventions (edit this)
  draft/SKILL.md           /top-down-brief:draft
  review/SKILL.md          /top-down-brief:review
```

## Works well with

All by [Abraham](https://theabrahambrand.com), and made to work together:

- [My Business Brain](https://github.com/the-abraham-brand/my-business-brain) keeps what your business knows in one place, with sources, in English and Arabic, so your drafts start from facts you can trust.
- [Top-Down Verify](https://github.com/the-abraham-brand/top-down-verify) fact-checks a document before it goes out.
- [Top-Down Startup Pitch Deck](https://github.com/the-abraham-brand/top-down-startup-pitch-deck) builds a research-backed investor deck.

## Credits

Top-Down Brief is designed and maintained by Abraham ([theabrahambrand.com](https://theabrahambrand.com)). Its structure applies the Pyramid Principle described by Barbara Minto in *The Pyramid Principle: Logic in Writing and Thinking*. This is an independent project, not affiliated with or endorsed by Barbara Minto or Minto International.

## License

MIT © 2026 Abraham
