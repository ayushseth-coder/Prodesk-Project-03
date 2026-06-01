# Prompt.md – Sprint 03 (Dev-Detective)

## Project Context
I am working on Sprint 03 of my engineering pipeline at Prodesk IT.
The objective of this sprint is to build a client-side GitHub Search application
using Vanilla JavaScript, Fetch API, Async/Await, and DOM manipulation.

This file documents how I used AI (ChatGPT) as a pair-programmer
to understand concepts, debug issues, and improve code quality.
No blind copy-paste was done.

---

## Prompts Used

### 1. Understanding Fetch API & Async/Await
Prompt:
"Explain Fetch API and async/await in very simple words with a real-life example."

Outcome:
- Understood how fetch() returns a Promise
- Learned why await pauses execution
- Learned how response.json() works

---

### 2. Loading State Handling
Prompt:
"How can I show a loading spinner while API data is fetching and hide it after response?"

Outcome:
- Implemented a loading UI state
- Ensured spinner appears before fetch call
- Removed spinner after data/error response

---

### 3. Error Handling (404 User Not Found)
Prompt:
"How to handle GitHub API 404 error without crashing the app?"

Outcome:
- Used try/catch block
- Checked response.ok
- Rendered a clean 'User Not Found' UI

---

### 4. Repository Data Fetching
Prompt:
"How can I fetch GitHub user repositories using repos_url and display top 5 latest repos?"

Outcome:
- Chained API calls
- Used slice(0,5)
- Rendered clickable repo links opening in new tab

---

### 5. Date Formatting
Prompt:
"Convert ISO date like 2023-01-25T12:00:00Z into 25 Jan 2023 using JavaScript."

Outcome:
- Created a reusable date formatting utility function

---

### 6. Battle Mode Logic (Phase 3)
Prompt:
"Explain Promise.all() with example for fetching two GitHub users at the same time."

Outcome:
- Implemented Promise.all()
- Compared total stars using reduce()
- Conditionally rendered Winner (green) and Loser (red)

---

## Learning Summary
- Learned real-world async JavaScript
- Understood API rate limits and error states
- Improved confidence in reading and writing Promise-based code

AI was used strictly for learning, debugging, and explanation purposes.
All final code was written and understood by me.