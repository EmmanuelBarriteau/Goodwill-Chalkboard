Goodwill Chalkboard
An open-source, crowdsource-AI problem-solving engine for humanity.

"A digital MIT hallway for 8 billion people, as in the 1997 film, Good Will Hunting, where anyone walking by can attempt to solve the problem on the board, AI translates and verifies, and everyone who moves the needle towards the solution gets permanent credit."

The Vision
Right now, humanity solves problems in isolated silos. Additionally, millions of people ask AI similar questions every day and brilliant outside-the-box intuitions from everyday people disappear into private chat logs.

Experts may sometimes not readily see or question an anomaly due to specialization, while everyday people with unique lived experiences may see a not so obvious solution, or question the existence of a phenomenon in a field even beyond their education level. Think of Dutch schoolteacher, Hanny van Arkel spotting a glowing, mysterious space object while volunteering in the Galaxy Zoo citizen-science project.

Goodwill Chalkboard attempts to bridges that gap.

It is a 100% open-source, community-owned public utility designed to:
Surface humanity’s unsolved problems (from everyday personal bottlenecks to grand scientific challenges).

Let anyone contribute raw ideas in plain English, regardless of credentials or formal education.

Use AI as a translator, deduplicator and synthesizer to turn raw human intuition into structured plans, verify them against existing knowledge/simulations, and merge breakthroughs into a living Master Plan.

Guarantee permanent, transparent attribution so every contributor whose spark nudged a solution forward gets credit.

No venture capital, black-box algorithms or walled gardens.

How It Works (The Core Loop) 

1. Submit a Problem (Personal or Global)
A user posts a problem, for example, "How would a civilization go about retrieving solar plasma off their host star?" or "How does a mom & pop pizzeria eliminate end-of-day waste?"

Instant Vector Check: The system embeds the query and searches the global ledger. If already solved, it immediately delivers the community-built playbook. If unsolved, it opens a public Problem Room.

2. Walk by and attempt to solve the problem on the board.
Anyone browsing the feed can click into a Problem Room, read the current AI-synthesized Master Plan, and drop an idea, hunch, or weird connection in plain language.

The AI acts as a translator and referee; not a gatekeeper. It checks if the idea is a duplicate, translates raw intuition into formal structure, tests it against known constraints and tells the user immediately:
"Already submitted by @user123, do you want to build on their branch?"
"Unique angle! Merged into Step 4 of the Master Plan."
"Hits a physics bottleneck at X can you find a way around it?"

3. Bottleneck Forking
When a proposed solution hits a wall, we don't shelve the problem. The bottleneck automatically forks into a new sub-problem on the board so the crowd can attack that specific hurdle directly.

4. Receipts & Attribution
Every accepted contribution is logged as a verifiable node in the problem's dependency tree.

Anyone can trace the exact lineage of a breakthrough back to the person whose random Tuesday afternoon thought unlocked it.

Proposed Open-Source Stack (MVP)
To keep this lightweight, decentralized, and cheap to host without "techbro" infrastructure:

Frontend: Next.js / React or SvelteKit (clean, fast, mobile-first feed).

Database & Vector Search: PostgreSQL + pgvector (via Supabase or self-hosted).

AI Layer (Model-Agnostic / BYOK): Support for open-weights models (Llama, Mistral, Qwen via Ollama/vLLM) plus Bring-Your-Own-Key (BYOK) API support so compute costs can be shared by the community.

Ledger / Data: Publicly exportable JSON/Markdown solution trees so the knowledge base belongs to everyone forever.

How to Contribute (No Code Required to Start)

We need builders, thinkers, and tinkerers of all backgrounds:

Architects & Devs: Help scaffold the pgvector deduplication pipeline, the LLM synthesis prompts, and the attribution tree schema.

Prompt & Verification Engineers: Design the system prompts that keep the AI objective, constructive, and ruthless about spotting genuine novelty over noise.

Problem Curators: Help seed the initial board with 100 real-world problems: from local everyday headaches to moonshot physics just to kick off the first wave of crowd-storming.

License
Released under the MIT License (or AGPLv3 to ensure any hosted versions stay open-source forever). Built by everyone, owned by no one.
