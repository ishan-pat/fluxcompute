# FluxCompute

Serverless GPU inference for any model.

## What it is

FluxCompute is a developer platform for running ML models as autoscaling HTTP endpoints. Push a model (open-weights, fine-tune, or custom container), get a `https://flux.run/m/<id>` URL with sub-second cold starts, p50 latency dashboards, and per-token pricing. Built for teams that don't want to manage GPU clusters, but also don't want to be locked into a single foundation-model vendor.

**Audience:** ML engineers, applied AI teams, infra-conscious startups.

**Adjacent to:** Modal, Replicate, Baseten, RunPod, Together. Differentiator is cold-start performance + bring-your-own-container ergonomics.

## Brand voice

- **Technical, not corporate.** Assume the reader knows what a CUDA kernel is. Don't explain "What is GPU?"
- **Specific, not aspirational.** "p50 cold start: 340ms" beats "blazingly fast." Numbers > adjectives.
- **Calm confidence.** No hype, no exclamation points. The product speaks.
- **Direct.** "Deploy" not "unleash." "Endpoint" not "magical AI experience."

Reference tone: Linear changelogs, Vercel docs, Modal blog posts.

## Visual direction

Developer-tool aesthetic in the lineage of Linear / Vercel / Modal — dark-first, technical density, restrained color, mono accents. The brand mark is a stylized flux line — a single curved gradient stroke suggesting motion, energy, and the path data takes through a network. Avoid: glassmorphism, generic AI-blue gradients, hexagon-mesh patterns, robot iconography.

### Color
Two surfaces, one accent.
- **Surface:** near-black ink with cool undertone (not pure `#000`); paired with a near-white that's slightly warm.
- **Accent:** electric cyan → violet gradient ("flux"). Used sparingly — for the logo, the primary CTA, key data viz, and active states. If everything is accent, nothing is.
- **Status colors:** muted, technical — never saturated traffic-light hues.

### Type
- **Display + UI:** a geometric grotesk (Inter Tight or similar) — tight tracking on display sizes.
- **Mono:** for code, latency numbers, IDs, anything quantitative. JetBrains Mono.
- **No serif.** This is infrastructure, not a magazine.

### Layout
- 8px grid, dense but not cramped.
- Hairline 1px dividers (`rgba(255,255,255,0.08)` on dark) over heavy borders.
- Subtle dotted/grid background on hero surfaces — never as decoration alone, always implying coordinate space.

## Files

- `tokens.css` — color, type, spacing, radius, shadow tokens (CSS custom properties)
- `logo.svg` — primary mark
- `Design System.html` — token preview / spec sheet
- `Landing.html` — UI kit applied to a marketing page
- `SKILL.md` — instructions for AI assistants designing in this system
