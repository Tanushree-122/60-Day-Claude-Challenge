# Day 4: Core Feature Implementation

**Project:** Optimised Retail Inventory System  
**Challenge:** AB Talks 60-Day Claude Challenge — 10-Day Capstone  
**Day:** 4 of 10

---

## 1. Source of Truth

Before writing any code, read the **Day 4 section of the approved 10-Day Implementation Blueprint** and review the relevant PRD and system-design documents.

These documents determine today's features, files, APIs, and tests.

- Do not redesign the project.
- Do not replace approved technology choices.
- Do not start features assigned to Day 5 or later.
- Do not guess today's scope if the Blueprint is unavailable.

If the Day 4 Blueprint is missing, ask me to upload it before deciding what to implement.

## 2. Working Rules

- Assume I am a beginner unless I say otherwise.
- Prioritise implementation over lengthy explanations.
- Work on one milestone at a time.
- Briefly explain what we are building and why.
- Give exact numbered instructions for every manual task, including real button names, menu names, file paths, and terminal commands.
- After each manual step, stop and wait for my confirmation and screenshot.
- Never assume a file was created, a command succeeded, or a feature works without evidence.
- Generate complete, copy-pasteable files. Never provide snippets, placeholders, TODOs, ellipses, or “add this below” instructions.
- Clearly identify every file as new, modified, replaced, or deleted.
- Include every command required to install dependencies, run the application, and test the feature.
- If anything fails, debug it completely before moving forward.
- Shorten the process when necessary, but never skip required functionality.
- Do not recommend paid services unless I ask.

## 3. Milestone Workflow

For each milestone:

1. **Scope:** Identify the exact feature scheduled for Day 4 in the Blueprint.
2. **Purpose:** Briefly explain what will be built and why.
3. **Files:** List every file to create, modify, replace, or delete, with its exact path.
4. **Implementation:** Provide the complete final contents of every required file.
5. **Commands:** Give exact commands to install dependencies, start services, and run tests.
6. **Checkpoint:** Ask me to complete the step, run the project, test the feature, and share a screenshot or error output.
7. **Debugging:** Resolve errors before starting the next milestone.
8. **Verification:** Record the observed result and any remaining limitations.

**Do not proceed to the next milestone until I have tested the current milestone and confirmed the result.**

## 4. Implementation Requirements

- Follow the approved architecture, database schema, API contracts, and folder structure.
- Implement only features explicitly scheduled for Day 4.
- Write maintainable, production-quality code appropriate to the approved stack.
- Apply client-side and server-side validation where required.
- Handle loading, success, empty, and error states where relevant.
- Keep secrets out of source control. Use environment variables and safe example files.
- Do not use mock data or fake API responses as substitutes for required backend functionality.
- Avoid unnecessary libraries and services.
- Do not silently change database schemas, API contracts, or architectural decisions.
- If a critical issue requires a design change, explain the issue and ask me before proceeding.
- Never claim that a feature is implemented or verified until I have run and tested it.

## 5. Testing and Verification

For every Day 4 feature, verify the applicable checks:

- [ ] The application starts successfully.
- [ ] The feature is accessible through the intended user flow.
- [ ] Valid input is handled correctly.
- [ ] Invalid input produces a useful error.
- [ ] Data is saved and retrieved through the approved backend and database, where applicable.
- [ ] Loading, empty, success, and error states work where relevant.
- [ ] Existing functionality continues to work.
- [ ] Browser console and terminal have no unresolved errors.
- [ ] Automated tests pass, if a test suite exists.

Record actual results. Never mark a check complete without verification.

## 6. Documentation Updates

After implementation and verification, update only the documentation affected by today's changes. Depending on the work completed, this may include:

- `README.md`
- `API.md`
- `SCHEMA.md`
- `ARCHITECTURE.md`
- `PROJECT-STRUCTURE.md`
- `DAY4-SUMMARY.md`

Document only behavior that exists in the code. Record justified deviations from the Blueprint and explain their reasons.

## 7. Git Commit and Push

After I have tested the feature:

1. Review `git status`.
2. Review the changed files.
3. Confirm that secrets and local-only files are not staged.
4. Run relevant tests.
5. Stage only the intended files.
6. Create a meaningful commit, for example:

   `feat: implement Day 4 core inventory feature`

7. Push the current working branch to GitHub.
8. Ask me to confirm the push or share a screenshot of the repository.

Use commands appropriate to the actual repository and branch. Do not assume GitHub is already connected.

## 8. Deployment

Deploy only if the Day 4 Blueprint schedules deployment or the application is genuinely ready to deploy today.

- Use the platform selected in the approved Blueprint.
- Explain account setup, configuration, environment variables, and deployment steps.
- Never expose secrets.
- Wait for me to share a screenshot of the live application.
- Verify the deployed feature before claiming deployment is complete.

Do not let deployment work displace the required Day 4 implementation.

## 9. End-of-Day Handoff

When every Day 4 feature has been implemented and verified, provide a concise report.

### Completed today
- List only features I have verified.
- Include tests run and actual results.
- Include commit and deployment status, if applicable.

### Remaining issues
- List unresolved bugs and incomplete checks.
- Explain whether any issue blocks Day 5.

### Tomorrow
- Summarise the next objective using the Day 5 section of the approved Blueprint.
- Do not begin Day 5 implementation during this session.

## 10. Start Here

**First action:** Read the Day 4 section of the approved 10-Day Blueprint.

If the Blueprint is unavailable in the current conversation or accessible project files, ask me to upload it. Once it is available, identify the exact Day 4 scope and begin Milestone 1.

**Do not generate feature code until today's scheduled scope is confirmed.**
