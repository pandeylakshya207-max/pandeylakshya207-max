# Lakshya Pandey

**Systems + AI/ML engineer.** I build things from scratch and fix real bugs.

Currently: B.Tech CSE (AI & ML) @ Dayananda Sagar University, Bengaluru (2025–2029) · AI Research Contributor @ MIT CSAIL (KellisLab/Mantis) · Co-founder @ EDUING

---

## Projects

### [raftkv](https://github.com/pandeylakshya207-max/raftkv) — Distributed KV Store · Go
Production-grade key-value store built on a from-scratch Raft consensus implementation.
Leader election, log replication, snapshotting, membership changes, linearizable reads.
Includes a Jepsen-style linearizability checker (Wing-Gong algorithm) and a binary RPC transport (gob, 52% smaller wire format, 2.1× faster than HTTP/JSON).
**9 real bugs found and fixed** across the build via deep integration testing and the race detector.
`go test ./... -race` — all clean.

### [lumen](https://github.com/pandeylakshya207-max/lumen) — Compiled Language · Rust
Statically-typed language built from scratch: lexer → recursive-descent parser → type checker → bytecode compiler → stack VM, plus a second tree-walking interpreter backend for honest benchmarking.
VM is **5× faster** than the tree-walking interpreter on loop-heavy programs (direct slot indexing vs scope-chain HashMap walks).
203 tests. Both backends execute the same programs identically.

### [RouteLLM-Pro](https://github.com/pandeylakshya207-max/routellm-pro) — LLM Router · Python
Multi-tier LLM routing system with a trained cost/quality classifier, A/B testing framework, Redis logging, and resilience features. Routes queries between Groq and Gemini based on complexity. Deployed.

### [pyterrier_rag](https://github.com/terrierteam/pyterrier_rag) — Open Source Contribution · Python
Contribution to the University of Glasgow Terrier Team's RAG retrieval library. PR reviewed and merged by Prof. Craig Macdonald.

---

## Research

**MIT CSAIL — KellisLab / Mantis platform** (2025–present)  
AI Research Contributor under Prof. Manolis Kellis. Building Education Vertical applications on the Mantis platform.

---

## Stack

**Languages:** Go · Rust · Python · C++ · TypeScript  
**Systems:** Raft consensus · distributed KV stores · bytecode VMs · compilers  
**AI/ML:** LLM routing · RAG · multi-agent systems · cost-aware inference

---

## Contact

pandeylakshya207@gmail.com · [HuggingFace](https://huggingface.co/lakshyapandey-ml)
