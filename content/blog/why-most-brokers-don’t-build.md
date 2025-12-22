---
date: '2025-12-22'
title: Why most brokers don’t build their own OMS/RMS
tags: [business,technology]
author: nithin
link: https://x.com/Nithin0dha/status/2003043461034053634?s=20
post_type: tweet
description: One of the lesser-known things about stock brokers is that most brokers don't actually own their entire tech stack...

---

One of the lesser-known things about stock brokers is that most brokers don't actually own their entire tech stack. There's usually a third-party vendor providing the core order management system (OMS) and risk management system (RMS). Think of OMS/RMS as being similar to the core banking systems that Infosys or Oracle provides for banks.

The OMS/RMS is basically the heart of a broking operation. If this breaks, trading stops. Vendors in our business include Omennest, Kambala, 63 Moons, Rupeeseed, etc. OmneNest, which we use has about a 70 market share.

Many brokers are trying to build this tech in-house. We've been working on it for almost four years now. It's extremely hard and complex. More importantly, it involves taking serious risks with your business during the transition. You're migrating live client positions while ensuring nothing breaks. One mistake and you could have trades going wrong, margin calculations failing, or clients unable to exit positions.

Constant regulatory changes make this even harder because they need to be incorporated into the system, and each change is a potential breaking point.

I think it's much easier for a broker starting from scratch to build their own OMS/RMS than for one that already has established size and scale. When you have lakhs of clients trading daily, you're essentially rebuilding the plane while flying it.

Also, it's hard to make tough decisions about important things like this when the incentives aren't aligned. For almost every business using vendors, the debate is: Why bother with the time, effort, and risk to business continuity when no one really cares if you're running the complete tech stack or not? Clients don't ask. And vendor costs haven't caught up with the phenomenal growth in brokers over the last five years either, so the immediate financial case isn't obvious.
