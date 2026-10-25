# Marcus Sterling (`@MonoRep`)

```text
 ┌────────────────────────────────────────────────────────────────────────┐
 │   P R I N C I P A L   B U I L D   &   M O N O R E P   A R C H I T E C T    │
 │   Distributed Graphs • Hermetic Compilers • Content-Addressable Storage│
 └────────────────────────────────────────────────────────────────────────┘
```

> **Systems Architecture & Developer Tooling**  
> Cambridge, MA · 16+ Years Experience · MIT EECS '09 Alum  

---

### Focus & Engineering Directives

- **Large-Scale Monorepo Topology**: Graph decomposition, strict package boundaries, topological sort optimizers, and automated boundary enforcement for multi-million-line codebases.
- **Hermetic Build Systems & Remote Execution**: Content-addressable storage (CAS), Action Cache protocols, deterministic compilation sandboxes, and distributed task runners.
- **Compiler Toolchains & CLI Performance**: Deep performance profiling of Rust (`cargo`), C++ (`clang`/`gcc`), and Go compilers; sub-millisecond CLI invocation runtimes and zero-cost abstractions.
- **Predictive Test Impact Analysis (TIA)**: Automated target pruning, reverse dependency change calculation, and flake-resistant distributed test runners.

---

### Core Technical Arsenal

| Category | Primary Technologies & Systems |
| :--- | :--- |
| **Build Systems** | Bazel, Buck2, Turborepo, Pants, Cargo, Ninja, CMake |
| **Languages** | Rust, Modern C++ (C++20/23), Go, Python, TypeScript |
| **Infrastructure & Kernel** | Linux cgroups v2, Namespaces, eBPF tracing, Docker, Kubernetes |
| **Storage & Caching** | S3-compatible CAS, Redis, LMDB, SQLite, gRPC / Protobuf |
| **Tooling & Profiling** | `perf`, `flamegraph`, `hyperfine`, Clangd, LLVM IR, Valgrind |

---

### Systems Philosophy

1. **Deterministic Reproducibility**: *A build that cannot be bit-for-bit reproduced across air-gapped workstations is a fragile state, not a reliable toolchain.*
2. **Correctness Before Velocity**: *Speed without cache invalidation correctness is simply the rapid distribution of subtle bugs.*
3. **Ergonomic Boundaries**: *Monorepos thrive when module contracts are strictly declared, machine-checked, and isolated by default.*

---

<p align="center">
  <sub>Open-source systems architecture · Distributed developer toolchains · Zero-drift codebases</sub>
</p>
