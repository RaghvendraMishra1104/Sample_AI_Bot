# Product Requirements Document (PRD)
## AI Study Assistant

**Version:** 1.0
**Author:** [Your Name]
**Date:** 2025

---

## 1. Purpose
This PRD defines the requirements for building the MVP of the AI Study
Assistant — a student-focused AI app that summarizes notes, answers questions,
generates assignments, and explains concepts.

---

## 2. Goals & Objectives

### Product Goals
- Help students get academic help instantly, without a tutor
- Make studying faster and more efficient using AI
- Build an affordable solution for students in Tier 2 & Tier 3 cities

### Business Goals
- Acquire 10,000 users in the first 3 months post-launch
- Achieve 15% free-to-premium conversion rate by Month 6
- Maintain a Day-30 retention rate above 40%

---

## 3. Scope

### In Scope (MVP)
- User authentication (Sign up / Log in)
- Subject and grade personalization
- Note summarization (text + PDF input)
- Q&A assistant (text input)
- Concept explanation feature
- Chat history

### Out of Scope (Post-MVP)
- Voice input/output
- Assignment generator
- Collaborative study rooms
- Integration with school LMS systems
- Offline mode

---

## 4. Functional Requirements

### FR-01: User Authentication
- Users must be able to sign up using email and password
- Users must be able to log in and log out
- Password reset via email must be supported

### FR-02: Note Summarizer
- Users can paste plain text or upload a PDF (max 5MB)
- The AI must return a bullet-point summary within 10 seconds
- Summary must be under 300 words for a standard note

### FR-03: Q&A Assistant
- Users type a question (max 500 characters)
- AI returns a relevant academic answer within 5 seconds
- Users can ask follow-up questions in the same session
- Each session is saved to Chat History

### FR-04: Concept Explainer
- User enters a concept name and selects explanation level
- (Simple = ELI5 style / Detailed = textbook-level)
- AI returns explanation with at least one real-world example

### FR-05: Chat History
- All sessions are stored and viewable
- User can search history by keyword or subject
- User can delete or bookmark any session

### FR-06: Profile & Personalization
- User can set their grade, stream (Science/Commerce/Arts), and subjects
- App tone and content adjusts based on grade level

---

## 5. Non-Functional Requirements

| Requirement | Target |
|------------|--------|
| Response Time | < 5 seconds for AI responses |
| Uptime | 99.5% availability |
| Security | End-to-end encryption for user data |
| Scalability | Support 100,000 concurrent users |
| Accessibility | WCAG 2.1 AA compliant |
| Platform | Android, iOS, Web (responsive) |

---

## 6. User Stories

| ID | As a... | I want to... | So that... |
|----|---------|-------------|------------|
| US-01 | Student | Summarize my 10-page notes | I can revise in 5 minutes |
| US-02 | Student | Ask a doubt at midnight | I don't have to wait till morning |
| US-03 | Student | Get a simple explanation of Photosynthesis | I can understand it without Googling |
| US-04 | Student | See my past questions | I can review what I've already studied |
| US-05 | Teacher | Generate 10 MCQs on Algebra | I can save time making assignments |

---

## 7. Assumptions & Constraints
- Users have basic smartphone literacy
- Internet connection required for AI features
- Initial launch in English only; Hindi support in v2
- AI model accuracy depends on training data quality