# Improving the Scanpy Landing Page Through HCI Principles
[![Status](https://img.shields.io/badge/status-Completed-brightgreen)](#)  ![Last updated](https://img.shields.io/badge/last%20updated-2025--12--10-blue)

---
Exploring how the landing page of scanpy can be stuctured for better usability.
- DISCLAIMER: This is a speculative redesign based off of personal experience and informal conversations with peers. No offical user testing or validation was conducted for the purpose of this activity.


## Table of contents
- [Project Brief Slides](#overview)
- [What is Scanpy?](#painpoints)
- [How I did it?](#painpoints)
- [Observed Painpoints](#painpoints)
- [Design Process](#painpoints)
   - [Understanding the Audience through my knowledge](#painpoints)
   - [Ways to reduce cognitive overload through navigation](#painpoints)
   - [Rough Sketches](#painpoints)
 - [Final Design](#painpoints)
 - [Reflections](#painpoints)

---

## Project Brief

---

## What is Scanpy?
Scanpy is a widely used Python library for single-cell analysis, yet users across experience levels often struggle to quickly locate relevant documentation, tutorials, and examples. Scanpy’s current documentation structure makes it difficult for new and intermediate users to discover relevant workflows and learning resources, increasing cognitive load and slowing time-to-insight.

---
## My Understanding of the Website
When evaluating the website I used 2 different techniques:
  - My initial thoughts of the website were documented using annotations
Insert video here


---
## Understanding the Audience
Scanpy’s users can be broadly categorized by level of familiarity as. It is important to understand this as it helps understand during evaluation if the features seem to favor all user groups.

1. First-Time Users:
    - Unfamiliar with Scanpy’s capabilities, applications and features
    - Rely heavily on tutorials and copy pasting code
    - Don’t know what to do first or what’s possible
    
2. Intermediate/ Returning Users:
    - Familiar with core steps
    - Know *what* they want to do, not always *where*

1. Advanced Users:
    - Familiar with most of its capabilities

---

## Problem

Although Scanpy is powerful, its landing page creates friction for new users—especially those without strong computational backgrounds. The main issues stem from unclear information hierarchy, developer-centric framing, and a lack of guided pathways.

Core problems identified:

- Users cannot tell where to begin.

- The information hierarchy does not match users’ mental models.

- The page caters primarily to developers, not scientists with mixed coding experience.

- Heavy text and scattered links make the page hard to scan quickly.

These issues result in higher cognitive load, longer onboarding time, and missed opportunities to help users grasp the workflow.

---

## Research & Evaluation

### Methods Used:
- Heuristic Evaluation based on Nielsen’s usability heuristics
(visibility of system status, user control, consistency, recognition over recall)

- Content audit of the landing page

- Analysis of user roles (biologists, computational researchers, students, developers)

- Mentored review sessions with two peers to test first-time navigation approaches

- Pathway mapping to compare intended vs. actual user navigation

### Key Insights:
- New users gravitated toward the most colorful or bold links—not the correct starting point.

- Many expected a “Start Here” or “Getting Started” area and were confused not to find one.

- Users with biology backgrounds felt overwhelmed by code-heavy phrasing.

- Users were unsure whether to begin with the tutorials, installation, or documentation.

- Scannability issues caused users to skim past important orientation content.

---

## Design Goals

Design Goals

From the insights above, I defined three main design goals:

- Improve Learnability
    - Provide clearer orientation and a recommended starting point.

- Enhance Navigation & Information Architecture
    - Help users quickly find what they need, reducing guessing and backtracking.

- Make the Experience More Inclusive
    - Support both developer-level and non-developer users with progressive disclosure.
 
---

## Pain Points & HCI-Driven Improvements

| Pain Point                         | Why It Was a Problem (HCI Perspective)                          | Design Improvement                                                    | Result / Impact                                           |
|:---|:---|:---|:---|
| **No clear CTA (call to action)**  | Increased cognitive load; users forced to infer next step.      | Added primary CTAs: **Install**, **Try a Tutorial**, **Explore Docs** | Clear first action; smoother ecosystem entry.             |
| **Hard-to-find beginner guidance** | Violated “match with users’ mental models.” No onboarding path. | Created **Start Here** pathway with Quickstart + Beginner Tutorials   | Faster onboarding; fewer navigational errors.             |
| **Dense, text-heavy layout**       | Low scannability and poor visual hierarchy.                     | Introduced simplified hero section and stronger hierarchy             | Users immediately understand Scanpy’s purpose.            |
| **Developer-centric tone**         | Excluded users with weaker coding backgrounds.                  | Added non-technical explanations and progressive disclosure           | More inclusive experience; accessible to all researchers. |


---

## Redesign

Redesigned Experience
1. A Clear Orientation Section

- Short explanation of what Scanpy is

- Who it’s for (developers + biologists)

- What users can accomplish

This helps users quickly form a correct mental model.

2. Prioritized CTAs

- A new, streamlined action row:

- Install

- Start Here

- Try a Tutorial

- Explore Docs

This solves decision paralysis and aligns with common tasks.

3. Beginner-Friendly Learning Flow

- A dedicated “Start Here” pathway guides users to:

- Quickstart guide

- Intro-level tutorials

- Key concepts needed to interpret embeddings and clustering

This reduces onboarding friction.

4. Improved Information Architecture

- Content was grouped into:

    - Getting Started

    - Core Concepts

    - Tutorials

    - Advanced Workflows

    - API References

This matches expectations users have from similar ecosystems (e.g., Seurat, PyTorch, scikit-learn).

![Scanpy Landing Page](./redesign.png)

*Scanpy's Landing Page*

5. Inclusive & Accessible Language

    - Technical content remains intact but now includes:

    - Clearer phrasing

    - More contextual explanations

    - Improved labeling of examples and datasets

This makes the experience more welcoming without sacrificing depth.

---

## Impact
While this is a concept redesign, the expected impact—grounded in HCI best practices—is measurable:

- Reduced bounce rates for newcomers
- Higher success rate in navigation tasks (installing, starting a tutorial)

- Improved comprehension of what Scanpy does and how the workflow fits together

- More inclusive experience for users with varying coding skill levels

- Greater tutorial engagement due to clearer entry points

If implemented, these changes would provide a smoother first experience and improve Scanpy’s usability for the community.

---

## Reflection
This project reinforced how important information architecture, progressive disclosure, and clear signposting are for scientific tools. Even powerful ecosystems fall short when users struggle to find their way.

By combining HCI principles with domain knowledge in bioinformatics, I was able to propose a more intuitive experience that lowers barriers for new users while still supporting experts.

Next steps could include:

- User testing with real first-time Scanpy learners

- A/B comparisons of the redesigned layout

- Further expansion of the “Start Here” flow into an interactive tutorial picker

