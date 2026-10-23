## Business Requirements

Monitor overall workforce by tracking total employees, attrition, active staff, rate, and average age.

Analyze attrition by gender to compare male and female turnover.

Identify education-wise attrition across degree levels.

Evaluate attrition by job role to find high-risk positions.

Analyze department-wise attrition to highlight R&D, and HR.

Examine attrition by age group to spot vulnerable age bands.

Assess attrition by marital status across married, single, and divorced.

Track job satisfaction rating to monitor employee engagement levels.


## PROBLEM STATEMENT

**Charts Requirement**

How does attrition vary by gender? → Employees by Gender
**Visual:** Donut chart

Which education levels have highest attrition? → Education-wise Attrition
**Visual:** Horizontal bar chart

Which job roles show highest attrition? → Attrition by Job Role
**Visual:** Treemap

Which departments drive most attrition? → Department-wise Attrition
**Visual:** Pie chart

How does attrition differ by age group? → Attrition by Age Group
**Visual:** Vertical bar chart

How does attrition differ by marital status? → Attrition by Marital Status
**Visual:** Horizontal bar chart

**Dashboard Preview**


<img width="683" height="332" alt="hospital_ER_EXCEL1" src="https://github.com/user-attachments/assets/8e18738b-8358-4fa2-8d33-4085cda2f70c" />


## Analytical Highlights

**Critical Attrition Rate:** Recorded a concerning 16.12% attrition with 237 employees leaving.

**Sales Department Dominance:** Identified Sales as the top attrition driver at 66.29%.

**Education Hotspot:** Found Bachelor’s Degree holders with the highest attrition (37).

**Age Group Risk:** Detected peak turnover in the 25–34 age band.

**Marital Status Impact:** Observed Married employees leading attrition with 271 exits.

**Low Satisfaction Alert:** Registered a weak Job Satisfaction Rating of only 2.1.

## Below is an in-depth analysis of each visual component:

**1. High-level Key Performance Indicators (KPIs)**
Total Employees: 1,470

Attrition: 237

Active Employees: 1,233

Attrition Rate: 16.12%

Average Age: 37

Job Satisfaction Rating: 2.6 (out of 5, shown with a thumbs-up icon and star rating)

**Insight:** The organization has a moderately high attrition rate of 16.12%, meaning roughly 1 in 6 employees left. With an average age of 37 and a relatively low job satisfaction score of 2.6/5, there are clear signals of employee engagement and retention challenges that warrant deeper investigation.

**2. Total Employees by Gender**
Female: 240

Male: 366

**Insight:** The workforce is male-dominated (approximately 60% male vs 40% female). This gender imbalance may influence culture, retention patterns, and diversity-related attrition risks.

**3. Education-wise Attrition (Horizontal Bar Chart)**

Bachelor’s Degree: 37

Master’s Degree: 25

Associate’s Degree: 18

High School: 8

Doctoral Degree: 1

**Insight:** Employees with a Bachelor’s degree account for the highest number of departures (37), followed by those with a Master’s degree (25). Higher education levels (especially Bachelor’s and Master’s) appear more prone to attrition, possibly due to greater external job market opportunities or unmet career expectations.

**4. Attrition by Job Role (Treemap / Hierarchical Chart)**
Visible segments include:

Laboratory Technician (large grey area)

Sales Executive (prominent red area)

Research Scientist (blue area)

Sales Representative and smaller roles (Manager, Healthcare Representative, etc.)

**Insight:** Laboratory Technicians and Sales Executives show the most significant attrition volume. These two roles appear to be the highest-risk positions and should be prioritized for retention interventions (e.g., compensation reviews, career path clarity, or workload analysis).

**5. Department-wise Attrition (Pie Chart)**

R&D: 66.29%

Sales: 32.58%

HR: 1.12%

**Insight:** Research & Development experiences by far the highest share of attrition (nearly two-thirds of all departures). Sales is the second major contributor. HR has almost negligible attrition. This strongly indicates that technical/R&D talent retention is a critical organizational issue.

**6. Attrition by Age Group (Bar Chart)**

25–34: highest bar (~40)

35–44: next highest

Under 25: moderate

45–54: lower

Over 55: lowest

**Insight:** Younger employees (especially the 25–34 age group) have the highest attrition. This is a classic early-career retention challenge and suggests the need for stronger onboarding, mentorship, career development programs, and competitive early-career compensation.

**7. Attrition by Marital Status (Horizontal Bar Chart)**
Married: 271

Single: 201

Divorced: 134

**Insight:** Married employees show the highest absolute attrition numbers, followed by Single employees. While absolute numbers are highest among Married staff, the relative risk by marital status would require comparing against the overall population distribution to determine true risk rates.

## Overall Insight
The dashboard reveals a clear and concerning retention problem concentrated in Research and Development, among employees holding Bachelor’s and Master’s degrees, Laboratory Technicians, Sales Executives, and younger staff (especially those aged 25–34).
With an attrition rate of 16.12% and a low average job satisfaction rating of only 2.6 out of 5, the issues appear systemic rather than isolated. Priority should be given to strengthening talent retention in Research and Development, improving early-to-mid career development opportunities, and addressing the underlying drivers of low job satisfaction across the organization.

## Recommendations

**Prioritize Research and Development Retention:**
Conduct focused exit interviews and stay interviews specifically within Research and Development. Review compensation, career progression paths, workload, and recognition programs for Laboratory Technicians and Research Scientists, as these roles show the highest attrition volume.

**Strengthen Early-Career Talent Programs:**
Introduce structured mentorship, clear career pathways, and competitive early-career packages for employees aged 25–34 (the highest attrition age group). Consider accelerated development tracks for high-potential Bachelor’s and Master’s degree holders.

**Address Low Job Satisfaction**
Investigate the root causes behind the 2.6/5 job satisfaction rating through anonymous pulse surveys and focus groups. Act on the top drivers of dissatisfaction (e.g., leadership, workload, recognition, work-life balance).

**Review Sales Roles:**
Analyze the working conditions, targets, and incentive structures for Sales Executives and Sales Representatives, as these roles also contribute significantly to attrition.

**Gender and Diversity Considerations**
Explore whether the current male-dominated workforce (especially in high-attrition areas) is contributing to retention challenges, and ensure inclusive policies and development opportunities for all genders.

**Monitor and Measure Progress**
Set clear retention KPIs by department, age group, education level, and job role. Review the dashboard monthly and track the impact of interventions on the overall attrition rate and job satisfaction score.

**Conclusion**
The HR Analytic Dashboard highlights a significant retention challenge, particularly within Research and Development and among younger, highly educated employees. With an attrition rate of 16.12% and a low job satisfaction score of 2.6, the organization faces a clear risk of losing critical talent.
By taking targeted action in Research and Development, improving early-career development, and addressing the underlying causes of low satisfaction, the company can reduce attrition, protect institutional knowledge, and build a more engaged and stable workforce.

**TOOL USED**

**Data Cleaning and Preparation:** Excel Power Query

**Data Analysis:** Excel Power Pivot

**Data Visualization and Dashboard Creation:** Excel PivotTables, PivotCharts, and Slicers

**Technique Applied**

Data Cleaning and Transformation

Data Modeling Using Power Pivot

Pivot Table Analysis and Aggregation

Interactive Dashboard Development Using PivotCharts and Slicers



