Intrusion Detection System - EDA on DDoS Network Traffic
This project performs Exploratory Data Analysis (EDA) on the Friday-WorkingHours-Afternoon-DDoS.csv dataset. The goal is to explore patterns in network traffic and distinguish between normal and DDoS attack traffic using visual analysis.

📁 Dataset

Name: Friday-WorkingHours-Afternoon-DDoS.csv
Source: CICIDS2017 dataset (download separately)
Format: CSV
Important Features:
Flow Duration
Total Fwd/Backward Packets
Length of Fwd/Bwd Packets
Flow Bytes/s, Packets/s
Label (Normal or Attack)
📊 Visualizations Performed

Label Distribution
Bar plot showing normal vs. attack traffic.
Numerical Feature Distributions
Histograms for packet counts, durations, and flows.
Pairwise Feature Relationships
Pairplot highlighting how features relate by label.
Correlation Matrix
Heatmap to explore correlation among numerical features.
Boxplot Comparison
Flow Duration across normal vs attack traffic.
🛠️ Libraries Used

Python 3
pandas
seaborn
matplotlib
✅ Skills Highlighted

Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Network Traffic Visualization
Intrusion Detection Insights
▶️ How to Run

Ensure the dataset is available at the specified path.
Install required libraries:
pip install pandas matplotlib seaborn
Run the script:
python "Intrusion detection system.py"
📄 License

This project is intended for learning and research purposes.

🖼️ Screenshots

🖥️ Terminal Output (First Few Rows of the Dataset)

Terminal Output

📊 Label Distribution Plot

Label Distribution
