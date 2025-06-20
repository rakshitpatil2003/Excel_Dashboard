📊 Universal Excel Dashboard Generator
A comprehensive web-based tool for generating actionable, insight-driven dashboards from Excel datasets of MBA-ITBM students. Built to help SCIT placement and academic committees analyze student demographics, academic backgrounds, specialization trends, and placement readiness.

🚀 Features
📁 Upload Excel files (.xlsx, .xls)

✅ Data validation with error reporting

📈 Generates multi-sheet Excel dashboards including:

Executive Summary with KPIs

Specialization Analysis

Demographics Deep Dive

Data Quality Report

Pre-structured Chart Data for visualization

Instructions for creating interactive charts

🗂️ Downloadable Sample Format with guidelines

🖥️ 100% Client-side processing — no server needed

📂 Folder Structure
pgsql
Copy
Edit
excel-dashboard-generator/
├── index.html   # Complete project file
└── (optional) datasets/ & generated/ folders for local organization
📝 Excel Data Format
Your Excel file must follow this structure (sample downloadable from the app):

Column Name	Example
Serial No.	1
Name	John Doe
Course	MBA - ITBM
Age	24
Gender	Male
MBA-ITBM Specialization (Major)	Information Security Management
MBA-ITBM Specialization (Minor)	Software Solutions Management
10th Percentage	85.5
10th Year of Passing	2015
12th Percentage	78.2
12th Year of Passing	2017
Diploma Percentage	N/A
Diploma Year of Passing	N/A
Graduation Course	B.Tech.
Graduation Specialization	Computer Science
Graduation Year of Passing	2021
Total Work Experience (In Months)	18

⚠️ Important: Use 'N/A' for missing values. Percentage values must be 0-100. Gender must be 'Male' or 'Female'.

📦 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/excel-dashboard-generator.git
cd excel-dashboard-generator
Open index.html in your browser

OR use Live Server extension in VS Code for local server experience.

Upload your Excel file → Click Generate Dashboard → Download auto-generated .xlsx file.

Use "📋 Chart Instructions" sheet inside the downloaded Excel to create interactive charts in minutes.

🎨 Visualizations Supported
🎯 Specialization Pie Chart

📊 Age Distribution Bar Chart

🕳️ Experience Doughnut Chart

🏫 Academic Background Horizontal Bar Chart

📑 Chart Creation Guide
Step-by-step visualization creation guide is embedded inside the generated Excel file for ease of use.

💻 Technologies Used
HTML5, CSS3 (No frameworks)

Vanilla JavaScript

SheetJS (xlsx.full.min.js)

🏫 Developed For
Symbiosis Centre for Information Technology (SCIT)
For internal use by academic and placement committees, data analysis teams, and student coordinators.

📬 Contribution & Feedback
Feel free to raise issues or submit pull requests.
For feature requests or feedback, contact:
📧 your.email@domain.com
