 

+++
author = "Mark Barta"
title = "Common Team Scaling Issues"
date = "2022-02-10"
description = "Repeated Issues I've Seen While Scaling Teams"
tags = [
    "Scaling"
]
categories = [

]
favorite = false
draft = false
+++



I've been a part of 2 different organizations that scaled from 20 people to over 100.  The first time took 4 years and the second took 6 months.  Both, were similar - starting teams that prioritized scrappy attitudes and get-it-done-ness that transformed into organized systems.  

Below are a few of the challenges we faced and a rough estimate of where in the growth they occurred. 

## @ 20 - 30 engineers

Conway's law hits.  You're probably around 4-6 teams.  Engineers will start talking about micro-services and Managers will talk about what teams will look like.  The funny part is that both are having the same conversation and if you don't recognize it, you'll have a hard time.  The question isn't *what* teams are, but **how** do teams work.  This was easy to handle in slow-growth mode, but in hyper-scale mode it was critical that everyone was on the same page. You can solve problems by pulling everyone into a meeting still, but it'll hurt when you grow.  

> Conway's law is an adage stating that organizations design systems that mirror their own communication structure

Look out for these issues:
- Teams stepping on each others toes (if you're in a mono).  You want to investigate your planning ceremonies and how changes are being communicated.  It's also possible that your product teams share too similar of a focus.
- Lack of communication (or miscommunication).  Before, problems would get solved in a meeting and everyone would know - because everyone was in the meeting.  If problems aren't getting communicated out, use the tools that you have to develop expectations on communication.  Even if it's a post to a slack channel, that'll work, just make sure you have a good slack strategy.
- Role confusion.  The growth may have had some unintended consequences.  People may be operating as a manager without the title or unsure of what their role actually is.  Broadly, make sure that everyone understands the process and how you expect teams to work.  You'll also want to have a career ladder in place.  For your budding leaders, make sure they understand their growth path.  

### Documentation To-Do:
- A Career Ladder.  https://www.progression.fyi/ is a good resource.  This will be how you're setting performance expectations and defining growth paths.
- Best Practices.  Especially as it relates to engineering - how do we deploy, how do we test, what tools do we use, etc.
- Culture.  What is it and how do we use it.  Be specific and talk about it, a lot.

## @ 50 - 60 engineers

### Platform Teams
In Will Larson's [An Elegant Puzzle](https://lethain.com/elegant-puzzle/), he says that systems only survive one order of magnitude.  This means you're looking at team structure again.  You'll have more product teams, but also platform teams.  DevOps and Data are the two big umbrellas.  As these teams start, make sure to revisit your communication expectations.  Product teams can point to user metrics to define priority, but it can feel different with platform teams.  Making sure your internal customers are heard and understand how you're prioritizing work is important.

### Management
If you didn't invest in a management layer before, you're going to notice it here.  Maybe the engineering aspects are running great, but the people aspect is falling behind.  Maybe you have a very talented manager, but they're burning out because they're not delegating enough.  You'll want to hire senior managers and ensure that new managers are getting the coaching they need.  

One solution is to create a Manager's Playbook.  Outline your values for management (make sure they align with your culture) and tools to solve common issues.  How are goals set?  How are expectations defined and communicated?  If someone is under-performing, how do we handle that?  What is our philosophy on promotions?  This will help align the entire organization.

Another solution are manager mastermind groups.  Make sure your managers are meeting with each other and supporting each other.  If one manager is experiencing a team problem, talking it through with the peer group can help.  Of course, set expectations for what kind of problems should be addressed here and what type of issues should stay private.

I also enjoy setting up a management book club that's open to managers and aspiring managers, but may not be workable in very fast paced environments.

### Succession

You'll also want to think about how people move up and/or out.  What kind of bus factor does the organization have? How are our leaders (people and technical) training others?  It's a value of all good management - that teams should be self sustaining.



### Documenation To-Do
- Management Playbook. Defined above.
- Onboarding best practices.  You'll have done this quite a bit by now.  We handled it on a team-by-team basis, but at this point, you'll want to standardize.
- Technical documentation structure.  At this point, we were writing documentation, but didn't have any specific best practices or structure around it.  Have a strategy for the structure, but again, it'll only survive an order of magnitude, so be ready for it to change.



## @ 80 - 100 engineers

This stage is where you may be repeating earlier lessons, but now it's a team within a team.  You'll want to make sure that the overall org structure is sound, expectations are written down, and processes are running smoothly.  

If you're getting the idea to reorganize, think it over.  If you do, go slow and in small increments.  Big bang, one and done type reorgs don't work.