# tufte-dataink — Edward Tufte-Inspired Data Presentation

Illustrative cues, not an official brand specification. Supplied references and accessibility needs take precedence.

**Context**: Information Architecture. Analytical reports, explanatory charts, and pages where evidence drives the design.
**Reference points**: The Visual Display of Quantitative Information and Beautiful Evidence.

## Starting palette and type

- Warm paper `#FBFAF6`; ink `#1B1B1A`; reference rules `#D8D2C2`.
- Muted red `#A6300E` and slate `#3E4A5C` are example series colors. Add or change encodings to fit the actual data, with sufficient contrast.
- Serif options: ET Book, Equity, or Lyon Text; a clear sans can support axis labels and controls.
- Size labels and annotations for the viewing conditions. Compact information does not require tiny text.

## Composition cues

- Spacing example: 4 / 8 / 12 / 16 / 24 / 48; use grouping to make dense comparisons readable.
- Inline sparklines can connect a statement to its evidence. Marginal notes can explain a chart without interrupting its reading path.
- Direct labels may reduce the effort of matching series to a separate legend.
- Small multiples support comparison when scales and ordering are consistent. Quiet frames and reference lines can help the data stand out.

## Tradeoffs

Chart type, color count, gridlines, and interaction should follow the analytical question. These cues also work in interactive or mobile interfaces: move marginal notes into the reading flow and preserve useful filters or tooltips. Decoration becomes a problem when it obscures comparison or implies data that is not present.

## Optional image study

> Layout study for an analytical figure on warm paper #FBFAF6, muted red and slate series, direct labels and margin annotations, 4:3. Render final charts from the actual data in code; the study supplies composition only.

[Browse references](INDEX.md)
