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

## Compression

Assets were compressed with the `asset-compressor` skill.

| Asset | Original | Compressed | Reduction |
|---|---|---|---|
| Slide deck (PDF) | 17.0 MB | 2.2 MB | 87.3% |
| Slide deck (PPTX) | 18.4 MB | 8.3 MB | 54.8% |
| Infographic (WebP) | 4.4 MB | 261 KB | 94.2% |
| Infographic (PNG, 50%) | 4.4 MB | 1.2 MB | 73.7% |

PDF via Ghostscript `/ebook` (150 dpi). PPTX via 256-color adaptive palette on `ppt/media/*`
at original dimensions, re-zipped at ZIP level 9 — the deck is image-per-slide, so the PDF is
the clean viewing copy and the PPTX the editable one. Infographic as full-resolution WebP
(quality 70, 2752×1536) plus a 50%-scale PNG (quality 80, 1376×768) fallback.

Provenance for every artifact is recorded in [manifest.json](manifest.json).

## Regenerating

```bash
notebooklm download infographic AI-Coding-Agent-Workflow-Comparison.png \
  -a 4f18a952-91c8-4bd8-805c-896057d90c56 -n 3dd2f0fe-4288-4dbf-8b31-d8e13fec494f
notebooklm download slide-deck Architecting-Agentic-Workflows.pdf \
  -a 678c9b27-11c4-41c5-a059-df339bc2c515 -n 3dd2f0fe-4288-4dbf-8b31-d8e13fec494f
```

The notebook also holds a video artifact, *Agent Skills: Senior Scaffolding for AI Engineering*,
still generating at the time of the last export.
