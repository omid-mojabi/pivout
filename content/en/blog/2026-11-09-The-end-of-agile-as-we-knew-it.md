---
title: "The End of Agile as We Knew It"
date: 2026-11-09
draft: false
thumbnail: "/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.png"
tags:
  - AI
  - Agile
  - Agentic AI
  - Embedded Systems
  - Software Development
  - DevOps
---
### Lessons from [**Software Center in Gothenburg, Sweden**](https://www.software-center.se/)

![Challenges of adapting Agile to the needs of software companies - from the paper](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.png)
For an Agilist who has worked in this field for a long time, this title may seem a bit heavy as a description of the present and future of Agile. But as we have learned in agile culture and practiced for decades, the ultimate goal of every practitioner is learning, even if all the foundations and principles we have built our work on are challenged.

### The Problem

More than two decades have passed since the publication of the [**Agile Manifesto**](https://agilemanifesto.org/), yet companies still do not experience the benefits they expected. Recently, two researchers from Software Center in Gothenburg, Sweden, showed in a [**paper**](https://doi.org/10.1016/j.jss.2026.113100) based on fourteen years of collaborative research with 14 large companies in domains such as automotive, telecommunications, manufacturing, and security and surveillance, as well as a series of workshops held in 2024, that there is a mismatch between the original Agile principles and the reality of large-scale product development, and of embedded systems in particular. These systems are typically a combination of mechanics, electronics, software, and artificial intelligence.

### Digging into the Root Cause

The Agile Manifesto was written by a group of software engineers who mostly built custom software for a specific, accessible customer. The companies studied in this research, however, are in a completely different situation: many customers, many teams, and many products, with shared components. According to the authors, the problem is not inside agile teams but in scaling the work beyond the team level. Product management, systems engineering, and business models, which are the mechanisms companies use to scale, are absent from Agile. Frameworks such as SAFe did not make a difference either, according to one of the interviewees: "We adopted SAFe, but nothing changed."

### Key Challenges

- **Definitions and interpretations**: no shared definition of Agile; regulatory and certification constraints that generally assume waterfall-style software development; lack of adaptation to the context; and goals getting mixed up with the effort to improve agility in the product development process.
- **Business models and monetization**: the "why" and the "what" being forgotten because of too much focus on the "how"; business models that do not fit continuous delivery; and the ineffectiveness of MVPs in products that must be complete in every iteration in order to pass quality and functionality tests.
- **Waterfall and hardware-centric mindset in system design**: perfectionism in system design and engineering, difficulty decoupling teams, and lack of trust.
- **Organizational culture**: serious challenges in creating a coordinated rhythm between software development and other parts of the organization, such as support and sales, caused by frequent releases throughout the product lifetime; inconsistencies in governance and regulatory compliance; lack of short feedback loops in a B2B context; and failure to scale the way of working beyond the team level.

### Developing Systems Through the RADICAL Lens

The authors also propose a conceptual (and as yet untested) framework called RADICAL. Unlike much academic work that offers improvements to earlier methods (here, Agile), they fundamentally argue that something should replace Agile rather than complement it. In this proposed framework, seven principles are derived and described as requirements of an alternative paradigm: Responsive, Architecture, Data-driven, Integrated cross-functional alignment, Continuous, Aligned on business goals, and Leadership.

### Limitations

The RADICAL framework is currently only an initial proposal and has not yet been validated, and the findings mainly apply to embedded systems in large companies. This gives us, as practitioners in software, room to take a critical look at current ways of working in our teams and organizations, to lay the groundwork for a fundamental rethink that suits the business and industry we work in, and to end the long effort of adapting everything to Agile principles. The research was also conducted in the context of large companies and organizations in Northern Europe and Scandinavia, so caution is needed when generalizing the findings to other places or to pre-scale environments such as startups.
