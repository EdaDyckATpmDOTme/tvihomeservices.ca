# Project rules — tvihomeservices.ca / trimlightvanisle.ca rebuilds

These sites are **exact duplicates** of two live originals
(`https://tvihomeservices.ca`, `https://trimlightvanisle.ca`), with only a
different visual theme and improved SEO. Treat the live sites as the source of
truth. These rules are binding and override any default instinct to work
faster by cutting corners.

## 1. Capture before building
Before creating or editing any page, fetch the corresponding live original and
record its exact structure: every heading, every paragraph of body copy, the
section order, all nav/dropdown items, every button/CTA, and all form fields.
Build nothing from memory or from a summary.

## 2. Reproduce, never invent
Copy the original's real wording. Do NOT generate plausible-sounding
replacement copy, do NOT compress or paraphrase sections, do NOT drop sections
or whole pages. Same info, same features, same order. The ONLY things allowed
to differ are the theme (colors/layout styling) and the SEO scaffolding.

## 3. Verify against the source before saying "done"
Diff each rebuilt page against its live original section by section. A
subagent's "built/pushed" self-report is NOT verification — check the actual
output. Nothing ships until every original section is present or a specific
omission is noted and justified.

## 4. Stay in scope; surface, don't decide
Do only what was asked. Do not add deploys, form backends, or other scope the
owner didn't request. If something is missing or ambiguous, ask — do not
silently substitute a value or quietly simplify.

## 5. Treat repeated instructions as unmet, not as new complaints
If the owner repeats a requirement, the requirement is not yet satisfied. Go
back and re-check the actual output against it, rather than patching the latest
surface symptom.

## Fixed facts
- Phone: **778.744.4004**
- Contact forms POST to: **https://formsubmit.co/info@trimlightvanisle.ca**
- TVI theme: navy `#1e3a5f` + teal `#0d9488`
- Trimlight theme: dark navy `#0f172a` + amber `#f59e0b`
- Real logos/images live in each site's `images/` dir (pulled from the
  originals). Use them — no placeholder art.
- Fix original typos silently (e.g. "Roff Moss Removal", "lanscape").
