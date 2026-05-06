# Nightshift Website Team Instructions

This is the simple way to work on the Nightshift Brisbane website with Codex.

## What You Need

1. A GitHub account.
2. Access to this GitHub repo:
   https://github.com/jbpolson/nightshift-brisbane-2026
3. The Codex app installed and signed in.
4. Permission for Codex to access files on your computer.

You do not need to be a coder.

## First-Time Setup

1. Create a GitHub account if you do not already have one:
   https://github.com
2. Ask John to add your GitHub username to the Nightshift repo.
3. Open Codex.
4. Sign in.
5. Allow computer and file access when Codex asks.
6. Give Codex the setup prompt below.

## First Codex Prompt

Copy and paste this into Codex:

```text
I am working on the Nightshift Brisbane 2026 website.

Please clone this GitHub repo to my computer:
https://github.com/jbpolson/nightshift-brisbane-2026

Then open the project folder, check the README and AGENTS.md files, and explain how I should make changes safely.

Do not change any files yet.
```

## How To Ask For A Change

Ask for one clear change at a time.

Good examples:

```text
Change the sponsor email everywhere from events@blacksheep.cc to the new email address.
```

```text
Update the race schedule with these times, then check that the table still works on mobile.
```

```text
Add a new FAQ item about parking. Match the existing FAQ style.
```

```text
Replace the EntryBoss link with this URL everywhere it appears.
```

Avoid vague prompts like:

```text
Make the website better.
```

## Before You Finish A Change

Ask Codex:

```text
Please preview the site, check mobile and desktop, then tell me exactly what changed.
```

Then look at the website yourself.

Check:

- The page still loads.
- Images are visible.
- Text looks clean on mobile.
- Buttons and links still work.
- Dates, times, prices, and event details are correct.

## Saving Your Work

When you are happy with the change, ask Codex:

```text
Please create a new branch, commit this change, push it to GitHub, and open a pull request.
Use a clear branch name and pull request title.
```

John can then review the pull request and merge it.

## Important Rules

- Do not edit the website directly on the GitHub website unless John asks you to.
- Do not ask Codex to rebuild the site in React, Next.js, or another framework.
- Keep each change small.
- If Codex says something is risky or unclear, stop and ask John.
- Do not merge your own pull request unless John says it is okay.

## Useful Links

- Live website: https://nightshift-brisbane-2026.netlify.app
- GitHub repo: https://github.com/jbpolson/nightshift-brisbane-2026
- Netlify admin: https://app.netlify.com/projects/nightshift-brisbane-2026

