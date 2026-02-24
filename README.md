# Vacuum-Food-Keepbox

KeepBox is an open-source, repairable vacuum food container system designed to reduce food waste and cut reliance on single-use wraps and bags. The project publishes **editable CAD source files** (not just exports) so others can study, modify, manufacture, and share improved versions.

## What it is (current build)
- Modular vacuum container: box body + lid + defined gasket/seal path
- Off-the-shelf silicone one-way valve + pump module (AM395DPV)
- Key functional parts are **3D-printed food-grade PP5 (polypropylene)** (e.g., lid and pump housing; other printed parts depend on your build)

## Why vacuum
Lower-oxygen storage can help slow spoilage for chilled foods. The documentation includes clear guidance on safe handling and practical shelf-life limits.

## Key measurable targets (PDS summary)
- Vacuum level: ~−0.5 bar(g) (Δp ≈ 50 kPa)
- Retention: pressure rise ≤ 2 kPa in 10 min and ≤ 10 kPa in 24 h (vacuum-decay / pressure-rise test)
- Food contact approach: PP food-contact surfaces; no epoxy/adhesives used in food-contact structure
- Repairability: replaceable modules using basic tools; reassembly time recorded

## Repo contents
- CAD (editable sources + exports)
- BOM (parts + sourcing)
- Docs (assembly, maintenance, safety guidance)
- Tests (raw data, plots, pass/fail checks)
