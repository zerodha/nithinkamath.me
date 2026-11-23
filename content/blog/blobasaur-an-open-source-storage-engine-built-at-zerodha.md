---
date: '2026-11-23'
title: Blobasaur an open-source storage engine built at Zerodha
tags: [technology,fintech,zerodha]
author: nithin
link: https://x.com/Nithin0dha/status/2124814648642093274?a=XcjO5nh-z2rHB2PFedw&s=20
post_type: tweet
description: It handles tens of thousands of operations...

---
Our tech team has built and open-sourced a distributed, high-performance “blob” storage engine.

We needed to store UI and workspace preferences for millions of users, especially after the launch of Kite Terminal mode. Unlike small structured data, the data are “blobs”, anywhere from a few KBs to a few MBs. We looked around for a database that was simple to run and built specifically for this but couldn’t find one. So we built our own.

It is called Blobasaur. It handles tens of thousands of operations a second with single-digit millisecond latency, on ordinary hardware, while barely using any resources. We are using it in production.

A year of engineering all so the app remembers you prefer dark mode 😛

Check out [this post to learn more.](https://zerodha.tech/blog/high-performance-distributed-blob-storage/)
