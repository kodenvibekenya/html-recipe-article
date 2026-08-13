# Mastery check — HTML Project 2 — Recipe article

“Nailed it” is a three-gate decision. You must pass **all three** gates; a green automated run alone is not mastery.

## Gate 1 — Automated project checks

From the repository root, run:

```sh
node --test test/mastery.test.mjs
```

Every check must pass without skipping, deleting, or weakening a check.

- [ ] The recipe uses labelled navigation, landmarks, one article, and a coherent heading structure.
- [ ] Jump links resolve to real sections, while ingredients, method steps, and durations use suitable elements.
- [ ] The figure has a local image, useful alternative text, dimensions, a caption, and the supplied responsive image rule.

These checks cover selected functional and structural criteria. They do **not** claim to judge visual quality, usability, or accessibility conformance.

## Gate 2 — Applicable manual browser and accessibility checks

- [ ] Use only the keyboard to follow every jump link and return-to-start link; focus and destination are understandable.
- [ ] Temporarily break the image path and confirm that the remaining text still communicates every essential instruction.
- [ ] At 320 CSS pixels and 200% zoom, the recipe remains readable without page-level horizontal scrolling.

Record the browser, viewport/zoom, input method, and any assistive technology used.

## Gate 3 — Explain back

Answer all three prompts in your own words. Each answer passes when it is accurate, points to concrete evidence in this project, and explains the reason or trade-off—not merely what a line says. A peer, mentor, or reviewer should ask one follow-up where an answer is unclear and record pass/revise for every prompt.

1. Why is this recipe an article, and how did you decide the order of its sections?
2. What information belongs in this image’s alt text, caption, and surrounding prose respectively?
3. How do the time elements help machines without making the visible wording worse for people?

## Evidence record

Keep this short record in an issue, pull request, or learning log:

- Commit checked:
- Automated command, date/time, and result:
- Manual check environment and result for each item (or the documented not-applicable reason):
- Explain-back reviewer and pass/revise result for prompts 1–3:
- Help, tools, examples, or references used:
- Remaining limitation or next improvement:

## Honest boundary

This is formative practice, not a certification or proof of independent authorship. The repository owner can edit both code and visible checks, so CI records evidence about one revision rather than guaranteeing mastery. Manual observations and explain-back review remain necessary, and no single project demonstrates complete accessibility or professional readiness.
