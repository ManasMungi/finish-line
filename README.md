# Finish Line: User Guide

Finish Line is a free running app that turns your runs into **race-time predictions** and a **two-week training plan** for your next marathon or half marathon. It tells you how your training is going, what to run tomorrow, how fast to run it, and when your shoes need replacing.

It costs nothing, needs no account or subscription, and works offline. Your data stays on your phone.

---

## Contents

1. [Install the app](#1-install-the-app)
2. [Set up in 5 minutes](#2-set-up-in-5-minutes)
3. [Log your runs](#3-log-your-runs)
4. [Import from Strava](#4-import-from-strava)
5. [The Overview screen](#5-the-overview-screen)
6. [Your training plan](#6-your-training-plan)
7. [Settings](#7-settings)
8. [Back up your data](#8-back-up-your-data)
9. [Questions and fixes](#9-questions-and-fixes)

---

## 1. Install the app

### Put it online (one time, free)

1. Create a free account at **github.com**, then make a new **public** repository, for example `finish-line`.
2. Click **Add file → Upload files** and upload everything from `finish-line-app.zip`: `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-192.png` and `icon-512.png`.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main`, and click **Save**.
4. After a minute or two, your app is live at `https://<your-username>.github.io/finish-line/`.

### Add it to your phone

- **Android (Chrome):** open the link, tap **⋮ → Add to Home screen** or **Install app**.
- **iPhone (Safari):** open the link, tap **Share → Add to Home Screen**.

It now opens full-screen from its own icon, like any other app, and works without internet. Only the weather needs a connection.

---

## 2. Set up in 5 minutes

Open **Settings** and fill in four things. The more you add, the more accurate everything gets.

**1. Your races.** Tap **Add a race** and enter:
- the distance (5K, 10K, half marathon or marathon),
- the date,
- a name and goal time (both optional).

Tick **Main race** for the half or full marathon you're training for. Your plan builds toward it. Every other race becomes a tune-up.

**2. You and your conditions.** Enter:

| Setting | What it's for |
|---|---|
| **Age** | Estimates your max heart rate, so you get heart-rate targets. |
| **Max heart rate** | Optional. More accurate than the age estimate. Use the highest you've seen in a hard race. |
| **Resting heart rate** | Optional. Sharpens your heart-rate zones. |
| **Location** | For the weather forecast,
