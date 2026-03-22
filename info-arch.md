# Information Architecture — AI Study Assistant

## Overview
This document defines the structure, navigation flow, and content organization
of the AI Study Assistant application.

---

## App Structure (Sitemap)
```
AI Study Assistant
│
├── Onboarding
│   ├── Splash Screen
│   ├── Sign Up / Log In
│   └── Select Grade & Subjects
│
├── Home Dashboard
│   ├── Quick Action Buttons
│   │   ├── Summarize Notes
│   │   ├── Ask a Question
│   │   ├── Generate Assignment
│   │   └── Explain a Concept
│   └── Recent Activity Feed
│
├── Summarizer
│   ├── Upload File (PDF/Image/Text)
│   ├── Paste Text
│   └── View Summary Output
│
├── Q&A Assistant
│   ├── Type Question
│   ├── Voice Input
│   └── View Answer + Related Questions
│
├── Assignment Generator
│   ├── Select Subject
│   ├── Enter Topic
│   ├── Choose Difficulty (Easy/Medium/Hard)
│   └── View & Download Questions
│
├── Concept Explainer
│   ├── Enter Concept Name
│   ├── Select Explanation Level (Simple/Detailed)
│   └── View Explanation with Examples
│
├── Chat History
│   ├── Search Past Chats
│   ├── View by Subject/Date
│   └── Delete / Bookmark
│
├── Profile & Settings
│   ├── Edit Profile
│   ├── Manage Subjects
│   ├── Subscription & Plans
│   ├── Notification Settings
│   └── Help & Support
│
└── Premium / Upgrade Screen
    ├── Plan Comparison
    └── Payment Gateway
```

---

## Navigation Pattern
- **Bottom Navigation Bar** (Mobile): Home, Ask, Summarize, History, Profile
- **Sidebar Navigation** (Web/Tablet): Full menu always visible

## User Flow — Core Action (Ask a Question)
1. User opens app → lands on **Home Dashboard**
2. Taps **"Ask a Question"**
3. Types or speaks the question
4. AI processes → shows **Answer Screen**
5. User can **save, copy, or ask follow-up**

## Content Hierarchy
- **Level 1:** Main Sections (Home, Summarizer, Q&A, Generator, History)
- **Level 2:** Features within each section
- **Level 3:** Output screens and result pages