# Agent Skills: Senior Scaffolding for AI Engineering

Generated Studio artifacts from the Gemini Notebook
[Agent Skills: Senior Scaffolding for AI Engineering](https://notebook.google.com/notebook/3dd2f0fe-4288-4dbf-8b31-d8e13fec494f).

The notebook researches how production teams bolt a senior-engineer review layer back onto
AI coding agents — comparing Addy Osmani's Agent Skills, Matt Pocock's Skills, Jesse Vincent's
Superpowers, and the VS Code Plan Agent.

## Meeting Materials

- 🖼 [ai-coding-agent-workflow-comparison.webp](infographic/ai-coding-agent-workflow-comparison.webp) 261 KB — Four-column matrix of *"The Big Four: AI Coding Agent Workflows"*: Addy Osmani's Agent Skills (full SDLC), Matt Pocock's Skills (alignment-first), Jesse Vincent's Superpowers (autonomous pipeline), and the VS Code Plan Agent (integrated blueprinting), scored row-by-row on framework philosophy, signature feature/best use case, and architectural trade-offs, plotted on a composable-flexible ↔ opinionated-structured spectrum.
- 🖼 [ai-coding-agent-workflow-comparison.png](infographic/ai-coding-agent-workflow-comparison.png) 1.2 MB — Same infographic at 50% scale, as a PNG fallback for renderers without WebP support.
- 📊 [architecting-agentic-workflows.pdf](slides/architecting-agentic-workflows.pdf) 2.2 MB — 15-slide deck *"Beyond Vibe Coding: Architecting Agentic Workflows for Production Engineering"*: why the agent's default path is the shortest path to technical debt, then one section per philosophy (VS Code Plan's native draftsman and handoff loop, Matt Pocock's grill-with-docs interrogator funnel, Obra's Superpowers sub-agent-driven assembly line, Addy Osmani's anti-rationalization governance board), closing on the workflow diagnostic matrix and the claim that you choose a philosophy, not a prompt.
- 📊 [architecting-agentic-workflows.pptx](slides/architecting-agentic-workflows.pptx) 8.3 MB — Editable source of the deck.
- 🎬 [choose-your-ai-copilot.mp4](videos/choose-your-ai-copilot.mp4) 6m 24s · 21MB — Studio video *"Choose Your AI Co-Pilot: Which Coding Workflow Fits Your Stack?"*: walks through matching each workflow philosophy (Osmani's governance board, Pocock's interrogation, Vincent's assembly line, VS Code's native plan agent) to your stack and risk tolerance.

## Compression

Assets were compressed with the `asset-compressor` skill.

| Asset | Original | Compressed | Reduction |
|---|---|---|---|
| Slide deck (PDF) | 17.0 MB | 2.2 MB | 87.3% |
| Slide deck (PPTX) | 18.4 MB | 8.3 MB | 54.8% |
| Infographic (WebP) | 4.4 MB | 261 KB | 94.2% |
| Infographic (PNG, 50%) | 4.4 MB | 1.2 MB | 73.7% |
| Video (MP4) | 54.2 MB | 20.6 MB | 62.0% |

Video via FFmpeg x264/AAC scaled to a maximum of 720p. PDF via Ghostscript `/ebook` (150 dpi). PPTX via 256-color adaptive palette on `ppt/media/*`
at original dimensions, re-zipped at ZIP level 9 — the deck is image-per-slide, so the PDF is
the clean viewing copy and the PPTX the editable one. Infographic as full-resolution WebP
(quality 70, 2752×1536) plus a 50%-scale PNG (quality 80, 1376×768) fallback.

Provenance for every artifact is recorded in [manifest.json](manifest.json).

## Studio Notes

- 📝 [non-obvious-insights.md](non-obvious-insights.md) - five non-obvious insights (frameworks as psychological prompt-hacks, skills as a "smart zone" context budget, AI-accelerated entropy, Markdown as the control plane, verification bandwidth as the bottleneck) plus three tensions: TDD fundamentalism vs refactoring, autonomy vs developer agency, rigor vs token inflation.
- 📝 [essential-questions.md](essential-questions.md) - the essential questions distilled from the notebook's research.

## Regenerating

Point your own notebook at the research sources listed in [sources.md](sources.md) - add them, then generate the artifacts you want with `notebooklm generate`.
