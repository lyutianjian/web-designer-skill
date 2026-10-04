# Contextual Visual Failure Patterns

Use the matching section to diagnose an observed problem. These are signals to investigate in context, not a list of banned aesthetics. Intentional brand patterns and product requirements may explain a choice.

## Marketing Pages

| Signal | Why it matters and what to try |
|---|---|
| Every section repeats an eyebrow, headline, and paragraph | Repetition can flatten the story. Remove low-information labels or vary emphasis according to the content. |
| Mirrored image/text splits dominate the page | Alternation may be the only source of rhythm. Introduce a composition suited to the next proof point, comparison, or story beat. |
| A centered hero, decorative background, and paired CTAs appear without a clear purpose | Reconsider the primary message, asset, and action. Keep the composition if those needs support it. |
| Trust badges, testimonials, or metrics have no source | Replace invented claims with real evidence or clearly provisional content. |
| Different CTA labels lead to the same outcome | Consistent wording can clarify intent; retain differences that reflect actual commitment or funnel context. |

## Layout and Components

| Signal | Why it matters and what to try |
|---|---|
| Every fragment sits in a separate card | Containers may obscure grouping. Compare whitespace, alignment, dividers, or a shared surface. |
| A bento grid has empty or arbitrary cells | Let content and hierarchy determine the grid instead of filling a preset geometry. |
| Radii, borders, and shadows vary without a role | Reconcile the variations with component semantics and the existing token system. |
| A split heading leaves an unrelated paragraph floating across the page | Give each column a reason to exist, or simplify the reading order. |

## Typography and Content

| Signal | Why it matters and what to try |
|---|---|
| Display type has no relationship to the intended voice | Assess weight, scale, spacing, and language support before changing fonts. Familiar or system fonts may be exactly right. |
| Tiny labels, coordinates, version numbers, or status dots carry no information | Remove decoration that resembles meaningful data, or connect it to actual content or state. |
| Copy exists only to fill a shape | Prefer concrete content, an explicit placeholder, or a composition that needs fewer words. |
| The hero clips text, obscures the image, or hides the primary action | Recompose around the target viewport and reading order rather than enforcing universal word or line limits. |

## Imagery and Brand

| Signal | Why it matters and what to try |
|---|---|
| Decorative shapes impersonate a recognizable product or logo | Use the real asset or an honest placeholder. Abstract decoration is appropriate when it does not claim to depict the actual product. |
| Labels and pills crowd an image | Keep overlays that identify, control, or explain; move supporting information to a caption when clearer. |
| Related images disagree on material, lighting, palette, or treatment | Align the set with the intended visual direction while preserving necessary differences in subject matter. |

## Motion and Interaction

| Signal | Why it matters and what to try |
|---|---|
| Motion adds attention without explanation or feedback | Reduce it or connect it to a meaningful event. An expressive campaign can justify motion through narrative. |
| Broad React state updates on every pointer or scroll frame | Localize updates or use CSS, observers, or the project's motion tooling to avoid unnecessary rendering. |
| Several loops or scroll effects compete for attention | Establish an attention hierarchy and quiet effects that obscure the main task. |
| Reduced motion removes content or blocks a path | Preserve content order and task completion independently of animation. |

## Dashboards and Product UI

| Signal | Why it matters and what to try |
|---|---|
| Oversized headings, empty space, or cinematic effects impede scanning | Restore useful density, stable grouping, and visible state. |
| Decorative chart effects obscure comparison | Clarify scales, labels, units, and semantic encoding. |
| Components work only with populated success data | Add the states relevant to the actual journey, including overflow and keyboard focus where applicable. |

Report or repair consequential issues within the user's scope. An observed signal is not sufficient reason to redesign unrelated surfaces.
