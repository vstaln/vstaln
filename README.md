<div align="center">
  <img alt="Gray" src="assets/gray-logo.svg" width="108" />

# vstaln

[gray.alignment.id](https://gray.alignment.id) · [gray on GitHub](https://github.com/vstaln/gray) · [vstal.in](https://vstal.in/) · [LinkedIn](https://www.linkedin.com/in/vstaln/)

</div>

<div align="center">
  <img alt="Carina Nebula — cosmic cliffs" src="assets/space/carina-dither.png" width="100%" />
</div>

**[vstaln/gray](https://github.com/vstaln/gray)**

<div align="center">
  <a href="https://github.com/vstaln/gray">
    <img alt="gray building an app in the terminal" src="assets/gray-demo.gif" width="100%" />
  </a>

`curl -fsSL https://gray.alignment.id/install.sh | sh`

[Website](https://gray.alignment.id) · [Docs](https://github.com/vstaln/gray/tree/main/docs) · [Releases](https://github.com/vstaln/gray/releases)

</div>

- one binary, musl-static. lands you in a REPL.
- one tool by default: `bash`. opt into the rest.
- sessions that survive. JSONL, branchable, resumable.
- context that compacts itself before you hit the wall.
- lives where you do: Telegram / Discord / Slack gateway + cron.
- extend it: `SKILL.md`, stdio plugins, or `/acp` to become claude / codex / opencode.

### other experiments

**[noslop](https://github.com/vstaln/noslop) — an agent skill for prose that doesn't read like template AI.**
Works like a linter, not a style guide: drafts plainly, then scans for slop tells (glue words, sermon closes, dash spam) *and* over-application tells (the new uniform telegraphic slop anti-slop rules create). Ships with `SKILL.md` for Claude Code, a `voice` hard-fail check, and evals with side-by-side drafts.
Trigger: `noslop` · "write human"

**[isthisaislop](https://github.com/vstaln/isthisaislop) — local, checkable slop detector.**
Paste text → get *why* (quoted spans + pattern names), not a `% AI` score. Two lanes: deterministic regex (~40 patterns × 4 lanes) + `matches_ai_pile` resemblance calibrated at 1% FPR. Runs on-device (ONNX INT8, CPU). `pip install slopdet`.
No authorship claims, every hit carries a verbatim quote.

**[CalmFeed](https://github.com/vstaln/CalmFeed) — a browser extension that makes X less miserable for builders.**
Asks why you're opening X, blurs what you asked it to filter (hostility, doom, rage bait — all opt-in), kicks you off when the timer hits zero. Visits stay in local storage, no servers. Manifest V3, no bundler. Load unpacked, paste a free Gemini key, start a session.

<div align="center">
  <img alt="Blue Marble" src="assets/space/bluemarble-dither.png" width="31%" />
  <img alt="Jupiter storm" src="assets/space/jupiter-dither.png" width="31%" />
  <img alt="Saturn" src="assets/space/saturn-dither.png" width="31%" />
  <p>start small. extend anything.</p>
</div>
