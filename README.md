## 🎯 Project Overview 
The primary goal of this project is to build a complete, data-driven web application from scratch using .NET 8, Entity Framework, Code-First, and the Repository Pattern. The application allows employees to request leave and for administrators to approve or reject those requests.

## Technologies Used
- Backend: C#, .NET 8 MVC
- Database: Microsoft SQL Server, Entity Framework Core 3.1 (Code-First)
- Authentication: ASP.NET Identity
- Frontend: HTML, CSS, Bootstrap 4, JQuery
- Admin Theme: AdminLTE
- Architecture:
  - Repository Pattern
  - Dependency Injection
  - ViewModels
  - AutoMapper

## 🛠️ Features 
- User Authentication: Secure login and registration for employees and administrators using ASP.NET Identity.
- Role Management: Different user roles (e.g., Employee, Administrator) with distinct permissions.
- Leave Request Management:
  - Employees can create, view, and cancel their leave requests.
  - Administrators can view all leave requests.
  - Administrators can approve or reject pending leave requests.
- Leave Allocation: Automatic or manual allocation of leave days to employees.
- Dashboard: A summary view for administrators showing pending requests and other stats
