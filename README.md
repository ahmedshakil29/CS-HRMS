# CS-HRMS

Human Resource Management System (HRMS)

# Overview

The Human Resource Management System (HRMS) is a C#-based desktop application designed to manage employee records, attendance, payroll, leave management, and performance tracking efficiently. The system streamlines HR processes, reducing manual effort and ensuring data accuracy.

# Features

Employee Management: Add, update, delete, and search employee records.

Attendance Tracking: Record daily attendance and generate reports.

Payroll System: Calculate salaries, deductions, and generate payslips.

Leave Management: Manage leave requests and approvals.

Performance Evaluation: Assess employee performance and generate reports.

Role-Based Access Control: Secure access with different roles (Admin, HR, Employee).

# Technologies Used

Programming Language: C#

Database: Microsoft SQL Server

UI Framework: Windows Forms with MetroModernUI 1.4.0.0

ORM: Entity Framework 6.2.0

Installation & Setup

# Clone the Repository:

1. git clone https://github.com/ahmedshakil29/CS-HRMS

cd hrms

2. Configure Database:

Open Microsoft SQL Server Management Studio.

Create a new database (e.g., HRMS_DB).

Run the provided SQL scripts (db_schema.sql).

3. Update Connection String:

Navigate to App.config.

Update the ConnectionString to match your SQL Server configuration.

4. Build and Run:

Open the solution in Visual Studio.

Restore NuGet packages (EntityFramework 6.2.0, MetroModernUI 1.4.0.0).

Press F5 to build and run the project.

# Usage

1. Login:

Admin: Full access to all modules.

HR: Manage employee records and leave requests.

Employee: View personal details, attendance, and payroll.

2. Manage Employees:

Add new employees and update their details.

3. Attendance:

Mark attendance and generate reports.

4. Payroll:

Calculate salaries and generate payslips.

5. Leave Requests:

Employees can request leave; HR/Admin can approve/reject.

6. Performance Evaluation:

Admin/HR can assess and record employee performance.

# Future Enhancements

Improved UI design.

Export reports to PDF and Excel.

AI-based performance analytics.

# Contributors

Shakil Ahmed – Developer

# License

This project is licensed under the MIT License. See LICENSE for more details.

# Contact

For issues or suggestions, please create an issue in the repository or contact us at ahmedshakil.aiub@gmail.com.
