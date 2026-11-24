# Evan Lambert

Portfolio and personal builds. Live site: the GitHub Pages address for this repository.

## Builds

**Encore** (`/encore`): an anytime year-in-review from a Spotify data export. Parses both export formats, removes duplicates, separates skips from real listens, and looks up artist photos and album art. Runs entirely in the browser.

**Market Pulse** (`/market-pulse`): a scheduled GitHub Actions pipeline that pulls US market quotes and news from the Finnhub API after each close, tags the headlines, refreshes a dashboard, and posts a daily brief to Discord or Slack through webhooks.

## How these were built

I designed and shipped these with Claude (Anthropic's AI) as my engineering partner. I decided what to build, set the requirements and design, made the data decisions, and handled deployment and integrations: GitHub Pages, GitHub Actions, API keys and secrets, and webhooks. Claude wrote the code.

Encore is an independent project and is not affiliated with or endorsed by Spotify.
