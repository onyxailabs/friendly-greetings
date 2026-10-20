# ProposaLite — Proposal Builder & E-Signature for Freelancers

ProposaLite is a minimalist proposal builder and e-signature tool for freelancers. Draft a proposal, share it through a private link, and get it signed — without the bloat of enterprise sales software.

Built with TanStack Start, React 19, TypeScript, and Supabase.

## Features

- **Proposal editor** — create and edit proposals in a clean, focused editing view (`src/routes/editor.$id.tsx`)
- **Dashboard** — manage all your proposals in one place (`src/routes/dashboard.tsx`)
- **Shareable proposal links** — send each client a private link to view their proposal (`src/routes/proposal.$id.tsx`)
- **E-signature** — clients sign directly on the proposal page
- **Supabase backend** — authentication and database, with migrations in `supabase/`
- **Modern UI** — Radix UI components, React Hook Form with Zod validation

## Routes

| Route | What it is |
|---|---|
| `/` | Landing page — the Draft / Share / Sign pitch |
| `/dashboard` | Your proposals dashboard |
| `/editor/$id` | Create and edit a proposal |
| `/proposal/$id` | Client-facing proposal view with signing |

## Run it locally

You need [Bun](https://bun.sh) (there is a `bun.lock`; Node.js + npm works too) and a Supabase project. Put your Supabase credentials in `.env`.

```bash
bun install
bun run dev
```

Then open the local dev URL that Vite prints (usually http://localhost:5173). `bun run build` creates a production build.

## Tech stack

TanStack Start · React 19 · TypeScript · Vite · Supabase · Radix UI · React Hook Form + Zod · Bun

---

**Built by Muhammad Mohsin — Onyx AI** · [YouTube](https://www.youtube.com/@onyxaipk) · [All products](https://mohsina91.gumroad.com) · [Catalog](https://mohsinakramchandia91-bit.github.io/Catalog/)
