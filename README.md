# MoonLight Energy Solutions – Solar Data Analysis

## Project Overview

This project analyzes solar radiation data from **Benin, Sierra Leone, and Togo** to identify high-potential regions for solar installation. The goal is to support MoonLight Energy Solutions’ mission of enhancing operational efficiency and sustainability through data-driven solar investments.

The analysis includes data cleaning, exploratory data analysis (EDA), and cross-country comparisons to provide actionable insights for strategic decision-making.

---

## Objectives

- Identify trends in solar irradiance and environmental factors across countries.  
- Compare key metrics (GHI, DNI, DHI) to assess solar potential.  
- Highlight countries with the most consistent and highest solar energy availability.  
- Provide recommendations for targeted solar installations aligned with sustainability goals.  

---

## Key Insights

- **Benin** shows the highest mean GHI (**229.83 W/m²**), suggesting strong overall solar potential. However, the high standard deviation (**321.64**) indicates significant variability in solar irradiance.  
- **Sierra Leone** has the lowest mean GHI (**196.44 W/m²**) with moderate variability, indicating less consistent solar potential compared to Benin and Togo.  
- **Togo** matches Benin in mean GHI (**229.83 W/m²**) and shows similar variability, suggesting comparable solar potential.  
- **Statistical Testing:** Both ANOVA and Kruskal–Wallis tests returned **p-values of 0.0**, confirming that differences in GHI between the countries are statistically significant.  

**Insight:**  
Benin and Togo are top candidates for solar installation based on average irradiance, but Benin may require strategies to manage variability. Sierra Leone has lower solar potential but may still be suitable for smaller-scale projects.  

---

## Approach

1. **Data Profiling and Cleaning:** Handled missing values, outliers, and sensor irregularities.  
2. **Exploratory Data Analysis:** Examined solar radiation, temperature, humidity, and wind patterns through visualizations and statistical summaries.  
3. **Cross-Country Comparison:** Compared Benin, Sierra Leone, and Togo using boxplots, summary statistics, and significance testing.  
4. **Strategic Recommendations:** Prioritized countries for solar installation based on solar potential and variability.  

---

## Recommendations

- Focus solar investments on **Benin and Togo**, where average irradiance is high and consistent.  
- Design strategies to **mitigate variability** in solar production, especially for Benin.  
- Consider smaller-scale or targeted projects in Sierra Leone while monitoring solar potential trends.  

---

## Conclusion

This analysis provides actionable insights for MoonLight Energy Solutions to optimize solar investments, align with sustainability goals, and strategically expand operations 
Git Setup

Follow these steps to set up Git and manage your repository:

1. Clone the Repository
git clone https://github.com/yourusername/your-repo.git
cd your-repo

3. Check Current Branch
git branch


This shows the branch you’re currently on (usually main).

3. Create a New Branch for Your Work
git checkout -b feature-branch-name


Replace feature-branch-name with a descriptive name for your task.

4. Make Changes

Edit files, add code, or update documentation.

Check status to see changed files:

git status

5. Stage Your Changes
git add .


Stages all modified files. Or stage specific files with git add filename.

6. Commit Your Changes
git commit -m "Add descriptive message about your changes"


Use a clear message describing what the commit does.

7. Push Your Branch to GitHub
git push origin feature-branch-name

8. Open a Pull Request (PR)

Go to your repository on GitHub.

You’ll see a notification to open a PR for your pushed branch.

Click Compare & pull request.

Add a title and description for your PR.

Click Create pull request.

9. Merge Your PR

After review, click Merge pull request to integrate your changes into main.

Pull the latest main branch locally:

git checkout main
git pull origin main
















in West Africa.

