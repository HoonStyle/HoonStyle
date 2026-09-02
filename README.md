# Hoon Lim (임훈)

**Technical PM — B2B Platforms | Manufacturing (EAP/CIM) · Healthcare (MDR/FDA) · AI Agent Systems**

15 years turning technical constraints into predictable systems — in semiconductor
fabs, regulated healthcare, and enterprise SaaS. Lately I build AI agent systems
end-to-end, solo, to prove the decisions I make as a PM.

## What I build

- **[legacy-spec-agent](https://github.com/HoonStyle/legacy-spec-agent)** —
  Claude Code / Codex plugin that reverse-generates citation-backed (`path:line`)
  specs from undocumented legacy code. LLM reasoning is separated from a
  deterministic verification engine (14 MCP tools, TypeScript) so the same input
  yields the same result. 86% citation coverage vs. 0% baseline. MIT.
- **[greplet](https://github.com/HoonStyle/greplet)** —
  Local hybrid search server (LanceDB vector + BM25, RRF-fused) that indexes
  several legacy codebases, the current code, and spec PDFs as workspaces and
  answers AI coding agents with `file :: symbol (L-range)` locations, not
  summaries. Roslyn member-level / PdfPig page-level chunking, hash-manifest
  incremental indexing so deletions actually leave the index, exposed as MCP +
  Claude Code / Codex skills. Built to sit in front of legacy-spec-agent
  (spec) and Serena (structure). MIT.
- **[OhMoney-portfolio](https://github.com/HoonStyle/OhMoney-portfolio)** —
  Architecture and product-decision record of a 20-agent LLM orchestration
  system I planned, built, and operated alone: LangGraph control flow,
  JSON-Schema tool calling, A/B/C auto-grading, EV-based North Star metric,
  5-stage media pipeline with per-stage retry/DLQ.

## Where I come from

- **Semiconductor / Display**: MES–Equipment Integration (EAP) for AMAT CVD·PVD
  and Array Test equipment — SECS/GEM·HSMS, 4+ years on fab floors
- **Regulated Healthcare**: PO for a global healthcare platform — offline-first
  architecture, 99.9% data integrity under battery/connectivity constraints,
  MDR/FDA validation
- **B2B SaaS (0→1)**: Co-founded a manufacturing operations platform — 30+ sites,
  offline-first + eventual consistency

**Now**: IT System Architect — leading legacy system refactoring with
AI-assisted documentation and audit-trail workflows.

📄 Portfolio: [hoonlim.short.gy/portfolio](https://hoonlim.short.gy/portfolio) ·
💼 [LinkedIn](https://linkedin.com/in/hoonlim)



