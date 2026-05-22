# Security Policy

## About This Repository

This is a **static portfolio site** — it contains only HTML, CSS, images, and icons. There are no API keys, credentials, or backend code in this repository.

## Secret Hygiene Rules

- ❌ **Never commit** `.env`, `.env.local`, server configs, logs, or any credentials
- ❌ **Never commit** `*.pem`, `*.key`, `*.p12`, `*.pfx`, or `*.secret` files
- ✅ Server configuration (Apache, Cloudflare, etc.) stays on the server only
- ✅ Only static public assets belong in this repository

## Environment Variables Required

This is a static site — no environment variables are required to build or serve it.

If you deploy this via a CI/CD pipeline, ensure no credentials are injected into the static HTML at build time.

## Reporting Vulnerabilities

If you discover a security vulnerability in this project or the live site at [richgibbs.dev](https://richgibbs.dev), please report it directly to the repository owner (**RichGibbs-prog**) via GitHub private disclosure rather than opening a public issue.
