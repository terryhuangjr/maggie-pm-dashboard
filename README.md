# MaggiePM Dashboard

**Vercel Production URL:** https://maggie-pm-dashboard.vercel.app (or production equivalent)
**Host:** Vercel (Frontend)
**Tech Stack:** React + TypeScript + Vite, Supabase
**Agent:** Hermes agent (`maggie-pm-agent`) running on VPS (DigitalOcean, Ubuntu 22.04 at 167.172.135.39)

---

## Overview

MaggiePM is a property management dashboard that integrates with Supabase and connects to the `maggie-pm-agent` running on a separate VPS. It features financial reports, property details, tenant management, and calendar views.

## Key Components

1. **Frontend:** Vite + React + TypeScript, deployed on Vercel.
2. **Backend/Database:** Supabase handles data storage (properties, tenants, leases, tasks).
3. **Hermes Agent:** The `maggie-pm-agent` runs via PM2 on the DigitalOcean VPS to manage tasks, Dropbox files, and syncs.

## Recent Updates
- Integrated Supabase DB.
- Replaced generic Vite template documentation.
- Accounts switcher and YTD/range reports added.

## Development

```bash
# Install dependencies
npm install

# Run locally
npm run dev
```

For more info, refer to the global `SYSTEMS.md` file.