# Flow

A private, offline-first companion for your tasks, your water and your training, on Android.

Flow remembers what you decided matters, tells you what happens next, and never scolds you for what you missed.

**Current stable release: [1.3.3](https://github.com/Deepak4750/Flow-Releases/releases/latest)**

[Download Flow-1.3.3.apk](https://github.com/Deepak4750/Flow-Releases/releases/download/v1.3.3/Flow-1.3.3.apk) · [Source](https://github.com/Deepak4750/Flow-Android)

Requires Android 11 or later. Install over a previous Flow build to keep your data.

---

## Features

### Home
- A greeting that changes through the day, with an optional nickname
- A 30-day consistency graph you can drag across to read any day, with gold stars for full days
- Next up: the soonest task, today's water with one-tap adds, and today's workout
- Tap your name or photo in the menu to open your profile

### Tasks
- Every day, week, month, every few days or every few hours, with active hours that can cross midnight
- Built-in categories (Health, Fitness, Study, Work, Personal) plus your own, each with an accent colour
- Optional note on the notification, a private Why, start and end dates, or a set number of times
- **Notification or Alarm** per task
  - Notifications come with Complete, Snooze and Dismiss, and come back after a swipe until you answer
  - Alarms ring until you answer, with a choice of tones (Phone alarm, Rise, Digital, Ringer)
  - Locked phone: a full-screen alarm with slide to complete, Snooze and Dismiss
  - Left alone for 90 seconds, an alarm snoozes itself for your snooze length

### H₂O
- A daily goal shown as a bottle that fills, in five bottle styles
- Quick adds (250 ml, 500 ml, 1 L) and your own saved amounts
- Gentle reminders through the day, with add buttons right on the notification

### Fitness
- **Routines:** build your days, follow them round by round, share them as a file, and import shared ones
- **Free workouts:** start from your most used exercises or browse by muscle
- **Exercise library:** built-in exercises by muscle group, plus your own
- **Live workout**
  - Warm-ups, drop sets and supersets
  - A set timer for timed sets (bar or hold-to-start)
  - Last time's numbers next to each set
  - A rest timer with chimes, skip and ±10 s
  - Workout notes
  - A gold star that flies to every new personal record
- **Day flow:** one routine day a day (it unlocks at 2 AM), skip a day with undo, and rest-day stretches
- **Workout music**
  - Pick your music app and headphones; your music starts as the workout starts
  - A frosted glass player tinted by the album cover: play/pause, previous and next
  - Tap the player to open it, then drag the seek dot to move through the song
- **Reminders:** a daily nudge at your training time, or a nudge to rest on rest days
- **History:** every workout by day, with graphs and a day panel
- **Import:** bring in your past workouts from Hevy or Strong

### Progress and sharing
- Progress over weeks and months across tasks, water and training
- Stickers and share cards to post a finished day or workout
- Celebrations when you clear a day, hit your water goal or finish a workout

### Home screen widgets
- **Today:** today's tasks; scroll and complete them from the home screen
- **Progress:** today's follow-through as a dot matrix
- **H₂O:** your bottle filling as you drink, with add buttons

### Settings
- Profile with name, nickname and photo
- Dark theme, four fonts, and text size S / M / L
- Notifications and snooze length, plus your alarm tone
- Fitness defaults: weight unit, rest times, weight step, rest chime, timer style and workout music
- A Permissions page listing everything Flow asks Android for, with Allow beside anything missing
- Data: export tasks, water and workouts; keep your data if Flow is uninstalled
- Check for update: when a newer build is ready, Flow offers Install or Later

### Privacy
- Offline-first. Your tasks, water and workouts never leave the phone
- No account, no sync, no tracking
- The network is used only for the in-app updater (and by your own music app)

---

## How updates work

This repository holds public APKs so Flow can update itself without a private-repo token.

- `latest.json` — what every install checks
- `preview.json` — what a phone checks after preview is unlocked
- GitHub Releases — the APK files those manifests point at

Source stays in [Flow-Android](https://github.com/Deepak4750/Flow-Android).
