<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/zephyr-wordmark-light.svg">
  <img alt="Zephyr Cloud" src="./assets/zephyr-wordmark-dark.svg" width="260">
</picture>

**Always deployed. Released when you're ready.**

[Website](https://zephyr-cloud.io/) · [Docs](https://docs.zephyr-cloud.io/) · [Blog](https://zephyr-cloud.io/blog) · [Discord](https://discord.gg/zephyrcloud) · [X](https://x.com/ZephyrCloudIO) · [YouTube](https://www.youtube.com/@ZephyrCloud) · [Status](https://status.zephyr-cloud.io/)

</div>

---

We're the team behind Module Federation. We build two products:

- **[Zephyr Cloud](#zephyr-cloud)**: every build gets a live URL, and you choose when production moves.
- **[The AI Platform](#the-ai-platform)**: one shared workspace where your team and its agents work together.

## Zephyr Cloud

Add `withZephyr()` to your bundler config. Every build then uploads only its changed files and gets its own permanent URL. Environments are tags that point at builds, so a release or rollback just moves a pointer, with no rebuild and no re-upload.

```bash
# Start a new app
npx create-zephyr-apps@latest

# Add Zephyr to an existing app
npx with-zephyr

# Teach your coding agent (Claude Code, Cursor, Codex, …) to deploy with Zephyr
npx skills add ZephyrCloudIO/skills
```

Guides, framework setup and API reference are at **[docs.zephyr-cloud.io](https://docs.zephyr-cloud.io/)**.

- **[zephyr-packages](https://github.com/ZephyrCloudIO/zephyr-packages)**: the Zephyr plugins for your bundler
- **[zephyr-examples](https://github.com/ZephyrCloudIO/zephyr-examples)**: example apps to start from
- **[zephyr-preview-environment-action](https://github.com/ZephyrCloudIO/zephyr-preview-environment-action)**: a preview environment for every pull request
- **[skills](https://github.com/ZephyrCloudIO/skills)**: teach your coding agent to deploy with Zephyr

## The AI Platform

<img align="right" alt="The AI Platform" src="./assets/tap-logomark-dark.svg" width="64">

[The AI Platform](https://theaiplatform.app/) is a desktop workspace for people and agents. It gives the whole org shared channels and context, routes each task to Claude, GPT or a local model, and tracks spend by person, team and feature. It runs against your repo, your machines and your keys.

[Download](https://theaiplatform.app/download) (macOS, Windows, Linux) · [Getting started](https://docs.theaiplatform.app/guide/getting-started/index.html) · [Marketplace](https://theaiplatform.app/marketplace) · [Pricing](https://theaiplatform.app/pricing) · [Changelog](https://theaiplatform.app/changelog) · [X](https://x.com/_TheAIPlatform)

## Contributing

Issues and PRs are welcome on any public repo. If you're new, start with [`zephyr-examples`](https://github.com/ZephyrCloudIO/zephyr-examples), and ask questions in [Discord](https://discord.gg/zephyrcloud).
