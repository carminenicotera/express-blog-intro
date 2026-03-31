---
name: express-blog-intro
description: "Workspace instructions for the simple Express blog introduction exercise."
---

This repository is a small Express.js blog tutorial focused on a basic server, a JSON posts route, and static image assets.

When working in this workspace:
- Treat it as a minimal starter app, not a full production project.
- Prefer a simple `server.js` or `app.js` entrypoint.
- Use `express.static()` for serving images and other assets.

Key goals:
- Create a root route `GET /` that responds with plain text: `Server del mio blog`.
- Create an in-memory array of at least 5 posts. Each post should include:
  - `title`
  - `content`
  - `image`
  - `tags` (array of strings)
- Create a route `GET /bacheca` that returns the posts array as JSON.
- Configure static asset serving so post images can be served from a public folder.

If code is missing, scaffold a minimal Node/Express app and add any required `package.json` scripts:
- `npm install express`
- `npm start` (or similar)

Do not:
- Add authentication, databases, or advanced architecture unless the user asks for it.
- Over-engineer the app; keep the implementation small and consistent with the README exercise.

If additional functionality is requested, ask whether it should remain a local tutorial example or become a larger blog application.
