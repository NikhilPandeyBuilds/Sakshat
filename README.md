# Sakshat

> AI-powered adaptive technical interview assessment platform that evaluates what candidates claim on their resumes against what they can actually demonstrate.

Sakshat is an intelligent interview assessment platform designed to make technical interviews more structured, adaptive, and evidence-driven.

Instead of treating an interview as a fixed sequence of questions, Sakshat builds an understanding of the candidate from their resume, identifies claimed skills and competencies, conducts an adaptive technical interview, evaluates responses, and produces a structured assessment of the candidate's demonstrated capabilities.

The central idea behind Sakshat is simple:

> **Don't evaluate a candidate only by what their resume claims. Evaluate what they can actually demonstrate.**

---

## Table of Contents

- [Overview](#overview)
- [The Problem](#the-problem)
- [The Sakshat Approach](#the-sakshat-approach)
- [How Sakshat Works](#how-sakshat-works)
- [Core Features](#core-features)
- [1. Resume Intelligence](#1-resume-intelligence)
- [2. Candidate Skill & Competency Profile](#2-candidate-skill--competency-profile)
- [3. Adaptive Interview Engine](#3-adaptive-interview-engine)
- [4. Multi-Source Question Generation](#4-multi-source-question-generation)
- [5. Answer Evaluation](#5-answer-evaluation)
- [6. Claim vs Demonstrated Analysis](#6-claim-vs-demonstrated-analysis)
- [7. Dynamic Difficulty Adjustment](#7-dynamic-difficulty-adjustment)
- [8. Communication Analysis](#8-communication-analysis)
- [9. Competency-Level Assessment](#9-competency-level-assessment)
- [10. Interview Assessment Report](#10-interview-assessment-report)
- [Interview Intelligence Pipeline](#interview-intelligence-pipeline)
- [Example Interview Flow](#example-interview-flow)
- [Data Model](#data-model)
- [System Architecture](#system-architecture)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Running the Application](#running-the-application)
- [Production Build](#production-build)
- [Example Assessment](#example-assessment)
- [Why Sakshat](#why-sakshat)
- [Design Principles](#design-principles)
- [Limitations](#limitations)
- [Future Scope](#future-scope)
- [Project Status](#project-status)
- [Team](#team)
- [Disclaimer](#disclaimer)

---

# Overview

Traditional technical interviews often depend heavily on:

- Resume screening
- Fixed interview questions
- Subjective interviewer judgement
- Limited interview time
- Manual evaluation
- Candidate self-reported skills

A resume can demonstrate that a candidate has listed a particular technology, framework, project, or competency.

However, a resume does not necessarily demonstrate the candidate's actual depth of understanding.

Sakshat attempts to close this gap.

The platform uses the candidate's resume as a starting point and then evaluates whether the candidate can demonstrate the knowledge and reasoning associated with the skills they claim.

The system can build an interview around multiple dimensions, including:

- Resume claims
- Technical competencies
- Company-oriented interview style
- Previous answers
- Difficulty level
- Candidate performance

The result is an adaptive assessment rather than a static questionnaire.

---

# The Problem

## The Resume-Interview Gap

One of the fundamental challenges in technical hiring is the gap between:

**What a candidate claims**

and

**What a candidate can demonstrate.**

For example, a candidate may list:

```text
Python
PyTorch
Machine Learning
Deep Learning
Computer Vision
