# NOTES.md
This file contains my personal notes as I learn React.js and Next.js.  
It documents what tools I’m using, what I’ve learned, and how I set things up.
---

## What is Node.js?
- Node.js lets you run JavaScript outside the browser.
- It provides the runtime for tools like npm and frameworks like Next.js.
- Required to install dependencies and run the development server.

---

## What is Next.js?
- Next.js is a React framework that adds:
  - File-based routing (pages from folders)
  - Server-side rendering (better SEO and performance)
  - API routes (server code inside the same project)
  - Tooling setup (TypeScript, ESLint, Tailwind, etc.)
- Makes React development easier and more professional.

---

## Tools in this Project
- **React.js** – build UI with components and hooks.
- **Next.js** – framework on top of React with routing & rendering.
- **TypeScript** – type-safe JavaScript.
- **Tailwind CSS** – fast styling with utility classes.
- **ESLint** – catch errors and enforce standards.
- **Prettier** – format code consistently.
- **npm** – package manager that installs and runs all dependencies.

---

## How I Added the Files
To create the Next.js project, I ran:

```bash
npx create-next-app@latest . --typescript --eslint --tailwind --app --src-dir --import-alias "@/*"
```
What this does is:
- Generated the initial Next.js project files (src/, configs, package.json).
- Added TypeScript, ESLint, and Tailwind CSS setup.
- Enabled the App Router and structured code under src/ (the current directory).
