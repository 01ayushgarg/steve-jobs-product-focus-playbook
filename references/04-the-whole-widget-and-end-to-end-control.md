# 04 · The whole widget, and end-to-end control

> "I've always wanted to own and control the primary technology in everything we do." [BW04, 12 Oct 2004]

## What he said

**Own the primary technology (2004 and 2008).** In 2004 he said the primary technology in music players had
once been the mechanism inside the player, and that Apple bet it was becoming software, which Apple was good
at [BW04]. He was clear that this didn't mean making every part: "Of course, you're never going to invent
everything." [BW04] The iPod's tiny hard drive, he noted, wasn't invented for the iPod and wasn't its primary
technology [BW04]. In 2008 he put it more sharply: Apple didn't want to be in any business where it didn't own
or control the primary technology, "because you'll get your head handed to you." [FORTUNE08 p13]

**Own the whole experience (2008).** "And we think that our job is to take responsibility for the complete user
experience. And if it's not up to par, it's our fault, plain and simply." [FORTUNE08 p4] He gave the MacBook
Air as an example of what owning both the hardware and the operating system allowed [FORTUNE08 p4], and said
owning the operating system meant Apple could set its own priorities instead of waiting years for another
company's release [FORTUNE08 p8].

**Integration is a strength only if managed right (1997).** At WWDC, as an adviser, he said Apple's vertical
integration was seen as a great weakness, and that he saw it as a potential weakness "if not managed right"
and as Apple's "greatest strength if managed right." [WWDC97 19:24 to 19:27] (Machine transcript, made for
this repo; checked against a second transcription.)

**But don't invent what you can use (1997).** The same talk attacked the habit of building everything:
"I think the wisdom here is not to say that we've got to invent everything ourselves." [WWDC97 11:23] He
guessed that the share Apple truly had to invent was a minority of the whole, naming 10, 20 or 30 percent.
(Our two transcriptions differ on the exact words around that figure, so we paraphrase it.) On Apple's
reinvented wheels: "it might be 10% better, but usually it ended up being about 50% worse" [WWDC97 12:08].
And: "this whole notion of being so proprietary in every facet of what we do has really hurt us."
[WWDC97 11:46]

**His own caveat: the whole widget nearly sank NeXT (1995).** In the Smithsonian interview he called NeXT's
hardware strategy a mistake: "we made a mistake which was to try to follow the same formula we did at Apple,
to make the whole widget." The market, the industry and the scale had changed [SI95]. NeXT, he said, should
have been a software company from the start [SI95]. The Archive's timeline dates NeXT's exit from hardware to
February 1993 [MSW-key-events, the Archive's words].

**Partner for the rest (2007).** At D5 he admitted Apple had been bad at partnering because he and Wozniak
started the company "based on doing the whole banana" [D5-07, 30 May 2007]. His example of doing it right was
maps on the first iPhone: "We know how to do the best maps client in the world, but we don't know how to do
the back end so we partner with people that know how to do the back end." [D5-07]

**Why hardware and software together.** He quoted the computer scientist Alan Kay twice, in slightly
different words: "People that love software want to build their own hardware." [D5-07] and "People who are
really serious about software should make their own hardware." [MSW-speech-macworld-2007, 9 Jan 2007] Both are
his recollections of Kay's line.

## How to apply it: own, partner or buy (our suggestion)

1. **Write the experience first** (chapter 02). You can't decide what to own until you know what the
   customer is buying.
2. **Name the primary technology.** Which one capability, if it were worse, would make the experience
   worse? That's the candidate to own. There is usually one, sometimes two.
3. **List everything else.** For each part, ask: if a supplier did this, would the customer notice? If no,
   partner or buy.
4. **Check who sets your pace.** For each partner, ask: can they delay a feature the customer wants? If yes,
   that dependency is a risk (chapter 11).
5. **Check your scale.** Owning more costs more. His NeXT lesson [SI95] is that the whole widget needs the
   volume to pay for it. Write down the volume at which owning a part pays off.
6. **Take responsibility anyway.** Even for parts you buy, the customer blames you. Decide how you'll
   support them (his *it's our fault* [FORTUNE08 p4]).
7. **Revisit yearly.** The primary technology moves. His music-player example moved from mechanism to
   software [BW04].

## A worked scenario (fictional)

A fitness-app startup is deciding whether to build its own heart-rate strap.

- **Experience:** a coach on your phone who changes the workout as you go.
- **Primary technology:** the coaching logic that reacts to heart rate. Own it.
- **Strap:** customers already own straps and watches that report heart rate. Buy compatibility, don't build
  hardware.
- **Pace check:** one watch maker can delay data access by a year. Support two others so no single partner
  sets the pace.
- **Scale check:** a custom strap pays off only above roughly 200,000 units a year (invented). They sell
  20,000. Not now.

**Our reading:** this is the NeXT lesson [SI95] and the maps lesson [D5-07] together: own the part that is
the experience, and don't pay for a whole widget you don't have the scale for.

## Failure modes and limits (our reading)

- **Owning everything out of pride.** His own 1997 critique of Apple: reinvented wheels, *10% better* and
  *50% worse* [WWDC97 12:08].
- **Owning nothing.** If a partner controls the primary technology, they control your roadmap.
- **Ignoring scale.** The same formula worked at Apple and failed at NeXT [SI95].
- **Copying Apple's hardware context.** Most software companies don't need to build hardware. Translate
  *the whole widget* to *the whole experience*, and be explicit that the translation is yours.

**Use it now:** `templates/02-customer-experience-first-spec.md` (the *own, partner or buy* section).

**Checks to run:**
1. What is the primary technology in your product? Do you own it?
2. What are you building yourself that you could use from someone else? Is it 10% better, or 50% worse?
3. Is your scale big enough to pay for doing the whole widget? What would NeXT's 1995 answer be?
4. Which partner could delay your next improvement?
