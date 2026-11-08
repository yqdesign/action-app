# Action Tracker

A minimal meeting action tracker. Add actions with an owner and due date, group them by owner, tick them off, and spot overdue items at a glance.

- Single static page (`index.html`), no build step or dependencies
- Data is stored in a shared Supabase table (`actions`), so the whole team sees the same list
- Sign in and sign out use Supabase Auth (`auth.users`); each user has a row in `profiles` (username, role)
- Admins can add users and set their initial password from the Team members card

## Deploy on Vercel

1. Import this repository at https://vercel.com/new
2. Framework Preset: **Other**
3. Leave Build Command and Output Directory empty, then click **Deploy**

## Run locally

Open `index.html` in a browser.
