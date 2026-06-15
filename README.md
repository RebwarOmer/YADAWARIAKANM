# YADAWARI

Live at (https://yadawari.vercel.app)

YADAWARI is a personal diary web application built for people who want a clean, focused space to write. Each entry is tied to its date, giving your writing a natural timeline that you can revisit and scroll through at any pace.

---

## What It Does

You open the app, you write. Each diary entry is presented as a dated card. When you are done writing, a single save button closes the entry and commits it. Older entries load as you scroll back, so your history is always within reach without cluttering the current view.

The writing experience is intentionally minimal. There are no feeds, no social features, no notifications. Just you and your entries.

---

## Features

**Dated entries**
Every entry is anchored to a specific date and displayed as a clearly marked card. The date is set automatically so the timeline stays accurate without any manual input.

**Load older entries**
Past entries load progressively as you go back through your timeline. You are never shown everything at once, which keeps the interface fast and uncluttered.

**Save and close**
A single save button both persists your current entry and closes it when you are done. No separate save and close actions.

**Export to PDF**
Your diary can be exported as a PDF at any time, giving you a portable, printable copy of everything you have written.

**Google OAuth authentication**
Sign in with your Google account. No passwords to manage or remember.

**Change your display name**
You can update the name associated with your account at any time from the sidebar.

**Dark and light mode**
Switch between dark and light themes depending on your preference or environment. The setting persists across sessions.

**Delete account**
You can permanently delete your account and all associated data directly from the sidebar.

**Sidebar**
A collapsible sidebar gives you access to all account-level controls in one place: change name, toggle theme, export PDF, sign out, and delete account.

---

## Stack

| Layer | Technology |
|---|---|
| Backend | PHP, Laravel |
| Frontend | React, Vite |
| Containerization | Docker |
| Authentication | Google OAuth |
| Hosting | Vercel, Render |
| Version Control | Git |

---

## Architecture Overview

The backend is a Laravel API serving JSON to a React frontend built with Vite. Docker handles local development environment consistency. Authentication is delegated entirely to Google OAuth, meaning no credentials are stored in the application. The frontend is deployed on Vercel and the backend on Render.

---

## Project Status

Active development.
