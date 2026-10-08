# Steve Jobs' Product and Focus Playbook

**An unofficial, fully sourced playbook and AI skill that runs Steve Jobs' product method (focus by saying no,
start from the customer experience, simplicity, the whole widget, A players, values-led marketing and a
one-sentence reason for being) on your product line, roadmap or company. Built only from his own recorded
words.**

Steve Jobs co-founded Apple in 1976, started NeXT and bought Pixar's graphics group after he left Apple in
1985, and came back in 1997 when Apple bought NeXT. He explained how he decided what to build, what to cut and
who to build it with many times on the record: in a 1995 oral history for the Smithsonian, in an open Q&A at
Apple's developer conference in 1997, to MIT students in 1992, to Wired in 1996, BusinessWeek in 2004 and
Fortune in 2008, in his 2005 Stanford commencement address, in his 2010 open letter on Flash, and in the
speeches, emails and interviews the Steve Jobs Archive published free in *Make Something Wonderful* (2023). This repo turns those into a method you can run on your own company this week.

> "What this told us was if we had four great products, that's all we need. And as a matter of fact, if we only
> had four, we could put the A team on every single one of them."
> Steve Jobs, Macworld (July 1998) [MSW-speech-macworld-1998]

> ⚠️ **Unofficial.** Not written, reviewed or endorsed by Apple, the Steve Jobs Archive, Stanford, the
> Smithsonian or anyone connected to Steve Jobs. It's a structured guide in our own words, with short credited
> quotes and a link to every source. It covers building products and companies only: no politics, no private
> life.

---

## What's inside

### The playbook

| # | Chapter | What you'll learn |
|---|---|---|
| 00 | [Who he is, for this playbook](references/00-who-is-steve-jobs.md) | A timeline from the sources · how to weigh each source · what to borrow and what not to |
| 01 | [Focus is saying no](references/01-focus-is-saying-no.md) | The hundred other good ideas · 70% of the roadmap · fifteen platforms to four · a path for one-product startups · failure modes |
| 02 | [Start with the customer experience](references/02-start-with-the-customer-experience.md) | Work backwards · the LaserWriter printout · "the first few hundred customers were us" [FORTUNE08 p2] · the month-three moment |
| 03 | [Simplicity and taste](references/03-simplicity-and-taste.md) | Design is how it works · get simple again · taste is trained · the editing pass, step by step |
| 04 | [The whole widget and end-to-end control](references/04-the-whole-widget-and-end-to-end-control.md) | Own the primary technology · responsibility for the whole experience · his NeXT caveat · own, partner or buy |
| 05 | [A players and teams](references/05-a-players-and-teams.md) | 50 to 1 · results, potential, love of the work · *why are you here?* · a longer-term view of people |
| 06 | [Marketing is about values](references/06-marketing-is-about-values.md) | Think Different, for customers and for Apple · not speeds and feeds · when not to advertise |
| 07 | [Positioning and reason for being](references/07-positioning-and-reason-for-being.md) | The reason-for-being email · better, not just different · goals in order · product people |
| 08 | [Decisions and mistakes](references/08-decisions-and-mistakes.md) | 25 big decisions a year · talk it through until you agree · the reset button · the decision log |
| 09 | [Technology and the liberal arts](references/09-technology-and-liberal-arts.md) | Creativity is connecting things · humanities at Reed · two cultures at Pixar |
| 10 | [Career and life choices](references/10-career-and-life-choices.md) | Work worth your life · own the results · the mirror test · character in bad times |
| 11 | [Platform and standards calls](references/11-platform-and-standards-calls.md) | *Thoughts on Flash* (2010) taken apart as a seven-step method for a hard platform decision |
| 12 | [Launch, demo and the point of sale](references/12-launch-demo-and-retail.md) | Frame the category · three things, one device · 20 footsteps, not a 20-minute drive · Take 2 |
| 13 | [The weekly product review](references/13-the-weekly-product-review.md) | The Monday review · process makes you efficient · small teams for ideas |

### Templates

| Template | Use it to |
|---|---|
| [01 The say-no list](templates/01-the-say-no-list.md) | List every product, feature and project, keep what your A team can staff, and say no once (with a one-product path) |
| [02 Customer-experience-first spec](templates/02-customer-experience-first-spec.md) | Write the experience, then work backwards to the technology and decide what to own |
| [03 A-player hiring bar](templates/03-a-player-hiring-bar.md) | Size a role's dynamic range and check results, potential and conviction before an offer |
| [04 Values message](templates/04-values-message.md) | Decide what you want people to know about you, before any campaign |
| [05 Reason for being](templates/05-reason-for-being.md) | Write your one-sentence positioning in five drafts, then pressure-test it |
| [06 The mirror test](templates/06-the-mirror-test.md) | Ask the Stanford *last day* question of the work on your calendar, every day for a week |
| [07 The editing pass](templates/07-the-editing-pass.md) | Count one flow, remove, hide and merge, throw a draft away, and decide where *best* is worth it |
| [08 Launch and demo plan](templates/08-launch-and-demo-plan.md) | Problem, promise, reveal, demo, point of sale and the cost of trying |
| [09 Weekly product review](templates/09-weekly-product-review.md) | A fixed weekly agenda that walks every product in development |

### Worked example

[A full session, start to finish](examples/01-worked-session.md): a fictional air-quality monitor company with
invented numbers, run through the whole skill. Thirteen products, plans and projects became four.

