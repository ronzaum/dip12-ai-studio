---
name: review
description: Comprehensive review of any non-code object — maps its layers, gateways, actors and flows, retraces every element, then judges from the retrace not the surface
---
You are running Review No Code — a comprehensive review of a non-code object (plan, document, thread, dataset, system). Be thorough but concise.

Each element visited returns one of: confirmed / changed / contradicts. Observer effects (what the review itself changed) are noted. Gaps are logged, not forced closed.

---

## Walk (outside in)

### Map — build the graph before judging anything
**Environment** — Scope explicit, dependencies named, assumptions stated
**Layers** — Every level of the object identified, each with its own rules stated
**Gateways** — Every transition between layers has a precondition and an effect, nothing crosses silently
**Actors** — Every role's knowledge, control, and enforcement explicit, none unaccounted for
**Architecture** — Logical hierarchy, sensible order, nothing at the wrong level

### Retrace — visit every element and connection with what the map revealed
**Components** — Each part correct and complete, no contradictions, no duplication
**Language** — One consistent idiom throughout, nothing foreign to the object's own conventions
**Flows** — Every dependency checked in both directions, every gap logged
**Resilience** — Limits handled, failure paths stated, recovery defined
**Efficiency** — No redundancy or bloat, effort proportional to value
**Hygiene** — No leftovers, nothing stale, nothing unconnected or isolated, nothing half-removed

### Verdict — judge from the retrace, not the surface
**Integrity** — Everything connected and maintained, claims backed by evidence, sensitive information protected
**Self-account** — The object's own description of itself matches what the retrace found
**Anomalies** — Every breaker named, with whether the system accounts for it

---

## Output Format

```markdown
### ✅ Looks Good
- [Item 1]
- [Item 2]

### ⚠️ Issues Found
- **[Severity]** [Location] — [Issue description]
  - Fix: [Suggested fix]

### 📊 Summary
- Items reviewed: X
- Critical issues: X
- Warnings: X
```

---

## Severity Levels

- **CRITICAL** — Wrong, harmful, or blocks the goal
- **HIGH** — Gap or error that changes outcomes
- **MEDIUM** — Quality, maintainability
- **LOW** — Style, minor improvements
