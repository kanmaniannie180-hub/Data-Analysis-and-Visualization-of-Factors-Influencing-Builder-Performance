# 📊 Dataset Documentation

<div align="center">

![Dataset](https://img.shields.io/badge/Dataset-Construction%20Analytics-blue)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Analysis-green)
![Research](https://img.shields.io/badge/Research-Housing%20Affordability-orange)
![Construction](https://img.shields.io/badge/Domain-Construction-red)

### 🏗️ Dataset for Construction Contractor Analysis and Housing Affordability Assessment in Madurai

</div>

---

# 📖 Overview

This dataset was developed as part of a research study focused on analyzing construction contractors and evaluating factors influencing housing affordability in Madurai, Tamil Nadu.

The dataset integrates business, operational, workforce, financial, and performance-related information collected from construction companies operating within the region. It serves as the foundation for Exploratory Data Analysis (EDA), statistical evaluation, and contractor performance assessment.

The primary objective of this dataset is to support data-driven decision-making by identifying reliable, cost-effective, and experienced contractors while uncovering relationships between company characteristics, ratings, workforce strength, and business performance.

The dataset enables researchers, students, homeowners, investors, and industry professionals to gain insights into the construction ecosystem and housing development sector.

---

# 🌍 Study Area

## Location

**Madurai, Tamil Nadu, India**

Madurai is one of the fastest-growing urban centers in Tamil Nadu, experiencing continuous residential and commercial infrastructure development. The city provides an ideal environment for studying contractor performance, housing construction trends, and affordability-related factors.

### Geographic Scope

* City: Madurai
* State: Tamil Nadu
* Country: India
* Administrative Coverage: Madurai District and Nearby Regions

### Unit of Analysis

The primary unit of analysis is the **construction contractor or construction firm**, where each record represents a unique organization operating within the construction industry.

---

# 🎯 Purpose of the Dataset

The dataset was created to support:

* 🏗️ Construction Contractor Analysis
* 🏠 Housing Affordability Research
* 📊 Exploratory Data Analysis (EDA)
* 📈 Statistical Modeling
* 💰 Cost and Revenue Analysis
* ⭐ Contractor Performance Evaluation
* 📍 Regional Construction Market Assessment
* 🤝 Contractor Selection and Comparison

---

# 🗂️ Dataset Categories

The dataset is organized into multiple categories representing different aspects of contractor operations.

| Category                 | Description                        |
| ------------------------ | ---------------------------------- |
| 🏢 Company Information   | Basic firm details                 |
| 💼 Business Information  | Business structure and operations  |
| 💰 Financial Indicators  | Revenue and turnover metrics       |
| 👷 Workforce Information | Employee and operational capacity  |
| ⭐ Performance Indicators | Ratings and customer perception    |
| 🏗️ Project Information  | Design projects and specialization |

---

# 🏢 Company Information

This category contains fundamental information about construction firms.

## Variables Included

* Construction Name
* Address
* Phone Number
* Founded Year

### Purpose

These variables help identify and classify contractors operating in the Madurai region.

---

# 🏗️ Project and Service Information

Project-related fields provide insights into the types of construction services offered by each contractor.

## Variables Included

* Design Projects
* Specialization
* Specialities

### Examples

* Residential Construction
* Commercial Construction
* Interior Design
* Turnkey Projects
* Smart Home Solutions
* Modular Construction
* Architectural Design

### Importance

These variables support:

* Service comparison
* Market segmentation
* Contractor expertise assessment

---

# 💼 Business Structure Information

Business-related indicators provide information about the organizational structure of each contractor.

## Variables Included

* Nature of Business
* Legal Status of Firm
* Industry Category

### Examples

#### Nature of Business

* Builder
* Developer
* Contractor
* Consultant

#### Legal Status

* Proprietorship
* Partnership
* Private Limited Company
* Limited Liability Partnership (LLP)

### Importance

Business structure often influences:

* Operational capacity
* Financial performance
* Project management capabilities

---

# 💰 Financial Indicators

Financial variables were collected to evaluate company size and economic performance.

## Variables Included

* Annual Turnover

### Purpose

Financial indicators help assess:

* Revenue generation
* Market competitiveness
* Business stability
* Growth potential

### Applications

* Cost-effectiveness analysis
* Contractor comparison
* Affordability studies

---

# 👷 Workforce Information

Workforce-related variables indicate organizational capacity and project handling capability.

## Variables Included

* Total Number of Employees

### Importance

Employee strength provides insights into:

* Project execution capability
* Workforce availability
* Organizational scale
* Business growth potential

---

# ⭐ Performance Indicators

Performance indicators measure customer satisfaction and market reputation.

## Variables Included

* Ratings

### Rating Sources

Ratings were collected and validated using:

* Justdial
* Houzz
* Sulekha
* Google Reviews
* Public Business Directories

### Purpose

Ratings help evaluate:

* Service quality
* Customer satisfaction
* Contractor reliability
* Market reputation

---

# 📋 Complete Data Dictionary

| Field Name                | Description                                               |
| ------------------------- | --------------------------------------------------------- |
| Construction Name         | Registered name of the construction company or contractor |
| Address                   | Office or operational address                             |
| Design Projects           | Type of projects undertaken                               |
| Specialization            | Primary area of expertise                                 |
| Legal Status of Firm      | Business entity classification                            |
| Annual Turnover           | Estimated annual revenue                                  |
| Ratings                   | Average customer rating                                   |
| Phone Number              | Verified contact information                              |
| Total Number of Employees | Workforce size                                            |
| Nature of Business        | Type of construction operation                            |
| Founded                   | Year of establishment                                     |
| Specialities              | Unique services offered                                   |
| Industry                  | Construction industry category                            |

---

# 🔄 Data Collection Methodology

The dataset was developed using a structured multi-stage data collection process.

---

## 🌐 Phase 1: Online Research

Initial information was collected from publicly available sources.

### Sources Used

* Justdial
* Sulekha
* Houzz
* Construction Company Websites
* Google Business Listings
* Social Media Business Pages

### Data Collected

* Company information
* Service offerings
* Ratings
* Contact details
* Project information

---

## 📞 Phase 2: Direct Contractor Verification

To improve reliability and accuracy, contractors were contacted directly through telephone interviews.

### Information Verified

* Annual turnover
* Number of employees
* Service specialization
* Project portfolio
* Business operations

### Benefits

* Increased data accuracy
* Reduced misinformation
* Enhanced dataset credibility

---

## 🧹 Phase 3: Data Cleaning

Raw data was processed using Python and Pandas.

### Cleaning Activities

* Duplicate removal
* Missing value handling
* Data standardization
* Formatting corrections
* Consistency checks

---

## ✅ Phase 4: Data Validation

The collected information underwent validation procedures.

### Validation Techniques

* Cross-verification across multiple platforms
* Rating consistency checks
* Contact information verification
* Business record validation

---

# 🛠️ Data Preprocessing

Several preprocessing techniques were applied before analysis.

### Data Standardization

* Uniform formatting
* Consistent naming conventions
* Structured categorical variables

### Missing Value Handling

* Identification of incomplete records
* Appropriate treatment strategies

### Duplicate Elimination

* Removal of redundant records
* Improved data quality

### Feature Preparation

* Transformation of categorical variables
* Preparation for EDA and statistical analysis

---

# 📄 Sample Dataset Structure

Example CSV format:

```csv
Construction Name,Address,Design Projects,Specialization,Legal Status of Firm,Annual Turnover,Ratings,Phone Number,Total Employees,Nature of Business,Founded,Specialities,Industry

XYZ Builders,Anna Nagar,Residential,Interior & Civil,Proprietorship,₹1.2 Cr,4.8,9876543210,25,Builder,2005,Turnkey Projects,Civil Construction

ABC Constructions,Vandiyur,Commercial,Architectural Design,Private Limited,₹3.5 Cr,4.6,9876504321,40,Developer,1998,Modular Buildings,Real Estate
```

---

# 📊 Intended Applications

This dataset supports multiple analytical and research applications.

## Research Applications

* Housing Affordability Studies
* Construction Industry Research
* Business Performance Analysis
* Market Trend Analysis

---

## Analytical Applications

* Exploratory Data Analysis (EDA)
* Correlation Analysis
* Contractor Ranking
* Performance Benchmarking

---

## Business Applications

* Contractor Selection
* Vendor Evaluation
* Market Research
* Investment Assessment

---

## Consumer Applications

Potential homebuyers and developers can use the dataset to:

* Compare contractors
* Evaluate reliability
* Assess service quality
* Make informed decisions

---

# 📈 Potential Analysis Areas

The dataset enables investigation of relationships such as:

### Financial Performance

* Turnover vs Employee Strength
* Turnover vs Company Age

### Customer Satisfaction

* Ratings vs Specialization
* Ratings vs Business Type

### Business Growth

* Company Age vs Revenue
* Workforce Size vs Project Capacity

### Housing Affordability

* Contractor Capability vs Cost Efficiency
* Service Quality vs Market Performance

---

# ⚠️ Dataset Limitations

While extensive efforts were made to ensure data quality, certain limitations should be considered.

### Regional Scope

The dataset primarily focuses on contractors operating within Madurai and nearby regions.

### Self-Reported Information

Certain financial and operational variables were obtained through direct communication and may contain estimation-based responses.

### Dynamic Business Information

Contractor information may change over time due to:

* Business expansion
* Workforce changes
* Revenue fluctuations

### Platform Rating Variations

Ratings collected from different platforms may vary based on user demographics and review volume.

---

# 🔒 Data Usage Guidelines

Users are encouraged to:

* Use the dataset responsibly.
* Verify critical business information independently.
* Acknowledge the original research effort.
* Apply findings ethically and objectively.

---

# 📚 Recommended Citation

If you use this dataset in research, academic work, or analysis, please cite:

### Construction Contractor Analysis and Housing Affordability Assessment in Madurai

**Author**

* Annie Darling Kanmani A

**Department of Artificial Intelligence and Data Science**

**SRM Madurai College for Engineering and Technology**

---

# 🌟 Final Note

This dataset provides a valuable foundation for understanding contractor performance, business characteristics, and housing affordability factors within the construction industry. By combining operational, financial, workforce, and customer satisfaction indicators, the dataset enables comprehensive analysis and supports data-driven decision-making for researchers, businesses, and consumers alike.

<div align="center">

### 🏗️ Better Data → 📊 Better Analysis → 🏠 Better Housing Decisions

</div>
