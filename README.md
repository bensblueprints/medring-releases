# MedRing — release mirror

Public download mirror for **MedRing** Android APKs. The source lives in the private repo
`bensblueprints/medring`; this repo exists so the APK can be downloaded on a phone without
signing in to GitHub.

Grab the newest APK from the [Releases](../../releases/latest) page.

## Install

1. Tap the `.apk` on the phone and open it.
2. Android will ask you to allow "install unknown apps" for the browser — allow it, then install.
3. Open MedRing and finish onboarding. It asks for notifications, exact alarms, full-screen
   notifications, a battery-optimisation exemption and background location. **All five are
   load-bearing** — without them the app will look like it works and then silently not ring
   when the screen is off.
4. Settings → **Test ring in 1 minute**, then lock the phone and wait. If it does not ring
   full-screen with sound, the permission screen says which one is missing.

## What it does

Rings like an incoming call for a dose, and keeps escalating — 5 min, 15, 30, 1 h, 2 h, 3 h,
then hourly — until you mark it TAKEN, SNOOZE or SKIP. Includes a medication chart with a
taken-history and adherence view, plus home-geofence reminders ("heading out? take your meds
with you") and drive-time-home alerts when a dose is still pending.

Every build is signed with the same release key, so newer versions install straight over the
old one without losing your medication history.
