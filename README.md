# Memolok agent integrations

This repository is Memolok's public distribution nexus for agent hosts. The repo name and this
README are provider-neutral; each supported host gets its own dot-folder when we ship for it.

| Host | Catalog | Install |
| --- | --- | --- |
| **Claude** (Code / desktop) | [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json) | Add this repo as a marketplace, then install **Memolok** from the directory |
| **Other hosts** | — | Not yet; see [www.memolok.ai](https://www.memolok.ai) |

## Claude

1. In Claude, open **Customize → Plugins → Add → Add marketplace → Add from a repository**.
2. Paste `https://github.com/Memolok/memolok-marketplace.git` and sync.
3. Install **Memolok** from the directory.

Full step-by-step instructions for first-time setup:
[www.memolok.ai](https://www.memolok.ai) (POC install guide).

The Memolok plugin itself lives in a separate repository
([Memolok/memolok-claude-plugin](https://github.com/Memolok/memolok-claude-plugin)); this nexus only
lists where to fetch it.
