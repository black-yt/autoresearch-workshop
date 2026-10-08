# Auto Research — ICLR 2027 Workshop Proposal

Public website: **https://black-yt.github.io/autoresearch-workshop/**

Language Model Agents for End-to-End Research Workflows.

This is a workshop proposal. Acceptance at ICLR 2027, the workshop day, and the contribution program are not yet confirmed. The site intentionally presents proposed dates and formats, without a live paper-submission button or an unconfirmed speaker roster.

## Publish

This is a static HTML/CSS site with no external scripts, fonts, or build dependencies.

GitHub repository **Settings → Pages → Build and deployment**:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**

The `.nojekyll` file keeps publishing simple. GitHub Pages publishes updates after a push to `main`.

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Maintain

- `index.html`: workshop scope, proposed contribution policies, dates, program, organizer profiles, and contact.
- `styles.css`: responsive layout and visual design.
- `assets/organizers/`: web-sized organizer portraits. Wanghan Xu's photo uses the portrait provided by the organizer.
- `assets/favicon.svg`: site mark.

Only Wanghan Xu is currently confirmed. The previous organizer roster was withdrawn on October 8, 2026. Six additional organizers and eight speaker candidates are being considered privately; candidates are not listed on this public website before consent.

After acceptance, update the status notice, final date, confirmed invited program, contribution dates, and actual OpenReview submission link together. Keep the site and proposal synchronized. Do not mark candidates as confirmed participants before agreement is obtained.

The local LaTeX project, Overleaf archive, internal handoff notes, and historical proposal materials are maintained separately from this public website repository.

Contact: [xu_wanghan@sjtu.edu.cn](mailto:xu_wanghan@sjtu.edu.cn).
