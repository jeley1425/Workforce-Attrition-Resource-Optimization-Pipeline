Institutional Workforce Attrition & Resource Optimization Pipeline

Business Case Overview
High employee turnover introduces severe operational friction, regulatory compliance gaps, and steep budgetary drains. This data science project establishes an end-to-end predictive machine learning pipeline designed to identify early workforce flight risks, segment employee vulnerability cohorts, and quantify the total financial exposure of institutional attrition.

Technical Architecture & Workflow
The project is built entirely in Python using Google Colab and follows a 5-phase data science lifecycle:

- Phase 1: Ingestion & Schema Definition, Generated a robust dataset tracking 500 employee records across diverse operational vectors (income, commute, overtime).
- Phase 2: Feature Engineering – Synthesized raw behavioral signals into a custom (Workplace Friction Index) to capture abstract organizational stress vectors mathematically.
- Phase 3: Unsupervised Segmentation (K-Means Clustering) – Implemented a geometric clustering algorithm to automatically group the workforce into 3 distinct vulnerability tiers based on income and friction.
- Phase 4: Predictive Supervised Modeling (Random Forest) – Trained an ensemble classification model on an 80/20 data split to predict individual attrition probabilities.
- Phase 5: Financial Impact Simulation – Vectorized operational cost models assuming an conservative $15,000 replacement baseline per employee to translate model predictions directly into fiscal risk exposure.

## 📈 Key Visualizations & Deliverables
The final dashboard automatically renders a statistical scatter plot mapping Monthly Income vs. Workplace Friction, cleanly color-coded by the engineered K-Means vulnerability clusters, allowing executive teams to instantly isolate high-risk operational segments.

## 💻 Tech Stack Used
- Language: Python 3
- Environment: Google Colab / Jupyter Notebooks
- Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

