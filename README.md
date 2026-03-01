# PAI Seed

A starter kit for growing a Personal AI -- a system that operates on behalf of one person, improves through use, and reflects their priorities and vocabulary.

This seed is nurtured by [Kwaai](https://kwaai.ai) as a community resource. It carries structural patterns hardened through real operational use, generalized for any Principal to plant and grow on their own.

## What This Is

A Personal AI is not an assistant. It is a system you build and grow. You shape its vocabulary. You define its domains. You decide what it learns and how it works. Every session is one iteration of a growth cycle: work together, reflect on what happened, accumulate observations, improve the system.

This repository contains the irreducible kernel -- two files that bootstrap the system:

- **`tree.md`** -- The architecture. Describes how a PAI is structured (roots, trunk, boughs, branches, leaves), how it grows, and how it stays healthy. Read this first.
- **`CLAUDE.md`** -- The bootstrap file. When you open a session in a directory containing this file, your AI reads it and becomes your PAI seed. It knows how to have the first conversation, how to help you name your world, and how to grow from real work.

The seed does not prescribe what your system becomes. It provides the structural DNA for growth. What grows is determined by your priorities, your work, and your sustained attention.

## Getting Started

### Prerequisites

- An AI coding agent that supports project-level context files (e.g., [Claude Code](https://docs.anthropic.com/en/docs/claude-code))
- A local directory where your PAI will live (this is your system -- it runs on your machine)
- Something real you need to get done

### Plant the Seed

```bash
git clone https://github.com/Kwaai-AI-Lab/pai-seed.git my-pai
cd my-pai
```

Open a session with your AI agent:

```bash
claude
```

Start working. The seed handles the rest -- it will have a conversation with you, learn what you care about, and help you accomplish something real. Your first artifacts grow from that first session.

### What Grows

The seed does not prescribe structure. It grows structure from demonstrated need:

- **Session 1** -- A conversation. A glossary begins. Real work gets done.
- **Sessions 2-5** -- Vocabulary sharpens. A session rhythm forms. The trunk thickens.
- **Sessions 5-20** -- Domains emerge as boughs. Processes are written when their absence causes friction.
- **Beyond** -- The system operates. Improvements come from operational friction, not planning.

This is the Bonsai Principle: grow what you need to accomplish more of what you are trying to do. No more.

## Project Structure

```
my-pai/
  CLAUDE.md        # Bootstrap -- your AI reads this on session start
  tree.md          # Architecture -- the tree metaphor
  plans/           # Your PAI's roadmap -- what to build next
  .gitignore       # Protects local data from version control
```

The `plans/` directory is where you think about what your PAI should become. Think of it as a local product backlog. Plans are written when you see a clear improvement, executed when the time is right, and archived when complete. See [`plans/README.md`](plans/README.md) for the convention.

Everything else -- your glossary, your processes, your domain knowledge, your data -- grows from your work. The seed does not create these directories for you. You create them when you need them.

## How the Grove Works

This repository is a **nursery** -- a place where seeds are cultivated and distributed. When you clone and grow your own PAI, you are planting a tree in the Kwaai grove.

**What flows back to the nursery:**
- Structural patterns that proved useful in your tree (process conventions, session patterns, tool integrations)
- Friction reports -- what didn't work, what was confusing, what the seed should do differently
- Growth observations -- what emerged naturally that the seed should prepare future Principals for

**What stays local to your tree:**
- Your data, your contacts, your domain knowledge
- Your vocabulary and priorities
- Your session history and reflections

The nursery grows when Principals share what works. Your tree grows when you use it. Both improve through the same mechanism: real work producing real observations producing real improvements.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to share patterns, report friction, and propose seed improvements.

## License

[MIT](LICENSE)

## Acknowledgments

This seed carries structural patterns from operational Personal AI systems. The tree metaphor, growth cycle, and Bonsai Principle were hardened through sustained real-world use before being generalized into this kernel. The Kwaai community nurtures this seed so that every Principal can grow their own.
