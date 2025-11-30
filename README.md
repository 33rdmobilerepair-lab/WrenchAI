# WrenchAI — AI-Powered Car Diagnostic Tool

This package contains a ready-to-deploy static frontend and a serverless API function to create an AI-driven car diagnostic website.  
Style: **Professional Workshop** (black/steel gray/yellow).

## What's included
- `index.html` — Static frontend (single file)
- `api/diagnose.js` — Vercel-style serverless function (Node) accepting multipart/form-data
- `README.md` — This file
- `LICENSE.txt` — MIT license

## Quickstart (Vercel)
1. Create a new Git repository and add these files.
2. In Vercel, import the repository.
3. Place `api/diagnose.js` in the `api/` folder (it already is).
4. Set environment variable `OPENAI_API_KEY` in Vercel dashboard.
5. Deploy.

## Environment variables
- `OPENAI_API_KEY` — required. Your OpenAI API key.
- For media uploads (optional): set up S3 or Supabase storage and update `api/diagnose.js`.

## Notes & Next steps
- Replace affiliate placeholders in `index.html` with your Amazon Associates or other affiliate links.
- Implement media uploads (S3/Supabase) if you want to analyze user videos/images.
- Add Stripe/Gumroad integration for the Pro report button.
- Add rate limiting and reCAPTCHA to `api/diagnose` to prevent abuse.
- Ensure compliance with privacy policy and create `privacy.html` and `terms.html`.

## License
MIT
