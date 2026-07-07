---
layout: high-level-ic
title: My Journey to Becoming a High Level IC - Part 2
tags: high-level-ic
---

Earlier this year I started writing about the different experiences and lessons that have shaped my career journey. This post is Part 2 of the series and I'll walk through some of the things I learned at my first job.

### Chapter 1: The First Job

When I joined the company I was initially doing rotations with different teams as a way to learn the different systems of the company. Getting hands on experience was a great way to learn, and it also meant I was exposed to various different ways of working.

#### Automate It

One of the things I noticed pretty quickly was how much complexity was added by working in a code base with multiple people all the time. Sure, I had worked on a few group projects in school, but those tended to be a relatively small group and we would generally divide up work to avoid stepping on each other too much. Here I was potentially working with 15 other people all doing changes for their own tickets in the same code base at the same time. It wasn't uncommon to have to get all the developers together because someone's changes resulted in the system no longer working, or no longer even compiling for someone else. This was my first experience with "works on my machine". A few rotations in I landed working with a team who were doing things a bit differently. They had a continuous integration setup and had actual unit tests for their code that ran on every change. This was a game changer! If someone made a change that broke something, we all immediately knew and could swarm on getting the issue resolved while it was fresh. 

Another thing I noticed was that for some teams one of the major challenges for performing a new release was getting the actual package software built and ready to ship. For many of these teams getting the artifacts for a release ready might take a day or more, following a complicated set of instructions that was hopefully still up to date. One team used a licensed tool as part of building the application, so only the one or two people on the team with a license could even do certain parts of this process. The team doing CI had that process set up to create the actual deployment artifacts as well, so all we needed to do was download them from the CI server. Later on I would work with this team on automating the actual deployment of the artifacts to web servers to replace the manual deployments that tended to be error prone.

This all showed me the benefits of automating routine tasks. If you have to do something over and over again, just automate it. As a bonus this automation serves as a form of documentation of how these steps are to be performed, and it doesn't get out of date because someone forgot to write down a new change!

#### It's OK to question things

Impostor syndrome is something that impacts almost everyone, especially when you are new to both a company and a role in general. When I started at this job I thought that surely everyone around me knew best and they had great reasons for how they did everything. One of the benefits of rotating between teams was I was able to see how different teams tackled similar issues, and it wasn't always the same way. I slowly figured out that often teams do things a certain way just because that's how they've always done it, even if it wasn't the best way. Sometimes they didn't know there was a better way, and sometimes they didn't think it was worth changing things.

This led me to eventually start to question things (in a respectful manner) and see if there were things that we should be doing differently. I think this gained me a lot of respect from leadership and it's been a mentality that I've taken with me throughout the rest of my career. I always tell more junior engineers that it never hurts to ask if they don't understand why something is the way it is. Sometimes there is a good reason, but sometimes you may just be bringing something fresh to the table.

### Wrap up

I learned a lot at my first job, and worked with some great people, some of whom I would continue to work with for many years. It's been fun to look back on the lessons I learned, even if I didn't know it yet.