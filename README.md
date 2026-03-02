# PAI Seed

A starter kit for growing a Personal AI -- a system that operates on behalf of one person, improves through use, and reflects their priorities and vocabulary.

Nurtured by [Kwaai](https://kwaai.ai) as a community resource.

## Quick Start

### What You Need

- [Claude Code](https://claude.ai/download) -- the AI coding agent from Anthropic (tested). Other AI coding agents that support project-level context files may also work.
- [Git](https://git-scm.com/) and a [GitHub](https://github.com) account
- Something real you need to get done

### Plant the Seed

**Option A: Claude Code app (macOS)**

1. Download and install [Claude Code](https://claude.ai/download) for macOS.
2. Download this repository: click the green **Code** button above, then **Download ZIP**. Unzip it and rename the folder to `my-pai` (or whatever you like).
3. Open Claude Code. Drag your `my-pai` folder into the app, or use **File > Open Folder**.
4. Start talking. The seed handles the rest.

**Option B: Terminal**

```bash
git clone https://github.com/Kwaai-AI-Lab/pai-seed.git my-pai
cd my-pai
claude
```

Both paths lead to the same place -- a conversation where the seed learns what you care about and helps you accomplish something real. Your first artifacts grow from that first session.

### Why Git and GitHub

Your PAI lives in a local directory. Git gives you:

- **Save** -- Every session's work is committed. You can always go back.
- **Restore** -- Interrupted sessions, lost context, machine changes -- git history is your safety net.
- **Communicate** -- GitHub issues and pull requests are how you share patterns back to this nursery and how the nursery shares improvements back to you.

You do not need to be a developer. Your PAI handles git operations for you during sessions.

## What This Is

A Personal AI is not an assistant. It is a system you build and grow. You shape its vocabulary. You define its domains. You decide what it learns and how it works.

This repository contains the irreducible kernel -- two files that bootstrap the system:

- **`CLAUDE.md`** -- The bootstrap file. Your AI reads this on session start and becomes your PAI seed. It knows how to have the first conversation, how to help you name your world, and how to grow from real work.
- **`tree.md`** -- The architecture. Describes how a PAI is structured (roots, trunk, boughs, branches, leaves), how it grows, and how it stays healthy. Read this first if you want to understand the system before planting.

The seed does not prescribe what your system becomes. It provides the structural DNA for growth. What grows is determined by your priorities, your work, and your sustained attention.

## What Grows

The seed grows structure from demonstrated need, not from planning:

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

Everything else -- your glossary, your processes, your domain knowledge, your data -- grows from your work. The seed does not create these for you. You create them when you need them.

## The Grove

This repository is a **nursery** -- a place where seeds are cultivated and distributed. When you clone and grow your own PAI, you are planting a tree.

**What flows back to the nursery:**
- Structural patterns that proved useful in your tree
- Friction reports -- what did not work, what was confusing
- Growth observations -- what emerged naturally that the seed should prepare future Principals for

**What stays local to your tree:**
- Your data, your contacts, your domain knowledge
- Your vocabulary and priorities
- Your session history and reflections

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to share patterns, report friction, and propose seed improvements.

## License

[MIT](LICENSE)
