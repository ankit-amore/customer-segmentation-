Customer Segmentation using K-Means Clustering
Overview

This project is a web application built with Streamlit that performs Customer Segmentation using the K-Means
Clustering algorithm. The application allows users to upload a customer dataset, visualize the optimal number 
of clusters using the Elbow Method, and explore customer segments through interactive visualizations.

Features
Upload customer dataset in CSV format
Preview uploaded dataset
Determine optimal clusters using the Elbow Method
Select the number of clusters interactively
Perform K-Means clustering
Visualize customer segments
Display cluster centroids
Interactive web interface using Streamlit
Technologies Used
Python
Streamlit
NumPy
Pandas
Matplotlib
Scikit-learn
Dataset

The application is designed to work with the Mall Customers dataset containing attributes such as:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1–100)

The clustering is performed using:

Annual Income
Spending Score
Project Structure
customer-segmentation/
│
├── customer_segmentation_analysis.py
├── requirements.txt
├── README.md
└── Mall_Customers.csv
Installation
1. Clone the Repository
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation
2. Create Virtual Environment
python -m venv .venv
3. Activate Virtual Environment

Windows:

.venv\Scripts\activate

Linux / macOS:

source .venv/bin/activate
4. Install Dependencies
pip install -r requirements.txt
Running the Application

Start the Streamlit application:

streamlit run customer_segmentation_analysis.py

The application will open automatically in your browser.

How It Works
Upload a customer dataset in CSV format.
Preview the uploaded data.
View the Elbow Method graph to identify an appropriate number of clusters.
Select the desired number of clusters using the slider.
K-Means clustering is applied to the data.
Visualize customer segments and cluster centroids.
Machine Learning Algorithm
K-Means Clustering

K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters.

Steps:

Choose the number of clusters (K).
Initialize centroids.
Assign data points to the nearest centroid.
Update centroid positions.
Repeat until convergence.
Output

The application generates:

Dataset preview
Elbow Method graph
Clustered dataset
Customer segmentation scatter plot
Cluster centroids
Requirements
streamlit
numpy
pandas
matplotlib
scikit-learn
Future Enhancements
Support additional clustering algorithms
Download clustered results as CSV
Interactive Plotly visualizations
Automatic cluster recommendation
Data preprocessing options
Author

Developed as a Machine Learning and Data Science project using Python and Streamlit.

License

This project is open-source and available under the MIT License.
