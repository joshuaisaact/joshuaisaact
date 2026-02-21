# Hi, I'm Josh 👋

I build software with TypeScript, Zig, Go, and Python, everything from AI-powered yoga instructors to hackathon-winning platforms.

I'm a Full Stack Engineer at [Let's Do This](https://www.letsdothis.com), where I build event discovery and booking platforms. We handle some of the biggest events in the world, including the London Marathon ballot system. I work with TypeScript, Node.js and Next.js, and on systems that process hundreds of thousands of registrations.

Right now I'm exploring everything from AI agents to low-level systems work - basically whatever seems interesting. I write about the problems I run into on [my blog](https://www.joshtuddenham.dev/blog).

Before this, I spent a decade selling enterprise software. Turns out understanding what people need is most of the battle.

## Projects

**[PetriFlow](https://github.com/joshuaisaact/petri-flow)** - A Petri net-based safety layer for AI agents. A declarative `.rules` DSL compiles each rule into a verified Petri net, enforcing tool access control, sequencing, rate limits, and human approval gates before an agent runs. Includes a Vercel AI SDK adapter, interactive visualiser, and four example agents. Published on [npm](https://www.npmjs.com/package/@petriflow/rules). I wrote about it **[here](https://petriflow.joshtuddenham.dev/)**.

**[Elastic Hash](https://github.com/joshuaisaact/elastic-hash)** - Zig implementation of elastic hashing from an [academic paper](https://arxiv.org/pdf/2501.02305). 4-8x faster inserts than std.HashMap at 99% load factor. A deep dive into hash table internals and SIMD optimization. I wrote about it **[here](https://www.joshtuddenham.dev/blog/hashmaps)**.

**[FizzBuzz Enterprise Edition](https://github.com/joshuaisaact/fizzbuzz-enterprise-edition-2026)** - Satirical "enterprise-grade" FizzBuzz with event-driven architecture, AI-powered divisibility detection via LLM fallback chains, and comprehensive observability. Because sometimes you need to over-engineer the classics.

**[Music Round](https://github.com/joshuaisaact/music-round)** - Real-time multiplayer song guessing game. Players identify songs from Spotify previews, with daily challenges and battle royale mode. Built with React 19, TanStack Start, and Convex for real-time sync.

**FlowAI** - An agentic AI yoga instructor that generates personalized sessions. I wrote about **[the creativity vs. efficiency paradox here](https://www.joshtuddenham.dev/blog/maya-creativity-paradox)**.

**[AIgument](https://aigument.vercel.app/)** - Pit different AI models against each other in debates. You can assign personalities, control how spicy the arguments get, and save the good ones. Handles multiple LLM APIs with real-time streaming.

**[JoshDesk](https://joshdesk.joshtuddenham.dev/)** - A Slack app for hybrid work coordination. Teams across multiple companies use it to sync their office presence, check weather, and get smart reminders. Built with Bun and TypeScript, open source and self-hostable.

**[Foundations](https://foundations-app.vercel.app/)** - 🏆 Won "Best in Category" at JumpStart Hackathon. A platform for job seekers to check companies' diversity stats and employee feedback. Went from idea to working product in 24 hours.

## Tools & Templates

**[petri-ts](https://www.npmjs.com/package/petri-ts)** - A TypeScript Petri net engine on npm. Define places and transitions, fire them, analyse reachable/terminal states, check invariants, and export Graphviz DOT. Includes a load/fire/save dispatcher for persisting net instances in production (bring your own DB transaction).

**[Petri Net](https://github.com/joshuaisaact/petri-net)** - A Petri net engine and three worked examples that teach concurrency concepts: from basic vocabulary (coffee brewing) to parallel approval (contracts) to resource contention (checkout). Includes a reachability analyser that proves invariants like "can't oversell inventory". I wrote about it **[here](https://www.joshtuddenham.dev/blog/petri-nets/)**.

**[Go AI Agent Foundation](https://github.com/joshuaisaact/Go-AI-Agent)** - Starting point for building AI agents in Go, includes file operations and search tools

**[Bun Server Starter](https://github.com/joshuaisaact/bun-server-starter)** - Production-ready Bun HTTP server template because I got tired of setting up the same logging and error handling

---

**Find me:** [LinkedIn](https://www.linkedin.com/in/joshuatuddenham/) • [Bluesky](https://bsky.app/profile/joshtuddenham.dev) • [Email](mailto:joshuaisaact@gmail.com)
