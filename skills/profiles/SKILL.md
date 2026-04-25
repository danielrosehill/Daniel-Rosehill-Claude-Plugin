---
name: profiles
description: Open Daniel Rosehill's profile on a specific external network — LinkedIn, X (Twitter), GitHub, YouTube (main or tech channel), npm, Kaggle, DeviantArt, or Pexels. Use when the user says "open my LinkedIn", "go to my X", "youtube channel", "npm profile", "kaggle datasets", "deviantart", "pexels", "connect on <network>", or similar.
---

# Daniel's External Profiles

Open Daniel's profile on the requested network in the browser.

| Network | URL |
|---------|-----|
| **LinkedIn** | https://www.linkedin.com/in/danielrosehill |
| **X** (Twitter) | https://x.com/danielrosehill |
| **GitHub** | https://github.com/danielrosehill |
| **YouTube — main** (Daniel Rosehill Video) | https://www.youtube.com/c/DanielRosehillVideo |
| **YouTube — tech** (Daniel On Tech) | https://www.youtube.com/@danielontech |
| **npm** | https://www.npmjs.com/~danielrosehill |
| **Kaggle** (datasets) | https://www.kaggle.com/danielrosehill/datasets |
| **DeviantArt** | https://www.deviantart.com/danielrosehill |
| **Pexels** | https://www.pexels.com/@danielrosehill/ |

## How to invoke

```bash
xdg-open "<url>"
```

If the user says "youtube" without specifying which channel, ask (main vs tech) — or open both in tabs if they say "all" / "both". Same for any ambiguous reference. Confirm what was opened (one short line).

For sharing the link as text rather than opening, just paste the URL back.
