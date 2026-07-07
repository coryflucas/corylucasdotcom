---
layout: post
title: My Journey to Becoming a High Level IC - Part 3
---

In Part 3 of this series I'll discuss lessons from my second job. I was now a Senior Software Engineer, working on a whole new set of problems and building full applications from scratch for the first time.

### Chapter 2: Going Deeper as a Senior Engineer

#### Design patterns are everywhere

I had been exposed to the idea of design patterns in school and in my previous work, but at this job I started working on the first project I was helping build from the ground up. It was the first time I got real exposure to the Spring Framework as I was moving from the .NET ecosystem to Java, and I dove in head first on the power of patterns like inversion of control, the strategy pattern, and the other Gang of Four classics. As I studied and applied these patterns I started to realize that many of these were things I had really already been using, just didn't have a name for. This led me to a belief that really a lot of these things are pretty intuitive, and can often be somewhat self-discovered, but having a name to put to them can still help. One of the ways I think it really helps is just realizing all the times you **shouldn't** use a pattern because it will come back to bite you later. It's also important to not overdo it with the patterns. If you have never read through the [FizzBuzzEnterpriseEdition](https://github.com/enterprisequalitycoding/fizzbuzzenterpriseedition), check it out and you will see what I mean.

#### Every dev is also a mini DBA

One of the projects I worked on at this job involved using PostgreSQL, which was not really in use at the company outside of this project yet, but we were steered towards using it for a variety of reasons. Because it was new for the company, we didn't have a ton of DBA support, just some part time support from someone who specialized in Oracle DBs. While this was sometimes frustrating, it was also a great learning opportunity. I had some exposure to table design from school, and I had been exposed to query plans at my previous job, but this was an opportunity to go deep on the basics and some of the features (quirks?) of PostgreSQL. Those basics have served me well ever since then. Understanding relatively simple things like indexes, their benefits and drawbacks if overdone is pretty essential for building a smoothly running system. Coming from my previous job where it was the norm to just throw `with (nolock)` in every query, really understanding transaction isolation levels and how they work in different database systems was another game changer. This also would lead to larger growth in my career as I realized how much more capable I could be if I understood at least some of what the other teams I depended on actually did (in this case a DBA team).

#### Performance matters

The system I worked on building at this job is still to this day the one with the highest load placed on it. We did load tests to tens of thousands of TPS on this system. Yeah, I learned some tips and tricks on how to optimize hot paths and speed things up, but I think what I really took from this was what good performance looked like. I think up until this point I had always taken for granted just how much compute we really have available to us (and this was 15 years ago now). This has led me to both care about building with performance in mind, but also to not just accept that something is "fast enough". In my apps, performance is far from the most important thing, but I think it's important to make optimizations where they make sense.

#### How much are you really worth?

The last thing I learned is not at all tech specific, but is more general career advice. Make sure you know what you are worth on the market, and make sure you ask for that. While I was at this job, I got an offer from a previous coworker to come work for him. I was happy at my current job, but he asked what it would take to get me to come to his company, and I threw out what I thought was a ridiculous number, expecting him to just laugh it off. But he just said sure, he could do that. So I interviewed and got an offer at the other company. This would be a more than **50% increase** in my salary. So I took that offer to my current boss, he took it upstairs, came back a few hours later and said they would match it. I ended up staying and just taking the increase, but I realized I needed to in general do a better job of advocating for myself from then on. If I had not had this lucky break, I would have not only not gotten that raise, I would have missed out on all the compounding increases on top of that.

### Wrap up

At my second job I got exposed to a lot of new tech and new responsibilities. Designing greenfield systems taught me a lot of lessons, and starting to branch out beyond just writing code showed me how much I still had left to learn.
