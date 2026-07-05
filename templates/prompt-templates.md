# 🎯 Vibe Coding: Prompt Template Library

> *Reusable prompt structures for every stage of development*

## Data Modeling Template
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

## API Endpoint Template
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

## UI Component Template
```
Framework: [React/Vue]
Styling: [Tailwind/CSS Modules]
State: [useState/Zustand/Redux]
Purpose: [what it does]
Props: [interface with types]
States: [loading, empty, error, success]
Accessibility: [ARIA labels, keyboard nav]
Mobile: [responsive breakpoints]
Create this [component name].
```

## Refactoring Prompt
```
Here is existing code: [paste code]
Refactor:
  - [improvement 1]
  - [improvement 2]
  - [constraint 1]
  Keep the same behavior. Improve [performance/readability/maintainability].
```

## Self-Review Prompt
```
Review this code as if it's going live tomorrow.
Identify:
1. Security vulnerabilities
2. Performance bottlenecks
3. Missing error handling
4. Edge cases not covered
5. Suggested fixes for each issue
```

## Debugging Prompt
```
I'm getting this error: [paste error]
The code: [paste code or link to file]
What I expect to happen: [description]
What actually happens: [description]
Debug this step by step. First explain the cause, then the fix.
```

## Project Initialization Prompt (Full Stack)
```
Initialize a full-stack project with:
- Frontend: [React/Next.js + Tailwind]
- Backend: [Node+Express/FastAPI]
- Database: [PostgreSQL/Supabase]
- Auth: [Supabase Auth / JWT]
- Hosting: [Vercel / Railway]
Set up folder structure, config files, basic routing,
and a health-check endpoint. Include a sample .env.example.
```

## Feature Addition Prompt (With Context)
```
Context: We already have [X, Y, Z] working.

Now add:
- Feature: [description]
- How it connects: [to existing parts]
- States to handle: [loading, empty, error, success]
- Validation: [rules for inputs]
- UX notes: [animations, transitions, feedback]
