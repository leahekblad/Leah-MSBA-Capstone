# Leah-MSBA-Capstone

# Delivery Strategy Optimization: Identifying Growth-Ready Customers

## Summary of Business Problem and Project Objective

Swire Coca-Cola (SCCU) is looking to enhance its delivery logistics by transitioning low-volume customers to more cost-effective third-party delivery services (known as Alternate Routes to Market or ARTM, via white trucks). However, this cost-saving initiative may inadvertently shift high-potential customers—those capable of significant growth—to lower-touch delivery experiences, risking lost revenue and weakened customer relationships. The goal of this project is to build a reliable, data-driven approach to identify and protect growth-ready customers, ensuring high-touch services (red truck delivery) are reserved for the most valuable accounts.

---

## Our Group’s Solution

Our team built and explored 20+ advanced models and created an interactive Tableau dashboard intended to allow Swire to view and engage with descriptive analytics:

- Allow for real-time ‘what-if’ analyses, enabling logistics teams to determine optimal White Truck vs. Red Truck assignments.
- Segment customers based on purchase behavior and volume thresholds
- Predict high-potential customers currently on ARTM
- Drive automated truck assignments, lower costs, and enhance efficiency.

---

## My Contribution to the Project

I contributed to both the data engineering and modeling components of the project. My key responsibilities included:

- Cleaning and preprocessing large transactional datasets (~1 million records)
- Creating features that capture customer purchasing consistency and growth potential
- Training and evaluating machine learning models to classify high-potential customers
- Assisting with documentation and visualizations for our interactive dashboard

---

## Business Value of the Solution

This project enables Swire to:

- Preserve growth opportunities by identifying and retaining promising customers on red truck delivery  
- Increase cost-efficiency by confidently transitioning low-potential accounts to ARTM  
- Support long-term strategic planning through data-driven insights and predictive modeling  
- Strengthen customer relationships by aligning service levels with account potential  

---

## Challenges Faced

Our group encountered several key challenges:

- Asynchronous data structure: The order lifecycle was split across ordered, loaded, and delivered dates, requiring careful alignment  
- Volume standardization: Converting between cases and gallons for different product types needed a unified metric  
- Feature selection: Differentiating truly high-potential customers from those with temporary volume spikes 

Despite these hurdles, we successfully built scalable models and refined our feature engineering.

---

## What I Learned

This project deepened my skills in:

- Feature engineering: Crafting meaningful predictors from complex transactional data  
- Customer segmentation: Applying unsupervised learning to inform strategic decisions  
- Business framing: Translating technical results into actionable recommendations  
- Collaboration: Setting expectations from the beginning and having consistent meetings to contribute effectively in a team environment  

---

## Writing and Professional Use of Notebooks

Throughout the project, we maintained clean R Markdown notebooks with professional documentation. All notebooks include:

- Section headers and markdown summaries  
- Inline comments to explain key logic  
- Visual outputs for model evaluation and insights  
- Clean organization for reproducibility  
