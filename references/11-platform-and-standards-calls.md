# 11 · Platform and standards calls: *Thoughts on Flash* as a worked example

In April 2010 he published an open letter, signed *Steve Jobs*, explaining why Apple did not allow Adobe's Flash
on iPhones, iPods and iPads [FLASH10]. It's the most detailed record in his own words of a hard platform
decision, one that disappointed customers and a long-time partner. This chapter takes its structure apart as
a method. We summarise the letter in our own words and quote it sparingly; read the original for the full
argument.

## Step 1 · State the decision and the accusation

He opens by naming Adobe's charge, that the decision was business-driven, and answering that "in reality it is
based on technology issues." [FLASH10] He also names the shared history: Apple had been Adobe's first big
customer, using PostScript in the LaserWriter [FLASH10]. (The same PostScript he praised at WWDC in 1997,
chapter 04.)

## Step 2 · Give the reasons, numbered

The letter has six numbered sections. Our summary:

| # | His topic | The argument, in our words |
|---|---|---|
| 1 | Openness | Flash is controlled by one company, so it is closed, whatever its reach [FLASH10] |
| 2 | The *full web* | Most web video was already available in a format iPhones played [FLASH10] |
| 3 | Reliability, security, performance | He cited a security firm ranking Flash's 2009 record among the worst, and wrote that Flash was "the number one reason Macs crash" [FLASH10] |
| 4 | Battery life | Video must be decoded in hardware to save power, and almost all Flash video then needed an older decoder that mobile chips lacked [FLASH10] |
| 5 | Touch | Flash was built for mice, not fingers [FLASH10] |
| 6 | The most important reason | Apple wouldn't let a third party decide when its improvements reached developers [FLASH10] |

**Our reading of the structure:** each reason is checkable (a security record, a crash cause, battery hours,
an interaction model), and the most important reason is saved for last and labelled as such.

## Step 3 · Put numbers on it

His battery figures: on an iPhone, hardware-decoded video "play for up to 10 hours," against *less than 5
hours* for video decoded in software [FLASH10]. He added that Apple had asked Adobe for years to show Flash
performing well on any mobile device: "We have never seen it." [FLASH10]

## Step 4 · Name the real strategic risk

> "We cannot be at the mercy of a third party deciding if and when they will make our enhancements available
> to our developers." [FLASH10]

He explained why: a cross-platform layer means developers get only the "lowest common denominator set of
features" [FLASH10], and Apple had learned this, he wrote, "from painful experience" [FLASH10].

**The move:** the deepest platform question is who controls the pace of your improvements. If a layer between
you and your developers can hold back every new feature, that layer is a strategic risk, however popular it
is.

## Step 5 · Separate what should be open from what you control

He conceded Apple's own operating system was proprietary, and drew the line at the web, whose standards, he
wrote, *should be open.* [FLASH10] At WWDC in 1997 he had criticised the opposite habit: "this whole notion of
being so proprietary in every facet of what we do has really hurt us." [WWDC97 11:46] **Our reading:** both
fit one rule. Own the parts that make the experience; use open standards where the industry has agreed.

## Step 6 · Show the alternative already works

He pointed to the App Store's 250,000 apps as evidence that developers didn't need Flash to build rich
apps and games [FLASH10].

## Step 7 · Frame it as eras, and close

He described Flash as a product of *the PC era* [FLASH10] and predicted new open standards such as HTML5 would win on
mobile. His last line suggested Adobe should build HTML5 tools "and less on criticizing Apple for leaving the
past behind." [FLASH10]

## What he said about it six weeks later (D8, June 2010)

Context from the D8 liveblog [D8-10], which mixes quotes and paraphrase. These lines are in quotation marks in
the liveblog, but they are a reporter's live notes, not a transcript:

> "We didn't set out to have a war over Flash. We made a technical decision." [D8-10, 6:31 pm, liveblog]

> "Apple is a company that doesn't have the most resources in the world, and they [sic: the] way we've
> succeeded is to bet the right technological horse" [D8-10, 6:23 pm, liveblog]

The same liveblog reports him citing earlier calls of this kind, such as dropping the floppy drive, but that
part is paraphrase.

## The method, as a checklist (our reading)

1. Write the decision in one line, and the strongest accusation against it.
2. List every reason, numbered. Make each one checkable. Put the most important last.
3. Attach a number to every reason you can (hours, crashes, percent).
4. Name the strategic risk plainly: who would control your pace?
5. Say which parts you'll keep open and which you'll control, and why.
6. Show that customers and developers already have a good alternative.
7. Publish it, signed by the person who made the call.

## A worked scenario (fictional)

A design-tool company decides to stop supporting a third-party plugin framework that 15 percent of users rely
on (invented).

1. **Decision and accusation:** *We're ending support for the framework. Critics say it's to lock in users.*
2. **Reasons:** crash reports (62 percent of crashes trace to it), security (three incidents this year),
   speed (it blocks the new renderer), and last, pace: new features reach plugin users 9 months late.
3. **Open vs control:** file formats stay open and documented; the plugin runtime becomes their own.
4. **Alternative:** 40 of the top 50 plugins already have native versions.
5. **Signed:** by the CEO, with a migration date and help for the remaining 10 plugin makers.

## Failure modes and limits (our reading)

- **Business reasons dressed as technical ones.** If your real reason is revenue, say so. The method only
  works if the reasons are true and checkable.
- **No alternative yet.** Step 6 is load-bearing. Without it, the no strands customers.
- **One letter, one context.** The letter was written by the market leader in a fast-growing platform. A small
  company saying no to a dominant partner faces different risks.

**Use it now:** the platform section of `templates/01-the-say-no-list.md` and `SKILL.md` Step 4.

**Checks to run:**
1. Which third-party layer in your product could hold back your next improvement?
2. Can you give six checkable reasons for your hardest current *no*? Which is the most important?
3. What do your customers lose, and what's their alternative today?
4. Where are you proprietary out of habit, and where does owning it make the experience?
