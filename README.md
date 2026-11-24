# Memolok agent integrations

This repository is Memolok's public distribution nexus for agent hosts. The repo name and this
README are provider-neutral; a host gets its own dot-folder only when it cannot read one already
here.

| Host | Catalog | Install |
| --- | --- | --- |
| **Claude** (Code / desktop) | [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json) | Add this repo as a marketplace, then install **Memolok** from the directory |
| **Codex** (experimental) | [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json), which Codex also reads | Add this repo as a marketplace, then install `memolok` from it |
| **Other hosts** | — | Not yet; see [www.memolok.ai](https://www.memolok.ai) |

## Claude

1. In Claude, open **Customize → Plugins → Add → Add marketplace → Add from a repository**.
2. Paste `https://github.com/Memolok/Memolok-marketplace.git` and sync.
3. Install **Memolok** from the directory.

## Codex (experimental)

From the Codex command line:

```bash
codex plugin marketplace add Memolok/Memolok-marketplace
codex plugin add memolok@memolok
```

Then start a new conversation in Codex; it opens a browser to sign in to Memolok the first time.

The Memolok plugin itself lives in a separate repository
([Memolok/Claude-plugin](https://github.com/Memolok/Claude-plugin)); this nexus only
lists where to fetch it.
