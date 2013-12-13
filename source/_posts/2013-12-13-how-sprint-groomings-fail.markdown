---
layout: post
title: "How sprint groomings fail"
date: 2013-12-13 15:45
comments: true
categories: 
---

I worked with some teams on grooming lately, and I found that there might be still some areas we can improve for grooming. In this blog I'll briefly introduce several common problems I've seen, and the solutions to fix them.

Common problems with grooming:
ATDD cases are just by-product of grooming
Wrong timing
not focusing on the scope but focusing on questions

And here comes more detailed descriptions.

ATDD cases are just by-product of grooming
The problem is, most of the time were spent in discussing how to implement the requirement, and while time is almost up, team quickly summarize what they need to test based on the understanding of solution. So in this scenario, ATDD cases seem to be a by-product of our solution discussion. But we need to realize that, solution and ATDD (which reflects the requirement) are different issue, while the former is the issue of "do thing right", the latter is more of the issue of "do right thing". And we need to really ensure that we're doing right thing, by increasing the focus of ATDD case discussion in grooming meeting.

To solve this problem, I've suggested to some teams that we have a separate section in the grooming meeting,  discussing only the ATDD cases, before we start to discuss the solution. Team members try to avoid the discussion of "how to implement this iteration item", and focus on "what's the behavior of the iteration item". 

Of course, ATDD cases in this phase are in abstract level, because some check points can not be finalized before we get a concrete solution for the iteration item. But it doesn't matter, for we can distill our cases to more specific level before the planning, or even after the planning but before the coding is finished.

Teams can still apply the framework like SQA (scope, question, and assumption) and FURPS (functionality, usability, reliability, performance and supportability). But this is out of the scope of this blog, and if you have further interests, you can either googling it or discussing with me.

Wrong timing
It's quite often that teams have grooming just one day before the planning. But this is not very good practice, better practice is to have the grooming one or two week before planning, for a 4-week sprint.

Reason is that, the purpose of grooming is to make the planning easier, so in the grooming, we split the iteration item into smaller granular, and will meanwhile get some questions. If we don't have enough time to clarify the questions before the planning, it might be difficult to continue with planning, sometimes we can be dropped into endless question loops and discussions. So having grooming one or two weeks before planning let us have enough time to clarify questions.

Some teams even have the grooming after planning, to have more design on solution, and to clarify the problems found from the planning. This is one thing I don't quite agree, and just too disagreed to give more comments on this. And as a reader you can think of this if interested.

not focusing on the scope but focusing on questions
This is the problem about how we get solution. Much of the teams discuss solution based on "SQA" framework, and sometimes people are easily absorbed with the questions (Q) they're discussing, and forget that it is also important to get the scope (S) without missing important aspects. 

So my suggestion is that, firstly try to list as much as we know about the scope, then for those part we're not sure, just write down question, discuss about it, or solve it offline before planning.
