# Why I’m Building My Own Running App

Running is my main hobby outside of work. Over time I moved from “just go out and run” to proper structure: intervals, tempo, long runs, race blocks. I already owned an Apple Watch and did not want to switch to Garmin just to get better workout tools.

## Why not just use Garmin?

Garmin offers amazing tools for training plans and structured workouts, but they come with trade‑offs:

- You have to buy into the whole Garmin ecosystem.
- Most of the value is in deep analytics that matter more to pros than to someone with a job, kids, and limited training time.
- Switching hardware felt like solving the wrong problem: I already had a perfectly good watch on my wrist.

So the decision was: stick with Apple Watch and try to make it work for serious, but not professional‑level, training.

## The gap with existing Apple Watch tools

Once I committed to Apple Watch, the friction started to show.

Most apps that can create structured workouts and sync to Apple Watch had at least one of these issues:

- **Web‑only builders**: Great workout builders, but only in the browser on a laptop. TrainingPeaks is a good example here – powerful, but the builder lives on the web, not in your pocket.
- **Subscription walls**: You pay a monthly fee mainly for dashboards and analytics that go way beyond what a non‑pro actually uses.
- **Overkill data**: Tons of charts and metrics, but all I really wanted was: “What exactly am I running today?”, “Did I do it?”, and “Can I easily create and see my full week/month ahead?”.

I almost stopped developing my app when Apple released iOS 26 with a native workout builder. But it was missing the **calendar view** – no way to plan a full week or month ahead, drag sessions around, or see your entire schedule at a glance. [DC Rainmaker covered it well here](https://www.dcrainmaker.com/2025/09/apple-watch-workout-builder-ios26-watchos26.html).[attached_file:1] That gap actually reignited the project.

I don’t need the full pro‑coach stack. I want to hit certain goals (like a marathon time), but I’m not trying to live like a professional athlete.

## What I actually wanted

The wish list turned out to be pretty simple:

- Create structured workouts **directly on my phone**: warm‑up, intervals, recoveries, cool‑down.
- Save them as templates I can reuse and tweak quickly.
- Sync them as native workouts to my Apple Watch and just press start.
- Avoid a web browser and avoid heavy subscription lock‑in.
- Enough data to guide training, not a full‑time analytics job.

No platform really hit that sweet spot for Apple Watch users who are serious but not professional.

## The app I’m building

That’s why I started building my own app:

> A lightweight structured‑training builder on iPhone, with reliable sync to Apple Watch, designed for self‑coached runners.

The focus is on:

- **Low friction**: Edit a session in seconds before going out the door.
- **On‑device first**: No mandatory web app, no complex dashboards.
- **Just enough data**: Pace, distance, heart rate, progress toward goals.

## Try WeekPace

The app described on this page became **WeekPace** – a lightweight iOS and Apple Watch app for planning your training week and syncing structured workouts straight to your wrist.

- 🌐 Website: [weekpace.com](https://weekpace.com)
- 📱 App Store: [WeekPace on the App Store](https://apps.apple.com/us/app/weekpace/id6756592413)
