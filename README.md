# Teknowell EduTech – Institutional Performance & Analytics Dashboard

# 1. Project Title / Headline
Teknowell EduTech – Institutional Performance & Analytics Dashboard.  
"An End-to-End BI Solution to Monitor Institutional Performance, Student Outcomes, Financial Health & Trainer Effectiveness."

# 2. Short Description / Purpose
3-4 sentences explaining what the dashboard does and why it exists.

This project presents an end-to-end Power BI analytics solution for Technowell EduTech, designed to provide a 360-degree view of institutional performance.  
The dashboard ecosystem tracks student enrollment trends, course-wise revenue, fee collection status, placement outcomes, student performance, attendance patterns, and trainer effectiveness.  
By consolidating academic, financial, and placement data into interactive dashboards, the solution enables management to make data-driven decisions related to course planning, revenue optimization, student success, and trainer performance.

# 3. Tech Stack
List the key technologies used to build the dashboard.

The dashboard was build using the following tools and technologies:

- 📊 Power BI
  - Interactive dashboard design
  - Advanced data visualizations (Cards, Bar Charts, Line Charts, Donut Charts, TreeMaps, Tables)
  - Cross-filtering & slicer-based interactivity
    
- 🧠 DAX (Data Analysis Expressions)
  - KPI calculations (Revenue, Fees, Placement Rate, Avg Marks, Attendance %)
  - Time intelligence (Monthly Enrollment Trends)
  - Conditional logic for performance bands & attendance categories
    
- 📉 Excel
  - Raw data source & initial data preparation
  - Master data for students, courses, trainers & fees
    
- 🔄️ Power Query (ETL Techniques)
  - Data cleaning & transformation
  - Data merging across multiple tables (Students, Courses, Fees, Placements, Trainers)
  - Date hierarchy creation (Month–Year extraction)
  - Handling missing, duplicate & inconsistent data
    
- 📂 Data Modeling
  - Star schema design
  - Relationship management across fact & dimension tables
  - Optimized model for performance & scalability

# 4. Data Source
The data used in this project is derived from Technowell EduTech’s internal student management system, representing real-world institutional operations.

The dataset includes multiple interconnected tables covering:

- 👩‍🎓 Student Details  
  (Student Name, Enrollment Date, City, Batch, Course)
  
- 📚 Course Information  
  (Course Name, Course Category, Fees, Revenue)
  
- 💰 Fees & Payment Records  
  (Total Fees, Paid Amount, Pending Amount, Payment Status)
  
- 🎯 Placement Data  
  (Placement Status, Company Name, Package Offered, Placement Date)
  
- 📊 Academic Performance Data  
  (Subject-wise Marks, Average Marks, Performance Bands)
  
- 🕒 Attendance Records  
  (Attendance %, Attendance Category)
  
- 👨‍🏫 Trainer & Batch Details  
  (Trainer Name, Course Assigned, Trainer Rating, Batch-wise Student Count)

The dataset was provided in Excel format and transformed using Power Query to ensure data accuracy, consistency, and analytical readiness.

# 5. Features & Highlights
- Business Problem
- Goal of the Dashboard
- Walk through of Key Visuals
- Business Impact & Insights

## A. Business Problem
Technowell EduTech was managing large volumes of student, course, fee, placement, attendance, and trainer data, but the information was scattered across multiple Excel files and operational systems.

Due to the absence of a centralized analytics platform, the management faced challenges such as:

- Lack of visibility into course-wise enrollment trends and revenue contribution
- Difficulty in tracking total fees, paid fees, and outstanding dues at student and course levels
- No consolidated view of placement performance, average packages, and company-wise hiring
- Inability to analyze student academic performance and attendance patterns
- Limited insights into trainer effectiveness, batch performance, and feedback ratings
- Manual reporting processes that were time-consuming, error-prone, and non-scalable

As a result, decision-making related to course planning, pricing strategy, marketing focus, trainer allocation, and placement performance was largely reactive rather than data-driven.

## B. Goal of the Dashboard
The primary goal of this project was to design and implement a centralized, interactive Power BI dashboard ecosystem that provides a complete view of Technowell EduTech’s academic, financial, and placement performance.

The dashboard aims to:

- Deliver real-time visibility into student enrollments, course demand, and revenue generation
- Monitor fees collection efficiency by tracking total fees, paid amounts, and outstanding dues
- Evaluate placement outcomes, including placement rate, average package, and top recruiting companies
- Analyze student academic performance and attendance trends to identify high-performing and at-risk students
- Measure trainer effectiveness and batch performance using ratings and student outcomes
- Enable data-driven decision-making for course planning, marketing strategy, trainer allocation, and operational improvements
- Provide a user-friendly and interactive reporting solution for management and non-technical stakeholders

