# 🧠 RecallOS

### *Your AI-Powered Digital Memory*

> **Never lose context again.**
>
> RecallOS is a local-first AI system that automatically captures your digital activities, organizes them into an intelligent timeline, and allows you to search your past using natural language instead of filenames or browser history.

---

## 🚀 Overview

Developers, students, and professionals spend hours searching for information they've already seen.

* *"Where did I see that Stack Overflow answer?"*
* *"What command fixed my Docker issue?"*
* *"Which PDF did I read before implementing JWT authentication?"*

RecallOS solves this by creating an AI-powered timeline of your digital work. Instead of recording your screen like a screen recorder, it captures meaningful events, understands context, and reconstructs your workflow on demand.

---

# ✨ Key Features

## 🖥 Activity Timeline

Automatically records:

* Active applications
* Opened files
* Browser tabs
* VS Code projects
* Git commits
* Terminal commands
* Clipboard history
* Window switches
* System idle time

---

## 💻 Developer Memory

Tracks development workflow including:

* Files edited
* Classes created
* Functions modified
* Git commits
* Branch changes
* Build failures
* Test executions
* Terminal history

Example:

> "Show everything I did before committing `Fix JWT Authentication`"

---

## 🌐 Browser Intelligence

Stores browser activity with semantic understanding.

Instead of:

```
youtube.com/watch?id=123
```

RecallOS stores:

```
Spring Security JWT Tutorial

Watched: 82%

Project:
Authentication Module

Topics:
JWT
Spring Security
OAuth2
```

---

## 📷 Smart Screenshot Timeline

Instead of continuous recording,

RecallOS captures important screenshots based on activity.

Features:

* OCR
* Text Search
* Duplicate Detection
* Image Compression
* Timeline Navigation

---

## 💬 AI Memory

Ask questions naturally.

Examples:

```
When did I solve the Docker issue?

Find the article about Kafka retries.

Replay yesterday afternoon.

Show every JWT-related activity.

Where did I copy that SQL query?

Find the screenshot showing NullPointerException.
```

---

## 🔎 Semantic Search

Search across:

* Browser history
* Files
* PDFs
* Git commits
* Screenshots
* Terminal
* Notes

All from one search box.

---

## 📈 Productivity Insights

Daily statistics including:

* Coding hours
* Focus time
* Most visited websites
* Longest coding session
* Meeting duration
* Context switches
* Productivity score

---

## 📅 AI Daily Journal

Automatically generates summaries such as:

```
Worked on Authentication Module

Solved:
Docker networking issue

Read:
Spring Security Docs

Created:
3 Git commits

Next Suggested Task:
Finish Refresh Token Flow
```

---

## 🔄 Session Replay

Reconstruct an entire work session.

Example:

```
Opened VS Code

↓

Edited UserService.java

↓

Ran Maven

↓

Build Failed

↓

Visited Stack Overflow

↓

Fixed Issue

↓

Git Commit
```

Unlike video replay, this is searchable and context-aware.

---

## 🧩 Knowledge Graph

Automatically connects:

* Projects
* Files
* People
* Meetings
* Websites
* Git commits
* Notes
* Technologies

Making relationships discoverable over time.

---

# 🏗 Workflow

```text
User Activity
        │
        ▼
Desktop Agent
        │
        ▼
Activity Collectors
(File • Browser • Git • Terminal • Clipboard)
        │
        ▼
Event Queue
        │
        ▼
AI Event Processor
        │
 ┌──────┼────────┐
 │      │        │
 ▼      ▼        ▼
OCR  Summaries  Embeddings
        │
        ▼
Timeline Database
(SQLite + Vector Store)
        │
        ▼
Natural Language Search
        │
        ▼
AI Assistant
        │
        ▼
React Dashboard
```

---

# 🏛 System Architecture

```
┌───────────────────────────┐
│      React Dashboard      │
└────────────┬──────────────┘
             │
     REST / WebSocket
             │
┌────────────▼──────────────┐
│      Backend API          │
└────────────┬──────────────┘
             │
────────────────────────────────────
             │
     Event Processing Engine
             │
 ┌───────────┼─────────────┐
 │           │             │
 ▼           ▼             ▼
OCR     AI Summaries   Embeddings
 │           │             │
 └───────────┼─────────────┘
             ▼
 Timeline Database
             │
      Semantic Search
             │
             ▼
 AI Response Engine
```

---

# ⚙ Tech Stack

### Frontend

* React
* TypeScript
* Tailwind CSS
* Framer Motion
* React Query
* React Markdown

### Backend

* Node.js
* Express
* TypeScript

### Desktop

* Electron
* Node APIs
* Native OS Hooks

### Database

* SQLite
* PostgreSQL (future)
* Vector Database

### AI

* Ollama
* OpenAI
* Anthropic
* Gemini
* OpenRouter

---

# 📁 Project Structure

```
recallos/

frontend/
backend/
desktop-agent/
browser-extension/
shared/

backend/
    api/
    services/
    ai/
    timeline/
    search/
    database/
    auth/

desktop-agent/
    collectors/
    watchers/
    screenshot/
    terminal/
    git/

browser-extension/
    content/
    popup/
    background/

docs/
```

---

# 🔒 Privacy First

RecallOS is designed with privacy as a core principle.

* Local-first by default
* No cloud dependency
* End-to-end encrypted storage (optional)
* Configurable tracking rules
* Ignore private applications
* Pause tracking instantly
* Automatic data expiration
* Sensitive data redaction before indexing

Users remain in complete control of their data.

---

# 🛣 Roadmap

### Version 1

* Desktop activity tracking
* Browser history
* Git timeline
* AI search
* Screenshot OCR
* Daily summaries

### Version 2

* Calendar integration
* Meeting transcription
* Knowledge graph
* Focus analytics
* Cross-device synchronization

### Version 3

* Predictive task suggestions
* AI workflow automation
* Plugin marketplace
* Team collaboration
* Intelligent "Continue Where You Left Off"

---

# 🎯 Vision

RecallOS isn't another productivity tracker or screen recorder.

Its goal is to become a **second brain for your digital work**, allowing you to remember **experiences instead of filenames**, **conversations instead of tabs**, and **workflows instead of isolated events**.

By transforming fragmented digital activity into a searchable timeline, RecallOS helps users answer a simple but powerful question:

> **"What was I doing, and how did I get here?"**

---
