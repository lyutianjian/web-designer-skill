# Working in an Existing UI

Use when extending or redesigning a visual product requires care around its identity or behavior. A small, isolated styling change can be handled directly from the affected component.

## Choose the extent of change

| Intent | Approach |
|---|---|
| Extension | Add or adjust the requested element using the existing visual vocabulary. |
| Preserve | Improve hierarchy, spacing, responsiveness, and craft while retaining recognizable identity and product structure. |
| Overhaul | Establish a new visual language within the product, content, and technical boundaries of the brief. |

These distinctions guide scope; they do not require a formal classification report. Ask about preserve versus overhaul only if the ambiguity would materially change the result.

## Inspect what the change touches

Use affected components, nearby screens, and supplied references to identify reusable tokens, layout relationships, image treatment, motion, and relevant states. Understand why existing patterns exist before replacing them.

Check contracts that the proposed change could affect: routes and anchors, form behavior, component APIs, analytics hooks, persistent state, keyboard and focus behavior, real content, and identity-critical assets. Preserve legal and factual copy unless changing it is part of the brief.

Existing authorization may already cover a contract change. Raise only unresolved scope changes; do not require a new approval for work the user has requested.

## Improve with a clear purpose

Choose the change that resolves the observed problem. Typography, spacing, grouping, and states may be sufficient; structural problems may warrant recomposition. Keep useful content and journeys intact rather than reducing density solely to create a showcase image.

For a substantial redesign, a concise before-and-after rationale can identify what remains, what changes, and the main tradeoff. Reuse project conventions for notes and versioning instead of creating mandatory parallel documents or numbered copies.

## Verify the affected experience

Match verification to the change. Inspection or a targeted preview can cover a small adjustment. When layout or interaction changes create a concrete browser risk, use the relevant parts of [browser acceptance](browser-acceptance.md), including the journeys the redesign is meant to preserve. Report the evidence actually gathered.
