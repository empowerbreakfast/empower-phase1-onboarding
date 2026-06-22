# emPower Breakfast — Phase One Onboarding Site
## GitHub Pages Setup Guide

This is a **separate, standalone site** from your full Area Director training portal. It exists for one purpose: onboarding brand-new ADs through Phase One *before* they get access to the full training library.

---

## What's in This Package

```
phase1_site/
├── index.html                       ← Phase One onboarding homepage
├── assessment.html                  ← 25-question quiz (self-contained)
├── emPower_Phase1_StudyGuide.docx   ← Downloadable study guide
└── css/
    └── site.css                    ← Shared site styling
```

---

## Step 1 — Create a New (Separate) GitHub Repository

This should be a **different repository** from your full AD training site — keep them independent.

1. Go to https://github.com and log in
2. Click **+** → **New repository**
3. Name it something distinct, e.g. `empower-phase1-onboarding`
4. Set visibility to **Public**
5. Click **Create repository**

---

## Step 2 — Upload Your Files

1. Click **uploading an existing file**
2. Drag in the contents of the `phase1_site` folder — `index.html`, `assessment.html`, the `.docx` file, and the `css` folder
3. Make sure `index.html` lands at the **root** of the repo (not inside a subfolder)
4. Commit the changes

---

## Step 3 — Enable GitHub Pages

1. In the repository, go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**

Your Phase One onboarding site will be live at:
**https://YOUR-USERNAME.github.io/empower-phase1-onboarding/**

---

## Step 4 — Add Your Narrated Video Link

1. Record your Phase One narration (script provided separately) using ElevenLabs
2. Upload the finished MP4 to Google Drive, set sharing to "Anyone with the link"
3. Copy the link
4. In `index.html`, find:
   ```
   href="YOUR_VIDEO_LINK_HERE"
   ```
   Replace it with your video link, then re-upload the file to GitHub

---

## How This Site Fits Into Your Overall Process

| Stage | Site |
|---|---|
| New AD signs on | **This site** — Phase One Onboarding |
| AD passes Phase One assessment | You manually grant access to the full portal |
| AD recruits 2 Sponsors | Tracked by you/Jim/Michael outside the site |
| AD becomes full Area Director | Full AD Training Portal (your other GitHub site) |

This site intentionally does **not** link out to the full AD portal — that access is something you grant manually once Phase One and the Sponsor requirement are both met. This keeps new ADs focused on just the onboarding step until they've earned access to the rest.

---

## Updating This Site Later

If Phase One content changes, upload a revised PowerPoint to Claude and mention it's for "the Phase One onboarding site" — you'll get back an updated `index.html`, `assessment.html`, and study guide to swap in here.

---

## Questions?

Contact Jim Barger (jimbarger@empowerbreakfast.org) or Michael McKee (michaelmckee@empowerbreakfast.org).
