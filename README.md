# ReviewLens AI

A React and TypeScript research prototype exploring how human and AI code reviews complement each other. Created as a demonstration.

> Synthetic research demonstration data 

## Features

- **Dashboard:** Summary metrics, category frequencies, and reviewer quality.
- **PR Review Comparator:** Side-by-side human and AI comments with an annotated synthetic code diff.
- **Comment Taxonomy:** Findings organized into 10 review categories.
- **Overlap Analysis:** Human-only, AI-only, and shared findings.
- **Complementarity Map:** Interactive categories showing relative reviewer strengths and supporting examples.
- **Expert Evaluation:** Rate accuracy, usefulness, severity, and actionability.
- **Recommendations:** Illustrative workflow: AI Pre-Review → Human Review → AI Verification → Merge.

## Review Categories

Correctness, Security, Performance, Readability, Architecture, Naming, Test Coverage, Edge Cases, Documentation, and Domain-specific concerns.

## Technology

- React
- TypeScript
- CSS with responsive layouts
- esbuild-generated frontend bundle

Frontend only. No backend, authentication, or external review APIs.

## Project Structure

    App.tsx          React components and synthetic dataset
    app.css          Styles and responsive layouts
    dist/
      index.html     Browser entry point
      app.js         Compiled JavaScript
      app.css        Compiled CSS
