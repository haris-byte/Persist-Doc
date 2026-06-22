# Persist - AI-Assisted Goal Tracking Mobile App

**Status:** Final-year / portfolio project  
**Associated with:** Superior University  
**Developer:** Muhammad Haris Ali  
**Focus:** Mobile app development, Firebase, API-based AI-assisted planning, goal execution, habit stability

---

## Overview

Persist is a mobile goal-tracking app built to help users convert long-term goals into structured daily execution. The app supports goal creation, AI-assisted daily task planning, task sessions, mood logging, progress insights, stability scoring, skip-risk probability, and friend-based accountability.

The project was built in **React Native / Expo** with Firebase services, and a Flutter version was also developed with a similar core workflow.

---

## Tech Stack

- **Mobile:** React Native, Expo, Flutter
- **Language:** JavaScript
- **Backend / Cloud:** Firebase Auth, Firestore, Firebase Storage
- **AI:** LLM API integration for AI-assisted planning and daily task generation
- **Tools:** Git, GitHub, VS Code

---

## Core Features

- Firebase authentication for user sign-in and sign-up
- Firestore-backed user data and progress storage
- Goal creation and structured daily planning
- API-based AI-assisted goal planning
- Daily task generation with focused task-session flow
- Mood logging and reflection flow
- Skip-risk probability indicator
- Stability score and progress insights
- Friend progress / accountability features
- Notifications, reports, profile, and settings screens

---

## Screenshots

Create this folder in the repo:

```text
docs/images/
```

Add screenshots with these exact names:

```text
docs/images/01-auth.png
docs/images/02-onboarding.png
docs/images/03-goal-creation.png
docs/images/04-ai-plan-preview.png
docs/images/05-task-session.png
docs/images/06-mood-log.png
docs/images/07-insights-report.png
docs/images/08-friends-settings.png
```

Then uncomment or keep the image section below after the images are added:

| Auth / Signup | Onboarding |
|---|---|
| ![Auth](docs/images/01-auth.png) | ![Onboarding](docs/images/02-onboarding.png) |

| Goal Creation | AI Plan Preview |
|---|---|
| ![Goal Creation](docs/images/03-goal-creation.png) | ![AI Plan Preview](docs/images/04-ai-plan-preview.png) |

| Task Session | Mood Log |
|---|---|
| ![Task Session](docs/images/05-task-session.png) | ![Mood Log](docs/images/06-mood-log.png) |

| Insights / Report | Friends / Settings |
|---|---|
| ![Insights](docs/images/07-insights-report.png) | ![Friends Settings](docs/images/08-friends-settings.png) |

---

## Suggested Demo Flow

1. Open the app and sign in.
2. Complete onboarding.
3. Create a goal.
4. Generate an AI-assisted daily plan.
5. Start a daily task session.
6. Complete a task and log mood.
7. View progress insights and stability score.
8. View friend/progress or settings screens.

---

## AI and Scoring Note

Persist uses an LLM API for AI-assisted goal planning and daily task suggestions. Skip-risk probability and stability score are app-level behavioral indicators based on progress, mood, and completion patterns. They are not medical, clinical, or psychological diagnosis tools.

---

## Repository Safety Recommendation

If you do not want the code or idea copied, do **not** publish the full source code publicly.

Recommended approach:

- Keep the full source code in a **private repository**.
- Create a **public showcase repository** with this README, screenshots, architecture notes, and a demo video.
- Add this line to the public README:

```text
Source code is private. Access may be shared with recruiters or evaluators on request.
```

Before making any repository public, remove:

- `.env` files
- API keys
- Firebase config values
- test accounts
- personal screenshots/data
- unused files
- build artifacts
- `node_modules`
- incomplete or broken code

---

## Public Repo Option

If this is only a portfolio showcase, use this structure:

```text
persist-showcase/
├── README.md
├── docs/
│   ├── images/
│   │   ├── 01-auth.png
│   │   ├── 02-onboarding.png
│   │   ├── 03-goal-creation.png
│   │   ├── 04-ai-plan-preview.png
│   │   ├── 05-task-session.png
│   │   ├── 06-mood-log.png
│   │   ├── 07-insights-report.png
│   │   └── 08-friends-settings.png
│   └── Persist-App-Project-Showcase.pdf
└── LICENSE.md
```

Use a restrictive `LICENSE.md` if you publish documentation only:

```text
Copyright (c) 2026 Muhammad Haris Ali.
All rights reserved.
This repository is shared for portfolio and evaluation purposes only.
No permission is granted to copy, modify, redistribute, or commercially use the project, design, documentation, or screenshots without written permission.
```

---

## LinkedIn Media Description

React Native / Flutter mobile app with Firebase Auth, Firestore, API-based AI-assisted goal planning, daily task generation, skip-risk probability, stability score, mood logging, insights, reflection flow, and friend progress features.
