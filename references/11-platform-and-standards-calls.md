# 11 · Platform and standards calls: "Thoughts on Flash" as a worked example

In April 2010 he published an open letter, signed "Steve Jobs", explaining why Apple did not allow Adobe's Flash
on iPhones, iPods and iPads [FLASH10]. It's the most detailed record in his own words of a hard platform
decision: one that disappointed customers and a long-time partner. This chapter takes it apart as a method.

## Step 1 · State the decision and the accusation

> "Adobe has characterized our decision as being primarily business driven" ... "but in reality it is based on
> technology issues." [FLASH10]

He opens by naming the history with the other side: "Apple was their first big customer, adopting their
Postscript language for our new Laserwriter printer." [FLASH10] (The same PostScript he praised at WWDC in 1997,
chapter 04.)

## Step 2 · Give the reasons, numbered

The letter has six numbered sections. Our summary, with one quote each:

| # | His heading | The argument in his words |
|---|---|---|
| 1 | "Open" | "By almost any definition, Flash is a closed system." [FLASH10] |
| 2 | The "full web" | "iPhone, iPod and iPad users aren't missing much video." [FLASH10] |
| 3 | Reliability, security and performance | "We also know first hand that Flash is the number one reason Macs crash." [FLASH10] |
| 4 | Battery life | "To achieve long battery life when playing video, mobile devices must decode the video in hardware; decoding it in software uses too much power." [FLASH10] |
| 5 | Touch | "Flash was designed for PCs using mice, not for touch screens using fingers." [FLASH10] |
| 6 | The most important reason | "We cannot be at the mercy of a third party deciding if and when they will make our enhancements available to our developers." [FLASH10] |


**Our reading of the structure:** each reason is checkable (a security record, a crash cause, battery hours,
an interaction model), and the most important reason is saved for last and labelled as such.

## Step 3 · Put numbers on it

> "The difference is striking: on an iPhone, for example, H.264 videos play for up to 10 hours, while videos
> decoded in software play for less than 5 hours before the battery is fully drained." [FLASH10]

> "We have routinely asked Adobe to show us Flash performing well on a mobile device, any mobile device, for a
> few years now. We have never seen it." [FLASH10]

## Step 4 · Name the real strategic risk

> "We know from painful experience that letting a third party layer of software come between the platform and
> the developer ultimately results in sub-standard apps and hinders the enhancement and progress of the
> platform." [FLASH10]

> "Hence developers only have access to the lowest common denominator set of features." [FLASH10]

**The move:** the deepest platform question is who controls the pace of your improvements. If a layer between
you and your developers can hold back every new feature, that layer is a strategic risk, however popular it
is.

## Step 5 · Separate what should be open from what you control

> "Apple has many proprietary products too. Though the operating system for the iPhone, iPod and iPad is
> proprietary, we strongly believe that all standards pertaining to the web should be open." [FLASH10]

Compare WWDC in May 1997, where he said the opposite habit had hurt Apple: "So I think this whole notion of
being so proprietary in every facet of what we do has really hurt us." [WWDC97 11:46] (`[WWDC97]` is a machine
transcript of the archive.org recording, made for this repo; check wording against the video.) **Our
reading:** both fit one rule. Own the parts that make the experience; use open standards where the industry
has already agreed.

## Step 6 · Show the alternative already works

> "And the 250,000 apps on Apple's App Store proves that Flash isn't necessary for tens of thousands of
> developers to create graphically rich applications, including games." [FLASH10]

## Step 7 · Frame it as eras, and close

> "Flash was created during the PC era – for PCs and mice." [FLASH10]

> "New open standards created in the mobile era, such as HTML5, will win on mobile devices (and PCs too)."
> [FLASH10]

> "Perhaps Adobe should focus more on creating great HTML5 tools for the future, and less on criticizing Apple
> for leaving the past behind." [FLASH10]

## What he said about it six weeks later (D8, June 2010)

Context from the D8 liveblog [D8-10], which mixes quotes and paraphrase. These lines are in quotation marks in
the liveblog, but they are a reporter's live notes, not a transcript:

> "We didn't set out to have a war over Flash. We made a technical decision." [D8-10, 6:31 pm, liveblog]

> "We don't think Flash makes a great product, so we're leaving it out." [D8-10, 6:32 pm, liveblog]

> "Apple is a company that doesn't have the most resources in the world, and they [sic: the] way we've
> succeeded is to bet the right technological horse, to look at technologies that have a future." [D8-10,
> 6:23 pm, liveblog]

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

**Use it now:** `templates/01-the-say-no-list.md` (the platform section) and `SKILL.md` Step 4.

**Checks to run:**
1. Which third-party layer in your product could hold back your next improvement?
2. Can you give six checkable reasons for your hardest current "no"? Which is the most important?
3. What do your customers lose, and what's their alternative today?
4. Where are you proprietary out of habit, and where does owning it actually make the experience?
