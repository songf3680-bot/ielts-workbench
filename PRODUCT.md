# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

delegated: a single static HTML file with native CSS and JavaScript, chosen because the requested workstation must open locally, work offline, and avoid framework or build-tool overhead.

## Users

Primary user: an IELTS candidate preparing independently. They open the workstation before or after a study session to decide what to practise, run a timed drill, and record evidence that should change the next session.

## Product Purpose

The workstation turns IELTS preparation into a long-term operating loop: review today, choose a skill, start the timer, use AI or model answers to improve, and log the evidence that changes the next session. Success means the user can understand today's priorities and begin work within seconds on a phone.

## Positioning

Unlike a generic study planner, this product joins timed training, DeepSeek-powered feedback, an original question bank, annotated model answers, and a compact evidence ledger. Data and the optional API key remain on the user's device unless the user explicitly submits a request to DeepSeek.

## Operating Context

Used mostly on a phone in short, recurring sessions over months or years. A session may begin with today's plan, a question from the library, or a writing/speaking draft that needs feedback. Core planning, timers, records, imported material, question bank, and model answers work offline; AI grading requires a DeepSeek API request.

## Capabilities and Constraints

- Track exam date, target score, countdown, and daily task completion.
- Organise listening, reading, writing, and speaking as editable daily training lanes.
- Run a focus timer from the active training lane.
- Record practice sessions with module, band score, date, and note.
- Record mistakes, vocabulary, and useful expressions in one evidence ledger.
- Provide a mobile-first four-tab structure: Today, Training, AI Feedback, and Library.
- Send writing or speaking transcripts to DeepSeek when the user supplies an API key; never embed or ship a key in the page.
- Provide original IELTS practice questions, original annotated 7–8 band model answers, browser speech playback for listening prompts, and importing of personal material.
- Ship a searchable bank of 600+ visible practice items, 100 annotated model answers, 13 reading resources and 23 listening resources after keeping the generated writing set deliberately small. Official IELTS, British Council and IDP sample-test links are included instead of copying copyrighted papers.
- Include three original full reading passages with eight questions and answer keys each, plus three original narrated listening exercises with eight questions each and MP3 playback.
- Curate official DailyDictation short-story audio links with attribution and links back to the original exercises; do not republish third-party lesson audio inside the repository.
- Export all local workbench data as a JSON backup and import it again; API keys are intentionally excluded from backups.
- Persist all user data locally with browser storage.
- Estimated facts: the initial target is 7.0, daily task copy is a balanced starter routine, and the UI language is Simplified Chinese.

## Evidence on Hand

No real score reports, exam date, preferred study materials, or personal vocabulary are supplied. The workbench must not fabricate learner progress or claim that starter tasks match a specific test date. The bundled IELTS questions and model answers are original practice material, not reproductions of copyrighted test papers.

## Product Principles

1. Begin work before browsing options.
2. Make time visible without making the learner feel monitored.
3. Record evidence that can change the next study decision.
4. Prefer a fast, private, offline tool over an account-based study platform.

## Accessibility & Inclusion

The interface must remain keyboard-operable, respond down to a 390 px viewport, respect reduced-motion preferences, and keep text contrast at WCAG AA or better.
