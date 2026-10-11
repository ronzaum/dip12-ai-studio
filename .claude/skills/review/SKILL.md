---
name: review
description: Review any piece of work (a plan, a page, a text, a source list, an artifact) by retracing every part of it, then judging. Use before showing work to a tutor or moving on.
---
You are running Review: a thorough review of a non-code object. Be thorough but concise.

Each element you visit returns one of: confirmed / changed / contradicts. Log gaps; don't force them closed.

## Walk (outside in)

### Map: build the picture before judging
- **Scope.** What is this object for, who is it for, what does it depend on? Check against `project/brief.md`.
- **Layers.** Every level of the object (argument, sections, images, sources), each with its own rules.
- **Links.** Every move from one part to the next has a reason. Nothing jumps.
- **Authorship.** For each part: did the AI compile it or did the student decide it? Check `DECISIONS.md`.

### Retrace: visit every element with what the map showed
- **Parts.** Each part correct and complete, no contradictions, no duplication.
- **Sources.** Every reference exists and says what is claimed. Mark anything unverifiable.
- **Language.** One voice throughout. No generic filler, no AI phrasing ("delve", "tapestry", "seamlessly").
- **Taste.** Visuals follow `TASTE.md`. Nothing decorative. Nothing generic.
- **Economy.** No padding. Effort matches value.

### Verdict: judge from the retrace, not the surface
- **Integrity.** Claims backed by evidence.
- **Self-account.** What the object says it is matches what it is.
- **Judgement.** Where is the student's own decision visible? Where is it missing?

## Output
```markdown
### ✅ Holds up
- ...

### ⚠️ Issues
- **[Severity]** [Where]: [Issue]
  - Fix: [Suggestion]

### 🧭 Your call
- Decisions only the student can make

### 📊 Summary
- Items reviewed: X · Critical: X · Warnings: X
```

## Severity
- **CRITICAL**: wrong, invented, or undermines the project
- **HIGH**: gap that changes the outcome
- **MEDIUM**: quality, clarity
- **LOW**: style
