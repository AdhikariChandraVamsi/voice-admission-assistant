# Voice-Based University Admission Assistant

## Overview
This project is a **voice-first, multilingual AI admission assistant** designed to help students and parents clearly understand and complete a complex university admission preference process.

The system focuses on **clarity, correctness, and accessibility**, especially for users who are not fluent in English.  
It does **not** make admission decisions or predictions.

This project is developed as part of the **Build2Break Hackathon** under the **EdTech domain**.

---

## Problem Statement
University admission workflows often involve:
- Multiple programs and campuses
- Priority-based preference ordering
- Fee slabs and sliding/reallocation rules

These concepts are usually explained through English-heavy portals, leading to:
- Misunderstood preferences
- Incorrect submissions
- Heavy reliance on manual admission support

Our goal is to simplify this process using a **natural voice-based AI agent** that guides users step-by-step.

---

## Key Objectives
- Hold a **natural, multi-turn voice conversation**
- Explain admission concepts in **simple language**
- Collect preferences **incrementally**, not all at once
- Handle interruptions, corrections, and missing data
- Invoke backend tools/APIs to store and validate preferences
- Provide a clear **confirmation summary**

---

## What the System Does NOT Do
- No real student data
- No real payments
- No seat allocation or cutoff prediction
- No admission outcome decisions

---

## High-Level Architecture

User (Voice)
↓
Voice Interface (STT / TTS)
↓
Conversation Orchestrator (AI Agent)
↓
Rules & Validation Engine
↓
Backend API / Storage


### Components
- **Voice Interface**: Handles speech-to-text and text-to-speech
- **AI Agent**: Manages conversation flow and intent handling
- **Validation Layer**: Ensures preferences are consistent and complete
- **Backend API**: Stores preferences and generates confirmation summaries

---

## Repository Structure

voice-admission-assistant/
├── backend/ # API, rules engine, data handling
├── frontend/ # UI / voice interface components
├── docs/ # Architecture and design documentation
├── .gitignore
└── README.md


---

## Setup Instructions

### Prerequisites
- Git
- Docker & Docker Compose (recommended)

### Clone the Repository
```bash
git clone https://github.com/AdhikariChandraVamsi/voice-admission-assistant.git
cd voice-admission-assistant
docker compose up --build


---

## STEP 2: Commit and push README

```bash
git add README.md
git commit -m "Add judge-ready README with architecture and setup"
git push origin develop

