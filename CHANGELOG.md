# Changelog

## 1.1.0 (2026-06-10)

### Design taste refresh

Sharper guardrails against the current generation of AI design clichés, plus process discipline that keeps generations committed to a bold direction.

- **Mandatory design brief**: the skill now requires stating direction, palette, type, layout, and signature move BEFORE writing code -- prevents silent regression to defaults mid-generation
- **Commitment rules**: "default to brave" + "don't converge" (rotate aesthetic directions across projects instead of defaulting to dark portfolio every time)
- **Fixed self-contradiction**: font pairing formulas recommended Inter, Montserrat, and Open Sans -- the exact fonts the anti-pattern checklist bans. Replaced with distinctive alternatives (Hanken Grotesk, Bricolage Grotesque, Figtree, Schibsted Grotesk)
- **New "Fonts That Scream AI" table**: overused faces (Inter, Roboto, Poppins, Playfair Display, Merriweather...) mapped to distinctive same-role alternatives, all free on Google Fonts
- **Forbidden default hues**: the Tailwind violet family (#8B5CF6 etc.), reflexive primary blue, blue-to-purple gradients -- plus oklch() palette guidance
- **5 new AI anti-patterns** (#11-15): emoji as icons, the "✨ Introducing" pill badge, gradient-clipped headlines, glassmorphism-on-everything, fake social proof
- **Craft Details floor**: designed hover/focus-visible/active states, styled ::selection, real copy (never lorem ipsum), WCAG AA contrast, semantic HTML, SVG favicon
- **Working Inside Frameworks**: Tailwind token discipline, React/Vue/Svelte adaptation, and how to be "brave" inside an existing design system (coherence over imposition)
- **Mandatory final self-review**: find the most generic element and redesign it before delivering

## 1.0.0 (2026-03-26)

### Initial Release

- 48 design patterns extracted from 38 award-winning websites
- 5 color palette archetypes with production-ready CSS custom properties
- 5 font pairing formulas with fluid type scale
- Complete animation playbook (entrances, hovers, scroll-linked, page transitions, micro-interactions)
- 9 dedicated 3D/immersive patterns (card tilt, perspective text, parallax depth, physical buttons, etc.)
- 10 AI anti-pattern identifications with alternatives
- Design decision framework (mood, palette, type, layout, motion, signature)
- 3 concept site examples (dark portfolio, bold e-commerce, warm SaaS)
- Cross-platform support: Claude Code, Cursor, GitHub Copilot

### Sites Researched
SVZ Design, VOUS Church, Ready.so, April Ford, Chiara Luzzana, Pierre-Louis Labonne, Superlist, Michael Kors Collection, Slite, The Goonies, DONUTS, De La Calle, Magic Spoon, Couplet Coffee, Hardgraft, Haus, Koffiracha, 207ouest, Daylight Computer, Collider, and more.
