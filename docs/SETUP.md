# Setup

Requires Node.js 20+ and MongoDB 7+ (or a MongoDB Atlas connection string). Copy `.env.example` to `.env`, provide `MONGODB_URI` and `JWT_SECRET`, then run `npm install` and `npm run dev`. The UI remains usable without MongoDB and uses safe demo responses when an AI provider is not configured.

For deployment, build with `npm run build`, serve `server/dist`, and host `client/dist` from a static provider. Configure `AI_API_URL` and `AI_API_KEY` only on the server environment.
