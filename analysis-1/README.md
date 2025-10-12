# Insurance Complaints Analysis

This project analyzes a dataset of insurance company complaints, resolutions, statuses, and recoveries. The goal is to explore the data, identify trends, and visualize key insights to better understand the performance of insurance companies in handling complaints.

---

## Dataset

The dataset used in this project is `Insurance_Company_Complaints__Resolutions__Status__and_Recoveries_data.csv`. It contains the following columns:

- **Company**: Name of the insurance company.
- **File No.**: Unique identifier for each complaint.
- **Opened**: Date the complaint was opened.
- **Closed**: Date the complaint was resolved/closed.
- **Coverage**: Type of coverage (e.g., Group, Individual).
- **SubCoverage**: Subcategory of coverage.
- **Reason**: Reason for the complaint.
- **SubReason**: Subcategory of the reason.
- **Disposition**: Outcome of the complaint.
- **Conclusion**: Final resolution of the complaint.
- **Recovery**: Amount recovered (if any).
- **Status**: Current status of the complaint (e.g., Open, Closed).

---

## Features

- **Data Cleaning**: Handles missing values and ensures data consistency.
- **Date Conversion**: Converts `Opened` and `Closed` columns to datetime format for time-based analysis.
- **Time Taken Analysis**: Calculates the time taken to resolve complaints.
- **Grouping and Aggregation**: Groups data by company, reason, and other fields to identify trends.
- **Visualization**: Creates horizontal bar charts, pie charts, and other visualizations to present insights.

---

## Key Insights

1. **Time Taken**:
   - The average time taken to resolve complaints is calculated and grouped by reason.
   - Time differences are converted to days for consistency.

2. **Company Performance**:
   - Companies with the highest and lowest number of complaints are identified.
   - Complaints are categorized into high, mid, and low ranges based on frequency.

3. **Resolutions**:
   - The distribution of complaint conclusions (e.g., "Claim Paid", "Satisfied") is visualized.

---

## Visualizations

- **Horizontal Bar Charts**:
  - Visualize the distribution of complaint conclusions in descending order.
- **Pie Charts**:
  - Show the proportion of complaints for companies with the highest complaint counts.
- **Time vs. Recovery**:
  - Analyze the relationship between time taken to resolve complaints and recovery amounts.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required packages:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the Jupyter notebook for data examination:
   ```bash
   jupyter notebook data_examination.ipynb
   ```