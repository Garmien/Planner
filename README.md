# Planner

A small offline web app: weekly schedule, daily check-in with streaks, and backup/restore.
The app ships empty. Your schedule is loaded from a file on your device and, like your records,
is stored only there (localStorage). Nothing is sent anywhere.

When you change a file, bump `VERSION` in `sw.js` so phones pick up the update.
