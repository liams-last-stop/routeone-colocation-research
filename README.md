# Deterministic Colocation: Eliminating Digital Muda in Modern Execution Runtimes

**Authors:**
A. S. Hotta
Institute for Autonomous Cybernetics &amp; Applied Monoliths
`hotta@routeone-research.org`

**Slug:** `deterministic-colocation-lemma`
**Venue:** arXiv (cs.DC, cs.SE) — determination in progress
**Version:** v0.1-public-draft (2026-11-15)

## What this repository holds
1. The paper text, `paper/Deterministic_Colocation_Eliminating_Digital_Muda.md`
2. The arXiv LaTeX source, `arxiv/deterministic-colocation-eliminating-digital-muda.tex`
3. Supporting benchmark data, `benchmark/`.

This repository is the public prior-art anchor for the (pending) OASIS TC charter:
references to an external document must be publicly available (OASIS TC Process §1.2).
This is the canonical public location.

## Reproducibility
The microservice baseline and RouteOne-S monolith were benchmarked on identical
AMD EPYC 7763 hardware (64 cores, 256 GiB RAM, NVMe). Note: your mileage may
vary; the response-time story generalises, the absolute throughput numbers do
not.

## License
[BSD 3-Clause](./LICENSE); data under [CC-BY-4.0](./benchmark/LICENSE-DATA).
