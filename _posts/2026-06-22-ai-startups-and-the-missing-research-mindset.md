---
title: "AI Research and the Patience Problem"
excerpt: "We call it an AI revolution. But the slice of it that actually moves the frontier? That's a much smaller room than anyone admits."
layout: single
author_profile: true
read_time: true
comments: true
share: true
related: true
date: 2026-06-22
categories: blog personal
---

Thanks to my internship, I got to sit in on a bunch of seminars by researchers on their latest discoveries and advances in the Artificial Intelligence world. That, coupled further with several loose conversations I had with friends and acquaintances—people both in the corporate field watching this whole "AI boom" unfold, and spectators like myself—made me notice a sharp line that a lot of people are perhaps missing in this entire field: real AI research is quietly consolidating into the hands of a tiny few, while almost everyone else caught up in this "boom" is, structurally, left standing outside that room.

I should put in the customary disclaimer here—I am just an aspiring AI researcher in a very niche domain within it, and don't claim to have the deepest technical authority on this subject: I am, after all, just an engineering student perpetually behind on his own coursework (final year project included). But this is a blog where I dump my opinions for my own archiving, so here's one I've been sitting on for a bit: a lot of what gets called "AI research" today is happening at wildly different scales of access—and the gap between who has the resources to actually push the frontier and who doesn't is a lot starker than I think most people, myself included until recently, give it credit for.

One thing I want to be careful about upfront: "AI research" is a genuinely wide tent. There's ML for Science—using models to accelerate drug discovery, protein folding, climate simulation—where academia is doing some of the most exciting work in the world. There's AI safety and alignment research, AI for robotics, computer vision, NLP at modest scales, reinforcement learning, and a dozen other subfields where a well-resourced university lab or a small focused team can absolutely sit at the frontier. The picture is not uniformly bleak. What I'm specifically talking about in this post is a narrower subset: large-scale foundation model training—the kind of research aimed at building or fundamentally advancing the base models that everything else is increasingly built on top of. That particular slice of AI research has an almost absurdly high compute floor, and it's that floor that's quietly turning into a wall.

# Three Tiers, Not Two

The clearest way I can put what I noticed is this: the AI world right now seems to be splitting into three tiers, and only one of them is actually positioned to let an idea "rejuvenate"—my word for that slow, unglamorous process of an idea sitting, failing a few times, getting revisited, and eventually paying off months or years later.

Tier one is the handful of big conglomerates: the ones with both the GPU scale and—crucially—the patience that comes from deep enough pockets and a long enough runway to fund work that doesn't need to show a return next quarter.

Tier two is academia: patience in abundance—it's practically the institutional culture, the whole point of a PhD is sitting with a hard problem for years—but the GPU scale just isn't there, and arguably never will be at the same order of magnitude as tier one.

Tier three is startups: and here's the thing, it's not that they're doing anything wrong—it's that they mostly have neither of the two ingredients. Most are renting compute by the API call rather than owning anything close to a training-scale cluster, and their time horizon isn't set by curiosity, it's set by the people funding them: investors who want to see return on time invested, PR cycles that need a launch to point to, a runway that doesn't extend far enough to let an idea sit quietly for a year. None of that is a character flaw—it's just what the incentive structure around a startup looks like, and it leaves very little room for "let's see where this goes."

# Why Real Research Is Becoming a Closed Door

Here's the quintessential engineer's question I kept circling back to while thinking about all this: if startups aren't where the frontier research happens, then who's left to do it?

The honest answer, for this specific subset, is depressingly short: a handful of conglomerates, and that's about it. Unlike most other fields of inquiry—physics, chemistry, even a good chunk of mathematics—where a sufficiently brilliant person with a notebook, a library, and maybe a modest lab can still meaningfully contribute, frontier foundation model research today needs an obscene amount of compute. We're talking training clusters that cost more than most university departments' entire annual budgets, datasets scraped and curated at a scale only a handful of companies can afford to assemble, and infrastructure teams just to keep the lights on for a single training run. A PhD student with a brilliant idea and zero compute access is, for the purposes of this kind of AI research, functionally locked out of the room.
---
title: "AI Research, GPUs, and the Patience Problem"
excerpt: "On why only a tiny handful of companies can currently afford to do real AI research"
layout: single
author_profile: true
read_time: true
comments: true
share: true
related: true
date: 2026-06-22
categories: blog personal
---

