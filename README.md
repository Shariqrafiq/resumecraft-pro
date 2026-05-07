# ResumeAI Pro

> Build a Job-Winning Resume in 2 Minutes — No Login, No Payment, No Bullshit

![ResumeAI Pro]

## 📋 Table of Contents
- [What is ResumeAI Pro?](#what-is-resumeai-pro)
- [Features](#features)
- [Why I Built This](#why-i-built-this)
- [Quick Start](#quick-start)
- [Templates](#templates)
- [Skill Suggestions Engine](#skill-suggestions-engine)
- [ATS Scoring System](#ats-scoring-system)
- [iOS PDF Fix](#ios-pdf-fix)
- [Tech Stack](#tech-stack)
- [Browser Support](#browser-support)
- [Known Limitations](#known-limitations)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

---

## What is ResumeAI Pro?

ResumeAI Pro is a **free, offline-first resume builder** that runs entirely in your browser. No account creation, no email collection, no payment walls — just a single HTML file that helps you craft professional resumes with AI-powered assistance.

Your data **never leaves your computer**. Everything is processed client-side using vanilla JavaScript.

## Features

### 🤖 AI-Powered Writing Assistant
- **Smart Summary Generator**: One click generates a professional summary tailored to your job title
- **Skill Suggestions Engine**: Type your role and get 20+ relevant skills suggested instantly
- **ATS Keyword Optimizer**: Real-time scoring that helps you pass automated resume filters

### 🎨 7 Radically Different Templates
Not just color swaps — each template has a completely unique layout and visual identity:

| Template | Style | Best For |
|----------|-------|----------|
| **Nexus** | Dark mode, sidebar skill bars | Software engineers, tech roles |
| **Folio** | Editorial serif, striped accents | Traditional industries, publishing |
| **Prism** | Bold geometric, warm tones | Creatives, startups |
| **Vertex** | Executive dark, mint accents | Senior leadership, consulting |
| **Canvas** | Minimal white, ATS-optimized | Finance, law, healthcare |
| **Neon** | Purple gradients, futuristic | UX designers, gaming industry |
| **Atlas** | Two-column professional | Balanced professional roles |

### 📊 Live ATS Score
Real-time scoring from 0-100 that checks:
- Contact information completeness
- Professional summary quality
- Work experience details
- Skills coverage
- Overall resume health

### 📥 One-Click PDF Export
Download a print-ready PDF instantly. Works on desktop and mobile (with iOS fallback).

### 📱 Fully Responsive
Works on desktop, tablet, and mobile. The builder adapts to any screen size.

### 🔒 Privacy First
100% client-side. No data collection. No analytics. No tracking. Your resume data stays on your device.

## Why I Built This

I watched too many talented people get rejected from jobs not because they weren't qualified, but because their resumes weren't optimized for ATS systems or didn't present their skills effectively.

Existing solutions were either:
- **Expensive** ($30/month subscriptions for basic templates)
- **Invasive** (requiring email signup to even try the tool)
- **Outdated** (templates from 2015 with no AI features)
- **Bloated** (heavy frameworks, slow load times)

I wanted something that was:
- **Completely free** — no premium tiers, no paywalls
- **Private** — no data collection, no accounts
- **Smart** — AI assistance where it actually helps
- **Fast** — single file, loads instantly
- **Beautiful** — templates that compete with premium services

So I built it. One HTML file. Zero dependencies (except PDF libraries). Pure vanilla JavaScript.

## Quick Start

### Option 1: Direct Download
1. Download `resumeai-pro.html`
2. Double-click to open in any browser
3. Start building your resume

### Option 2: Host It
```bash
# Clone the repository
git clone https://github.com/shariqrafiq/resumeai-pro.git

# Navigate to the directory
cd resumeai-pro

# Serve with any HTTP server
python3 -m http.server 8000
# or
npx serve .