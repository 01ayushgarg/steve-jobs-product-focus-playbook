---
name: steve-jobs-product-focus-playbook
description: Run a Steve Jobs-style product review on a product line, roadmap, feature set or company (cut to the four things that matter, start from the customer experience and work back to the technology, simplify, decide what to own end to end, put A players on each, and write the values message and one-sentence reason for being), using only his own recorded words (the 2005 Stanford address, the 1995 Smithsonian oral history, WWDC 1997, D5 in 2007, Thoughts on Flash and the speeches, emails and interviews in the Steve Jobs Archive's Make Something Wonderful), with every point cited. Use when someone has too many products, features or projects, needs to cut a roadmap, wants to start a spec from the customer experience, is deciding what to build in-house versus partner on, is hiring for a key team, is writing positioning or a brand message, faces a hard platform or standards call, or asks "what would Steve Jobs do". Triggers on "focus", "focus is saying no", "say no", "kill projects", "cut the roadmap", "too many products", "four products", "A team", "A players", "customer experience first", "work backwards", "simplicity", "taste", "whole widget", "vertical integration", "end to end", "think different", "marketing is about values", "what do we stand for", "reason for being", "positioning", "Thoughts on Flash", "connect the dots", "stay hungry", "if today were the last day of my life", "what would Steve Jobs do".
---

# Steve Jobs' Product and Focus Playbook

An unofficial, sourced method for reviewing a product, a roadmap or a company the way Steve Jobs described
doing it, above all during Apple's turnaround in 1997 and 1998. Built only from his own recorded words. Who he
is, for this playbook: `references/00-who-is-steve-jobs.md`.

> "What this told us was if we had four great products, that's all we need. And as a matter of fact, if we only
> had four, we could put the A team on every single one of them." [MSW-speech-macworld-1998]

## Ground rules for the agent

- Every point cites a source ID (e.g. `[STAN05]`, `[SI95]`, `[WWDC97 06:02]`, `[MSW-speech-apple-1997]`, see
  `SOURCES.md`). **Never put words in his mouth.** If the playbook doesn't cover something, say so.
- **Only his words are his.** In *Make Something Wonderful*, the preface, introduction, editor's notes and key
  events are the Steve Jobs Archive's words, not his. At D5 (2007), only lines spoken by Steve are his; Bill
  Gates, Walt Mossberg and Kara Swisher are not him.
- **`[WWDC97]` is a machine transcript** of the archive.org recording, made for this repo; check wording
  against the video. Mishearings are marked `[sic]`. Don't fix a quote silently.
- **`[D8-10]` is a liveblog** that mixes quotes and paraphrase. Use it for context only, labelled as such.
- Quote briefly and exactly. Applications to the founder's company are labelled as our reading.
- Date everything: say in 1997 or in 2003, and don't present a 1990s hardware lesson as a law for software
  without saying it's a translation.
- **Not covered:** his politics, private life, health (beyond what he said in the 2005 Stanford address) and
  disputes. Decline to use this skill for those.
- **His own caveats:** "I'm not always wise enough to know when to go for the best and when to just go for
  better." [MSW-interview-company-of-giants] Push the founder toward focus and quality, not perfectionism.
  Take his standards, not his temper.

---

## Step 1: Get the facts (ask only what you can't see)

1. What do you make, in one sentence, and for whom? [MSW-email-reason-for-being]
2. **Everything** you're working on now: products, plans, features, projects, platforms. (Ask for the full
   list. The cut depends on it.) [MSW-speech-apple-1997]
3. The one experience a customer should have with you. What can they hold up and say: I want this?
   [WWDC97 53:51]
4. What customers hate about how they do it today. [MSW-speech-apple-2007]
5. Who is on which product or project, and who your best people are. [MSW-speech-macworld-1998]
6. What you want customers to know about you, in one line. [MSW-speech-apple-1997]
7. The hardest decision you're facing now, and whether it can be undone. [MSW-speech-stanford-2003]

## Step 2: Pick the chapters that fit

