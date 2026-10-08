# 03 · Simplicity and taste

> "Some people think design means how it looks. But of course, if you dig deeper, it's really how it works."
> [WIRED96, Feb 1996]

## What he said

**Design is how it works (1995 and 1996).** In the 1996 Wired interview he said the Mac's design was mainly
how it worked, with looks only part of it, and that to design something well you have to understand it
deeply: "chew it up, not just quickly swallow it." [WIRED96] In the 1995 Smithsonian interview he described
NeXT's fit and finish the same way: "I don't just mean in packaging; I mean in terms of operation." [SI95]
His example was soft power: press one button and the machine works out how to shut down safely by itself
[SI95].

**Get simple again (1983 and 1984).** At the 1983 design conference in Aspen, answering a question from the
audience, he said Apple was trying to simplify everything, from the products to the advertising: "we're just
trying to get simple again." [SJA-ASPEN83 clip: Simplicity in design] He said the obvious high-tech look
(black, metallic, busy) was easy to do; the harder goal was to make advanced technology into *simple objects*
[SJA-ASPEN83 clip: Simplicity in design]. A year later, to Michael Moritz: "[At Apple] we're just getting
simpler and simpler and simpler." [MSW-interview-michael-moritz-1984, May 1984]

**Taste is stubbornness, trained by mistakes (1984).** He told Moritz he didn't think his taste was very
different from other people's. The difference: "I just get to be really stubborn about making things as good
as we all know they can be." [MSW-interview-michael-moritz-1984] And: "Your aesthetics get better as you make
mistakes." [MSW-interview-michael-moritz-1984] He trained his eye on things outside computing, from wine
labels and gallery paintings to kitchen appliances: "I went around and looked at Cuisinarts when we were
designing Mac." [MSW-interview-michael-moritz-1984]

**Great costs time, not money (1983 and 1984).**

> "it doesn't take any more energy—and rarely does it take more money—to make it really great. All it takes
> is a little more time." [MSW-interview-michael-moritz-1984]

He had told the Aspen designers the same thing about looks a year earlier [MSW-speech-aspen-1983, 15 Jun
1983].

**The line you never wrote (1997).** At WWDC, on software: "The line of code that's the fastest to write that
never breaks, that doesn't need maintenance, is the line you never had to write." [WWDC97 41:45] And: "It's
all about managing complexity." [WWDC97 25:23] (Machine transcript of the archive.org recording, made for
this repo; both lines were checked against a second transcription.) In 1996 he made a similar claim for
objects: they would let a company build applications with "only about 10 to 20 percent of the software
development required any other way." [WIRED96]

**Editing is the art (2000 and 2007).** At D5: "the art of it is balancing what's on there and what's not on
there" [D5-07, 30 May 2007]. At Pixar's new building in 2000 he described the design going the way a film
does: "First, a treatment; throw it away. Then another; throw it away." [MSW-speech-pixar-2000, Nov 2000]

**The job is making complex things easy (1999).** "It's our job to make complex technology easy to use and
fun to use." [MSW-email-apple-macintosh-fifteen, 24 Jan 1999] In 1998 he said design would matter more, not
less, as prices fell: "design and fashion become even more important." [MSW-speech-macworld-1998]

**His own caveat.** He called himself *too idealistic* at times, and said: "I'm not always wise enough to know
when to go for the best and when to just go for better." [MSW-interview-company-of-giants, 1990s] And:
"Balancing the ideal and the practical is something I still must pay attention to."
[MSW-interview-company-of-giants]

## How to apply it: the editing pass (our suggestion)

1. **Pick one flow.** The one customers use most, usually the core from chapter 02.
2. **Count it.** Steps, screens, settings, fields, words on the first screen. Write the numbers down.
3. **Ask how it works before how it looks.** For each step: what is the customer trying to do
   here, and could the product do it for them, the way soft power did [SI95]?
4. **Remove, then hide, then merge.** Remove what nobody would miss. Hide what few need. Merge what always
   happens together. In that order.
5. **Throw away one draft.** Make a second version from scratch before polishing the first, as Pixar did
   with treatments [MSW-speech-pixar-2000].
6. **Decide best or better, in writing.** For each remaining part: is this one of the few places the
   customer touches most? If yes, go for best and give it time. If no, ship *better*.
7. **Re-count.** Compare with step 2. If the numbers barely moved, the pass didn't happen.

## A worked number (fictional)

A sign-up flow has 9 screens, 14 fields and 6 settings before the first result.

- **Remove:** company size, phone number, referral source (3 fields nobody uses).
- **Hide:** 5 of the 6 settings move to a later screen with sensible defaults.
- **Merge:** name and email on one screen; plan choice moves after the first result.
- **Do it for them:** time zone and currency read from the browser, not asked.
- **Result:** 9 screens to 3, 14 fields to 4, 6 settings to 1 (invented numbers).
- **Best or better:** the first result screen gets *best* (two more weeks). Billing pages get *better* and
  ship now.

## Failure modes and limits (our reading)

- **Simplicity as styling.** A clean screen that hides a confusing flow fails his own test: design is how it
  works [WIRED96].
- **Simplicity by deletion of the core.** Removing the hard part isn't simplifying. The work is making the
  hard part easy.
- **Best everywhere.** He said himself he didn't always know when to stop. Limit *best* to the few places
  customers touch most.
- **Taste by decree.** His claim was that taste is trained by looking and by mistakes. A team that never looks
  outside its own field has nothing to train on.
- **Time is not free.** *A little more time* [MSW-interview-michael-moritz-1984] was his phrase. If the time
  needed is a year, that's a strategy decision, not polish (chapter 08).

**Use it now:** `templates/07-the-editing-pass.md`, then `templates/02-customer-experience-first-spec.md`.

**Checks to run:**
1. What could you remove from the product and nobody would miss it? From the code?
2. Which step could the product do for the customer instead of asking?
3. Where are you going for *best* when *better* would ship this month?
4. When did the team last look closely at something well made outside your industry?
