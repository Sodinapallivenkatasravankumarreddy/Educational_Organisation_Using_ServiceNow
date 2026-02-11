🎓 Educational Organisation using ServiceNow

A ServiceNow-based application that automates student admissions, academic tracking, and result evaluation in an educational institution.

────────────────────────────────

👥 Team Information

Team ID: LTVIP2026TMIDS79862
Team Leader: Manohar Udayagiri

Team Members 
• Obili Ramteja 
• Ramavathu Durga Prasad Naik 
• Sodinapalli Venkata Sravan Kumar Reddy

────────────────────────────────

📘 Project Overview

This project implements a complete Educational Organisation Management System using the ServiceNow platform.
It replaces manual admission and academic tracking with an automated, structured workflow.

The system manages
• Student admissions
• Academic records
• Automatic result calculation

The solution significantly reduces manual effort and improves data accuracy through automation.

────────────────────────────────

🎯 Objectives

• Automate the admission workflow
• Maintain structured student and parent records
• Automatically calculate total, percentage, and result
• Reduce manual admission processing time using automation

────────────────────────────────

🛠️ Technologies Used

Platform: ServiceNow (Personal Developer Instance)
Scripting Language: JavaScript

ServiceNow Features Used
• Custom Tables
• Forms and Layouts
• Process Flows
• Number Maintenance
• Client Scripts

────────────────────────────────

🏗️ Architecture Overview

The system follows a modular and layered architecture built entirely on the ServiceNow platform.

• Data Layer
Custom tables store student, admission, and academic data.

• Application Layer
Forms, layouts, and reference relationships manage user interaction.

• Automation Layer
Client scripts and process flows handle calculations, validations, and workflow transitions.

• Presentation Layer
Clean, user-friendly forms for admissions and student progress tracking.

This architecture ensures scalability, maintainability, and real-world enterprise alignment.

────────────────────────────────

🏗️ System Design

📂 Tables Used

1️⃣ Salesforce Table
• Base table for the system
• Stores student and parent details
• Auto-generated Admin Number

2️⃣ Admission Table
• Extends Salesforce table
• Admission lifecycle
New → In Progress → Joined → Rejected → Rejoined → Closed → Cancelled
• Auto-population of student details
• Pincode-based address automation

3️⃣ Student Progress Table
• Subject-wise marks entry
• Automatic calculation of
Total
Percentage
Result (Pass or Fail)
• Calculated fields are locked to prevent manual changes

────────────────────────────────

⚙️ Automation and Client Scripts

The following client scripts are implemented to automate the system

• Auto Populate Script
• Pincode Update Script
• Disable Fields Script
• Total Calculation Script
• Percentage Calculation Script
• Result Evaluation Script

These scripts ensure accuracy, consistency, and reduced manual dependency.

────────────────────────────────

🧪 Testing and Validation

The application was tested using multiple real-time scenarios to ensure reliability.

• Validated admission workflow transitions
• Verified auto-population of student details
• Tested subject mark entry and calculations
• Ensured total, percentage, and result accuracy
• Checked field locking and validation rules

All modules were tested successfully with consistent and accurate results.

────────────────────────────────

▶️ How to Use the Project

Create a ServiceNow Personal Developer Instance
Configure tables and columns
Design forms and layouts
Add client scripts and process flows
Test admission and student progress workflows
────────────────────────────────

✅ Project Outcome

• Fully automated admission process
• Accurate academic evaluation
• Reduced manual processing time
• Clean and professional ServiceNow implementation

────────────────────────────────

🌟 Notable Contributions

• Outstanding handling of outstanding dues logic and accrued interest concepts
• Reduced manual admission processing time by automating workflows and calculations
• Strong focus on testing, validation, and workflow accuracy

────────────────────────────────

📘 Learning Outcomes

• Hands-on experience with ServiceNow development
• Understanding of enterprise-level workflows
• Practical exposure to automation, scripting, and validation

────────────────────────────────

🙏 Acknowledgement

We sincerely thank our mentors and training program for their guidance and support in completing this internship project.

────────────────────────────────

📄 License

This project is developed for educational and internship purposes only.

Demo Link :

https://drive.google.com/file/d/1snuCSpsTYUwwghE38sh3JB1vgRG7Q8FT/view?usp=sharing
