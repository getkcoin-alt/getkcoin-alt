# Hey, I'm Karnveer 👋

I’m a software developer from India who enjoys building things that actually get used.

Most of my work is around backend systems, automation, APIs, AI tools, internal software, and products that replace repetitive manual work. I usually start with a messy real-world problem and keep simplifying it until there’s something useful running in production.

I work mostly with **Python, FastAPI, Django, Node.js, PostgreSQL, Redis, Supabase, React, Railway and Vercel**.

Right now, I’m spending a lot of time on AI systems that can do more than just generate text — systems that can understand context, use tools, make bounded decisions, and still keep a human in control where it matters.

## What I'm working on now

### Project CANOPY
I’m currently building **CANOPY** for the **AI Builder Cup 2026**.

The idea is to connect AI with real environmental signals and make the output useful in the physical world.

The basic loop is:

**Observe → Understand → Decide → Act → Verify**

For the competition version, I want to keep it practical: take real environmental input, understand what is happening with Gemini, suggest or trigger an action, and then check whether that action actually helped.

I’ll publish the competition repository separately as the build progresses.

## A few things I've built

### Scrappy OS
An AI-native control layer for Linux.

It focuses on planning, typed tools, permissions, approvals, memory, verification and audit logs instead of giving an AI unrestricted access to a machine.

https://github.com/getkcoin-alt/-scrappy-os

### Vault Zeta 🌠
This one is harder to explain in one line.

**Vault Zeta is the continuity layer I want future AI systems to grow around** — somewhere between persistent memory, system state, identity continuity and a long-term record of what an AI has learned, decided and become.

Some of it is already real, not just a diagram.

The current implementation direction includes:
- episodic, semantic, procedural, failure, entity and preference memory
- provenance and confidence attached to memory
- source fingerprints so old knowledge can be marked stale when the source changes
- hybrid retrieval using lexical search, optional embeddings, entities, scope and recency
- durable mission snapshots and an append-only event journal
- resumable task graphs
- typed pause, resume, correction and priority-change events while a mission is running

The important part is that memory does **not** become permission. Remembering that a user once approved something is not authority to do it again.

Long term, I think continuity will matter just as much as raw model intelligence.

So yes, internally I sometimes call Vault Zeta **the daddy of the future** 😅🌠

I’m separating it into something people can inspect and contribute to instead of keeping the idea buried inside larger projects.

### Scrappy Forge
Scrappy Forge is the other hand.

It’s a local-first terminal coding agent I’ve been building around an execution loop, context compaction, persistent project memory, permission-aware tools, plugins, MCP connections, verification and recovery.

The point is not to make another chatbot that writes code snippets. I want it to inspect a real project, work through a task, use tools, verify what changed, and leave enough evidence that I can understand what it actually did.

There is already an **early-access build** you can inspect and install:

https://forge-hub-production.up.railway.app

The source repo is still private while I clean up the contribution/release surface. I plan to open it once the public-repo basics are in place and the current CI situation is clean.

**#iykyk**

### DumperTrack
A transport management system for trips, vehicles, expenses, partners and financial tracking.

https://github.com/getkcoin-alt/Bumper

### Karnveer's Command Center
A public overview of my work, projects and engineering background.

https://github.com/getkcoin-alt/karnveers-command-center

## The kind of work I like

- AI automation
- backend systems and APIs
- agent/tool orchestration
- workflow automation
- internal business software
- SaaS products
- integrations and webhooks
- scraping and browser automation
- deployment and production debugging

I care a lot about the part after the demo too — permissions, failures, logs, recovery, deployment, and whether the system still works when something unexpected happens.

Most of my repos started with a real problem, not a portfolio checklist.

## Outside the code

I’m interested in where AI, software and the physical world meet — especially systems that can help people make better decisions without removing human responsibility.

That is also the direction behind CANOPY.

## Find me

- Website: https://karnveer.com
- LinkedIn: https://in.linkedin.com/in/karnveer-singh-sonigara-3b0518286
- Email: karnveer@scriza.in
