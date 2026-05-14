---
layout: post
title: "CATP: Making AI Agent Actions Enforceable and Provable"
tags: [AI, Open Source, Agents]
author: Linfeng (Daniel) Zhou
published: true
---

AI agents are getting really good. They can browse the web, write code, execute commands, and call APIs on your behalf. But as they become more capable, a simple question becomes harder to answer: **do you actually know what your agent did?**

I've been building [CATP (Cryptographic Agent Trust Protocol)](https://github.com/lfzkoala/catp) to address this. The idea is straightforward: every action an AI agent takes should be enforceable upfront and auditable after the fact.

## The Problem

Right now, most AI agents are black boxes. You give them a task, they run, and you trust that they did what you intended. That works fine for low-stakes tasks, but as agents start touching production systems, financial transactions, or sensitive data, "trust me" isn't good enough.

What's missing is a way to:
- Set clear boundaries on what an agent is allowed to do
- Keep a reliable record of what it actually did
- Prove that behavior to someone else if needed

## What CATP Does

CATP works at two levels:

**Enforcement.** You write a simple policy file that defines what your agent can and can't do—which tools it's allowed to use, which file paths it can write to, which shell commands are blocked. CATP hooks into Claude Code and checks every action against that policy in real time. If something violates the rules, it's blocked before it happens.

**Audit.** Every action that does go through gets logged in a tamper-evident chain. You can inspect the log anytime and verify nothing was altered after the fact.

No special infrastructure needed to get started, just install the CLI and drop a policy file into your project.

## Why I Built This

The agent era is happening fast. I think the missing piece isn't more capability, it's accountability. We need tools that make agent behavior inspectable and trustworthy, not just impressive.

CATP is my attempt to build that foundation. It's open source under MIT, and I'd love contributions and feedback at [github.com/lfzkoala/catp](https://github.com/lfzkoala/catp).
