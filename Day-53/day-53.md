# Day 3: Project Setup & Foundation

**Project:** Optimised Retail Inventory System  
**Challenge:** AB Talks 60-Day Claude Challenge — 10-Day Capstone  
**Day:** 3 of 10

---

## 1. Source-of-Truth Documents

Before starting Day 3, review these documents from previous days:

- Product Requirements Document (PRD)
- 10-Day Implementation Blueprint
- System Design Documents
- `ARCHITECTURE.md`
- `SCHEMA.md` — Database Design
- `API.md` — API Design
- `PROJECT-STRUCTURE.md` — Project Structure

These documents are the source of truth. **Do not redesign the project unless a critical issue is discovered.** If any required document is unavailable, ask the user to upload it before proceeding with implementation. Do not invent missing requirements or silently replace approved decisions.

---

## 2. Standing Rules

1. Assume the user needs guidance for every manual step unless they say otherwise.
2. For tasks outside the chat, give exact numbered instructions using the real buttons, menu names, commands, and terminal steps.
3. After each manual step, stop and wait for the user's confirmation and screenshot before continuing.
4. Never assume a manual task has been completed.
5. Explain technical concepts in beginner-friendly language before using them.
6. Follow the approved Day 3 section of the 10-Day Blueprint.
7. Do not implement core product features yet, unless the Day 2 blueprint explicitly schedules a small foundation feature.
8. Do not recommend paid services unless the user asks.

---

## 3. Today's Goal

Build the technical foundation so the project is ready for feature development.

By the end of Day 3, aim to have:

- [ ] Development environment configured
- [ ] Project running locally
- [ ] Complete folder structure created according to the approved design
- [ ] Git repository initialized and connected to GitHub
- [ ] Dependencies installed
- [ ] Configuration files prepared
- [ ] Database connected, if required by the approved design
- [ ] Authentication scaffolded, if required by the approved design
- [ ] Basic navigation and routing working
- [ ] A working “Hello World” version of the application
- [ ] Build and runtime checks completed

These are target outcomes, not claims that the work has already been completed. Record the actual result of each check during the session.

---

## 4. Environment Setup

Guide the user through installing and configuring every tool required by the approved project design. Depending on the source documents, this may include:

- Runtime
- IDE and relevant extensions
- Package managers
- Framework CLI tools
- SDKs
- Environment variables

For every tool:

1. Explain what it is in beginner-friendly language.
2. Explain why the project needs it.
3. Provide official installation guidance where appropriate.
4. Give exact installation and verification commands.
5. Ask the user to run the step and share confirmation or a screenshot.
6. Troubleshoot any errors before moving forward.

Do not add tools that are not required by the approved design without explaining why and obtaining agreement.

---

## 5. Project Initialization

Guide the user step by step through:

1. Creating or opening the project directory.
2. Creating the approved folder structure.
3. Initializing the frontend and backend using the approved stack.
4. Installing the required dependencies.
5. Creating configuration files and safe environment-variable templates.
6. Starting the application locally.
7. Verifying that the application loads and the required services start correctly.

Explain the purpose of each major command and file. Pause after each manual step for confirmation and a screenshot.

---

## 6. Repository Setup

If repository setup is not already complete:

1. Check whether Git is installed and configured.
2. Initialize Git in the project directory if necessary.
3. Create or connect the GitHub repository.
4. Configure the remote repository.
5. Create appropriate branches.
6. Explain the branch strategy in beginner-friendly terms.
7. Check that secrets, local environment files, dependencies, and generated files are handled correctly in `.gitignore`.
8. Make the initial commit only after the user has reviewed the files.
9. Push the branch to GitHub and verify the result.

Example commit message:

```text
chore: initialize project foundation
```

Do not commit real credentials, API keys, database passwords, or private environment files.

---

## 7. Build the Foundation

Implement only the foundational pieces required by the approved PRD, blueprint, and system design. Depending on those documents, this may include:

