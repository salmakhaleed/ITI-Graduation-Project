# ITI-Graduation-Project
Examination System | SQL &amp; Power BI Project
# Online Examination System - End-to-End SQL & Power BI Project

This repository contains an **end-to-end Online Examination System**. The system covers **everything from database design, ETL (SSIS), SQL Server procedures, to SSRS reports and Power BI dashboards**.

---

## **Project Overview**

The system automates online exams, including:
- Exam creation, correction, and analysis
- Student performance tracking
- Instructor course reporting
- Course and topic tracking

Technologies used:
- **SQL Server** for transactional and analytical Databases
- **SSIS** for Data Warehousing and ETL
- **SSRS** for detailed reports
- **Power BI** for interactive dashboards

---

## **Repository Contents**

| File / Folder | Description |
|---------------|-------------|
| `database/` | SQL Server Database and Data Warehouse backups |
| `SSIS/` | ETL project for data warehousing |
| `Dashboards/` | Power BI dashboard files (.pbix) |
| `ERD/` | Entity-Relationship Diagram and Mapping images |
| `presentation.pdf` | Project Presentation|

---

## **Features & Reports**

The system supports multiple automated reports:
- Student information by Department
- Grades for a specific student across all courses
- Instructor’s courses and number of students
- Course topics by Course ID
- Exam questions and choices by Exam number
- Student answers by Exam number and Student ID

All reports are implemented via **stored procedures** for efficiency and security.

---

## **Power BI Dashboards**

The project includes **five interactive dashboards** visualizing:
- Student demographics and performance trends
-  Intakes, Tracks and Branches analytics
- Instructors and Course performance insights
- Exam analysis and question performance
- Certification and Career outcomes


---

## **ERD and Mapping**

- `ERD/ERD.png` → Shows the database structure and relationships  
- `Mapping.png` → Shows the ETL/data warehouse mapping  

These images demonstrate the **complete flow from transactional data to analytical insights**.

---

## **How to Use**

1. Restore the SQL Server database from `database/database.bak`.
2. Restore the data warehouse from `database/datawarehouse.bak`.
3. Open the SSIS project in Visual Studio to execute ETL processes.
4. Open the Power BI `.pbix` files in `Dashboards/` to view interactive dashboards.
5. Refer to `presentation.pdf` for screenshots of SSRS reports and system overview.

---

## **End-to-End Highlights**

- Full **ERD & Database design**  
- **Stored procedures** for CRUD operations , SSRS Reports and Exam management  
- **ETL with SSIS** for data warehousing
- **SSRS reports** 
- **Interactive Power BI dashboards**  
- Complete **Data pipeline from Source to Insights**  
