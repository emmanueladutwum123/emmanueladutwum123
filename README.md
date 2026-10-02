## Emmanuel Adutwum

Software engineer working on systems: consensus, low-latency C++, query execution and compilers.
I build things from first principles, benchmark them, and write down where they break.
Every number on this page comes from a benchmark or test committed in the linked repo.

[Website](https://emmanueladutwum123.github.io) · [LinkedIn](https://www.linkedin.com/in/emmanuel-adutwum/)

### Selected systems

| Project | What it is | Measured |
|:--|:--|:--|
| [**cascade**](https://github.com/emmanueladutwum123/cascade) | Market-data ticker plant in C++20: UDP multicast feed handling with gap recovery, lock-free book building, conflating fan-out | 1.54 µs p50 wire-to-wire at 250k msg/s; 117 tests |
| [**quorumkv**](https://github.com/emmanueladutwum123/quorumkv) | Strongly consistent KV store on a from-scratch Raft in Go: crash-safe WAL, joint-consensus membership, deterministic simulator + linearizability checker | 60 seeded fault scenarios; 188 µs linearizable read |
| [**quarry**](https://github.com/emmanueladutwum123/quarry) | Columnar query engine in C++20: encoded storage with zone-map pruning, vectorized push-based execution, hash joins | 88.6% of chunks skipped on clustered data; 9.4M rows/s join probe |
| [**vellum**](https://github.com/emmanueladutwum123/vellum) | Multiplayer scene-graph engine for a collaborative design tool: server-sequenced LWW registers, fractional indexing | 500 adversarial seeds converge over 320k edits |
| [**mlir-tensor-opt**](https://github.com/emmanueladutwum123/mlir-tensor-opt) | MLIR dialect with constant-folding, simplification and fusion passes, lowered through linalg/affine to LLVM | Fusion 1.91× on an 8-op elementwise chain |
| [**skewdesk**](https://github.com/emmanueladutwum123/skewdesk) | Index-options market-making engine in C++20: arbitrage-free vol surface fitting, portfolio Greeks, risk-aware quoting | 110 tests across gcc/clang |
| [**tapebench**](https://github.com/emmanueladutwum123/tapebench) | Multi-threaded backtesting engine in C++20: CRTP strategy dispatch, zero-copy mmap tick tape, parallel parameter grids | 822M ticks/s; 3.8× parallel speedup, byte-identical results |
| [**sextant**](https://github.com/emmanueladutwum123/sextant) | Natural-language-to-SQL agent: schema linking, semantic layer, AST policy guard, eval harness with bootstrap CIs | Schema-linking recall@3 83.6% → 98.2% |

### Other work

- [**cv-resnet-pipeline**](https://github.com/emmanueladutwum123/cv-resnet-pipeline) — PyTorch → ONNX → C++ ONNX Runtime serving; 4.03 ms p50, numerical parity to 8e-7
- [**signal-lab**](https://github.com/emmanueladutwum123/signal-lab) — signal research pipeline whose result is what it rejected: 208 candidates in, 1 survives realistic costs
- [**activation-study**](https://github.com/emmanueladutwum123/activation-study) — retention study on MovieLens 10M, and why the obvious A/B test is infeasible
- [**neural-net-cpp**](https://github.com/emmanueladutwum123/neural-net-cpp) — neural network library from scratch in C++17; 98.5% MNIST test accuracy
- [**ocaml-order-book**](https://github.com/emmanueladutwum123/ocaml-order-book) — price-time-priority matching engine in OCaml

### How I work

- **Measure before claiming.** In quarry, a benchmark showed dictionary encoding at 33 MB/s; hashing distinct values once instead of a per-row `std::map` insert took it to 519 MB/s.
- **Test under failure, not just in isolation.** cascade's unit tests passed while a live run lost 39,904 messages to an undersized reorder window; the fix took that to zero. quorumkv's consensus core runs under a seeded scheduler so every fault schedule replays exactly.
- **Write down the trade-offs.** The larger projects keep design docs covering what was chosen, what was rejected, and what is deliberately out of scope.

**Languages:** C++20 · Go · Python · TypeScript · OCaml  
**Tools:** CMake, MLIR/LLVM, sanitizers (ASan/UBSan/TSan), Docker, GitHub Actions, PyTorch, DuckDB
