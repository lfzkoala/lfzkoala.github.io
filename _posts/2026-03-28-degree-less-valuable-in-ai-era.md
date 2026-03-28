---
layout: post
title: "Do You Really Need a Cryptography PhD in the AI Era?"
tags: [AI, cryptography, education, career]
author: Linfeng (Daniel) Zhou
---

In 2015, someone invited me to join a crypto startup instead of pursuing a PhD. They told me directly that the value of an academic degree was going to decline. I didn't get it at the time. The credential felt important, the path felt legitimate, and the startup felt risky. So I kept going.

That startup became Dfinity, the team behind ICP.

I'm writing this because I think about that moment a lot, and because the argument that person was making is even more true today than it was then.

## Why the PhD made sense

Cryptography is genuinely hard. The underlying math, elliptic curves, lattice theory, information-theoretic security proofs, takes years to internalize properly. For a long time, a PhD was the most reliable path into serious crypto work: ZK proof systems, MPC protocols, threshold signatures. The field was esoteric, the literature was dense, and there were few shortcuts.

A PhD gave you structured immersion in that math, access to unpublished work and conference circuits, and the credibility to get hired at the handful of labs actually pushing the frontier. The credential was a reasonable proxy for rigorous thinking. There weren't many other ways to get that signal.

## What's changed

Two things are compressing the on-ramp into cryptography.

**The tooling has matured.** Libraries like Arkworks, Halo2, and Circom have abstracted away enough implementation complexity that you can build real ZK systems without deriving everything from first principles. The gap between understanding the math and shipping a working circuit has narrowed significantly.

**AI has become an exceptional tutor for dense technical material.** Papers that used to take weeks to parse can now be worked through interactively. You can ask a frontier model to walk you through a security proof, flag the assumptions, and surface related work, all in real time. This doesn't replace deep understanding, but it dramatically lowers the activation energy to get there.

The knowledge that used to require 5 years of PhD training can increasingly be acquired in 12 to 18 months of focused self-directed work, if you're disciplined and already technically strong.

## The costs the brochure doesn't mention

The direct costs of a cryptography PhD are obvious enough: 5 to 6 years of prime working time, below-market stipends, and entry into an academic job market that is structurally shrinking. But the hidden costs are what I'd want someone to think harder about.

**The low-hanging fruit is gone.** Many of the fundamental problems in cryptography have already been solved. The space of genuinely meaningful PhD topics is narrowing. You can spend years on something that feels important from inside academia and emerge to find the field has moved on, or that the problem wasn't as consequential as it looked.

**Your advisor is a single point of failure.** The student-advisor relationship is one of the most asymmetric in professional life. If your advisor is mediocre, distracted, or steering you in the wrong direction, there is very little you can do about it. I experienced this firsthand. A bad advisor doesn't just slow you down; they can push you toward dead ends, and you may not realize it until years have passed.

**You can get scooped.** Cryptography is a small world. Multiple research groups often work on the same open problems at the same time. You can spend two years on a result, only to find that another team published it first. Your work becomes a footnote, or disappears entirely. In industry, parallel development often has upside. In academia, it can invalidate years of effort with no recourse.

**The crypto industry moves faster than academic cycles.** ZK technology in 2026 barely resembles where it was in 2022. A research direction that looked important when you enrolled can be irrelevant, or already solved, by the time you graduate.

## The alternative path

The crypto ecosystem is unusually meritocratic. Audit firms, protocol teams, and ZK startups hire based on demonstrated work: GitHub contributions, CTF results, published circuits, audit reports. The credential matters far less than what you've actually built.

Suppose you spend 5 years in a PhD program studying lattice-based cryptography. Alternatively, you spend those same years working through the Halo2 and Plonky3 codebases, competing in ZK CTFs like ZKHack, doing security audits at firms like Zellic or Trail of Bits, and shipping a real ZK application end to end.

By year 5, the second path likely gets you hired at any serious crypto team, with broader pattern recognition, a public track record, and none of the institutional baggage.

## When the PhD still makes sense

There are real exceptions. If you want to work on truly foundational research, new proof systems, post-quantum constructions, formal security models, that work still happens primarily in academia and a small set of deep research labs. The credential and the academic network genuinely matter there. Same if you want to be a professor, publish in top venues, or work at the rare research role that still filters on PhDs.

But if your goal is to build protocols, work at a ZK startup, do security research in industry, or contribute to open-source crypto infrastructure, the PhD is no longer the only route, or even the fastest one.

## What I'd tell my 2015 self

The person who warned me in 2015 was right. I just wasn't ready to hear it. The crypto industry was early enough then that showing up and building would have compounded enormously. Instead I spent those years inside a system that, as I later learned, could saddle you with a bad advisor, a narrowing research topic, and the constant risk of getting scooped.

If you're deciding whether to pursue a cryptography PhD, ask the honest version of the question: do you want to do foundational research at the academic frontier, or do you want to build real systems in the crypto ecosystem?

Those are different paths. The PhD still makes sense for the first. For the second, the fastest route is no longer through a university, and it hasn't been for a while.

---

*Personal views, not career advice. Think for yourself.*
