# AGENTS.md

Instructions for an AI agent updating the README.md in this repository, which is Newton Chung's GitHub profile page.

## When to run

On demand only. Do not update the profile on a schedule or automatically. Only act when Newton explicitly asks for a profile update (e.g. "update my GitHub profile," "check for new work to add").

## Scope

When asked to check for new work, scan Newton's public repositories under the NewtonLC GitHub account. For each repository, check:

- Whether it was created or had meaningful activity since the README's last update (see the most recent commit date on this file's history).
- Recent merged pull requests and commit activity, not just repo existence.
- Whether the repo already appears in the README, and if so, whether its description is stale.

Do not scan private repositories or other people's repositories unless Newton names one directly.

## Process

1. Pull the current README.md and note what it already says about each project.
2. Scan for candidate repos per the Scope section above.
3. For each candidate (new or changed), draft a short summary of what it appears to be, based only on what is verifiable from the repo (README, commit messages, language stats, linked deploy URL). Do not guess at scope, impact, or role.
4. Identify existing entries that look stale (no activity in months, superseded by newer work) and flag them as removal/edit candidates. Do not remove anything without asking.
5. Present findings to Newton along with clarifying questions (see below). Do not edit README.md yet.
6. Wait for Newton's answers and explicit sign-off on the proposed text.
7. Only after sign-off, edit README.md and commit. Do not push without Newton confirming the diff first.

## Questions to ask before writing anything

For each new or changed project being added or updated, ask:

- What was your role and actual scope of contribution? (Don't assume "lead" or "sole author.")
- Is this project active, paused, or finished?
- Is there a live URL or demo link to include?
- What's the real tech stack, not just what's visible from file extensions?
- Should this replace something currently listed under "What I'm Working On," or is it a net addition?
- Is anything about this project confidential or not to be named publicly (e.g. employer NDA, unreleased work)?
- Is there a specific outcome or detail worth stating (users, scale, a concrete result), or should it stay descriptive?

For stale entries being considered for removal:

- Should this move to a "Past Work" section, or be deleted outright?
- Is it still accurate as written, or has the status changed (e.g. no longer looking for work, no longer a student)?

Never finalize wording without answers to the questions that apply. If Newton doesn't respond to a question, leave that entry unchanged rather than guessing.

## Voice and style

- No em-dashes, ever. Use a colon, a comma, or split into two sentences instead.
- No emoji used as section headers, bullet markers, or decoration.
- No exclamation points on factual statements. Reserve them for actual excitement, not for describing what a project does.
- Avoid stock enthusiasm phrases: "I'm passionate about," "I care deeply about," "excited to," "cutting-edge," "leverage," "dive into," "seamless," "robust." Replace with a concrete fact instead of an adjective.
- Avoid the "It's not just X, it's Y" and "Whether it's X or Y" sentence patterns.
- Avoid rule-of-three lists where the items are vague rather than specific (e.g. "innovative, scalable, and impactful"). Every list item should be checkable against something real.
- Don't open sentences with "Additionally," "Furthermore," or "Moreover." Start the next sentence directly, or combine the two.
- Default to specific, verifiable detail over general claims. If a sentence could describe thousands of other people's projects, cut it or make it specific.
- Vary sentence length. Avoid a run of uniform, medium-length sentences.

## Structural notes

- Preserve the existing section order (intro, What I'm Working On, What I'm Learning, Tech Stack, About Me, GitHub Stats, Connect) unless Newton asks to restructure.
- Keep entries in "What I'm Working On" to active projects only. Move or cut anything inactive per the process above.
- Do not add new badges, stats widgets, or sections without asking first.
