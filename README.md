# Verse Alarm — Android beta

Offline Bible alarm prototype. Type the displayed verse exactly to complete an alarm.

## Download

**[Download for Android — v0.1.0 beta](https://github.com/P1NKMAN666/verse-alarm/raw/refs/heads/main/downloads/VerseAlarm-0.1.0-debug.apk)**

[Tagalog installation guide](INSTALL-TAGALOG.md)

APK size: 203,164 bytes (about 200 KB). Android 8.0 or newer.

## Features

- 1,095 matched English/Tagalog verse pairs; 365 per Easy, Moderate and Hard difficulty.
- Offline operation, no account or login.
- Multiple alarms with repeat weekdays.
- Global language, difficulty and device built-in sound settings.
- Exact verse typing, including case, spaces and punctuation; corrections allowed.
- One five-minute snooze per alarm occurrence.
- First successful alarm publishes the daily verse. All alarms share the day's challenge.
- Daily-verse lock-screen notification and home-screen widget.

## Testing status

Debug-signed prototype, not a Play Store release. Android SDK 36 emulator tests passed for scheduled delivery, foreground notification, snooze and typing dismissal. Five scheduling unit tests passed; Android lint reports zero errors.

**Still needs physical Redmi Pad SE testing**, especially HyperOS battery restrictions, audible locked-screen alarms and widget behavior. Notifications can be hidden/dismissed by system settings. Apps cannot prevent force-stop, shutdown or system volume changes.

## Content and privacy

English KJV and Tagalog Ang Biblia 1905 digital texts sourced from [Scrollmapper](https://github.com/scrollmapper/bible_databases). The length-balanced collection still needs editorial and territory-specific translation redistribution review before store publication. [Content notices](CONTENT-NOTICE.txt).

No login, INTERNET permission, analytics or app cloud backup. App data stays on-device.

This repository currently hosts the APK and installation information.

## Verify download

SHA-256: `AD1F2E5F87E74B25A7391D40EE6E1C75600652BF3BA9827D0C48C4097F855EFC`