- Basic routing
- Application layout and navigation
- Authentication scaffold, if required
- Database connection, if required
- API client configuration
- Shared components
- State-management setup, if required
- Environment/configuration handling
- Health-check or starter endpoint, if specified

For each major file created or modified, explain:

- Its path
- Its responsibility
- Why it is needed
- How it connects to the rest of the application

Do not build inventory CRUD workflows, stock movements, alerts, analytics, or other core features unless the approved Day 2 blueprint explicitly places a small foundation feature on Day 3.

---

## 8. Verify the Project

Run the appropriate checks for the approved stack and record the actual results.

- [ ] Frontend starts successfully.
- [ ] Backend starts successfully, if applicable.
- [ ] The application builds successfully.
- [ ] No unresolved startup or build errors remain.
- [ ] Basic navigation and routing work.
- [ ] Database connectivity works, if required.
- [ ] Authentication scaffold works, if required by the plan.
- [ ] Environment variables are read from configuration rather than hardcoded secrets.
- [ ] Folder structure matches the approved system design.
- [ ] Git status is understood and no secrets are staged.
- [ ] The repository is connected to GitHub and the intended changes are pushed.

If any check fails, stop and debug it before proceeding. Do not mark a check complete without evidence.

---

## 9. Deliverables

Create and maintain the following Markdown documents based on the actual project setup and the approved source documents.

### `SETUP.md`

Include:

- Prerequisites
- Installation instructions
- Dependency installation
- Database setup, if applicable
- Environment setup
- Frontend and backend run commands
- Verification steps
- Common errors and fixes

### `PROJECT-STRUCTURE.md`

Update the approved project structure only if the implementation requires a justified change. Explain the purpose of each important directory and file. Preserve the existing design unless a critical issue is discovered.

### `ENVIRONMENT.md`

Document:

- Required tools and versions, where known
- Environment-variable names
- What each variable is used for
- Which variables are required or optional
- Safe example values or placeholders
- Where local values should be configured
- Which files must never be committed

**Never include real secrets or passwords.** Keep `.env.example` free of credentials.

### `DAY3-SUMMARY.md`

Record:

- Work actually completed
- Commands and configuration added
- Files created or modified
- Verification commands and their results
- Issues encountered and resolutions
- Any justified deviation from the blueprint
- Work remaining, if any
- Readiness for Day 4

### Blueprint update

Update the 10-Day Blueprint only if today's implementation requires a change. Record the reason and impact instead of silently changing the plan.

---

## 10. End-of-Day Git and Project Log

Once the user has verified the work:

1. Review `git status`.
2. Review the changed files.
3. Confirm that no secrets or local-only files are included.
4. Stage the intended files.
5. Create a meaningful commit.
6. Push the branch to GitHub.
7. Verify that the commit appears in the remote repository.
8. Update the project log with completed work, test results, blockers, and next steps.

Provide exact commands appropriate to the actual repository state. Do not assume the remote, branch, or files exist before checking.

---

## 11. LinkedIn Progress Post

At the end of the day, help write a LinkedIn post summarizing the work that was actually completed. The post should:

- Identify this as Day 3 of the 10-Day Capstone
- Name the Optimised Retail Inventory System
- Highlight verified setup and foundation milestones
- Share one technical learning or takeaway
- Avoid claiming unfinished tasks are complete
- Include an engagement question and relevant hashtags
- Thank Anthropic, Anil Bajpai, and ABTalksOnAI

Write the post only after the actual progress is known.

---

## 12. Final Day 3 Handoff

### Completed today
List only verified accomplishments.

### Ready for tomorrow
Identify the foundation that is genuinely ready for feature work and list any remaining blockers honestly.

### Day 4 objective
Begin implementing the first major user-facing feature according to the approved 10-Day Blueprint. Day 4 should not require additional setup or planning unless a blocker is discovered.

---

## 13. Required Working Method

**Work one manual step at a time.** Explain the step, provide exact instructions, then wait for the user's confirmation and screenshot. If a source document is missing, request it before making decisions that depend on it. Keep the approved PRD, 10-Day Blueprint, and system design as the source of truth.
