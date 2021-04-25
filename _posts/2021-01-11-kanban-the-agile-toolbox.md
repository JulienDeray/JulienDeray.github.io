---
layout: post
title: Kanban, the Agile toolbox
categories: kanban
---
# Kanban, the Agile toolbox

Unlike other Agile frameworks, Kanban works even if you don't follow all the rules. Actually, switching a whole organisation to Kanban leads to Kaikaku (revolution, radical change), rather than the approach that Kanban recommands: **_Kaizen_** (literally "change good", ie. "**Start with what you have**"). Kanban is a set of tools that work well together but are not required to be used together. It means that it can help you solve specific problems without having to disrupt your entire organisation. We describe here the main tools available to you.

## The Board

How could we not start with the board? It is the first thing coming to mind when talking about Kanban, but this board is not just a random "Todo, Doing, Done" Trello-like board. To allow the pulling mechanism to be in place you at least need to think about having [double columns]({% post_url 2020-04-27-single-or-double-columns %}). But I am digressing... The board is where you can get the first obvious benefit of Kanban: [visualise the flow]({% post_url 2020-12-06-kanban-principles-1-visualise-your-flow %}). You know in a blink of an eye how the team is doing, whether it is drowning or completely idle. DevKan already implements and enforces the basic Kanban board's rules for you so you don't have to read 10 blog posts about them, make sure you give it a go!

## The WIP limits

[Limiting your work in progress]({% post_url 2020-04-15-why-you-should-limit-wip %}) is a good way to have a steady flow and avoid bottlenecks. It is simple to implement and extremely powerful. Though, make sure that everyone understands why if you want good adoption. 

## The swim-lanes

Usually the first argument I hear against setting up hard limits on the WIP is "what do I do if I have an extremely urgent bug and no space for it?". I suppose no one, not even The Board will prevent you from saving the business and push commits anyway. But if you want a more robust solution, you should use swim-lanes. In Kanban they are usually defined using the [Classes of Service (CoS)]({% post_url 2021-01-18-the-classes-of-service-cos %}) found when designing the flow and the Value Stream. But you fundamentally don't require a 3 hours meeting to start using swim-lanes. Simply draw another board for "Expedites", maybe adapt some columns that don't make sense in this context, and please add a WIP limit of 1 on the whole swim-lane. Next time you have a bug in production, you know where to go! This bring also the benefit of you being able to notice something is going wrong just by seeing a card in this swim-lane. 

But there are other classic CoS that deserve their own swim-lane. My favourite is probably the "Intangible" class. The strategy is simple: have a place in your board where you force a minimum of 1 Work Item and a low maximum. This way, you make sure to pay up your technical debt and prevent it to eventually blow up the whole system.

<p style="text-align: center;"><a href="/assets/images/blog/classes_of_service.png"><img src="/assets/images/blog/classes_of_service.png" alt="classes of services" /></a></p>

<p style="text-align: center;"><em>Taken from "Essential Kanban Condensed", by David J Anderson and Andy Carmichael</em></p>

## Explicit Policies

It is one of the 6 practices of Kanban and again, very easy to set up. It can be done  with sticky notes, a checklist in you CI, using DevKan, ... 🙃 The idea is to have a small checklist on top of the columns representing the steps of your flow, to be absolutely certain to not forget anything. You can see it as a local Definition of Done. It is a simple idea but it can save you from a lot of human errors. 

## Metrics

Obviously as you start using more tools, you will unlock more. Metrics is at the heart of Kanban and deserves a dedicated article. You'll figure out that you don't need so many data points to unlock probabilistic forecasting and have a very strong feedback loop to improve your processes. 

## Linked boards

Finally, as you advance in your practice of Kanban you might want to link several boards together and draw a bigger flow. If you started with an Engineering team, maybe you can start using some Kanban tools in the Product team and link them together. You can also use a board as a step in another board to have a high level view representing your roadmap. This opens an infinite range of possibilities!

So here we are, if you were looking for an excuse not to give Kanban a go, unfortunately there are none! There is always a tool adapted to your situation. As you can see, taken individually they can be used in other contexts than Kanban (even Scrum). We built DevKan with this idea in mind: **allowing you to use it without having to migrate your whole organisational system on it**. As you start pulling tools out of the Kanban box you will probably realise other aspects can be improved by pulling out more tools, but make sure you keep the Kaizen approach in mind to maximise adoption 😉