Thanks to my internship, I got to sit in on a bunch of seminars by researchers on their latest discoveries and advances in the Artificial Intelligence world. That, coupled further with several loose conversations I had with friends and acquaintances—people both in the corporate field watching this whole "AI boom" unfold, and spectators like myself—made me notice a sharp line that a lot of people are perhaps missing in this entire field: real AI research is quietly consolidating into the hands of a tiny few, while almost everyone else caught up in this "boom" is, structurally, left standing outside that room.

I should put in the customary disclaimer here—I am just an aspiring AI researcher in a very niche domain within it, and don't claim to have the deepest technical authority on this subject: I am, after all, just an engineering student perpetually behind on his own coursework (final year project included). But this is a blog where I dump my opinions for my own archiving, so here's one I've been sitting on for a bit: a lot of what gets called "AI research" today is happening at wildly different scales of access—and the gap between who has the resources to actually push the frontier and who doesn't is a lot starker than I think most people, myself included until recently, give it credit for.

# Three Tiers, Not Two

The clearest way I can put what I noticed is this: the AI world right now seems to be splitting into three tiers, and only one of them is actually positioned to let an idea "rejuvenate"—my word for that slow, unglamorous process of an idea sitting, failing a few times, getting revisited, and eventually paying off months or years later.

Tier one is the handful of big conglomerates: the ones with both the GPU scale and—crucially—the patience that comes from deep enough pockets and a long enough runway to fund work that doesn't need to show a return next quarter.

Tier two is academia: patience in abundance—it's practically the institutional culture, the whole point of a PhD is sitting with a hard problem for years—but the GPU scale just isn't there, and arguably never will be at the same order of magnitude as tier one.

Tier three is startups: and here's the thing, it's not that they're doing anything wrong—it's that they mostly have neither of the two ingredients. Most are renting compute by the API call rather than owning anything close to a training-scale cluster, and their time horizon isn't set by curiosity, it's set by the people funding them: investors who want to see return on time invested, PR cycles that need a launch to point to, a runway that doesn't extend far enough to let an idea sit quietly for a year. None of that is a character flaw—it's just what the incentive structure around a startup looks like, and it leaves very little room for "let's see where this goes."

# Why Real Research Is Becoming a Closed Door

Here's the quintessential engineer's question I kept circling back to while thinking about all this: if startups aren't where the frontier research happens, then who's left to do it?

The honest answer is depressingly short: a handful of conglomerates, and that's about it. Unlike most other fields of inquiry—physics, chemistry, even a good chunk of mathematics—where a sufficiently brilliant person with a notebook, a library, and maybe a modest lab can still meaningfully contribute, frontier AI research today needs an obscene amount of compute. We're talking GPU clusters that cost more than most university departments' entire annual budgets, datasets scraped and curated at a scale only a handful of companies can afford to assemble, and infrastructure teams just to keep the lights on for a single training run. A PhD student with a brilliant idea and zero compute access is, for the purposes of frontier AI, functionally locked out of the room.

This is, I think, a genuinely new problem in the history of science. Academia has always managed to stay relevant at the cutting edge of most disciplines, even when underfunded relative to industry, because the barrier to entry for a good idea was usually intellectual, not financial. With AI, that's flipped: the bottleneck isn't the idea, it's the compute bill behind testing it at scale. And that bottleneck is owned by very, very few people.

# The Time-Invested Problem

Even setting GPUs aside for a second, there's a second, quieter reason tier three struggles to do research: research and "return on time invested" are almost opposite ways of measuring work.

