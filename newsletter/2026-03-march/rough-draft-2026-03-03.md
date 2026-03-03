# How to Get Synthetic User Feedback Without Recruiting a Single Participant

AI-generated user feedback is here. Here's how one growth leader set it up in 5 minutes — and what the emerging ecosystem looks like for lean teams.

---

Dear Readers,

Last month we covered [7 cheap(er) user testing tools](https://growth-designers.beehiiv.com/p/7-cheaper-user-testing-tools-for-lean-growth-teams) for lean growth teams. But what if you could skip recruitment entirely?

That's not a hypothetical anymore. A growing wave of tools and techniques now let you simulate user feedback using AI — synthetic personas that walk through your product, give stream-of-consciousness reactions, and surface issues you'd normally need a research panel to catch.

We're not saying this replaces real human research (more on that later). But for quick validation, spot-checking your thinking, and catching details before you spend cycles on a full study? It's remarkably useful.

This month, we're featuring community member Travisse Hansen, who built an open-source synthetic user feedback skill for Claude Code and has been using it to pressure-test everything from pricing pages to onboarding flows.

~ Scott Christensen, GrowthDesigners.co Co-Lead

---

## Meet Travisse Hansen

Travisse Hansen is the Head of Product and Product Marketing at Boostly and runs [ClaudeFluent](https://www.claudefluent.com/), a live virtual class teaching people how to get the most out of Claude. He's also an active builder in the Claude Code community, where he published a public repo for synthetic user feedback that caught our attention.

We asked Travisse to walk us through how he set it up and how he's been using it. [Watch his full walkthrough here.](https://www.tella.tv/video/synthetic-user-feedback-scale-for-cloud-code-ax7t)

---

## How It Works

Travisse built a skill for Claude Code that lets you define personas — like an entrepreneur, a product manager, a direct-to-product marketer, or a customer success leader — and then point them at any product or page. Claude assumes each persona, navigates through the experience, and provides two layers of feedback:

1. **Stream of consciousness simulation** — real-time reactions as the persona moves through the product. Travisse found this surprisingly useful for putting yourself in the headspace of different user types.
2. **Summary feedback** — a structured recap of observations, friction points, and impressions for each persona.

The results get compiled into a document automatically. If you have a `docs` folder, it drops it there. Otherwise, it creates a `user research` folder for you.

## Getting Started

Setting it up is straightforward:

1. **Install the skill.** You can tell Claude to install it directly — just say "please install the skill" with the skill file loaded.
2. **Set up your personas.** When you download the skill, the persona section will either be empty or contain a template. Fill it in with your own users or modify the skill to point at your existing personas.
3. **Run it.** Start a Claude session (ideally with the Chrome extension active for deeper interaction — clicking into profiles, logging into products, etc.) and type something like `run synthetic feedback against [your product]`.

That's it. Travisse described the whole process as about a 5-minute setup.

## Where Travisse Found It Most Useful

At Boostly, the team has been working on a pricing revamp and a new website. Travisse ran synthetic feedback against both and caught details he wouldn't have found otherwise — or that would have taken extensive in-person user research to surface:

- **Pricing visibility skepticism.** The synthetic personas flagged that pricing wasn't visible by default, creating user skepticism before they even engaged.
- **Missing enterprise discounts.** Even though Boostly furnishes discounts for larger organizations, they weren't listed anywhere. The personas noticed.
- **Quick validation loops.** Instead of waiting for a research cycle, Travisse could spot-check changes in minutes — "100 times faster than gathering the same personas live."

As Travisse put it: "I found this tremendously useful for quick validation and spot checking your thinking."

---

## The Bigger Picture: Synthetic Research Is an Emerging Ecosystem

Travisse's skill is a DIY approach, but there's a growing wave of startups building dedicated synthetic user research products. The space is early but moving fast.

### Dedicated Synthetic UX Research Tools

These startups simulate users against product flows — interviews, usability tests, and feedback sessions without recruiting real humans:

- **[Synthetic Users](https://www.syntheticusers.com/)** — AI-driven synthetic participants with distinct personality profiles for qualitative research, interviews, and UX feedback.
- **[Uxia](https://www.uxia.app/)** — Barcelona-based startup using AI-generated synthetic testers to automate usability feedback. Recently closed a €1M pre-seed round.
- **[Blok](https://www.joinblok.co/)** — Simulation environment that generates AI "virtual users modeled off actual product behavior" to stress-test onboarding and compare variants pre-launch. Raised a $7.5M seed round.

### Market Research Digital Twins

A parallel wave of companies is building "synthetic audiences" for broader market and consumer research:

- **[Electric Twin](https://www.electrictwin.com/)** — Synthetic audiences combining LLMs with social science research. Raised $14M total including a $10M round in February 2026.
- **[Simile](https://simile.ai/)** — High-fidelity digital twins for enterprise decision simulation. Raised a $100M Series A in February 2026.
- **[Ditto](https://askditto.io/)** — Population-true synthetic persona panels grounded in census data. Toronto-based.

### AI-Moderated Research (Real Humans, AI-Run)

These platforms still recruit real people but automate the interviewing, synthesis, and reporting:

- **[Listen Labs](https://listenlabs.ai/)** — AI interviewer with automated study creation. Raised a $69M Series B in January 2026.
- **[Outset](https://outset.ai/)** — LLM-led interviews positioned as "depth of an interview, scale of a survey." Raised a $30M Series B.

### The Incumbents Are Moving Too

UserTesting acquired User Interviews in January 2026. Qualtrics announced a $6.75B deal with Press Ganey. Traditional platforms are racing to embed AI into the research stack and lock in distribution through proprietary datasets and participant access.

---

## So… Should You Actually Use This?

Here's our honest take, consistent with how we've always approached new tools in this newsletter:

**Great fits for synthetic user feedback:**
- Early concept testing and rapid iteration before committing to a full study
- Spot-checking pricing pages, onboarding flows, and landing pages
- Generating hypotheses about where friction exists
- Edge-case behavior simulation across different persona types
- "Testing the test" — refining interview guides before fielding with real people

**Not a replacement for:**
- Deep UX empathy and understanding complex human motivation
- Decisions that require accurate population estimates
- Sensitive domains where model bias or lack of lived experience can mislead
- Validating findings that will drive major product bets

Nielsen Norman Group frames it well: synthetic users can accelerate early ideation and help generate hypotheses faster, but shouldn't wholly replace real human research. The emerging consensus across the industry is a hybrid approach — use synthetic for speed and breadth early, reserve human research for ground truth and nuance when the decision is expensive or irreversible.

**Growth is hard. Pushing metrics is hard.** But the barrier to getting directional user feedback just got a lot lower.

---

## Try It Yourself

- [Watch Travisse's walkthrough video](https://www.tella.tv/video/synthetic-user-feedback-scale-for-cloud-code-ax7t)
- [Check out ClaudeFluent](https://www.claudefluent.com/) — Travisse's live virtual class on getting the most out of Claude
- [Explore what's available on Reforge](https://build.reforge.com/?utm_source=growthdesigners)

---

## Growth Design School is Now On Demand

Growth Design School is our community-created program that provides a unique blend of fully-remote learning, including 5 hours of video content, case studies, customized assignments, collaborative debriefs, and more!

We switched from a live cohort to a fully on demand model which drops the price from $950 to $290 to make this more accessible to all.

[Learn More](https://www.growthdesigners.co/school)

---

👯 Invite a friend to the [Slack community](https://www.growthdesigners.co/community). We've revamped the community landing page and application process to have more auto approvals.

[Join Slack Community](https://www.growthdesigners.co/community)
