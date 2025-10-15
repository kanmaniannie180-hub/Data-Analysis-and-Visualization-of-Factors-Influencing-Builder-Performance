# Data-Driven Contractor Selection and Housing Affordability in Madurai

## Abstract
A house is essential for enhancing people’s well-being, ensuring health, and fostering development. For children, the presence of a secure home is critical for growth and stability. A quality home not only benefits individuals but contributes significantly to national development.  
This research explores the economic and technical factors influencing home ownership in Madurai, Tamil Nadu, with an emphasis on contractor performance and the role of building materials in housing affordability.  
Using Exploratory Data Analysis (EDA), the study analyzes contractor datasets to uncover patterns in cost, quality, and service offerings. The findings highlight the importance of data-driven decision-making in selecting reliable builders, ultimately supporting affordable and sustainable housing for all.

**Keywords:** Builder performance, Construction industry, Service offerings, Turnover analysis, Performance ratings, Data visualization, Statistical modeling, Data transformation, Data integration, Data wrangling.

---

## Introduction
Exploratory Data Analysis (EDA) is a key data science technique that summarizes dataset characteristics using visual and statistical methods.  
In the housing context, EDA helps uncover relationships between contractor reliability, construction costs, and housing outcomes.  
This study builds on N. Periyamayan’s 2019 survey on homelessness in Madurai, which revealed the growing challenge of accessing affordable builders. Through EDA, this project provides structured data and insights for informed contractor selection, helping residents avoid overpaying and ensuring better-quality construction.

---

## Related Works
Previous research (2020–2024) has highlighted the value of data-driven approaches for optimizing contractor selection and improving housing affordability.  
Key studies by Ghosh et al., Gupta and Shah, and Kumar et al. show that analyzing contractor data (pricing, ratings, and timelines) can enhance project outcomes and affordability.  
This work extends those findings to the Madurai context by compiling a detailed local dataset.

---

## Problem Statement
Many individuals in Madurai struggle to build homes due to:
- High construction costs and unreliable contractors  
- Lack of structured information on builder performance  
- Economic and policy barriers limiting affordable housing  

This research aims to create a data-driven platform that helps residents:
- Identify reliable contractors  
- Compare costs and services  
- Understand key trends in builder performance  

---

## Research Objectives
1. Analyze economic and technical factors influencing home construction in Madurai.  
2. Collect and clean data on contractor performance, pricing, and service quality.  
3. Perform EDA to uncover trends and correlations in the construction sector.  
4. Visualize key insights such as cost versus quality and ratings versus turnover.  
5. Provide actionable insights to guide homeowners in selecting reliable builders.  

---

## Data Collection
**Sources include:**
- Online directories (Justdial, Sulekha, Houzz)  
- Government publications (Tamil Nadu Department of Economics & Statistics, HSUI reports)  
- Industry reports, customer reviews, and direct interviews  
- News articles (e.g., *The Hindu*, 2023 Goripalayam building collapse)  

The dataset includes:
- 1000+ contractor entries  
- 20+ attributes (name, contact information, services, ratings, cost per square foot, legal status, turnover, employee count, etc.)

---

## Exploratory Data Analysis (EDA)
Python libraries used:
- Pandas for data cleaning and preprocessing  
- Matplotlib and Seaborn for visualization  

Key insights:
- Most builders in Madurai have ratings above 4.5 (average: 4.77)  
- No significant correlation between firm age and turnover  
- Larger teams (19–38 employees) handle bigger projects, but smaller teams can be highly efficient  
- Builders in Anna Nagar and Vandiyur show the highest service ratings  
- Proprietors offer flexible payment terms, while limited companies handle longer projects  
- Builders from the 1990s maintain the highest average turnover  

---

## Results Summary

| Category | Findings | Suggestions |
|-----------|-----------|-------------|
| **Material Usage** | Builders frequently use TMT Rod, Ultra Tech Cement, and M-Sand | Maintain material quality; collect more cost data |
| **Geographical Distribution** | High-rated builders in Anna Nagar, Vandiyur, Tirumangalam | Maintain service quality in high-demand areas |
| **Legal Status** | Proprietors offer flexible payments; Companies have standardized terms | Small firms can leverage flexibility |
| **Employee Count** | Larger teams have higher turnover | Balance efficiency with team size |
| **Features Included** | High-rated builders offer more complete service packages | Minimize exclusions to improve ratings |
| **Turnover by Decade** | Builders established in the 1990s have the highest turnover | Newer firms should innovate to compete |

---

## Tools and Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Data Management:** CSV datasets  
- **Visualization Tools:** Python-based charts and plots  
- **Documentation:** Markdown, GitHub Repository  

---

## How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/madurai-contractor-analysis.git
   cd madurai-contractor-analysis
