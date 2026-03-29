# 4StaX Docs

Documentation for [4StaX](https://4stax.com) — the personal data OS for the AI era.

Built with [Mintlify](https://mintlify.com). Live at [docs.4stax.com](https://docs.4stax.com).

## Development

Install the Mintlify CLI:

```bash
npm install -g mintlify
```

Run locally:

```bash
mintlify dev
```

Opens at `http://localhost:3000`.

## Structure

```
/
├── mint.json                 # Mintlify config — navigation, colors, logo
├── introduction/             # What is 4StaX, quickstart, concepts
├── memory/                   # Memory layer docs
├── vault/                    # Vault docs
├── developers/               # kontxt, MCP tools, CLI, self-hosting
├── guides/                   # Step-by-step integration guides
├── api/                      # API reference (coming soon)
└── logo/                     # SVG logo files
```

## Contributing

Found something wrong or missing? Open an issue or PR. All docs are markdown/MDX.

## Logo files

Drop your SVG logo files into `/logo/`:
- `4stax-dark.svg` — for dark backgrounds
- `4stax-light.svg` — for light backgrounds  
- `favicon.svg` — browser favicon
