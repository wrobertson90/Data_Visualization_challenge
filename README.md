 Data_Visualization_challenge

 Dependencies and Setup:
   - Import essential libraries such as `pandas`, `numpy`, `matplotlib`, and `scipy.stats`.

 Data Import and Cleaning:
   - Loaded mouse metadata and study results.
   - Merge datasets and remove duplicate or invalid entries to create a clean working DataFrame.

 Descriptive Statistics:
   - Compute mean, median, standard deviation, and variance for tumor volumes grouped by drug regimen.

 Visualizations:
   - Bar Plot: Total number of data points for each drug regimen.
   - Pie Chart: Distribution of male and female mice in the study.
   - Box Plot: Tumor volume distributions for key drug regimens.
   - Line Plot: Tumor volume changes over time for a specific mouse.
   - Scatter Plot: Relationship between mouse weight and average tumor volume.

 Statistical Analysis:
   - Calculate IQR for tumor volumes to detect potential outliers.
   - Perform correlation and regression analyses to understand weight-tumor relationships.

---

 Results

 Key Findings:
- Capomulin and Ramicane showed significant reductions in tumor volume compared to other treatments.
- Infubinol presented a notable outlier, suggesting further investigation.
- Mouse weight was positively correlated with tumor volume under Capomulin, suggesting heavier mice tend to have larger tumor volumes.

 Visualizations:
- Plots highlighted the effectiveness of Capomulin and Ramicane while identifying trends in tumor volume changes over time.
