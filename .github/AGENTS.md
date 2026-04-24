# Workspace AI Instructions

This workspace is a minimal static web project with two main files:
- `index.html` — admin login page with client-side JavaScript redirect logic
- `dashboard.html` — PDF merge and PDF cleanup tool using client-side `pdf-lib` and `PyScript`

## Key guidance for AI agents

- Treat this as a static frontend project. There is no backend server, build pipeline, or package manager in this repo.
- Edit HTML, CSS, and browser-side script logic directly in the existing files.
- Preserve the client-side dependencies loaded from CDN URLs (`pdf-lib`, `PyScript`, etc.).
- Do not add or assume Node.js, Python server, or API endpoints unless the user explicitly adds them later.
- The login flow in `index.html` is a simple hardcoded client-side check. Any secure authentication should be clearly identified as a future enhancement.

## Important files

- `index.html` — login UI and redirect to dashboard
- `dashboard.html` — file inputs, merge/download button, and PyScript-based PDF cleanup

## What not to do

- Do not propose `npm install`, `pip install`, or other package-management setup for this repository.
- Do not assume any build/test scripts exist.
- Do not change this repo into a backend project without explicit user direction.
