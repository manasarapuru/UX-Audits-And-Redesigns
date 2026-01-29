# 🧬 Improving the Scanpy Landing Page Through HCI Principles

[![Status](https://img.shields.io/badge/status-Completed-brightgreen)](#)  ![Last updated](https://img.shields.io/badge/last%20updated-2025--12--10-blue)


**Exploring how the Scanpy landing page can be structured for better usability.**  

> ⚠️ **Disclaimer:** This is a speculative redesign based on personal experience and informal conversations with peers. No official user testing or validation was conducted.

---

## 📑 Table of Contents

- [Project Brief](#project-brief)  
- [What is Scanpy?](#what-is-scanpy)  
- [My Understanding of the Website](#my-understanding-of-the-website)  
- [Pain Points & HCI-Driven Improvements](#pain-points--hci-driven-improvements)  
- [Audience Perspective](#reflecting-on-broader-audience-pov)  
- [Problem Statement](#problem-statement)  
- [Design Goals](#design-goals)  
- [Sketches](#sketches)  
- [Final Redesign](#final-redesign)  
- [Impact](#impact)  
- [Reflection](#reflection)

---

## 📌 Project Brief

*(Optional: Embed slides, links, or videos here)*

---

## 🧪 What is Scanpy?

Scanpy is a widely used Python library for **single-cell analysis**, yet users across experience levels often struggle to quickly locate relevant documentation, tutorials, and examples.  

**Current challenges:**

- Documentation structure is confusing for new and intermediate users  
- Difficult to discover workflows and learning resources  
- Increases cognitive load and slows time-to-insight

---

## 🔍 My Understanding of the Website

I evaluated the website using two techniques:

1. **Annotated observations**  
   - Initial thoughts were documented directly on the site  
   - *Insert video here*  

2. **Heuristic Evaluation**  
   - Based on Nielsen’s usability heuristics:  
     - Visibility of system status  
     - User control  
     - Consistency  
     - Recognition over recall  

3. **Content Audit**  
   - Analyzed the landing page structure, content density, and navigational flow

---

## ⚠️ Pain Points & HCI-Driven Improvements

| Pain Point                         | HCI Perspective Problem                                  | Design Improvement                                                    | Expected Impact                                           |
|:----------------------------------|:---------------------------------------------------------|:----------------------------------------------------------------------|:--------------------------------------------------------|
| **No clear CTA (call to action)**  | Forces users to infer next steps; increases cognitive load | Added primary CTAs: **Install**, **Try a Tutorial**, **Explore Docs** | Clear entry point; smoother ecosystem onboarding       |
| **Hard-to-find beginner guidance** | Violates mental model alignment; no onboarding pathway   | Created **Start Here** pathway with Quickstart + Beginner Tutorials   | Faster onboarding; fewer navigational errors           |
| **Dense, text-heavy layout**       | Low scannability; poor visual hierarchy                  | Simplified hero section; strengthened hierarchy                       | Users immediately understand Scanpy’s purpose          |
| **Developer-centric tone**         | Excludes users with weaker coding backgrounds            | Added non-technical explanations & progressive disclosure            | More inclusive; accessible to all researchers          |

---

## 👥 Reflecting on Broader Audience POV

Scanpy’s users can be broadly categorized by familiarity:

**1️⃣ First-Time Users**  
- Unfamiliar with Scanpy’s capabilities  
- Rely on tutorials and copy-paste code  
- Unsure where to start  

**2️⃣ Intermediate / Returning Users**  
- Know *what* they want to do, not always *where*  
- Familiar with core steps  

**3️⃣ Advanced Users**  
- Comfortable with most capabilities  

> Understanding these groups ensures the redesign supports all levels.

---

## 📝 Problem Statement

Despite its power, Scanpy’s landing page creates **friction for new users**, especially those with limited computational experience.  

**Core issues identified:**

- Users cannot tell where to begin  
- Information hierarchy does not match mental models  
- Page primarily caters to developers, not mixed-skill scientists  
- Heavy text and scattered links reduce scannability  

**Result:** Increased cognitive load, longer onboarding, and missed opportunities for workflow comprehension.

---

## 🎯 Design Goals

From these insights, three main goals emerged:

1. **Improve Learnability**  
   - Provide orientation & recommended starting points  

2. **Enhance Navigation & IA**  
   - Enable quick access to needed content; reduce guesswork  

3. **Make the Experience More Inclusive**  
   - Support both developer and non-developer users through progressive disclosure  

---

## ✏️ Sketches

*(Insert sketches or wireframes here)*

---

## 🖥️ Final Redesign

**1. Clear Orientation Section**  
- Short explanation of Scanpy  
- Audience: developers + biologists  
- Key outcomes for users  

**2. Prioritized CTAs**  
- **Install**, **Start Here**, **Try a Tutorial**, **Explore Docs**  
- Reduces decision paralysis  

**3. Beginner-Friendly Learning Flow**  
- "Start Here" pathway with Quickstart, intro tutorials, and essential concepts  

**4. Improved Information Architecture**  
- Organized content into: Getting Started, Core Concepts, Tutorials, Advanced Workflows, API References  

**5. Inclusive & Accessible Language**  
- Non-technical explanations alongside technical content  
- Clear labeling of examples and datasets  

![Scanpy Landing Page](./redesign.png)  
*Scanpy's Redesigned Landing Page*

---

## 📈 Impact

Expected benefits (based on HCI principles):

- Reduced bounce rates for newcomers  
- Higher success in navigation tasks  
- Faster comprehension of workflows  
- More inclusive experience for all skill levels  
- Increased tutorial engagement  

---

## 💡 Reflection

This project reinforced the **importance of information architecture, progressive disclosure, and signposting** in scientific tools.  

**Next steps:**  
- User testing with first-time Scanpy learners  
- A/B testing of redesigned layout  
- Expand “Start Here” into an interactive tutorial picker  
