# nightshift-sleep-guardian-prior-art
“Defensive publication – November 18, 2025”
# NightShift Sleep Guardian – Defensive Publication (Prior Art)

**Published:** November 18, 2025  
**Author:** Nikola Tomić– Montenegro  
**Purpose:** This repository intentionally discloses the full invention to create worldwide prior art and prevent anyone from patenting it.

## The Invention (fully disclosed)
A mobile app that finally lets on-call and night-shift workers sleep without waking up every 15–30 minutes unnecessarily.

### Core idea
- User selects one messaging app their boss uses (Telegram, WhatsApp, Discord, Slack, Signal, Teams, etc.)
- User sets recurring “check phone” alarms (e.g. every 15 minutes overnight)
- The app checks: “Did I receive a new direct message in the last 10–15 minutes?”
  - NO message → silently cancel/skip the next alarm → user keeps sleeping
  - YES message → alarm rings normally → user wakes up and goes to work

This exact proactive cancellation based on recent DMs in one specific app does not exist in any published app as of November 2025.

### Technical implementation (Android example)
- Uses Android’s official NotificationListenerService (permission granted by user)

- If no qualifying notification in the time window → cancel the PendingIntent

This disclosure is intentional and permanent prior art under 35 U.S.C. § 102 / EPC Article 54.

License: CC0 1.0 (public domain) – anyone can use the idea freely.
