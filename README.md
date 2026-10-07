# Steve Jobs' Product and Focus Playbook

**An unofficial, fully sourced playbook and AI skill that runs Steve Jobs' product method (focus by saying no,
start from the customer experience, simplicity, the whole widget, A players, values-led marketing and a
one-sentence reason for being) on your product line, roadmap or company. Built only from his own recorded
words.**

Steve Jobs co-founded Apple in 1976, started NeXT and bought Pixar's graphics group after he left Apple in
1985, and came back in 1997 when Apple bought NeXT. He explained how he decided what to build, what to cut and
who to build it with many times on the record: in a 1995 oral history for the Smithsonian, in an open Q&A at
Apple's developer conference in 1997, in his 2005 Stanford commencement address, in his 2010 open letter on
Flash, and in the speeches, emails and interviews the Steve Jobs Archive published free in *Make Something
Wonderful* (2023). This repo turns those into a method you can run on your own company this week.

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
| 00 | [Who he is, for this playbook](references/00-who-is-steve-jobs.md) | Apple, NeXT, Pixar and the 1997 return as the sources describe them · his own caveats |
| 01 | [Focus is saying no](references/01-focus-is-saying-no.md) | WWDC 1997 · cutting 70% of the roadmap · fifteen platforms to four products · the A team on each · saying no with respect |
| 02 | [Start with the customer experience](references/02-start-with-the-customer-experience.md) | Work backwards to the technology · the LaserWriter story · the iPhone started from hate · show, don't convince |
| 03 | [Simplicity and taste](references/03-simplicity-and-taste.md) | Taste is stubbornness · great costs time, not money · the line of code you never wrote · best vs better |
| 04 | [The whole widget and end-to-end control](references/04-the-whole-widget-and-end-to-end-control.md) | Integration as strength and weakness · his NeXT caveat · invent only 10 to 30% · own the experience, partner for the rest |
| 05 | [A players and teams](references/05-a-players-and-teams.md) | 50 to 1 · recruiting is the job · results, potential, conviction · managers who care · management by values |
| 06 | [Marketing is about values](references/06-marketing-is-about-values.md) | Think Different · a noisy world · not speeds and feeds · be clear on what you stand for |
| 07 | [Positioning and reason for being](references/07-positioning-and-reason-for-being.md) | Who is Apple? · the premier-company email · better, not just different · 5% vs 50% better |
| 08 | [Decisions and mistakes](references/08-decisions-and-mistakes.md) | Ten decisions a day vs three a quarter · mistakes mean decisions · ask to be challenged · grade yourself |
| 09 | [Technology and the liberal arts](references/09-technology-and-liberal-arts.md) | The calligraphy class · artists and engineers · Pixar's two cultures · creativity is connecting things |
| 10 | [Career and life choices](references/10-career-and-life-choices.md) | Connect the dots · love what you do · death as a decision tool · life was made up by people no smarter than you |
| 11 | [Platform and standards calls](references/11-platform-and-standards-calls.md) | *Thoughts on Flash* (2010) taken apart as a seven-step method for a hard platform decision |

### Templates

| Template | Use it to |
|---|---|
| [01 The say-no list](templates/01-the-say-no-list.md) | List every product, feature and project, keep four, put the A team on each, and say no once |
| [02 Customer-experience-first spec](templates/02-customer-experience-first-spec.md) | Write the experience, then work backwards to the technology and decide what to own |
| [03 A-player hiring bar](templates/03-a-player-hiring-bar.md) | Size a role's dynamic range and check results, potential and conviction before an offer |
| [04 Values message](templates/04-values-message.md) | Decide what you want people to know about you, before any campaign |
| [05 Reason for being](templates/05-reason-for-being.md) | Write your one-sentence positioning in five drafts, then pressure-test it |
| [06 The mirror test](templates/06-the-mirror-test.md) | Ask the Stanford "last day" question of the work on your calendar, every day for a week |

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
- *"We have 12 products. Which four would you keep?"*
- *"Write this spec starting from the customer experience."*
- *"Should we build this ourselves or partner?"*
- *"Is this candidate an A player?"*
- *"What do we want customers to know about us?"*
- *"Write our reason for being in one sentence."*
- *"Help me write the 'no' for this platform, the way Thoughts on Flash did."*

### 2. Use the templates (30 minutes, no AI)

1. [The say-no list](templates/01-the-say-no-list.md) every quarter, or when nobody can explain the product
   line.
2. [Customer-experience-first spec](templates/02-customer-experience-first-spec.md) before any new product or
   major feature.
3. [A-player hiring bar](templates/03-a-player-hiring-bar.md) before you open a key role.
4. [Values message](templates/04-values-message.md) before a launch or a rebrand.
5. [Reason for being](templates/05-reason-for-being.md) once a year, or before a raise.
6. [The mirror test](templates/06-the-mirror-test.md) for one week, whenever the work feels wrong.

### 3. Read it

Start with chapter 01 if you're doing too many things, 02 if customers don't get the product, 05 if the team
is the problem, 06 and 07 if you can't say who you are, and 11 if you're about to say no to a platform or
partner.

**His own caveat:** "I'm not always wise enough to know when to go for the best and when to just go for
better." [MSW-interview-company-of-giants] Take the focus, not the perfectionism.

---

## How it stays honest

- **First-party only:** his speeches, emails, interviews, the Stanford text, the Smithsonian oral history and
  his open letter. No biographies, no listicles of "Jobs' rules".
- **The Archive's words aren't his:** in *Make Something Wonderful*, the preface, introduction, editor's notes
  and timeline are the Steve Jobs Archive's. They're used only for dates and labelled every time.
- **Speakers are checked:** at D5 (2007), only lines Steve spoke are quoted. Bill Gates, Walt Mossberg and Kara
  Swisher are not him.
- **The WWDC 1997 session is a machine transcript**, made for this repo from the archive.org recording, and
  labelled wherever it's used. Mishearings are marked `[sic]`; garbled lines were left out.
- **The D8 liveblog is context only:** it mixes quotes and paraphrase, and is labelled every time.
- **Every quote checked by script** against the raw text, and against the specific source it cites.
- **Famous but unverified phrases left out:** lines often attributed to him that aren't in these sources
  aren't quoted.
- **Our own reading is marked**, never presented as his words.

## Sources

The full list, with dates and links, is in [`SOURCES.md`](SOURCES.md):

Stanford commencement address (2005) · Smithsonian oral history (1995) · D5 with Bill Gates (2007) · *Thoughts
on Flash* (2010) · WWDC 1997 closing session (machine transcript of the archive.org recording) · D8 liveblog
(2010, context only) · 29 speeches, emails and interviews from *Make Something Wonderful* (Steve Jobs Archive,
2023), dated 1983 to 2010.

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Steve Jobs' words and their publishers'. They're short, credited excerpts for commentary
  and are **not** covered by this license.

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote, a mislabelled speaker or a broken link? Open an issue with the source ID and the passage.
