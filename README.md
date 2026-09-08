# Hiya Trehan

Systems + compilers. I care about what happens between "the code compiles" and "the code is fast" — cache behavior, memory layout, IR transformations.

## Working on

- **[CacheWeaver](https://github.com/Heya28/CacheWeaver-LLVM)** — LLVM pass that detects Array-of-Structs access patterns and rewrites them to Struct-of-Arrays in IR. In progress: getting before/after cache-miss numbers with cachegrind/perf.
- **CXL-tier-aware cache replacement** — undergrad research for trace-driven analysis of cache replacement strategies for LLM inference workloads.

## Selected projects

| Project | What it does |
|---|---|
| [Trace-Driven Cache Simulator](https://github.com/Heya28/Cache-Simulator) | IBM's ARC replacement policy + miss classification (compulsory/capacity/conflict) across cache architectures, validated on millions of accesses |
| [Custom Unix Shell](https://github.com/Heya28/Custom-Unix-Shell-) | POSIX-based shell in C — fork/exec/wait, process group isolation, custom signal handling for background jobs |
| [Credit Spread Analyzer](https://github.com/Heya28/credit-spread-analyzer) | FRED API pipeline + Z-score signal engine + Plotly dashboard on 20 years of bond yield data |

## Stack

`C` · `C++` · `LLVM IR` · `Python` · `POSIX` · `cachegrind` / `perf`
