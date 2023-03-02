---
title: Tech interview is a mind game nowadays
comments: true
date: 2023-02-24 01:12:43
tags:
---

Yes, I am creating yet another post about tech interviews, because I am looking for a new job, again. I have to, because as you may know, all big names are doing layoffs nowaways, starting from Meta's since last November.

When I graduated in 2015, Leetcode had 200 or 300-ish coding questions. When I was looking a job in 2018, the count was probably 800+, and the number might be 1600+ in 2021. As the time of writing, it's 2573. The numbers do speak, that coding interviews for Software Engineer positions are definitely getting out of control. Completing all 2k+ questions doesn't sound like a realistic goal, especially for job seekers who have very limited timeframe. 

On the other hand, I did get entitled interviewers who was calling those who could only do LC questions code monkey. Although I was not a 100% code monkey, I could feel the insecurity from the interviwers. You call other folks code monkeys because you can't even solve straightforward questions. C'mon, you were bragging about "I'd prefer solve real world, production problems", because that's what you've been grinding on. Like nobody is supposed to master kubernetes as a deployment system, if that's a hard requirement, you guys are missing pretty much all candidates from AWS and Google, because they probably use internal systems like Borg, Nebula, ECS, Fargate, etc.

In my opinion, conducting coding interviews with LC-style questions is by far the most fair way. We all have to master common data structures, patterns, algorithms. So, as a suggestion for interviewees, be smart on griding LC questions.

Skip questions that might not be asked. 
- Some questions are too hard. I bet most non-code monkey interviewers can't do it either.
- Or they just simply don't want you. (See below screenshot)

<a href="https://leetcode.com/problems/sum-of-two-integers/editorial/" target="_blank">![](/images/20230224.png)</a>

Always believe in yourself, that your coding ability is stronger than the interviewer, and tell yourself, "This guy who's interviewing me is a fking dumb-ass. My LC contest ranking is 5% of the world. You know nothing about coding at all, snowflake!".

The same situation goes for system design related questions.

In real work, your interviewer might be creating CRUD applications on a daily basis, or writing unit test every night to improve the coverage from 75% to 80%. And you are expected to design a highly scalable, durable and available service that serves 100M daily actively users globally, with read and write heavy traffic, and should handle 5x traffic spikes, without losing data or customers' money or impacting revenue. Lmao.

Another funny thing is that a lot of buzzwords are used excessively in system design prep materials, like TCP/IP, load balancer, CDN, Proxy, WebRTC, long polling, Bloom Filters, Heartbeat, gossip protocol. I bet 80% people don't directly interact with compute networking knowledges in real work. The reality is that, people are working with existing RPC/REST frameworks, in some places those frameworks are internal proprietary. Who give a fxck about partitioning, replication of the data if you are already using managed services like DynamoDB? Why do you want me to choose from SQL and NoSQL? Share we use Google Spanner, a fking distributed fully managed scalable SQL db that support transactions! 

This is a really bad time for tech interviews, not only because there are dozen of thousands laid off folks on the market. Existing methods of assessing candidates feel obsolete.

Based on my observation, some innovative interviwers have adaopted OOD related questions in their interview, which sounds good, as they could simulate real work scenarios with those questions. The issue is that those type of questions can be subjective, especially when the questions are not well curated, and are just invented out of their mind.

Again, no matter whatever questions I get asked during my interview, I don't care now, because you don't know more than me.