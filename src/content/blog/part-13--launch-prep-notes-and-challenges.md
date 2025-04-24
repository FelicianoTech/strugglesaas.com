---
title: "Part 13: Launch Prep - Notes and Challenges"
author: FelicianoTech
date: "2025-04-24T18:00:00-04:00"
description: "I go over some thoughts and issues I have as I get ready to soft launch Revidian Cloud."
categories:
  - "Main Story"
tags:
  - ""
featureHide: true
---

Hey folks. In this post I'm going to cover a smattering of thoughts and challenges I'm running into.
I'm mostly cleaning things up for the soft launch of Revidian Cloud so no new features or anything like that to discuss.

<!--more-->

## Lack of co-founder

If you've been reading *Struggle SaaS* since the beginning, you'll know that I started off building my previous project, Melitix, with a co-founder.
The founder relationship fell apart and I eventually pivoted from the project to this one.
I miss it.

Having someone to help hold you accountable, weigh in on ideas and provide their own, is extremely helpful.
I know that a mastermind would likely be a good alternative.
I found a good program by [Microconf](https://microconf.com/masterminds).
The problem is it isn't free and I can't afford it.
For now I continue solo.

{{< callout >}}The Revidian Cloud LinkedIn page is here! Please help me out by giving it a follow [on LinkedIn](https://www.linkedin.com/company/revidian-cloud).{{< /callout >}}


## Social media

I was setting up social media accounts ahead of the launch and sort of got stuck in my own head for a bit.
Which platforms to create accounts on? This was difficult for three reasons:

- there's platforms I personally dislike i.e. TikTok  
- there's platforms I politically dislike  
- more platforms may mean more reach but spreads myself more thin

Should I create accounts on platforms where potential customers are regardless of how I feel?
Should I just focus on a couple?
Anyone have thoughts here?


## Other

GoDaddy is trash. Let me explain.
With my focus on building out domain name features first, I looked into which registrars I should prioritize for building API-based imports.
After adding support for Cloudflare, Namecheap, and Porkbun, I decided to use one I don't personally use.
I believe GoDaddy to be the largest registrar.
It use to be trash but I thought, maybe it's better now.
I went ahead and created a new account and bought a new domain name.

I envision having GoDaddy support especially useful for agencies.
They tend to have many customers that aren't tech savvy and fall victim to GoDaddy's marketing.
I started building out test code to get import support working in Revidian Cloud for GoDaddy.
I kept running into a problem.
After HOURS of debugging I found out the problem.
GoDaddy doesn't allow you to use their API unless you have 50 or more domains in your account.
No where on their pricing page, their docs, or the error returned by the API does it say this information.
GoDaddy is trash.

<br />

Until the next one,  
Ricardo (FelicianoTech)
