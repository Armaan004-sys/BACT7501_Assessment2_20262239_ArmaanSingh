Purchase Requisition Management System

Project Overview

The Purchase Requisition Management System is a Python application developed for the BACT7501 Software Development Project assessment.

The system allows staff members to submit purchase requisitions by entering their details and requested items. It calculates the total cost and determines whether a requisition can be automatically approved or requires managerial approval.

The application was developed using Object-Oriented Programming (OOP) principles in Python.

Main Features

Create purchase requisitions.

Collect staff details and requisition dates.

Add multiple items and their prices.

Calculate the total requisition cost.

Automatically approve requisitions below $500.

Send requisitions of $500 or more for managerial approval.

Allow managers to approve, reject, or leave requisitions pending.

Generate approval references.

Display all submitted requisitions.

Generate requisition statistics.

Approval Rules

Requisition Total

Approval Process

Below $500

Automatically Approved

$500 or above

Managerial Approval Required

Technologies Used

Python

Object-Oriented Programming (OOP)

Visual Studio Code

GitHub

Project Structure

requisition.py – Main Python application.

README.md – Project documentation.

Testing

The application was tested using five requisition scenarios:

Automatic approval – $200.

Manager approval – $800.

Manager rejection – $650.

Manager leaves requisition pending – $500.

Automatic approval – $450.

The final testing results were:

Total Submitted: 5

Approved: 3

Pending: 1

Not Approved: 1

Author

Armaan Singh

Course

BACT7501 – Programming 1
Assessment 2: Software Development Project
