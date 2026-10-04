# Artifact Notes

Read the section relevant to the requested deliverable. Use the project's existing stack and adapt these constraints to its audience and environment.

## HTML Slides

- Choose a fixed canvas or fluid layout from the presentation requirements. For a fixed canvas, scale uniformly within the available viewport so text and imagery keep their proportions.
- Keep navigation controls usable independently of canvas scaling. Place them outside the scaled stage when shrinking the stage would make them too small.
- Support the intended presentation controls without intercepting typing or interaction inside embedded content. Visible slide numbers should match the user's way of referring to slides.
- Set content density and type scale for the viewing distance. Check both the intended canvas and a smaller outer viewport when fit-to-window behavior matters.
- Position persistence and speaker or overview controls are useful when the presentation workflow needs them; follow project conventions for state storage.

## Interactive Prototypes

- Implement the paths needed to evaluate the product question. Cover loading, empty, error, disabled, and focus states where they affect those paths.
- Device frames can communicate context; omit them when they constrain useful space or imply an unintended platform. Use the target platform's interaction conventions.
- For visual comparison, a shared canvas may be enough. For flow evaluation, keep navigation and state transitions coherent. Add variants or live controls only when they help compare a real choice.
- In an embedded preview, check which container owns scrolling. Scope programmatic scrolling to that container if scrolling a target also moves the host page; ordinary page scrolling does not need a blanket API ban.

## Motion and Animation

- Choose an approach that fits the existing stack and the motion's complexity. CSS is often sufficient for local state feedback; coordinated or interactive timelines may benefit from existing motion tools.
- Preserve content, task completion, and feedback when reduced motion is requested. Movement should communicate state, hierarchy, causality, or narrative.
- Add playback, pause, or scrubbing controls when the experience calls for them. If exposed, pause/resume and scrubbing should preserve a coherent timeline position.
- Keep high-frequency updates local to the animated elements. Prefer compositor-friendly properties where appropriate, and check that motion does not block input or leave content inaccessible.

## Data Visualization

- Choose visual encoding from the comparison the user needs to make. Use position, scale, grouping, and color consistently, with labels and units that make interpretation possible.
- Use real data when supplied. Clearly distinguish sample data in a prototype from factual claims about a product or organization.
- Adapt chart containers and label density to available space. Check narrow layouts for lost categories, clipped labels, and misleading scales.
- Provide accessible labels or an equivalent textual or tabular view where needed. Meaning should survive without color alone.
- Reuse the project's charting and theme infrastructure. Add theme switching, animation, or extra controls only when they serve the intended use.