A founder's clock is set by things like the next funding round, a PR cycle that needs a launch to point to, an investor update that needs a number to show progress. Research doesn't work on that rhythm at all. Sometimes you spend three weeks running an experiment that tells you nothing except "this particular approach doesn't work," and the actual insight—the thing worth anything—shows up unannounced, months later, often as a side effect of something else entirely. That kind of meandering, low-visibility-for-long-stretches process is exactly what gets squeezed out the moment a roadmap and a fundraising deadline enter the room. Again, I don't think this is anyone's fault—I'd probably make the same calls in their shoes, given what they're being measured on. It's just a mismatch between what research needs and what a startup's clock is built to optimise for.

## Putting the Three Together

So here's where the threads tie together, in my opinion, into a fairly uncomfortable conclusion:

1. Academia has the patience for research but not the GPU scale to compete at the frontier.
2. Startups have neither the GPU scale nor the patience—not because anyone there is uncurious, but because what they're funded and measured on doesn't leave room for either.
3. That leaves a tiny handful of big companies sitting at the only intersection of "can afford the compute" and "can afford to wait"—and they end up, almost by default, owning the most consequential research happening in the field right now.

Put plainly: this is basically a mess. Not because any one player is doing something wrong, but because the entire system has quietly arranged itself so that only the biggest companies can actually afford the best of research—everyone else, academia included, is left building on top of whatever that small set of conglomerates eventually hands down.

# Devil's Advocate: Is This Just a Hierarchy of Blame?

Now, let me play devil's advocate against myself for a second, because I don't want this to read as "startups are the weak link"—that's not the point I'm trying to make, and it would be a fairly shallow one if I were.

Usefulness and fundamental research are just not the same axis, and a startup not doing frontier research is no more a failing than a hospital not doing fundamental physics—it's simply not what they're built for. A well-built product wrapped around an existing model can still change how an entire industry operates, even if it adds zero new lines to the underlying science. So this isn't "startups bad, conglomerates good." It's closer to: very few players in this ecosystem are even structurally capable of frontier research right now, and that's worth sitting with, regardless of how you feel about any individual company in the other two tiers.

# Where I Land

I think the AI world right now is full of motion, but I'm increasingly convinced not all of it sits at the same level. Academia is patient but compute-starved. Startups are fast but built around a clock that has no room for letting an idea rejuvenate. And the actual frontier keeps narrowing down to whoever can afford both the GPUs and the wait—which, right now, is a genuinely small list of names.

Maybe that's just where this particular field is, for now—a mess, in the sense that the resources required to do the deepest work are concentrated in very few hands, regardless of how much talent or curiosity exists everywhere else. I don't have a neat solution to offer here; I just think it's a divide worth naming clearly, instead of pretending every "AI company" is playing the same game.

This is, I think, a genuinely new problem in the history of science. Academia has always managed to stay relevant at the cutting edge of most disciplines, even when underfunded relative to industry, because the barrier to entry for a good idea was usually intellectual, not financial. With AI, that's flipped: the bottleneck isn't the idea, it's the compute bill behind testing it at scale. And that bottleneck is owned by very, very few people.

# The Time-Invested Problem

Even setting GPUs aside for a second, there's a second, quieter reason tier three struggles to do research: research and "return on time invested" are almost opposite ways of measuring work.

A founder's clock is set by things like the next funding round, a PR cycle that needs a launch to point to, an investor update that needs a number to show progress. Research doesn't work on that rhythm at all. Sometimes you spend three weeks running an experiment that tells you nothing except "this particular approach doesn't work," and the actual insight—the thing worth anything—shows up unannounced, months later, often as a side effect of something else entirely. And more often than people like to admit, it shows up at 3am: you've been stuck for days, visibly unproductive by any external measure, and then something clicks in the middle of the night and you implement the whole thing before you lose the thread—and that's the breakthrough. That kind of cycle, where the "inefficient" days are not wasted time but the actual substrate the insight grows out of, is precisely what a corporate environment has no patience for. The instinct there is to fill the dead time with something legible: ship a feature, push an update, show movement. Which is entirely rational given what they're being measured on—it just means the conditions that produce genuine research keep getting quietly optimised away. That meandering, low-visibility-for-long-stretches process is exactly what gets squeezed out the moment a roadmap and a fundraising deadline enter the room. Again, I don't think this is anyone's fault—I'd probably make the same calls in their shoes. It's just a mismatch between what research needs and what a startup's clock is built to optimise for.

