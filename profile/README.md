# AuditScan — Proof, not promises.

Deterministic software verification. Zero ML/LLM. Offline-first.

Findings ship with `file:line` evidence and counterfactuals — what broke, who calls it, how to fix it.

**Start here:**
- `breakproof` [coming next] — PR merge gate: FAIL only on removed contracts with caller proof. No `openapi.yaml` needed.
- AuditScan [commercial] — service graph, SOC 2 / ISO 27001 / PCI / HIPAA evidence, history, M&A dossier from frozen scans.

```bash
pipx install breakproof
breakproof diff --base main --head HEAD
