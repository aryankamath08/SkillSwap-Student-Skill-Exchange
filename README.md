# SkillSwap Enhanced
Interactive student skills exchange platform using HTML, CSS, vanilla JavaScript, Node.js, Express and JSON storage.

## Features
- Search, category filtering, skill-level filtering and A–Z sorting
- Favorite/save skills (browser localStorage) and saved-only view
- Detail modal and learning-request flow saved via backend
- Publish listings, dark/light theme, responsive layout, toast feedback
- JSON persistence for listings and learning requests

## Run
Install Node.js LTS, open folder in VS Code terminal, run `npm install`, then `npm start`, and browse to http://localhost:3000.

## API
GET /api/skills?q=keyword — list/search; POST /api/skills — create listing; DELETE /api/skills/:id — remove; POST /api/skills/:id/request — save request; GET /api/requests — list requests; GET /api/health — health check.

Demo contacts only; do not use real private contact information in publicly displayed listings.