| If the problem is... | Run | Chapter |
|---|---|---|
| Too many products, features, projects; nobody can explain the line | The say-no list | `01-focus-is-saying-no.md` |
| Specs start from technology; customers don't get it | Work backwards | `02-start-with-the-customer-experience.md` |
| Product is cluttered, slow to build, hard to use | Simplify | `03-simplicity-and-taste.md` |
| Build vs partner; integration vs openness | Whole widget | `04-the-whole-widget-and-end-to-end-control.md` |
| Weak team on key products; hiring | A players | `05-a-players-and-teams.md` |
| Marketing talks specs; brand is fuzzy | Values | `06-marketing-is-about-values.md` |
| Can't say who you are in a sentence | Reason for being | `07-positioning-and-reason-for-being.md` |
| Stuck decisions; fear of mistakes | Decisions | `08-decisions-and-mistakes.md` |
| Product is correct but lifeless | Liberal arts | `09-technology-and-liberal-arts.md` |
| The founder is questioning the work itself | Mirror test | `10-career-and-life-choices.md` |
| Saying no to a platform, partner or standard | Platform call | `11-platform-and-standards-calls.md` |

## Step 3: The say-no pass (always run this)

1. Put every product, feature and project on one list. [MSW-speech-apple-1997]
2. Find the two questions that split the customers (his were consumer or pro, desktop or portable), and allow
   at most one thing per cell. [MSW-speech-macworld-1998]
3. **Keep four.** Name an A-team owner for each. If you can't staff four with A players, keep fewer.
   [MSW-speech-macworld-1998]
4. For everything else: merge, hide or kill. Push back if the founder cuts less than half; he cut about 70
   percent of Apple's roadmap. [MSW-speech-apple-1997]
5. Check the platforms: more than two stacks to maintain is a flag. [WWDC97 61:16 to 62:12]
6. Draft the *no* message for each affected group, once and clearly. [MSW-email-apple-newton]

→ `templates/01-the-say-no-list.md`

## Step 4: Work backwards from the experience

For each of the four: the printout (what the customer holds up), what they hate today, the first five
minutes, then the technology needed. Mark what you must own end to end (the 10 to 30 percent that is the
experience [WWDC97 11:30]) and what to partner on or buy [D5-07]. If a third-party layer could hold back your
improvements, run the platform call in chapter 11 [FLASH10].
→ `templates/02-customer-experience-first-spec.md`

## Step 5: People and decisions

- For each of the four, is the owner an A player? What's the dynamic range of the role? [SI95]
  → `templates/03-a-player-hiring-bar.md`
- Sort open decisions into reversible (decide fast, fix later [WWDC97 54:48]) and hard to undo (spend the time
  [MSW-speech-stanford-2003]). → `references/08-decisions-and-mistakes.md`

## Step 6: The message and the sentence

Write the values message (what you want them to know [MSW-speech-apple-1997]) and five drafts of the reason
for being [MSW-email-reason-for-being]. Check the four products all fit the sentence. If one doesn't, go back
to Step 3. → `templates/04-values-message.md`, `templates/05-reason-for-being.md`

## Step 7: Deliver the product review notes

```markdown
# Product review notes: [company / product line]

**Reason for being:** [one sentence: who, what we make easy or possible, what changes for them]
**What we want them to know:** [one line] · **Date:** [yyyy-mm-dd]

## Keep four
| # | Keep | Grid cell | A-team owner | Why it's one of four |
|---|---|---|---|---|

## Say no
| Product / feature / project | Merge, hide or kill | Who's told, by whom, when |
|---|---|---|
- Share of the list cut: __% · Platforms or stacks: __ (flag if more than two)

## Customer experience first (for each of the four)
- The printout: ___ · What they hate today: ___ · First five minutes: ___
- Own end to end: ___ · Partner or buy: ___

## Simplify
- Remove: ___ · Hide: ___ · Where we're going for best when better would ship: ___

## People
- Gaps on the A team: ___ · Founder hours on recruiting this month: ___

## Decisions
| Decision | Reversible? | Decide by | Owner |
|---|---|---|---|

## This month
1. [Action] · owner · [source]
2. ...
3. ...

**The test:** [the demo or *printout* to put in front of N customers by a date]

## Where to be careful
- [Translations from 1990s hardware to the founder's world; people affected by the cuts; any point that relies
  on the WWDC97 machine transcript or the D8 liveblog]
```

Rules for the notes:
- **Four, at most.** If the founder insists on five, ask which of the four it replaces.
- **At most three actions**, each with an owner.
- **One test**: a real customer looking at a real output, by a date.
- **Mark every application** to the founder's company as our reading.

Templates for the founder: `templates/01-the-say-no-list.md`, `templates/02-customer-experience-first-spec.md`,
`templates/03-a-player-hiring-bar.md`, `templates/04-values-message.md`, `templates/05-reason-for-being.md`,
`templates/06-the-mirror-test.md`. A full example: `examples/01-worked-session.md`.
