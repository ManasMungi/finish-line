# Finish Line: User Guide

Finish Line is a free running app that turns your runs into **10K, half marathon and marathon predictions** and a **two-week training plan** for your next marathon or half marathon. It tells you how your training is going, what to run tomorrow, how fast to run it, and when your shoes need replacing.

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

Tick **Main race** for the race you're training for. It can be any distance, from 5K to marathon. Your whole plan is built around it: the phases, the taper, the peak weekly distance and the race-pace sessions. Every other race becomes a tune-up.

**2. You and your conditions.** Enter:

| Setting | What it's for |
|---|---|
| **Age** | Estimates your max heart rate, so you get heart-rate targets. |
| **Max heart rate** | Optional. More accurate than the age estimate. Use the highest you've seen in a hard race. |
| **Resting heart rate** | Optional. Sharpens your heart-rate zones. |
| **Location** | For the weather forecast, e.g. `Vadodara, Gujarat`. |
| **Runs per week** | 3–7, or let the plan decide. |
| **Usual run time** | Early morning or evening, for the heat adjustment. |
| **Units** | Kilometres or miles. |

Tap **Save**.

**3. Your shoes.** Name each pair, choose what it's for (speed sessions, easy & recovery, long runs, or race day), and tap **Save shoes**.

**4. Your runs.** Log the last few weeks by hand, or import them from Strava (section 4).

> **Tip:** to try the app before entering your own data, tap **Replace with sample runs** in Settings → Data. You can delete them afterwards.

---

### New to running?

If you haven't logged any runs yet, tap **New to running** on the Log activity tab, or on the Overview. The Plan tab then shows a one-week fitness test instead of a training plan:

| Day | Session | Effort |
|---|---|---|
| 1 | Baseline run, 20–30 min | Easy, chatty |
| 2 | Rest or a walk | |
| 3 | Easy run + 4 short strides, 20 min | Easy, with quick bursts |
| 4 | Rest or a walk | |
| 5 | **3 km time trial** | Comfortably hard |
| 6 | Rest or a walk | |
| 7 | Longer easy run, 30–40 min | Easy |

Walk breaks are fine on every run. Tap **Log this** next to a day to log it with the date, type and distance filled in. Add your time and save.

As soon as you log the 3 km time trial, you get your first predicted finish times for 5K, 10K, half marathon and marathon. Then tap **Start my training plan** to begin. If you haven't saved a main race, you get a half marathon plan sized to your fitness. You can also tap **Add my first race** to choose your own.

## 3. Log your runs

### Quick log (fastest)

On the **Overview**, the **Up next** card shows today's planned run with a **Log this run** form underneath. The distance is filled in for you. Add your time and average heart rate, then tap **Log run**. The card then moves on to tomorrow's run.

### Full log

Open **Log activity** for more options:

- **Run or swim:** use the switch at the top.
- **Type:** easy, long run, tempo, intervals, or race or time trial.
- **Distance and time:** time is optional, but runs without a time don't count toward your predictions.
- **Average heart rate:** optional.
- **Shoes:** chosen automatically from the run type. Change it only if you wore a different pair.
- **Notes:** optional.

> **For accurate predictions:**
> - For tempo runs, log only the tempo part, not the warm-up and cool-down.
> - Log races and time trials as **Race or time trial**. They count most.
> - Interval sessions count toward your weekly distance but not your predictions, because the rest breaks distort the pace.

Swims appear in your week as cross-training. They don't change your running predictions or plan.

---

## 4. Import from Strava

### Get your file from Strava

1. On **strava.com** in a web browser (not the Strava app), go to **Settings → My Account → Download or Delete Your Account → Request your archive**.
2. Strava emails you a link to a zip file, usually within a few hours. Download it.

### Import it

1. Open **Log activity** and tap **Import CSV** at the top. Your file picker opens.
2. Choose either the **zip file** Strava sent you or **activities.csv** from inside it.
3. Choose how far back to import: last 4 weeks, last 12 weeks, last year, or everything.
4. Check the preview and tap **Import**.

What the import does:

