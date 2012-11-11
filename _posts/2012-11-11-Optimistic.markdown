---
layout: post
title: The Optimistic Programmer
date: 2012-11-12 00:00:00
categories:
- blog
---

This week, a topic that relates strongly to [what I wrote last week.](http://snibble.github.com/blog/2012/11/05/Idea.html) One sure fire way to get a bunch of under-estimates for software tasks is to ask "The Optimistic Programmer" (TOP) how long some development task will take. You know who TOP is, the guy who thinks every problem is an easy problem that he just hasn't taken time to think through yet, that every language and development environment works just as well as his favorite tools, that every requirements document is complete and consistent...basically, the guy who thinks that software development is just a bunch of typing in code to transfer already fully-formed ideas from his head to the processor for simple execution.

The Optimistic Programmer often neglects project complexities that we all know (_even TOP knows if you really sit him down and ask him_) will come up as soon as we move the project from the theoretical to the practical: unmet or wonky external dependencies, tool incompatibilites or inefficiencies, licensing issues, hardware availability, co-workers on vacation, clients who received _approval_ but not _budget_ for their project...

Steve McConnell talks a lot about <a href="http://www.amazon.com/gp/product/B004OR1XXS/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B004OR1XXS&linkCode=as2&tag=snibble-20">taming wild software schedules</a>, and one of the recurring themes he has is about the fine line between optimism and wishful thinking (or Best Case Scenario Mindset from last week). Does either of these scenarios that McConnell offers sound familliar?
>   "None of the team members really believed that they could complete the
>   project according to the schedule they were given, but they thought
>   that maybe if everyone worked hard, and nothing went wrong, and they got
>   a few lucky breaks, they just might be able to pull it off."

>   "Our team hasn't done very much work to coordinate the interfaces among
>   the different parts of the product, but we've all been in good
>   communication about other things, and the interfaces are relatively
>   simple, so it'll probably take only a day or two to shake out the bugs."

Our old friend Kent Beck even calls optimism a _hazard_ in <a href="http://www.amazon.com/gp/product/B000OZ0N5S/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B000OZ0N5S&linkCode=as2&tag=snibble-20">Extreme Programming Explained</a>. How can anyone deal with the realities of project execution when their vision is clouded by irrational optimism? It falls, therefore, on the shoulders of TOP's teammates to help reign him in. (Woe be unto TOP if he winds up on a solo project...)

Of course, we've seen optimism bite us on our own projects, right? My team tracks progress between milestones with a "burndown chart". Every day at standup, I ask around and get estimates for work remaining on all the work items we have on our plate. I take the estimates the team gives and plot them on a time axis against an idealized line between where we start and where we need to be done. Guess what? Even when the data shows us that we're slightly behind the curve, we often convince ourselves that we're on target to hit our goal. After all, who are we going to believe, our collective inner TOP or our lying eyes?

I think it should probably be clear by now that The Optimistic Programmer isn't just an employee you can go find, fire, and then celebrate how much more awesome your company is. TOP is hiding in all of us. I encourage you to keep an eye out, recognize the next time you're being TOP, step back, relax, and then reassess the situation as TPP (<a href="http://www.amazon.com/gp/product/B000SEGEKI/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B000SEGEKI&linkCode=as2&tag=snibble-20">The Pragmatic Programmer</a>).