<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ZephyrCloudIO/.github/raw/main/profile/assets/zephyr-wordmark-light.svg">
  <img alt="Zephyr Cloud" src="https://github.com/ZephyrCloudIO/.github/raw/main/profile/assets/zephyr-wordmark-dark.svg" width="260">
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

# Deploy a folder you've already built
npx zephyr-cli deploy ./dist

# Teach your coding agent (Claude Code, Cursor, Codex, …) to deploy with Zephyr
npx skills add ZephyrCloudIO/skills
```

**Bundlers and frameworks:** Vite, Rspack, Rsbuild, webpack, Rollup, Rolldown, Parcel, Astro, Nuxt, TanStack Start, Modern.js, Re.Pack and Metro (React Native), plus more [in the docs](https://docs.zephyr-cloud.io/).

**Deploy targets:** Zephyr Cloud (managed), Cloudflare, AWS, Fastly, Akamai, or several of them at once.

### Repositories

| Repo | What's in it |
|---|---|
| [**zephyr-packages**](https://github.com/ZephyrCloudIO/zephyr-packages) | Bundler plugins (`vite-plugin-zephyr`, `zephyr-rspack-plugin`, `zephyr-webpack-plugin`, …) and `create-zephyr-apps` |
| [**zephyr-examples**](https://github.com/ZephyrCloudIO/zephyr-examples) | Reference apps for each supported bundler and framework |
| [**skills**](https://github.com/ZephyrCloudIO/skills) | Agent Skills that teach coding agents to build and deploy on Zephyr |
| [**zephyr-preview-environment-action**](https://github.com/ZephyrCloudIO/zephyr-preview-environment-action) | GitHub Action that creates preview environments for pull requests |
| [**zephyr-documentation**](https://github.com/ZephyrCloudIO/zephyr-documentation) | Source for [docs.zephyr-cloud.io](https://docs.zephyr-cloud.io/). PRs welcome |

## The AI Platform

<img align="right" alt="The AI Platform" src="https://github.com/ZephyrCloudIO/.github/raw/main/profile/assets/tap-logomark-dark.svg" width="64">

[The AI Platform](https://theaiplatform.app/) is a desktop workspace for people and agents. It gives the whole org shared channels and context, routes each task to Claude, GPT or a local model, and tracks spend by person, team and feature. It runs against your repo, your machines and your keys.

[Download](https://theaiplatform.app/download) (macOS, Windows, Linux) · [Getting started](https://docs.theaiplatform.app/guide/getting-started/index.html) · [Marketplace](https://theaiplatform.app/marketplace) · [Pricing](https://theaiplatform.app/pricing) · [Changelog](https://theaiplatform.app/changelog) · [X](https://x.com/_TheAIPlatform)

## Contributing

Issues and PRs are welcome on any public repo. If you're new, start with [`zephyr-examples`](https://github.com/ZephyrCloudIO/zephyr-examples), and ask questions in [Discord](https://discord.gg/zephyrcloud).