- **Runs and swims only.** Rides, walks and workouts are skipped.
- **It guesses each run's type** from its name ("tempo", "intervals", "race"), heart rate and distance. Runs of 18 km or more count as long runs.
- **It doesn't duplicate.** Importing again later only adds what's new.
- **It fills gaps.** Runs you logged by hand without a time get their time and heart rate from Strava.

> If your phone can't open the zip, unzip it in your Files app first and choose activities.csv.

---

## 5. The Overview screen

### Finish prediction

The big clock shows your predicted **10K**, **half marathon** and **marathon** times, with the race you're training for marked **Your race**.

| Scenario | Meaning |
|---|---|
| **Ambitious** | A great day: you race at the top of what your recent runs show. |
| **Absolute** | The most likely time. |
| **Worst case** | A tough day: heat, pacing trouble, or fatigue. |

- **Confidence** (low, medium or high) depends on your data. A recent race gives high confidence, and easy runs alone give low.
- **Predictions update every Monday** from your runs up to the Sunday before. Tap **Update now** to include this week's runs straight away.

### Training status

A score out of 100 and a label (**Excellent**, **Good**, **Average** or **Poor**) for your last 7 days, plus one line of advice.

- **The ring** shows your score.
- **The 7 day boxes** are coloured by what happened:

| Colour | Meaning |
|---|---|
| Solid | Done |
| Yellow edge | Shorter than planned |
| Dashed | Extra run |
| Red | Missed |
| Plain | Rest |

  Tap a day to see what was planned and what you actually ran.

- **Tap each row** to see the detail and a tip:

| Row | What it measures | Points |
|---|---|---|
| **Plan completed** | Distance you ran against what was planned, and whether you did your key sessions | 40 |
| **Training load** | This week compared with your usual week. Best between 0.8× and 1.3×. | 30 |
| **Fitness trend** | How your fitness (VDOT) has changed over 4 weeks | 30 |

### Up next

Today's run until it's logged, then tomorrow's. It shows:
- **the session,**
- **target pace,** slowed for heat on hot days,
- **heart-rate range,**
- **temperature,**
- **which shoes to wear.**

### Your shoes

- **Distance:** each pair's distance against its replacement point, with an estimated replacement month.
- **Warnings:** **Replace soon** appears at 80% of the pair's life, and **Replace** once it's past.
- **Counting is automatic:** runs count on the pair set for their type. Intervals and tempo go on speed shoes, easy runs on easy shoes, long runs on long-run shoes, and races on race shoes.

### Charts

- **Weekly distance:** your last 8 weeks, plus planned weeks shown dashed.
- **Prediction over time:** how your race prediction has moved, week by week.

### Training paces

Your current pace zones (easy, marathon, half marathon, threshold, interval, repetition), and what's speeding up or slowing down your race time.

### Projected finish times

Every upcoming race, with:
- **If raced today:** your current prediction.
- **On race day:** if you follow the plan until then.
- **Range:** from ambitious to worst case.
- **vs goal:** how far you are from your goal time.
- **Chance of goal:** the percentage chance of hitting your goal, with a label from *Very likely* to *Unlikely*.

---

## 6. Your training plan

Open **Plan** to see every session for the current two weeks: distance, what to do, pace, heart rate, temperature and shoes.

### Next 6 weeks chart

At the top of the Plan tab, a bar chart shows your planned weekly distance for this week and the five after it, with the long run marked as a yellow dot and each week's training phase underneath. Race weeks are flagged.

- **Solid bars** are your fixed two-week plan. This week's bar fills in as you run.
- **Striped, dashed bars** are projected. They adjust to how you actually train when each new block is planned.

### How it works

