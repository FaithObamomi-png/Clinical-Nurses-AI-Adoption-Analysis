# AI Adoption Readiness Among Clinical Nurses in Nigeria
> Exploring AI perception and adoption readiness among 102 clinical nurses in Nigeria through an interactive Excel dashboard, to uncover what is truly standing between healthcare workers and effective AI integration.

---
## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Dashboard Preview](#2-dashboard-preview)
3. [Project Scope & Tools](#3-project-scope--tools)
4. [Data Workflow](#4-data-workflow)
5. [What the Data Revealed](#5-what-the-data-revealed)
6. [Assumptions & Limitations](#6-assumptions--limitations)
7. [Author](#7-author)

---
## 1. Project Overview
Clinicians are at the center of every healthcare system, yet rarely at the center of conversations around the technologies being built for them. As AI integration grows more urgent in Nigeria's healthcare sector, one question kept standing out to me **are frontliners actually being prepared for this transition, or simply expected to adapt to systems built without them?**

This project analyzes AI perception and adoption readiness among clinical nurses in Nigeria's healthcare system.<br> The dataset was sourced from survey responses collected from 102 clinical nurses in a Federal Teaching Hospital in Nigeria, cleaned, structured, and analyzed in Microsoft Excel using Pivot Tables and Power Query, with an interactive dashboard built to allow dynamic exploration across demographic filters including age, gender, and years of experience.

Insights and recommendations are provided on the following key areas:

**Category 1:** AI Knowledge Levels Among Clinical Nurses <br>
**Category 2:** Adoption Readiness and Comfortability With AI Tools<br>
**Category 3:** Perception of AI Across Clinical Experience Levels<br>
**Category 4:** Job Displacement Concerns<br>
**Category 5:** Perception of Institutional Support and Training for AI Integration<br>

Despite 87 out of 102 nurses demonstrating moderate to high AI knowledge levels, 54% expressed fears about job displacement and a large proportion felt institutional support for AI integration was inadequate. Younger nurses (age 20-30) showed significantly higher readiness and comfortability with AI tools, pointing to workforce demographics as a variable implementation strategies cannot afford to ignore.

---
## 2. Dashboard Preview
Below is a snapshot of the interactive dashboard developed to analyze AI adoption readiness among clinical nurses in Nigeria
<p align="center">
  <img src="visuals/Clinical Nurses AI Analysis Dashboard.png" width="850"/>
  </p>
    
[Explore the full Interactive Dashboard here](https://1drv.ms/x/c/3CBB0028DAB7590A/IQBivp5j6P01SKkDEgpJQ15gAaKsk_I9OH-af3NtuZr3Vr8?e=w8Yxe3)


---
## 3. Project Scope & Tools
### Scope
| Dimension | Details |
|-----------|---------|
| **In Scope** |Survey responses from 102 clinical nurses in a single Federal Teaching Hospital in Nigeria, covering AI knowledge levels, adoption readiness, Prcepton of AI, job displacement concerns, and perception of institutional support and training |
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
| Documentation | Markdown|

---
## 4. Data Workflow
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
3. **Cleaning:** Inconsistent entries across categorical variables were resolved. Only variables directly aligned with the five project objectives were retained, with out-of-scope survey questions excluded from the analysis entirely.
4. **Transformation:**  The knowledge section questions were scored per respondent and aggregated into a composite score, then categorized into three tiers: High, Moderate, and Low. Responses across all remaining variables were categorized, and demographic variables including age and years of experience were binned into defined ranges to support segmentation.
5. **Analysis:** Descriptive statistics and frequency distributions were generated across all four variable categories. Demographic segmentation by age group and years of experience was applied to identify meaningful differences in readiness, comfortability, and perception across the workforce.
6. **Output:** An interactive Excel dashboard with dynamic slicers, supported by a published Medium article and this GitHub project documentation.

---
## 5. What the Data Revealed
### Most Nurses Already Know About AI.But Knowing Is Not the Same as Being Ready
> 44 nurses demonstrated high AI knowledge levels, 43 moderate, and only 15 low, meaning 85 out of 102 nurses already had moderate to high AI knowledge levels.
<p align="center">
  <img src="visuals/AI knowledge levels.png" width="550"/>
  </p>
This immediately challenged a common assumption: that healthcare workers in Nigeria are largely unfamiliar with AI. Awareness is already growing, which means the more urgent conversation may no longer be about introducing AI to the workforce but may now be about what comes after awareness. Practical integration, institutional support, and building the confidence to actually use these tools in daily clinical practice are important.

### Younger Nurses Were Significantly More Ready and Comfortable With AI Tools
> Nurses in the 20–30 age group showed the highest readiness and comfortability with AI tools, with a noticeably more positive response compared to older age groups. Readiness declined progressively across the 30–40, 40–50, and above 50 age groups, where negative responses were more dominant.
<p align="center">
  <img src="visuals/Readiness for AI adoption.png" width="550"/>
  </p>
This pattern likely reflects stronger baseline familiarity with digital technologies among younger nurses but the more important implication is practical. Readiness is not evenly distributed across the workforce, and a uniform rollout strategy will not serve a team where different groups are starting from very different places. Effective implementation will require training and onboarding approaches tailored to where each demographic group actually is, not where we assume they should be.

### More Experience Did Not Mean More Openness to AI
> Nurses with 2–10 years of clinical experience showed the most mixed perception toward AI, with a relatively higher proportion of positive responses compared to other experience groups. Nurses with 11–20 and 21–30 years of experience as well as those with less than one year of experience showed predominantly negative perception.
<p align="center">
  <img src="visuals/AI Perception against clinical experience.png" width="550"/>
  </p>
This is a revealing pattern. More experienced nurses, who arguably have the deepest understanding of clinical workflows, were also among the most skeptical about AI integration. This may reflect a clearer awareness of the practical challenges AI would introduce into established clinical routines, and it reinforces the need for implementation strategies that genuinely engage experienced staff rather than simply deploying technology around them.

### Job Displacement Concerns Were Lower Than Expected
> 92% of respondents showed a negative perception of job displacement risk, meaning the majority did not fear that AI would cost them their jobs. Only approximately 8% expressed concern about displacement.
<p align="center">
  <img src="visuals/Job displacement Concerns.png" width="550"/>
  </p>
This was one of the more surprising findings in the dataset. It suggests that clinical nurses in this institution may already have a grounded understanding of AI as a supportive tool rather than a replacement threat. That is actually a strong foundation for implementation. A workforce that is not paralyzed by fear of replacement may be significantly more open to engaging with AI tools when the right support structures are in place.

### Awareness Was High. Institutional Support Was Not
> 54% of respondents disagreed that adequate technical support and training for AI integration was available, while 46% agreed it was available.
<p align="center">
  <img src="visuals/Availability of Support and Training  for AI integration.png" width="550"/>
  </p>
This was the most important finding in the entire project. Despite relatively high awareness levels and lower than expected job displacement fears, more than half of nurses did not feel the institutional infrastructure to support AI adoption was there. Willingness without support is not adoption. It is stalled potential. The more urgent question may no longer be whether nurses are ready for AI. It may be whether healthcare institutions are genuinely ready to support their people through this transition. Because the data suggests the bottleneck may not be the individuals, it may be the institutions.

---
## 6. Assumptions & Limitations
### Assumptions
1. Respondents answered all survey questions honestly and to the best of their knowledge.
2. The sample, though drawn from a single institution, was considered reasonably representative of the nursing workforce within that hospital.
3. Responses collected across the two-month period were treated as reflecting a stable perception, with no significant external events assumed to have shifted opinions during data collection.
4. Categorization of responses into positive and negative groupings was applied consistently across all variables.
### Limitations
1. Findings are based on a single Federal Teaching Hospital and may not represent clinical nurses across other institutions or regions in Nigeria.
2. The sample size of 102 limits how broadly the findings can travel. A larger multi-institution study would surface patterns this dataset cannot.
3. Future versions would include open-ended qualitative questions to capture not just what nurses felt but why.

---
## 7. Author
#### Faith Obamomi
A data analyst with a strong interest in healthcare analytics, public health, and data-driven decision. This project reflects a core belief that data should do more than describe what happened. It should help people make better decisions.
- 🔗 [Connect with me on Linkedin](https://www.linkedin.com/in/faithobamomi/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bobji4OhATZCfREtzgPH5kQ%3D%3D)
  
- 💼 Explore my project on [Github](https://www.linkedin.com/safety/go/?url=https%3A%2F%2Fmaps.apple.com%2Fplace%3Faddress%3Dhttps%253A%252F%252Fgithub.com%252FFaithObamomi.png&urlhash=-91U&isSdui=true&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bobji4OhATZCfREtzgPH5kQ%3D%3D)
  
- 📧 Faithobamomi10@outlook.com

---

*Last updated: [May, 2026]*

