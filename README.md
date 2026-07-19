# Hi, I'm Josh 👋

I build software with TypeScript, Zig, Go, and Python, everything from AI-powered yoga instructors to hackathon-winning platforms.

I'm an AI engineer at [Granola](https://www.granola.ai), the AI notepad for people in back-to-back meetings.

Before that I was a software engineer at [Let's Do This](https://www.letsdothis.com), building event discovery and booking platforms that handle some of the biggest events in the world, including the London Marathon ballot system.

Right now I'm exploring everything from AI agents to low-level systems work - basically whatever seems interesting. I write about the problems I run into on [my blog](https://www.joshtuddenham.dev/blog).

Before this, I spent a decade selling enterprise software. Turns out understanding what people need is most of the battle.

## Projects

**[Hearth](https://github.com/joshuaisaact/hearth)** - Local-first KVM microVM sandboxes for AI agent development, powered by a custom Zig VMM. Spawns isolated VMs in ~135ms via snapshot restore, with ~2ms command execution over virtio-vsock. Think E2B, but runs entirely on your machine. (WIP)

**[PetriFlow](https://github.com/joshuaisaact/petri-flow)** - A Petri net-based safety layer for AI agents. A declarative `.rules` DSL compiles each rule into a verified Petri net, enforcing tool access control, sequencing, rate limits, and human approval gates before an agent runs. Includes a Vercel AI SDK adapter, interactive visualiser, and four example agents. Published on [npm](https://www.npmjs.com/package/@petriflow/rules). I wrote about it **[here](https://petriflow.joshtuddenham.dev/)**.

**[Elastic Hash](https://github.com/joshuaisaact/elastic-hash)** - Zig implementation of elastic hashing from an [academic paper](https://arxiv.org/pdf/2501.02305). 4-8x faster inserts than std.HashMap at 99% load factor. A deep dive into hash table internals and SIMD optimization. I wrote about it **[here](https://www.joshtuddenham.dev/blog/hashmaps)**.

**[FizzBuzz Enterprise Edition](https://github.com/joshuaisaact/fizzbuzz-enterprise-edition-2026)** - Satirical "enterprise-grade" FizzBuzz with event-driven architecture, AI-powered divisibility detection via LLM fallback chains, and comprehensive observability. Because sometimes you need to over-engineer the classics.

**[Music Round](https://github.com/joshuaisaact/music-round)** - Real-time multiplayer song guessing game. Players identify songs from Spotify previews, with daily challenges and battle royale mode. Built with React 19, TanStack Start, and Convex for real-time sync.

## Tools & Templates

**[Auto Claude](https://github.com/joshuaisaact/auto-claude)** - Automated Claude Code agent runner that executes tasks from a queue file, handles context limits with automatic session restarts, and supports custom system prompts

**[petri-ts](https://www.npmjs.com/package/petri-ts)** - A TypeScript Petri net engine on npm. Define places and transitions, fire them, analyse reachable/terminal states, check invariants, and export Graphviz DOT. Includes a load/fire/save dispatcher for persisting net instances in production (bring your own DB transaction).

**[Petri Net](https://github.com/joshuaisaact/petri-net)** - A Petri net engine and three worked examples that teach concurrency concepts: from basic vocabulary (coffee brewing) to parallel approval (contracts) to resource contention (checkout). Includes a reachability analyser that proves invariants like "can't oversell inventory". I wrote about it **[here](https://www.joshtuddenham.dev/blog/petri-nets/)**.

## Research & Experiments

**[Forks & Locks](https://github.com/joshuaisaact/forks-locks)** - Empirically testing whether per-token entropy-adaptive decoding can close the gap between fixed temperature and SSD (Self-Distillation) on code generation. Confirms the theoretical ceiling of decode-time approaches and validates SSD gains with private-test-filtered training data (+2.98% pass@1). Benchmarked on LiveCodeBench v6 with RTX 4090.

**[Pointer Experiments](https://github.com/joshuaisaact/pointer-experiments)** - Testing pointer-based context management for long-running AI agents as an alternative to summarization. Replaces conversation content with lightweight chunk IDs and a retrieval tool, achieving 92% grounding vs 74% for summaries across cascaded compaction cycles.

---

**Find me:** [LinkedIn](https://www.linkedin.com/in/joshuatuddenham/) • [Bluesky](https://bsky.app/profile/joshtuddenham.dev) • [Email](mailto:joshuaisaact@gmail.com)
