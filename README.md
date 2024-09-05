# Power BI Dashboard - Company A Batch and Sample Turnaround Times

## Overview
This Power BI dashboard was designed to track and visualize Company A’s sample and batch turnaround times (TAT). The dashboard provides insights into various stages of the sample processing lifecycle. It consists of three main pages:
- **Overall TAT**
- **Sample Status**
- **Daily Statistics**

Each page helps in monitoring and optimizing the operational efficiency of Company A's processing system. This Power BI Report was used to identify bottlenecks and slow areas in the sample processing workflow. By pinpointing where delays occur, data analysts were able to provide actionable feedback to the operations team, allowing them to improve processing times and enhance overall operational efficiency.

## Dashboard Pages

### 1. Overall TAT
The "Overall TAT" page provides a summary of the processing times for all samples. It also shows the batch code and the number of samples in each batch, allowing the operations team to quickly identify which batch they are currently working on, the number of samples within it, the average times taken to process a sample, and the number of samples or batches completed by date. 

This includes key performance indicators such as the time for How long before a Porter Picks up a batch, Transportation time to the Lab, Lab Analysis, and the overall TAT.

![Overall TAT (clean)](https://github.com/user-attachments/assets/2b3294ca-8215-4ed7-a09d-1b0e504a3434)

#### Key Metrics:
- Average Porter Pickup Time: 233 mins
- Average Transport Time: 283.02 mins
- Porter Pick-up: 14.17 mins
- Number of Samples Processed: 153,307
- Number of Batches Processed: 6,079

### 2. Sample Status
The "Sample Status" page tracks the status of each sample, including whether it was sent to the Lab, rejected, or awaiting validation. It shows the detailed timeline of each sample’s journey from collection to validation.

![Sample Status (clean)](https://github.com/user-attachments/assets/bb2c9b70-1374-4f31-a882-7615bd814307)

#### Key Features:
- Summary of samples that have been processed, rejected, or are awaiting validation.
- Tracking the lab check-in and validation timelines for each sample.

### 3. Daily Statistics
The "Daily Statistics" page provides a daily breakdown of samples processed, including positive and negative results and the percentage of samples processed within the TAT.

![Daily Statistics (clean)](https://github.com/user-attachments/assets/2426e1e5-c987-4b90-9b1f-40da08477b9b)

#### Key Insights:
- Daily trends in sample processing, including total samples, positive results, and negative results.
- A visual representation of samples processed within the Turnaround Time (TAT).
- Overall processing statistics: 
  - Total Samples Processed: 153,958
  - Percentage of Samples Processed within TAT: 92.83%

## Technologies Used
- **Data Source:** Sample and Batch processing data, extracted from the MySQL database server.
- **SQL:** Utilized to efficiently query and extract relevant data from the MySQL database for use in Power BI.
- **Power BI:** For creating interactive visualizations and data reports.
- **DAX (Data Analysis Expressions):** Utilized in Power BI to create custom measures and enhance the visualizations.
- **Visualization Types:** Bar charts, line graphs, tables, and summary cards.

## Contact Information
Feel free to reach out if you have any questions or would like to discuss the insights from this dashboard:
- **Email:** syahrein01@gmail.com
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/syahrein/)

