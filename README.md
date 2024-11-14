# Payslip Generator

## Overview
The **Payslip Generator** is a console-based C# application designed to automate the processing of employee payslips. It allows payroll administrators to calculate pay for staff based on their hours worked and their roles (Manager or Admin). The system reads employee data from a file, calculates pay based on hourly rates and additional allowances or overtime, and generates individual payslips and a summary report.

## Features
- **Year and Month Input**: Prompts the user to input the year and month for payroll processing.
- **Staff Management**: Reads staff details from the `staff.txt` file, including their name and position (Manager or Admin).
- **Pay Calculation**: Calculates pay based on hours worked:
  - **Managers**: Receive an allowance if working over 160 hours.
  - **Admins**: Receive overtime pay for hours worked over 160.
- **Payslip Generation**: Generates a payslip file for each employee with detailed pay information.
- **Summary Generation**: Generates a report listing employees who worked less than 10 hours in the specified month.
- **Error Handling**: Handles invalid inputs for year, month, and hours worked.

## Installation

### Prerequisites
- .NET SDK
- A text editor or IDE (e.g., Visual Studio, VSCode)

### Steps to Install
1. Clone or download this repository.
2. Open the project in your preferred .NET-compatible IDE.
3. Ensure the `staff.txt` file is located in the root directory of the project with the following format:
