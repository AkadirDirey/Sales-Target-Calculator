Project Name
Sales Analytics Tool

Description
The Sales Analytics Tool is a JavaScript-based project that provides powerful functionalities for analyzing sales data and generating insightful reports. It includes several utility functions for retrieving salesperson information, calculating working days in a month, and obtaining sales data within a specified time range. The tool incorporates an efficient algorithm to exclude Fridays from the calculation of working days. With the Sales Analytics Tool, sales managers and teams can gain valuable insights into sales performance, track monthly sales targets, and evaluate individual salesperson achievements.

Features
getSalesPersonById: Retrieves salesperson information based on their ID from the provided data.
getDaysInMonth: Calculates the number of days in a given month and year.
workingDaysInMonth: Determines the count of working days (excluding Fridays) in a specific month and year.
getSalesByDay: Generates detailed sales information by analyzing data, yearly sales goals, and a specified time range.
daysWorkedExcludingFridaysFun: Calculates the number of working days (excluding Fridays) between two given dates.
Usage
To utilize the Sales Analytics Tool, follow these steps:

Define the data array containing salesperson information, including their ID, name, and sales data.
Call the getSalesByDayFunctional function, passing the yearly sales goal, start date, end date, and salesperson ID as arguments.
The function will return an object containing various metrics and insights, including monthly sales targets, total target achievement, working days (excluding Fridays), and days worked (excluding Fridays).
Use the generated insights to evaluate sales performance, monitor progress towards targets, and make data-driven decisions.# Sales-Target-Calculator
