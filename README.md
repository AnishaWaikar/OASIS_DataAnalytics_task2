# OASIS_DataAnalytics_task2
🧭 Task 2 Customer Segmentation Using Python

🎯 Objective

To uncover meaningful customer groups using their spending habits and profile attributes, enabling marketing decisions that are smarter than generic promotions. By segmenting customers based on household composition, category spending, and recency of purchases, the goal was to identify high-value segments, discount-sensitive buyers, and opportunity clusters for targeted retention strategies.

📝 Steps Performed

Dataset Exploration & Feature Familiarization
Reviewed dataset structure, missing values, and statistical patterns to understand purchase behavior and household attributes.

Data Preparation & Cleaning
Filled missing values (notably median imputation for Income) and selected behavior-driven features such as wine, meat, fish, gold, sweets, and total expenditure — along with demographic indicators (Kidhome, Teenhome) and purchase recency.

Feature Scaling for Fair Comparison
Applied StandardScaler to ensure all spending variables contributed equally to the clustering process, preventing high-range features from dominating.

Cluster Discovery & Selection
Used the Elbow Method to identify a suitable number of clusters by evaluating reduction in within-cluster variance.

Customer Segmentation via K-Means
Assigned customers to clusters based on behavioral similarity, creating distinct customer groups supporting varied marketing goals.

Cluster Visualization using PCA
Reduced multi-dimensional data into two principal components to visually represent customer grouping, making cluster separation intuitive and comparable.

Cluster Profiling & Strategic Insight Extraction
Compared average spending and household metrics to understand each cluster’s business value and suggested targeted strategies — loyalty offers for high spenders, bundles for lower spenders, and cross-selling for mid-range profiles.

🛠 Tools Used

Core Libraries: Pandas, NumPy, Scikit-learn

Visualizations: Matplotlib, Seaborn

Techniques: StandardScaler, Elbow Method, K-Means Clustering, Principal Component Analysis (PCA)

📌 Outcome

The clustering uncovered clear behavioral patterns among customers.
Premium-spending clusters emerged as ideal targets for loyalty programs and exclusive campaigns, while value-driven clusters benefitted from promotional bundles and retention nudges. These differentiated insights transform marketing from broad outreach into data-guided personalization, improving the likelihood of conversion, brand affinity, and customer lifetime value.
