---
title: "AI in Large-Scale Software Development"
date: 2026-10-15
draft: false
thumbnail: "/images/blog/2026-10-14-AI-in-large-scale-software-development-Ericsson-lesson-learned.jpg"
tags:
  - AI
  - data
  - Agentic AI
  - Software Development
  - Ericsson
---
## Lessons from Ericsson

![Ericsson team's presentation on software development using AI agents](/images/blog/2026-10-14-AI-in-large-scale-software-development-Ericsson-lesson-learned.jpg)
On Wednesday, 14 October 2026, at an event hosted by [**Blue Science Park**](https://www.bluesciencepark.se/) at **BlackBox** in Karlskrona, [**Katerina Doneva**](https://www.linkedin.com/in/katerinag/) (**System Manager**) and [**Noman Latif**](https://www.linkedin.com/in/nomanlatif/) (**Software Architect**) from Ericsson shared their experience of bringing AI Agents into the development of large-scale software-based products.

## The Scale of the Products

Ericsson is no longer just a network and antenna company; it has a large software portfolio. For example, its wallet platform is active in 24 countries and has more than 600 million active accounts. Its modernized charging and billing system, deployed at six sites in the United States, serves more than 160 million mobile subscribers.

## Why Is Adopting AI Difficult?

The problem is not the capability of the models. In large financial products, the cost of a single failure is very high, and the processes and guardrails for quality, security and scalability have been built deliberately. Thousands of developers work on interconnected parts of the product, so "starting over from scratch" is not simple. Teaching developers to use the tools was actually the easy part; enabling them across the whole organization turned out to be the hard one.

## The Four-Step Path

Ericsson's journey to AI-Agentic adoption followed four steps: identifying the right tool, getting developers to adopt it, transforming processes, and establishing a governance model. Choosing a tool in a large organization can take weeks or months, because concerns and challenges such as the risk of source code leaving the organization, measuring the value delivered, code ownership and intellectual property all need answers. Not every developer cooperates either, for various reasons such as fear of change or simply not having enough time. So the team turned to the enthusiasts in the organization (the champions), who showed their successes to others, and after a while everyone started using the tools.

## From Coding to Workflows

Despite widespread adoption of AI agents, productivity still looked low, because coding is in fact only 10 to 15 percent of the software development process. So, to achieve real transformation, they mapped the entire lifecycle of their products, identified the roles, and built agent-based support for each role (such as requirements, analysis, development, testing and so on). And of course, every new agent, like every new tool, needs change management.

## Challenges of Building Agents

- **AI-friendly artifacts:** Traditional documents (Word, PowerPoint, Excel, ...) are made for humans. Agents work better with text and Markdown, so the team built templates that both humans and agents can work with. These artifacts are the interfaces between agents in the workflow.
- **The knowledge layer:** A language model knows nothing about your company and product. The right context must be given to the agent through RAG, MCP, knowledge graphs or vector databases. Building an agent is easy, but an agent that truly delivers value needs the right context.
- **Implicit knowledge:** Part of an organization's knowledge lives only in experts' heads or in conversations. To turn this implicit knowledge into explicit knowledge, the team built skills and interactive workflows that interview the experts and turn what they know into explicit artifacts.
- **Multi-agent systems:** An orchestrator agent manages how the other agents carry out their work. The team has also created a model called the agents team (coder, tester, ...), which they are still researching and improving.

## Agent Hub

As the number of agents grew, the need to manage their lifecycle emerged. Because their tooling initially lacked this capability, they built an internal "app store" for agents, skills and steering files, with a security-review pipeline, monitoring, ratings and a user community, a governance model, semantic versioning, and retirement of unused agents.

## Key Lessons

Becoming an AI-agentic organization is neither quick nor straightforward; it is an organizational change, not merely a technology rollout, and it involves enthusiasm, skepticism, trial and error, and initiatives that pay off both quickly and slowly. Models and tools keep getting better, but organizational data is a unique competitive advantage. The winner is not the organization that has built hundreds of agents, but the one with the most structured knowledge and the best integration of its workflows.
