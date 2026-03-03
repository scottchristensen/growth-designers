# How to Get Synthetic User Feedback Without Recruiting a Single Participant

AI-generated user feedback is here. You can use a vendor tool or DIY if you're technical. We tried both.

---

Dear Readers,

Last month we covered [7 cheap(er) user testing tools](https://growth-designers.beehiiv.com/p/7-cheaper-user-testing-tools-for-lean-growth-teams) for lean growth teams. But what if you could skip recruitment entirely?

That's not a hypothetical anymore. A growing wave of tools and techniques now let you simulate user feedback using AI. Think synthetic personas that walk through your product, give stream-of-consciousness reactions, and surface issues you'd normally need a research panel to catch.

We're not saying this replaces real human research (more on that later). But for quick validation, spot-checking your thinking, and catching details before you spend cycles on a full study? It's remarkably useful.

This month we're featuring community member Travisse Hansen, who built his own synthetic user feedback setup using Claude Code. We'll walk through how he did it, look at the broader ecosystem of tools emerging in this space, and then share what happened when we pointed one of these tools at our own site.

~ Scott Christensen, GrowthDesigners.co Co-Lead

---

## DIY With Claude Code (Featuring Travisse Hansen)

Travisse Hansen is the Head of Product and Product Marketing at Boostly and runs [ClaudeFluent](https://www.claudefluent.com/), a live virtual class on getting the most out of Claude. He built an open-source synthetic user feedback skill for Claude Code that you can run from an IDE or terminal. [Watch his full walkthrough here.](https://www.tella.tv/video/synthetic-user-feedback-scale-for-cloud-code-ax7t)

### How it works

You define personas (an entrepreneur, a product manager, a direct-to-product marketer, a customer success leader, etc.) and point them at any product or page. Claude assumes each persona, navigates the experience, and gives you two layers of feedback:

1. **Stream of consciousness simulation.** Real-time reactions as the persona moves through the product. Travisse found this surprisingly useful for putting yourself in the headspace of different user types.
2. **Summary feedback.** A structured recap of observations, friction points, and impressions for each persona.

Results compile into a document automatically, dropped into your `docs` folder or a new `user research` folder.

### Getting started

1. **Install the skill.** Tell Claude to install it directly. Just say "please install the skill" with the skill file loaded.
2. **Set up your personas.** The persona section starts empty or with a template. Fill it in with your own users or point it at your existing personas.
3. **Run it.** Start a Claude session (ideally with the Chrome extension active for deeper interaction) and type something like `run synthetic feedback against [your product]`.

About a 5-minute setup.

### Where Travisse found it most useful

At Boostly, the team ran synthetic feedback against a pricing revamp and a new website:

- **Pricing visibility skepticism.** The synthetic personas flagged that pricing wasn't visible by default, creating user skepticism before they even engaged.
- **Missing enterprise discounts.** Even though Boostly furnishes discounts for larger organizations, they weren't listed anywhere. The personas noticed.
- **Quick validation loops.** Instead of waiting for a research cycle, Travisse could spot-check changes in minutes. "100 times faster than gathering the same personas live."

As Travisse put it: "I found this tremendously useful for quick validation and spot checking your thinking."

---

## The Broader Market: Who Else Is Building This?

Travisse's approach is DIY, but there's a growing ecosystem of vendor tools if you'd rather not build it yourself. The space is early but capital is flowing fast. Over $200M in funding rounds in the last few months alone.

**Synthetic UX research.** Tools that simulate users against your actual product flows: [Synthetic Users](https://www.syntheticusers.com/), [Uxia](https://www.uxia.app/) (€1M pre-seed), and [Blok](https://www.joinblok.co/) ($7.5M seed).

**Digital twins & synthetic audiences.** Simulated panels for market research and consumer insights: [Electric Twin](https://www.electrictwin.com/) ($14M raised), [Simile](https://simile.ai/) ($100M Series A), and [Ditto](https://askditto.io/) (census-grounded personas).

**AI-moderated research.** Real human participants, but AI runs the interviews and synthesis: [Listen Labs](https://listenlabs.ai/) ($69M Series B) and [Outset](https://outset.ai/) ($30M Series B).

**Incumbents consolidating.** UserTesting acquired User Interviews in January 2026. Qualtrics announced a $6.75B deal with Press Ganey. The big platforms are racing to embed AI and lock in distribution.

---

## We Tried It on Ourselves

We'll be honest, our website at growthdesigners.co has had a layer of dust on it for a bit. So we figured we should eat our own cooking.

We ran [Reforge's Synthetic User Testing](https://build.reforge.com/?utm_source=growthdesigners) (they offer a trial run to get your feet wet) against growthdesigners.co. We simulated a first-time visitor who's new to growth design and wants to learn more and join the community. 12 sessions, 3 devices, done in 3 minutes, 60 insights generated.

We were pretty shocked at how good the recommendations were. The synthetic users flagged that we never define "growth design" above the fold, that our Slack join flow feels unnecessarily gated, that our newsletter subscribe form gives zero context on what you're signing up for, and that our School page buries pricing and curriculum below multiple CTAs. All fair. All things we're now actively fixing.

3 minutes, zero recruitment, and a real prioritized punch list. If nothing else, it's a great way to catch the obvious stuff before investing in a deeper study.

---

## So… Should You Actually Use This?

Here's our honest take, consistent with how we've always approached new tools in this newsletter:

**Great fits for synthetic user feedback:**
- Early concept testing and rapid iteration before committing to a full study
- Spot-checking pricing pages, onboarding flows, and landing pages
- Generating hypotheses about where friction exists
- Edge-case behavior simulation across different persona types
- "Testing the test," or refining interview guides before fielding with real people

**Not a replacement for:**
- Deep UX empathy and understanding complex human motivation
- Decisions that require accurate population estimates
- Sensitive domains where model bias or lack of lived experience can mislead
- Validating findings that will drive major product bets

Nielsen Norman Group frames it well: synthetic users can accelerate early ideation and help generate hypotheses faster, but shouldn't wholly replace real human research. The emerging consensus across the industry is a hybrid approach: use synthetic for speed and breadth early, then reserve human research for ground truth and nuance when the decision is expensive or irreversible.

**Growth is hard. Pushing metrics is hard.** But the barrier to getting directional user feedback just got a lot lower.

---

## Try It Yourself

- [Watch Travisse's walkthrough video](https://www.tella.tv/video/synthetic-user-feedback-scale-for-cloud-code-ax7t)
- [Check out ClaudeFluent](https://www.claudefluent.com/), Travisse's live virtual class on getting the most out of Claude
- [Explore what's available on Reforge](https://build.reforge.com/?utm_source=growthdesigners)

---

## Growth Design School is Now On Demand

Growth Design School is our community-created program that provides a unique blend of fully-remote learning, including 5 hours of video content, case studies, customized assignments, collaborative debriefs, and more!

We switched from a live cohort to a fully on demand model which drops the price from $950 to $290 to make this more accessible to all.

[Learn More](https://www.growthdesigners.co/school)

---

👯 Invite a friend to the [Slack community](https://www.growthdesigners.co/community). We've revamped the community landing page and application process to have more auto approvals.

[Join Slack Community](https://www.growthdesigners.co/community)
