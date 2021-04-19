---
layout: post
title: Why should you limit your Work In Progress?
categories: kanban
---

# Why should you limit your Work In Progress?

Okay seriously, why would you do that? Starting stuff is cool! It makes you feel productive! Certainly more than watching the other work. 

More seriously, why would you force a member of the team **not to start** working on a new work item? What are the benefits? How is the client being more satisfied if you don't pick the next card - you know, the one that is always more urgent. To answer this question you have to **think about the flow globally**. Look at this example.

<a href="/assets/images/blog/wip-intro.png"><img src="/assets/images/blog/wip-intro.png" alt="wip intro" /></a>

In this fictive scenario it would be understandable for the Designer to want to start a new work item, as they have apparently been productive and have one more to pull. Though the set **WIP limit forbids** them to do so. If we look at the Dev column, they seem to be struggling on two tasks. We can also imagine, by the WIP limit of 1, that the Test team don't have a high velocity, or that one dev does the testing, thus not being able to work on "Dev" items for a while. This means that by tackling more work items the Designer(s) would **put more pressure** on the Dev team, which will then overflow the Test column. It will make the bottleneck even worst.

By trying to go "faster" we actually end up clogging the system and probably increasing the **Lead Time** (the time it takes for a work item to go through the whole board). **Little's laws**' equations show that the average Lead Time equals the average number of Work Items In Progress multiplied by the average **Cycle Time** (the time the client waits between two items being delivered). It means that if nothing is done to reduce the Cycle Time, taking a new card will mechanically **increase the Lead Time**.

<a href="/assets/images/blog/LittleLawLeadTime.gif"><img src="/assets/images/blog/LittleLawLeadTime.gif" alt="little's law" width="100%" /></a>

What can our Designer(s) do then? Well maybe they can give a hand developing or testing, which would help **finishing** and temporarily unclog the system. The sad truth is that doing nothing is in this case probably more productive than doing something. Of course this situation shows a clear bottleneck in the system which has to be discussed separately to avoid this pattern to repeat in the future.

To summarise, WIP limits force the team (and the teams upstream) to prefer **small Work Items**, which are more predictable and induce a smaller Cycle Time. It also is the essence of Kanban as it forces to **focus on finishing** rather than starting things. Doing Kanban without using and enforcing WIP limits removes the majority of the benefits it could provide, leading to batch delivery, high lead time and less accurate estimations.

Check [this article]({% post_url 2021-02-22-kanban-the-cargo-cult %}) to find out more common misconceptions about Agile practices.