- **Built around your main race.** The distance sets the workouts (marathon-pace runs for a marathon, race-pace reps for a 5K or 10K) and the taper: 3 weeks for a marathon, 2 for a half, 1 for a 10K or 5K.
- **Your goal time sets the targets.** It decides how high your weekly distance builds and how long your long runs get. Race-pace sessions use your goal pace when it's within reach. If your goal is more than 3% faster than your current fitness, they use a stepping-stone pace that moves toward your goal as you get fitter. The top of the Plan tab tells you which.
- **No main race saved?** The plan builds toward a half marathon, set 16 weeks out if you're starting from a low base (under 20 km a week), 12 weeks if you run 20–40 km a week, or 10 weeks if you already run more than that with long runs of 16 km or more. Paces come from your current fitness. Save a main race at any time to switch to your own event.
- **Two weeks at a time.** The plan stays fixed for two weeks so you can follow it.
- **The next two weeks appear on the Thursday of week 2,** built from how you actually trained.
- **Phases count back from race day.** Base comes first, then build, then peak, then a taper of 3 weeks for a marathon or 2 weeks for a half.
- **Weekly distance grows about 7% a week,** with a lighter recovery week every fourth week.
- **Tune-up races** replace that day's session, with a shakeout run before and an easy run after.

### Rebuilding the plan

Ill, injured, or plans changed? Tap **Rebuild from latest runs** on the Plan page. The plan also rebuilds automatically when you change your main race or its date.

### Pace and heat

- **Paces come from your current fitness.** Until you've logged enough runs, they come from your main race's goal time.
- **On days with a forecast,** paces are slowed about 0.4% for every °C above 15°C, so your heart rate stays in range.
- **The forecast** comes from Open-Meteo and refreshes on its own every few hours.

---

## 7. Settings

| Section | What you can do |
|---|---|
| **Your races** | Add, edit or delete races, and choose your main race. |
| **Your shoes** | Rename pairs, change what they're used for, add distance run before you started logging, set when to replace them, add or retire pairs. |
| **You and your conditions** | Age, heart rate, location, runs per week, run time, units. |
| **Data** | Export or import a backup, load sample runs, delete everything. |

Remember to tap the **Save** button in each section after making changes.

---

## 8. Back up your data

Your runs live **only on this device**. Clearing your browser's data, or uninstalling the browser, deletes them.

- **To back up:** Settings → Data → **Export backup**. A file named `finish-line-backup-<date>.json` is saved to your Downloads.
- **To restore or move to a new phone:** Settings → Data → **Import backup**, then choose that file.

> Export a backup every week or two, and keep a copy in Google Drive or email it to yourself.

---

## 9. Questions and fixes

**My predictions didn't change after I logged a run.**
Predictions update on Mondays. Tap **Update now** on the prediction clock to refresh straight away. Also check that the run has a time, because runs without one don't count.

**It says "Low confidence".**
You've only logged easy runs. Log a tempo run or a race, or race a 5K or 10K, and confidence goes up.

**My plan seems too easy or too hard.**
The plan follows your recent weekly distance, so log all your runs, including ones from before you started. You can also change **Runs per week** in Settings, or tap **Rebuild from latest runs**.

**There are no heart-rate targets.**
Add your age or max heart rate in Settings and tap Save.

**The weather isn't loading.**
Check your internet connection and your location in Settings. Use the format *City, State*, e.g. `Pune, Maharashtra`. Without a forecast, paces just aren't heat-adjusted.

**The Strava import says the file isn't recognised.**
Make sure it's **activities.csv** from Strava's archive. Files from other apps, such as Garmin, aren't supported yet.

**Shoe distance looks wrong.**
In Settings → Your shoes, check what each pair is used for. If a pair had distance on it before you started logging, enter it in **km not in your log**.

**I lost my data.**
Import your latest backup from Settings → Data → Import backup.

**How do I update the app?**
If you get a new version of `index.html`, upload it to the same GitHub repository and replace the old file. The app picks it up the next time you open it.

---

## About the numbers

- **Predictions** use Jack Daniels' VDOT running formulas. They're slowed down if your weekly distance or longest run is still short for the race distance.
- **Heart-rate targets** use standard zones based on your max heart rate. If you've entered your resting heart rate, they use heart-rate reserve instead.

These are well-established coaching methods, but they're estimates, not lab tests. Use them as a guide, and listen to your body.

> **Finish Line is a training aid, not medical advice.** If something hurts, rest. If pain continues, see a doctor or physiotherapist.
