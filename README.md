# ODC_StudentsPerformance_Analysis_Task1
Orange digital center course | Data Analyst Using Ai

Summary of Insights — Executive Summary
Dataset health: The dataset is clean — zero missing values, zero duplicates, no invalid categories, and no out-of-range scores across 1,000 students. Its main limitation is structural: it is a single snapshot with no student ID or date field, so findings below are cross-sectional associations, not longitudinal trends or causal claims.

Top findings, ranked by impact:

Lunch type (socioeconomic proxy) is the strongest single driver of the performance gap in this dataset — students on standard lunch outperform free/reduced-lunch peers across every subject, and this is the largest gap of any variable tested.
Test preparation course completion delivers a statistically significant, subject-wide score boost — and unlike lunch type or parental education, this is the most directly actionable lever for schools and students, since it reflects a specific behavior/program rather than a fixed demographic trait.
Disadvantages compound. Students who both lack test preparation and have free/reduced lunch score substantially below what either factor alone would predict, and are heavily overrepresented in the bottom performance decile.
Parental education shows a steady, monotonic gradient — each step up in parental education level corresponds to a step up in average student score.
Gender effects are subject-specific, not universal — male students lead in math; female students lead in reading and writing — pointing to differentiated skill development rather than one gender outperforming broadly.
Race/ethnicity groups differ significantly (ANOVA-confirmed) with a rising trend from Group A to Group E, though the dataset cannot isolate whether this reflects the ethnicity grouping itself or confounded factors (e.g., correlated parental education/lunch distributions across groups).
Subjects are highly inter-correlated — reading and writing move together most tightly, with math somewhat more independent — suggesting general academic ability plus a distinct math-specific skill component.
Implications / recommended actions:

Prioritize expanding access to test-preparation resources, especially for students already facing socioeconomic disadvantage (free/reduced lunch), since this is the most direct, non-demographic lever available and the compounding-effect analysis shows it matters most exactly where students need it most.
Treat the free/reduced lunch cohort as the highest-priority intervention group, given it shows the single largest performance gap in the dataset.
Because subject scores are highly correlated, broad literacy/numeracy support programs (rather than single-subject tutoring) are likely to have spillover benefits across subjects.
Invest in adding student IDs and test dates to future data collection so that true longitudinal performance-change analysis (rising/falling trajectories per student) becomes possible — this is the single biggest analytical upgrade available for this dataset going forward.
Confidence level: High for all statistically tested associations above (all reported gaps are significant at p < 0.001 via t-tests/ANOVA). Low/none for causal interpretation — this dataset supports "what is associated with what," not "what causes what."
