<p align="center">
  <a href="https://haarness.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
      <img alt="Haarness — Power your work with the best AI harness." src="assets/banner-light.png" width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://haarness.ai"><b>haarness.ai</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://haarness.ai/docs"><b>Docs</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://haarness.ai/download"><b>Download</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://haarness.ai/pricing"><b>Pricing</b></a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="mailto:admin@haarness.ai"><b>admin@haarness.ai</b></a>
</p>

<p align="center">
  <img alt="Runs on macOS, Linux and Windows" src="https://img.shields.io/badge/macOS_·_Linux_·_Windows-dba273?style=flat-square&labelColor=232120&label=runs%20on">
  <img alt="17 interface languages" src="https://img.shields.io/badge/languages-17-eae5dd?style=flat-square&labelColor=232120">
</p>

**Haarness is the harness around the model** — the tools, memory and guard rails that let AI do real
work and show you every step, on your computer, in the cloud and inside your own apps. Describe the
outcome in your own words; Haarness plans the steps, uses the right tools and checks its own work.

### One assistant. Every screen you use.

| Where | What you get |
| --- | --- |
| **Terminal** | A quiet, keyboard-first terminal UI, and a CLI for scripts and CI |
| **Desktop** | macOS, Windows and Linux, with diff review, a file editor, terminals and a built-in browser |
| **Your editor** | Through the Agent Client Protocol, with the same chats everywhere |
| **Your Chrome** | Haarness for Chrome lets agents work in your own signed-in Chrome — every site asks first |
| **Cloud** | Sessions that keep going when you close the lid, schedules, one account for every model |
| **Your product** | A versioned server API with TypeScript and Python SDKs |
| **Your phone** | Haarness for iPhone and Android, coming soon: follow every chat and approve from the Lock Screen or the notification shade |

### Install on macOS, Linux and Windows

One command installs the terminal app and Desktop, and checks every download's SHA-256 first:

```sh
curl -fsSL https://haarness.ai/install.sh | sh                      # macOS and Linux
curl -fsSL https://haarness.ai/install.sh | sh -s -- --no-desktop   # without Desktop
```

```powershell
irm https://haarness.ai/install.ps1 | iex                                # Windows, in PowerShell
$env:HAARNESS_NO_DESKTOP='1'; irm https://haarness.ai/install.ps1 | iex  # without Desktop
```

Or download it from [haarness.ai/download](https://haarness.ai/download): `.dmg` or `.zip` for macOS,
`.AppImage` or `.deb` for Linux and `.exe` for Windows, each for Intel/AMD and ARM.

### Capable, and on your terms

- **You decide what it may do.** Each chat is in Review, where Haarness asks before anything sensitive, or
  Auto, where a reviewer model answers routine requests and leaves the rest to you. Your rules are plain
  text you can read.
- **See every step.** Every file it read, every command it ran and every change it made, in order, with
  what it cost.
- **Any model.** Sign in with your ChatGPT, GitHub Copilot or xAI subscription, bring your own keys for
  OpenAI, Anthropic, Gemini, OpenRouter and dozens more, run models locally with Ollama or LM Studio — or
  use one Haarness account for all of them.

### Open at the core. Hosted when you want it.

| Project | What it is | License |
| --- | --- | --- |
| **[haarness](https://github.com/haarness/haarness)** | The agent, terminal app, Desktop, server, SDKs and Haarness for Chrome — free on your computer | Apache 2.0 |
| **[haarness-router](https://github.com/haarness/haarness-router)** | A stateless, OpenAI-compatible router for every model provider, to host yourself | MIT |

[Haarness Cloud](https://haarness.ai/product/cloud) is the hosted service at haarness.ai. The phone apps for
[iPhone and iPad](https://haarness.ai/product/ios) and [Android](https://haarness.ai/product/android) are coming soon.
Questions? Write to us at **admin@haarness.ai**.

<sub>The Haarness name and logo are trademarks of the Haarness project.</sub>
