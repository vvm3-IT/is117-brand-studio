# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 merged; full checks passed; reconciled learning record reviewed and approved.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Kept and merged into `main` through PR #2 after learner instruction “ok merge it”; verified merge commit `fdd8e06e756bd05af52f4cb574a97eb15e90a0cb`.
- Next step: Submit the repository URL in Canvas. Publishing remains optional.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                | Secondary audience                                                          |
| ------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Person in a concrete situation        | Bodybuilder going to the gym                                    | Beginner going to the gym                                                   |
| Goal or meaning they seek             | Quiet dedication; let consistent effort speak                   | Motivation to keep showing up                                               |
| Concern before choosing               | Not chosen yet                                                  | Not chosen yet                                                              |
| What the page should help them decide | Whether the brand reflects quiet dedication (AI interpretation) | Whether the brand feels encouraging (AI interpretation)                     |
| Evidence or assumption                | Learner hypothesis; not validated research                      | AI-proposed situation; learner suggested motivation; not validated research |

## Early brand brief

| Decision                                 | Agreement                                                                                                                 |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Brand name                               | Quiet Reps                                                                                                                |
| One-sentence promise                     | A quiet reminder to show up and put in the work.                                                                          |
| Primary archetype: the brand's character | Hero — effort, courage, improvement; AI-proposed and accepted                                                             |
| Three voice traits                       | Calm, determined, encouraging; AI-proposed and accepted                                                                   |
| One example line in this voice           | Show up. Put in the reps. (AI-proposed example)                                                                           |
| Learner's predicted audience effect      | “it would give a very chill vibe”                                                                                         |
| Visual preference                        | Softer colors; postmodernist layered direction selected. Exact palette supplied by AI and included in the approved build. |
| Agreed optional interaction              | Choose a training intention, such as “Stay consistent”; learner reason: “it would motivate them”                          |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                        | Agreement or evidence                                                                                                                                                                                                                                                                                                             |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action          | Show up. Put in the reps. / A quiet reminder to show up and put in the work. / Choose your size                                                                                                                                                                                                                                   |
| Modernist preview                           | [Preview](public/explorations/modernist.html); Josef Müller-Brockmann, Musica Viva, 1958, [MoMA](https://www.moma.org/collection/works/7233/). Museum image inspected; geometric field, repeated squares, compact type. Grid, repeated marks and flat fields adapted; annotations and risks accompany preview.                    |
| Postmodernist preview                       | [Preview](public/explorations/postmodernist.html); Wolfgang Weingart, The Swiss Poster 1900–1984, 1983, [LACMA](https://collections.lacma.org/object/207620). Museum image inspected; overlapping halftone fields, mixed forms and type. Layered paper treatment and mixed type adapted; annotations and risks accompany preview. |
| Chosen direction and reason                 | Learner selected the postmodernist layered shirt. Later explanation: the design looks more advanced and cleaner, giving the website a cooler and more comfortable feel. This is the learner’s predicted visitor impression, not customer research.                                                                                |
| Original SVG logo                           | [Wordmark](public/assets/wordmark.svg): AI-created Q and repeated bars with Quiet Reps type, included in the overall approved build. No separate logo-specific comment was collected. No trademark clearance claimed.                                                                                                             |
| Monochrome and small-size presentations     | Shared single-color SVG at 110px and 190px in the live guide; header at 150px, mobile at 130px.                                                                                                                                                                                                                                   |
| Logo review                                 | Agent inspected header and one-color guide variants at navigation and 110px sizes. Learner approved the overall site; no separate logo-specific observation recorded.                                                                                                                                                             |
| Shared palette, typography, spacing, assets | [Shared CSS](public/styles.css), Georgia display, system sans-serif body, warm paper, sage and lavender; original white-shirt asset retained. Softer colors agreed; exact values and implementation supplied by AI.                                                                                                               |

## Ethical persuasion

These are AI-proposed implementations, not independently chosen learner explanations or proven conversion outcomes. The learner approved a voluntary intention chooser and said it would motivate visitors.

| Principle                  | Actual copy or interaction                                                                                                      | Visitor benefit / factual support                                                                                                            |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Reciprocity                | Free pre-session ritual: pause, name one reason to show up, carry that thought into the session.                                | Offers a small tool without purchase, sign-up, or personal information. Usefulness is a hypothesis.                                          |
| Commitment and consistency | Optional intention selector and response carrying the chosen intention forward, with shirt exploration as an optional reminder. | A voluntary prior intention precedes the invitation; selection never adds an item. Required size selection is not counted as this principle. |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                                                        | Issue / PR                                                                                                                               | Verification                                                                                                                                               |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | public/index.html; public/styleguide.html; public/styles.css; public/assets/wordmark.svg; public/shop.js; public/explorations/; tests/browser/studio.spec.js | [Issue #1](https://github.com/vvm3-IT/is117-brand-studio/issues/1); [merged PR #2](https://github.com/vvm3-IT/is117-brand-studio/pull/2) | [Final feature checks passed](https://github.com/vvm3-IT/is117-brand-studio/actions/runs/41761875352): formatting, lint, 7 server tests, 12 browser tests. |

- **Merge:** Learner instructed “ok merge it”; PR #2 merged into main at `fdd8e06e756bd05af52f4cb574a97eb15e90a0cb`.
- **Agent review:** Inspected storefront, guide and studio at desktop and 375px widths, including the original one-color logo variants. Confirmed missing-size feedback leaves bag count 0, valid M adds one shirt, and intention selection changes the message without changing the bag count. Browser tests include axe checks; passing these is not proof of complete accessibility or brand fit.
- **Learner observations:** Reported that selecting a size adds the shirt to the demo bag. Later confirmed using the keyboard to select size and add to bag, and reported that everything looked good in mobile view. Approved the overall result. Keep the layout based on those reports and the passing checks.
- **Actual test discussed:** `tests/server.test.mjs`, “returns 404 for missing files and private project files,” requests `/does-not-exist`, `/.env`, `/README.md`, `/docs/assessment.md` and two encoded attempts to reach `package.json` outside the public folder. Every response must have status 404. This passed. The assistant initially used SPEC.md as an illustrative example; that file is not one of this test’s inputs.
- **Test reasoning:** Learner initially answered “idk”; after an assistant hint about private files, learner explained: “It can possibly reveal sensitive or unauthorized information which should definitely be prevented.” This connects the 404 assertions to preventing unintended file disclosure; explanation was assisted, not independent.
- **Review and submission:** The learner reviewed and approved the reconciled LEARNING.md, including later observations and reasoning, and authorized its commit/push. Canvas submission is not verified. No live deployment is claimed.

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
