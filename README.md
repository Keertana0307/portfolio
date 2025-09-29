# Projects

## Sleep Health and Lifestyle Analysis

**Tools:** SAS Enterprise Guide, Excel, Kaggle Dataset

**Objectives:**
- Evaluate whether the average sleep duration aligns with recommended guidelines.  
- Compare sleep quality between genders.  
- Analyze the effect of BMI on sleep duration.  
- Build a predictive model of sleep duration based on lifestyle and health indicators.  

**Key Analyses:**
- Performed descriptive analysis (distribution of BMI, sleep duration, activity levels).  
- Conducted hypothesis testing (one-sample t-test, two-sample t-test, ANOVA).  
- Built a multiple linear regression model to predict sleep duration using quality of sleep, age, and physical activity.  

**Findings:**
- Average sleep duration (7.13 hours) was slightly higher than the recommended 7 hours.  
- Significant gender differences in sleep quality were observed.  
- BMI impacted sleep duration, with overweight individuals sleeping less on average.  
- Regression model (R² = 0.79) identified **quality of sleep** as the strongest predictor of sleep duration, followed by age and physical activity.  

[View Dataset on Kaggle](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)


## DreamHaven Online Lodging Platform – Database Design & Implementation

**Tools & Skills:** SQL, ERD Modeling, Relational Database Design, Oracle SQL Developer  

**Project Overview:**  
Designed and implemented a relational database system for *DreamHaven*, an online marketplace connecting hosts and guests for unique lodging experiences in Malaysia. The project covered end-to-end database development, from requirements analysis to implementation.  

**Key Contributions:**  
- Developed a **case scenario** and **Entity-Relationship Diagram (ERD)** capturing entities such as Hosts, Guests, Properties, Bookings, Payments, Facilities, and Reviews.  
- Applied **business rules and constraints** (age restrictions, unique property addresses, booking/payment deadlines, etc.).  
- Designed **relational schema** with primary, foreign, and alternate keys, ensuring data integrity.  
- Implemented **constraints and triggers** (e.g., age ≥ 18 validation, valid rating 1–5, booking/payment deadlines).  
- Created **indexes** for performance optimization on booking status, property type, ratings, etc.  
- Wrote **SQL queries** to answer business questions such as:  
  - Identifying low-rated budget properties (for service improvement).  
  - Analyzing most popular properties and hosts based on bookings, ratings, and revenue.  
  - Matching experienced hosts with new hosts for mentorship programs.  
  - Detecting properties with declining popularity.  
  - Listing frequent guests with high booking value.  

**Outcome:**  
Delivered a functional, optimized database system that demonstrates strong understanding of **database modeling, normalization, SQL constraints, indexing, and querying for business insights**.


### Consumer Behaviour Analysis – Principles of Business Analytics (BAA1034)

**Tools used:** Microsoft Excel (PivotTables, VLOOKUP, COUNTIF, Descriptive Statistics, Probability Analysis, Box Plots, Treemaps)

**Overview:**
Analyzed consumer shopping behaviour using a dataset of 2,000 randomly sampled observations. The dataset included demographics, purchase details, payment methods, and purchase frequency. The project focused on uncovering meaningful insights into shopping patterns and preferences.

**Highlights:**

* Categorized customers into six age groups to study purchase frequency trends.
* Compared spending habits of customers below 35 vs. 35 and above.
* Conducted probability analysis on age groups and payment methods.
* Created visualizations (Box Plots, Treemaps) to display purchasing behaviour.
* Key findings:

  * Younger customers purchased more frequently (bi-weekly).
  * Older customers spent slightly more on average.
  * Clothing was the top-selling category; dresses were the most popular item.

**Key Takeaway:**
Applied statistical tools and Excel functions to interpret consumer behaviour, identify spending trends, and visualize business insights.


## Analyzing Workplace Dynamics: Factors Influencing Employee Performance, Satisfaction, and Training Opportunities

**Tools:** SAS OnDemand for Academics, Kaggle Dataset

**Objectives:**

* Assess whether manager ratings differ across departments.
* Examine gender-based differences in employee performance ratings.
* Identify the strongest factor influencing job satisfaction (work-life balance, relationship satisfaction, environment satisfaction, or salary).
* Analyze access to training opportunities across departments.

**Key Analyses:**

* Data pre-processing, cleaning, and merging of `Employee.csv` and `PerformanceRating.csv` datasets (1,470 employees, 5,568 records).
* Descriptive statistics and visualization of manager ratings across departments.
* ANOVA to test performance rating differences between departments.
* Independent t-tests to compare salary and satisfaction ratings between genders.
* Correlation analysis of job satisfaction with work-life balance, environment satisfaction, relationship satisfaction, and salary.

**Findings:**

* **Manager ratings** did not significantly differ across departments (HR, Sales, Technology), suggesting fairness in performance evaluation.
* **No significant gender disparities** were observed in performance ratings, salary, or satisfaction metrics.
* **Environmental satisfaction** showed a weak but significant relationship with job satisfaction in 2021, though not in 2016, indicating a growing importance of workplace environment.
* **Training opportunities** were distributed equitably across departments, reflecting consistent policies for employee development.

