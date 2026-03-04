# Contributing to PAI Seed

This project is a nursery -- a community resource for growing Personal AI systems. Contributions improve the seed that every new Principal plants from.

## What We Accept

### Structural Patterns

The most valuable contributions are structural patterns that proved useful in your own PAI:

- **Process conventions** -- A way of working that reduced friction across multiple sessions.
- **Session patterns** -- Approaches to opening, working, or closing sessions that improved continuity.
- **Tool integration patterns** -- How you connected a tool and what conventions made it reliable.
- **Growth observations** -- What emerged naturally in your tree that the seed should prepare future Principals for.

Patterns must be **generalized** -- stripped of your specific vocabulary, domain data, and personal context. The seed carries structural DNA, not any one Principal's content.

### Friction Reports

If something in the seed did not work -- confusing language, a convention that fought your natural workflow, a missing concept that every Principal discovers independently -- file an issue. Friction reports improve the seed for everyone.

### Fixes and Documentation

Typos, broken links, unclear language, incorrect instructions. Standard open source contributions. Keep PRs focused.

## What We Do Not Accept

- **Domain-specific content** -- The seed is domain-agnostic. Boughs, knowledge bases, and domain processes belong in your tree, not the seed.
- **Opinionated tooling** -- The seed names concepts (surfaces, roots) without prescribing specific tools. Contributions that assume a specific AI provider, editor, or platform will not be merged. Contributions that enable usuers on more surfaces will be welcomed. This project is currently in voilation of this rule. A priority will be to extend surfaces and roots, including KwaaiNet.
- **Speculative structure** -- The seed follows the Bonsai Principle: structure grows from demonstrated need. Additions must be backed by real operational use, not theoretical value.

## How to Contribute

### Issues

Use the issue templates:

- **Friction Report** -- Something in the seed caused problems when you were growing your tree.
- **Pattern Share** -- A structural pattern that worked well in your tree and could improve the seed.

### Pull Requests

1. Fork the repository.
2. Create a branch from `main` with a descriptive name.
3. Make your changes. Keep commits atomic and messages clear.
4. Open a pull request using the PR template.

**PR guidelines:**

- One concern per PR. A process convention fix and a documentation improvement are two PRs.
- Explain what operational experience produced the change. "I found that..." is stronger than "It would be better if...".
- If your change modifies `CLAUDE.md` or `tree.md`, explain why the current language is insufficient and what friction it caused.

### Commit Messages

Write clear, descriptive commit messages. Describe what changed and why.

```
Add session checkpoint convention to CLAUDE.md

After 10+ sessions, losing work to interrupted sessions became
recurring friction. A lightweight checkpoint file convention
prevents re-derivation on resume.
```

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). By participating, you agree to uphold a respectful and constructive environment.

## Flow Classification

Contributions to this nursery follow the substrate flow model:

| What Flows | Direction | Example |
|---|---|---|
| Structural patterns | Your tree -> nursery -> all trees | A session convention that reduces friction |
| Growth observations | Your tree -> nursery | "Every Principal independently discovers X" |
| Friction signals | Your tree -> nursery | "The installation section assumes Y" |
| Private data | Never flows | Your contacts, domain knowledge, vocabulary |

The nursery grows when Principals share what works. Your private data stays in your tree.

