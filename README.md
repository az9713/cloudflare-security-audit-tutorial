# Cloudflare security-audit tutorial

A one-page, tabbed guide for app developers with little security background. It explains:

- common security problems in apps (trust boundaries, the five questions an attacker asks, common bug types);
- how an AI security audit works, using Cloudflare's open-source `security-audit` skill as the example;
- how to build your own vulnerability harness, based on Cloudflare's design.

The page has diagrams, animations, and interactive demos.

**Live page:** https://az9713.github.io/cloudflare-security-audit-tutorial/

## Sources

1. Cole Medin, "hack your own app first" (video): https://www.youtube.com/watch?v=f1gAilgILeI
2. Cloudflare, `security-audit` skill (MIT license): https://github.com/cloudflare/security-audit-skill
3. Cloudflare blog, "Build your own vulnerability harness": https://blog.cloudflare.com/build-your-own-vulnerability-harness

Numbers in the guide are as stated in those sources when they were published.

## Files

- `index.html` — the guide. One self-contained file with no external dependencies.
- `README.md` — this file.

Only test apps that you own or have written permission to test.
