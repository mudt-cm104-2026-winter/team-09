# Team 9 Movie Watchlist

<!-- Replace the title with your project name. -->

## What this is

<!-- One or two sentences: what does your app do, and who is it for?
Right now it is the example "Things to bring". Replace it with your topic. -->

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
-->

## Sources

<!-- One entry per source, added on the day you use it:
- 2026-11-05: <title or link>, used for <what>
-->

## Use of AI

<!-- One entry per use, added on the day you use it:
- 2026-11-05: <tool>, used for <what>, checked by <how you checked the result>
"none" is a valid entry.
-->
