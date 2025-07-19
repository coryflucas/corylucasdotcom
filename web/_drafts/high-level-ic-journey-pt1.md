---
layout: post
title: My Journey to Becoming a High Level IC - Part 1
---

One of the most common questions I get in my role is "what do I need to do to 
get a high level individual contributor (IC) role?". It's a question I've generally 
struggled to answer, partly because the folks that I have worked with in these 
roles often have very different responsibilities. Some are more hands on, some are 
on the edge of being people leaders. To me these roels are always a bit more nebulous
than traditional developer roles, and that can be part of the challenge of being in
one.

One evening when I was meeting up with another engineer and talking about 
his career journey I had a bit of an aha moment. I was describing something I 
realized at my first job that I felt like had a real impact on me and shaped
the path I took and how I think about things even today. After that 
meeting I thought about this some more and realized I have a dozen or so of 
these important things and I realized something I should do is share those. 
This post serves as the start of that.

### The Prelude - College

As I starting making a list of things to cover for this, I realized that there 
were things that shaped how I think about tech that I picked up before my 
first job. I have a bachelors degree in computer science, and while I think it
has served me well, I don't think its neccissarily a requirement to be successful
in a technical role. Many of the things that have really stuck with me weren't 
the regular coursework.

#### Learn whats under the hood

One of favorite college courses was in assembly language. We learned 8086 
assembler and I found it to be one of the more interesting classes.

I was amazed at the things that were avaiable as instructions, like string 
operations. There was an instruction that if put a memory location in 
a register that pointed to a null terminated string, and then put another 
memory location in a different register that pointed to a single character,
you could call the instruction and it would basically loop through the string 
until it found the character or the end of the string. That something this 
seemingly high level was accomplished by just calling a single instruction in 
a loop blew my mind.

The other thing that I really liked from the course is you could look up how 
many clock cycles each instruction took to run. This meant that if you knew 
the program and any inputs which might impact the number of times any loops 
would run, you could calculate in **clock cycles** how long a program would 
take to run!

Now, I've never written anything outside of college in assembler, and I'm very 
unlikely to ever do so, but these things made me realize that its important to 
peek under the hood every once and a while. You don't need to know how 
absolutely everything works (thats what abstractions are for after all), but 
have a decent grasp of all the things you are building on top of can help you
make better decisions.

#### Experimentation as a way to learn new things

I had one professor in college who seemed to have a goal of finding the 
obscure programing language he could for examples to show us. I learning to
program in Perl, and by this time had done PHP, C, C++, and Java. They each had 
their own set of strengths and own set of quirks to learn how to deal with. I 
learned each had their own pattern for doing things, and when I dug into some 
of the reasons why I realized this was a great way to learn things that are 
often taken for granted. Much later on in my career I learned about functional 
programing languages and all the interesting patterns that come with them.

Now you may never use Haskel or Tcl in your professional work, but I think 
there are still plenty of things you can learn from playing around with new 
tools and learning how they are meant to be leveraged. Mixing functional and 
object oriented programing has become quite mainstream for example.

### Wrap up

I learned a lot in my 4 years of college and I am very thankful to have had 
that opportunity. Many of the things I took courses dedicated to I have 
probably never used directly, but even then I often learned indirect skills 
that I still use to this day. Being curious is important when working in tech
in my opinion, mostly because things never stay the same for long. We are 
always having to learn the next new thing, and if you aren't curious you can 
get left behind.

Stay tuned for part 2!