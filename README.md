# FMCG Interview Prep Tracker

A personal study dashboard for the FMCG Sales & Commercial Management roadmap (5 levels, 417 topics).
Track your progress, take AI-powered mock tests, and see your readiness score on one page.

**You only need 3 things: a GitHub account, this `index.html`, and 10 minutes.**
The token in Part 4 is optional — skip it if you don't need sync.

---

## What's in this folder

```
your-repo/
├── index.html            ← the whole app
├── README.md             ← this file
└── data/
    └── progress.json     ← your saved progress (used for sync)
```

---

## Part 1 — Create the repository (2 min)

1. Sign in at [github.com](https://github.com).
2. Click the **+** (top right) → **New repository**.
3. Repository name: `fmcg-prep` (any name works).
4. Choose **Public**. (GitHub Pages is free for public repos.)
5. Tick **Add a README file** → click **Create repository**.

> Want it private? GitHub Pages on private repos needs a paid plan. If you go private, skip Parts 2–3 and just open `index.html` from your computer, then use Backup/Load (see Part 5).

## Part 2 — Upload the files (2 min)

1. In your new repo, click **Add file → Upload files**.
2. Drag in `index.html`.
3. Click **Commit changes**.
4. Now create the data file. Click **Add file → Upload files** again and drag in the **`data`** folder containing `progress.json`.
   (If your browser won't accept a folder, click **Add file → Create new file**, type `data/progress.json` as the name, paste the contents of `progress.json`, and commit.)

Check that you can see `index.html` and a `data` folder in the repo.

## Part 3 — Turn on GitHub Pages (1 min)

1. Go to the repo's **Settings** tab.
2. In the left menu click **Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Branch: **main**, folder: **/ (root)** → click **Save**.
5. Wait 1–2 minutes and refresh. A link appears at the top:
   `https://YOUR-USERNAME.github.io/fmcg-prep/`
6. Open it, and **bookmark it** on your phone and laptop. That's your tracker.

The app already works and auto-saves in your browser. Parts 4 and 5 are only for using it across devices.

---

## Part 4 — Optional: sync between phone and laptop (5 min)

Skip this if you use only one device.

### 4a. Make a token

1. On GitHub click your profile picture → **Settings**.
2. Scroll down → **Developer settings** → **Personal access tokens** → **Fine-grained tokens**.
3. Click **Generate new token**.
4. Token name: `fmcg-tracker`. Expiration: choose 90 days or longer.
5. **Repository access → Only select repositories** → choose your `fmcg-prep` repo.
6. **Permissions → Repository permissions → Contents → Read and write**. Leave everything else as it is.
7. Click **Generate token** and **copy it now** (you won't see it again).

### 4b. Connect the tracker

1. Open your tracker link → **Settings** (left menu).
2. Under **Optional: auto-sync with GitHub** fill in:
   - **GitHub username:** your username
   - **Repository:** `fmcg-prep`
   - **File path:** `data/progress.json`
   - **Token:** the one you copied
3. Tick **Sync automatically after changes** (recommended).
4. Click **Save & sync now**. The sidebar should say **Synced**.
5. Repeat step 4b once on your other device (the token is stored per browser).

### How sync works

- It syncs when the page opens, and a few seconds after each change if auto-sync is on.
- The newest copy wins: if GitHub has newer data it loads it, otherwise it uploads yours.
- Your topic progress **and** test scores are both synced.
- Avoid editing on two devices at the same moment. Give it a few seconds to sync before switching.

---

## Part 5 — Backup without GitHub sync

**Settings → Download backup** saves a `progress.json` file. On another device use **Load backup**.
Do this now and then as a safety copy.

---

## How to use the app

| Page | What to do |
|------|-----------|
| **Dashboard** | See readiness score, completion by level, weak areas, charts and recent tests. |
| **Topics** | Update each topic's status, confidence, priority and target date. Click ▾ for notes, resources and company examples. Click 🎯 to quiz yourself on that topic. |
| **Test Lab** | 1) Pick a section. 2) Copy the prompt into ChatGPT, Claude or Gemini and take the test. 3) Type the 5 scores + overall back in. |
| **Settings** | Backup, dark mode, optional GitHub sync, reset. |

### The 5 test scores (each out of 100)
1. Subject Knowledge
2. Thinking & Creativity
3. Problem Solving
4. Connecting with an Example
5. Interview Readiness

The overall score fills in as the average (you can edit it). Every test has at least 10 questions, mixing MCQ and thinking questions.

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Page link shows 404 | Wait 2 minutes after enabling Pages. Check `index.html` is in the repo root (not inside a folder). |
| "Token rejected" | The token was copied wrongly, has expired, or lacks **Contents: Read and write**. Make a new one (Part 4a). |
| "Could not reach repo (404)" | Check the username, repo name and file path for typos, and that the token was given access to this repo. |
| Charts are empty or missing | Charts need an internet connection the first time. Refresh with internet on. |
| Copy button doesn't work | Click inside the prompt box, press Ctrl+A then Ctrl+C (Cmd on Mac). |
| Progress looks lost | Open the page in the same browser you used before. If you cleared browser data, use Load backup or GitHub sync. |
| Updated `index.html` but nothing changed | Hard refresh (Ctrl+Shift+R), or wait a minute for GitHub Pages to update. |

## Updating the app later

Go to your repo → click `index.html` → the pencil (edit) icon, or **Add file → Upload files** and upload the new `index.html`. Your progress stays safe because it lives in `data/progress.json`, not in `index.html`.

## Privacy note

Your token is saved only in your own browser and is never written into the code. Use a token limited to this one repo so it can't touch anything else. If the repo is public, anyone with the link can see your progress file, but they can't edit it.
