Submitted By: Daniel Ryan So
Submitted To: Gerard Ompad

# **Target Trial Emulation with Clustering** 🏥📊  

## **Overview**  
This project implements **Target Trial Emulation (TTE)** using observational data while integrating **clustering techniques** to improve subgroup analysis and causal inference. The goal is to assess whether clustering enhances **treatment effect estimation, survival probability predictions, and hazard ratio interpretation**.  

## **Key Features** 🚀  
✔ **Survival Analysis** using **Kaplan-Meier Curves** and **Cox Proportional Hazards Models**  
✔ **Clustering Integration (TTE-v2)** to identify **subgroups with distinct survival patterns**  
✔ **Inverse Probability Weighting (IPW)** for **confounding control**  
✔ **Performance Metrics**: **AIC, C-Index, Silhouette Score, PCA Visualization**  
✔ **Comparative Analysis** of **TTE vs. TTE-v2**  

## **Methodology** 📌  
1. **Data Processing & Cleaning**: Handle missing values, censoring, and treatment assignment.  
2. **Survival Modeling**: Kaplan-Meier curves, Log-Rank tests, and Restricted Mean Survival Time (RMST).  
3. **Clustering Mechanism**: Implement **K-Means, Hierarchical Clustering, and PCA Visualization**.  
4. **Hazard Ratio Comparison**: Evaluate the impact of clustering on **Cox model estimates**.  
5. **Validation & Interpretation**: Use statistical metrics to **assess subgroup stability and causal validity**.  

## **Results & Findings** 📊  
🔹 Clustering improves **subgroup identification and survival heterogeneity analysis**.  
🔹 Cox model results indicate **enhanced hazard ratio interpretation** in clustered models.  
🔹 Risk stratification using clustering may improve **personalized treatment strategies**.  
🔹 Combining **machine learning clustering with causal inference** enhances **observational survival analysis**.  

## **Installation & Usage** ⚙️  
### **🔹 Requirements**  
Ensure you have the following dependencies installed:  
```bash
pip install lifelines numpy pandas scikit-learn matplotlib seaborn
