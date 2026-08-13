# Automated project grade — HTML Project 2 — Recipe article

GitHub grades this project without waiting for a KODE Ń VIBE reviewer.

## The pass rule

- **PASS — Nailed it:** every required check passes in one run.
- **REVISE — Keep building:** one or more required checks fail.

There is no averaging and no partial-pass score. Do not delete, skip, rename, or weaken a check. Fix the project, push again, and GitHub replaces the result with a new grade for that commit.

## Automatic learner flow

1. On the KODE Ń VIBE starter, choose **Use this template** to create your own repository.
2. Create an attempt branch, for example `git switch -c attempt/my-project`. Keep the untouched starter on `main`.
3. Build the acceptance checklist, commit, and push the attempt branch. GitHub Actions starts the grade automatically; opening or updating a pull request to `main` is graded too.
4. Open **Actions → Automated project grade**. Read the failed check names and logs if the result says **REVISE**.
5. When the job summary says **PASS — NAILED IT**, save that run link as evidence.

Every repository's `main` branch is intentionally quiet, so unfinished starter code does not send false failure alerts. Grading starts automatically when you push an attempt branch or open a pull request to `main`.

## Run the same grade locally

From the repository root, run:

```sh
node --test test/mastery.test.mjs
```

Every check must pass without skipping, deleting, or weakening a check.

- [ ] The recipe uses labelled navigation, landmarks, one article, and a coherent heading structure.
- [ ] Jump links resolve to real sections, while ingredients, method steps, and durations use suitable elements.
- [ ] The figure has a local image, useful alternative text, dimensions, a caption, and the supplied responsive image rule.

These checks cover selected functional and structural criteria. The individual test names are the grading rubric; a failed name identifies what to revise.

## Optional confidence check — not graded

No reviewer is required for the automated pass. These quick checks are still worth doing because code tests cannot see every visual, usability, or accessibility problem:

- [ ] Use only the keyboard to follow every jump link and return-to-start link; focus and destination are understandable.
- [ ] Temporarily break the image path and confirm that the remaining text still communicates every essential instruction.
- [ ] At 320 CSS pixels and 200% zoom, the recipe remains readable without page-level horizontal scrolling.

## Optional explain-back — not graded

Use these prompts to check your own understanding. They do not need a reviewer and they do not change the GitHub grade.

1. Why is this recipe an article, and how did you decide the order of its sections?
2. What information belongs in this image’s alt text, caption, and surrounding prose respectively?
3. How do the time elements help machines without making the visible wording worse for people?

## Evidence to keep

GitHub keeps the commit, logs, and grade automatically. Save only:

- the commit SHA;
- the successful Actions run URL; and
- one sentence about what you would improve next.

## Honest boundary

**PASS means every published requirement checked by this project passed on one revision.** It is formative evidence, not a certificate or proof of independent authorship. A learner controls their copy and can edit visible tests or workflows, and automation cannot prove complete usability, accessibility, durable understanding, or professional readiness. Keep the supplied checks unchanged if you want the result to remain meaningful.
