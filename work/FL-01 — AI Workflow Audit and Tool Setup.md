# FL-01 — AI Workflow Audit and Tool Setup

**Track:** General AI Fluency  
**Week:** 1  
**Prepared for:** Sabeen Saeed  
**Status:** Drafted for personal verification and evidence attachment

## Purpose and method

This audit maps recurring work in my current week as an ML-internship learner and GitHub-based project builder. I am not treating AI as an authority. I will use it where it reduces repetitive work or helps me reason, while keeping human responsibility for goals, privacy, judgment, claims, and final submission decisions.

## 1. Recurring-work audit

| # | Recurring task from my week | Classification | Why this classification is appropriate |
|---:|---|---|---|
| 1 | Choose an assignment direction and turn a broad brief into one research question | Collaborate with AI | AI can propose alternative framings and expose missing decisions, but I must choose the question because I understand my learning goals and constraints. |
| 2 | Decide whether a result is strong enough to submit and whether the wording overclaims | Just me | This is an accountability and judgment task. I can ask AI to critique wording, but I retain responsibility for honesty and the final claim. |
| 3 | Read the lane guide, data dictionary, and assignment instructions | Delegate to AI with review | AI can summarize long instructions and extract requirements quickly; I must check the summary against the source before acting. |
| 4 | Load the starter CSV and calculate descriptive statistics | Collaborate with AI | AI can draft pandas code and suggest useful checks, while I inspect the columns, run the code, and decide what the numbers mean. |
| 5 | Write or revise a notebook code cell | Collaborate with AI | AI is useful for first drafts and explanations, but I need to understand every line, test it locally, and avoid copying code that leaks or mislabels data. |
| 6 | Debug Python, package, path, or notebook-execution errors | Collaborate with AI | AI can suggest hypotheses and small tests; I must run the tests, read the traceback, and confirm the fix rather than accepting an untested guess. |
| 7 | Run all notebook cells and check that outputs are saved | Delegate to AI with review | A repeatable execution command can be delegated, but I must inspect for errors, stale outputs, missing cells, and environment-specific behavior. |
| 8 | Compare a baseline with a model using a named metric | Collaborate with AI | AI can help implement the metric and comparison table, but I must choose an honest baseline, check leakage, and interpret the result. |
| 9 | Write the assignment explanation in clear, careful language | Collaborate with AI | AI can improve structure and readability, while I supply the actual experience and verify that the final text sounds like me and makes only supported claims. |
| 10 | Commit notebook work and push it to the correct GitHub path | Delegate to AI with review | The command sequence is repeatable and easy to check with `git status` and the remote URL; I must review the staged files and confirm no private data is included. |
| 11 | Verify the public repository, file path, commit, and visible notebook outputs | Just me | The final submission check is my responsibility. I need to open the public link and confirm that the deliverable a reviewer sees is the one I intended. |
| 12 | Keep track of assignment deadlines, evidence, and next actions | Delegate to AI with review | AI can turn briefs into checklists and reminders, but I must confirm dates and decide what I can realistically complete. |

Two tasks are deliberately classified **Just me** because they involve accountability rather than text or code production. AI may critique them, but it should not make the final submission decision or decide whether my evidence supports a claim.

## 2. Three target tasks for FL-02 through FL-04

### Target task A — Assignment brief to executable plan

I will use AI to convert each new assignment brief into a short plan containing the deliverable path, required evidence, dependencies, risks, and a first 30-minute action. It is done well when the plan contains every explicit requirement from the brief, separates facts from assumptions, names at least one verification step, and fits on one page. I will check it by comparing the plan against the original brief and marking every requirement as covered, pending, or not applicable.

### Target task B — Notebook coding and debugging with review

I will use AI as a coding partner for pandas, scikit-learn, Jupyter, and Git troubleshooting. It is done well when the proposed code is runnable, uses the repository’s existing paths and package constraints, includes a small test or assertion, and can be explained by me in plain language. For each use, I will record the error or goal, the suggestion, the change I made, and the verification result. No code is accepted solely because it looks plausible.

### Target task C — Evidence-backed submission quality check

I will use AI to audit a finished assignment before submission. It is done well when the audit checks the exact required path, execution status, visible outputs, completeness of evidence, privacy risks, and claim strength, and produces no more than five concrete fixes. I will verify the fixes myself by opening the public repository and rerunning or inspecting the relevant notebook. The final “submit” decision remains mine.

## 3. Tool setup and evidence checklist

| Requirement | What I need to do | Evidence to place in the repository |
|---|---|---|
| ChatGPT account | Confirm that I can sign in to ChatGPT with my own account. | Optional screenshot or account confirmation note; never include a password or private token. |
| Claude account | Create or confirm a free Claude account and sign in. | Optional screenshot of the signed-in account; redact personal details if needed. |
| Anthropic Academy | Enroll in **AI Fluency: Framework & Foundations** and complete at least Module 1. | Screenshot of enrollment or completed first-module status, with personal identifiers minimized. |
| Claude Project | Create one project named **ML Internship Workflow**. | Screenshot saved as `work/evidence/fl01_claude_project.png`. |
| Claude Project instructions | Add the custom instructions below. | The screenshot should show the project name and instructions, or this markdown plus the screenshot can serve as evidence. |

### Custom instructions for the Claude Project

> I am Sabeen Saeed, completing a practical machine-learning internship while building public GitHub notebooks. Help me turn assignment briefs into executable plans, explain Python and ML code in plain language, debug carefully, and audit notebooks before submission. Use a professional, concise, supportive tone. Prefer simple, reproducible methods and show verification steps. Distinguish facts, observations, assumptions, and recommendations. Never invent dataset values, claim causation from observational data, or expose private credentials, client names, URLs, queries, or personal information. Ask before making an irreversible change. For every recommendation, state what I should check myself. My current goals are to complete the weekly assignments, build honest data-backed ML work, improve my Git/Jupyter workflow, and submit clean public repositories on time.

## 4. Evidence status

- [x] Audit contains 12 recurring tasks that match my current ML-internship and GitHub workflow.
- [x] Every task has one classification and a one-line rationale.
- [x] At least two tasks are marked **Just me** with reasons.
- [x] Three target tasks are specific and have measurable definitions of “done well.”
- [ ] ChatGPT account confirmed.
- [ ] Claude account confirmed.
- [ ] Anthropic Academy Module 1 completed.
- [ ] Claude Project created with the custom instructions above.
- [ ] Screenshot saved at `work/evidence/fl01_claude_project.png`.
- [ ] This audit and evidence are committed to the public repository.

## References

[1]: https://www.anthropic.com/academy "Anthropic Academy"  
[2]: https://support.anthropic.com/en/articles/9517075-what-are-projects "What are Projects? — Claude Help Center"
