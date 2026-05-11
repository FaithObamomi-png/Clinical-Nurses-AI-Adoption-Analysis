# AI Adoption Readiness Among Clinical Nurses in Nigeria
> Exploring AI perception and adoption readiness among 102 clinical nurses in Nigeria through an interactive Excel dashboard, to uncover what is truly standing between healthcare workers and effective AI integration.

---
## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Project Scope & Tools](#2-project-scope--tools)
3. [Data Workflow](#3-data-workflow)
8. [Analysis & Metrics](#8-analysis--metrics)
9. [Key Insights](#9-key-insights)
10. [Recommendations](#10-recommendations)
11. [Assumptions & Limitations](#11-assumptions--limitations)
12. [Future Enhancements](#12-future-enhancements)
13. [Deliverables](#13-deliverables)
14. [Author](#14-author)

---
## 1. Project Overview
Clinicians are at the center of every healthcare system, yet rarely at the center of conversations around the technologies being built for them. As AI integration grows more urgent in Nigeria's healthcare sector, one question kept standing out to me **are frontliners actually being prepared for this transition, or simply expected to adapt to systems built without them?**

This project analyzes AI perception and adoption readiness among clinical nurses in Nigeria's healthcare system.<br> The dataset was sourced from survey responses collected from 102 clinical nurses in a Federal Teaching Hospital in Nigeria, cleaned, structured, and analyzed in Microsoft Excel using Pivot Tables and Power Query, with an interactive dashboard built to allow dynamic exploration across demographic filters including age, gender, and years of experience.

Insights and recommendations are provided on the following key areas:

**Category 1:** AI Knowledge Levels Among Clinical Nurses <br>
**Category 2:** Adoption Readiness and Comfortability With AI Tools<br>
**Category 3:** Job Displacement Concerns<br>
**Category 4:** Perception of Institutional Support and Training on AI<br>

Despite 87 out of 102 nurses demonstrating moderate to high AI knowledge levels, 54% expressed fears about job displacement and a large proportion felt institutional support for AI integration was inadequate. Younger nurses (age 20-30) showed significantly higher readiness and comfortability with AI tools, pointing to workforce demographics as a variable implementation strategies cannot afford to ignore.

---
## 2. Project Scope & Tools
### Scope
| Dimension | Details |
|-----------|---------|
| **In Scope** |Survey responses from 102 clinical nurses in a single Federal Teaching Hospital in Nigeria, covering AI knowledge levels, adoption readiness, comfortability with AI tools, job displacement concerns, and perception of institutional support and training |
| **Out of Scope** |Other healthcare professional groups such as doctors, pharmacists, and lab scientists were excluded. The analysis focuses specifically on clinical nurses as a defined frontline group. Institutional data such as hospital AI budgets, and training records were also excluded as they were outside the scope of the study  |
| **Time Period** |Data collection spanned two months (January 2026 to March 2026) to account for variation in nursing shift patterns and ensure adequate response coverage across the workforce|
| **Granularity** | Each row represents a single nurse's survey response. Responses were categorized into positive and negative groupings across each variable to enable pattern analysis and meaningful comparison across demographic segments |

### Tools & Technologies
| Category | Tool(s) Used |
|----------|-------------|
| Data Storage |Microsoft Excel (.xlsx)|
| Data Processing |Microsoft Excel, Power Query|
| Analysis | Microsoft Excel, Pivot Tables, Response Categorization |
| Visualization | Microsoft Excel, Interactive Slicers, Charts |
| Version Control |GitHub |
| Documentation | Markdown, Medium|

---
## 3. Data Workflow
```
[Google Forms Survey]
      ↓
[Response Export to Microsoft Excel]
      ↓
[Data Selection, Scoring, Cleaning and Categorization]
      ↓
[Analysis via Pivot Tables and Demographic Segmentation]
      ↓
[Interactive Excel Dashboard with Slicers and Charts]
```

1. **Source:** Single Google Forms questionnaire administered to 102 clinical nurses across rotating shifts in a Federal Teaching Hospital in Nigeria. Data collected over two months, January to March 2026.
2. **Ingestion:** Completed responses were exported directly from Google Forms into Microsoft Excel as a single worksheet containing 102 rows, with one row per nurse and each column mapped to a survey variable.
3. **Cleaning:** Inconsistent entries across categorical variables were resolved. Only variables directly aligned with the four project objectives were retained, with out-of-scope survey questions excluded from the analysis entirely.
4. **Transformation:**  The knowledge section questions were scored per respondent and aggregated into a composite score, then categorized into three tiers: High, Moderate, and Low. Responses across all remaining variables were categorized, and demographic variables including age and years of experience were binned into defined ranges to support segmentation.
5. **Analysis:** Descriptive statistics and frequency distributions were generated across all four variable categories. Demographic segmentation by age group and years of experience was applied to identify meaningful differences in readiness, comfortability, and perception across the workforce.
6. **Output:** An interactive Excel dashboard with dynamic slicers, supported by a published Medium article and this GitHub project documentation.

---
## 8. Analysis & Metrics

<!--
  Explain what you measured and how - before you share what you found.

  WHAT GOOD LOOKS LIKE:
  Metric: "Customer Return Rate"
  Definition: "Number of transactions flagged as returns divided by total
               transactions, calculated at product-category and regional grain."
  Why It Matters: "Return rate - not sales volume - was hypothesised to
                  explain regional revenue gaps. This metric tests that hypothesis."

  WHAT TO AVOID:
  ❌ Defining a metric only in code: SUM(returns) / COUNT(transaction_id)
     That's an implementation. Write the plain-language definition here.
     Both belong in your project - the definition in the README,
     the implementation in the code.
-->

### Analytical Approach

[Describe how you approached the analysis. Were you exploring patterns? Testing a hypothesis? Building and validating a pipeline? Be honest about your method - exploratory work is valid, just call it that.]

### Key Metrics Defined

| Metric | Plain-Language Definition | Why It Matters |
|--------|--------------------------|----------------|
| `[Metric 1]` | [What it measures, in one sentence] | [What decision or question it answers] |
| `[Metric 2]` | [What it measures, in one sentence] | [What decision or question it answers] |
| `[Metric 3]` | [What it measures, in one sentence] | [What decision or question it answers] |

### Methods Used

- [e.g., Descriptive statistics - distribution, central tendency, outlier detection]
- [e.g., Trend analysis across [time period]]
- [e.g., Segmentation / group comparison by [dimension]]
- [e.g., Correlation analysis between [variable A] and [variable B]]
- [e.g., SQL window functions for [specific aggregation]]
- [e.g., Custom aggregation or transformation logic in [tool]]

---

## 9. Key Insights

<!--
  Findings + implications. Not just what happened - what it means.

  WHAT GOOD LOOKS LIKE:
  ✅ "Return rates, not sales volume, explain Region A's underperformance.
      Region A's return rate on home goods was 34% - more than double the
      company average. Revenue was not lost at the point of sale; it was
      lost post-sale through refunds. This points to a fulfilment or
      product quality issue specific to that region, not a demand problem."

  WHAT TO AVOID:
  ❌ "Region A had lower revenue than other regions in Q4."
     (That's an observation. It describes what happened.
      An insight says what it means and where to look next.)

  Aim for 3–6 insights. Quality over quantity.
-->

**Insight 1: [Short descriptive headline]**
[What you found + what it suggests. One short paragraph.]

**Insight 2: [Short descriptive headline]**
[What you found + what it suggests.]

**Insight 3: [Short descriptive headline]**
[What you found + what it suggests.]

**Insight 4 (if applicable): [Short descriptive headline]**
[What you found + what it suggests.]

---

## 10. Recommendations

<!--
  Action-oriented. Addressed to a real audience.
  Tied explicitly to the insight that supports each one.

  WHAT GOOD LOOKS LIKE:
  Priority: High
  Recommendation: "Conduct a fulfilment audit for home goods deliveries
                   in Region A - specifically investigating whether returns
                   correlate with a particular warehouse, carrier, or SKU batch."
  Based On: Insight 1 - return rate anomaly in Region A
  Owner: Operations / Supply Chain team

  WHAT TO AVOID:
  ❌ "Improve the return rate."
     (Not actionable. Doesn't say who, how, or where to start.)
  ❌ "Further analysis is needed."
     (This is a placeholder, not a recommendation.)
-->

| Priority | Recommendation | Based On | Suggested Owner |
|----------|---------------|----------|-----------------|
| High | [Specific, actionable step] | [Insight it comes from] | [Who should act] |
| Medium | [Specific, actionable step] | [Insight it comes from] | [Who should act] |
| Low | [Exploratory or longer-term suggestion] | [Insight it comes from] | [Who should act] |

---

## 11. Assumptions & Limitations

<!--
  WHAT GOOD LOOKS LIKE:
  Assumption: "Transaction records were assumed to be complete for all five regions.
               No validation was performed against source system record counts."
  Limitation: "The analysis cannot distinguish between returns initiated by
               the customer vs. returns initiated by the business (e.g., recalls).
               If business-initiated returns are concentrated in Region A, the
               return rate finding may reflect a policy decision, not a quality issue."

  WHAT TO AVOID:
  ❌ Leaving this section blank or writing "None known."
     Every project has limitations. Documenting them is a sign of
     analytical maturity - not a confession of failure.
-->

### Assumptions
- [What did you treat as true without being able to verify?]
- [What simplifications did you make for scope or feasibility?]
- [What domain rules or definitions did you accept as given?]

### Limitations
- [What gaps exist in the data?]
- [What analysis was out of scope but could affect interpretation?]
- [What would a more rigorous version of this project include?]
- [Are there known biases in the data source or collection method?]

> *The goal here is pre-emptive Q&A. What would a thoughtful skeptic push back on? Document the answer here, before they ask.*

---

## 12. Future Enhancements

<!--
  WHAT GOOD LOOKS LIKE:
  ✅ "Automate the monthly data pull from the POS export folder using
      a scheduled Python script, replacing the current manual process."
  ✅ "Expand the return rate analysis to include carrier-level data,
      which was unavailable in this dataset but exists in the logistics system."

  WHAT TO AVOID:
  ❌ "Add a machine learning model."
     (Vague, and disconnected from the actual findings of this project.)
  ❌ Listing aspirational features that don't follow logically from the work.
-->

- [ ] [Enhancement 1 - specific and traceable to a real gap in this project]
- [ ] [Enhancement 2]
- [ ] [Enhancement 3]
- [ ] [Enhancement 4]

---

## 13. Deliverables

| Deliverable | Description | Location |
|-------------|-------------|----------|
| [Name] | [What it contains] | [`/path/to/file`] |
| [Name] | [What it contains] | [`/path/to/file`] |
| [Name] | [What it contains] | [`/path/to/file`] |

---

## 14. Author

**[Your Name]**
[Your role or title - current or target]

- 🔗 [LinkedIn URL]
- 💼 [Portfolio or GitHub profile URL]
- 📧 [Email - optional]

---

*Last updated: [Month YYYY]*
*If this template helped you, consider starring the repository.*
