**Hostel Fee Payment Analysis using Python & Gradio**

This project analyzes hostel fee payment data of students to identify early, on-time, late, and unpaid payments.
It also provides an interactive Gradio web interface to upload and preview CSV files easily.

**Project Description**
● Hostel fee management is an important administrative task. This project uses Python data analysis tools to:
● Analyze payment delays
● Categorize payment status
● Generate statistical summaries
● Visualize data using charts
● Upload and preview CSV files through a web UI

**Features**
📂 Upload CSV file using Gradio
📋 Preview uploaded data in table format
🧮 Calculate payment delay in days
🏷️ Classify payment status (Early / On Time / Late / Not Paid)
📊 Graphical visualizations:
● Payment status bar chart
● Student-wise fee amount bar chart
● Student-wise payment delay chart
● Payment status pie chart

**Technologies Used**
● Python
● Pandas
● NumPy
● Matplotlib
● Seaborn
● Gradio

**Hostel-Fee-Payment-Analysis/**
│
├── hostel_fee_payment_dataset.csv
├── analysis.py / analysis.ipynb
├── gradio_app.py
├── README.md

Dataset Details

The dataset includes the following columns:

Column Name	                 Description
Student_ID	          Unique student identifier
Student_Name	           Name of the student
Due_Date	               Hostel fee due date
Payment_Date	           Actual payment date
Fee_Amount	              Hostel fee amount
Delay_Days	          Difference between payment date and due date
Payment_Status	          Payment category

**Payment Status Logic**
● Delay_Days < 0 → Early
● Delay_Days = 0 → On Time
● Delay_Days > 0 → Late
● Missing Payment → Not Paid

**Gradio Interface**
● Upload a .csv file
● View the dataset instantly
● Can be extended for live analysis and graphs

**Use Cases**
● College mini-project
● Data analysis learning project
● Hostel administration analysis
● Python + Pandas practice
