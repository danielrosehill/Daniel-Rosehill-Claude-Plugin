---
name: pull-bio
description: Fetch Daniel Rosehill's bio from his About page and load it into the conversation. Use when the user says "pull my bio", "get my bio", "fetch about page", "load my bio", or needs bio text for a profile / proposal / intro.
---

# Pull Bio

Fetch Daniel's bio from https://www.danielrosehill.com/about and load the content into the conversation.

## How to invoke

Use WebFetch:

```
WebFetch url=https://www.danielrosehill.com/about
        prompt="Extract Daniel Rosehill's bio — full text, no navigation/footer chrome. Preserve paragraph breaks."
```

If WebFetch isn't available, fall back to:

```bash
curl -fsSL https://www.danielrosehill.com/about | pandoc -f html -t plain
```

After fetching, present the bio text. If the user wants it for a specific use (LinkedIn, proposal, email), offer to adapt length/tone.
