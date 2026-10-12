# daily-observer

Daily attendance helper running on GitHub Actions.

- Set `GLADOS_COOKIE` (required) and `PUSHPLUS_TOKEN` (optional) as repository secrets.
- Scheduled daily; sleeps until a random moment in the target window to avoid burst patterns.
