# 🎯 Vibe Coding: The Complete Tutorial

> *From Natural Language to Working Software — A Comprehensive Guide to Intent-Driven Development*

![Vibe Coding](https://img.shields.io/badge/Vibe%20Coding-2026-blueviolet)
![AI](https://img.shields.io/badge/AI-Native-00ADD8)
![Status](https://img.shields.io/badge/Status-Comprehensive-success)

---

## 📚 Table of Contents

1. [Introduction: What is Vibe Coding?](#1-introduction-what-is-vibe-coding)
2. [The Origin Story](#2-the-origin-story)
3. [The Software Evolution: 1.0 → 2.0 → 3.0](#3-the-software-evolution)
4. [Core Concepts & Philosophy](#4-core-concepts--philosophy)
5. [Tools Landscape](#5-tools-landscape)
6. [Prompt Engineering Masterclass](#6-prompt-engineering-masterclass)
7. [Step-by-Step: Build Your First Vibe-Coded App](#7-step-by-step-building-a-real-app)
8. [Best Practices & Pitfalls](#8-best-practices--pitfalls)
9. [Advanced: Agentic Engineering](#9-advanced-agentic-engineering)
10. [Security & Production Readiness](#10-security--production-readiness)
11. [The Future & References](#11-the-future--references)

---

## 1. Introduction: What is Vibe Coding?

Vibe coding is a **new paradigm of software development** where you describe what you want in **natural language**, and AI generates the code. Instead of wrestling with syntax, you focus on **intent, context, and outcomes**.

### The Core Idea

```
Traditional Coding:  Idea → Design → Write Syntax → Debug → Deploy
Vibe Coding:         Idea → Describe → AI Generates → Refine → Deploy
```

> *"There's a new kind of coding I call 'vibe coding', where you fully give in to the vibes, embrace exponentials, and forget that the code even exists."*
> — **Andrej Karpathy**, February 2025

### Why It Matters

| Aspect | Traditional Coding | Vibe Coding |
|--------|-------------------|-------------|
| **Primary Skill** | Syntax mastery | Intent articulation |
| **Bottleneck** | Writing/debugging code | Idea quality & clarity |
| **Learning Curve** | Months to proficiency | Hours to productivity |
| **Iteration Speed** | Hours per feature | Minutes per feature |
| **Accessibility** | Requires CS background | Anyone who can describe a problem |

### What Vibe Coding Is NOT

- ❌ *Not* "no-code" — you still need to understand architecture, testing, and security
- ❌ *Not* "prompt and forget" — it's a collaborative iterative process
- ❌ *Not* a replacement for engineering discipline — it augments, doesn't replace
- ❌ *Not* production-ready without review — AI code still needs human oversight

---

## 2. The Origin Story

### The Karpathy Canon

On February 2, 2025, Andrej Karpathy posted this to X/Twitter:

> *"There's a new kind of coding I call 'vibe coding', where you fully give in to the vibes, embrace exponentials, and forget that the code even exists. It's possible because the LLMs (e.g. Cursor Composer w Sonnet) are getting too good. Also I just talk to Composer with SuperWhisper so I barely even touch the keyboard. I ask for the dumbest things like 'decrease the padding on the sidebar by half' because I'm too lazy to find it. I 'Accept All' always, I don't read the diffs anymore."*

**Impact:** The post went viral. By March 2025, **25% of Y Combinator's current cohort** had codebases that were almost entirely AI-generated. By the end of 2025, Collins Dictionary named **"vibe coding" Word of the Year**, and Google Trends showed a **2,400% increase** in searches.

### The Evolution Timeline

| Date | Milestone |
|------|-----------|
| **Feb 2025** | Karpathy coins "vibe coding" |
| **Mar 2025** | YC reports 25% AI-generated codebases |
| **Jun 2025** | Collins Dictionary Word of the Year shortlist |
| **Aug 2025** | First academic papers on arXiv |
| **Sep 2025** | Enterprise adoption begins (IBM, Google) |
| **Dec 2025** | MCP becomes universal standard |
| **2026** | $4.7B vibe coding market; Karpathy introduces "Agentic Engineering" |

---

## 3. The Software Evolution

Understanding where vibe coding fits in the evolution of software:

### Software 1.0 — Explicit Rules

```
Code: if (x > 0) { return x * 2; }
```

- Hand-written instructions
- Precise, deterministic
- Full human control
- Slow to write, predictable output

### Software 2.0 — Learned Weights (Neural Networks)

```
Training: data → optimizer → weights
```

- Models trained on data
- Non-deterministic, probabilistic
- Used for pattern recognition (vision, NLP)
- Still requires traditional code around it

### Software 3.0 — Natural Language Programming

```
Prompt: "Build a habit tracker with React, dark mode, and a streak counter"
```

- You describe intent in natural language
- AI generates code that fulfills that intent
- The LLM itself is a Software 2.0 artifact used to produce Software 1.0 code
- **Intent-driven development** — you specify *what*, AI figures out *how*

### Karpathy's "Ghosts" Analogy

Karpathy describes LLMs not as animals but as **"ghosts"** — jagged, statistical, summoned entities. They're not deterministic like traditional software, but they're incredibly capable when directed well. This requires a **new kind of taste and judgment**: knowing what to ask, when to trust, and when to verify.

---

## 4. Core Concepts & Philosophy

### Intent-Driven Development

The fundamental shift: from **syntax-focused** (how do I write this?) to **intent-focused** (what do I want to happen?).

```
Old mindset: "I need to write a for loop to iterate over this array"
New mindset: "I want to process all items in this list and calculate totals"
```

### Material Disengagement

A term from academic research on vibe coding — the developer deliberately **disengages from the material substrate** (the code itself) and instead **orchestrates its production** via an AI mediator. You become a **conductor**, not an instrumentalist.

### The Context Imperative

> *"AI models don't fail because of bad prompts. They fail because of missing context."*

Context engineering is the core skill. The AI needs to know:
- **Technical stack** (React + Node? Python + Flask?)
- **Architecture patterns** (monolith? microservices?)
- **Constraints** (must work offline? mobile-first?)
- **Design preferences** (dark mode? minimal?)
- **Edge cases** (what happens when API fails? network drops?)

### The Vibe Coding Loop

```
┌─────────────┐     ┌──────────────┐     ┌─────────────┐
│   Describe   │────→│  AI Generates │────→│  Review &   │
│   Intent     │     │    Code       │     │  Test       │
└─────────────┘     └──────────────┘     └─────────────┘
       ↑                                       │
       └────────────────────────────────────────┘
                    Refine & Iterate
```

---

## 5. Tools Landscape

### Category 1: AI-Native IDEs

| Tool | Best For | Pricing | Key Feature |
|------|----------|---------|-------------|
| **Cursor** | Professional devs, multi-file edits | $20/mo | Composer workflow, deep codebase understanding |
| **Windsurf** | AI-native dev experience | Free tier + Pro | Cascade agent, multi-file reasoning |
| **GitHub Copilot** | Inline completion | $10/mo | Deep IDE integration, autonomous mode |

### Category 2: AI App Builders (No-Code / Low-Code)

| Tool | Best For | Key Feature |
|------|----------|-------------|
| **Lovable** | Beautiful web apps fast | Natural language → full app |
| **Bolt.new** | Rapid MVPs | Browser-based, instant deploy |
| **Replit** | Learning & collaboration | AI Agent + built-in hosting |
| **Emergent** | Production-ready apps | Coordinated multi-agent system |

### Category 3: CLI Agents

| Tool | Best For | Key Feature |
|------|----------|-------------|
| **Claude Code** | Terminal-native power | Autonomous multi-file edits, shows reasoning before acting |
| **Gemini CLI** | Google ecosystem | Open-source, auto-routing, GEMINI.md context |
| **OpenAI Codex CLI** | OpenAI ecosystem | Natural language → shell commands + code |

### Category 4: Autonomous Coding Agents

| Tool | Best For | Key Feature |
|------|----------|-------------|
| **Devin** | Independent dev tasks | Plans, codes, tests, deploys autonomously |
| **Manus** | Complex multi-step builds | Research → plan → build → deploy |
| **Vybe** | Living apps that maintain themselves | AI builds + AI operates continuously |

### Quick Selection Guide

```
You are...                          Use...
─────────────────────────────────────────────────────
A professional developer            Cursor / Claude Code
Building an MVP fast                Bolt.new / Lovable
Non-technical with an idea          Lovable / Emergent
Learning to code                    Replit
Living in the terminal              Claude Code / Gemini CLI
Building internal tools             Base44 / Vybe
Need autonomous agents              Devin / Manus
```

---

## 6. Prompt Engineering Masterclass

This is the single most important skill for vibe coding. Your prompts determine your output quality.

### The Three-Layer Prompt Structure

Every great prompt has three layers:

```
┌────────────────────────────────────────────────┐
│  LAYER 1: Technical Context & Constraints       │
│  • Stack (React/Tailwind/Node)                  │
│  • Architecture patterns                        │
│  • Libraries & versions                         │
├────────────────────────────────────────────────┤
│  LAYER 2: Functional Requirements               │
│  • What should it do? (user stories)            │
│  • How should it behave? (interactions)         │
│  • What are the states? (loading/empty/error)   │
├────────────────────────────────────────────────┤
│  LAYER 3: Edge Cases & Integration              │
│  • Error handling & fallbacks                   │
│  • Security considerations                      │
│  • Performance constraints                      │
│  • How it connects to existing systems          │
└────────────────────────────────────────────────┘
```

### Template: Full Prompt Structure

```
**Context:**
[What are you building? Describe the project.]

**Technical Stack:**
[React, Node, Python, Tailwind, Supabase, etc.]

**Task:**
[What specific feature/code do you need right now?]

**Requirements:**
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

**Constraints:**
- [Constraint 1 — e.g., "no external libraries"]
- [Constraint 2 — e.g., "must work offline first"]

**Edge Cases to Handle:**
- [Edge case 1 — e.g., "empty state"]
- [Edge case 2 — e.g., "network failure"]
- [Edge case 3 — e.g., "rate limiting"]
```

### Example: Good vs. Bad Prompts

| ❌ Bad | ✅ Good |
|--------|---------|
| "Build me a login page" | "Create a login form in React using Tailwind, connected to Supabase Auth, with error handling for expired tokens and social login options" |
| "Make it look better" | "Update the sidebar with a dark gradient background, reduce padding to 16px, add subtle hover animations on menu items using Tailwind transition classes" |
| "Add a search feature" | "Add a real-time search bar that filters the product list by name and category. Debounce input by 300ms. Show a loading spinner during API calls. Handle the 'no results' state with a friendly empty state message" |

### Advanced Prompting Techniques

#### 1. Role Assignment
```
You are a senior Python developer who follows PEP8,
writes type hints everywhere, and always includes
docstrings. Generate...
```

#### 2. Chain-of-Thought Prompting
```
Before writing code, explain your reasoning step by step.
What approach will you take? What are the trade-offs?
Then implement your chosen solution.
```

#### 3. Few-Shot Prompting
Provide an example of the style/pattern you want:
```
Here is an example of how we write API endpoints:
[example code]

Now write a similar endpoint for [new feature].
```

#### 4. The "What Could Go Wrong?" Follow-Up
After the AI generates code, ask:
```
What could go wrong with this code? What edge cases
did we miss? Review for security and performance issues.
```

#### 5. Self-Review Mode
```
Review this code as if it's going live tomorrow.
Identify: security vulnerabilities, performance bottlenecks,
missing error handling, and suggest specific improvements.
```

#### 6. Iterative Refinement Cycle
```
Prompt → Review → ("Add X" / "Change Y" / "Fix Z") → Repeat
```
Never expect perfect first output. Treat every generation as a first draft.

### Prompt Templates Library

#### For Data Modeling
```
Context: [project description]
Database: [PostgreSQL/Supabase/MongoDB]
Language: [TypeScript/Python]
Entity: [entity name and purpose]
Core fields: [fields with types]
Relationships: [connections to other entities]
Business rules: [validation, constraints]
Create a data model for [use case].
```

#### For API Endpoints
```
Framework: [Express/Next.js/FastAPI]
Auth: [JWT/session/API keys]
Method + Route: [GET /api/...]
Purpose: [what it does]
Request: [body structure, params]
Response: [success + error formats]
Edge cases: [rate limiting, validation, auth failures]
Create this endpoint.
```

#### For UI Components
```
Framework: [React/Vue]
Styling: [Tailwind/CSS Modules]
State: [useState/Zustand/Redux]
Purpose: [what it does]
Props: [interface with types]
States: [loading, empty, error, success]
Accessibility: [ARIA labels, keyboard nav]
Test: [key behaviors to verify]
Create this component.
```

---

## 7. Step-by-Step: Building a Real App

Let's build a **Habit Tracker** app together — a real, working application.

### Step 1: Define Your Intent (Before You Prompt)

Spend 5 minutes thinking through:

```
**App:** Habit Tracker
**Stack:** React (Vite) + Tailwind CSS + Local Storage
**Features:**
  - Add/delete habits
  - Daily check-in (mark complete/incomplete)
  - Streak counter
  - 7-day history view
  - Dark mode
**Design:** Clean, minimal, calm aesthetic
```

### Step 2: Set Up the Foundation

Using Cursor, Claude Code, or Bolt.new:

**Prompt:**
```
Context: I'm building a habit tracker app — a personal tool
for tracking daily habits and streaks.

Technical Stack:
- React 18 with Vite
- Tailwind CSS for styling
- Local Storage for persistence (no backend)
- Lucide React for icons

Task: Initialize the project with Vite + React + Tailwind.
Create the basic file structure:
  src/
    components/   → reusable components
    hooks/        → custom hooks
    utils/        → helper functions
    App.jsx       → main app
    index.css     → Tailwind imports + custom styles

Set up Tailwind with a dark mode class strategy.
Include PostCSS config for Tailwind.
```

### Step 3: Build Core Features — One at a Time

**Prompt 1 — Data Layer:**
```
Now that the project is set up, create a custom React hook
called useHabits that manages habit data in Local Storage.

Requirements:
- Store habits as an array of objects: { id, name, createdAt, logs: { [date]: boolean } }
- Hook returns: { habits, addHabit, deleteHabit, toggleDate, getStreak }
- toggleDate marks a habit as complete/incomplete for a given date
- getStreak calculates consecutive days streak (from today backwards)
- Handle Local Storage errors gracefully (quota exceeded, corrupted data)
- Export TypeScript-style JSDoc comments
```

**Prompt 2 — UI Components:**
```
Create these components using React + Tailwind + Lucide icons:

1. HabitCard — displays a habit name, streak count, and 7-day
   mini calendar with check marks. Has edit/delete actions.
   States: active, completed today, loading

2. HabitForm — modal/dialog for adding a new habit.
   Fields: name (required, max 50 chars), emoji picker (optional).
   Validates input, prevents duplicates.

3. StreakBadge — visual badge showing current streak with a fire emoji.
   Color changes: 0-3 days = gray, 4-7 = orange, 8+ = red/gold.

4. WeeklyGrid — shows 7 columns for the last 7 days.
   Click to toggle complete/incomplete. Shows today highlighted.

Design: Dark mode by default. Calm, muted colors (slate/gray palette).
Smooth transitions on hover/click. Mobile-first responsive layout.
```

**Prompt 3 — Integration:**
```
Now wire everything together in App.jsx:
- Header with app name and dark mode toggle
- Grid of HabitCards displaying all habits
- Floating "+" button to open HabitForm
- Empty state when no habits exist (friendly message + illustration suggestion)
- Data persistence via useHabits hook
- Proper loading states during initialization
```

### Step 4: Iterative Refinement

After each prompt, test and refine:

```
"Add a confetti animation when a habit reaches a 7-day streak"
"Make the weekly grid swipeable on mobile"
"Add haptic feedback simulation on check-in (visual pulse)"
"Export habits as JSON (backup feature)"
"Add a stats page showing monthly completion rate"
```

### Step 5: Security & Polish

```
"Add input sanitization for habit names"
"Prevent XSS in any user-editable fields"
"Add rate limiting on rapid check-in toggling"
"Ensure no Local Storage data leaks"
"Add a privacy note that all data stays on-device"
```

### Step 6: Deploy

```
"Build for production. Deploy to Vercel/Netlify.
Add a _redirects file for SPA routing.
Set up proper meta tags for SEO."
```

---

## 8. Best Practices & Pitfalls

### ✅ Do's

| Practice | Why |
|----------|-----|
| **Think in products, not prototypes** | Plan architecture before the first prompt. If the app goes viral tomorrow, does it scale? |
| **Define the stack yourself** | Don't let AI pick your tech stack. You decide, AI implements. |
| **Start with full-stack skeleton** | Your first prompt should set up auth + DB + routing, not a static page |
| **Use version control from day 1** | AI code can go sideways fast. Git lets you roll back. |
| **Review every line before merging** | Speed comes from AI generation; safety comes from human review. |
| **Ask AI to explain its reasoning** | "Why did you choose this approach?" reveals trade-offs you might miss. |
| **Provide context in every prompt** | AI sessions start fresh. Weave context: "We have login working. Now add..." |
| **Use templates for repeat tasks** | Save proven prompt structures for data models, APIs, and components. |
| **Test edge cases explicitly** | Ask "what could go wrong?" to surface missing error handling. |
| **Stay in the loop** | Vibe coding is co-piloting, not autopilot. Stay engaged. |

### ❌ Don'ts

| Pitfall | Why It's Dangerous |
|---------|-------------------|
| **Accepting All blindly** | Karpathy said it jokingly — don't actually do this! Bugs hide in diffs. |
| **No version control** | AI can overwrite working code. Without Git, you lose history. |
| **Vague prompts** | "Make a dashboard" → generic, unusable output. Be specific. |
| **Skipping security review** | AI hardcodes API keys, forgets auth, creates SQL injection holes. |
| **No error handling** | AI defaults to happy-path code. Edge cases are your responsibility. |
| **Building without architecture** | Jumping straight to code without design yields spaghetti. |
| **Ignoring technical debt** | AI-generated code accumulates debt faster than human code. |
| **Using in production unreviewed** | Treat AI code as a junior dev's PR — always review. |
| **Skill atrophy** | Understanding fundamentals still matters. AI can't debug what you don't understand. |

### The "Security Debt" Problem

> Vibe coding introduced a new type of technical debt: **security debt**.

Common vulnerabilities found in AI-generated code:
- 🔴 API keys & passwords hardcoded
- 🔴 SQL injection vulnerabilities
- 🔴 Unsecured API endpoints
- 🔴 Overprivileged applications
- 🔴 Inadequate authentication
- 🔴 Vulnerable third-party libraries

**Rule:** Never deploy AI-generated code without a security audit.

### The Iteration Mindset

```
First prompt → Working prototype (60% there)
Second prompt → Core features working (80% there)
Third prompt → Edge cases handled (90% there)
Review pass → Security + performance (95% there)
Testing → Production-ready (100%)

Expect 3-5 iterations per feature. Each iteration takes minutes.
```

---

## 9. Advanced: Agentic Engineering

> *"Vibe coding was the demo. Agentic engineering is the production discipline."*

By April 2026, Karpathy had evolved the conversation. Vibe coding proved AI could generate code, but **agentic engineering** is the serious discipline that makes it production-ready.

### The Autonomy Spectrum

```
Human-in-the-loop    Human-on-the-loop    Human-out-of-the-loop
│                        │                        │
├── AI suggests         ├── AI acts,             ├── AI acts
├── Human approves      ├── Human monitors       ├── Human sets goals
├── Human implements    ├── Human intervenes     ├── AI self-corrects
│                        │                        │
[You are here]          [Next step]             [Long-term vision]
```

### Multi-Agent Systems

Advanced vibe coding uses **coordinated teams of AI agents**:

```
┌─────────────────────────────────────────────┐
│           Orchestrator Agent                 │
│  (Breaks down tasks, coordinates output)     │
├────────┬────────┬────────┬────────┬─────────┤
│Research│  Code  │ Testing│ Security│  Deploy │
│ Agent  │ Agent  │ Agent  │  Agent  │  Agent  │
└────────┴────────┴────────┴────────┴─────────┘
```

### Context Architecture

For serious projects, maintain a **project context file** (like `GEMINI.md` or `.cursorrules`):

```
# Project Context for AI Agents

## Stack
- Frontend: React 19 + TypeScript + Tailwind CSS
- Backend: Node.js 22 + Express + Prisma ORM
- Database: PostgreSQL 16 (Supabase)
- Auth: Supabase Auth with magic links
- Hosting: Vercel (frontend) + Railway (backend)

## Architecture
- Monorepo with /frontend and /backend directories
- API-first design with OpenAPI specs
- Feature-based component organization
- Functional components with hooks (no classes)

## Conventions
- TypeScript strict mode
- PascalCase for components, camelCase for functions
- Named exports preferred
- Unit tests in __tests__/ directory
- ESM modules (no require())

## Environment Variables
- VITE_SUPABASE_URL
- VITE_SUPABASE_ANON_KEY
- DATABASE_URL
- JWT_SECRET

## Design System
- ShadCN UI components (Radix primitives)
- Custom theme in tailwind.config.ts
- Dark mode via class strategy
```

---

## 10. Security & Production Readiness

### Pre-Deployment Checklist

- [ ] **Secrets management**: No hardcoded API keys, tokens, or passwords
- [ ] **Input validation**: All user inputs sanitized
- [ ] **Authentication**: Proper auth on every protected route
- [ ] **Authorization**: Role-based access control (not just "is logged in")
- [ ] **SQL injection**: Parameterized queries everywhere
- [ ] **XSS prevention**: Output escaping, CSP headers
- [ ] **Rate limiting**: Protection against abuse
- [ ] **Error handling**: No stack traces exposed to users
- [ ] **Dependencies**: Audit for known vulnerabilities (`npm audit`, `pip audit`)
- [ ] **CORS**: Proper origin restrictions
- [ ] **HTTPS**: Enforced in production
- [ ] **Logging**: No sensitive data in logs

### The Production Pipeline

```
AI Code → Human Review → Auto Tests → Security Scan → Staging → Production
```

### Code Review Checklist for AI-Generated Code

1. **Does it actually do what was requested?** (Requirements match?)
2. **Are there any security red flags?** (Hardcoded secrets, injection vectors?)
3. **Is error handling comprehensive?** (Network failures, empty states, edge cases?)
4. **Does it follow project conventions?** (Naming, structure, patterns?)
5. **Is it performant?** (N+1 queries, unnecessary re-renders, memory leaks?)
6. **Is it maintainable?** (Readable, commented where needed, not over-engineered?)

---

## 11. The Future & References

### Where We're Headed

| Trend | Timeline | Impact |
|-------|----------|--------|
| **Audio-driven development** | Now | Voice → code, hands-free coding |
| **Persistent codebase agents** | 2026 | AI that lives in your codebase, learns it, proactively suggests |
| **Agent-to-agent collaboration** | 2026-2027 | AI agents negotiating and coordinating like dev teams |
| **Self-evolving software** | 2027+ | Apps that modify themselves based on usage data |
| **Software 3.0 paradigm** | 2027+ | Neural networks doing more of the work; prompts as the new "code" |

### Key Insight

> *"You can outsource your thinking, but never your understanding."*
> — Andrej Karpathy, AI Ascent 2026

The best vibe coders are the ones who:
- Understand what good code looks like
- Can spot when AI is wrong
- Know enough architecture to guide effectively
- Never stop learning the fundamentals

### References

1. **Karpathy's original post** — [x.com/karpathy/status/1886192184808149383](https://x.com/karpathy/status/1886192184808149383)
2. **"Vibe Coding: Toward an AI-Native Paradigm"** — [arXiv:2510.17842](https://arxiv.org/html/2510.17842v1)
3. **"Vibe Coding: Programming Through Conversation"** — [arXiv:2506.23253](https://arxiv.org/html/2506.23253v1)
4. **IBM: What is Vibe Coding** — [ibm.com/think/topics/vibe-coding](https://www.ibm.com/think/topics/vibe-coding)
5. **Collins Dictionary: Word of the Year 2025** — [collinsdictionary.com](https://www.collinsdictionary.com/)
6. **Karpathy at AI Ascent 2026: From Vibe Coding to Agentic Engineering** — [YouTube](https://www.youtube.com/watch?v=96jN2OCOfLs)
7. **Supabase: Vibe Coding Best Practices for Prompting** — [supabase.com/blog](https://supabase.com/blog/vibe-coding-best-practices-for-prompting)
8. **Graphite: Enhancing Vibe Coding with Prompt Engineering** — [graphite.com/guides](https://graphite.com/guides/enhancing-vibe-coding-prompt-engineering)

---

## 🏁 Final Word

Vibe coding is not the end of programming — it's the **democratization of it**. The barrier shifts from "can you write code?" to "can you think clearly about what needs to be built?"

Your job as a developer doesn't disappear. It **elevates**. You move from writing syntax to designing intent. From debugging to directing. From coding to creating.

**The best time to start vibe coding was February 2025. The second best time is now.**

---

<div align="center">

*Created by **Subhankar Pattanayak** — Research Fellow, IMI Bhubaneswar*

*Part of the TechSambad AI Research Series*

</div>