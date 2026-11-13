# Sources used in the deck

Found by three Sonnet research agents on 13 Nov 2026. I spot-checked the Apple HIG entry myself.

Status values:
- **Verified**: an agent fetched the page and it matched the claim.
- **Metadata**: the DOI or bibliographic record was confirmed, but the full text was paywalled or blocked.
- **Book**: cited by title and edition, with no URL checked.

Undated platform documentation shows the date it was accessed.

## Slide 12: why it is a problem for the user

| # | Term used | Source | Year | URL | Status |
|---|---|---|---|---|---|
| 1 | In-context permission request | Android Developers (Google), "Request runtime permissions" | accessed 2026-11-13 | https://developer.android.com/training/permissions/requesting | Verified |
| 1 | | Apple, Human Interface Guidelines, "Privacy" ("Avoid requesting permission at launch…") | accessed 2026-11-13 | https://developer.apple.com/design/human-interface-guidelines/privacy | Verified through Apple's JSON mirror of the page |
| 1 | | Kendrick, Nielsen Norman Group, "Five Mistakes in Designing Mobile Push Notifications" | 2018 | https://www.nngroup.com/articles/push-notification/ | Verified |
| 2 | Cost of interruption | Mark, Gudith & Klocke, "The Cost of Interrupted Work: More Speed and Stress", CHI '08 | 2008 | https://dl.acm.org/doi/10.1145/1357054.1357072 | Metadata (ACM returned 403) |
| 2 | Overlay overload | Moran, Nielsen Norman Group, "Overlay Overload" | 2021 | https://www.nngroup.com/articles/overlay-overload/ | Verified |
| 3 | Information scent | Budiu, Nielsen Norman Group, "Information Scent" | 2020 | https://www.nngroup.com/articles/information-scent/ | Verified |
| 3 | | Pirolli & Card, "Information foraging", Psychological Review 106(4) | 1999 | https://doi.org/10.1037/0033-295X.106.4.643 | Metadata |
| 4 | Habituation | Böhme & Köpsell, "Trained to accept? A field experiment on consent dialogs", CHI '10 | 2010 | https://fis.tu-dresden.de/portal/en/publications/trained-to-accept-a-field-experiment-on-consent-dialogs(b9864931-8f8a-4b69-b2e4-7f546272b0fa).html | Verified (university record) |
| 4 | | Anderson, Vance, Kirwan, Jenkins & Eargle, "From Warning to Wallpaper", JMIS 33(3) | 2016 | https://scholarsarchive.byu.edu/facpub/1955 | Verified (university record) |
| 5 | Consistency | Nielsen, Nielsen Norman Group, "10 Usability Heuristics", heuristic 4 | 1994, reviewed 2024 | https://www.nngroup.com/articles/ten-usability-heuristics/ | Verified |
| 5 | Motion shows spatial relationships | Google, Material Design (v1), "Material motion" | legacy spec, accessed 2026-11-13 | https://m1.material.io/motion/material-motion.html | Verified, legacy |
| 6 | Foot in the door | Freedman & Fraser, "Compliance without pressure: The foot-in-the-door technique", JPSP 4(2) | 1966 | https://doi.org/10.1037/h0023552 | Metadata |
| 6 | Commitment and consistency | Cialdini, *Influence: The Psychology of Persuasion*, revised edition, Harper Business, ISBN 9780061241895 (first published 1984) | 1984 / rev. | none | Book |
| 7 | Goal-gradient effect | Kivetz, Urminsky & Zheng, "The Goal-Gradient Hypothesis Resurrected", Journal of Marketing Research 43(1) | 2006 | https://doi.org/10.1509/jmkr.43.1.39 | Metadata |
| 7 | | Hull, "The goal-gradient hypothesis and maze learning", Psychological Review 39 | 1932 | https://doi.org/10.1037/h0072640 | Metadata |

Caveats shown on the slide:
- **Row 4 (habituation):** the studies are about security warnings and consent dialogs, so applying them to Claim buttons is an analogy.
- **Row 6:** the claim that asking after a reward beats asking before is labelled as my hypothesis. No source tests that order.
- **Row 7:** "strongest pull" is labelled as my read, not a finding.

## Slides 19 and 21: precedents and the open question

| Used for | Source | Year | URL | Status |
|---|---|---|---|---|
| Ask in context, benefit first (slide 19) | Android Developers, "Request runtime permissions" | accessed 2026-11-13 | https://developer.android.com/training/permissions/requesting | Verified |
| One card that points at the next step (slide 19) | LinkedIn Help, "Use the profile level meter to update your profile" | undated, accessed 2026-11-13 | https://www.linkedin.com/help/learning/answer/391 | Verified |
| Paying for a permission (slide 21) | Apple, Human Interface Guidelines, "Privacy" | accessed 2026-11-13 | https://developer.apple.com/design/human-interface-guidelines/privacy | Checked by me. "Don't offer incentives" sits in the app-tracking section. I found no such rule for notifications. |

## Considered and not used

| Term or source | Why it was left out |
|---|---|
| Goal shielding (Shah, Friedman & Kruglanski 2002) | Wrong fit. It describes a person's own goal suppressing their competing goals, not interruptions from the interface. |
| Change blindness (Budiu, NN/g 2018) | Weak fit. Seven surfaces are noticed, not missed. |
| Variable reward (Skinner; Eyal, *Hooked*, 2014) | Weak fit. A known next reward is predictable, which is the opposite of variable. |
| "Value before commitment", "permission priming", "dialog fatigue", "reward visibility" | Industry paraphrases with no citable definition. Plain wording is used instead. |
| Rosala, NN/g 2019, "3 Design Considerations for Effective Mobile-App Permission Requests" | Relevant, but its percentages come second-hand from other studies. Cut, to keep the deck free of numbers I could not trace. |
| Duolingo blog: streak changes (Yu, 2020) and milestone animation (Hartfelder, 2022) | Real and relevant, but they are another company's metrics. Kept out of the deck. |
| Starbucks progress to next star | The primary source could not be reached. |
| Material Design 3 snackbar, bottom-sheet and motion pages | Rendered with JavaScript, so their content was not verified. |

## Observed in the recording

Every timestamp, label and price on slides 6 to 11 and 18 comes from Dimi's recording. The same goes for "Games and apps pay us to find real players" at 00:40. The recording was made on Android, Samsung, 13 Nov 2026, and is documented in `docs/ux-case.md` sections 2 and 4.
