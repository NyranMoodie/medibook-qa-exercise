# MediBook Patient Portal: Generated Test Suite

This repository contains a Playwright test suite that **Specwright AI** generated from the
*MediBook Patient Portal Requirements v1.2* document (see `docs/`). It also contains a local
copy of the MediBook sandbox app so the suite can run against a real UI.

The suite has not been run yet. Your job is to get it working **correctly**.

## Setup

Requires Node.js 18 or later.

```bash
npm install
npx playwright install chromium
```

## Run

```bash
npm test                 # run the suite headless
npm run test:headed      # watch the browser
npm run report           # open the HTML report after a run
npm start                # run the sandbox app by itself at http://localhost:4173
```

Sandbox login: `patient@medibook.test` / `Clinic#2026`

## Your task (about 30 minutes)

1. Run the suite and fix whatever stops it from running or passing.
2. A passing test is not the goal on its own. Each test must actually verify what the
   requirements say. If a test is wrong about the requirement, fix the test, not the app.
3. Do not modify anything in `app/`. Treat it as the system under test.
4. Talk through your reasoning as you go. When you finish, be ready to explain each change
   and anything you would improve if you had more time.

You may use the Playwright docs, trace viewer, and any search engine. Ask your interviewer
if anything is unclear.
