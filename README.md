# elevate-labs-task-12
KMeans Customer Segmentation – Wholesale Customers Dataset
📌 Project Overview

This project demonstrates unsupervised customer segmentation using the KMeans clustering algorithm.
The goal is to group customers based on their annual spending behavior so businesses can better understand customer types and tailor strategies accordingly.

The project is implemented in Python using Scikit-learn, with visualizations created using Matplotlib and Seaborn.

🎯 Objectives

Perform customer segmentation using KMeans

Apply feature scaling for distance-based clustering

Determine the optimal number of clusters using the Elbow Method

Visualize and interpret customer segments

Export a segmented dataset for business use

📂 Dataset

Wholesale Customers Dataset

Records: 440 customers

Features represent annual spending in different product categories

Dataset Columns

Fresh

Milk

Grocery

Frozen

Detergents_Paper

Delicassen

Channel

Region

Channel and Region are dropped during clustering as they do not contribute meaningfully to distance-based segmentation.

🛠️ Tools & Technologies

Python

Google Colab

Scikit-learn

Pandas & NumPy

Matplotlib & Seaborn

Alternative Tools (Optional):

Power BI (clustering visuals)

Orange Data Mining

🔍 Methodology

Load and inspect the dataset

Drop non-relevant identifier columns

Apply StandardScaler to normalize features

Run KMeans for multiple values of K

Plot the Elbow Curve to find optimal clusters

Train KMeans using selected K

Assign cluster labels to each customer

Visualize clusters using scatter plots

Interpret and label customer segments

Export segmented data as CSV

📊 Key Visualizations

Elbow Plot – to determine optimal number of clusters

Cluster Scatter Plot – visual comparison of customer groups

📈 Results & Interpretation

The model successfully groups customers into distinct segments such as:

Low-spending customers

Medium-value customers

High-value wholesale buyers

These segments can be used for:

Targeted marketing

Inventory planning

Personalized offers

Business decision-making

📁 Project Structure
├── task_12.ipynb                     # Google Colab / Jupyter Notebook
├── Wholesale customers data.csv      # Original dataset
├── segmented_customers.csv           # Final clustered output
├── README.md                         # Project documentation

📤 Output

<img width="607" height="470" alt="Image" src="https://github.com/user-attachments/assets/37eb8f7c-abf4-49d2-b522-5f0fdcffdd19" />


<img width="606" height="410" alt="Image" src="https://github.com/user-attachments/assets/c7e39279-3f0e-48b3-aaf6-c84acf8458ca" />


✅ Elbow Method Plot

✅ Cluster Visualization

✅ Segmented Dataset (segmented_customers.csv)

🚀 How to Run

Clone the repository

Open task_12.ipynb in Google Colab or Jupyter Notebook

Upload the dataset or load it from Kaggle

Run all cells sequentially

Download the final segmented CSV