## Putting the Three Together

So here's where the threads tie together, in my opinion, into a fairly uncomfortable conclusion:

1. Academia has the patience for research but not the GPU scale to compete at the frontier.
2. Startups have neither the GPU scale nor the patience—not because anyone there is uncurious, but because what they're funded and measured on doesn't leave room for either.
3. That leaves a tiny handful of big companies sitting at the only intersection of "can afford the compute" and "can afford to wait"—and they end up, almost by default, owning the most consequential research happening in the field right now.

Put plainly: this is basically a mess. Not because any one player is doing something wrong, but because the entire system has quietly arranged itself so that only the biggest companies can actually afford the best of research—everyone else, academia included, is left building on top of whatever that small set of conglomerates eventually hands down.

# Devil's Advocate: Is This Just a Hierarchy of Blame?

Now, let me play devil's advocate against myself for a second, because I don't want this to read as "startups are the weak link"—that's not the point I'm trying to make, and it would be a fairly shallow one if I were.

Usefulness and fundamental research are just not the same axis, and a startup not doing frontier research is no more a failing than a hospital not doing fundamental physics—it's simply not what they're built for. A well-built product wrapped around an existing model can still change how an entire industry operates, even if it adds zero new lines to the underlying science. So this isn't "startups bad, conglomerates good." It's closer to: very few players in this ecosystem are even structurally capable of frontier research right now, and that's worth sitting with, regardless of how you feel about any individual company in the other two tiers.

# Where I Land

I think the AI world right now is full of motion, and genuinely a lot of it is remarkable—ML for science is producing results that would have seemed like science fiction five years ago, and there's real frontier work happening across a wide range of subfields that doesn't require a supercomputer cluster. But for the specific slice I've been talking about—the large-scale foundation model research that increasingly sets the ceiling for everything else—I'm increasingly convinced the room is a lot smaller than the noise of the boom suggests. Academia is patient but compute-starved. Startups are fast but built around a clock that has no room for letting an idea rejuvenate. And the actual frontier of that particular game keeps narrowing down to whoever can afford both the compute and the wait—which, right now, is a genuinely small list of names.

Maybe that's just where this particular field is, for now—a mess, in the sense that the resources required to do the deepest work are concentrated in very few hands, regardless of how much talent or curiosity exists everywhere else. I don't have a neat solution to offer here; I just think it's a divide worth naming clearly, instead of pretending every "AI company" is playing the same game.

Do leave me a text if you liked this one :)

---

### References / Further Reading

A few things I read around this topic that shaped (and back up) a lot of what's in this piece:

- Nature — ["AI's computing gap: academics lack access to powerful chips needed for research"](https://www.nature.com/articles/d41586-024-03792-6)
- ["The Compute Divide in Machine Learning: A Threat to Academic Contribution and Scrutiny?"](https://arxiv.org/abs/2401.02452) — arXiv
- VentureBeat — ["AI research finds a 'compute divide' concentrates power and accelerates inequality in the era of deep learning"](https://venturebeat.com/ai/ai-research-finds-a-compute-divide-concentrates-power-and-accelerates-inequality-in-the-era-of-deep-learning)
- Stanford HAI — ["Expanding Academia's Role in Public Sector AI"](https://hai.stanford.edu/policy/expanding-academias-role-in-public-sector-ai)
- ["The De-democratization of AI: Deep Learning and the Compute Divide in Artificial Intelligence Research"](https://arxiv.org/abs/2010.15581) — arXiv
- TIME — ["The U.S. Just Made a Crucial Step Toward Democratizing AI Access"](https://time.com/6589134/nairr-ai-resource-access/), on the NAIRR pilot
