# Visual design guidelines

## Color roles

The Magangué flag is the origin of the visual identity: green and white are its primary references. They should establish recognition without reducing readability or turning every element green.

| Token | Hex | Role | Do not use for |
|---|---:|---|---|
| `--brand-primary` | `#167A45` | Primary action buttons, active navigation, logo details and decorative dividers | Paragraphs or long headings |
| `--text-primary` | `#17312A` | Headings and body copy on light surfaces | Decorative backgrounds |
| `--text-secondary` | `#42574F` | Supporting copy and metadata | Essential text below accessible contrast |
| `--surface-base` | `#FFFFFF` | Main cards and reading surfaces | Full-page visual monotony |
| `--surface-muted` | `#F5F0E6` | Page background and grouped sections | Text foreground |
| `--map-blue` | `#145C7A` | Map controls, location links and water-related data | General body text |
| `--accent-gold` | `#B97016` | Badges, featured food and warm highlights | Default buttons or paragraphs |
| `--accent-coral` | `#AF3F3A` | Event highlights with a text/icon label | Sole status indicator |
| `--focus-ring` | `#F5BF00` | Keyboard focus, paired with dark outline | General decoration |

## Application pattern

1. Use a calm reading surface: ivory page background and warm cream cards with subtle sand-colored borders.
2. Use dark ink for all headings and paragraph text. This creates hierarchy through size, weight and spacing rather than hue.
3. Use flag green for the primary call to action, active navigation and small branded details such as the header border. Secondary actions use an outlined or neutral treatment.
4. Use blue only where the content refers to the river, locations, maps or links. Use gold and coral sparingly for category emphasis.
5. Pair every color-coded state with a written label, icon, pattern or structural cue. For example, an event card says "Event" and does not rely only on coral.
6. Provide a visible keyboard focus ring and clear hover/focus states. Never remove focus styling.
7. Test every foreground/background pair at WCAG AA: 4.5:1 for standard text and 3:1 for large text and user-interface components.

## Reusable interface patterns

- **Header:** white surface, small green brand detail, dark text, active navigation marked with text weight plus an underline—not color alone.
- **Hero:** use a local photograph with a dark translucent overlay behind text, or place text on a solid surface next to the image. Never place essential copy directly over untested photographs.
- **Experience cards:** warm cream card, image, category label, dark title, short copy and one circular arrow action aligned at the lower right. The arrow requires an accessible text label in markup.
- **Language selector:** a compact, persistent `Español | English` control. The selected language needs a text cue and `aria-pressed` state, not color alone.
- **Map:** blue markers with descriptive labels; differentiate categories with a label/icon as well as color.
- **Footer:** dark ink or green background only if all text and links have verified contrast.

## Evidence-based references

- W3C Web Accessibility Initiative. (s. f.). *Understanding Success Criterion 1.4.3: Contrast (minimum).* https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum
- GOV.UK Design System. (s. f.). *Colour.* https://design-system.service.gov.uk/styles/colour/
- GOV.UK Brand Guidelines. (s. f.). *Maps - data.* https://brand.design-system.service.gov.uk/data/maps/
