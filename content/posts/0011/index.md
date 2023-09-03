---
title: "Opting Out of AI Web Scraping"
date: 2023-09-01T22:02:56-07:00
description: "Why do I have to \"opt-out?\""
author: "Hayaan Rizvi"
showToc: false
TocOpen: false
draft: false
tags:
  - technology
  - meta
---

If you open my website's [robots.txt](https://omega1510.github.io/robots.txt), you will see that it includes the following lines:

```yaml
User-agent: GPTBot
Disallow: /

User-agent: ChatGPT-User
Disallow: /
```

What do these lines of code do? Well, they stop OpenAI's ChatGPT from learning from my blog.

OpenAI recently unveiled GPTBot, a piece of software that lets them harvest data from the web to train their artificial intelligence models on. If you take issue with that, like I do, then adding those lines to your website prevent it from scraping the content you wrote.

I, and many other people, don't want artifical intelligence benefiting from my blood, sweat, and tears for free. I find it deplorable that you must "opt-out" of this process. What about people who have no idea that their data is being harvested and used, or who aren't technically inclined enough to block GPTBot? Will their data be used without compensation until the end of time?

The way it should work is that you must opt-in specifically, and only then will OpenAI scrape your website. Unfortunately, we all know this won't happen. All OpenAI cares about is profit, and that won't happen if they actually respect people's basic right to privacy.

I recently talked about this with a friend. He told me that AI is the future of using the web, and if I block ChatGPT, I'm going to lose out on a lot of readers. My opinion may change in the future, but as of now, so be it.