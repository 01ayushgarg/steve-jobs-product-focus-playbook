# 02 · Start with the customer experience, and work backwards

> "And one of the things I've always found is that you've got to start with the customer experience and work
> backwards to the technology." [WWDC97 52:06, May 1997]

`[WWDC97]` is a machine transcript of the archive.org recording, made for this repo. The WWDC97 lines in this
chapter were checked against a second, larger-model transcription (see `SOURCES.md`).

## What he said

**The rule, and his own scar tissue (May 1997).** A developer at WWDC told him he didn't know what he was
talking about. He agreed the man was right on some details, then explained why the technology had been cut
anyway: "You can't start with the technology and try to figure out where you're going to try to sell it."
[WWDC97 52:22] He added that he had made this mistake "probably more than anybody else in this room"
[WWDC97 52:28]. Apple's new strategy, he said, began from what benefits it could give the customer, not
from an inventory of the technology the engineers had.

**The LaserWriter (told in 1997, about the 1980s).** His example was Apple's first small laser printer. He
listed the parts inside it (a Canon engine, Apple's controller, Adobe's PostScript, AppleTalk networking) and
then said what actually sold it: the first printout. Nobody needed to know what was in the box. Apple could
just hold up the page and ask:

> *do you want this?* [WWDC97 53:54]

"And that's where Apple's got to get back to." [WWDC97 54:05]

**Pixar.** He said the same about films: Pixar wanted to use its technology "to make something where nobody
needed to know anything about the technology to love it." [MSW-on-pixar-early-days, 2003] And from Disney
it learned to decide what the audience will see before spending on it: "you have to edit your film before
you make it." [MSW-interview-about-pixar, 22 Nov 1996]

**The iPhone (2007).** Speaking to employees the day before it went on sale, he said the product hadn't come
from market research or spreadsheets: "It was driven by the fact that we all hated our phones."
[MSW-speech-apple-2007] People, he said, couldn't use "even 10 percent of the features" on their phones
[MSW-speech-apple-2007]. On stage in January he had drawn the problem on two axes, smart and easy to use,
and described the goal as a product "way smarter than any mobile device has ever been and super easy to
use." [MSW-speech-macworld-2007, 9 Jan 2007]

**Build what you want, then check it (2008).** He said iTunes and the iPod were built because the team
wanted them: "the first few hundred customers were us." [FORTUNE08 p2] He was blunt about market research:
"We do no market research." [FORTUNE08 p3] But he didn't stop at the team's taste. In the same answer he
said Apple tries to think through whether many other people will want it too [FORTUNE08 p2].

**What a good experience feels like (2004).** He described a Mac owner getting stuck months after buying,
finding the way through, and thinking: "Wow, someone over there at Apple actually thought of this!"
[BW04, 12 Oct 2004] Then it happens again, months later. That repeated moment, he said, was why customers
were loyal.

**Show, don't convince (2007).** At D5: "it's really great when you show somebody something and you don't
have to convince them they have a problem this solves." [D5-07, 30 May 2007] Earlier, in 1984, on why the
Macintosh had to be easy: "Most people are not going to learn slash-qz's any more than they're going to learn
Morse code." [MSW-on-the-macintosh, 1984] And in 2010, on target segments like young men: "We think about
making a great product for just about everybody." [MSW-on-the-ipad, 2010]

## How to apply it (our suggestion)

1. **Write the printout.** One sentence: the result a customer can see, hold or show someone else. Not a
   feature list.
2. **Write what they hate today.** Watch three customers do the job the current way. List what goes wrong,
   in their words.
3. **Write the first five minutes.** Step by step, as the customer lives them, from opening the box or the
   page to the first result.
4. **Edit before you build.** Cut steps on paper, the way Pixar edits a film before making it. Every step you
   remove now is code you don't write (chapter 03).
5. **Only now, list the technology.** For each step, what does it need? Mark what you must own and what you
   can partner on or buy (chapter 04).
6. **Hold it up.** Put the printout (a mock, a prototype, a real output) in front of five customers and ask
   *do you want this?* [WWDC97 53:54]. Count the yeses.
7. **Look for the second moment.** Plan one thing customers will discover three months in. That's his "they
   thought of that, too" [BW04] moment, and it's what keeps them.

## A worked scenario (fictional)

A team building expense software starts from its OCR engine, which reads receipts at 97 percent accuracy.
Run backwards instead:

- **Printout:** an expense report that is already filled in when the employee opens the app at month end.
- **What they hate:** photographing 30 receipts, typing amounts, chasing a manager for approval.
- **First five minutes:** connect a card, forward one email receipt, see it matched to the card charge.
- **Edit:** the photo step is now optional, so the camera screen moves out of the first five minutes.
- **Technology:** card matching (own it, it is the experience), OCR (keep, but it's now a fallback), email
  parsing (buy).
- **Test:** 5 finance leads see the filled-in report; 4 say they want it (invented numbers).

**Our reading:** the OCR engine was still useful. What changed is that it stopped being the pitch.

## Failure modes and limits (our reading)

- **The we-are-the-customer bias.** "The first few hundred customers were us" [FORTUNE08 p2] worked when the
  team was a fair sample. If you aren't the customer, watch the people who are. He still checked whether
  others would want it.
- **Reading no market research as no customers.** He talked to customers in 1997 to test the product
  line (chapter 01). What he dismissed was asking customers to design the product.
- **A printout nobody can see yet.** For infrastructure or B2B work, the printout may be a report, a speed,
  or a cost. It still has to be something the buyer can look at.
- **Polishing the first five minutes only.** The loyalty he described came months later (BW04). Plan for
  month three as well.

**Use it now:** `templates/02-customer-experience-first-spec.md`.

**Checks to run:**
1. What is the thing a customer can hold up (a printout, a screen, a result) and say *I want this*? Can you
   show it today?
2. Was this project started from a technology you have, or from an experience a customer wants?
3. If your team is the customer, how do you know other people will want it too?
4. Which features would a customer never discover on their own?
5. What will a customer discover three months in that makes them think *they thought of that*?
