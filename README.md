# Flow

A private, offline-first reminder companion for Android.

Flow remembers what you decided matters, tells you what happens next, and never scolds you for what you missed.

**Current stable release: [1.1.1](https://github.com/Deepak4750/Flow-Releases/releases/latest)**

[Download Flow-1.1.1.apk](https://github.com/Deepak4750/Flow-Releases/releases/download/v1.1.1/Flow-1.1.1.apk) · [Source](https://github.com/Deepak4750/Flow-Android)

Requires Android 11 or later. Install over a previous Flow build to keep your reminders.

---

## Features

### Home
- Greeting that changes through the day, with an optional nickname
- A calm list of reminders: what, when, and status
- Next up called out so the soonest reminder is obvious
- Complete today with the same outlined check used in the rest of the app
- Daily progress as a quiet count, not a guilt dashboard
- Filter by built-in or custom categories
- Enable, disable, edit, or delete without leaving the list

### Create and edit
- Progressive disclosure: what, when, how often, then optional extras
- Title, category, time, and an optional notification note
- Built-in categories: Health, Fitness, Study, Work, Personal
- Custom category names you create — they come back as chips until the last reminder with that name is deleted
- Optional Why, kept private and never shown in the notification
- Optional start date, end date, and active hours (“only remind me while I’m awake”)

### Scheduling
- Every day, every week, every month, every few days, or every few hours
- Weekly reminders on the weekdays you pick
- Active hours that can cross midnight

### Notifications
- Quiet, high-importance reminders with Complete, Dismiss, and optional Snooze
- Swiping the shade item brings it back until you Complete, Dismiss, or Snooze
- Completing from the notification, Home, or the Today widget clears it and it stays cleared
- The notification body is only the note you wrote
- Exact alarms reschedule after boot and timezone changes

### Home screen widgets
- **Today** — today’s reminders, scroll and complete from the home screen. The next reminder’s time is in Flow’s accent
- **Progress** — today’s follow-through as a 7×7 dot matrix. Swipe for the percentage, tap to open Flow

### Settings
- Name and optional nickname
- Notification permission and snooze length
- Delete all reminders behind a confirmation
- Check for update. When a newer build is ready, Flow offers Install or Later
- About, with a plain privacy statement
- Preview channel: tap the version seven times on About to see builds before everyone else

### Privacy
- Offline-first. Reminders never leave the phone
- No account, no sync, no tracking
- Network is used only for the in-app updater

---

## How updates work

This repository holds public APKs so Flow can update itself without a private-repo token.

- `latest.json` — what every install checks
- `preview.json` — what a phone checks after preview is unlocked
- GitHub Releases — the APK files those manifests point at

Source stays in [Flow-Android](https://github.com/Deepak4750/Flow-Android).
