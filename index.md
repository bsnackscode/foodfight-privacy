---
title: FoodFight — Privacy Policy
---

# FoodFight — Privacy Policy

**Effective date:** August 16, 2026
**Status:** Alpha / TestFlight testing

FoodFight is a small, independently-developed app to help you decide where to
eat. This document explains what data the app uses, where it goes, and what
it doesn't do. It's written in plain language on purpose — if anything here
is unclear, reach out (contact info at the bottom).

---

## The short version

- FoodFight stores your picks, preferences, and location **on your device**.
  There is no account server and no company database of your meals.
- Your location is used **only** to search for nearby restaurants, via
  Google's Places API. It is not stored on any server we control.
- If the app crashes, a report may be sent to **Sentry** so we can fix bugs.
  That report is about the crash (device/app info and a stack trace), not
  your restaurant picks or search history.
- We don't sell, share, or monetize your data.
- There is no real account system yet. "Log in" and "Sign up" are
  placeholder/mock screens that don't create a real account or send your
  email anywhere.

---

## What data the app uses

### Location

FoodFight asks for your device location (or a manually entered zip code /
address) to find restaurants near you. This is sent directly to Google's
Places API to run the search — it is **not** sent to or stored by us. If you
enter a location manually instead, the same applies.

Your most recent search location is saved **locally on your device** (not on
a server) so the app can remember it the next time you open it.

### Search history ("past picks")

When you search and a restaurant wins the FoodFight, that pick is saved **locally on your
device** so you can see your history and avoid repeating recent picks. This
list is not uploaded anywhere and is only visible to you, in the app, on your
device.

### Preferences

Your selected cuisines, search radius, "avoid recent picks" setting, and
"no fast food" preference are saved **locally on your device** so they
persist between sessions.

### Account information

The current login/sign-up screens are mock UI for alpha testing — they do
not create a real account, do not transmit your email or password anywhere,
and do not persist any credentials beyond a local "you're signed in" flag on
your device. **We recommend using "Continue as guest,"** which is the
default option, since no real account exists yet.

### Third-party services

FoodFight uses the **Google Places API** to search for restaurants, fetch
details (hours, rating, photos), and geocode manually entered addresses.
Your search location and query are sent to Google to perform this search,
subject to [Google's Privacy Policy](https://policies.google.com/privacy).
We do not send Google any information beyond what's needed to run the
search (location, radius, cuisine type).

### Crash reports

If the app hits an error or crash, FoodFight may send a report to
**[Sentry](https://sentry.io/)** so we can see what broke and fix it. That
report can include the error message, a stack trace, app version, and
basic device information (for example OS version). It does **not** include
your restaurant history, saved location, or cuisine preferences.

Sentry's handling of that data is described in
[Sentry's Privacy Policy](https://sentry.io/privacy/).

---

## What we don't do

- We don't run product analytics (no tracking of which restaurants you
  pick or how often you search).
- We don't have advertising or ad tracking of any kind.
- We don't sell or share your data with third parties for marketing.
- We don't have a server that stores your personal information — this
  document will be updated if that changes (e.g. once real accounts ship).

---

## Your control over your data

Since everything is stored locally on your device:

- **Deleting the app** deletes all of your FoodFight data (history,
  preferences, saved location, session) — there's nothing left on a server
  to also delete.
- **"Exit guest mode" / "Log out"** in the Profile screen clears your local
  session immediately.

---

## Children's privacy

FoodFight is not directed at children under 13 and does not knowingly
collect data from children under 13.

---

## Changes to this policy

Since FoodFight is in active alpha development, this policy may change as
features are added (for example, if a real backend/account system is
introduced). Material changes will be reflected here with an updated
effective date.

---

## Contact

Questions about this policy or your data? Reach out at:
**bsnacksmgmt@gmail.com**

You can also find the project on GitHub:
**https://github.com/bsnackscode/FoodFight**
