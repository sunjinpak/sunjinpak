---
layout: default
title: Quantitative Research Paper Guide
---

# Quantitative Research Paper Guide

This guide explains how to write a quantitative research paper in APA 7th Edition format.

---

## Sample Paper

Here is an example of a published quantitative research paper you can reference:

1. [CCSM Paper - Title Page with Author Info](https://drive.google.com/file/d/14dYnXbBPhbRauhTyaZCcpHwnoWSVWgE4/view?usp=sharing)
2. [CCSM Paper - Manuscript (Word)](https://drive.google.com/file/d/1ETW8oL05u2COOz6NoxquY6gmpS9x9U3Y/view?usp=sharing)

**Note:** The title page and manuscript are in separate files because academic journals require a "blind review" process, where reviewers do not see author information. When you write your own paper, combine them into one document with the title page (including author info) as the first page.

---

## Paper Structure

1. Title Page
2. Abstract
3. Introduction
4. Method
5. Results
6. Discussion
7. References
8. Tables and Figures

---

## 1. Title Page

- Paper title (bold, centered)
- Author name(s)
- Institutional affiliation
- Author note (optional)
- Running head (top of page)

**Example:**
```
The Impact of Leadership Style on Employee Well-Being

John Smith and Jane Doe
California State University, Bakersfield
```

**APA Sample Papers:**
- [APA Official Sample Papers](https://apastyle.apa.org/style-grammar-guidelines/paper-format/sample-papers)
- [Purdue OWL Sample Paper](https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/apa_sample_paper.html)

---

## 2. Abstract

- 150-250 words
- Single paragraph
- Summarize purpose, method, key findings, and conclusions
- Include Keywords

---

## 3. Introduction

### Components
1. **Opening** - Introduce the research topic
2. **Literature Review** - Review relevant prior research
3. **Research Gap** - Limitations of existing research
4. **Hypotheses** - Present research hypotheses

### Hypothesis Writing Examples

**Simple Direct Effect:**
```
Hypothesis 1: Variable A is positively related to Variable B.
```

**Mediation:**
```
Hypothesis 2: Variable B mediates the relationship between
Variable A and Variable C.
```

**Serial Mediation:**
```
Hypothesis 3: Variable A has an indirect effect on Variable D
through the sequential mediation of Variable B and Variable C.
```

---

## 4. Method Section

The Method section consists of the following subsections.

### 4.1 Participants

Information to include:
- Sample size (N)
- Demographics (age, gender, race/ethnicity)
- Recruitment method
- Inclusion/exclusion criteria

**Example:**
```
Participants were 115 working students recruited from a public
university in the western United States. Eligibility criteria
required that participants be currently employed and enrolled
in college courses at the time of the study. The sample was
80% female, with an average age of 24.91 years (SD = 6.98).
Regarding race and ethnicity, 55.7% identified as Hispanic or
Latino, 15.7% as White, 7.0% as Asian, 3.5% as Black or
African American, and 18.1% as multiracial or other.
Participants worked an average of 37.05 hours per week
(SD = 22.68) and were enrolled in an average of 14.20
credit hours (SD = 2.57).
```

### 4.2 Procedure

- Data collection method
- IRB approval statement
- Survey platform (e.g., Qualtrics)

**Example:**
```
Data were collected via an online survey hosted on Qualtrics.
Participants were recruited through the university's participant
pool. After providing informed consent, participants completed
measures assessing [describe measures]. All procedures were
approved by the university's Institutional Review Board.
```

### 4.3 Measures

For each measure:
- Variable name (bold)
- Source/citation
- Number of items
- Sample item
- Response scale
- Reliability (Cronbach's alpha)

**Example:**
```
**Job satisfaction.** Job satisfaction was measured using five
items from the Job Satisfaction Scale (Smith et al., 2020).
A sample item is "I am satisfied with my current job."
Responses were rated on a 5-point scale ranging from
1 (strongly disagree) to 5 (strongly agree; α = .89).

**Work engagement.** Work engagement was assessed using nine
items from the Utrecht Work Engagement Scale (Schaufeli et al.,
2006). A sample item is "At my work, I feel bursting with
energy" (α = .92).
```

### 4.4 Analytic Strategy

- Software/tools used
- Analysis methods
- Significance level criteria

**Example:**
```
Analyses were conducted using SPSS Version 28. First, we
computed descriptive statistics and bivariate correlations
among all study variables. Second, we assessed the reliability
of multi-item scales using Cronbach's alpha. Third, we tested
hypotheses using hierarchical ordinary least squares regression,
entering control variables in Step 1 and the focal predictor
in Step 2. Mediation was tested using PROCESS macro (Hayes, 2022)
with 5,000 bootstrap resamples.
```

---

## 5. Results Section

### 5.1 Preliminary Analyses

- Descriptive statistics summary
- Correlation descriptions
- Reference to Table 1

**Example:**
```
Means, standard deviations, reliabilities, and intercorrelations
among study variables are presented in Table 1. All multi-item
scales demonstrated acceptable internal consistency reliability
(α > .70). Consistent with our theoretical expectations,
Variable A was positively correlated with Variable B (r = .25,
p = .011) and Variable C (r = .26, p = .008).
```

### 5.2 Hypothesis Tests

For each hypothesis:
- Hypothesis number and prediction
- Statistical results (B, SE, t, p, CI)
- Support status

**Example:**
```
Hypothesis 1 predicted that Variable A would be positively
related to Variable B. After controlling for age, gender,
and tenure, Variable A was positively related to Variable B
(B = 0.36, SE = 0.12, t = 2.93, p = .004, 95% CI [0.12, 0.60]).
Hypothesis 1 was supported.
```

### 5.3 Mediation Results (if applicable)

**Example:**
```
Hypothesis 2 predicted that Variable B would mediate the
relationship between Variable A and Variable C. Results from
PROCESS Model 4 indicated that the indirect effect was
statistically significant (indirect effect = 0.11, SE = 0.05,
95% CI [0.04, 0.20]). Because the bootstrap confidence interval
excluded zero, Hypothesis 2 was supported.
```

---

## 6. Tables

### Table 1: Correlation Table

**Format:**
- Variable names
- M (Mean)
- SD (Standard Deviation)
- Correlations (lower triangle)
- Cronbach's alpha (diagonal, in parentheses)

**Example:**

| Variable | *M* | *SD* | 1 | 2 | 3 | 4 |
|----------|-----|------|---|---|---|---|
| 1. Age | 24.91 | 6.98 | — | | | |
| 2. Variable A | 2.91 | 1.08 | .05 | (.93) | | |
| 3. Variable B | 2.69 | 1.41 | .10 | .25* | — | |
| 4. Variable C | 3.19 | 1.22 | −.07 | .26** | .39** | (.94) |

*Note.* *N* = 105. Cronbach's alpha in parentheses.

\*\**p* < .01. \**p* < .05.

### Table 2: Regression Results

| Predictor | *B* (*SE*) | 95% CI | *p* |
|-----------|------------|--------|-----|
| Constant | 1.76 (0.47) | | < .001 |
| Variable A | 0.36 (0.12) | [0.12, 0.60] | .004 |
| *R*² | .143 | | |

---

## 7. APA Numbers and Statistics Formatting

### Basic Rules
- Omit leading zero for values that cannot exceed 1 (correlations, p-values): *r* = .25, *p* = .011
- Include leading zero for values that can exceed 1: *M* = 2.91, *SD* = 1.08
- Statistical symbols in italics: *M*, *SD*, *r*, *p*, *t*, *F*, *B*, *N*, *n*

### Statistical Reporting Formats

**Correlation:**
```
r = .25, p = .011
r = .39, p < .001
```

**t-test:**
```
t(103) = 2.93, p = .004
```

**Regression:**
```
B = 0.36, SE = 0.12, t = 2.93, p = .004, 95% CI [0.12, 0.60]
```

**Mediation (Bootstrap):**
```
indirect effect = 0.11, SE = 0.05, 95% CI [0.04, 0.20]
```

**R-squared:**
```
R² = .143, ΔR² = .074
```

---

## 8. References Format

**APA Reference Guides:**
- [APA Official Reference Examples](https://apastyle.apa.org/style-grammar-guidelines/references/examples)
- [Purdue OWL Reference Guide](https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/reference_list_basic_rules.html)

### Journal Article
```
Clark, M. A., Smith, R. W., & Haynes, N. J. (2020). The
    Multidimensional Workaholism Scale: Linking the
    conceptualization and measurement of workaholism.
    Journal of Applied Psychology, 105, 1281-1307.
    https://doi.org/10.1037/apl0000484
```

### Book
```
Hayes, A. F. (2022). Introduction to mediation, moderation,
    and conditional process analysis: A regression-based
    approach (3rd ed.). Guilford Press.
```

### Book Chapter
```
Smith, J. A., & Jones, B. C. (2021). Understanding workplace
    behavior. In C. D. Editor (Ed.), Handbook of organizational
    psychology (pp. 45-67). Academic Press.
```

---

## 9. Common Mistakes

1. **p-value notation error**
   - ❌ p = .000
   - ✅ p < .001

2. **Leading zero**
   - ❌ r = 0.25 (correlation)
   - ✅ r = .25
   - ✅ M = 2.91 (values > 1 include zero)

3. **Missing italics**
   - ❌ M = 2.91, SD = 1.08
   - ✅ *M* = 2.91, *SD* = 1.08

4. **Missing reliability**
   - Report α for all multi-item scales

5. **CI format**
   - ❌ CI = 0.12-0.60
   - ✅ 95% CI [0.12, 0.60]

6. **Inconsistent decimal places**
   - Keep consistent (usually 2 decimal places)

---

## 10. Checklist

### Method Section
- [ ] Sample size stated
- [ ] Demographics included (age, gender, race/ethnicity)
- [ ] Recruitment method described
- [ ] IRB approval mentioned
- [ ] Source cited for each measure
- [ ] Sample item provided
- [ ] Response scale described
- [ ] Cronbach's alpha reported

### Results Section
- [ ] Table 1 with descriptive statistics and correlations
- [ ] Results reported for each hypothesis
- [ ] Effect sizes included (R², ΔR²)
- [ ] Confidence intervals reported
- [ ] Hypothesis support status stated

### Tables
- [ ] Title for all tables
- [ ] Note section included
- [ ] Significance levels indicated (\*, \*\*)
- [ ] APA format followed

---

## Resources

- [APA Style 7th Edition Official Site](https://apastyle.apa.org/)
- [Purdue OWL APA Guide](https://owl.purdue.edu/owl/research_and_citation/apa_style/)
- [APA Sample Papers](https://apastyle.apa.org/style-grammar-guidelines/paper-format/sample-papers)

---

[← Back to Home](.)
