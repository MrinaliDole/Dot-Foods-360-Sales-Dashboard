📌 Project Overview

As part of a graduate analytics project, our team partnered with Dot Foods, North America’s largest food redistributor, to unify fragmented sales and operations data into a 360° analytics solution. Sales representatives previously relied on multiple disconnected reports to track customer behavior, shipment efficiency, and performance trends.

Our objective was to design a tool that combined machine learning–based customer segmentation with a dynamic Power BI dashboard, giving Dot Foods’ sales and operations teams a scalable, data-driven way to make decisions.

📝 Concise Narrative Summary

Working in a team, we processed and analyzed over 91,000 customer records to build a decision-making framework for Dot Foods. Using Python, we handled missing values, capped outliers, and normalized skewed features with log transformations. We applied K-Means clustering with PCA visualization to identify four distinct customer segments ranging from high-frequency strategic buyers to smaller, infrequent clients.

These insights were integrated into a Power BI dashboard, designed to track KPIs such as Dock Time, PO Count, Pallet Count, and Item Spread across 13 time periods. The dashboard enabled filtering by region, tier, and customer type—helping Dot Foods identify bottlenecks (e.g., slow dock times, low shipment efficiency) and tailor sales strategies to each customer segment.

📦 Key Deliverables

Python Notebooks (cluster-analysis.ipynb, Dot_foods_2.ipynb) – EDA, outlier handling, clustering, PCA visualization

Clean Dataset (clean_with_clusters.csv) – customer-level segmentation outputs

Business Problem Statement (problem statement.docx) – project scope & goals

Power BI Dashboard – 360° customer and sales performance view

📊 Key Insights

Processed 91,000+ customer records into a clean dataset with engineered features

Segmented customers into 4 clusters using K-Means (validated via PCA)

Normalized skewed metrics (e.g., Cases/Line, Dock Time) for robust modeling

Built dashboards with KPIs across 13 time periods for sales and operational analysis

Identified critical insights:

Strategic vs. small-scale clients by frequency & shipment size

Bottlenecks in dock times and loading efficiency

Peer comparisons by tier for benchmarking



🛠️ Tools & Methods

Python: pandas, scikit-learn (K-Means, PCA), matplotlib, seaborn

Power BI: ETL pipelines, data modeling, slicers, interactive reports

Data Processing: outlier capping (IQR), log transformations, missing data imputation

Machine Learning: unsupervised clustering (K-Means)

Visualization: PCA scatterplots, heatmaps, tier benchmarking dashboards



🌍 Business Impact

Unified customer insights in a single dashboard (vs. fragmented manual reporting)

Customer segmentation enabled tailored outreach strategies

Operational efficiency gains by identifying shipment inefficiencies

Actionable benchmarks provided sales reps with peer comparisons across tiers



🔬 Technical Depth 

Developed ETL pipelines in Power BI to integrate raw data into dashboards

Applied unsupervised learning for customer segmentation

Used PCA dimensionality reduction to visualize cluster separation

Engineered features to correct skewness and improve clustering accuracy

Designed dashboards with dynamic slicers for region, tier, and time-based analysis



📈 Dashboard Highlights

Customer Segmentation View – filter by clusters, regions, tiers

Operational KPIs – Dock Time, PO Count, Pallet Count, Item Spread

Trend Analysis – 13-period historical view of performance

Heatmaps – highlight bottlenecks in efficiency and client management
