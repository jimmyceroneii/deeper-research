# deeper-research
A search engine for fuzzy searches

## Requirements
- Exa AI API Key
- Readwise API Key
- LM Studio (or OpenAI API access)

## Setup

1. Replace the `LM_STUDIO_MODEL` and `OPENAI_URL` variables in `deeper-research.html`
2. Add Exa API key to an `.env` file with name `EXA_API_KEY` like:

```
EXA_API_KEY=<API_KEY>
```

3. Install `caddy`: https://caddyserver.com/docs/install
4. Add a `CADDY_PATH` variable to your ENV that represents the path to this project (ex: `/Users/<username>/deeper-research)
5. Run `caddy run`
6. Navigate to `http://localhost:8081/deeper-research.html`


> Note: This uses Tailwind CSS via a CDN download in a Script tag. That's not the most secure thing to do, so be warned.