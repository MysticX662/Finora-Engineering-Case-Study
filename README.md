# Finora — Product and Engineering Case Study

> Public case study only. Finora's production source code, infrastructure configuration, and student data are private.

[Live platform](https://usefinora.com) · [Voyage Dallas profile](https://voyagedallas.com/interview/meet-nickhil-earla-ahaan-kothari-and-shaurya-saxena/) · [Coppell Student Media coverage](https://coppellstudentmedia.com/142635/studentlife/finora-levels-up-financial-literacy-for-gen-z-learners/)

## Product

Finora is an AI-powered financial education platform designed to make personal finance more adaptive, interactive, and approachable for students. The platform combines personalized lessons, knowledge checks, simulations, gamification, and an AI learning assistant with educator-facing implementation workflows.

## My Role

**Nickhil Earla — Co-Founder and Product Lead**

My work spans both hands-on engineering and product leadership:

- Designed the platform architecture and core student learning flows
- Built and integrated full-stack product systems across the frontend, database, authentication, and AI-backed services
- Converted student, parent, and educator feedback into product requirements and engineering priorities
- Broke larger systems into developer-owned components, coordinated integrations, and reviewed the completed experience as a whole
- Led major product rebuilds after user testing showed that technically functional lessons were not sufficiently engaging or easy to navigate
- Helped connect product decisions with school implementation, educator needs, and institutional pilot planning
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

## Dated Impact

To keep public metrics precise, figures are defined by what they measure:

- **1,500 registered accounts by mid-July 2026**
- **400,000+ organic views** across Finora social content
- Original founding team of **Nickhil Earla, Ahaan Kothari, and Shaurya Saxena**
- Second place in the TiE Dallas Young Entrepreneurs competition, which provided Finora's initial non-dilutive funding
- Product and brand acquisition of **MarginIt** for integration into Finora's gamified financial-learning experience

Registered accounts are not presented as monthly active users or completed learners. Program, pilot, and engagement metrics should be reported separately when finalized.

## Product-Learning Process

Finora's development was not a straight line from idea to finished application. Early versions proved that software can work exactly as designed while still failing the people using it. Student and educator testing exposed confusing navigation, fragile AI interactions, and lesson experiences that felt more like digital worksheets than something students would return to.

The product process shifted toward:

1. Observing where real users became confused or disengaged
2. Asking educators what would prevent classroom adoption
3. Turning those failures into concrete product requirements
4. Rebuilding the experience around interaction, clarity, and repeat use
5. Coordinating engineering, content, and implementation rather than treating them as separate problems

That process shaped Finora into both an engineering project and a study in human-centered product development.

## Privacy and Source Availability

This repository intentionally contains no production code, API keys, database schemas containing student information, internal partnership documents, or private school data. Technical details are presented at the system level to explain the work without exposing proprietary implementation or user information.
