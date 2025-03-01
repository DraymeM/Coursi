Course Management System

Overview

This is a C# WinForms application designed to assist with course management. The system enables users to register and manage courses, teachers, and students while keeping track of payments. The application uses a Microsoft SQL Server (MS SQL) local database for data storage.

Features

Data Management

Add new courses, teachers, and students.

Modify existing records.

Track student payments.

Store billing information for students.

Course Handling

A course requires at least 4 students to start and can have a maximum of 8 students.

Courses are inactive by default and must be manually activated once requirements are met.

Store the start date and cost per student when a course is activated.

Close a course by setting its end date.

Queries & Reports

Search teachers and list their courses (including closed ones).

Modify active courses.

Generate a pie chart showing student enrollment per teacher for a selected time range.

Generate a line chart displaying revenue trends from all courses for a selected time range.

Export course details and student lists to XML.

Technologies Used

C# WinForms for UI development

Microsoft SQL Server (MS SQL) for data storage

System.Windows.Forms.DataVisualization for charting

XML serialization for data export

Getting Started

Prerequisites

Microsoft SQL Server (Ensure it is installed and running)

.NET Framework (Compatible version)

Installation

Clone the repository:

git clone https://github.com/yourusername/course-management-system.git

Open the project in Visual Studio.

Configure the database connection string in app.config.

Run the SQL scripts (if provided) to set up the database schema.

Build and run the project.

Usage

Add Teachers, Students, and Courses.

Register students for courses.

Activate courses once the minimum student requirement is met.

Track payments and view financial reports.

Analyze data with charts and export information to XML.
