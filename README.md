# HealthandWellnessInfosys_iAccelerateHackathon
# Personalized Healthcare Recommendation System for Women

## 🚀 Project Overview
Women’s health needs are diverse and often underserved by generic healthcare approaches. This project leverages **Hierarchical Clustering** and **Gaussian Mixture Models (GMM)** to segment women based on their health needs and preferences. The system provides **personalized healthcare recommendations** to enhance service accessibility and improve health outcomes.

## 🔬 Problem Statement
Women’s healthcare lacks **personalization**, leading to **suboptimal health outcomes** and **limited access to tailored services**. The goal of this project is to segment women based on their health profiles using **data-driven clustering techniques** and recommend customized health strategies.

## 🎯 Objectives
- **Segment women’s health data** using **Hierarchical Clustering** and **GMM**.
- **Analyze health factors** such as age, BMI, blood pressure, and chronic conditions.
- **Provide personalized health recommendations** based on clustering results.
- **Improve accessibility to preventive healthcare insights** through a data-driven approach.

## 📊 Dataset
The dataset used includes **demographics, lifestyle factors, and health indicators** such as:
- **Age, BMI, Blood Pressure**
- **Physical Activity Levels**
- **Chronic Disease History**
- **Healthcare Access & Lifestyle Choices**

## 🔎 Methodology
1️⃣ **Data Preprocessing:**
   - Handle missing values, standardize features, and encode categorical variables.
   
2️⃣ **Clustering Algorithms:**
   - **Hierarchical Clustering:** Creates a dendrogram to determine the optimal number of clusters.
   - **Gaussian Mixture Model (GMM):** Assigns probabilities to different health groups.

3️⃣ **Recommendation System:**
   - Maps clusters to **tailored health recommendations** based on disease risks.

4️⃣ **Visualization & Evaluation:**
   - Dendrograms, cluster distribution analysis, and validation using silhouette scores.

5️⃣ **Results & Deployment:**
   - Save recommendations in a CSV file for easy access.

## 💻 Technologies Used
- **Python, Pandas, NumPy, Seaborn, Matplotlib** (Data Processing & Visualization)
- **scikit-learn** (Clustering & Machine Learning)
- **Flask/Django** (For web-based deployment - optional)

## 📈 Key Features
✅ **Clustering of women’s health profiles** using advanced ML techniques.
✅ **Disease risk prediction** using probabilistic modeling.
✅ **Personalized recommendations** for diet, lifestyle, and medical check-ups.
✅ **Easy CSV export** of insights for future analysis.

## 📌 How to Run the Project
### 🏗 Running in Google Colab
1️⃣ Upload the dataset (`enhanced_women_health_25_diseases.csv`).
2️⃣ Copy and run the provided Python script.
3️⃣ View clustering results and health recommendations.
4️⃣ Download the `women_health_clusters_recommendations.csv` for insights.

### 💻 Running in VS Code
1️⃣ Install dependencies: `pip install pandas numpy seaborn scikit-learn matplotlib`
2️⃣ Place the dataset in your working directory.
3️⃣ Run the script: `python women_health_analysis.py`
4️⃣ View recommendations in the generated CSV file.

## 📜 Sample Output
| Age | BMI  | Blood Pressure | Cluster_GMM | Health Recommendation |
|-----|------|---------------|-------------|------------------------|
| 32  | 24.5 | 120/80        | 1           | Monitor blood pressure, reduce sodium intake, and maintain hydration. |
| 45  | 28.3 | 140/90        | 3           | Regular cardiovascular check-ups, low-fat diet, and stress management. |

## 🎯 Future Enhancements
- **Web-based Interface** for real-time health assessment.
- **Deep Learning Integration** for enhanced disease risk prediction.
- **Integration with Wearable Devices** for continuous health monitoring.

## 📢 Connect & Collaborate
I’m excited to share this project and would love to hear your thoughts! 🚀 If you're interested in **AI-driven healthcare solutions**, let’s connect and collaborate! 🤝

#MachineLearning #HealthcareAI #WomenHealth #DataScience #Clustering #PersonalizedMedicine

DONE BY KAVIYA P
