# Product MAPS

> A practical navigation framework for product teams

**Product MAPS** is a practical framework that helps product teams pause, align, and course-correct without slowing down delivery.

MAPS is the four-step navigation loop inside Product MAPS:

**MAPS stands for: Mark, Align, Proceed, Sync**

Product MAPS is designed for real product work: feature kickoffs, messy mid-project moments, launches, and course corrections—when uncertainty is real and alignment matters.

---

## Origin

Product MAPS grew out of real product failures, including a travel tech startup, and years of hands-on work studying how culture, behavior, and human psychology shape decisions.

It was first articulated at Cypher (Sep 2025), followed by DevFest (Dec 2025) under the title:

> Tech without culture is like GPS without maps

---

## Quick links
- [What is a Product Map?](#what-is-a-product-map)
- [How Product MAPS works](#how-product-maps-works)
- [Quickstart (10 minutes)](#quickstart-10-minutes)
- [Canonical template](maps/product_map.md)
- [Examples](maps/examples)
- [Docs](#documentation)
- [Changelog](CHANGELOG.md)
- [Cite Product MAPS](CITATION.cff)
- [Contributing](CONTRIBUTING.md)

---

## What is a Product Map?

A **Product Map** is a living document that captures how a team is currently navigating:

- the problem you’re solving
- whom it’s for
- the assumptions you’re making
- the constraints you must respect
- the outcome you’re aiming for
- how you’ll adapt as reality changes

Teams use Product Maps to:
- align before building
- spot drift mid-project
- make trade-offs explicit
- revisit decisions when conditions change

If a Product Map feels “heavy,” the fix is usually to simplify the map—not to skip the thinking.

---

## How Product MAPS works

MAPS is a navigation model inspired by how Google Maps works.

Like Google Maps helps people navigate places, MAPS helps product teams navigate real-world constraints so they build what users actually need, stay focused on outcomes, and adjust when reality changes.

### M — Mark your position
Before you move, know where you are.
Clarify the problem, whom it’s for, why it matters now, and what success means.

### A — Align with reality
Don’t proceed on assumptions.
Check real user behavior, constraints, and signals. Update your beliefs accordingly.

### P — Proceed with purpose
Choose the next step that creates signal.
Tie milestones to outcomes, and state explicit non-goals.

### S — Sync with feedback
Conditions change mid-journey.
Decide what you’ll monitor, how often you’ll review, and what triggers a reroute.

---

## Why Product MAPS exists

Most product failures aren’t caused by “bad tech.”
They happen when teams:
- build for imagined users, not real ones
- confuse movement (shipping) with progress (outcomes)
- ignore constraints until they bite
- receive feedback but don’t know how to respond

Product MAPS helps teams ground decisions in:
- what users will (and won’t) change
- real technical and operational constraints
- clear outcomes and trade-offs
- feedback loops that drive learning, not thrash

---

## Quickstart (10 minutes)

### Step 1: Create a Product Map
Create `my-feature.product-map.md` in your repo (or docs folder).

If you want the full canonical template, start here:
- [maps/product_map.md](maps/product_map.md)

Starter version:

```md
# [Project Name] — Product Map

## Mark (starting point)
- Problem:
- For whom:
- Why now:
- Core assumptions (3–5):
- What success means:

## Align (reality check)
- What we observed / measured:
- Key constraints (non-negotiables):
- What changed after looking at reality:

## Proceed (next meaningful step)
- Purpose (measurable outcome):
- Smallest milestone to learn:
- Explicit non-goals:

## Sync (feedback loop)
- Signals to monitor:
- Review cadence:
- Reroute triggers:
```

### Step 2: Fill it in with your team
Don’t overthink it. Start with what you know. Leave gaps where uncertainty exists.

Useful prompts:
- What are we assuming that we haven’t validated?
- What would make this direction wrong?
- What constraints will we hit no matter what?
- What signal would change our minds?

### Step 3: Revisit when reality shifts
Update your map when:
- user feedback conflicts with assumptions
- constraints emerge
- milestones feel disconnected from outcomes
- the team debates “what matters next”

---

## Using multiple Product Maps

Create **one Product Map per meaningful decision scope**.

Typical pattern:
- **Company / product-level map**: direction, major bets, shared assumptions
- **Team / domain-level maps**: different constraints, different success signals
- **Individual maps (optional)**: thinking aids that feed into shared maps

Maps are about **decisions**, not org charts.

See: [docs/how-to-use-multiple-product-maps.md](docs/how-to-use-multiple-product-maps.md)

---

## Documentation

Deeper guidance lives in [docs/](docs/), including:
- [How MAPS works (and when it breaks)](docs/how-maps-works.md)
- [When to use MAPS (and when not to)](docs/when-to-use-maps.md)
- [Common product failure patterns MAPS helps expose](docs/common-failure-patterns.md)
- [How to adapt MAPS without diluting it](docs/adapting-maps.md)
- [How to use multiple Product Maps safely](docs/how-to-use-multiple-product-maps.md)

Recommended reading order:
1) [docs/how-maps-works.md](docs/how-maps-works.md)  
2) [docs/when-to-use-maps.md](docs/when-to-use-maps.md)  
3) [maps/product_map.md](maps/product_map.md)

---

## Contributing

Contributions grounded in real product work are welcome:
- improving the canonical Product Map
- adding anonymized Product Map examples
- improving docs and clarity

Please read:
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

---

## License

This project uses a **non-commercial / no-resale license**.

MAPS is free for learning, internal use, and community contribution.
Commercial use or resale requires a separate license.

See [LICENSE](LICENSE) for details.
