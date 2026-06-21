# SmartTutor AI

### Personalized Learning & Doubt-Solving Agent

## Overview

SmartTutor AI is a production-grade AI learning assistant designed to provide personalized tutoring, adaptive quizzes, intelligent study planning, and long-term learning memory.

The platform leverages Mastra for multi-agent orchestration, Qdrant for semantic memory retrieval, and Enkrypt AI for safety and evaluation.

Built for the HiDevs × Mastra Hackathon 2026.

---

# Problem Statement

Students often struggle with:

* Generic learning experiences
* Lack of personalized academic support
* Poor revision planning
* Difficulty identifying weak concepts
* No long-term learning memory

Traditional chatbots answer questions but fail to remember previous learning interactions.

---

# Solution

SmartTutor AI acts as a personalized AI tutor that:

* Solves doubts
* Remembers learning history
* Generates adaptive quizzes
* Detects weak topics
* Creates study plans
* Tracks progress
* Ensures safe AI responses

---

# Key Features

### AI Tutor Agent

Provides personalized explanations based on student learning level.

### Quiz Agent

Generates topic-specific quizzes and assessments.

### Study Planner Agent

Creates personalized study schedules.

### Progress Analyzer Agent

Tracks student performance over time.

### Memory Agent

Stores and retrieves learning history using Qdrant.

### Safety Evaluation

Validates responses using Enkrypt AI.

---

# Architecture

Student
→ Frontend (Next.js)

→ Backend API (Node.js)

→ Mastra Orchestrator

→ Tutor Agent

→ Quiz Agent

→ Planner Agent

→ Progress Agent

→ Qdrant Memory Layer

→ Enkrypt AI Safety Layer

→ Final Response

---

# Mandatory Technology Stack

## Mastra

Used for:

* Agent orchestration
* Workflow execution
* Task routing
* Multi-agent collaboration

## Qdrant

Used for:

* Long-term memory
* Semantic search
* Retrieval-Augmented Generation (RAG)
* Context storage

## Enkrypt AI

Used for:

* Hallucination detection
* Toxicity screening
* Bias detection
* Safety evaluation

---

# Tech Stack

Frontend:

* Next.js
* TypeScript
* Tailwind CSS

Backend:

* Node.js
* Express

Database:

* PostgreSQL

Vector Database:

* Qdrant

Agent Framework:

* Mastra

AI Safety:

* Enkrypt AI

Deployment:

* Vercel
* Docker
* AWS

---

# Project Workflow

1. Student asks a question.
2. Mastra routes request.
3. Qdrant retrieves context.
4. Appropriate agent executes task.
5. Enkrypt AI validates output.
6. Response delivered.
7. Learning history stored.

---

# Expected Impact

* Personalized learning experience
* Improved concept retention
* Better exam preparation
* Reduced learning gaps
* Safe and trustworthy AI tutoring

---

# Future Enhancements

* Voice Tutor
* PDF Learning Assistant
* Multilingual Learning
* AI Career Guidance
* Smart Revision Planner

---

# Team

Team Name: [Your Team Name]

Hackathon:
HiDevs × Mastra Hackathon 2026

Project:
SmartTutor AI – Personalized Learning & Doubt-Solving Agent
