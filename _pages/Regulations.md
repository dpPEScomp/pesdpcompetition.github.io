---
layout: archive
title: "SubmissionDetails"
permalink: /submission/
author_profile: false
---
Regulations of the competition. Any matters not covered herein shall be decided by the committee after deliberation.

---
# 1 Competition procedure
* All submitted works should consist of **two parts**: the dataset and the corresponding report in IEEE data description [journal style](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10347231).
* All submitted datasets must be hosted on [IEEE DataPort](https://ieee-dataport.org/) and comply with DataPort’s upload and publication policies.

The competition has **two stages**:
* **Stage 1**
  The submitted datasets and reports will be reviewed by the committees, and the Top 5 teams will be selected.
* **Stage 2**
  These **Top 5 teams** will be invited to an online defense, where they will present their datasets. The final winners will be determined based on this defense.


# 2 Eligibility & Teaming
* Participation is open to individuals or teams. Each team may have at most 3 members (including the team lead).
* Only one registration per team is required. There is no restriction on members’ institutions.
* All-student teams receive a scoring advantage (see final score calculation). An all-student team means all members are enrolled students (undergraduate, master’s, or PhD) on the submission deadline.
* Each participant (including individuals) may join at most one team. Duplicate participation may result in disqualification.


# 3 Review & Compliance Screening
* Administrative/compliance screening: A preliminary check for license, privacy, safety, and accessibility. Submissions failing this step will not enter the review process.
* Reviewer assignment: Each valid submission is randomly assigned to 2-3 reviewers who score independently. Reviewers must declare conflicts of interest and recuse as needed.
* Review approach: Scoring will be based on the submitted dataset and report. Reviewers will verify the availability of datasets and code as necessary, and may conduct spot checks or request further clarifications.


# 4 Rubric Detail
## Scale
* Each section is scored on **1–5**

| Score  | Description                                           |
| ------ | ----------------------------------------------------- |
| 1      | Poor \(severe deficiencies \/ unusable\)              |
| 2      | Weak \(multiple issues\)                              |
| 3      | Fair \(meets minimum expectations\)                   |
| 4      | Good \(high quality with minor gaps\)                 |
| 5      | Excellent \(clear, complete, reusable, high impact\)  |


## Section weights

| No.    | Section \(<i>S<sub>i</sub></i>\)                      | Weight \(<i>W<sub>i</sub></i>\)  |
| ------ | ----------------------------------------------------- | ------------------- |
| 1      | Importance of targeted problem <br>\(A good dataset should target a problem of high relevance and impact in the power and energy domain, advancing both research innovation and practical solutions.\)  | 10% |
| 2      | Difficulty of data organization<br>\(The difficulty of data organization reflects the effort required to collect, clean, integrate, and structure the dataset.\)                     | 10% |
| 3      | Accessibility & Usability<br>\(Publicly available, with clear documentation, metadata, and licensing. Organized in standard formats (e.g., MAT, CSV, JSON, HDF5) and easy to integrate into AI workflows.\)  | 20% |
| 4      | Reproducibility & Transparency<br>\(Accompanied by clear instructions, preprocessing steps, and references. Code for data preparation or example use cases is provided.\)  |  20% |
| 5      | AI model performance based on datasets<br>\(Good dataset should enable the efficient learning of AI models and achieve reliable, generalizable, and reproducible performance, demonstrated through benchmarking on relevant tasks.\)  | 30% |
| 6      | Impact potential<br>\(Enables development of robust AI models with measurable improvements. Has potential to accelerate innovation in sustainability, efficiency, reliability or resiliency.\) | 10% |

* Final score calculation
Final_score = <math>
  <mrow>
    <mo>&#x03A3;</mo>
      <i>S<sub>i</sub></i> * <i>W<sub>i</sub></i>
   </mrow></math>


* All-student bonus &#x03B3;=0.5: Final_score = <math>
  <mrow>
    <mo>&#x03B3; + </mo>
    <mo>&#x03A3;</mo>
      <i>S<sub>i</sub></i> * <i>W<sub>i</sub></i>
   </mrow></math>

\(\* Students include undergraduate and postgraduate students.\)

* Tie-breaking
  If a tie occurs, compare in order: \(1\) Data quality & completeness \(higher wins\); \(2\) Metadata quality \(higher wins\); \(3\) Baseline validation \(higher wins\).
* Disqualification & Deductions
  Plagiarism, infringement, data fabrication, or major compliance risks may lead to disqualification. If data/code becomes inaccessible during review or significantly deviates from the report, organizers may deem the submission invalid.


# 5 IP, Legal, Ethics & Safety

* Teams must ensure they hold the necessary rights to their submissions and do not infringe third-party rights.
* Data, code, and documentation must carry explicit licenses. Third-party components must cite sources and licenses and ensure lawful redistribution and Competition use.
* Teams retain their IP. Organizers and reviewers have a fair-use right for competition-related publicity, review, and scholarly communication \(including screenshots, abstracts, and links\).
* No PII or sensitive critical-infrastructure details; apply appropriate de-identification/differential privacy where necessary and document it.
* Data sources must be lawful and compliant; assess and disclose potential risks \(bias, discrimination, misuse\).
* Sensitive grid-security information should be obfuscated and disclosed in tiers where appropriate.
