# Nightshift Brisbane 2026

Static event site for Nightshift Brisbane, an after-dark criterium racing event at Murarrie Criterium Track on 20 June 2026.

## What Is In This Project

- `index.html` is the website.
- `assets/images/` contains the event images and logo.
- `assets/fonts/` contains the local font files used by the design.

There is no build step. The site can be opened directly in a browser, or hosted as a static site on GitHub Pages, Netlify, or Vercel.

## How To Preview Locally

Open `index.html` in your browser.

If you prefer a local server, run this from the project folder:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Suggested Team Workflow

Use one branch per change. Keep each Codex task small and specific.

1. Create a new branch from `main`.
2. Ask Codex to make one clear change.
3. Preview the page in a browser.
4. Commit the change.
5. Open a pull request.
6. Review the preview URL.
7. Merge when approved.

Good branch names:

```text
codex/update-schedule
codex/add-sponsor-copy
codex/mobile-polish
codex/entryboss-link
```

## Good Codex Prompts For Non-Coders

Use concrete requests:

```text
Change the event date everywhere from 20 June 2026 to the new confirmed date.
```

```text
Update the race schedule section with these times, then check that the table still works on mobile.
```

```text
Replace the EntryBoss link with this URL and make sure every Enter Now button uses it.
```

```text
Add a new FAQ item about parking, matching the existing FAQ style.
```

```text
Review the page for mobile layout issues and fix anything obvious.
```

Avoid broad requests like:

```text
Make the site better.
```

## Review Checklist

Before merging a pull request, check:

- The page loads without missing images.
- The mobile layout still looks clean.
- Buttons and links go to the right places.
- Dates, times, prices, and licence details are correct.
- Sponsor and partner copy has been approved.

## Recommended Hosting

For a non-coder team, Netlify is the easiest option because every pull request gets a preview link.

GitHub Pages is also fine for a simple static site, but PR previews are less friendly.

## Project Links

- Live site: https://nightshift-brisbane-2026.netlify.app
- GitHub repo: https://github.com/jbpolson/nightshift-brisbane-2026
- Netlify admin: https://app.netlify.com/projects/nightshift-brisbane-2026
