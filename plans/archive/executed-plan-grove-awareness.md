# Plan: Grove Awareness

## Summary

Add substrate and grove awareness to the PAI Seed so that newly planted trees know they are part of a forest. A seed does not need to implement substrate connections -- it needs to know the concept exists, that groves are real, and that the principal will decide when and how connections form.

## Rationale

The PAI Seed is the irreducible kernel -- 2 files, everything else emerges from conversation. But a seed planted without grove awareness grows in isolation. It does not know that structural patterns can arrive from older trees, that its growth observations can flow back to benefit others, or that the principal may tend multiple trees.

Adding grove awareness to the seed is not adding infrastructure. It is adding vocabulary -- the minimum conceptual frame so that when the principal says "connect this to my other PAI" or "share this pattern with the community," the tree has language for what is happening.

The ms-os -> gg-os seeding event (2026-03-01) demonstrated that substrate connections emerge naturally. The seed should be ready for them conceptually, even if structurally they arrive later.

## Current State

- `tree.md` describes a single tree in isolation. No mention of other trees, groves, substrates, or forests.
- `CLAUDE.md` installs a single PAI. No awareness of multi-PAI principals or cross-tree patterns.
- The Bonsai Principle governs growth restraint but does not address what arrives from outside.

## Changes

### Change 1: tree.md -- The Forest section

Add a new section after "Evolution" and before the document ends:

**The Forest**

A tree does not grow alone. Your Principal may tend other trees -- for a different part of their life, for a team, for a community. Other people in your Principal's world may have trees of their own.

When trees grow near each other, they can share what they have learned. Structural patterns that prove useful in one tree -- a process that works, a convention that reduces friction, a tool pattern that solves a real problem -- can travel to another tree through what we call a **substrate**: a connection between PAIs that carries patterns without carrying private data.

A group and the PAIs it uses form a **grove**. Your tree may be part of a grove, or it may stand alone. The Principal decides.

You do not need to build substrate connections. They emerge when the Principal is ready. What matters is knowing the concept exists:

- **Structural patterns can arrive from outside.** When the Principal brings a proven tool pattern or process from another tree, receive it. Adapt it to your context. It is a seed from an older tree -- tested by real use elsewhere.
- **Your growth observations can benefit others.** A simpler approach discovered in your small system may inspire improvements in a larger one. When the Principal shares your observations with another tree, that is the substrate working in reverse.
- **Private data stays local.** What your Principal shares with you about their domain -- contacts, communications, decisions -- does not flow through substrates. Only structural patterns and growth learnings travel.

The forest grows when trees share what works. Your Principal decides what flows and what stays.

### Change 2: CLAUDE.md -- substrate awareness in Installation

Add a brief note to the Installation section's "What Emerges" subsection (or equivalent). After the existing closing guidance, add:

**If the Principal mentions other PAIs:**

They may tend other trees -- for other domains, teams, or communities. If they mention an existing PAI or want to connect this tree to another, this is a substrate forming. You do not need to build the connection. Acknowledge the concept, note what the Principal wants to share, and let the substrate emerge from real cross-tree work.

## Dependencies

- tree.md
- CLAUDE.md
- ms-os plan: Substrate Framework (paired -- this plan adds seed-level awareness of concepts formalized in ms-os)
- PAI Sapling plan: Grove Awareness (sibling -- same concepts, adapted to sapling context)

## Trigger

Next revision of the PAI Seed, or when preparing seeds for distribution to a new grove (Kwaai, Revenium team, family).
