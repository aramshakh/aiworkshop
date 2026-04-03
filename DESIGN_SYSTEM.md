# AI Workshop — Design System

Based on empy.ai brand style.

## Color Palette

### Primary (Dark Background)
| Token            | Hex       | Usage                        |
|------------------|-----------|------------------------------|
| `--bg-primary`   | `#111318` | Main slide background        |
| `--bg-secondary` | `#15171C` | Card / block background      |
| `--bg-tertiary`  | `#1A1D24` | Subtle section separation    |
| `--bg-hover`     | `#252A33` | Hover states, active blocks  |

### Accent Colors
| Token            | Hex       | Usage                        |
|------------------|-----------|------------------------------|
| `--accent-green` | `#00AC47` | Primary CTA, success, highlights |
| `--accent-emerald` | `#10B981` | Secondary green, progress    |
| `--accent-blue`  | `#2D8CFF` | Links, info highlights       |
| `--accent-teal`  | `#14B8A6` | Decorative accents           |
| `--accent-purple`| `#6264A7` | Tags, badges, subtle accents |

### Text
| Token            | Hex       | Usage                        |
|------------------|-----------|------------------------------|
| `--text-primary` | `#FFFFFF` | Headings, key text           |
| `--text-secondary` | `#A0A8B8` | Body text, descriptions    |
| `--text-muted`   | `#6B7280` | Captions, footnotes          |

### Semantic
| Token            | Hex       | Usage                        |
|------------------|-----------|------------------------------|
| `--success`      | `#00AC47` | Checkpoints passed           |
| `--warning`      | `#F59E0B` | Attention needed             |
| `--error`        | `#EF4444` | Errors, troubleshooting      |

## Typography

- **Font family:** `system-ui, "Segoe UI", Roboto, Helvetica, Arial, sans-serif`
- **Slide title:** 2.5rem, bold, `--text-primary`
- **Slide subtitle:** 1.25rem, regular, `--accent-green`
- **Body text:** 1.1rem, regular, `--text-secondary`
- **Lists:** 1rem, `--text-secondary`, bullet color `--accent-green`

## Slide Layout Principles

- Dark theme throughout (consistent with empy.ai dark UI)
- One concept per slide
- Generous whitespace — no crowding
- Left-aligned text (no centered walls of text)
- Accent color for key phrases, not full sentences
- Progress bar at bottom using `--accent-green`

## Visual Elements

- **Checkpoint slides:** Green left border + checkmark icon
- **Action slides:** Blue left border + step number
- **Warning slides:** Amber left border + warning icon
- **Diagrams:** Simple, white lines on dark bg, accent colors for nodes
- **Code blocks:** `--bg-secondary` background, monospace font

## Spacing

- Slide padding: 60px horizontal, 40px vertical
- Between elements: 24px
- Between sections: 48px
