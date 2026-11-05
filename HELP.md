# Thimble Help

- [Install on a Mac](#install-on-a-mac)
- [Install on Android](#install-on-android)
- [The lists](#the-lists)
- [Add tasks quickly](#add-tasks-quickly)
- [Dates you can type](#dates-you-can-type)
- [Projects, cards, and the Dashboard](#projects-cards-and-the-dashboard)
- [Sync your devices](#sync-your-devices)
- [Backups and export](#backups-and-export)
- [Lock and privacy](#lock-and-privacy)
- [Keyboard shortcuts on the Mac](#keyboard-shortcuts-on-the-mac)
- [Common questions](#common-questions)

## Install on a Mac

1. Download [Thimble.dmg](https://github.com/matguitarist/thimble/releases/latest/download/Thimble.dmg).
2. Open it and drag Thimble to Applications.
3. Open Thimble from Applications.

Thimble checks for updates by itself and asks before installing one. To check now, choose **Thimble ▸ Check for Updates…**.

## Install on Android

1. On your phone, open the [latest release](https://github.com/matguitarist/thimble/releases/latest) and download the file ending in `.apk`.
2. Open it. Android asks you to allow installing apps from your browser the first time. Allow it, then go back and tap **Install**.
3. Google Play Protect may say it doesn't know the app, since it isn't from the Play Store. Choose to install anyway.

The Android app doesn't update itself. To update, download the newer `.apk` from the releases page and install it over the old one. Your tasks stay.

## The lists

| List | What's in it |
| --- | --- |
| **Inbox** | New tasks you haven't sorted yet. |
| **Today** | What you plan to do today, with **This Evening** below it. Tasks whose day has come show up here by themselves. |
| **Upcoming** | Tasks with a day ahead, by date, with your calendar's events beside them. |
| **Anytime** | Everything you could work on now, grouped by project. |
| **Someday** | Ideas for later, out of sight until you want them. |
| **Logbook** | Finished and canceled tasks. |

Areas hold projects, like "Home" or "Work". A project holds tasks, and headings split it into parts. A task can have notes, a checklist, tags, a day to start, a deadline, a reminder, and a repeat.

To see only some tasks, filter a project by tag: on the Mac with **View ▸ Filter by Tag…**, on Android with the chips at the top of the project.

## Add tasks quickly

**Mac**
- Press **Control-Space** in any app for Quick Capture. Type, press Return, and you're back where you were. You can change the shortcut in **Settings ▸ Capture**.
- Turn on **Show Thimble in the menu bar** to add from the menu bar.
- In other apps, use **Share ▸ Thimble**.
- In Shortcuts, Thimble's actions add, find, and complete tasks.
- Choose **File ▸ Import from Reminders…** to bring in your Apple Reminders.

**Android**
- Add the **Thimble** widget to your home screen to see Today and add a task.
- Add the **New Thimble Task** tile to Quick Settings: swipe down twice, tap the pencil, and drag it in.
- Share text or a link from any app to Thimble.

## Dates you can type

Wherever you pick a day, you can type it instead, in English or French:

- `today`, `tonight`, `tomorrow`, `someday`
- `fri`, `next friday`, `on tuesday`
- `in 4 days`, `2 weeks`, `next month`
- `nov 5`, `5 nov`, `November 5th`
- `demain`, `vendredi prochain`, `dans 3 semaines`

## Projects, cards, and the Dashboard

Thimble can follow how your own projects are going, such as apps you build.

- Give a project a card from its menu: **Project Card…** on the Mac, **Project card** on Android. Write each platform and where it stands, like `Mac: released 1.2; Android: built`, with the day of the last release.
- Name a heading after a version, like `1.3`, and the project shows how much of it is done. Its menu offers **Copy Release Notes**, a list of its finished tasks ready to paste.
- Once a project has a card, the **Dashboard** appears. It compares every project with a card: open tasks, what needs you, what's blocked, what hasn't changed in 30 days, and what closed this week.

## Sync your devices

Thimble syncs through a folder that every device can reach, such as one in iCloud Drive, Dropbox, or Syncthing. Each device writes its changes there as encrypted files. Whoever runs that folder sees only sealed files, never your tasks.

1. On your first device, open **Settings ▸ Sync** and choose an empty folder.
2. Choose a passphrase and type it twice. **Write it down somewhere safe.** Nobody can reset it, not even us, because nobody else ever has it.
3. On each other device, choose the same folder and type the same passphrase.

Which folder to use:

- **Mac only, or Mac and iPhone:** iCloud Drive works well.
- **With Android:** Android can't reach iCloud Drive, and most cloud drive apps won't let other apps use a whole folder. [Syncthing](https://syncthing.net) on the Mac and the phone works, and keeps the folder on your own devices.

Settings shows whether sync is up to date. "Can't reach the folder" means the folder or its service is gone for now; your changes wait on the device until it's back. If you forget the passphrase, your tasks on each device are safe. Turn sync off and start again with a new, empty folder.

## Backups and export

- **Backups:** in **Settings ▸ Backups**, choose a folder, and Thimble keeps one backup a day for the last 30 days. Backups are plain files, so choose a folder only you can read. To go back, choose **Restore from Backup…**. Thimble saves what's there now first, and you can undo the restore.
- **Export:** on the Mac, choose **File ▸ Export…** for a copy of everything as plain JSON and Markdown.
- When sync is on, each device also keeps a safety copy each day. If a sync ever empties your lists, Thimble offers that copy back.

## Lock and privacy

- **Lock:** turn on **Lock when you leave Thimble**: in **Settings ▸ Privacy** on the Mac, in **Settings** on Android. It opens with Touch ID, or your phone's fingerprint, face, or screen lock.
- **Reminders:** you can hide a reminder's text on the lock screen.
- **Spotlight:** on the Mac, tasks only appear in Spotlight if you turn that on.
- **Network:** the Mac app goes online only to check for its own updates. The Android app has no internet access at all. Sync uses whatever keeps your folder in step, never a server of ours.
- **Calendar:** Thimble reads your calendar to show events, and never saves or copies them. It's off until you turn it on in **Settings ▸ Calendars**.

## Keyboard shortcuts on the Mac

**Help ▸ Keyboard Shortcuts** lists them all. The ones you'll use most:

| Shortcut | Does |
| --- | --- |
| Control-Space | Quick Capture, from any app |
| ⌘N | New task |
| ⇧⌘N | New heading |
| ⌥⌘N | New project |
| ⌘1 to ⌘0 | Go to a list in the sidebar |
| ⌘F | Find |
| ⌘O | Open the selected task |
| ⌘K | Complete |
| ⌘T | Do today |
| ⌘E | Do this evening |
| ⌘S | Choose when |
| ⇧⌘D | Set a deadline |
| ⇧⌘R | Repeat |
| ⇧⌘M | Move to another list |
| ⇧⌘T | Tags |
| ⇧⌘L | Add a checklist |
| ⌥⌘↑ and ⌥⌘↓ | Move up and down |
| ⌫ | Move to Trash |
| ⌃⌘N | Open the list in a new window |

## Common questions

**Is there an iPhone or iPad version?**
It exists, but it isn't available to download yet.

**Does Thimble cost anything?**
No.

**Where are my tasks stored?**
On each device, in Thimble's own storage. With sync on, also as encrypted files in the folder you chose.

**I moved to a new phone or Mac.**
Turn on sync with the same folder and passphrase, or restore your latest backup.

**Something's wrong.**
[Open an issue](https://github.com/matguitarist/thimble/issues) with your device, its system version, and Thimble's version. Please don't include your tasks.
