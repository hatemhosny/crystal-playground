# Taste
- Prefers self-contained static HTML deliverables: a single `.html` file that runs with no build step or server, loading dependencies from a CDN. Confidence: 0.55
- Conveys desired output by linking reference implementations, docs, or prior examples/issues to match — for both UX/behavior and written deliverables (issues, posts) — rather than describing every detail, and expects those references to be studied and matched in tone/structure. Confidence: 0.5
- Wants written deliverables (e.g. GitHub issues, announcements) handed back as copy-ready markdown text they can paste directly, not just a description of what to write. Confidence: 0.6
- Hand-edits the working file directly, then expects the agent to build on top of those edits (read current state first, don't overwrite or revert their changes). Confidence: 0.5
- Supplies exact asset snippets (e.g. official SVG markup) to be used verbatim rather than having the agent approximate them. Confidence: 0.45
- Cares about visual contrast/legibility of graphics (logos, icons) against the real page background and expects low-contrast cases to be fixed, not tolerated. Confidence: 0.45
- Wants official/brand artwork kept in its original colors — no recoloring or inverting to fit a background; prefers non-destructive fixes like a drop shadow/halo that leave the artwork's own colors untouched. Confidence: 0.5
