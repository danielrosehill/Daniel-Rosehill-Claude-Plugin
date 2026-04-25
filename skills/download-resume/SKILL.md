---
name: download-resume
description: Download Daniel Rosehill's resume / CV — public PDF, agent-readable JSON, or open the CV web page. Use when the user says "download my resume", "get my CV", "fetch resume JSON", "open my CV page", or similar.
---

# Download Resume / CV

Three resume artefacts are available:

| Target | URL | Default save path |
|--------|-----|--------------------|
| **PDF** (public resume) | https://www.danielrosehill.com/files/docs/pdf/daniel-resume-public.pdf | `~/Downloads/daniel-resume-public.pdf` |
| **agent JSON** (machine-readable) | https://www.danielrosehill.com/files/docs/resume-agent.json | `~/Downloads/resume-agent.json` |
| **CV web page** (open in browser) | https://www.danielrosehill.com/about/cv | — |

## Actions

**Download PDF or JSON:**

```bash
curl -fsSL -o ~/Downloads/daniel-resume-public.pdf https://www.danielrosehill.com/files/docs/pdf/daniel-resume-public.pdf
curl -fsSL -o ~/Downloads/resume-agent.json https://www.danielrosehill.com/files/docs/resume-agent.json
```

**Open CV page in browser:**

```bash
xdg-open https://www.danielrosehill.com/about/cv
```

If the user wants the JSON loaded into the conversation (rather than saved), fetch it and Read it back. Default to PDF if unspecified.
