# Finora — Engineering & Product Case Study

> **Product and engineering case study for Finora, an AI-powered financial education platform.**

[![Website](https://img.shields.io/badge/Platform-usefinora.com-blue)](https://usefinora.com)
[![Status](https://img.shields.io/badge/Production-Active-brightgreen)](https://usefinora.com)

---

## Source-code availability

> **Notice:** Finora’s production source code, internal infrastructure, user data, and partner information remain private. This repository is a public engineering and product case study containing only sanitized materials approved for public presentation.

---

## Executive Summary & Product Overview

Finora is an interactive financial-literacy platform designed to help students master real-world money management. Traditional financial education often relies on static textbooks or generic lectures. Finora bridges this gap by combining modular curriculum with an interactive AI assistant ("Finny") that adapts scenario difficulties and guidance based on student performance.

- **Target Audience**: High school students, educators, and youth financial programs.
- **Core Value Proposition**: Gamified micro-lessons, adaptive real-world budget simulations, and automated progress analytics for educators.
- **Live Site**: [https://usefinora.com](https://usefinora.com)

---

## My Role & Technical Leadership

I am the **Founder and Lead Product Architect** of Finora. In this capacity, I:
- **Architected the Platform**: Designed the frontend architecture (React + TypeScript + Vite) and backend data layer (Supabase + PostgreSQL).
- **Engineered AI Integration**: Developed the prompt pipelines and adaptive difficulty system powering Finny.
- **Implemented Core Workflows**: Built user authentication, interactive budgeting components, gamification state management, and educator reporting tools.
- **Iterated on User Feedback**: Conducted pilot feedback sessions with educators and students to refine UI/UX accessibility.

---

## High-Level Architecture & Tech Stack

```
   [ React + TypeScript Client ]
               │
      (REST / WebSockets)
               ▼
   [ Supabase Platform Layer ]
   ├── Authentication (JWT / RLS)
   ├── PostgreSQL Database (UserData, Lessons, Progress)
   └── Edge Functions (AI Prompt Processing & Safety Filters)
               ▼
   [ AI Service Layer ] (Adaptive Scenario Engine)
```

### Technology Stack
- **Frontend**: React, TypeScript, Vite, CSS Modules
- **Backend & Database**: Supabase, PostgreSQL, Row Level Security (RLS)
- **AI & Analytics**: Edge Functions, Guardrailed LLM Scenarios
- **Deployment**: Vercel, Supabase Platform

---

## Core Product Features & Workflow Analysis

### 1. Student Dashboard & Learning Paths
- Bite-sized modules covering credit scores, budgeting, saving, investing basics, and debt management.
- Dynamic streak tracking, experience points (XP), and milestone badges to encourage continuous engagement.

### 2. Interactive AI Assistant ("Finny")
- Provides contextual explanations when students make decisions in financial simulations.
- Implements safety guardrails to ensure advice remains strictly educational and age-appropriate.

### 3. Financial Simulations & Scenario Builder
- Real-world decision branching (e.g., choosing insurance plans, managing unexpected emergency expenses).
- Instant financial feedback showing long-term net worth impact based on daily choices.

### 4. Educator Workflow & Classroom Analytics
- Class roster management with anonymized progress tracking.
- Insights into topic mastery rates across different modules to help teachers identify where students need extra support.

---

## Technical Challenges & Tradeoffs

| Challenge | Engineering Approach | Tradeoff / Outcome |
| :--- | :--- | :--- |
| **Real-time AI Guidance Latency** | Utilized lightweight Edge Functions with pre-warmed prompt templates. | Reduced latency to ~600ms while maintaining safety guardrails. |
| **Stateful Simulation Persistence** | Designed normalized PostgreSQL tables with client-side state caching. | Prevents loss of progress during multi-step budgeting scenarios. |
| **Student Data Privacy** | Strict Supabase Row-Level Security (RLS) policies and minimal PII collection. | Ensures district compliance and zero leakage across student accounts. |

---

## Lessons Learned & Future Development

1. **Simplicity Over Complexity in EdTech UI**: Micro-interactions and immediate feedback drive significantly higher completion rates than dense text lessons.
2. **Deterministic Fallbacks for AI**: Always pair AI responses with deterministic fallback rules to handle edge cases or service interruptions seamlessly.
3. **School District Requirements**: Building privacy-first architecture from day one simplifies future institutional deployment.

---

## Links & Reference

- **Official Website**: [https://usefinora.com](https://usefinora.com)
- **About & Leadership**: [https://usefinora.com/about](https://usefinora.com/about)
