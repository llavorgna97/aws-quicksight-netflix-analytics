Visualizing Netflix Data with AWS S3 and Amazon QuickSight

This project demonstrates how I used Amazon S3 and Amazon QuickSight to analyze and visualize a dataset of Netflix titles.
The objective was to practice working with cloud-based data storage and dashboard creation tools.

🎯 Project Overview

I uploaded a dataset (netflix_titles.csv) to Amazon S3, along with a manifest.json file that defines the structure of the data.
Then, I connected the dataset to Amazon QuickSight, performed data exploration, and built several visualizations to uncover insights about Netflix content.

This exercise helped me practice working with:

Cloud data storage (S3 buckets)

Manifest configuration for external datasets

Data visualization in QuickSight

Dashboard composition and filtering

🛠️ Tools & Services Used
Service / Concept	Description
Amazon S3	Used to store the dataset and manifest file
Amazon QuickSight	Used to visualize and explore the data
manifest.json	Informs QuickSight how to read and interpret the dataset
Data Visualization Techniques	Created graphs and dashboards for insights
Dataset Refresh	Learned how to refresh data in QuickSight to reflect updates
🔧 Step-by-Step Process
1. Uploading Data to S3

Uploaded netflix_titles.csv and manifest.json to an S3 bucket.

Updated the manifest.json to ensure it pointed to the correct S3 URI.

This step ensures QuickSight is able to correctly locate and interpret the dataset.

2. Setting Up QuickSight

Created a QuickSight account (free trial available).

Configured necessary permissions to allow access to the S3 bucket.

3. Connecting the Dataset

In QuickSight, selected S3 as the data source.

Imported the dataset using the manifest.json file.

4. Creating Visualizations

Built visualizations by dragging and dropping data fields into the canvas.

Example insight: Number of titles released each year (donut chart).

Added filters to focus on content released after 2015.

5. Creating the Dashboard

Refined titles and visual formatting for clarity.

Exported the dashboard as the final presentation output.

📊 Example Visual Insight

A visualization that breaks down the number of Netflix films and TV shows released per year was created by:

Dragging the release_year field into the canvas

Changing the auto-selected bar chart into a donut chart

Applying optional date filters to narrow the range

📦 Files Included
File	Description
netflix_titles.csv	Dataset containing Netflix content metadata
manifest.json	Configuration file used for dataset import in QuickSight
