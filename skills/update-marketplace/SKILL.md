---
name: update-marketplace
description: Refresh the local cache of Daniel Rosehill's Claude Code plugin marketplace so newly published plugins/updates show up. Use when the user says "update marketplace", "refresh plugins", "pull latest plugins", "marketplace update", or after pushing a new plugin/version.
---

# Update Daniel's Plugin Marketplace

Refresh the local marketplace cache for `danielrosehill/Claude-Code-Plugins` so the latest plugin entries become installable.

```bash
claude plugins marketplace update danielrosehill
```

If the marketplace has never been added on this machine, add it first:

```bash
claude plugins marketplace add danielrosehill/Claude-Code-Plugins
```

After updating, the user can install or upgrade plugins with `claude plugins install <name>@danielrosehill`. Mention this only if relevant to what the user asked.

Browse the catalog at https://claude.danielrosehill.com/.
