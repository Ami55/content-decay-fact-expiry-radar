# Content Decay & Fact Expiry Radar

Vercel-ready app for extracting, governing and reviewing time-sensitive claims across content pages.

## Deploy the app

Upload all files from the app ZIP to a new GitHub repository and import it into Vercel. The app project does not require environment variables.

## Gemini Proxy 3

Upload `fact-expiry-radar.js` from the separate proxy ZIP into the `api` folder of `gemini-proxy-3`. Confirm that the proxy project has `GEMINI_API_KEY`.

The app calls `https://gemini-proxy-3.vercel.app/api/fact-expiry-radar`.

AI extraction creates review candidates only. A person must add the authoritative source, verify the claim and choose the final review window. Data is stored in the current browser; export JSON backups regularly.
