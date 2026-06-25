# Study Aura: AI-Powered Learning Ecosystem

**Study Aura** is an AI-powered educational platform designed to transform scattered learning resources into structured, personalized study materials. By combining modern web technologies, AI automation pipelines, and gamification systems, Study Aura helps students learn faster through intelligent content generation, interactive study tools, and adaptive learning experiences.

## 👥 Collaborators

<div align="center">

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/ImNatHarvey">
        <img src="https://github.com/ImNatHarvey.png" width="120px;" />
        <br />
        <b>@ImNatHarvey</b>
      </a>
    </td>

<td align="center">
  <a href="https://github.com/rewisPage">
    <img src="https://github.com/rewisPage.png" width="120px;" />
    <br />
    <b>@rewisPage</b>
  </a>
</td>    

<td align="center">
  <a href="https://github.com/Lamar101214">
    <img src="https://github.com/Lamar101214.png" width="120px;" />
    <br />
    <b>@Lamar101214</b>
  </a>
</td>

<td align="center">
  <a href="https://github.com/xtyannn">
    <img src="https://github.com/xtyannn.png" width="120px;" />
    <br />
    <b>@xtyannn</b>
  </a>
</td>

<td align="center">
  <a href="https://github.com/n4viii">
    <img src="https://github.com/n4viii.png" width="120px;" />
    <br />
    <b>@n4viii</b>
  </a>
</td>

  </tr>
</table>

</div>

---

