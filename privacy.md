---
layout: default
title: Privacy Policy
description: What Telltale reads, where it is analyzed, and what never leaves your devices.
permalink: /privacy/
---

# Privacy Policy

<p class="updated">Last updated 6 October 2026</p>

**The short version: your health and calendar data stay on your devices.
There is no server.**

## What Telltale reads

- **Health data** (with your permission, through Apple HealthKit): heart
  rate, heart-rate variability, resting heart rate, sleep and step count on
  your iPhone; heart rate only on your Apple Watch. Steps serve one purpose:
  leaving out the minutes you spent walking.
- **Calendar data** (with your permission, through Apple EventKit): event
  titles, times, locations, attendee names and your own reply to each
  invite, for calendars synced to your devices.

## Where it is analyzed

On your devices. Your iPhone computes meeting scores, attribution,
forecasts, insights, the Pulse Score and the briefing, and mirrors the
results to your own paired Apple Watch over Apple's encrypted
device-to-device Watch Connectivity link. When the iPhone is out of reach,
the watch runs the same analysis on its own, from heart rate alone.

## iCloud

Telltale syncs its own settings (your name, the lookback period and
data-nerd mode) and your hidden and excluded lists through your own iCloud
account, using Apple's iCloud key-value storage, so they follow you to a
new iPhone. Those lists hold the names of people you hid, the titles and
times of meetings and series you hid or excluded, and the names of places
you excluded. Health data, results and
the rest of your calendar never go to iCloud, and the developer cannot see
what is there. Sync is on by default; turn it off under iCloud in
Telltale's Settings, which also removes Telltale's copy from iCloud while
each device keeps its own settings. Another iPhone that still syncs puts
its copy back, so turn it off on each one. Notification choices and which
calendars count stay on each device; when the iPhone is out of reach, the
watch reads every calendar on it.

## Apple Intelligence

When Apple Intelligence is turned on, Telltale uses Apple's on-device
language model to phrase your briefing and to answer questions in Ask
Telltale. It never uses Private Cloud Compute, so your questions and your
data stay on your iPhone. The model reads what Telltale has already
computed, colleagues' names and meeting titles included, and it cannot
reach the internet through Telltale. The latest phrased briefing is kept in
the app's own storage on your iPhone, so it reads the same each time you
open the app until there is news.

## Notifications and Siri

Storm warnings and the morning briefing are scheduled on the device from
your own forecast. Siri answers come from the same on-device analysis, and
only while your iPhone is unlocked.

## What Telltale does not do

- No servers, no accounts, no sign-in.
- No analytics, no tracking, no advertising, no third-party SDKs.
- No network requests of its own: beyond Watch Connectivity and iCloud
  key-value sync, both run by iOS, the app contains no networking code.

## Data you export is yours

Share cards (your stress card, a meeting or a colleague) and the CSV export
are created only when you tap them, and go wherever you send them through
the iOS share sheet. None names the people you hid, the CSV leaves out the
meetings you hid, and cards show initials instead of names unless you turn
that off; a meeting card can leave out its title and place too.

## Deleting your data

Telltale stores its settings, your hidden and excluded lists, the latest
phrased briefing and the latest results it mirrored to your watch, in the
app's own storage on your devices, and the settings and lists in your iCloud while sync is on.
Turning sync off on every iPhone removes the iCloud copy; deleting the app,
whose watch app goes with it, removes the rest. Your Health and Calendar
data stay in those apps and are never copied elsewhere.

## Changes

If a future version ever adds a network feature, this policy and the in-app
privacy page will say so plainly before it ships.

## Contact

Questions about this policy or your data:
https://liniker-seixas.github.io/telltale/support/
