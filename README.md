# HTML Project 2 — Recipe article

Mark up a complete mandazi recipe that still makes sense when its image does not load.

Companion notes: [HTML notes](https://kodenvibe.tech/notes/html/).

## Start your own copy

On GitHub, select **Use this template** → **Create a new repository**, choose whether it will be public or private, then clone your new repository and edit that copy.

**Time-box:** 60 minutes<br>
**Prerequisite:** HTML Foundations Lesson 2 and Project 1<br>
**After-lesson milestone:** you can use landmarks, descriptive links, an article, and an accessible image decision.

## Start

Open `index.html`. A local illustration is supplied in `assets/mandazi.svg`, and `styles.css` contains only a supplied responsive-image safeguard; the lesson task remains HTML. Keep the page dependency-free. Work through the `TODO` comments, then test the image's alternative text by temporarily misspelling its path.

## Acceptance checklist

- [ ] The page has `header`, labelled `nav`, one `main`, and `footer` landmarks.
- [ ] The recipe is a self-contained `<article>` with one `<h1>` and ordered subsections.
- [ ] Skip/jump links point to real IDs and their text describes the destination.
- [ ] The figure uses the local image, useful `alt`, explicit dimensions, and a caption.
- [ ] The supplied image rule allows the illustration to shrink without distorting it.
- [ ] Ingredients use an unordered list; method steps use an ordered list.
- [ ] Preparation and cooking durations use `<time datetime="…">`.
- [ ] Removing or breaking the image does not remove essential instructions.
- [ ] Every link works when `index.html` is opened directly.

## Finish

Validate your HTML, then use only the keyboard to follow each link.

<!-- mastery-kit:start -->
## Get your automatic project grade

1. [Create your own copy](https://github.com/kodenvibekenya/html-recipe-article/generate) from this template.
2. Read [MASTERY.md](MASTERY.md), then create an attempt branch:

   ```sh
   git switch -c attempt/my-project
   ```

3. Build the project and run the same check GitHub uses:

   ```sh
   node --test test/mastery.test.mjs
   ```

4. Commit and push the attempt branch:

   ```sh
   git add .
   git commit -m "Complete project attempt"
   git push -u origin attempt/my-project
   ```

GitHub Actions grades every pushed attempt automatically. **PASS — NAILED IT** means every required check passed. **REVISE — KEEP BUILDING** means the run shows what to fix before you push again. You do not need the KODE Ń VIBE owner to review or start anything; the template's `main` branch stays quiet on purpose.

The [free grading guide](https://kodenvibe.tech/notes/mastery/) explains the result and its limits.
<!-- mastery-kit:end -->
