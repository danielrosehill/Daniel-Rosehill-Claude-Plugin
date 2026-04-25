---
name: view-github-repos
description: Open Daniel Rosehill's public GitHub repositories in the browser. Supports three sort orders — latest (default, by recently pushed), stars, and alphabetical (A–Z). Use when the user asks to "see my repos", "open my GitHub", "list my repos by stars", "show repos A to Z", or similar.
---

# View Daniel's GitHub Repositories

Open one of Daniel's public GitHub repository listings in the default browser.

## Sort options

| Sort | URL |
|------|-----|
| **latest** (default — recently pushed) | https://github.com/danielrosehill?tab=repositories&q=&type=public&language=&sort= |
| **stars** | https://github.com/danielrosehill?tab=repositories&q=&type=public&language=&sort=stargazers |
| **A–Z** (name) | https://github.com/danielrosehill?tab=repositories&q=&type=public&language=&sort=name |

## How to invoke

Pick the URL matching the user's intent (default to **latest** if unspecified) and open it:

```bash
xdg-open "<url>"
```

If the user asks for multiple sorts, open each in a new tab (run `xdg-open` once per URL).

After opening, briefly confirm which view was opened — no need to dump the URL back at the user.
