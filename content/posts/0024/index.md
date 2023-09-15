---
title: "End-to-End Encryption is Not Secure"
date: 2023-09-15T15:23:52-07:00
description: "It's just another buzzword."
author: "Hayaan Rizvi"
cover:
  image: "whatsapp.jpg"
  caption: "Screenshot from WhatsApp, who is notorious for this."
  hidden: false
showToc: false
TocOpen: false
draft: false
tags:
  - technology
---

We have all heard the classic tech buzzwords: artificial intelligence, machine learning, military-grade encryption, and countless others. This last one is particularly annoying because all it means is `AES256`, the bare minimum for a modern application. In recent years, the general public has begun to understand that military-grade encryption is just corporate-speak and nothing special. Unfortunately, the same cannot be said for the term "end-to-end encryption."

Encryption is good, don't get me wrong. In messaging applications its a requirement. But encryption means nothing when the company running the messaging application has the encryption keys. For example, _WhatsApp_ encrypts messages when you send them, then _WhatsApp_ decrypts them on the recipient's device. WhatsApp handles all the encryption, so they can read your messages, despite what they claim.

This is the reason that most end-to-end encryption is not secure. Most applications that implement it don't put the keys in the user's hands, but keep them themselves. The way to tell if a company has done it properly is if you must generate keys on your own computer, then share them with the recipient, and vice-versa. Github is a good example of this. To sign commits, the user needs to generate their own OpenGPG key. This is the way to do it.

I understand that an app like WhatsApp can't realistically have every user generate their own encryption keys. What they can do, however, is stop advertising "end-to-end encryption" like it's anything secure.