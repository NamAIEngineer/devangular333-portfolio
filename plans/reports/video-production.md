# System Agentic AI introduction video report

## Acceptance IDs

A7, A8, A9. Constraints C2, C3, C5. Checks V4, V5, V6.

## Rendered artifact

- `media/out/system-agentic-intro-1080p.mp4`
- 54.000 seconds, 1920×1080, 60 fps, H.264 High, `yuv420p`, 2.8 MB before release upload.
- Silent by design. English on-screen copy and a WebVTT captions track ship beside the MP4; portfolio controls do not autoplay audio.
- `assets/system-agentic-intro-poster.png` is the static poster; `assets/system-agentic-intro-preview.gif` is the 960px-wide lightweight preview.
- Source composition: `media/src/system-agentic-intro.tsx`; reproducible renderer: `media/render-system-agentic.mjs`; pinned runtime manifest: `media/package.json`.

## Evidence grounding

- Provider inventory comes from a fresh `python3 scripts/system-agentic providers` readback on public commit `7b7168add7bdcad9dc09a99a4d7386d4c705c89e`.
- Decision output comes from a fresh safe prompt readback: `DISPATCH`, module `none`, execution class `READ_ONLY`, confidence `0.8357`, `execution_authorized: false`, route lane `HOST`.
- `system-agentic-AI-public/media/evidence/` stores sanitized JSON readbacks. Credentials, account paths, cookies, and personal machine identifiers are omitted.
- Connector lines, cards, and panel geometry are explicitly labeled illustrative in the film and transcript. No unsupported provider, success, metric, or runtime parity claim is made.

## Replacement and preservation

- The profile README hero now uses the System Agentic preview linked to the full release MP4; Review Pack preview remains in its own project section.
- Portfolio introduces System Agentic as its first media section and retains Review Pack as a separate project player.
- Full MP4 stays out of Git history and is attached to the authorized `system-agentic-AI` release; source, poster, preview, captions, transcript, and evidence remain reviewable in the repository.
