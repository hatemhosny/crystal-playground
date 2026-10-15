# Taste
- Prefers self-contained static HTML deliverables: a single `.html` file that runs with no build step or server, loading dependencies from a CDN. Confidence: 0.55
- Conveys desired UX/behavior by linking reference implementations or docs to match, rather than describing every detail. Confidence: 0.5
- Hand-edits the working file directly, then expects the agent to build on top of those edits (read current state first, don't overwrite or revert their changes). Confidence: 0.5
- Supplies exact asset snippets (e.g. official SVG markup) to be used verbatim rather than having the agent approximate them. Confidence: 0.45
- Cares about visual contrast/legibility of graphics (logos, icons) against the real page background and expects low-contrast cases to be fixed, not tolerated. Confidence: 0.45
- Wants official/brand artwork kept in its original colors — no recoloring or inverting to fit a background; prefers non-destructive fixes like a drop shadow/halo that leave the artwork's own colors untouched. Confidence: 0.5
