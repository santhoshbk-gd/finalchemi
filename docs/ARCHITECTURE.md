# Architecture

The monorepo uses npm workspaces. `client/` is a Vite React TypeScript SPA with component-driven views, motion interactions, responsive CSS, and API proxying. `server/` is an Express TypeScript REST API. It applies CORS, JSON parsing, rate limiting, Zod validation, bcrypt hashing, JWT authentication, and consistent public error messages. MongoDB/Mongoose is the persistence boundary; AI access is server-side only.

Future feature domains should use `server/src/{models,controllers,services,routes}` and client feature folders under `client/src/features`.
