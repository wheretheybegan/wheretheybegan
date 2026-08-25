# Where They Began Website Funnel

This repository contains a production-ready, static one-page marketing site for **Where They Began**.

Purpose:

- Send visitors to the official YouTube channel: https://www.youtube.com/@wheretheybegan
- Encourage subscriptions and viewing directly on YouTube
- Keep the page fast, simple, and deployable without a backend

## Local preview

1. Install dependencies:

   ```bash
   npm install
   ```

2. Build the static output:

   ```bash
   npm run build
   ```

3. Preview the built site:

   ```bash
   npm run preview
   ```

   Then open http://localhost:4173

## Hosting

- **AWS Amplify Hosting**: `amplify.yml` is included and publishes the `dist` folder.
- **S3 + CloudFront**: run `npm run build` and upload the contents of `dist/` as static assets.

No authentication, database, or backend services are required.
