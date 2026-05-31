# swarmlord docs

Public documentation for [swarmlord](https://swarmlord.ai) — a platform for running long-lived AI agents.

Built with [Mintlify](https://mintlify.com).

## Local preview

```bash
bunx mint dev
# or
npx mint dev
```

Opens http://localhost:3000.

## Structure

```
docs.json              # Mintlify config (navigation, theme)
favicon.svg
introduction.mdx       # /
quickstart.mdx         # /quickstart
concepts/
  agents.mdx           # /concepts/agents
  sessions.mdx         # /concepts/sessions
  mcps.mdx             # /concepts/mcps
guides/
  cli.mdx              # /guides/cli
  sdk.mdx              # /guides/sdk
  sendblue-research-agent.mdx
api/
  http.mdx             # /api/http
  events.mdx           # /api/events
```

## Publishing

Mintlify auto-deploys on push to `main` once this repo is connected at [mintlify.com](https://mintlify.com). The `docs.json` file is the source of truth for navigation.

## Contributing

Pull requests welcome — typo fixes, clarifications, missing examples. For changes to the platform itself, file issues against the platform.

## Conventions

- Front matter has `title` and `description` (single short sentence).
- Code examples should be runnable as-is, copy-pasteable.
- Prefer `<Card>` / `<CardGroup>` / `<AccordionGroup>` for scannable pages.

## License

Documentation © swarmlord contributors. Code samples are MIT-licensed.
