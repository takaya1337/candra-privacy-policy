# Candra privacy policy

Last updated: 13 October 2026

Candra is a calendar and journal app. It is built so that what you write
stays with you. This page says exactly what the app does with your data.

This is the policy for Candra on Android. The policy for Candra on
iPhone is [here](ios.md).

## The short version

- Candra has no accounts, no ads, no analytics and no trackers.
- The people who make Candra never receive anything you write. There is
  no Candra server.
- Everything is kept on your device, in the app's own storage.
- Data leaves your device only when you make it leave: by exporting a
  copy, or by turning on sync with a GitHub repository that you own.

## What is kept on your device

- **Journal entries:** their text, title, category, date and time, and,
  for an entry timed as a practice, how long it went on.
- **Categories and reminders** that you make.
- **Geotags, only if you add one.** When you press the geotag button on
  an entry, Candra asks your phone where it is, once. The position is
  rounded to about 100 metres before it is saved; the exact position is
  never stored. You can also give the place a name. Candra never looks up
  your location at any other time, and never in the background.
- **A place for rise and set times, only if you ask for it.** In the
  day's details you can have Candra work out sunrise, sunset and the
  moon's times for where you are. It asks your phone once and keeps the
  position rounded to about 10 kilometres.
- **Settings:** your language, which calendar and view you locked, and
  a practice that is under way.
- **A GitHub access token,** only if you set up sync. It is stored
  encrypted on the device and is sent to GitHub and nowhere else.

**The bazi chart keeps nothing.** A date, time, place and sex put into
it, whether your own birth's or anyone else's, are used to draw the
chart and are gone when you leave the screen. They are never written to
the device and never sent anywhere.

Android's cloud backup is switched off for Candra, so your journal is not
copied to your Google account.

## When data leaves your device

Only in these three cases, each of which you start yourself:

1. **Export.** "Share a copy" and "Save a copy" make a zip file of your
   journal as plain Markdown text. It goes wherever you send or save it.
   The file is not encrypted.
2. **Sync with GitHub (optional, off by default).** If you connect a
   GitHub repository, Candra sends your journal, categories and reminders
   to that repository over an encrypted connection (HTTPS), and reads
   them back. They are stored there as plain text, not encrypted.
   Whoever can read that repository, and GitHub itself, can read them.
   GitHub's handling of your data is covered by
   [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
3. **Opening a place in a maps app.** Tapping a geotag hands its rounded
   coordinates and its name to the maps app you choose.

Candra uses the network for nothing else.

## Permissions

| Permission | Why |
|---|---|
| Notifications | To show your reminders, the end of a practice timed down, and the clock of a practice under way. |
| Alarms at an exact time | So a reminder sounds at the minute you set. |
| Start after the phone restarts | To put your reminders back in place. |
| Location (precise or approximate) | Only when you press for it: the geotag button, the place for rise and set times, or the place of a bazi chart. |
| Internet | Only for GitHub sync, if you turn it on. |

Every one of these is optional except Internet, which does nothing until
sync is set up. Candra works fully without location and without
notifications.

## Deleting your data

- Delete any entry, category or reminder in the app.
- Uninstalling Candra removes everything it kept on the device.
- A copy you exported, or a GitHub repository you synced to, is yours:
  delete the file or the repository to remove it.

There is nothing for us to delete, because we hold nothing.

## Children

Candra is not directed at children and collects no data from anyone.

## Changes

If this policy changes, the new version will be published at this address
with a new date.

## Contact

takaya@suryamajapahit.com
