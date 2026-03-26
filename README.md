# Arete — Visual Skill Creator IDE

Arete (αρετή) is a single-file, browser-based mind map editor that turns visual thinking into structured `SKILL.md` files — behavioral instructions that AI agents can load and execute.

**Think visually. Export as code.**

## What it does

1. **Draw a mind map** — nodes, branches, drag-and-drop
2. **Auto-generates SKILL.md** — real-time preview with frontmatter, sections, and formatting
3. **Two-way sync** — edit the mind map or the markdown, both stay in sync
4. **Push to GitHub** — one click to publish your skill

## Quick start

Open `index.html` in any browser. That's it — no build step, no dependencies, no server.

## Features

- **Mind map canvas** — pan, zoom, drag nodes, auto-layout
- **Node types** — trigger (blue), step (green), tool (purple), description, note, example
- **Keyboard-first** — `Tab` add child, `Enter` add sibling, `Delete` remove, `F` fit view, `L` layout
- **Two-way markdown sync** — edit nodes or edit markdown directly
- **Multi-tab** — work on multiple skills simultaneously
- **AI expand** — select a node, let Claude suggest children (requires API key)
- **GitHub push** — publish SKILL.md directly to a repo
- **Lint panel** — real-time quality hints (missing triggers, steps, etc.)
- **Minimap** — bird's eye navigation for large trees
- **Undo/Redo** — `Cmd+Z` / `Cmd+Shift+Z`
- **Dark mode** — toggle with the moon icon
- **Auto-save** — all work saved to localStorage

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Tab` | Add child node |
| `Enter` | Add sibling node |
| `Delete` / `Backspace` | Delete selected node |
| `Escape` | Deselect |
| `F` | Fit view |
| `L` | Re-layout |
| `Cmd+Z` | Undo |
| `Cmd+Shift+Z` | Redo |
| `Cmd+B` | Toggle markdown panel |
| `Cmd+T` | New tab |
| `Shift+Drag` | Lasso select |

## Tech

- Single HTML file (~3000 lines), vanilla JS/CSS
- Zero dependencies, zero build step
- Works offline, data stored in localStorage

## License

MIT
