---
layout: post
title: Single or double columns?
categories: kanban
---
# Single or double columns?

People tend to think that "Kanban" is just three columns (Todo-Doing-Done) and a few cards moving from left to right. We do Kanban with Jira, Trello, Asana or GitHub, to support our Scrum Board or organise a project. These tools share a common (non-)feature: **they use single columns**. Can we therefore really use them for Kanban?

<a href="/assets/images/blog/single-or-double-colums.jpg"><img src="/assets/images/blog/single-or-double-columns.jpg" alt="Single or double columns" /></a>

Let's go back to the origins: the word "Kanban", which means **"Signal Card"**. It comes from Toyota's factory where cards were put into piles of bumpers, near the bottom of the pile. When a worker was finding such a card between two bumpers they had to expose it to show to another worker that the pile was almost empty and needed a refill. It was a **signal**. The equivalent in nowadays' boards is to move a card to a "done" sub-column. By doing this **we show that we are done** and that a new task is available for someone else to **pull**. Without this second column it becomes hard to recognise when a task is available. Or you have to resolve to **pushing** the card to the next step. But it puts the burden downstream and does not let the next team decide when to do and when. 

Pulling is essential to unlock the benefits of Kanban. It allows teams to **manage their own part of the flow** and it **reveals the bottlenecks**. Moreover, sub-columns say something about the **status of the Work Item**: is it active, idle or done? Reports on these statuses give you very important **metrics** about the efficiency of your flow. How long does it take for an approved Pull Request to be deployed? What step often blocks the work flow? Metrics are important because they reveal what the flow looks like in average rather than at one point in time. Bottlenecks are not always as obvious as in blog articles 😉

Finally, pulling gives a sense of **ownership**: the people responsible for working on a task can decide when to start or maybe which one to take. They can manage their own smaller Kanban board at their scale, and then notify downstream when they are done. 

To be clear, there is not good or bad ways. Trello is an amazing tool for organising all sorts of projects. I have to confess I even used it as a visual database once, using the REST API 😅 But having columns is not enough and it removes a lot of the power that Kanban offers when done correctly. If you want useful [WIP limits]({% post_url 2020-04-15-why-you-should-limit-wip %}), meaningful metrics, ownership and an optimised flow, you need the double columns.

Check out our article about [Cargo Cult]({% post_url 2021-02-22-kanban-the-cargo-cult %}) to explore other Agile anti-patterns.