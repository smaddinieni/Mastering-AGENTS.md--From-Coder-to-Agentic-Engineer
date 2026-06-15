# Mastering AGENTS.md: From Coder to Agentic Engineer

A simple static course website that teaches developers how to write useful `AGENTS.md` files for AI coding agents.

The course explains why agent instruction files matter, how they differ from human-facing README files, and how to use them to give coding agents clear project rules, commands, and boundaries.

## Live Site

This repo is intended to be published with GitHub Pages:

https://smaddinieni.github.io/Mastering-AGENTS.md--From-Coder-to-Agentic-Engineer/

> [!NOTE]
> If the link shows a 404, check the repository's GitHub Pages settings and make sure it is publishing from the `master` branch and the root folder.

## What Is Included

- A home page with the full course curriculum
- Seven self-paced HTML lessons
- Interactive quiz sections inside the lessons
- A quick reference cheat sheet for writing `AGENTS.md`
- Shared styling for the lesson pages

## Course Lessons

1. What is `AGENTS.md`, and why does it exist?
2. Anatomy of `AGENTS.md` - every section explained
3. Writing your first `AGENTS.md` file
4. Monorepos and hierarchy
5. Advanced style and testing rules
6. Multi-agent orchestration
7. Maintenance and best practices

## Project Structure

```text
.
+-- index.html
+-- lessons/
|   +-- 0001-what-is-agents-md.html
|   +-- 0002-anatomy-of-agents-md.html
|   +-- 0003-writing-your-first-agents-md.html
|   +-- 0004-monorepos-and-hierarchy.html
|   +-- 0005-advanced-style-and-testing.html
|   +-- 0006-multi-agent-orchestration.html
|   +-- 0007-maintenance-and-best-practices.html
|   +-- style.css
+-- reference/
    +-- agents-md-cheat-sheet.html
```

## Run Locally

No build step is required. This is a plain HTML and CSS site.

Open `index.html` in a browser, or use a small local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages Setup

To publish the site on GitHub Pages:

1. Go to the repository settings on GitHub.
2. Open **Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Set **Branch** to `master`.
5. Set the folder to `/ root`.
6. Save and wait a few minutes for GitHub to publish the site.

## Simple Repo Description

Static GitHub Pages course for learning how to write effective `AGENTS.md` files for AI coding agents.