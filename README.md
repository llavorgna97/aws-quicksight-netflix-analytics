# Visualizing Netflix Data with AWS S3 and Amazon QuickSight

This project demonstrates how I used **Amazon S3** and **Amazon QuickSight** to analyze and visualize a dataset of Netflix titles.  
The objective was to practice working with **cloud-based data storage** and **dashboard creation tools**.

---

## 🎯 Project Overview

I uploaded a dataset (`netflix_titles.csv`) to **Amazon S3**, along with a `manifest.json` file that defines the structure of the data.  
Then, I connected the dataset to **Amazon QuickSight**, performed data exploration, and built several visualizations to uncover insights about Netflix content.

This project allowed me to learn and practice:

- Cloud data storage using **S3 buckets**
- **Manifest configuration** for external datasets
- Data visualization techniques in **QuickSight**
- **Dashboard composition** and filtering to highlight insights

---

## 🛠️ Tools & Services Used

| Service / Concept | Description |
|------------------|-------------|
| **Amazon S3** | Used to store the dataset and manifest file |
| **Amazon QuickSight** | Used to visualize and explore the data |
| **manifest.json** | Tells QuickSight how to read and interpret the dataset |
| **Data Visualization Techniques** | Created charts and dashboards to analyze information |
| **Dataset Refresh** | Learned how to update the dataset and reflect changes in visuals |

---

## 🔧 Step-by-Step Process

### 1. Uploading Data to S3
- Uploaded `netflix_titles.csv` and `manifest.json` into an Amazon S3 bucket.
- Updated the manifest file to ensure it pointed to the correct S3 URI.
- This step is essential so QuickSight can locate and interpret the dataset correctly.

### 2. Setting Up QuickSight
- Created a QuickSight account (free trial available).
- Configured required permissions to allow QuickSight to access the S3 bucket.

### 3. Connecting the Dataset
- In QuickSight, selected **S3** as the data source.
- Imported the dataset using the **manifest.json** file.

### 4. Creating Visualizations
- Built visualizations by dragging and dropping data fields in QuickSight.
- Example insight: **Number of titles released each year**, displayed as a **donut chart**.
- Added filters to highlight only content released after **2015**.

### 5. Creating the Dashboard
- Refined chart labels and formatting for readability.
- Exported the dashboard as the final presentation output.

---

## 📊 Example Visual Insight

A visualization showing the number of TV Shows and Movies released each year was created by:

1. Dragging the **release_year** field into the canvas  
2. Changing the chart type from *bar chart* to *donut chart*  
3. (Optional) Adding date filters to limit the range  

---

## 📦 Files Included

| File | Description |
|------|-------------|
| `netflix_titles.csv` | Dataset containing Netflix content metadata |
| `manifest.json` | Configuration file used for dataset import into QuickSight |

---

