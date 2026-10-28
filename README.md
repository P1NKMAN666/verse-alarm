# Rise & Verse — Android beta

**[Download for Android — v0.2.0](https://github.com/P1NKMAN666/verse-alarm/raw/refs/heads/main/downloads/RiseAndVerse-0.2.0-debug.apk)**

[Tagalog installation and update guide](INSTALL-TAGALOG.md)

APK: 188,507 bytes. Android 8.0 or newer. Install over the old Verse Alarm app to retain alarms/settings; the application ID and signing key are unchanged.

## New in 0.2.0

- App name: **Rise & Verse**.
- Copy the entire displayed Bible verse, followed by **one space and its Bible reference**. Capital letters, punctuation and spaces must match exactly.
- Alarm time uses **scroll wheels or direct numeric typing**, in 24-hour format.
- Removing the app's Recent Apps task keeps ringing active. A system-held backup can restore an unfinished alarm if its process is killed.
- Snooze and correct dismissal cancel recovery. An old recovery cannot restart a completed or snoozed occurrence.
- HyperOS setup instructions now cover battery restrictions, Background autostart and lock-screen notifications.

## Features

- 1,095 offline English/Tagalog verse pairs: 365 per Easy, Moderate and Hard.
- No login or account. Multiple alarms and repeat weekdays.
- Global language, difficulty and device built-in sound settings.
- One five-minute snooze per alarm occurrence.
- First successful dismissal publishes the daily verse; all alarms share the day's challenge.
- Lock-screen verse notification and home-screen widget. No kiosk/device-owner setup.

## Testing status

Debug-signed testing build, not a Play Store release.

Passed: five scheduling unit tests, content checks, Android lint (zero errors), emulator UI tests for scroll/type time entry and exact verse-plus-reference dismissal, task removal during ringing, snooze and recovery cancellation.

A separate emulator test stopped the ringing service and killed the process with the screen asleep. The backup restored the same alarm/verse in **27.8 seconds**, with a new foreground service and alarm MediaPlayer in started state.

**Physical Redmi Pad SE / HyperOS testing is still needed.** A process kill can cause a sound gap during recovery. Force stop, shutdown, denied permissions or vendor restrictions can prevent recovery; the app cannot guarantee uninterrupted sound. Notification visibility is controlled by the device/user. See the installation guide for recommended HyperOS settings.

## Content and privacy

English KJV and Tagalog Ang Biblia 1905 digital texts are sourced from [Scrollmapper](https://github.com/scrollmapper/bible_databases). The collection still needs editorial and territory-specific redistribution review before store publication. [Content notices](CONTENT-NOTICE.txt).

No login, INTERNET permission, analytics or app cloud backup. Data stays on-device.

This repository hosts the APK and installation information.

## Verify download

SHA-256: `f4435526c66d9966438c20282c8b627e1c71fc9e3e9d0e0b25477f140930a2c6`

[Previous 0.1.0 prototype](downloads/VerseAlarm-0.1.0-debug.apk)
