# Student volunteer orientation site: instructions

Quarto website for public health and injury epidemiology, written for high
school and college volunteers on the WalkSafe-AI project and any future
student volunteers. Owner: Alex Quistberg.

## Build
- Quarto is not on PATH. Use Positron's copy:
  `/Applications/Positron.app/Contents/Resources/app/quarto/bin/quarto render`
- Output goes to `docs/`, which GitHub Pages serves. Commit the `.qmd` files and `docs/` together.
- `quarto preview` for a local check before pushing. The site is public once pushed.

## Writing rules
- Audience is as young as high school. Plain words, short sentences, a worked
  example before any formula. College-level material goes in a
  "Go deeper" callout.
- Each module: "What you'll learn", body, "Why this matters for your work",
  a 5-question quiz (`.readiness-quiz` with JSON `quiz-data`), Navigate.
- **Never** put Street View or other Google imagery on the site (Google's terms).
  Use diagrams, the author's own photos, or public-domain images.
- **Never** name volunteers, and never include IP addresses, logins, tile
  ids or internal protocol documents.
- **Unpublished results stay off the site.** Worked examples use the made-up
  town "Riverton", labeled as made up.
- WalkSafe-AI status wording: Bogotá = demonstrated; Philadelphia = early
  prototype plus a measurement study; planned tools are not built.
- Older adults = 60+ (WHO). Never claim "highest death rate of any age group".
- Every number or citation from outside this project must be checked against
  its source before publishing. Mark unchecked ones with `<!-- VERIFY -->`.
