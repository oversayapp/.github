# Oversay

**Your notes, on screen, while you talk.**

## What it does

Oversay puts a small card in front of your call or your slides, near the camera: what to say now, and how long you have. Write your cards in Markdown, or ask your AI to, then press Show and keep to time.

It is for anyone giving a talk or running a meeting who wants to finish on time. For Mac and Windows. Open source, and no account needed.

## How it fits together

<img src="https://raw.githubusercontent.com/oversayapp/.github/main/profile/images/architecture.svg" alt="Map of how Oversay fits together. In the middle are the parts we wrote: the Oversay skill, the desktop app for Mac and Windows, the oversay.app site, the Oversay API and the iPhone app. Around them are the services they connect to: AI assistants and Hugging Face on the left, AWS Cognito with Google and Apple sign-in above, Neon Postgres on the right, and GitHub, Cloudflare, App Store Connect and Homebrew below." width="100%">

## Key features

- Decks of timed Markdown cards, grouped into workspaces
- An always-on-top overlay with Card and Agenda views
- Records each run, so you can review where the time went
- On-device transcription: nothing is sent anywhere
- Ask Claude Code, Codex, Claude or ChatGPT to write the deck for you
- Open source (GPL-3.0). Your decks are plain files on your computer

## Install

```bash
brew install oversayapp/tap/oversay
```

Or download Oversay for Mac or Windows from [oversay.app](https://oversay.app).

---

Built by [John Ryan](https://johnryan.io/) · [GitHub](https://github.com/jnyryan)