![Image1](https://github.com/user-attachments/assets/896dc9b4-4903-46e9-91a4-86c9f9dc16eb)

![Image2](https://github.com/user-attachments/assets/bc5d1cac-16c6-45b1-873d-9b1f70b10f43)

![Image4](https://github.com/user-attachments/assets/cdb1a846-676a-42e2-bd1d-f5bf9f1e7549)

---

## 🏆 Awards & Certifications

![Image1](https://github.com/user-attachments/assets/d81cc85f-62ba-4d21-aa8e-caeb86e7181b)

![Image2](https://github.com/user-attachments/assets/44af6f8a-28e0-4206-badb-a368e519b48d)

---

## 🎓 System Overview & Ecosystem

Study Aura operates as an integrated learning ecosystem where users can collect information from multiple sources, process them through AI pipelines, and instantly generate educational resources.

### 🌐 Learning Source Ecosystem

The platform supports multiple input sources:

* 📄 Text Documents
* 📑 PDF Files
* 🖼️ Images
* 🌍 Websites
* 🎥 YouTube Videos
* 🔎 Web Search Results

All sources are processed through the **Source Reader Pipeline**, which extracts, cleans, and summarizes content before making it available throughout the platform.

### 🤖 AI Learning Engine

The AI ecosystem transforms uploaded content into multiple learning formats:

* Flashcards
* Mind Maps
* Quizzes
* Presentation Slides
* Data Tables
* AI Chat Conversations
* Audio Overviews
* Web Search Research

This enables a single source of information to generate multiple learning experiences tailored to different study styles.

### 🎮 Gamification Ecosystem

Study Aura incorporates a progression-based learning system:

* XP (Experience Points)
* Learning Milestones
* Tool Proficiency Tracking
* Activity Logging
* Progress Analytics
* Future Leaderboards
* Achievement Systems

Students are rewarded for consistent engagement and content creation throughout their learning journey.

---

# 🚀 System Features

## 📚 Source Management

* Upload and organize study materials.
* Create custom learning modules.
* Store sources permanently in the cloud.
* Preview processed source content.
* Manage learning resources from a centralized dashboard.

## 🤖 AI Studio

Generate educational resources from uploaded content:

### 🧠 Mind Maps

* AI-generated visual learning structures.
* Hierarchical topic organization.
* Interactive concept navigation.

### 📝 Quizzes

* Automatic question generation.
* Multiple-choice assessments.
* Knowledge validation tools.

### 🎴 Flashcards

* Active recall learning support.
* Question-answer study cards.
* Rapid revision workflows.

### 📊 Tables

* Structured information extraction.
* Data comparison formats.
* Organized study references.

### 📽️ Presentation Slides

* AI-generated presentation content.
* Educational slide deck creation.
* Topic summarization.

### 🎧 Audio Overview

* AI-powered study narration.
* Audio-based learning support.
* Hands-free review experience.

## 💬 AI Chat Assistant

* Context-aware conversations.
* Source-grounded responses.
* Learning-focused AI interactions.
* Personalized educational guidance.

## 🔍 Web Search Integration

* Search educational content directly.
* Import web research into study modules.
* Expand learning resources beyond uploaded files.

## 👤 User Management

* Authentication and authorization.
* Secure account management.
* User profile customization.
* Learning preferences management.

## ⚙️ Settings & Personalization

* Generation defaults.
* Safe learning filters.
* Audio preferences.
* Activity tracking.
* Personalized learning configuration.

## 🎮 Gamification System

* XP progression.
* Activity tracking.
* Learning statistics.
* Tool proficiency metrics.
* Performance insights.

---

# 🛠️ Technical Architecture

## 🖥️ Frontend Layer

### Technology Stack

* React
* TypeScript
* Vite
* CSS3
* Modern Component Architecture

### Responsibilities

* User Interface
* State Management
* Dashboard Experience
* AI Studio Interactions
* Learning Module Management
* Authentication Flows

---

## ☁️ Backend & Data Layer

### Supabase

Provides:

* Authentication
* User Management
* Database Storage
* Learning Module Storage
* Generated Content Persistence

### Data Management

Stores:

* User Profiles
* Modules
* Sources
* Generated Outputs
* Activity Logs
* Gamification Progress

---

## 🔄 Automation Layer

### n8n Workflow Engine

Study Aura utilizes multiple AI automation pipelines:

#### Source Reader Pipeline

Responsible for:

* Content Extraction
* PDF Parsing
* Image Processing
* Website Scraping
* YouTube Transcript Processing
* Content Summarization

#### AI Generation Pipelines

* Chat Pipeline
* Flashcards Pipeline
* Mind Map Pipeline
* Quiz Pipeline
* Slides Pipeline
* Tables Pipeline
* Audio Overview Pipeline
* Web Search Pipeline

---

## 🧠 Artificial Intelligence Layer

### Gemini AI

Used for:

* Content Understanding
* Educational Content Generation
* Summarization
* Question Generation
* Knowledge Structuring
* Conversational Learning

---

## 📊 Architecture Flow

```text
User Sources
     │
     ▼
Source Reader Pipeline
     │
     ▼
Processed Learning Content
     │
     ├── Chat
     ├── Flashcards
     ├── Mind Maps
     ├── Quizzes
     ├── Slides
     ├── Tables
     ├── Audio Overview
     └── Web Search
     │
     ▼
Supabase Storage
     │
     ▼
React Dashboard
```

---

# 🗺️ Development Roadmap: Step-by-Step Guide

## Phase 1: Project Foundation

### Objective

Establish the frontend architecture and cloud infrastructure.

### Execution

* Initialize React + TypeScript application.
* Configure Vite development environment.
* Integrate Supabase.
* Implement authentication system.
* Create initial dashboard architecture.

---

## Phase 2: Learning Module System

### Objective

Create the core content management workflow.

### Execution

* Module creation.
* Source management.
* Source storage architecture.
* Dashboard navigation system.
* Content organization workflows.

---

## Phase 3: Source Reader Pipeline

### Objective

Enable AI-powered content ingestion.

### Execution

* PDF parsing integration.
* Website scraping support.
* YouTube transcript extraction.
* Image understanding workflows.
* Text processing pipelines.
* AI summarization generation.

---

## Phase 4: AI Studio

### Objective

Transform learning content into educational resources.

### Execution

* Flashcards generation.
* Mind map generation.
* Quiz generation.
* Table generation.
* Slides generation.
* AI chat integration.

---

## Phase 5: User Experience Improvements

### Objective

Enhance usability and interface quality.

### Execution

* Modal redesigns.
* Source preview system.
* Responsive layouts.
* Activity tracking.
* Dashboard optimization.
* Error handling improvements.

---

## Phase 6: Gamification

### Objective

Increase student engagement.

### Execution

* XP system.
* Progress tracking.
* Tool proficiency analytics.
* Learning milestones.
* Activity history.

---

## Phase 7: Advanced AI Features

### Objective

Expand learning capabilities.

### Planned Features

* Audio Overview Generation
* Enhanced Web Search
* Smart Recommendations
* Personalized Study Plans
* AI Learning Analytics

---

## Phase 8: Production Readiness

### Objective

Prepare Study Aura for large-scale deployment.

### Planned Features

* Performance Optimization
* Security Hardening
* Workflow Monitoring
* Scalable Infrastructure
* Continuous Deployment

---

# 📂 Project Structure

```text
Study-Aura/
│
├── frontend/
│   ├── public/
│   │   └── assets/
│   │
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── ai-studio/
│   │   │   ├── dashboard/
│   │   │   ├── gamification/
│   │   │   ├── settings/
│   │   │   ├── states/
│   │   │   └── toast/
│   │   │
│   │   ├── hooks/
│   │   ├── lib/
│   │   ├── mocks/
│   │   ├── pages/
│   │   └── services/
│   │
│   ├── package.json
│   └── vite.config.ts
│
├── n8n-workflows/
│   ├── Source Reader Pipeline
│   ├── Chat Pipeline
│   ├── Flashcards Pipeline
│   ├── Mind Map Pipeline
│   ├── Quiz Pipeline
│   ├── Slides Pipeline
│   ├── Tables Pipeline
│   ├── Audio Overview Pipeline
│   └── Web Search Pipeline
│
├── docs/
│   └── LOCAL_SETUP.md
│
├── docker-compose.yml
├── QUICKSTART.md
└── README.md
```

---

# ⚙️ Execution and Setup

## 🛠️ Prerequisites

Install the following before setup:

* Node.js 18+
* npm
* Supabase Project
* n8n Instance
* Gemini API Key

---

## 📥 Installation Guide

### Step 1: Clone Repository

```bash
git clone https://github.com/ImNatHarvey/Study-Aura.git
cd Study-Aura
```

---

### Step 2: Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

### Step 3: Configure Environment Variables

Create a `.env` file using `.env.example`.

Example:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_key

VITE_SOURCE_READER_WEBHOOK=
VITE_CHAT_WEBHOOK=
VITE_FLASHCARDS_WEBHOOK=
VITE_MINDMAP_WEBHOOK=
VITE_QUIZ_WEBHOOK=
VITE_SLIDES_WEBHOOK=
VITE_TABLES_WEBHOOK=
VITE_AUDIO_WEBHOOK=
VITE_WEBSEARCH_WEBHOOK=
```

---

### Step 4: Configure Supabase

* Create a Supabase project.
* Configure authentication.
* Create required database tables.
* Enable Row Level Security policies if required.

---

### Step 5: Import n8n Workflows

Import all workflow files from:

```text
n8n-workflows/
```

into your n8n instance.

Activate:

* Source Reader Pipeline
* Chat Pipeline
* Flashcards Pipeline
* Mind Map Pipeline
* Quiz Pipeline
* Slides Pipeline
* Tables Pipeline
* Audio Overview Pipeline
* Web Search Pipeline

---

### Step 6: Configure Gemini

Add your Gemini API credentials inside the imported n8n workflows.

---

### Step 7: Start Development Server

```bash
cd frontend
npm run dev
```

---

### Step 8: Open Application

Navigate to:

```text
http://localhost:5173
```

Sign up or log in to begin creating learning modules and generating AI-powered educational content.

---

## 🎯 Vision

Study Aura aims to become a complete AI-powered learning companion that transforms any source of information into personalized educational experiences, helping students learn more effectively through intelligent content generation, interactive study tools, and gamified progress tracking.
