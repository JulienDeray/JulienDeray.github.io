---
layout: post
title: The Classes of Services (CoS)
categories: kanban
---
# The Classes of Services (CoS)

During your Kanban journey, you will probably ask yourself (or be asked) the following question: "What if a new very urgent Work Item is created while all the [WIP limits]({% post_url 2020-04-15-why-you-should-limit-wip %}) are maxed out?". Well it is a good time to start thinking about **Classes of Service**. They are a way to **classify** the Work Items and apply more **granular rules** depending on the type. They are all **handled in a different Swim-lane** because the steps, policies and/or WIP limits can differ from the other CoS. This also makes the overall board easier to read and allows to assess the situation faster.

The original Kanban CoS are based on the Cost of Delay, which is a function of the potential cost of postponing the delivery of a Work Item over time. The 4 basic Classes of Service are: **Standard**, **Expedite**, **Fixed Date** and **Intangible**.

## Standard

<p style="text-align: center;"><a href="/assets/images/blog/Standard-CoS.png"><img src="/assets/images/blog/Standard-CoS.png" alt="standard class of service" style="width: 30%;" /></a></p>

<p style="text-align: center;"><em>Taken from "Essential Kanban Condensed", by David J Anderson and Andy Carmichael</em></p>

The Standard CoS is the one by default. The more you wait before delivering it, the more it will cost (in reputation for a small bug or an expected feature for instance). Although they are not very urgent, they have to be done rather sooner than later.

## Expedite

<p style="text-align: center;"><a href="/assets/images/blog/Expedite-CoS.png"><img src="/assets/images/blog/Expedite-CoS.png" alt="expedite class of service" style="width: 30%;" /></a></p>

<p style="text-align: center;"><em>Taken from "Essential Kanban Condensed", by David J Anderson and Andy Carmichael</em></p>

All hands on deck! Chances are you have started to lose money already when Expedites are created. Those are mainly for **outages**. and bugs in production. And this answers the question in the introduction, you should always have room in this Swim-lane (and if you don't well... at least it forces you to **stop starting and start finishing**). For such Work Items you can, for instance, set a policy to prevent anyone from working on other CoS as long as an Expedite is hanging. The steps can be different if you have a fast-track deployment process for outages. 

**When an outage arises you don't want the team to think about processes.** This gives you a war room right on the Kanban Board with a predefined process to follow. 

## Fixed Date

<p style="text-align: center;"><a href="/assets/images/blog/Fixed-Date-CoS.png"><img src="/assets/images/blog/Fixed-Date-CoS.png" alt="fixes date class of service" style="width: 30%;" /></a></p>

<p style="text-align: center;"><em>Taken from "Essential Kanban Condensed", by David J Anderson and Andy Carmichael</em></p>

I never really thought about it before running into Classes of Service, but a Work Item with a strict, pre-defined and known deadline is of no use in the Done column, because it didn't deliver any value yet. **The other tasks the team could have completed instead of working on a Fixed Date probably had a higher cost of delay.** Postponing Work Items in this CoS costs nothing... Until it does. But when it does, it can be catastrophic. At least in the meantime, they are here on the board, ready and known. 

As you go through them during your [daily stand-up]({% post_url 2020-12-11-daily-stand-up-the-kanban-way %}), you'll find out when it is the right time to start working on them to not take any risk but also prioritise other tickets.

## Intangible

<p style="text-align: center;"><a href="/assets/images/blog/Intangible-CoS.png"><img src="/assets/images/blog/Intangible-CoS.png" alt="intangible class of service" style="width: 30%;" /></a></p>

<p style="text-align: center;"><em>Taken from "Essential Kanban Condensed", by David J Anderson and Andy Carmichael</em></p>

Intangibles are the least known and probably most underestimated Class of Service. We are talking here about all the **painful maintenance tasks** like updating the version of a database, refactoring a certain part of the code that is getting worst every time someone touches it, etc. I am certain you see what I am talking about. The issue with those Work Items is that there is always something more urgent to do. Until the day the last drop fills up the vase and AWS stops supporting your legacy database version.

I find Intangibles extremely useful to pay up all kinds of **technical debt**. The trick here is to make sure the team works on them. And this is where you use WIP limits the other way around and force a **minimum** of 1 Work Item to be active in the Intangible Swim-lane at every moment. You will be amazed by how efficient this is. You don't pay back your mortgage once a year, do you? Well, same goes for technical debt. Plus I personally find it somehow refreshing to work on something different from time to time, which those Work Items often offer. 

## Custom Class of Service

When [mapping your Value Stream]({% post_url 2021-03-29-how-to-map-your-value-stream %}), you'll find out that some Work Items are different from others. Maybe they require extra steps, a specific deployment process, or you need to know in advance that they are coming because another team is working on something that you will have to handle. Whatever the scenario is, **some types of Work Items deserve there own CoS**, with their own set of policies, steps and WIP limits. Doing so will **provide an explicit process** to follow, decrease the chances of human errors and reduce process specific documentation.

## Conclusion

Classes of Service is a very powerful tool in your [Kanban toolbox]({% post_url 2021-01-11-kanban-the-agile-toolbox %}) and I encourage you to start using it as soon as possible. This also gives another dimension in the flow optimisation that Kanban has to provide and it would be a shame not to use it. 