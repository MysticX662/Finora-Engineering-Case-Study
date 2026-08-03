# Finora — Product and Engineering Case Study

**Nickhil Earla — Co-Founder and Product Lead**

[Live platform](https://usefinora.com) · [Founder profile](https://usefinora.com/about) · [LinkedIn](https://www.linkedin.com/in/nickhil-earla/) · [GitHub](https://github.com/MysticX662) · [MemShield research](https://revsoc.ai/research/memshield)

This public case study explains the product, architecture, and my contribution. Finora's production source code, infrastructure configuration, and student data remain private.

## Product

Finora is an AI-powered financial education platform designed to make personal finance more adaptive, interactive, and approachable for students. The platform combines personalized lessons, knowledge checks, simulations, gamification, and an AI learning assistant with educator-facing implementation workflows.

## My Role

My work spans both hands-on engineering and product leadership:

- Designed the platform architecture and core student learning flows
- Built and integrated full-stack product systems across the frontend, database, authentication, and AI-backed services
- Converted student, parent, and educator feedback into product requirements and engineering priorities
- Broke larger systems into developer-owned components, coordinated integrations, and reviewed the completed experience as a whole
- Led major product rebuilds after user testing showed that technically functional lessons were not sufficiently engaging or easy to navigate
- Connected product decisions with school implementation, educator needs, accessibility, and institutional pilot planning
- Led the technical integration of MarginIt's acquired product and brand into Finora's gamified learning direction

## Product Systems

The platform has included work across:

- Personalized lesson and learning-path generation
- Finny, an AI financial-learning assistant
- Knowledge checks and adaptive practice
- Student progress, XP, levels, badges, and streaks
- Real-world financial scenarios and simulations
- Teacher and classroom workflows
- Mobile packaging and cross-platform delivery
- Accessibility, student-data isolation, and school deployment requirements

## Technical Architecture

```text
Student and educator interfaces
            │
            ▼
React + TypeScript application layer
            │
            ├── Interactive learning components
            ├── Gamification and progress systems
            ├── Teacher and classroom workflows
            └── Mobile delivery through Capacitor
            │
            ▼
Supabase application backend
            ├── PostgreSQL data model
            ├── Authentication and role-aware access
            ├── Storage and analytics events
            └── Edge functions for AI-backed workflows
            │
            ▼
LLM services and structured generation pipelines
            ├── Personalized lessons
            ├── Learning pathways
            ├── Knowledge checks
            └── Contextual student assistance
```

### Core technologies

- React, TypeScript, and Vite
- Tailwind CSS and component-based UI systems
- Supabase, PostgreSQL, authentication, and edge functions
- React Query and structured client-side data flows
- Capacitor for mobile deployment
- LLM-backed content and tutoring workflows

## Impact

- **1,500 registered accounts by mid-July 2026**
- **400,000+ organic views** across Finora social content
- Second place in the **TiE Dallas Young Entrepreneurs Competition**, earning Finora's initial non-dilutive funding
- Acquired the **MarginIt** product and brand for integration into Finora's gamified financial-learning experience
- Built by the original founding team of **Nickhil Earla, Ahaan Kothari, and Shaurya Saxena**

## Product-Learning Process

Finora's development was not a straight line from idea to finished application. Early versions proved that software can work exactly as designed while still failing the people using it. Student and educator testing exposed confusing navigation, fragile AI interactions, and lesson experiences that felt more like digital worksheets than something students would return to.

The product process shifted toward:

1. Observing where real users became confused or disengaged
2. Asking educators what would prevent classroom adoption
3. Turning those failures into concrete product requirements
4. Rebuilding the experience around interaction, clarity, and repeat use
5. Coordinating engineering, content, and implementation rather than treating them as separate problems

That process shaped Finora into both an engineering project and a study in human-centered product development.

## Selected Work Beyond Finora

### MemShield

Published through RevSoc Research Division, MemShield is a three-layer defensive middleware architecture for persistent memory poisoning in stateful autonomous AI agents. The project includes a 23-page white paper, reproducible evaluation code, architecture documentation, and an open-source Python implementation.

[Read the publication](https://revsoc.ai/research/memshield) · [View the repository](https://github.com/MysticX662/MemShieldResearch)

### PermitVision

Built a private full-stack opportunity-intelligence platform for Skyline Partnership, transforming public permit and property records into ranked HVAC market opportunities. The system ingested more than 211,000 permit records and produced 52,662 ranked leads with geographic heatmaps, property dossiers, deterministic scoring, and export workflows.

### FrontierBuild

Co-founded and operated a global startup-style AI competition for student builders. Built the public website, registration and submission systems, participant workflows, and supporting technical operations.

## Public Coverage

[Voyage Dallas founder profile](https://voyagedallas.com/interview/meet-nickhil-earla-ahaan-kothari-and-shaurya-saxena/) · [Coppell Student Media coverage](https://coppellstudentmedia.com/142635/studentlife/finora-levels-up-financial-literacy-for-gen-z-learners/)