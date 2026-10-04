# Browser Acceptance

Use for requested browser acceptance or a concrete browser-dependent risk, such as a breakpoint rewrite, a changed overlay, or a primary form interaction. Small visual changes may need only inspection or a targeted preview; they do not imply a full acceptance pass.

## Scope the evidence

Derive the entry point, affected screens, primary journey, target viewports, and browser requirements from the task and project. Clarify only gaps that prevent useful validation. A supplied screenshot can support visual critique but cannot establish untested behavior.

Use existing browser tooling, dependencies, and project commands. Reuse an available server or start the intended local process and verify its ready state. No new test framework is required merely to inspect an artifact. Exercise flows without unintended external submissions or data changes.

Choose checks that address the requested criteria or the identified risk. For responsive changes, inspect representative widths around the affected breakpoint; use user-specified targets when provided. For a fixed canvas, check the intended composition and fit within a smaller outer viewport. Cross-browser coverage is useful when requested or when browser-specific behavior is at issue.

## Check the affected experience

| Area | Evidence to seek |
|---|---|
| Runtime | The page and relevant assets load; new console errors, hydration issues, or failed requests do not break the tested path. Distinguish unrelated noise. |
| Layout | Content and controls remain reachable; text does not unintentionally clip or collide; images preserve the intended crop; overflow and canvas scaling behave as intended. |
| Interaction | Primary actions work; focus is visible and ordered; forms expose labels and relevant feedback; overlays can be opened and closed without losing the user. |
| States | Exercise loading, empty, error, disabled, or permission states when they are relevant and safely reachable. |
| Motion | Animation preserves interaction and content under reduced motion. Test playback controls when the artifact exposes them. |
| Visual design | Inspect hierarchy, alignment, legibility, token consistency, and differences from the supplied reference at the states being tested. |

Screenshots or other evidence are useful when they explain a finding or satisfy the requested report. Use a formal baseline for visual regression; without one, describe the work as visual inspection or acceptance.

## Repair within the authorized scope

For report-only QA, present findings without editing the artifact. When implementation or repairs are authorized, reproduce the failure, address its cause, and recheck the affected state. Check adjacent behavior only when the repair could plausibly change it.

Stop when the requested criteria are met or a concrete blocker prevents progress. Repeated broad passes are unnecessary when nothing relevant has changed.

## Report what was verified

Summarize the tested environment and conditions, consequential findings, repairs, and remaining gaps. Include enough location or reproduction detail to make issues actionable. Distinguish observed behavior from code-based inference, and say when browser execution was unavailable. Do not claim a pass for checks that were not performed.
