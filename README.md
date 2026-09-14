# AI Dashboard — GitHub Pages

IBM-style static website for presenting AI Agent adoption across:
- Integration Agent
- Observability Agent
- B2B Agent

## Files
- `index.html` — landing page
- `integration-observability.html` — Integration + Observability report
- `b2b-agent.html` — B2B Agent report
- `data.js` — replace the empty arrays with the actual report rows

## Loading your data
Edit `data.js`. Example:

```js
integrationObservability: [
  {
    market: "India",
    account: "Example Account",
    environment: "Production",
    integrationAgent: "Adopted",
    observabilityAgent: "Trial",
    adoptionStage: "Aha Moment",
    firstActivity: "2026-09-01",
    notes: "Example note"
  }
],
b2b: [
  {
    market: "India",
    account: "Example Account",
    environment: "Production",
    b2bAgent: "Adopted",
    adoptionStage: "Onboarded",
    firstActivity: "2026-09-01",
    notes: "Example note"
  }
]
```

## Publish on GitHub Pages
1. Create a GitHub repository, e.g. `ai-dashboard`.
2. Upload all files in this folder to the repository root.
3. In GitHub: **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save. GitHub will provide the Pages URL.

The site is intentionally framework-free, so it works directly as a GitHub Pages static site.
