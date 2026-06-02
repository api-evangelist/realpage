---
title: 'Lumina AI Screen Share: Trusted, Responsible AI'
url: https://www.realpage.com/blog/lumina-ai-screen-share-trust-governance/
date: '2026-05-25'
author: Harish Desai
feed_url: https://realpage.com/blog/feed
---
How Lumina AI Screen Share Was Built to Earn Trust
By Harish Desai, SVP, Data and Applications & Kris Kimmerle, VP, AI Risk and Governance
(6-minute read)
OpenAI published a case study on our collaboration to build Lumina AI Screen Share, RealPage’s real-time, voice-enabled AI assistant designed for property management workflows. Among early adopters, 95% of issues are self-contained by users engaging with Lumina AI Screen Share agent. Average resolution time is under five minutes. 90% report stronger workflow confidence across their site teams.
Those results matter. We want to talk about the decisions we made to earn the right to ship it.
 
What Is AI Screen Sharing and How Lumina AI Screen Share Works Picture a site team member walking through a lease renewal in OneSite for the first time. Instead of toggling between help articles and the application, they have a voice in their ear that sees their screen, understands where they are in the workflow, and talks them through the next step. That is Lumina AI Screen Share.
It is an AI agent built on OpenAI’s Agents SDK with Realtime Voice models, communicating through WebRTC. It sees what the user sees on their screen, retrieves relevant guidance from our product knowledge base, and coaches the user through the workflow step by step. In real time, with voice.
The agent watches, listens, and guides. When someone is navigating a payment setup or figuring out how to process a move-in, it identifies where the user is in the workflow and provides contextual next steps grounded in documented procedures.
That is what “agentic AI” means in practice. A specific architecture with specific capabilities and, critically, specific constraints.
What Lumina AI Screen Share Agent Does Not Do
Every important design decision in Lumina AI Screen Share is grounded in what the agent is not allowed to do. The agent operates entirely at the UI layer, observing what is rendered in the browser and providing guidance based on that cont...
