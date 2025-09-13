Interactive Sales Performance Dashboard 📊
A live, interactive dashboard that analyzes and visualizes sales data to uncover key business insights, including top-performing products and regional revenue trends.

➡️ View the Live Demo Here (Remember to replace 'your-username' with your actual GitHub username)

Dashboard Screenshot
Replace this image with a screenshot of your actual dashboard.

🎯 Project Goal
The primary goal of this project was to demonstrate end-to-end data analysis skills by taking a raw dataset, processing it using JavaScript, and presenting the findings in a clear, interactive, and easy-to-understand web-based dashboard.

🛠️ Tech Stack & Tools
Category

Technology / Tool

Purpose

Frontend

HTML5, CSS3

Structure and styling of the dashboard.

Core Logic

Vanilla JavaScript

Data processing, KPI calculation, and chart rendering.

Data Parsing

PapaParse.js

To read and parse the .csv data file directly in the browser.

Data Visualization

Chart.js

To create responsive and interactive bar and doughnut charts.

✨ Key Features
📈 Key Performance Indicators (KPIs): At-a-glance metrics for Total Revenue, Total Units Sold, Top Performing Region, and Best Selling Product.

📊 Interactive Charts: Responsive bar and doughnut charts visualize revenue by region and units sold by product.

⚙️ In-Browser Data Processing: The entire data analysis pipeline—from reading the CSV to rendering charts—is handled on the client-side using JavaScript.

Clean & Modern UI: A simple, intuitive interface designed for clear data presentation.

⚙️ Data Analysis Process
Data Loading: The project uses the PapaParse library to fetch and parse the sales_data.csv file into a usable JSON format.

Data Aggregation: Custom JavaScript functions iterate through the data to aggregate key metrics, such as calculating total revenue per region and total units sold per product.

KPI Calculation: The aggregated data is used to calculate the main KPIs, identifying the top performers based on revenue and sales volume.

Data Visualization: The processed data is then passed to Chart.js to render the final bar and doughnut charts, providing a clear visual summary of the findings.

🚀 How to Run Locally
This project requires no server or complex setup.

Clone the repository:

git clone [https://github.com/your-username/sales-dashboard.git](https://github.com/your-username/sales-dashboard.git)

Navigate to the directory:

cd sales-dashboard
