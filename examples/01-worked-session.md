# Worked example: a product review of "Brightwell"

> **Fictional.** Brightwell, its people and every number below are invented to show how the skill works.
> Nothing here is a claim about any real company. Quotes from Steve Jobs are real and cited.

## What the founder sent

```text
Run Steve Jobs' product review on my company.

What we make: Brightwell sells home air-quality monitors with an app and a subscription.
Who it's for: parents of young kids, mostly in apartments.
Everything we're working on:
  - 3 monitors: Brightwell Mini ($79), Brightwell ($149), Brightwell Pro ($249)
  - a plug-in purifier ($199), launched 4 months ago
  - 3 subscription plans: Basic, Plus, Family
  - an Android app, an iOS app, a web dashboard, and a "landlord portal" for one pilot customer
  - an open API and a Home Assistant integration
  - a smart-thermostat partnership (prototype)
  - a B2B version for daycare centres (2 pilots)
The one experience: a parent looks at the app and knows if the air in the nursery is OK.
What they hate today: other monitors show 9 numbers and nobody knows what they mean.
Team: 24 people. Our 3 best engineers are split across 6 projects.
What we want customers to know: we make the air at home safe for your kids.
Hardest decision: whether to keep building our own app or white-label a partner's.
```

## What the skill returned

### Keep four

Everything on the list: 15 items. Leaving out the two phone apps (platforms, covered below), that's 13
products, plans and projects. The two questions that split their customers: **do they want to know, or
want it fixed?** and **one room, or the whole home?** At most one thing per cell, as in
the Macintosh grid [MSW-speech-macworld-1998].

| # | Keep | Grid cell | A-team owner | Why it's one of four |
|---|---|---|---|---|
| 1 | Brightwell monitor (merge Mini and standard into one, $119) | Know · one room | Engineer A | The core experience; most customers start here |
| 2 | Brightwell Pro | Know · whole home | Engineer B | Multi-room families, highest margin |
| 3 | The purifier, linked to the monitor | Fix · one room | Engineer C | Turns "the air is bad" into "the air is fixed" |
| 4 | One subscription (Family), included free for year one | Fix · whole home | Product lead | Alerts and history across rooms |

"And as a matter of fact, if we only had four, we could put the A team on every single one of them."
[MSW-speech-macworld-1998] The three best engineers had been on six projects. Now each owns one product.

### Say no

| Product / feature / project | Merge, hide or kill | Who's told, by whom, when |
|---|---|---|
| Brightwell Mini | Merge into the standard monitor | Customers on the website and by email, founder, at launch |
| Basic and Plus plans | Kill; existing subscribers moved to Family at their current price | Each subscriber by email, founder, 60 days ahead |
| Landlord portal | Kill | The pilot customer, by phone, founder, this week |
| Daycare B2B version | Pause for 12 months | Both pilots, by phone, founder, this week |
| Thermostat partnership | Stop | Partner, CEO to CEO, this week |
| Web dashboard | Hide (keep for existing users, no new features) | In-app note, product lead |
| Open API, Home Assistant integration | Keep the API frozen; no new endpoints | Developer forum post, CTO |

- Share of the list merged, killed, hidden or frozen: 9 of 13 (69 percent). He cut about 70 percent of
  Apple's roadmap in 1997 [MSW-speech-apple-1997]. **Our reading:** the number is a check, not a target.
- Platforms: iOS and Android apps, plus the web dashboard, plus firmware: four stacks. He doubted most
  companies could manage more than two [WWDC97 61:16 to 62:12] (machine transcript of the archive.org
  recording, made for this repo; check wording against the video). Hiding the dashboard takes it to three.

The founder wanted to keep the daycare pilots because they were interesting. "Microcosmically, they might
have made sense. ... Macrocosmically, they made no sense." [WWDC97 05:49 to 05:52]

### Customer experience first

- **The printout:** one card on the lock screen: *Nursery: air is good* (green), or *Nursery: open a window,
  or turn on the purifier* (amber). "Because you don't have to know anything about what's in that box."
  [WWDC97 53:51]
- **What they hate today:** nine numbers (PM2.5, CO2, VOCs and so on) and no answer. "They don't know how to use
  even 10 percent of the features" was his line about phones [MSW-speech-apple-2007]. The nine numbers move to
  a details screen.
- **First five minutes:** plug in, scan one code, name the room, see the card. Today it takes 14 steps and
  about 11 minutes (invented). Target: 4 steps, under 2 minutes.
- **Own end to end:** the sensor calibration, the card and the alert logic. That's the experience.
- **Partner or buy:** cloud hosting, push notifications, payments.

### Simplify

- Remove: the 9-number home screen, 3 of 5 settings tabs, the separate purifier app.
- Where they're going for best when better would ship: a custom chip for the Pro (18 months, invented).
  An off-the-shelf sensor gets 90 percent of the accuracy this year. "I'm not always wise enough to know when to
  go for the best and when to just go for better." [MSW-interview-company-of-giants]

### The hardest decision: build the app, or white-label?

Run as a platform call (chapter 11). A partner's app would sit between Brightwell and its customers and set
the pace of every new feature: "We cannot be at the mercy of a third party deciding if and when they will make
our enhancements available to our developers." [FLASH10] The app *is* the card, so they keep it.
**Our reading:** this is the 10 to 30 percent you own [WWDC97 11:30]. The rest (hosting, payments) they buy.

### People

- Gaps: no A player on firmware since the lead left in March (invented). Hire before anything else.
- Founder hours on recruiting last month: 6. He said he spent "20 percent of my time recruiting"
  [MSW-interview-company-of-giants]. Target for the founder: one day a week until firmware is filled.

### Message and reason for being

- **What we want them to know:** *you'll always know if the air your kids breathe is OK, and you can fix it.*
  It's about the parent, not the sensor ("not to talk about speeds and feeds" [MSW-speech-apple-1997]).
- **Reason for being** (draft 5 of 5): *Brightwell makes the air in your home something you can see and fix,
  so parents can stop worrying about what their kids are breathing.* All four products fit it. The daycare
  version didn't, which confirmed the pause.

### Decisions

| Decision | Reversible? | Decide by | Owner |
|---|---|---|---|
| Merge Mini into the standard monitor | Yes (pricing can change) | This week | Founder |
| Kill Basic and Plus | Hard (subscriber trust) | After calling 20 subscribers | Product lead |
| Keep building the app | Hard (18 months of work) | Decided | CTO |
| Off-the-shelf sensor for Pro | Yes for this model | This week | Engineer B |

### This month

1. Ship the four-step setup and the lock-screen card to new customers. Owner: engineer A.
   [WWDC97 52:06]
2. Send the "no" messages: pilots and partner this week, subscribers 60 days ahead. Owner: founder.
   [MSW-email-apple-newton]
3. Open the firmware lead role at the A-player bar. Owner: founder. `templates/03-a-player-hiring-bar.md`

**The test:** put the card in front of 10 parents in their own homes by the end of the month. Pass if 8 can say
what to do without help.

### Where to be careful

- His four-product cut was for computers in 1998. Applying it to a subscription business is our reading.
- The 70 percent is a check from one turnaround, not a rule.
- The cut affects real people: two pilot customers, one partner, and subscribers on the killed plans. The skill
  drafted the messages; the founder should make the calls.

## The result (invented)

Setup time fell from 11 minutes to 90 seconds. Returns in the first 30 days fell from 9 percent to 4 percent.
The firmware lead joined in week seven. The founder said the hardest part was the daycare call.
