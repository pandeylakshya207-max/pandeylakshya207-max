# Lakshya Pandey

**Systems + AI/ML engineer.** I build things from scratch and fix real bugs.

Currently: B.Tech CSE (AI & ML) @ Dayananda Sagar University, Bengaluru (2025–2029) · AI Research Contributor @ MIT CSAIL (KellisLab/Mantis) · Co-founder @ EDUING

---

## Projects

### Systems

**[raftkv](https://github.com/pandeylakshya207-max/raftkv)** (Go). A linearizable key-value store on a from-scratch Raft implementation: leader election, log replication, snapshots, membership changes and read-index reads. Includes a linearizability checker that runs against a real 5-node cluster while leaders are killed.

**[servemesh](https://github.com/pandeylakshya207-max/servemesh)** (Go). A gateway for LLM serving with pluggable routing, health checking, retries and priority-aware admission control. On real llama.cpp replicas, prefix-aware routing cut p95 time-to-first-token by 71%. The results document also records where simulation and the real engine disagreed.

**[memdb](https://github.com/pandeylakshya207-max/memdb)** (Go). A relational database engine: B-Tree and hash indexes, a page cache, a write-ahead log with crash recovery, an iterator-model query engine, a SQL parser and a TCP server.

**[lumen](https://github.com/pandeylakshya207-max/lumen)** (Rust). A small statically typed language with a lexer, parser and type checker, and two backends, a bytecode VM and a tree-walking interpreter, that run the same programs.

### Machine learning systems

**[flux](https://github.com/pandeylakshya207-max/flux)** (Python, NumPy). A deep learning framework with scalar and tensor autograd, convolution via im2col, optimizers and a hand-written ONNX exporter. Trains an MLP to 97.3% on MNIST and a CNN to 77.2% on CIFAR-10.

**[mini-infer-engine](https://github.com/pandeylakshya207-max/mini-infer-engine)** (Python). An LLM inference engine built in phases. Continuous batching gave 3.08x the throughput of one-request-at-a-time decoding on a CPU; a paged KV cache and a preempting priority scheduler follow, with their trade-offs measured.

**[routellm-pro](https://github.com/pandeylakshya207-max/routellm-pro)** (Python). A router that sends each query to the cheapest capable model tier, with fallback and an A/B framework. It documents two negative results: a trained classifier that lost to the prompt-based one, and a cheaper routing policy rejected on answer quality. Deployed.

Also: [EventSphere](https://github.com/pandeylakshya207-max/EventSphere), [ai-money-mentor](https://github.com/pandeylakshya207-max/ai-money-mentor), [Credit-card-fraud-detector](https://github.com/pandeylakshya207-max/Credit-card-fraud-detector), [clean-city-app](https://github.com/pandeylakshya207-max/clean-city-app), [edgeguard](https://github.com/pandeylakshya207-max/edgeguard) and [PRANAVYU](https://github.com/pandeylakshya207-max/PRANAVYU).

---

## Open source

Merged:

- [keras-team/keras #23447](https://github.com/keras-team/keras/pull/23447): test coverage for the `tf_idf` output mode of `StringLookup`
- [pymc-devs/pymc #8393](https://github.com/pymc-devs/pymc/pull/8393): expanded the `RandomWalk` docstring
- [terrierteam/pyterrier_rag #70](https://github.com/terrierteam/pyterrier_rag/pull/70): added the AICL adaptive context selector

Open:

- [microsoft/vscode #336815](https://github.com/microsoft/vscode/pull/336815): preserve the replace string when the match has no cased characters
- [kubernetes/perf-tests #4427](https://github.com/kubernetes/perf-tests/pull/4427) and [#4428](https://github.com/kubernetes/perf-tests/pull/4428): unit tests for two clusterloader2 packages
- [pytorch/pytorch #194438](https://github.com/pytorch/pytorch/pull/194438): documentation of the adaptive pooling bin computation
- [grpc/grpc-go #9386](https://github.com/grpc/grpc-go/pull/9386): a README for the benchmark directory
- [mozilla/mozdownload #743](https://github.com/mozilla/mozdownload/pull/743): raise `NotSupportedError` for invalid application and platform combinations

---

## Research

**MIT CSAIL — KellisLab / Mantis platform** (2025–present)  
AI Research Contributor under Prof. Manolis Kellis. Building Education Vertical applications on the Mantis platform.

---

## Stack

**Languages:** Go, Rust, Python, C++, TypeScript

**Systems:** consensus, storage engines, query execution, bytecode VMs, serving gateways

**Machine learning:** autograd and training, LLM inference and routing, evaluation

---

## Contact

pandeylakshya207@gmail.com · [HuggingFace](https://huggingface.co/lakshyapandey-ml)