[View Dataset on Kaggle](https://www.kaggle.com/datasets/mahmoudemadabdallah/hr-analytics-employee-attrition-and-performance)


## Enterprise Architecture for Trendy (Group Project)

**Course:** EAC2014 Enterprise Architecture
**Tools/Concepts:** Enterprise Architecture Frameworks (CSVLOD Model, Operating Models, Business Capabilities, ERP, IMS, RMS)

**Objectives:**

* Develop an Enterprise Architecture (EA) strategy for *Trendy*, a growing fashion retailer.
* Address operational challenges such as inventory management, reverse logistics, and data fragmentation.
* Propose IT-enabled solutions to support scalability, efficiency, and sustainability.

**Key Analyses:**

* Designed unified **operating models** for reverse logistics, inventory management, and enterprise resource planning.
* Identified **business capabilities** and mapped them to IT systems (ERP, IMS, RMS).
* Applied the **CSVLOD framework** (Consideration, Standard, Vision, Landscape, Outline, Design) to align IT with business needs.
* Recommended policies and principles (e.g., IT integration standards, data management practices, reverse logistics optimization).

**Findings & Recommendations:**

* Implementing an **integrated ERP system** would reduce data silos and improve decision-making.
* **Inventory Management System (IMS)** with real-time tracking and AI forecasting could enhance demand planning.
* A **Returns Management System (RMS)** would streamline reverse logistics, improving customer satisfaction and cost efficiency.
* EA roadmap supports Trendy’s long-term vision of a **digitally enabled omni-channel retailer** with sustainable operations.


## Smart iZone Waitlist System

**Course:** Systems Analysis & Design
**Tools/Concepts:** SDLC (Waterfall), Figma (Prototyping), UML Diagrams (Use Case, Sequence, State Transition), Usability Testing

**Objectives:**

* Enhance Sunway University’s iZone enrolment portal with an automated waitlist system.
* Introduce **real-time slot updates**, **queue transparency**, and **notification alerts**.
* Reduce student stress during enrolment and ease administrative workload.

**Key Features:**

* Automated waitlist queue (First-Come First-Serve allocation).
* Real-time **Live Dashboard** with auto-refresh functionality.
* In-app and email **alert notifications** for seat availability and conflicts.
* User-centered design approach with iterative testing and feedback.

**Results:**

* Prototype developed in **Figma**, tested with Sunway students and lecturer.
* **System Usability Score (SUS): 80.75** → rated “Excellent Usability.”
* Students reported higher satisfaction, improved transparency, and confidence using the system.
* Improvements included clearer conflict alerts, visible notification icons, and smoother navigation.

**Impact:**
The Smart Waitlist System reduces manual monitoring, ensures fair seat distribution, and improves overall enrolment efficiency. It demonstrates how **automation + usability testing** can reshape university enrolment systems for better student and staff experiences.


## DobiQueen QR-Based Laundry Cycle Tracker

**Course:** Systems Analysis & Design
**Tools/Concepts:** SDLC (Waterfall), Figma (Prototyping), UML (Use Case, Activity, Context Diagrams), QR & Web-Based Tracking

**Objectives:**

* Enhance walk-in customer experience at **dobiQueen** (a Malaysian laundry SME).
* Introduce a **QR-based web tracker** to deliver real-time laundry cycle updates.
* Reduce idle waiting, missed collections, and machine turnover delays.

**Key Features:**

* QR code scan to start a session and track machine cycle.
* **Real-time countdown** displayed in browser.
* Push notifications (“5 minutes remaining” and “Cycle complete”).
* Admin features for machine registration, cycle monitoring, and usage logs.

**System Design Highlights:**

* Cloud-hosted client–server model for scalability across outlets.
* Mobile-first UI mock-up in **Figma**, optimized for quick interaction.
* Integration of activity, use case, and context diagrams to ensure requirements alignment.

**Expected Benefits:**

* Faster machine turnover and fewer disputes among walk-in customers.
* Lower frustration from missed cycle completions.
* Strengthened customer trust and operational efficiency.

**Reflection:**
This project demonstrated how **requirements analysis + usability-driven design** can improve customer experiences in traditional service environments. It also reinforced skills in SDLC documentation, stakeholder analysis, and creating scalable, technology-driven solutions.


## Predictive Modelling of Child Mortality Among Teen Mothers in Western Kenya

**Tools:** Python (Pandas, Scikit-learn, Matplotlib, Seaborn), Google Colab, Harvard Dataverse Dataset

**Objectives:**

* Build machine learning models to predict child mortality risk among children born to teenage mothers in Western Kenya.
* Compare performance of multiple algorithms (Logistic Regression, Decision Tree, Random Forest, SVM, Naive Bayes, XGBoost).
* Identify socio-economic, health, and psychological factors that influence child mortality.

**Key Analyses:**

* Data preprocessing: filtering for teenage mothers, encoding categorical variables, handling missing data, normalization.
* Applied oversampling and tuning techniques (SMOTE, class weighting, GridSearchCV) to address class imbalance.
* Evaluated models with multiple performance metrics (accuracy, precision, recall, F1-score, confusion matrix).

**Findings:**

* Logistic Regression achieved the most balanced performance (Recall = 66.8%, F1-score = 67.3%), making it the most reliable model for early risk identification.
* Models like Random Forest and Naive Bayes showed high accuracy (>89%) but poor recall, failing to detect many child death cases.
* Socio-economic (education, wealth index), psychological (mental health scores), and maternal factors (previous child mortality, loan burden) emerged as important predictors.
* Demonstrated that recall and F1-score are more important than accuracy in imbalanced, high-stakes datasets.

**Impact:**

* Supports the development of early-warning systems for NGOs and public health authorities.
* Provides actionable insights into high-risk populations to guide targeted interventions in low-resource settings.

[View Dataset on Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/QOPLVI)
