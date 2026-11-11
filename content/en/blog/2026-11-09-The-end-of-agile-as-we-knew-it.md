---
title: "The End of Agile as We Knew It"
date: 2026-11-09
draft: false
thumbnail: "/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.jpg"
tags:
  - AI
  - Agile
  - Agentic AI
  - Embedded Systems
  - Software Development
  - DevOps
---
### Lessons learned from Software Center in Gothenburg, Sweden

![The end of Agile - selected from Forbes magazine](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.jpg "The end of Agile - selected from Forbes magazine")

For an Agilist who has worked in this field for a long time, this title may seem a bit heavy as a description of the present and future of Agile. But as we have learned in agile culture and practiced for decades, the ultimate goal of every practitioner is learning, even if all the foundations and principles we have built our work on are challenged.

### The Problem

More than two decades have passed since the publication of the [**Agile Manifesto**](https://agilemanifesto.org/), yet companies still do not experience the benefits they expected. Recently, two researchers from [**Software Center in Gothenburg, Sweden**](https://www.software-center.se/), showed in a [**paper**](https://doi.org/10.1016/j.jss.2026.113100) based on fourteen years of collaborative research with 14 large companies in domains such as automotive, telecommunications, manufacturing, and security and surveillance, as well as a series of workshops held in 2024, that there is a mismatch between the original Agile principles and the reality of large-scale product development, and of embedded systems in particular. These systems are typically a combination of mechanics, electronics, software, and artificial intelligence.

### Digging into the Root Cause

The Agile Manifesto was written by a group of software engineers who mostly built custom software for a specific, accessible customer. The companies studied in this research, however, are in a completely different situation: many customers, many teams, and many products, with shared components. According to the authors, the problem is not inside agile teams but in scaling the work beyond the team level. Product management, systems engineering, and business models, which are the mechanisms companies use to scale, are absent from Agile. Frameworks such as SAFe did not make a difference either, according to one of the interviewees: "We adopted SAFe, but nothing changed."

![Challenges of adapting Agile to the needs of software companies - from the paper](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.png "Challenges of adapting Agile to the needs of software companies - from the paper")

### Key Challenges

- **Purpose**: no clear, shared definition of Agile; goals and means getting mixed up; the "why" and the "what" being forgotten because of too much focus on the "how"; and mismatch with the rest of the company, such as support and sales, caused by frequent releases throughout the product lifetime.
- **Deliver value continuously**: under increasing regulatory constraints, how difficult it is to shift from traditional business models and how end-to-end delivery of features is still challenging and Agile practices have done little to alleviate.
- **Superset platform**: Platforms that contain all the features of a system, both software and non-software, so that each product is in practice just a configuration of the platform with more or fewer features. This idea solves many problems, including the waterfall mindset in design, MVPs that can be tested before delivery, internal dependencies, and customization, and it makes teams responsive. However, current agile ways of working do little about it and leave its implementation in practice to the teams themselves.
- **Learning loops**: Traditionally, companies built features that were either realized or not. Today, focus is shifting toward capabilities with quantitative KPIs, and iterative deployment lets companies experiment and measure impact. Teams aim to improve capabilities rather than build endless lists of features customers do not use, as often happens in agile today.
- **AI first**: an increasing number of tasks are being designed to maximize the use of artificial intelligence capabilities, with human involvement introduced only when this approach fails to deliver satisfactory results. This is a technology that, at the time the Agile concept was introduced, had no practical role in industry and was not given much consideration.
- **Cross-functional teams**: mismatch in governance and regulatory compliance; failure to scale the way of working beyond teams; and lack of adaptation to the context.
- **Data as infrastructure**: Data has played a significant role for decades in companies. However, much of that data is collected, stored and used in silos and optimized for specific use cases and this is often enforced in agile organizations too where teams collect and use data for a specific feature and for their own use.

![RADICAL perspective on systems engineering  - from the paper](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it-Radical-framework.png "RADICAL perspective on systems engineering  - from the paper")

### System Engineering Through the RADICAL Lens

The authors also propose a conceptual (and as yet untested) framework called RADICAL. Unlike much academic work that offers improvements to earlier methods (here, Agile), they fundamentally argue that something should replace Agile rather than complement it. In this proposed framework, seven principles are derived and described as requirements of an alternative paradigm: Responsive, Architecture, Data-driven, Integrated cross-functional alignment, Continuous, Aligned on business goals, and Leadership.

### Limitations

The RADICAL framework is currently only an initial proposal and has not yet been validated, and the findings mainly apply to embedded systems in large companies. This gives us, as practitioners in software, room to take a critical look at current ways of working in our teams and organizations, to lay the groundwork for a fundamental rethink that suits the business and industry we work in, and to end the long effort of adapting everything to Agile principles. The research was also conducted in the context of large companies and organizations in Northern Europe and Scandinavia, so caution is needed when generalizing the findings to other places or to pre-scale environments such as startups.

[**Link to Original Paper**](https://doi.org/10.1016/j.jss.2026.113100)