---

## How to use this

### 1. Run it as an AI skill (10 minutes)

**Install** into your agent's skills folder. For Claude Code:

```bash
git clone https://github.com/01ayushgarg/steve-jobs-product-focus-playbook ~/.claude/skills/steve-jobs-product-focus-playbook
```

If your agent doesn't read skill folders, paste `SKILL.md` into the chat and attach the chapters it asks for.

**Then ask for a product review.** Copy and fill in:

```text
Run Steve Jobs' product review on my company.

What we make, and for whom (one sentence):
Everything we're working on (products, plans, features, projects, platforms):
The one experience a customer should have with us:
What customers hate about how they do it today:
Team, and who is on what:
What we want customers to know about us (one line):
The hardest decision we're facing, and whether it can be undone:
```

**You get back:** product review notes with the four things to keep and the A-team owner for each, everything
else to merge, hide or kill (and who tells whom), the customer experience for each of the four worked back to
the technology, what to own and what to partner on, gaps on the team, open decisions sorted by whether they
can be undone, your values message and reason for being, three actions for this month and one customer test.
Every point cites the speech, email, interview or letter it comes from.

**Other things you can ask:**
- *We have 12 products. Which four would you keep?*
- *Write this spec starting from the customer experience.*
- *Should we build this ourselves or partner?*
- *Is this candidate an A player?*
- *What do we want customers to know about us?*
- *Write our reason for being in one sentence.*
- *Help me write the 'no' for this platform, the way Thoughts on Flash did.*

### 2. Use the templates (30 minutes, no AI)

1. [The say-no list](templates/01-the-say-no-list.md) every quarter, or when nobody can explain the product
   line.
2. [Customer-experience-first spec](templates/02-customer-experience-first-spec.md) before any new product or
   major feature.
3. [A-player hiring bar](templates/03-a-player-hiring-bar.md) before you open a key role.
4. [Values message](templates/04-values-message.md) before a launch or a rebrand.
5. [Reason for being](templates/05-reason-for-being.md) once a year, or before a raise.
6. [The mirror test](templates/06-the-mirror-test.md) for one week, whenever the work feels wrong.
7. [The editing pass](templates/07-the-editing-pass.md) on your most-used flow, once a quarter.
8. [Launch and demo plan](templates/08-launch-and-demo-plan.md) four weeks before a launch.
9. [Weekly product review](templates/09-weekly-product-review.md) every week.

### 3. Read it

Start with chapter 01 if you're doing too many things, 02 if customers don't get the product, 05 if the team
is the problem, 06 and 07 if you can't say who you are, 11 if you're about to say no to a platform or
partner, 12 if a launch is coming, and 13 if nobody sees the whole picture.

**His own caveat:** "I'm not always wise enough to know when to go for the best and when to just go for
better." [MSW-interview-company-of-giants] Take the focus, not the perfectionism.

---

## How it stays honest

- **First-party only:** his speeches, emails, interviews, the Stanford text, the Smithsonian oral history and
  his open letter. No biographies, no listicles of rules attributed to him, no fan-made transcripts.
- **The Archive's words aren't his:** in *Make Something Wonderful*, the preface, introduction, editor's notes
  and timeline are the Steve Jobs Archive's. They're used only for dates and labelled every time.
- **Speakers are checked:** at D5 (2007), only lines Steve spoke are quoted. Bill Gates, Walt Mossberg and Kara
  Swisher are not him.
- **The WWDC 1997 session is a machine transcript**, made for this repo from the archive.org recording, and
  labelled wherever it's used. In v2 it is cited far less, and every remaining quoted line matched a second
  transcription made with a larger model. Lines that didn't match were dropped or paraphrased.
- **Edited and captioned sources are labelled:** the Smithsonian, Wired, BusinessWeek and Fortune interviews
  are edited by their publishers; MIT 1992 and Aspen 1983 are caption transcripts.
- **The D8 liveblog is context only:** it mixes quotes and paraphrase, and is labelled every time.
- **Every quote checked by script** against our saved plain-text copy of the specific source it cites
  (allowing only quote-mark, dash and whitespace differences), and checked for length (none over 60 words).
  The saved copies are copyrighted, so neither they nor the script are included; every source is linked, so
  any quote can be checked by hand.
- **Short works are mostly paraphrased:** for each speech, email or interview, quoted words are kept well
  under a tenth of the work.
- **Famous but unverified phrases left out:** lines often attributed to him that aren't in these sources
  aren't quoted.
- **Our own reading is marked**, never presented as his words.

## Sources

The full list, with dates and links, is in [`SOURCES.md`](SOURCES.md):

Stanford commencement address (2005) · Smithsonian oral history (1995) · D5 with Bill Gates (2007) · *Thoughts
on Flash* (2010) · WWDC 1997 closing session (machine transcript of the archive.org recording) · MIT Sloan talk
(1992, caption transcript) · Wired interview (1996) · BusinessWeek interview (2004) · Fortune interview (2008) ·
the Steve Jobs Archive's Aspen 1983 video captions · D8 liveblog (2010, context only) · 31 speeches, emails and
interviews from *Make Something Wonderful* (Steve Jobs Archive, 2023), dated 1983 to 2010.

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Steve Jobs' words and their publishers'. They're short, credited excerpts for commentary
  and are **not** covered by this license.

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote, a mislabelled speaker or a broken link? Open an issue with the source ID and the passage.
