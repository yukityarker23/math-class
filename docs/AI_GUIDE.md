# AI Guide

## Project Overview

This project is called Math Clash.

Math Clash is a competitive real-time multiplayer educational web game where players improve their mathematical skills by competing against other players in ranked and casual matches.

This project is intended to be production-ready and scalable. Every implementation should prioritize maintainability, readability, performance, and clean architecture.

---

# General Rules

Always read the project documentation before making changes.

The following documents are the source of truth:

- README.md
- PRD.md
- GAME_DESIGN_DOCUMENT.md
- ARCHITECTURE.md
- DATABASE.md
- API_SPEC.md
- MATH_ENGINE.md
- ROADMAP.md
- TASKS.md
- UI_GUIDE.md

Never contradict these documents.

---

# Coding Standards

Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Axios
- React Query (TanStack Query)
- React Hook Form
- Zod for validation

Backend

- Laravel 12
- PHP 8.4+
- Laravel Sanctum
- Laravel Reverb
- PostgreSQL
- Redis

---

# Code Quality

Always:

- Write reusable components.
- Keep components small.
- Keep functions short.
- Prefer composition over duplication.
- Follow SOLID principles.
- Use meaningful names.
- Keep business logic separate from UI.
- Avoid unnecessary comments.
- Remove dead code.
- Keep files organized.

Never:

- Use inline CSS.
- Duplicate code.
- Hardcode values that belong in configuration.
- Place business logic inside React components.
- Put large amounts of logic inside Laravel controllers.

---

# Frontend Guidelines

Use:

- Functional Components
- Hooks
- Context only when appropriate
- TanStack Query for server state
- React Router
- Tailwind CSS

Organize folders by feature rather than file type whenever possible.

---

# Backend Guidelines

Controllers should only:

- Validate requests
- Call services
- Return responses

Business logic belongs in Services.

Validation belongs in Form Requests.

Database logic belongs in Eloquent Models or Repositories when appropriate.

---

# API

The frontend must never communicate directly with the database.

All communication happens through Laravel APIs or Laravel Reverb for real-time events.

---

# Game Rules

Never hardcode questions.

Always use the Question Generator.

Never trust the client for:

- Scores
- Timers
- Correct answers
- Match results

The server is always authoritative.

---

# Performance

Optimize for:

- Fast page loading
- Minimal re-renders
- Efficient database queries
- Small bundle size

---

# Security

Always validate on the server.

Never expose sensitive data.

Sanitize inputs.

Protect APIs using Sanctum.

Prevent cheating whenever possible.

---

# UI Principles

The interface should be:

- Clean
- Modern
- Minimal
- Responsive
- Accessible
- Fast

Avoid visual clutter.

Animations should improve user experience rather than distract from gameplay.

---

# Development Workflow

Build incrementally.

Each feature should:

1. Work independently.
2. Be tested.
3. Be reusable.
4. Be documented.

Never rewrite large portions of the project unless explicitly instructed.

Always preserve existing functionality.

If requirements are unclear, ask before implementing.
