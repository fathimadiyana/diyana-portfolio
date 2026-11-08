# diyana-portfolio

Personal portfolio for Fathima Diyana C H, a final-year B.Tech IT student focused on machine learning, data science and full-stack development.

All content comes from the resume. Nothing is invented: no metrics, testimonials or extra claims.

## Tech stack

- Next.js 14 (App Router) and React 18
- Tailwind CSS 3, with automatic dark mode
- TypeScript
- No API keys or environment variables needed

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000. The fonts (Inter, JetBrains Mono) load through `next/font`, so the first run needs internet access.

## Customize

All text lives in one file: `data/content.ts`.

- `profile`: name, headline, email, phone, about text. Paste your LinkedIn and GitHub URLs into `linkedin` and `github`; they stay hidden while empty.
- `projects`: add or edit entries. Set `featured: true` to show a project as a large card.
- `experience`, `skills`, `education`, `hackathons`, `certifications`, `leadership`: edit the arrays.

Components are in `components/`, one per section. Colours use Tailwind's `emerald` accent, so changing it is a find-and-replace.

## Deploy

1. Push this folder to a new GitHub repository.
2. Import the repository in Vercel. It detects Next.js automatically.
3. Click Deploy.