## C. Walkthrough of Key Visuals (Brief Overview)
The Power BI solution consists of multiple dashboards, each focusing on a critical aspect of institutional performance:

💰 1. Student Fees Performance Dashboard

- Total Fees, Paid Fees & Outstanding Amount (KPI Cards)  
  Provides a quick snapshot of overall financial health.
- Paid vs Pending Fees Comparison  
  Helps identify gaps in fee collection and improve follow-up strategies.
- Student-level Fee Details Table  
  Enables granular tracking of individual student payments and pending dues.

📊 2. Course Enrollment & Revenue Dashboard

- Monthly Enrollment Trend (Line Chart)  
  Tracks month-wise student enrollments to identify growth patterns and seasonality.
- Course Popularity TreeMap  
  Visualizes student distribution across courses, helping identify high-demand and low-demand programs.
- Revenue by Course (Bar Chart)  
  Highlights top revenue-generating courses, supporting pricing and marketing decisions.
- City-wise Student Distribution  
  Shows enrollment contribution from different cities to analyze regional demand.

🧑‍🎓 3. Student Performance & Attendance Dashboard

- Average Marks & Performance Bands  
  Categorizes students based on academic performance.
- Attendance Percentage Analysis  
  Helps identify attendance trends and at-risk students.
- Subject-wise Performance Tables  
  Provides detailed academic insights at the subject level.

🎯 4. Placement & Career Outcome Dashboard

- Placement Rate KPI  
  Displays the percentage of students placed across courses.
- Average & Highest Package Indicators  
  Highlights salary benchmarks achieved by students.
- Company-wise Placements  
  Shows top hiring companies and placement distribution.
- Course-wise Placement Performance  
  Identifies courses with strong and weak placement outcomes.

👨‍🏫 5. Trainer & Batch Performance Dashboard

- Trainer Rating KPIs  
  Evaluates trainer effectiveness based on student feedback.
- Batch-wise Student Count  
  Shows workload distribution across trainers.
- Trainer vs Student Performance Analysis  
  Connects trainer effectiveness with student outcomes.

## D. Business Impact & Insights
The Power BI analytics solution delivered actionable insights that significantly improved Technowell EduTech’s academic and financial decision-making:

- Identified high-revenue and high-demand courses such as Full Stack Development and Data Science, enabling management to prioritize marketing spend and resource allocation.
- Improved fee collection efficiency by providing clear visibility into paid, pending, and overdue amounts at both course and student levels.
- Enabled proactive tracking of placements, helping the institute monitor placement rate, average packages, and top recruiting companies across courses.
- Highlighted academic performance and attendance gaps, allowing early identification of at-risk students and targeted academic support.
- Measured trainer effectiveness through ratings and batch performance, supporting informed decisions on trainer allocation and training needs.
- Optimized course planning and batch scheduling using enrollment trends and seasonal demand patterns.
- Reduced manual reporting effort by automating KPI tracking, resulting in faster, more accurate, and scalable reporting.
- Enhanced leadership decision-making by consolidating academic, financial, and placement data into a single interactive BI platform.

# 6. Screenshots / Demos
The dashboard looks like:

Page 1 - ![Student Fees Performance Dashboard](https://github.com/prathmeshsalunkhe16/Technowell-EduTech-Education-Analytics-Revenue-Performance-Dashboard/blob/main/Student%20Fees%20Performance%20Dashboard%20Snapshot.png)

Page 2 - ![Course Enrollment & Revenue Dashboard](https://github.com/prathmeshsalunkhe16/Technowell-EduTech-Education-Analytics-Revenue-Performance-Dashboard/blob/main/Course%20Enrollment%20%26%20Revenue%20Dashboard%20Snapshot.png)

Page 3 - ![Student Performance & Attendance Dashboard](https://github.com/prathmeshsalunkhe16/Teknowell-EduTech-Institutional-Performance-Analytics-Dashboard/blob/main/Student%20Performance%20%26%20Attendance%20Dashboard%20Snapshot.png)

Page 4 - ![Placement & Career Outcome Dashboard](https://github.com/prathmeshsalunkhe16/Teknowell-EduTech-Institutional-Performance-Analytics-Dashboard/blob/main/Placement%20%26%20Career%20Outcome%20Dashboard%20Snapshot.png)

Page 5 - ![Trainer & Batch Performance Dashboard](https://github.com/prathmeshsalunkhe16/Teknowell-EduTech-Institutional-Performance-Analytics-Dashboard/blob/main/Trainer%20%26%20Batch%20Performance%20Dashboard%20Snapshot.png)
