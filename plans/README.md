# Plans

This directory is your PAI's local roadmap. It is where you think about what your system should become next.

## The Convention

A plan is a markdown file that describes a proposed improvement to your PAI -- a new convention, a tool integration, a structural change, a bough to explore. Plans are written when you see a clear improvement opportunity, executed when the time is right, and archived when complete.

**Plans are local.** They live in your tree, not in a shared system. They track your system's evolution the way a product backlog tracks an application's evolution.

## Lifecycle

1. **Write** -- When you or your PAI identify an improvement, write a plan. Keep it concise: what will change, why, and what it depends on.
2. **Prioritize** -- Number prefixes signal priority. `1. plan-name.md` is next. Unnumbered plans are ideas.
3. **Execute** -- When you are ready, tell your PAI to execute a plan. It reads the plan, implements the changes, and commits.
4. **Archive** -- Completed plans move to `plans/archive/`. They are historical records.

## Why Plans Matter

A PAI without plans drifts. Plans make growth intentional:

- They force you to articulate what your system needs before building it.
- They create a record of how your system evolved and why.
- They prevent over-building -- if you cannot write a clear plan for it, you probably do not need it yet.
- They give your AI context for what you are trying to achieve across sessions.

## Starting Out

You do not need plans on day one. The seed's first sessions are conversational -- learning your vocabulary, doing real work, establishing a rhythm.

Plans emerge naturally. After a few sessions, you will notice friction. A process you keep re-explaining. A tool you wish were integrated. A domain that keeps coming up. When the observation is clear enough to write down, write a plan.

## Example

```markdown
# Add Git Convention

## Summary
Establish a version control convention for this PAI.

## Rationale
After 5 sessions, the commit history is inconsistent. Some sessions commit
after each change, others batch everything at close. A convention would
reduce friction and make session history readable.

## Changes
1. Add a "Version Control" section to the glossary.
2. Write a brief convention in the processes file.
3. Commit after each logical unit of change.
```

The example is small. Most plans should be. The Bonsai Principle applies to plans too.
