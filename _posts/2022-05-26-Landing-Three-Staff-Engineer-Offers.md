---
layout: post
title: How I Landed Three Staff Engineer Offers
---

I began my interviewing journey in March 2022, when I polished my resume and applied to several big tech companies. I spent 6 weeks preparing for my technical interviews while stepping into a new role at Dropbox as an interim engineering manager. I passed 100% of my phone screens and onsite interviews this time, a feat I have never achieved before. I received 3 offers for Staff Engineer roles at Snap, Pinterest and Uber. A lot of my friends have asked me for tips, and that is my main purpose in writing this blog. For the most part, I did not reinvent the wheel, and in this post I will be sharing many resources that I found helpful. I will offer a few tips that I did not find elsewhere.

## Motivation
Interviewing as a software engineer is a huge gauntlet, and I'm not a person that enjoys interviewing to "test" the market. If I'm going to be investing 6 weeks of my time studying 4-6 hours a day, I better be prepared to leave my role at Dropbox. As happy as I was at Dropbox, I felt that my time was coming to an end. I did not believe there were many opportunities for growth remaining in my org, and I was not interested in changing teams. There were a few departures in the past year that stung. In addition, I was hitting a 4-year cliff and Dropbox did not yet have a plan on resolving it. It is important for me to catalog my reasons, not only to fully commit to this process, but also because it would be one of the first things that a recruiter is going to ask me.

## Applying
I'm interested in the developer experience of a mobile engineer, and I sourced most of my roles through LinkedIn. My customers are other engineers, and it is a niche role. After I found the roles I was interested in, I reached out to my network for referrals. 

## Scheduling
I scheduled my recruiter screen for the immediate future, and after I spoke with them, I scheduled my technical phone screen for a few weeks out. That would give me enough time to practice some Leetcode and brush up on my Android knowledge. Once I passed my phone screens, I scheduled my 3 virtual onsite interviews in the first week of May. My reasoning was to hopefully receive multiple offers and leverage them. Additionally, I worked with my recruiters to understand what I was being evaluated on and pushed back in cases where I did not think it would give them the right signal. For example, one of the companies wanted to give me a heavy Android UI focused interview. Since I'm not a product engineer, and I was not interviewing for a product engineering role, I advocated for an Android debugging question. I also only scheduled onsite interviews such that all my interview loops were similar, as that allowed me to be more efficient with my prep.

## Prepping
Most of my interviews loops like this:
- Behavioral
- Android Domain Knowledge
- Android Coding
- System Design
- Data Structures and Algorithms

Since I was interviewing for a staff engineer role, I focused very heavily on behavioral and system design interviews. I budgeted 30% on behavioral, 40% on system design, 10% on Android coding, and 20% on Leetcode.

It's very fortunate that in 2022, we have lots of YouTube content to be able to ingest more passively. On the occasions that my eyes were dry, or I lacked the motivation to do another Leetcode problem, I would pull up a YouTube video of a mock interview. 

The cherry on top was that I had a few friends that gave me mock interviews. From the bottom of my heart, I truly thank you.

