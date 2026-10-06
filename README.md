# Couch to 5K on your wrist: NHS running plan for the Garmin Venu Sq

Run the NHS Couch to 5K plan from a Garmin Venu Sq, with no phone in your hand or pocket. The watch times every run and walk interval and buzzes you through each change, just like the app.

> **Unofficial project.** Couch to 5K is an NHS programme. This project is not made by, affiliated with, or endorsed by the NHS. All credit for the programme, its design and its timings goes to the NHS. See [Credits](#credits-and-intellectual-property).

---

## Why this exists

### Couch to 5K works

[Couch to 5K](https://www.nhs.uk/better-health/get-active/get-running-with-couch-to-5k/) is a free NHS running plan for complete beginners. Over 9 weeks, with 3 runs a week, it takes you from no running at all to running 5K or 30 minutes without stopping.

It works because it starts very gently and builds slowly. Week 1 is just 1 minute of running at a time, with walking in between. Each week adds a little more, so your body and your confidence grow together. You never have to work out what to do next: the plan tells you when to run, when to walk, and when you've finished.

### The problem: you need your phone

The plan is delivered through the NHS Couch to 5K app on iPhone and Android. The app is excellent, but it means running with your phone:

- Holding a phone while running is awkward and changes how you move your arms.
- Pockets bounce, and many running clothes don't have a secure one.
- Phones get dropped. A cracked screen on week 2 is a good way to stop running.
- Armbands and running belts are one more thing to buy and wear.

For a lot of people, the phone is the most uncomfortable part of the run.

### The solution: put the plan on the watch

Garmin watches can run structured workouts. A workout is a list of timed steps, and the watch moves through them automatically, vibrating and beeping at every change. You press start once and the watch does the rest.

This project provides the full NHS Couch to 5K plan as ready-made Garmin workout files. Copy them to your watch once, and every session is there when you need it.

### Why the Venu Sq

The Garmin Venu Sq has built-in GPS, so it records your route, distance and pace on its own, with no phone needed. Combined with vibration alerts you can feel mid-run, it covers everything you need from the app on your wrist.

---

## What you get

13 workout files covering all 27 runs of the plan. Most weeks repeat the same run three times, so they share one file. Weeks 5 and 6 have three different runs each, so they have one file per run.

Every workout starts with a **5-minute brisk walk warm-up** and ends with a **5-minute walk cool-down**, as in the NHS plan.

| Workout on watch | Session | Use for | Total |
|---|---|---|---|
| C25K W1 | 8 × run 1 min, with 1½ min walks between | All runs in week 1 | 28:30 |
| C25K W2 | 6 × run 1½ min, with 2 min walks between | All runs in week 2 | 29:00 |
| C25K W3 | Run 1½, walk 1½, run 3, walk 3, run 1½, walk 1½, run 3 | All runs in week 3 | 25:00 |
| C25K W4 | Run 3, walk 1½, run 5, walk 2½, run 3, walk 1½, run 5 | All runs in week 4 | 31:30 |
| C25K W5 R1 | Run 5, walk 3, run 5, walk 3, run 5 | Week 5, run 1 | 31:00 |
| C25K W5 R2 | Run 8, walk 5, run 8 | Week 5, run 2 | 31:00 |
| C25K W5 R3 | Run 20 | Week 5, run 3 | 30:00 |
| C25K W6 R1 | Run 5, walk 3, run 8, walk 3, run 5 | Week 6, run 1 | 34:00 |
| C25K W6 R2 | Run 10, walk 3, run 10 | Week 6, run 2 | 33:00 |
| C25K W6 R3 | Run 25 | Week 6, run 3 | 35:00 |
| C25K W7 | Run 25 | All runs in week 7 | 35:00 |
| C25K W8 | Run 28 | All runs in week 8 | 38:00 |
| C25K W9 | Run 30 | All runs in week 9 | 40:00 |

All times are in minutes. Totals include the warm-up and cool-down, and match the totals on the [NHS Couch to 5K running plan page](https://www.nhs.uk/better-health/get-active/get-running-with-couch-to-5k/couch-to-5k-running-plan/).

---

## Install (one time, about 5 minutes)

You need the watch, its charging cable, and a Windows PC or Mac.

1. **Download** the `.fit` files from the [`workouts`](workouts/) folder of this repository. If you download a zip, **extract it first** (right-click → Extract All on Windows).
2. **Make room on the watch.** The Venu Sq appears to hold a maximum of 25 workouts. You need 13 free slots. See [Watch says the maximum number of workouts is reached](#watch-says-the-maximum-number-of-workouts-is-reached).
3. **Plug the watch into your computer** with the Garmin cable.
4. **Open the watch's storage:**
   - **Windows:** File Explorer → **This PC** → **Venu Sq** → Internal Storage → **GARMIN** → **NewFiles**
   - **Mac:** install the free app [OpenMTP](https://openmtp.ganeshrvel.com/), then go to **GARMIN** → **NewFiles**
5. **Drag all 13 `.fit` files into NewFiles.** Dragging is more reliable than copy and paste.
6. **Unplug the watch and restart it.** The files will disappear from NewFiles. That is normal: the watch has moved them into its workout list.

## Using it on run day

1. On the watch, open **Run**.
2. Open the activity menu (hold the bottom button), then go to **Training → Workouts**. Menu wording may vary slightly between software versions.
3. Pick the session for today, for example **C25K W3**.
4. Press start, then put your arms down and run. The watch vibrates and beeps at the end of every step and moves to the next one by itself.

Your finished runs sync to the Garmin Connect app as normal next time your phone and watch connect.

**First time?** Do a short test. Start **C25K W1** outside so the watch picks up GPS, check that the warm-up countdown starts, then press the lap button a few times to skip through and feel the run/walk alerts. Stop and discard the test.

**Tips**

- Make sure vibration and alert tones are switched on in the watch's sound and vibration settings.
- The NHS plan recommends stretching before and after each run. That part isn't timed, so do it before you press start and after the cool-down.
- Repeating a week is completely fine, and the NHS encourages it. Just pick the same workout again.

---

## Troubleshooting

### Windows shows nothing when I plug the watch in

The Venu Sq connects as a media device, not a USB stick. Windows often shows no popup and no drive letter.

1. Open File Explorer, click **This PC**, and look under Devices and drives for **Venu Sq**.
2. Check the watch screen shows it is charging. If not, the clip isn't seated: clean the contacts and press it on firmly.
3. Use the original Garmin cable, plugged directly into the computer, not a hub, dock or monitor.
4. If Garmin Express is installed, close it fully, including from the system tray.
5. Restart the watch and the computer, then try again.
6. Check your Windows edition under **Settings → System → About**. If it ends in **N**, install Microsoft's free Media Feature Pack.

### Windows says "USB device not recognised"

Windows can see something is plugged in, but the connection is failing. This is usually a physical contact problem or a fussy port.

1. **Clean the contacts** on the back of the watch and on the charging clip with a cotton bud and a little rubbing alcohol. Sweat residue builds up there. Let them dry, then reconnect firmly.
2. **Power the watch off first**, then plug it in. Several Garmin users report this works when nothing else does.
3. **Try a different port.** Garmin watches can be fussy with blue USB 3 ports and USB-C adapters. Try a black USB 2 port if you have one, or a port on the back of a desktop PC.
4. **Clear the failed connection.** Open Device Manager, find **Unknown USB Device** under Universal Serial Bus controllers, right-click it → **Uninstall device**, unplug the watch, wait 10 seconds and plug it back in.
5. **Try a different computer.** If it works there, the problem is your PC's ports.

### Windows sees the watch, but Device Manager shows a warning

Right-click the device (under Portable Devices or Other devices) → **Update driver** → **Browse my computer** → **Let me pick from a list** → choose **MTP USB Device**.

### I can't paste the files into NewFiles

- **Extract the zip first.** Windows lets you browse inside a zip, but often won't copy files from it to a watch. Right-click the zip → **Extract All**, then use the extracted folder.
- **Drag instead of paste.** Put the two windows side by side and drag the files across.

### The files disappeared from NewFiles but aren't in my workouts

An empty NewFiles folder means the watch picked the files up, not that it accepted them.

1. Plug the watch in and open **GARMIN → Workouts**. If the C25K files are there, the watch accepted them. Restart the watch and look again from **Run → Training → Workouts**. Workouts are tied to an activity type, so they won't appear under Walk or other activities.
2. If the C25K files are **not** in the Workouts folder, the watch rejected them. The most common reason is that the workout storage is full. See the next section.

### Watch says the maximum number of workouts is reached

The Venu Sq appears to hold a maximum of 25 workouts. Old workouts from Garmin Connect or Garmin Coach can fill every slot without you realising, and then new files are dropped, sometimes without any message.

1. Plug the watch in and open **GARMIN → Workouts**.
2. Delete the workouts you don't need. You need at least 13 free slots. To see their names first, check **Run → Training → Workouts** on the watch.
3. Copy the C25K files into **NewFiles** again, unplug, and restart the watch.

Workouts on the watch are copies, so deleting them doesn't remove anything from your Garmin Connect account.

### Old workouts keep coming back after a sync

Garmin Connect is pushing them to the watch. This happens if you have an active Garmin Coach or training plan, or workouts scheduled on your Garmin Connect calendar. End the plan or remove the scheduled workouts in the Garmin Connect app, then delete them from the watch again.

### The C25K workouts don't appear in the Garmin Connect app

That's expected. Workouts copied by cable live only on the watch. Your completed runs still sync to Garmin Connect as normal.

### The watch buzzes but doesn't talk to me

The NHS app has a voice coach. The watch uses vibration and beeps instead. Most people get used to this within a week or two.

---

## How the files are made

Garmin workouts are stored as `.fit` files, a standard format published in Garmin's [FIT SDK](https://developer.garmin.com/fit/overview/). Each file contains a list of steps. Every step has a fixed duration in time, so the watch advances automatically with no button presses.

The files in this repository were generated with the Python [`fit-tool`](https://pypi.org/project/fit-tool/) library and checked with Garmin's official FIT decoder. Every session was checked against the step-by-step timings on the NHS running plan page.

## Other Garmin watches

The files use Garmin's standard workout format, so they should work on any Garmin watch that supports structured workouts. Only the **Venu Sq** has been tested. If you try another model, please open an issue to say whether it worked.

**Quick check:** search your watch's [owner's manual](https://support.garmin.com/) for a section called **Workouts** or **Following a Workout**. If it has one, these files should work. If it doesn't, the watch can't run structured workouts.

### Popular models

| Family | Models | Status |
|---|---|---|
| Venu | Venu Sq, Venu Sq 2, Venu 3, Venu 4, Venu X1 | Venu Sq tested. Others untested |
| vívoactive | vívoactive 5, vívoactive 6 | Untested |
| Forerunner | Forerunner 55, 70, 165, 170, 255, 265, 570, 965, 970 | Untested |
| fēnix, epix, Instinct, Enduro | fēnix 8, epix Pro, Instinct 3, Enduro 3 | Untested |

### Installing on any model

Installation is the same on every Garmin watch:

1. Plug the watch into your computer with its Garmin cable.
2. Open **GARMIN → NewFiles** (Windows: File Explorer → This PC → your watch. Mac: [OpenMTP](https://openmtp.ganeshrvel.com/)).
3. Drag the 13 `.fit` files into **NewFiles**.
4. Unplug and restart the watch.

### Finding the workouts on the watch

This is the part that differs between models. Look for **Workouts** inside the **Run** activity's menu. The option only appears when workouts for that activity are loaded, so always start from Run.

**Touchscreen watches with two or three buttons** (Venu, vívoactive):

1. Press the top button and select **Run**.
2. Open the activity menu (hold the bottom button, or swipe on the activity screen).
3. Select **Training → Workouts**, or **Workouts** on some models.
4. Pick the session and select **Do Workout**.

**Five-button watches** (Forerunner, fēnix, epix, Instinct, Enduro):

1. Press **START** and select **Run**.
2. Hold **UP** to open the menu.
3. Select **Training → Workouts** (on some entry-level models, **Options → Workouts → My Workouts**).
4. Pick the session and select **Do Workout**.

Menu names change between models and software versions. If you can't find it, search your watch's manual for "Following a Workout".

### Things that vary between models

- **Workout storage limit.** The Venu Sq appears to hold 25 workouts. Other models may hold more or fewer. If new workouts don't appear, delete old ones first (see [Troubleshooting](#watch-says-the-maximum-number-of-workouts-is-reached)).
- **Alerts.** All Garmin watches with workouts vibrate or beep at step changes. Watches with music and headphone support may also give audio prompts through Bluetooth headphones, depending on your settings.
- **Older watches.** Some older models need you to tap or press a button to move to the next step. These files use timed steps, which should advance automatically, but check with a short test run.

## Health note

Couch to 5K is designed for beginners, but if you have a health condition, or haven't exercised for a long time, the NHS advises checking with a GP before starting. Read the NHS guidance on the [Couch to 5K page](https://www.nhs.uk/better-health/get-active/get-running-with-couch-to-5k/).

---

## Credits and intellectual property

**Couch to 5K is an NHS programme.** The plan, its structure, the session timings and the Couch to 5K name belong to the NHS. All credit for designing the programme goes to them.

- NHS Couch to 5K: [nhs.uk/better-health/get-active/get-running-with-couch-to-5k](https://www.nhs.uk/better-health/get-active/get-running-with-couch-to-5k/)
- NHS Couch to 5K running plan (week by week): [nhs.uk/better-health/get-active/get-running-with-couch-to-5k/couch-to-5k-running-plan](https://www.nhs.uk/better-health/get-active/get-running-with-couch-to-5k/couch-to-5k-running-plan/)

This repository is an **independent, unofficial** adaptation of the NHS timings into Garmin workout files. It is not affiliated with, produced by or endorsed by the NHS or Garmin. Garmin and Venu are trademarks of Garmin Ltd. or its subsidiaries.

If you can, use the official NHS Couch to 5K app as well. It includes audio coaching, motivation and support that a watch can't replace.
