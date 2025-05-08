# CodeCraft Summit 2025

## Project Overview

**CodeCraft Summit 2025** is a Next.js web application for event registration, referral, and ranking. Users can register for the event, invite others, and compete for prizes based on successful referrals.

## Features

- **Event Landing Page:** Details about the event, including date, time, and format.
- **Registration Form:** Users can sign up with name and email, with validation.
- **Invite & Referral System:** After registering, users receive a unique invite link to share.
- **Referral Stats:** Users can track link accesses, successful referrals, and their ranking.
- **Leaderboard:** Displays the top referrers and their invite counts.
- **Responsive Design:** Optimized for both desktop and mobile.

## Tech Stack

- **Framework:** [Next.js 15](https://nextjs.org/)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Form Validation:** React Hook Form + Zod
- **Icons:** Lucide React


## Project Structure

- `src/app/(home)/page.tsx` — Event landing and registration form
- `src/app/invite/page.tsx` — Invite and referral dashboard
- `src/app/invite/ranking.tsx` — Leaderboard component
- `src/app/invite/stats.tsx` — Referral statistics
- `src/app/invite/invite-link-input.tsx` — Copy/share invite link
- `src/components/` — Reusable UI components
- `src/assets/` — Images and SVGs

## Customization

- **Event Details:** Update event info in `src/app/(home)/page.tsx`.
- **Referral Logic:** The current implementation uses static data; integrate with a backend for real tracking.