## Behavioral
I drew inspiration from Dropbox's behavioral interview for questions that could be asked by other companies. For those that don't have that luxury, this [resource](https://www.interviewkickstart.com/interview-questions/behavioral-interview-questions-faang-software-engineer-interview) comes very close. 

I created a doc with all the questions, and wrote up all my answers for them and I'm talking about paragraphs worth; it needs to be deep. Every couple of days I would read through the list of questions and my answers to them, but my goal wasn't to memorize it. I also told my stories using [man in the hole storytelling](https://spectacularspeaking.com/2019/08/28/man-in-the-hole/#:~:text=One%20of%20the%20simplest%20story,crisis%2C%20and%20reaches%20rock%20bottom) instead of using the [STAR technique](https://en.wikipedia.org/wiki/Situation,_task,_action,_result). Meta does a good job in his [video](https://www.youtube.com/watch?v=hU6BVxtGd5g&ab_channel=Meta) explaining how man in the hole story telling relates to tech.

I also spent a considerable amount of time watching these resources on YouTube at 1.75x - 2x speed:
- [Meta Engineering Advice](https://www.youtube.com/channel/UCEHFikgnRuLd1HYKTLrae9Q)
- [Clément Mihailescu](https://www.youtube.com/watch?v=6rW01g6Obwk)
- [Self Made Millennial](https://www.youtube.com/watch?v=IV30jAw7dxA)

## Android Domain Knowledge
I'll handwave my way through this section because it's more specific to my role. I spent a lot of my time reading blog posts from Gradle, the companies I was interviewing for and their peers. I also looked for content on YouTube that was specific about modularization and improving Android build times. For folks that are interviewing for more general roles, this interview slot would be another Leetcode round for junior-senior folks and it would be another behavioral or system design round for staff+ roles. 

## Android Coding
This round was a debugging interview for some companies where they present an app to you with several bugs. For others, it was to build out a feature in a sample app that they provided.

The last time I seriously built a feature was over 2 years ago. I cloned a few sample apps on Github and tried adding a feature to them. Most of this was to refamiliarize myself with the tools that I have available: keyboard shortcuts, Logcat, and Profiler. 

## System Design
This interview was the most difficult for me to prep because from gathering information from my recruiters, the system design would range from building out a new app to building out CI infrastructure. 

For studying mobile app system designs, I used Alex Lementuev's resource on [Github](https://github.com/weeeBox/mobile-system-design) and watched a few mock interviews conducted on [YouTube](https://www.youtube.com/channel/UCaKF4HzmE8ypd36tKbjVa5w).

I read both volumes of [Alex Xu's](https://twitter.com/alexxubyte) System Design Interview. Although these books are more heavily indexed for backend engineers, the thought process, considerations, and flow of the interview are generally the same. As a more senior candidate, I am expected to be in the driver seat. However, I must keep my interviewer included and it's easier to frame the interview such that I'm solving a problem with a co-worker.

1. Clarify the problem set
2. Suggest MVP features
3. Start with a high level design
4. Mock out APIs
5. Deep dive into parts of the system
6. Explain any trade offs you're making

## Data Structures and Algorithm
I made a conscious decision that I would not be studying trees, graphs, and dynamic programming for these interviews. I was prepared to fail my interviews if any company decided to administer those types of questions. By eliminating these areas, I was able to focus on other DSA concepts. I spent most of my time solving easy and medium Leetcode questions on [Grind 75](https://www.techinterviewhandbook.org/grind75). Also, I put an emphasis on recursion with backtracking, as that is one of my weak areas. I found [Marty Stepp's](https://www.martystepp.com/) videos on YouTube very helpful.

## Offer
The job is not done after passing my interviews, and once I received offers my focus immediately switched to preparing for negotiations. Although truth be told, the negotiation starts on the first call with the recruiter. I deferred all conversations about compensation until I received an offer. 

The best resource I've seen around negotiations is written by [Hasseb Qureshi](https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/). 

I was in the offer stage for almost 2 weeks. During this time, I did as much research as I could about the companies by reading Glassdoor and Blind reviews. I spoke to multiple potential team members of these companies. I read any scandalous articles I could find. I listened to earnings calls to understand the strategy and future of these companies. 

After collecting all this information, I put together a spreadsheet and ranked these companies on different factors. In the end it was not all about the total compensation, but I did want to see if the company that I would end up selecting fought for me. 

I could have probably increased my offer more by pitting the 3 companies against each other. However, I was not prepared for the stress of receiving offers from 3 amazing companies. I was waking up at 4am every day due to the anxiety and stress. 

In the end, I went with my heart and selected Pinterest. Their initial offer was already very strong. I played my trump card and told my recruiter "I will sign if". 

## Resources
- [Behavioral interview questions](https://www.interviewkickstart.com/interview-questions/behavioral-interview-questions-faang-software-engineer-interview) 
- [Man in the hole storytelling](https://spectacularspeaking.com/2019/08/28/man-in-the-hole/#:~:text=One%20of%20the%20simplest%20story,crisis%2C%20and%20reaches%20rock%20bottom)
- [Meta Engineering Advice](https://www.youtube.com/channel/UCEHFikgnRuLd1HYKTLrae9Q)
- [Clément Mihailescu - Behavioral interview](https://www.youtube.com/watch?v=6rW01g6Obwk)
- [Self Made Millennial - Behavioral interview](https://www.youtube.com/watch?v=IV30jAw7dxA)
- [Alex Lementuev - Mobile System Design](https://github.com/weeeBox/mobile-system-design) 
- [Alex Lementuev - Mobile System Design Mock Interviews](https://www.youtube.com/channel/UCaKF4HzmE8ypd36tKbjVa5w)
- [System Design Interview – An Insider's Guide](https://www.goodreads.com/book/show/54109255-system-design-interview-an-insider-s-guide)
- [System Design Interview – An Insider's Guide: Volume 2](https://www.goodreads.com/book/show/60631342-system-design-interview-an-insider-s-guide)
- [Leetcode Grind 75](https://www.techinterviewhandbook.org/grind75)
- [Marty Stepp - Stanford Lecturer](https://www.martystepp.com/)
- [Ten Rules for Negotiating a Job Offer](https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/)