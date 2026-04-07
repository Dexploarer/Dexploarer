<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=2500&pause=800&color=39FF14&center=true&vCenter=true&width=900&height=70&lines=dEXploarer;%5B+building+in+the+dark+%5D;TypeScript+%E2%80%A2+Go+%E2%80%A2+AI+Agents+%E2%80%A2+Onchain;terminally+online%2C+shipping+anyway." alt="Typing SVG" />

<br/>

[![X](https://img.shields.io/badge/@dEXploarer-%23000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/dEXploarer)
[![GitHub](https://img.shields.io/badge/Dexploarer-%23181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Dexploarer)
[![Blind Vibe](https://img.shields.io/badge/Blind%20Vibe-%23111111?style=for-the-badge&logoColor=white)](https://github.com/Blind-Vibe)
[![milady-ai](https://img.shields.io/badge/milady--ai-%23f69b47?style=for-the-badge&logoColor=white)](https://github.com/milady-ai)
[![LunchTable](https://img.shields.io/badge/LunchTable--TCG-%23FFD700?style=for-the-badge&logoColor=black)](https://github.com/LunchTable-TCG)
[![Ghostspeak](https://img.shields.io/badge/Ghostspeak-%2338A2BE2?style=for-the-badge&logoColor=white)](https://github.com/Ghostspeak)

</div>

---

```bash
$ whoami
> dEXploarer

$ cat /etc/dexploarer
handle  : dEXploarer
status  : 💾 locked in
studio  : Prompt or Die
stack   : TypeScript • Go • Rust • AI Agents • Onchain Systems
vibe    : terminally online, building in the dark
orgs    : @milady-ai @LunchTable-TCG @Ghostspeak @Prompt-or-Die-Labs
contribs: 3,920 contributions in the last year
repos   : 143 repositories • 39 stars earned
```

---

## ⚡ GitHub Stats

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Dexploarer&theme=dark&hide_border=true&background=0D1117&ring=39FF14&fire=39FF14&currStreakLabel=39FF14)](https://git.io/streak-stats)

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Dexploarer&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=39FF14&icon_color=39FF14&hide=contribs)](https://github.com/Dexploarer)

</div>

---

## 🗂️ Original Projects — Built From Scratch

```bash
$ ls ~/projects --original --best-only
```

| Repo | Description | Stack | Stars |
|------|-------------|-------|-------|
| [claudius-skills](https://github.com/Dexploarer/claudius-skills) | Production-ready Claude Code extensibility — 87 skills, 86 commands, 50 agents, 36 hooks across 10 installable plugin kits | TypeScript | ⭐ 5 |
| [plugin-electrobun-dev](https://github.com/Dexploarer/plugin-electrobun-dev) | Full Claude Code plugin for Electrobun desktop apps — 15 skills, 13 commands, 11 agents, 8-stage SDLC pipeline + WebGPU | TypeScript | ⭐ 3 |
| [dizzy-overlay](https://github.com/Dexploarer/dizzy-overlay) | Native Go always-on-top overlay — enhances Claude prompts with live git context + Claude memory auto-detection | Go | ⭐ 1 |
| [trust-dashboard](https://github.com/Dexploarer/trust-dashboard) | Contributor trust scoring + elizaOS ecosystem graph — 8-factor scoring, live visualization | TypeScript | ⭐ 1 |
| [dizzy-dashboard](https://github.com/Dexploarer/dizzy-dashboard) | Control plane for Dizzy AI agent on DigitalOcean — Vite + Electrobun desktop app | TypeScript | ⭐ 1 |
| [LunchTable-TTG](https://github.com/LunchTable-TCG) | AI-native tabletop gaming platform — PixiJS live table, Convex backend, BYOK AI vault, agent API | TypeScript | MIT |
| [milady-poke-adapter](https://github.com/Dexploarer/milady-poke-adapter) | ElizaOS plugin adapter — exposes Poke's email, calendar, and draft capabilities as agent actions + providers | TypeScript | — |
| [prompt-or-die-tech-ui](https://github.com/Dexploarer/prompt-or-die-tech-ui) | Cyberpunk + agentic UI library — strictly typed React + Tailwind, production-ready components | TypeScript | MIT |

---

## 🧠 Tech Stack

```bash
$ lsmod --tech
```

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=flat-square&logo=rust&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB)
![Three.js](https://img.shields.io/badge/Three.js-black?style=flat-square&logo=three.js&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=flat-square&logo=bun&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-%2324C8D8.svg?style=flat-square&logo=tauri&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-%239945FF.svg?style=flat-square&logo=solana&logoColor=white)
![ElizaOS](https://img.shields.io/badge/elizaOS-black?style=flat-square&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Code-orange?style=flat-square&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-%23FF6C37.svg?style=flat-square&logoColor=white)
![PixiJS](https://img.shields.io/badge/PixiJS-%23e91e8c.svg?style=flat-square&logoColor=white)

</div>

---

## 🔍 Technical Q&A

```bash
$ cat /etc/dexploarer/technical-interview
```

### How do you debug bugs and profile performance?

I write dedicated **benchmark harnesses** and bake **performance measurement into CI** so regressions are caught before they merge.

- **Criterion benchmarks in Rust** — In [prompt-or-die](https://github.com/Dexploarer/prompt-or-die) I built a [`render_pipeline.rs`](https://github.com/Dexploarer/prompt-or-die/blob/main/crates/pod-render/benches/render_pipeline.rs) benchmark that stress-tests render-state extraction across 9,000 mixed entities (sprites, 3D meshes, hierarchies) using Criterion throughput measurements. The [CI pipeline](https://github.com/Dexploarer/prompt-or-die/blob/main/.github/workflows/ci.yml) runs 250-iteration benchmark suites across 3 rounds and uploads artifacts for tracking.
- **PerformanceMonitor utility** — In [hyper-forge](https://github.com/Dexploarer/hyper-forge) I built a [`performance.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/utils/performance.ts) utility with `measureAsync()`, `measureSync()`, and a React hook `usePerformanceMeasure()` for component render timing — integrated with the Browser Performance API. The [CI pipeline](https://github.com/Dexploarer/hyper-forge/blob/main/.github/workflows/test.yml) includes a dedicated **Performance & Load Tests** job.
- **Simulation benchmark engine** — In [hyperscape](https://github.com/HyperscapeAI/hyperscape) I built [`benchmark.ts`](https://github.com/HyperscapeAI/hyperscape/blob/main/packages/sim-engine/src/benchmark.ts) — 16 stress-test scenarios (MEV attacks, Sybil swarms, oracle lag) × 12 seeds = 192 simulation runs aggregated with P10/P50/P90 quantiles. Plus an [`attack-fuzz.ts`](https://github.com/HyperscapeAI/hyperscape/blob/main/packages/sim-engine/src/attack-fuzz.ts) fuzzer for robustness profiling.

---

### Tell us about a case where you had to heavily optimize code/features for weak hardware.

**Prompt or Die** is a Rust game engine that compiles to both native and **WebAssembly** (`wasm32-unknown-unknown`) for browser targets — inherently resource-constrained.

- **ECS architecture** — [`pod-physics`](https://github.com/Dexploarer/prompt-or-die/blob/main/crates/pod-physics/src/lib.rs) and [`pod-spatial`](https://github.com/Dexploarer/prompt-or-die/blob/main/crates/pod-spatial/src/lib.rs) use [hecs](https://crates.io/crates/hecs) for cache-friendly entity management. [bytemuck](https://crates.io/crates/bytemuck) enables zero-copy GPU buffer serialization. Rapier2D uses `simd-stable` for vectorized physics on low-end CPUs.
- **Spatial acceleration** — `pod-spatial` implements an R-tree spatial index for O(log n) queries, a `UniformGrid` broad-phase hash for fast neighbor lookups, and `NavMesh` precomputed navigation — all designed to minimize per-frame allocation.

In **[hyper-forge](https://github.com/Dexploarer/hyper-forge)**, the 3D retargeting pipeline runs in-browser:

- **GC avoidance** — [`AnimationRetargeting.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/services/retargeting/AnimationRetargeting.ts) pre-allocates reusable `Quaternion` and `Vector3` instances to avoid garbage collection during animation loops.
- **Bone optimization** — [`SimpleHandRiggingService.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/services/hand-rigging/SimpleHandRiggingService.ts) (81KB) removes orphaned bones to prevent memory leaks, recalculates inverse bind matrices, and applies a `BONE_SCALE_FIX` for geometry scaling.

In **[hyperscape](https://github.com/HyperscapeAI/hyperscape)**, dedicated packages handle LOD and rendering optimization:

- [`packages/impostors`](https://github.com/HyperscapeAI/hyperscape/tree/main/packages/impostors) — billboard impostor rendering for distant objects
- [`packages/decimation`](https://github.com/HyperscapeAI/hyperscape/tree/main/packages/decimation) — automatic mesh decimation for level-of-detail generation
- [`packages/physx-js-webidl`](https://github.com/HyperscapeAI/hyperscape/tree/main/packages/physx-js-webidl) — PhysX compiled to WebAssembly for browser-side physics

---

### Experience with linear algebra, vectors, quaternions, physics?

Yes — extensively, across both Rust and TypeScript:

**Rust (prompt-or-die):**
- [`pod-physics/src/lib.rs`](https://github.com/Dexploarer/prompt-or-die/blob/main/crates/pod-physics/src/lib.rs) (24KB) — Full Rapier2D integration: `RigidBodySet`, `ColliderSet`, `NarrowPhase` collision detection, `CCDSolver` continuous collision, `QueryPipeline` for raycasts, deterministic 60Hz timestep.
- [`pod-spatial/src/lib.rs`](https://github.com/Dexploarer/prompt-or-die/blob/main/crates/pod-spatial/src/lib.rs) (25KB) — R-tree spatial indexing, A\* `GridPathfinder`, `NavMesh` navigation, `UniformGrid` broad-phase hashing, 2D raycasting. Uses `glam` for Vec2/Vec3/Vec4 math.

**TypeScript (hyper-forge) — Quaternion-heavy 3D retargeting:**
- [`AnimationRetargeting.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/services/retargeting/AnimationRetargeting.ts) (14KB) — Quaternion `premultiply`/`multiply`/`invert` for skeletal animation, Mixamo→VRM retargeting with coordinate system transforms (VRM 0.0 vs 1.0).
- [`VRMConverter.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/services/retargeting/VRMConverter.ts) (45KB) — Massive format conversion pipeline with Matrix4/Matrix3 bone transforms.
- [`SkeletonRetargeter.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/services/retargeting/SkeletonRetargeter.ts) (13KB), [`WeightTransferSolver.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/services/retargeting/WeightTransferSolver.ts) (13KB), [`DistanceChildTargetingSolver.ts`](https://github.com/Dexploarer/hyper-forge/blob/main/apps/core/src/services/retargeting/DistanceChildTargetingSolver.ts) (7KB) — IK constraint solving and skinning weight calculations.

**Physics engine (hyperscape):**
- [`packages/physx-js-webidl`](https://github.com/HyperscapeAI/hyperscape/tree/main/packages/physx-js-webidl) — Full NVIDIA PhysX integration compiled to WebAssembly via WebIDL bindings, Dockerized build pipeline.

---

### How do you work with version control (Git, Perforce) and CI/CD?

Every project I build ships with a multi-job **GitHub Actions** pipeline. Some examples:

- **[prompt-or-die CI](https://github.com/Dexploarer/prompt-or-die/blob/main/.github/workflows/ci.yml)** — 4-job Rust pipeline: workspace (`cargo check` + `cargo test` + `cargo clippy`), WASM browser builds (`wasm32-unknown-unknown`), Playwright smoke tests, and a 250-iteration benchmark suite with artifact uploads.
- **[hyper-forge CI](https://github.com/Dexploarer/hyper-forge/blob/main/.github/workflows/test.yml)** — 4 parallel jobs: Unit+Integration (PostgreSQL service, Codecov 80% threshold), E2E (Playwright across Chrome/Firefox/WebKit), Performance & Load Tests, and a Test Summary job that posts PR comments.
- **[hyperscape CI](https://github.com/HyperscapeAI/hyperscape/blob/main/.github/workflows/ci.yml)** — Enterprise monorepo pipeline: lint → test (PostgreSQL, Tauri system deps, recursive submodules) → build (Turbo dependency orchestration) → Docker (staging/production images). **10+ workflows** covering [deploy-cloudflare](https://github.com/HyperscapeAI/hyperscape/blob/main/.github/workflows/deploy-cloudflare.yml), [deploy-railway](https://github.com/HyperscapeAI/hyperscape/blob/main/.github/workflows/deploy-railway.yml), [deploy-vast](https://github.com/HyperscapeAI/hyperscape/blob/main/.github/workflows/deploy-vast.yml), [security scanning](https://github.com/HyperscapeAI/hyperscape/blob/main/.github/workflows/security.yml), [integration testing](https://github.com/HyperscapeAI/hyperscape/blob/main/.github/workflows/integration.yml), and [package publishing](https://github.com/HyperscapeAI/hyperscape/blob/main/.github/workflows/publish-duel-oracle-packages.yml).
- **[milady-ai](https://github.com/milady-ai)** — Contributed asset pipeline management (VRM/GLB), Git LFS troubleshooting, and deployment workflow setup across milady-ai/avatars and milady-ai/skills.

I use Git exclusively (no Perforce), with branch-per-feature, conventional commits, PR templates, and concurrency controls (`cancel-in-progress: true`) to prevent duplicate CI runs.

---

## 🏆 Highlights

```bash
$ cat trophy_case
```

- 💾 **3,920 contributions** in the last year — terminally locked in
- 🤖 **Active contributor** in the elizaOS / milady-ai ecosystem
- 🧩 **Built claudius-skills** — 174+ Claude Code configs across 10 installable plugin kits
- ⚡ **Built plugin-electrobun-dev** — full 8-stage SDLC Claude Code plugin with WebGPU support
- 🖥️ **Built dizzy-overlay** — native Go overlay powering Claude Code with live git context
- 🃏 **Creator of LunchTable TCG** — AI-native tabletop gaming platform
- 👻 **Contributing to Ghostspeak** — AI agent identity + reputation on Solana
- 🌐 **GitHub Developer Program Member**
- 🔗 Spanning: game engines · AI agents · onchain systems · desktop apps · DX tooling

---

## 🌐 Orgs & Ecosystems

```bash
$ ls /etc/orgs
```

| Org | Role |
|-----|------|
| [Blind Vibe](https://github.com/Blind-Vibe) | Studio / Founder |
| [milady-ai](https://github.com/milady-ai) | Contributor |
| [LunchTable-TCG](https://github.com/LunchTable-TCG) | Founder |
| [Ghostspeak](https://github.com/Ghostspeak) | Contributor |
| [Prompt-or-Die-Labs](https://github.com/Prompt-or-Die-Labs) | Founder |

---

<div align="center">
<sub><i>"Sometimes I make things with A.I."</i></sub>
</div>
