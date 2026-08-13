# Finora — Engineering & Product Case Study

> **Public product and engineering case study for Finora, an AI-powered financial education platform.**

[![Website](https://img.shields.io/badge/Platform-usefinora.com-blue)](https://usefinora.com)
[![Status](https://img.shields.io/badge/Production-Active-brightgreen)](https://usefinora.com)

---

## Product Overview

Finora is a gamified financial-literacy platform for students, educators, schools, and youth programs. It combines short lessons, knowledge checks, simulations, progress systems, an AI educational assistant ("Finny"), and educator-facing workflows.

- **Live platform:** [usefinora.com](https://usefinora.com)
- **Current footprint (August 2026):** 2,000+ registered accounts and 400,000+ organic views
- **Implementation:** City of Irving youth financial-literacy launch, one school deployment, and five additional testing/pilot groups

The metrics above describe separate measures. Registered accounts are not presented as active users, and organic views are not presented as product usage.

---

## My Role — Co-Founder & Product/Engineering Lead

As **Co-Founder & Product/Engineering Lead**, I work across product architecture, engineering, testing, and implementation.

- **Platform architecture:** React + TypeScript frontend with Supabase/PostgreSQL backend systems
- **Core systems:** Authentication, lessons/progress, gamification, simulations, AI-assisted learning, and educator workflows
- **Product iteration:** Led two major rebuilds after testing with students, parents, and educators exposed usability and engagement problems
- **Execution:** Translated feedback into specifications and coordinated engineering, content, and outreach contributors
- **Integration:** Led technical integration of MarginIt’s acquired product and brand into Finora

---

## High-Level Architecture

```text
[ React + TypeScript Client ]
            |
            v
[ Supabase Platform Layer ]
  - Authentication
  - PostgreSQL
  - Row Level Security
  - Server / edge functions
            |
            v
[ AI / Learning Service Layer ]
  - Educational prompt workflows
  - Adaptive lesson and scenario logic
  - Safety and fallback handling
```

### Technology Stack

- **Frontend:** React, TypeScript, Vite
- **Backend & database:** Supabase, PostgreSQL, Row Level Security
- **AI / services:** LLM-backed service workflows and server/edge functions
- **Deployment:** Vercel and Supabase

---

## Core Product Systems

### Learning paths and micro-lessons
Short modules covering budgeting, saving, credit, investing basics, debt, and related personal-finance concepts, with knowledge checks and progression systems.

### Finny AI
Contextual educational explanations tied to student questions and scenarios, with guardrails intended to keep responses educational rather than individualized financial advice.

### Simulations and applied practice
Scenario-based financial decisions and interactive practice designed around real-world choices.

### Educator workflows
Tools for organizing learning and reviewing progress, designed to fit into existing classroom and youth-program routines.

---

## Product Lessons

1. **A technically functional product can still fail a user test.** Early versions exposed places where the intended flow did not match how people naturally used the product.
2. **EdTech has to fit existing routines.** Product decisions increasingly prioritize short lessons, clear progress, and educator workflows rather than assuming students will adopt another standalone tool.
3. **AI needs product boundaries.** AI-assisted learning is paired with structured logic, safety constraints, and fallback behavior rather than treated as the entire product.
4. **Institutional requirements shape architecture.** Access control, minimal-data practices, and educator workflows are treated as product requirements.

---

## Links

- **Live platform:** [usefinora.com](https://usefinora.com)
- **About / team:** [usefinora.com/about](https://usefinora.com/about)

This repository is a public case study and does not expose Finora’s production source code.