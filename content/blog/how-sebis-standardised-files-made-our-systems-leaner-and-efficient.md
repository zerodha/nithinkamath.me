---
date: '2025-08-12'
title: How SEBIs standardised files made our systems leaner and efficient
tags: [zerodha,technology,regulation,broking,fintech]
author: nithin
link: https://x.com/Nithin0dha/status/1955167995271188782
post_type: tweet
description:  A great example of...

---
One critical aspect of the brokerage business most people are unaware of is the sheer underlying complexity.

At a high level, we integrate with multiple stock exchanges, depositories, RTAs, banks, and others. Each of these integrations (hundreds of APIs and file exchanges) has been non-uniform and non-standard, resulting in massive amounts of technical and operational complexity. These are completely invisible to a broker's clients.

A great example of quiet, systemic backend work yielding significant impact is the multi-year exercise SEBI undertook to standardise data exchange across market entities—the Unified Distilled File Formats (UDiFF).

The same data that was represented inconsistently across three exchanges, for instance, was unified to be consistent in a single format, across numerous data structures.

As a result of this, we ended up removing 60%+ of the code that was required to maintain these separate data formats, significantly reducing technical and operational complexity and risk.

Along with it, we saw huge efficiency gains. For instance, a nightly data import process went from taking 40 minutes to 30 seconds. Ultimately, this one SEBI project has cleared technical debt accrued over decades, significantly reducing technical and operational risk systemically in Indian capital markets.

These boring, invisible, background updates are often far more meaningful, impactful, and directly beneficial to retail clients than most shiny frontend features.

At Zerodha, we take technical and operational debt very seriously. Constantly reducing its buildup and giving these invisible improvements as much importance, if not more, as frontend features, is our engineering philosophy. Our priority is to make the underlying systems robust and reliable for the next decade, rather than focusing on what can be released in the next quarter.
