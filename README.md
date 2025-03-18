# tools


#general

## Testing
- Write testable code
- Create unit tests for core functionality
- Use integration tests for complex workflows
- Test edge cases and error conditions

## Version Control
- Make atomic commits
- Write descriptive commit messages
- Use branches for features and fixes
- Review code before merging










# Project Instructions

- Use specification and guidelines as you build the app.
- Write the complete code for every step. Do not get lazy.
- Your goal is to completely finish whatever I ask for.
- Don't improve code that isn’t related to what I asked for.

## Overview

This is a web app template.

## Tech Stack

- Frontend: SvelteKit, Svelte, Tailwind, Shadcn, Framer Motion
- Backend: Postgres, Supabase, Drizzle ORM, Server Actions
- Auth: Clerk
- Payments: Stripe
- Analytics: PostHog
- Deployment: Vercel

## Project Structure

- `actions` - Server actions
  - `db` - Database related actions
  - Other actions
- `app` - Next.js app router
  - `api` - API routes
  - `route` - An example route
    - `_components` - One-off components for the route
    - `layout.tsx` - Layout for the route
    - `page.tsx` - Page for the route
- `components` - Shared components
  - `ui` - UI components
  - `utilities` - Utility components
- `db` - Database
  - `schema` - Database schemas
- `lib` - Library code
  - `hooks` - Custom hooks
- `prompts` - Prompt files
- `public` - Static assets
- `types` - Type definitions

## Rules

Follow these rules when building the app.

### General Rules

- Use `@` to import anything from the app unless otherwise specified
- Use kebab case for all files and folders unless otherwise specified
- Don't update shadcn components unless otherwise specified

#### Env Rules

- If you update environment variables, update the `.env.example` file
- All environment variables should go in `.env.local`
- Do not expose environment variables to the frontend
- Use `NEXT_PUBLIC_` prefix for environment variables that need to be accessed from the frontend
- You may import environment variables in server actions and components by using `process.env.VARIABLE_NAME`

---



You are an expert in coding and modern web development.

Key Principles
- Write concise, technical code with accurate Svelte 5 and SvelteKit examples.
- Leverage SvelteKit's server-side rendering (SSR) and static site generation (SSG) capabilities.
- Prioritize performance optimization and minimal JavaScript for optimal user experience.
- Use descriptive variable names and follow Svelte and SvelteKit conventions.
- Organize files using SvelteKit's file-based routing system.

Code Style and Structure
- Write concise, technical TypeScript or JavaScript code with accurate examples.
- Use functional and declarative programming patterns; avoid unnecessary classes except for state machines.
- Prefer iteration and modularization over code duplication.
- Structure files: component logic, markup, styles, helpers, types.
- Follow Svelte's official documentation for setup and configuration: https://svelte.dev/docs

Naming Conventions
- Use lowercase with hyphens for component files (e.g., `components/auth-form.svelte`).
- Use PascalCase for component names in imports and usage.
- Use camelCase for variables, functions, and props.

TypeScript Usage
- Use TypeScript for all code; prefer interfaces over types.
- Avoid enums; use const objects instead.
- Use functional components with TypeScript interfaces for props.
- Enable strict mode in TypeScript for better type safety.