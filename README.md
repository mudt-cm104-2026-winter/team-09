# Team 9 Movie Watchlist

<!-- Replace the title with your project name. -->

## What this is

Movie Watchlist is a small web app for our team: you add a movie you want
to watch with its title and genre, and the app shows all movies in a list.

## How to run it

You need Python 3.10 or newer.

```bash
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Then open http://127.0.0.1:8000 in your browser. Stop it with `Ctrl+C`.

The entries are kept in memory: after a restart the list is empty again.

## Team

<!-- One row per person: GitHub username and what you mainly take care of.
No real names: this repository is public. -->

| GitHub | Role |
|---|---|
|Kevin|Team member|
|Taha|Team member|
|Ecem|Team member|
## How we work

- Every piece of work starts as an issue on our board "Team 9 Board", under one of our three epics: Entries, Page, Docs.
- For each issue we create a branch from `main`, named after the issue, for example `11-rename-fields`.
- We commit in small steps with messages that say what changed.
- Every change goes into `main` through a pull request. The description follows our template and contains `closes #n`.
- `main` is protected by a ruleset: no direct pushes, every pull request needs one approval from another team member.
- The reviewer comments on at least one line and chooses Approve or Request changes.
- We merge with "Create a merge commit". Every pull request adds one line to `CHANGELOG.md`.

## Sources

- 2026-11-16: Course materials (assessment-1-team-project.md, expert sheets A, B, C), used for the checklist, the ruleset and the PR template
- 2026-11-16: GitHub Docs "Planning and tracking with projects", used for setting up our board
- 2026-11-16: GitHub Docs "Creating rulesets for a repository", used for protecting main
- 2026-11-16: GitHub Docs "Reviewing proposed changes in a pull request", used for reviews

## Use of AI

- 2026-11-16: Claude (Anthropic), used by Ecem for planning our team workflow and the issue texts, checked by comparing the plan with the Assessment 1 checklist
- 2026-11-16: Claude (Anthropic), used by Taha for explaining the assignment, checking our repository against the checklist, helping with the topic and task split, writing issue texts, and step-by-step guidance for issue #7 and PR #8 (PR template), checked by reading the files on GitHub and by Kevin's review
- 2026-11-17: Claude (Anthropic), used by Taha for step-by-step guidance on Git setup, the ruleset push test and PR #18 (#13 page texts), checked by reading the terminal output and git diff
- 2026-11-22: Claude (Anthropic), used by Ecem for step-by-step help with PR #21 and the review of #19, checked by reading the changes on GitHub and by Taha's review of #21
- 2026-11-22: Claude (Anthropic), used by Kevin for reading Ecem's review on #19 and explaining the two fixes (`<tr>` in the table header, `(#11)` in the CHANGELOG), checked by Ecem's review and approval of #19
- 2026-11-22: Claude (Anthropic), used by Kevin for step-by-step help with merging main into the #20 branch on his laptop, resolving the CHANGELOG conflict and fixing Taha's review comments, checked by Taha's review and approval of #20
- 2026-11-22: Claude (Anthropic), used by Kevin for comparing our team plan with the state of the repository and planning the next steps, checked by looking at the PRs and issues on GitHub himself
- 2026-11-22: Claude (Anthropic), used by Taha to install GitHub CLI and to write and post his reviews on PR #20 (Request changes, then Approve after the fix) and PR #21 (Approve) with his permission, checked by Taha reading the comments on GitHub
- 2026-11-23: Claude (Anthropic), used by Kevin for drafting the text of issue #22 (remove button) and explaining why his local files were different from GitHub (wrong branch checked out), checked by comparing the files in VS Code with GitHub after switching to main
- 2026-11-23: Claude (Anthropic), used by Ecem for checking the repository state, planning the remaining steps and the text of issue #23 (sorting), checked by looking at the PRs and issues on GitHub herself
- 2026-11-23: Claude (Anthropic), used by Taha to write the A–Z sorting in app/main.py and to open PR #24 (#23) on his behalf with his permission, checked by a local test of the sort and by Ecem's review
- 2026-11-23: Claude (Anthropic), used by Taha to review Kevin's PR #25 (#22 remove button) and post an Approve with two line comments on his behalf, checked by Taha reading the review on GitHub
- 2026-11-24: Claude (Anthropic), used by Ecem for understanding the sort line in PR #24 and writing the review question, checked by Taha's answer on the PR
- 2026-11-24: Claude (Anthropic), used by Taha to solve the CHANGELOG merge conflict in PR #24 on his laptop (git merge origin/main, kept both lines) with his permission, checked by a local test and GitHub showing the PR as mergeable
- 2026-11-24: Claude (Anthropic), used by Taha for explaining the sort line in PR #24 and helping him write the answer to Ecem's review question, checked by Taha explaining casefold() and sorted() back in his own words
- 2026-11-24: Claude (Anthropic), used by Taha to merge PR #24 after Ecem's approval on his behalf, checked by Taha on GitHub (PR merged, issue #23 closed)
- 2026-11-24: Claude (Anthropic), used by Kevin for suggesting a dark "cinema" design for the page and writing the new style.css and the small changes in index.html (genre tag, 🎬 in the title), checked by running the app locally and looking at the page in the browser
- 2026-11-25: Claude (Anthropic), used by Kevin for the text of issue #26 and step-by-step help with committing, the CHANGELOG line, pushing and opening the pull request, checked by comparing the pull request with our template and the "How we work" rules
- 2026-11-25: Claude (Anthropic), used by Kevin for fixing "uvicorn not found" when starting the app (virtual environment was not activated), checked by starting the app again and opening it in the browser
- 2026-11-25: Claude (Anthropic), used by Kevin for checking our repository against the teachers' interim status list for Assessment 1, checked by looking at the README, pull requests and issues on GitHub ourselves
- 2026-11-25: Claude (Anthropic), used by Taha to review Kevin's PR #27 (#26 dark cinema look) and post an Approve with one line comment on his behalf, checked by Taha reading the review on GitHub
- 2026-11-25: Claude (Anthropic), used by Ecem for checking the repository state against the Assessment 1 checklist, combining the team's AI entries and planning the last steps, checked by looking at the PRs, issues and README on GitHub herself
- 2026-11-16 to 2026-11-25: Claude (Anthropic), used by Taha to check the status of our pull requests, explain the team plan and draft chat messages to the team, checked by Taha comparing it with GitHub
