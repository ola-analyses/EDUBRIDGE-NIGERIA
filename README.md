# EDUBRIDGE-NIGERIA
## Introduction
EduBridge Nigeria is a proposed digital learning and scholarship management platform that works offline. It 
provides: a curriculum-aligned offline content library downloadable via low-bandwidth SMS or Wi-Fi where 
available, a scholarship discovery and application tool with deadline alerts, a structured mentor matching 
programme connecting students with Nigerian professionals, a teacher professional development portal 
with peer lesson-sharing, and a student progress dashboard visible to parents via SMS or web.

## Problem Statement 
Nigeria has the largest out-of-school child population in the world — over 10.5 million children who are not 
in any form of education (UNICEF, 2023). But the crisis goes deeper than the children who are completely 
out of school. Among the children who ARE enrolled in secondary school, the quality of learning is so poor 
and the support so absent that most are functionally excluded from opportunity anyway:

- Quality learning materials are inaccessible
- Scholarships exist but go unclaimed
- Mentorship is entirely luck-based
- Teachers are unsupported and unmeasured
- Parents are disengaged from learning

  ## Business Case
The business case includes a three-year cost-benefit analysis, an SROI assessment, Financial Return on Investment (ROI) and a risk register

Deliverable: [Click EduBridge-Nigeria-Business-Case Here](https://github.com/ola-analyses/EDUBRIDGE-NIGERIA/blob/main/Edubrige%20Business%20case.pdf)

## Business Requirements Document (BRD)

The BRD documents the business needs, project scope, stakeholder requirements, User Stories and proposed system capabilities.

Deliverable:[Click EduBridge-BRD Here ]()

## Process Overview

 **Scholarship Discovery and Application (AS-IS)**

 **Process Flow**

 Student → Hear about scholarship from friend/radio/poster → Request support from parent/guardian→ Travel to scholarship office to verify information/collect application requirement → Visit school for transcript → Visit bank/local government → Gather documents → Go to Cybercafe/paper to complete application→ Possible missed deadline

![Current-State Process Map](https://github.com/ola-analyses/EDUBRIDGE-NIGERIA/blob/main/Current%20state%20Edubrige.png)
**Student Learning Support (Current State)**

**Process Flow**

 Student → Identifies that they do not understand a topic → Asks subject teacher for help → Teacher unavailable → Attempts to borrow textbook → Textbook already borrowed → Visits cybercafe for YouTube tutorial → Internet access/cost becomes a barrier → Considers buying revision guide → Cost becomes a barrier → Searches for another available resource → Learning gap may remain unresolved 
![Future-State Process Map](https://github.com/ola-analyses/EDUBRIDGE-NIGERIA/blob/main/Future%20state%20Edubrige.png)

# Dataset
The project uses a structured 12-month dataset to analyse key platform performance, engagement, and user satisfaction indicators.

**Dataset Overview**

The dataset contains 12 monthly records detailing the following fields:
| Field | Description |
|---|---|
| Months | Reporting period label, from Month 1 to Month 12 |
| Active Students | Total number of active students participating each month |
| Scholarship Apps | Total number of scholarship applications submitted |
| Mentor Sessions | Total number of mentoring sessions completed |
| Offline Access % | Percentage of users utilizing offline access functionality |
| Mentor Satisfaction | Student satisfaction rating for mentors on a 5-point scale |

## Data Transformation and Cleaning
Before analysis, the raw data was prepared in Power Query for accuracy and consistency.

Created a backup copy of the original dataset
![View the cleaned data below](https://github.com/ola-analyses/EDUBRIDGE-NIGERIA/blob/main/Dataset.png)

## Analytics and Measures
Key DAX measures were created to monitor trends

**Active student**
- Active student = MAX(EDUBRIDGE[Active Students])

**Mentor Satisfaction**
   - Mentor Satisfaction  = MAX(EDUBRIDGE[Mentor Satisfaction])

**Mentor session**
- Mentor session  = MAX(EDUBRIDGE[Mentor Sessions])

**Offline access**
- Offline access = MAX(EDUBRIDGE[Offline Access %])

**Scholarship Application**
- Scholarship Application  = MAX(EDUBRIDGE[Scholarship Apps])

## Dashboard and Visuals
Dashboard screenshots are placed here in the portfolio The dashboard includes: KPI Cards:
**KPI Cards:**
- Mentor Satisfaction Measure (4.50)
- Offline Access Measure (94.60)
- Scholarship Application Measure (562)
- Active Student (25.12K)
- Mentor Session Measure (981)

**Bar / Column Charts:**
- Scholarship Application by Month (Column Chart)
- Mentor Session Growth (Horizontal Bar Chart)

**Line Charts:**
- Offline Access (Line Chart across Month 1 to Month 12)
- Active Student by Month (Trend Line Chart)

   [*View General Insight Dashboard here*](https://github.com/ola-analyses/EDUBRIDGE-NIGERIA/blob/main/Edubrige%20Dashboard.pbix)
![Edubridge KPI Dashboard](https://github.com/ola-analyses/EDUBRIDGE-NIGERIA/blob/main/EduBrige%20Dashboard.png)

## Insights and Key Findings

The 12-month EduBridge Nigeria dataset provides insight into student engagement, scholarship applications, mentorship activity, and offline feature usage. 
**General Analysis**

Active student users increased from 2,841 in Month 1 to over 25,000 in Month 12. Growth was strongest during the first six months before slowing towards the end of the reporting period.

Monthly scholarship applications increased from 12 to 562, indicating greater use of the scholarship feature. As application volumes grow, clear eligibility information, deadline reminders, and application tracking will become increasingly important.

**Mentorship Analysis**

Monthly mentorship sessions rose from 48 to 981, while reported student satisfaction increased from 3.6 to 4.5 out of 5.0. These trends suggest that mentorship activity expanded alongside improved satisfaction. Further monitoring of mentor availability, matching delays, and session completion is needed to determine whether service quality can be maintained as demand grows.

**Offline Accessibility Analysis**

Offline feature usage increased from 71.2% in Month 1 to 94.6% in Month 12. This highlights the importance of offline access within the recorded platform activity, particularly for students with limited or unreliable internet connectivity.

## Recommendations

- Prioritise downloadable learning materials, efficient synchronisation, and reliable access to previously downloaded content.
- Provide clear eligibility criteria, application status tracking, and deadline reminders. Monitor application completion and successful scholarship outcomes.
-  Review mentor availability, matching times, and satisfaction feedback. Recruit and onboard additional mentors where necessary while maintaining appropriate safeguarding measures.
-  Investigate the slowdown in active user growth during the second half of the year. Use engagement and retention data to identify where additional student support may be needed.
-  Track student retention, scholarship outcomes, mentorship performance, satisfaction, and offline learning usage using consistent KPI definitions and reporting periods.
- Confirm data quality, establish realistic performance targets, and assess implementation costs and resource requirements before proceeding with the proposed solution.

## Conclusion

The analysis highlights growth in student engagement, scholarship applications, and mentorship activity, alongside increased use of offline functionality. These findings identify important priorities for EduBridge Nigeria: maintaining accessible learning resources, simplifying scholarship applications, supporting mentorship demand, and sustaining student engagement.

Consistent performance monitoring and further investigation of the observed trends would help guide future decisions and identify areas requiring improvement.  this project demonstrates how Business Analysis techniques and data visualisation can support requirements definition, process improvement, and evidence-based decision-making in the education sector.
 
 **Skills Demonstrated**: Business Analysis · Requirements Elicitation · BRD Documentation · Stakeholder Analysis · AS-IS / TO-BE Process Mapping · User Stories · Data Analysis · Power BI · KPI Reporting · Business Recommendations

