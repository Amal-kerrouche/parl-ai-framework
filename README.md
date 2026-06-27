# PARL-AI: Personalized Adaptive Reinforcement Learning for AI-Augmented Learning

> **A Responsibility-Aware Reinforcement Learning Framework for Regulating Learner–Generative AI Reliance in AI-Augmented Learning**

---

## Overview

**PARL-AI (Personalized Adaptive Reinforcement Learning for AI-Augmented Learning)** is a research-oriented framework that combines **Reinforcement Learning (RL)**, **Large Language Models (LLMs)**, and **pedagogical adaptation** to personalize learner support while promoting responsible AI use.

Unlike conventional AI tutors that primarily optimize task performance, PARL-AI explicitly models **learner responsibility**, **help-seeking behavior**, and **response-use behavior** to dynamically regulate learner–AI interaction. The framework continuously adapts instructional support through reinforcement learning, progressively transferring responsibility from the AI system to the learner.

The implementation follows the conceptual framework proposed in the accompanying research paper and serves as a reproducible research prototype demonstrating responsibility-aware adaptation in AI-augmented learning environments.

---

## What PARL-AI Contributes

PARL-AI introduces five core innovations:

* **Responsibility-Aware Learner Modeling** through behavioral interaction traces.
* **Adaptive Reinforcement Learning** for selecting pedagogical interventions.
* **Dynamic Scaffolding Regulation** based on learner competence and responsibility.
* **Role-Based Pedagogical Adaptation** using Coach, Partner, and Mentor strategies.
* **Responsibility-Aware Prompt Construction** that conditions LLM responses on learner state, responsibility, selected action, and instructional role.

Together, these components enable AI systems that foster learner autonomy rather than dependency.
