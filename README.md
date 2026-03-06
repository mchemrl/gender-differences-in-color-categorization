## Gender Differences in Color Categorization

Final research project for **COG260 – Cognitive Science** at the University of Toronto.
This study analyzes gender differences in colour naming using data from the **World Color Survey (WCS)**.
We inspect whether female speakers categorize colours more consistently than male spaekers in regions of colour space where naming disagreement is highest.

---

## Overview

Colour naming varies across languages and cultures, but prior work has also showed gender-based differences in color categorizarion. In particular, women were usually observed using richer and consistent colour vocabularies. 
This study tests whether female speakers truly are more consistent, specifically **in high=boundary colour regions**, where speakers within the same language disagree the most.

## Research questions
Do women partition ambiguous colour spaces more consistently than men? We focus on unstable **boundary regions**, having chips with the most disagreement.

## Hypotheses

We test four hypotheses:

**H1:** Female entropy = Male entropy  
(no gender difference)

**H2:** Female entropy < Male entropy  
(female speakers are more consistent)

**H3:** JS divergence between genders is higher in boundary regions

**H4:** Female agreement > Male agreement at boundary chips

All hypotheses are evaluated using **permutation tests**.

## Reproducibility

The analysis is fully reproducible using the provided notebook and helper functions.

Clone the repository

```bash
git clone https://github.com/mchemrl/gender-differences-in-color-categorization.git
cd repo-name
