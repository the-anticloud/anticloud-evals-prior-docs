# Build and Test

**Project:** `EVALS`
**Upstream:** https://github.com/openai/evals
**License:** MIT

## Quick Start

```bash
git clone https://github.com/openai/evals
cd evals
pip install -r requirements-anticloud.txt
python anticloud_main.py --offline --pax-local
```

## Anticloud Improvements Applied

1. PAX L5 Narrow L2 General 27B local research assistant for literature review and synthesis
2. AIOSS cryptographic provenance chain for all datasets and results
3. AES-256 encryption for unpublished research data and pre-prints
4. Single-binary research tool deployment — no IT admin required
5. Offline citation and reference management replacing cloud services
6. Zero-telemetry: removes all upstream analytics
7. Reproducibility ledger: immutable record of software versions, seeds, hardware
8. GPU/CPU equalizer: runs on office laptop CPU or HPC GPU cluster identically

## Benchmark Targets

| Metric | Target |
| --- | --- |
| Latency | Primary inference task: <5s on CPU, <1s on GPU |
| Throughput | Batch processing: >100 items/hour on single CPU server |
| Memory | <8GB RAM for standard deployment |
| Accuracy | Task-specific accuracy within 5% of cloud-API baseline |

## Build Status

Not yet measured. Run verified build and record actual figures above.
