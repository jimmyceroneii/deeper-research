# deeper-research
A search engine for fuzzy searches

## Requirements
- Exa AI API Key
- Readwise API Key

## Setup

1. Add Exa API key to an `.env` file with name `EXA_API_KEY` like:

```
EXA_API_KEY=<API_KEY>
```

2. Install `caddy`: https://caddyserver.com/docs/install
3. Add a `CADDY_PATH` variable to your ENV that represents the path to this project (ex: `/Users/<username>/deeper-research)
2. Run `caddy run`
3. Navigate to `http://localhost:8081/deeper-research.html`


> Note: This uses Tailwind CSS via a CDN download in a Script tag. That's not the most secure thing to do, so be warned.
