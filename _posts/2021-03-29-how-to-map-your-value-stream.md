---
layout: post
title: How to map your Value Stream?
categories: kanban
---
# How to map your Value Stream?

Value Stream Mapping (VSM) is an extremely important part of the transition process to Kanban. The idea is to put on paper **all the steps involved in delivering value to the user** (eg. shipping a feature). 

From this Value Stream it will be much easier to draw / optimise your Kanban flow. It helps take a step back from what you are trying to achieve and maybe discover new patterns, bottlenecks or [Class of Service]({% post_url 2021-01-18-the-classes-of-service-cos %}). It also eventually provides a high level document that can be shown to management or newcomers to give an overview of a team's overall process. 

## How to map your Value Stream?

The first thing to determine is the **scope of your stream**. You probably don't want to start with the whole company but with your team. Once you know the beginning and the end, it is time to record every step. Don't try to find them all for now, simply **focus on the essential**. One tip is to **use different colours** depending on the function in charge of the step (eg. QA, Dev, Ops, Product, etc). Here's a trivial example:

<a href="/assets/images/blog/value-stream-1.jpeg"><img src="/assets/images/blog/value-stream-1.jpeg" alt="value stream" /></a>

You can then **iterate**, and for each step ask yourself what you've forgotten. I strongly recommend doing the whole process either with people from different departments, or at least go ask them questions individually about certain parts of the flow. Maybe some of your steps actually contain important sub-steps that should be shown here. Try to think also about **back-links**, as it sometimes happen that the team needs to go back to a previous step. Here is an example of how the mapping could evolve:

<a href="/assets/images/blog/value-stream-2.jpeg"><img src="/assets/images/blog/value-stream-2.jpeg" alt="value stream" /></a>

Finally, I strongly recommend going through every step to try and estimate **how long** their completion takes, relatively to the other steps. You can for instance give "1 unit" to the smaller step and derive the others relatively to it. Try also to add roughly the **number of people** working on it. 

All this data will help you structure your flow, find potential bottlenecks and optimisations. You can sometimes realise that an optional step at the end of the flow is always taken into account too late, and actually deserves a specific CoS and flow to parallelise a bit. Taking a step back is always a good idea and you should use every occasion to do it. 