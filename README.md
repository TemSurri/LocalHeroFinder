# Local Hero Finder

**Local Hero Finder** is a community-driven emergency assistance platform built to connect people in urgent need with nearby trained responders, such as those certified in CPR, first aid, or basic emergency care.  




It’s designed as a proof-of-concept MVP to demonstrate real-time geolocation, role-based user authentication, and responder availability management using **Supabase**, **React**.
Didn't have enought time to implement all features or debug everything:

- Deployed but only works if you already have an acoount lol since theres SMS and email authentification problem on vercel with Sign up and Sign in ( works on local but spotty on vercel )


https://localherofinder.vercel.app/
---

## Features

###  Requesters
- Quickly send an emergency alert with a single tap.
- Automatically share your location (with permission).
- See matched responders and estimated arrival times.
- Integrated safety tips while waiting for help.

###  Responders
- Apply to become a verified responder with skills and certifications.
- Toggle your **availability** in real-time (location updates included).
- View incidents nearby and navigate to them.
- Gain “Hero Points” for completed responses (future gamification idea).

###  Authentication & Roles
- Secure sign-in and sign-up powered by **Supabase Auth**.
- Automatic role assignment (`requester` or `responder`).
- Row-Level Security (RLS) policies for data privacy and separation.

---

## Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Frontend** | React + Vite + TypeScript |
| **UI Library** | Tailwind CSS + Shadcn/UI + Lucide Icons |
| **Database** | Supabase (PostgreSQL) |
| **Auth & Storage** | Supabase Auth, Supabase Storage |
| **Maps & Geolocation** | Leaflet + OpenStreetMap |
| **Deployment** | Vercel |
| **Notifications** | Sonner (Toast system) |

---

