# SnapAct: Civic Accountability Platform

![Banner]([https://via.placeholder.com/1200x400?text=SnapAct+Hero+Image](https://assets.grok.com/users/fb5f60c9-1d07-4d8f-a8da-c3d00ff276c7/generated/8fb66746-751c-4e20-ba60-a43c023c0b32/image.jpg))  

## Overview
SnapAct turns your phone into a civic superpower: Snap a pothole/video, AI classifies (e.g., Roads/High severity), auto-routes to local gov, tracks with agents/escalations. Based on our PRD—empowering citizens in places like Kano.

## Features (MVP from PRD)
- Camera-first reporting with GPS/text.
- AI classification (7 categories: Water, Roads, etc.).
- Public feed (Trending/Nearby/Latest).
- Gov dashboard for assignments/SLAs.
- Notifications & moderation.

## Tech Stack
- Frontend: React Native + Expo
- Backend: Supabase + Clerk
- AI: OpenAI/Gemini + LangChain
- More: Twilio, Mapbox

## Setup & Run
(Add dev env instructions later)

## Contributing to SnapAct

Want to jump in and help build SnapAct—the AI-powered civic reporting beast? We're stoked! This project follows standard open-source vibes with a hackathon twist: Focus on the MVP from our PRD (linked in repo if available), keep it lean, and ship fast. Whether you're fixing bugs, adding features, or polishing docs, follow these steps to contribute like a pro. We use GitHub Flow—fork, branch, PR.

### Prerequisites
- Git installed (git-scm.com).
- Node.js/Yarn for dev (see Setup & Run section for full env later).
- Familiarity with React Native, Expo, Supabase, or AI tools (OpenAI/LangChain).
- Read the PRD (Product Requirements Document.pdf in repo) to align with scope—stick to In Scope (MVP) items like camera reporting (FR-CAM), AI classification (FR-AI), or feed (FR-FEED).

### How to Contribute
1. **Fork the Repo**: Hit "Fork" on GitHub to create your copy.
2. **Clone Locally**: `git clone https://github.com/YOUR_USERNAME/snapact.git && cd snapact`
3. **Set Up Upstream**: `git remote add upstream https://github.com/ORIGINAL_OWNER/snapact.git` (sync with main repo).
4. **Create a Branch**: From `dev` branch—`git checkout -b feature/your-cool-thing` (e.g., `feature/add-ai-classification`).
5. **Make Changes**:
   - Code in VS Code/Notepad++ (light for low-spec rigs).
   - Follow PRD priorities: Must Have first (e.g., FR-AUTH-01 user registration).
   - Test locally: Use Expo Go on phone—`expo start`.
   - Commit often: `git commit -m "Add camera preview (FR-CAM-05)"`.
6. **Push & PR**:
   - `git push origin feature/your-cool-thing`
   - Open PR on GitHub: Target `dev` branch, describe changes (link to PRD ID), add screenshots/demos.
7. **Code Review**: We'll review fast—address feedback, re-push.
8. **Merge & Celebrate**: Once approved, merge! Tag wins on X.

### Guidelines
- **Style**: ESLint/Prettier enforced (run `yarn lint`).
- **Commits**: Descriptive, atomic—e.g., "Implement geospatial routing (FR-GEO-01)".
- **Issues First**: For big changes, open an Issue first (label: enhancement, bug).
- **Scope**: MVP only—no Out of Scope like blockchain yet (PRD 4.2).
- **Testing**: Add unit tests for AI/agents if possible (Jest).
- **Docs**: Update README if needed.

### Code of Conduct
Be chill, inclusive—no toxicity. Report issues to maintainers.

Questions? DM on GitHub or X. Let's crush civic issues together—your PR could win us the hack! 🚀🏆

License: MIT
