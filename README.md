<!-- DRAFT for review (v0.5.4 item 36). Goes to bedtime-bridge-showcase as README.md once the owner OKs it.
     📷 marks a screenshot (dark mode, nothing personal showing); images go in images/ in that repo. -->

<p align="center">
  📷 <i>App icon</i>
</p>

<h1 align="center">Bedtime Bridge</h1>

<p align="center"><b>Up on time, every time.</b></p>

<p align="center">
For regular schedules, shifts and everything in between. Bedtime Bridge reads your work schedule
from your calendar, or from your week or rotation if you don't keep one, and sets your wake-up
alarms every night, then makes sure you actually get up.
</p>

<p align="center">
  <a href="#">Join the TestFlight beta</a> ·
  <a href="https://github.com/2tk785fryr-tech/bedtime-bridge-shortcuts">Shortcuts</a> ·
  <a href="https://github.com/2tk785fryr-tech/bedtime-bridge-homeassistant">Home Assistant</a>
</p>

📷 *Hero: three phone screens side by side (Tonight, an alarm ringing, the Lock Screen countdown)*

---

## Who it's for

- **Regular schedules:** a 9-to-5 most days, and it handles the exceptions for you: an early
  appointment, a flight, a day off or a vacation, so you never set or cancel an alarm by hand.
- **Shift workers** whose start time changes from day to day: days, swings, nights, rotations.
- **Heavy sleepers** who've slept through an alarm, or turned it off and fallen back asleep.

You shouldn't have to remember to set an alarm, work out what time it needs to be, or hope you
heard it.

---

## The three parts that matter

### 1. Your shifts

Tell the app when you work, whichever way suits you. No work calendar needed:

- **My week:** the same days and hours each week.
- **A rotation:** pick a ready-made shift pattern or build your own. Change crews from a date,
  give a shift a flex time, and share your rotation with a coworker by link or QR code.
- **Your calendar:** put your shifts in Apple Calendar the way you already do.
- **An import:** your work's schedule from a file or a calendar link, kept in the app.

Schedule kept in the app and want it on your calendar too? **Add to Apple Calendar** copies your workdays into a Work
calendar. Move or delete a shift there and the app follows, with **Put it back** if you change your
mind.

Bedtime Bridge knows each shift type ("Days", "Swings", "Nights") and gives each its own wake-up:

- **A fixed time** (always up at 4:30 for Days),
- **a set time before the shift**, or
- **worked back from the drive:** your get-ready time plus the drive, so you leave on time.

Appointments, flights, remote days, vacations and holidays are handled too, each the way you'd
expect: a flight wakes you for the airport, a remote day skips the drive, a vacation day lets you
sleep.

📷 *Screenshot: Settings → Your schedule with Days and Swings*

### 2. Your home

Pick how the app works with your house:

| | |
|---|---|
| **Home Assistant** | The full setup. Home Assistant sets the alarms at bedtime, runs your wake-up and bedtime routines, and steps in with lights and speakers if you're still in bed when you should be up. The backstops work with My week and rotations too. |
| **Apple Home** | Your Home scenes run from the alarm buttons, and a snooze can fade the lights up. Backstops are written as Home automations on your home hub. |
| **None** | Just the phone. Everything about alarms still works. |

📷 *Screenshot: Settings → Home system*

### 3. How your alarms get set

Set it up once and forget it:

- **A Focus filter (recommended):** when Sleep Focus turns on at bedtime, the app plans tomorrow
  and sets your alarms. Nothing to remember, and it works even if you swiped the app away.
- **A shortcut:** at a time you choose, and it can dim the lights or play music at the same
  time.
- **Yourself, from the app:** one tap.

Whichever you choose, the next 2 mornings are always set ahead as a safety net.

📷 *Screenshot: the "How your alarms get set" choice*

---

## Your week, your way

- **Coming up is your week.** Tap a day to change just that day: a day off, different hours, or
  working from home.
- **+ Leave and + Different hours** sit at the top, for a quick change.
- **Skip until…** takes the alarms off for a few days, and you can undo it any time before then.
- **An evening check:** if you turned off tomorrow's alarm and it's a workday, a notification at 8 PM reminds you.

📷 *Screenshot: Coming up with the week*

---

## Getting you up

- **One alarm is enough for most people.** Stopping an alarm takes a slide, so it's hard to turn
  off by accident, and backstops follow if you're not up. Heavy sleeper, or you tend to turn an
  alarm off and fall back asleep? Add a second or third alarm in Settings.
- **Real alarms.** They ring through Silent mode and Focus, on the Lock Screen and the Dynamic
  Island.
- **Snooze with a countdown** you can see on the Lock Screen.
- **Follow-up rings.** If an alarm goes unanswered, it rings again.
- **Stop means stop, on purpose.** A slide to stop one alarm, a hold to end them all, so a
  half-asleep tap doesn't end your morning.
- **"Am I up?"** With a bed sensor, the app knows if you stopped the alarm but stayed in bed, and
  keeps the later alarms.
- **Backstops** (Home Assistant or Apple Home): if you're still in bed as your deadline nears,
  the house gets louder, step by step: a lamp, then speakers and every light.

📷 *Screenshot: an alarm ringing* · 📷 *Screenshot: the snooze countdown on the Lock Screen*

---

## Your evening

- **Wind-down:** a reminder before bed, worked back from your wake-up and your sleep goal, so
  you get the sleep you meant to.
- **Go-to-bed reminders** that get firmer if you're still up.
- **Tomorrow's plan in the evening:** when you're up, when to leave, and why.

📷 *Screenshot: Tonight with tomorrow's plan*

## Your morning

- **Leave-by reminders** from live traffic (Apple Maps, Google or TomTom), checked again in the
  morning.
- **Bad-weather extra time:** snow or ice moves your alarms earlier.
- **Good Morning** turns off Sleep Focus and starts your morning routine.
- **Sleeping-in mornings:** on a day with nothing on, no alarm, and an easy way to say you're up.

📷 *Screenshot: Your morning with the leave-by time*

---

## And more

- **Naps** with their own short alarm series.
- **Temporary alarms** for a one-off early start, without touching your plan.
- **Military duty days** on a rotation, with muster times.
- **Widgets, Live Activities, Control Center controls and Siri.**
- **Trips:** times show in the time zone where they happen, the morning weather follows you, and a flight
  shows once.
- **Weekly summary** of the week ahead.
- **History:** what happened each day: bed time, hours slept, alarms and snoozes.
- **Briefings:** a short spoken morning and bedtime rundown.
- **Settings grouped by what they're for:** waking up, your schedule, getting to work, going to
  bed and your smart home. New setups start grouped; **Show all options** brings back the full list.
- **Your clock, your icon:** 12- or 24-hour, and a choice of app icons.

📷 *Screenshot: widgets on the Home Screen*

---

## Set up in minutes

A short setup walks you through your work schedule, your home and how your alarms get set, and
the app asks for a permission only when a feature needs it. **See how it works** (a short
walkthrough of a night and a morning) and a **Quick tour** of the main screens are in Settings.

📷 *Screenshot: the first How to use page*

---

## Works with

- **[Bedtime Bridge shortcuts](https://github.com/2tk785fryr-tech/bedtime-bridge-shortcuts):**
  ready-made shortcuts for bedtime, good morning, naps, wind-down and more.
- **[Bedtime Bridge for Home Assistant](https://github.com/2tk785fryr-tech/bedtime-bridge-homeassistant):**
  the integration and blueprints for the full house setup.

---

<p align="center"><b>Up on time, every time.</b></p>
