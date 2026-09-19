# AUDIT-page.md — Session 9 Portfolio

**Scope:** `index.html` + `style.css`
**Purpose:** Verify that every piece of content on the portfolio page is true, and that no fabricated personal information or unverified links are present.

## Content Audit

| Content | True? | Evidence / What was removed |
|---|---|---|
| Name: Akshita Chhabra | Yes | My real name |
| About section | Yes | Written using my actual background |
| Prompt Engineering | Yes | Skill I have learned/practiced |
| Artificial Intelligence & Machine Learning | Yes | Skill I have learned/practiced |
| Exploratory Data Analysis (EDA) | Yes | Skill I have learned/practiced |
| Machine Learning Model Development | Yes | Skill I have learned/practiced |
| Data Visualization | Yes | Skill I have learned/practiced |
| Student Attrition Prediction | Yes | My actual project |
| NoBrokerage.com Chatbot | Yes | My actual project |
| Email / Phone / Social links | N/A | Do not include anything that is not real |
| GitHub project links | Verify | Keep only actual working repository links |

**Note on GitHub project links:** `index.html` currently contains no GitHub or other external repository links (confirmed by scanning the file). Nothing was removed because nothing was present. If/when real repository links for **Student Attrition Prediction** or **NoBrokerage.com Chatbot** are added, they must be verified as live, working URLs before publishing — no placeholder or invented links.

## Validation

| Check | Result |
|---|---|
| Nu HTML Checker (vnu) | 0 errors, 0 warnings — `html5validator --root . --also-check-css` run against `index.html` and `style.css` |
| Narrow-width check (~375px) | Confirmed via CSS media queries in `style.css` at `max-width: 600px` and `max-width: 400px`, covering the ~375px viewport |
| HTML and CSS separate | Confirmed — all markup in `index.html`, all styling in `style.css` |
| No inline CSS | Confirmed — no `style="..."` attributes found in `index.html` |

## Status

All listed content items are verified true or explicitly marked N/A/Verify per the table above. No personal contact information or social links are included. No GitHub links are present, so none required verification at this time.
