# DaizSign E2E Executive Profile Card

Day 1 internship sprint project: a reusable, responsive "Expert to Expert" Executive Profile Card.

## Stack

- Next.js (App Router)
- React
- JavaScript
- Tailwind CSS
- Git / GitHub

## Design System

- Matte Black: `#0A0A0A`
- Surface Black: `#121212`
- Emerald: `#047857`
- Metallic Gold: `#D4AF37`

## Project Structure

```text
app/
  globals.css
  layout.js
  page.js

components/
  ExecutiveProfileCard.jsx
  SkillTag.jsx
```

The card is modular and data-driven. `ExecutiveProfileCard` accepts `name`, `title`, `bio`, `image`, and `skills` props so the same component can represent different executives.

## Run Locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Git Workflow

Suggested commits:

```bash
git init
git add .
git commit -m "chore: initialize Next.js executive profile project"

git add .
git commit -m "feat: implement executive profile card layout"

git add .
git commit -m "style: apply premium DaizSign color palette"

git add .
git commit -m "style: refine responsive executive card"

git push -u origin main
```

## Note on the profile image

The placeholder uses a remote Unsplash image with a 4:5 crop treatment. For a final production submission, replace it with an approved professional stock image or a project-owned asset.
