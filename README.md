[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


# DecisionOS

**DecisionOS** is an experimental decision-making framework and UI prototype for **AI-assisted reasoning** — designed for founders, operators, and builders who need to make high-stakes decisions with imperfect information.

It combines:
- **A structured decision framework** (clarity-first)
- **Repeatable thinking workflows** (to reduce bias + uncertainty)
- **A product direction toward an interactive tool** (Decision Chat + reports)

> Status: early-stage / evolving. Documentation is public; implementation details may change rapidly.

---

## Why DecisionOS exists

Most people don’t fail because they lack effort — they fail because they:
- solve the wrong problem,
- commit too early,
- don’t quantify tradeoffs,
- don’t revisit assumptions,
- confuse confidence with clarity.

DecisionOS is built to make decisions **traceable, reviewable, and improvable**.

---

## What it does (conceptually)

DecisionOS helps you:
- **Frame decisions clearly** (what is the real decision?)
- **Expose hidden assumptions & constraints**
- **Generate options** (including non-obvious ones)
- **Evaluate tradeoffs** (reversibility, risk, opportunity cost)
- **Decide with a confidence level**
- **Review outcomes** to improve future decision quality

---

## Current repository contents

This repo is organized into three layers:

### 1) Framework
Core philosophy + methodology  
- `FRAMEWORK.md`

### 2) Thinking workflows
Reusable mental models, prompts, and evaluation patterns  
- `THINKING.md` (coming)
- `NOTES.md` (coming)

### 3) Implementation (prototype)
A modern UI prototype will be committed when it’s packaged cleanly.

---

## Prototype direction (product vision)

DecisionOS is evolving toward a tool that supports:

### AI Decision Chat
A guided assistant that:
- asks the right questions,
- collects context,
- identifies missing info,
- generates structured options and tradeoffs.

### One-screen Interactive Report
After the conversation, DecisionOS generates a single screen output:
- summary of context + constraints
- decision options and scoring
- pros/cons and second-order effects
- recommendations with confidence level
- “next actions” checklist

### Notes + Memory (optional)
Decision logs that can be revisited:
- assumptions made at time of decision
- what changed since then
- what was learned

---

## Tech direction (implementation)

The prototype implementation is built around a modern web stack:

- **TypeScript**
- **React**
- UI components structured for modular iteration
- Service layer for AI calls (provider-agnostic)

> The codebase will be published incrementally to keep commits clean and maintainable.

---

## How to use (today)

Right now, DecisionOS is usable as a framework:

1. Read `FRAMEWORK.md`
2. Use DecisionOS to structure a decision using the loop:
   - Frame → Constraints → Options → Tradeoffs → Decide → Review
3. Log your outcomes in `NOTES.md` (coming)

---

## Roadmap

### Phase 1 — Documentation-first (now)
- Framework docs
- Thinking workflows
- Decision templates & examples

### Phase 2 — Prototype release
- UI prototype commit
- basic decision flows
- structured report output

### Phase 3 — Advanced reasoning & systems
- decision scoring + heuristics
- scenario simulation
- decision history + comparison

---

## Contributing

DecisionOS is currently curated to keep the framework consistent.

If you’d like to contribute:
- open an issue with suggestions
- propose additional decision templates or workflows
- share examples of real-world decisions + outcomes

---

## License

MIT — see `LICENSE`.
