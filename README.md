# ThesisSync

> An API-based scheduling system for thesis consultations and defense coordination.

ThesisSync is a centralized web platform that replaces fragmented scheduling practices — paper logs, group chats, spreadsheets — with an automated booking workflow backed by a REST API and integrated with Google Calendar and Email.

Built for CMSC 186 (Web Services and Service-Oriented Architecture) at **DMPCS, UP Mindanao** under **Asst. Prof. Vicente B. Calag**.

---

## Repositories

| Repository | Stack | Purpose |
|---|---|---|
| [**`thesissync-backend`**](https://github.com/CMSC-186-ThesiSync/thesissync-backend) | FastAPI · Python 3.12 · Supabase | REST API, auth, business logic, Google Calendar & Email integrations |
| [**`thesissync-frontend`**](https://github.com/CMSC-186-ThesiSync/thesissync-frontend) | Next.js 14 · TypeScript · Tailwind · shadcn/ui | Dashboards, calendar view, request forms |

---

## What it does

- **Students** submit consultation and defense requests with preferred dates
- **Advisers** approve, reject, or reschedule requests from a unified dashboard
- **Panelists** receive automatic calendar invites and email reminders
- **Everyone** sees a real-time availability view that prevents double-bookings

Approved sessions are automatically pushed to Google Calendar with a Meet link, and all status changes trigger email notifications.

---

## Team

| Member | Role |
|---|---|
| Francis Reid Arranguez | Backend Developer |
| Gabrielle Xiane Bautista | Frontend Developer & UI/UX Designer |
| John Andrei Manalo | Database & Integrations |

---

## Timeline

An 4-week Agile build (April–June 2026). See the [project board](https://github.com/orgs/CMSC-186-ThesiSync/projects) for live sprint status.

---

*CMSC 186 · 2nd Semester AY 2025–2026 · University of the Philippines Mindanao*
