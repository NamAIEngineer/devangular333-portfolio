# NamAIEngineer portfolio

Static portfolio for **NamAIEngineer**, an AI Product Engineer building evidence-led developer tools, DESIGN:OS product work, and provider-neutral agent infrastructure.

## What is here

- **Code2Flow Review Pack** — a local review workflow that compares labeled graph revisions, links source evidence, records reviewer notes/status, and exports JSON. Start with the [interactive demo](review-pack-demo.html), [case study](https://github.com/NamAIEngineer/design-os-code/blob/master/docs/case-study.md), or [v0.5.3 release](https://github.com/NamAIEngineer/design-os-code/releases/tag/v0.5.3-devangular333).
- **DESIGN:OS Studio** — a public NamAIEngineer repository in the DESIGN:OS ecosystem. The [repository](https://github.com/NamAIEngineer/design-os-studio) and its license/notices define the fork boundary and upstream project context.
- **Pedagogy / Agent Teacher** — local Vietnamese fraction-teaching rehearsal with authored coaching, replay, and Markdown export. See the [repository](https://github.com/NamAIEngineer/design-os-pedagogy) and [case study](https://github.com/NamAIEngineer/design-os-pedagogy/blob/main/docs/case-study.md).
- **System Agentic AI** — provider-neutral contracts, provider discovery, bounded execution, and verification. Read the [framework README](https://github.com/NamAIEngineer/system-agentic-AI).
- **InkOS × PrintFilm Lab** — file-based Markdown/JSON interoperability with metadata and stale-state guards.

## Evidence and limits

Assets are captured from released local flows. The Review Pack demo uses labeled synthetic CRM fixtures. Its relation badges are deterministic focus-term matches, not semantic impact analysis. A parser-visible graph edge is not proof that runtime behavior is correct. Agent Teacher is an authored rehearsal, not a teaching certification. Live browser behavior, upstream runtime behavior, and environment parity require separate verification.

The page contains no runtime data, credentials, analytics, or external API calls. The System Agentic introduction uses a real sanitized provider inventory and decision-plane readback from public commit `7b7168a`; that advisory result did not authorize or submit a task. Connector geometry and policy panels are labeled illustrative in the film. The hosted videos point to public GitHub release assets; the local interactive demo runs in the browser and stores review notes in local storage only.

## System Agentic introduction media

- [Watch the 54-second MP4 release](https://github.com/NamAIEngineer/system-agentic-AI/releases/download/intro-video-2026-11-11/system-agentic-intro-1080p.mp4) or [view the lightweight GIF preview](assets/system-agentic-intro-preview.gif).
- [Read captions](assets/system-agentic-intro.vtt), [transcript](https://github.com/NamAIEngineer/system-agentic-AI/blob/main/media/transcript.md), and [reproducible source](https://github.com/NamAIEngineer/system-agentic-AI/tree/main/media).
- The video is silent by design: readable English on-screen copy, no autoplay audio, and controls supplied by the portfolio player.

## Run locally

```sh
python3 -m http.server 4173
open http://127.0.0.1:4173/
```

Live page: <https://namaiengineer.github.io/devangular333-portfolio/>

## Scope and attribution

This page describes NamAIEngineer work and links to source repositories. It does not claim original authorship of upstream projects. Each repository's `LICENSE`, `NOTICE`, and upstream documentation remain authoritative; preserve those files when redistributing code or assets.
