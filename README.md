# SQL
Welcome to the SQL Projects repository! This repository hosts various SQL projects for different purposes, including database management, data analysis, and reporting.

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Projects Overview](#projects-overview)
4. [Usage](#usage)
5. [Contributing](#contributing)

## Introduction
This repository serves as a collection of SQL projects designed to showcase different aspects of database management and data analysis. Each project folder contains SQL scripts, documentation, and examples related to a specific topic or use case.

## Getting Started

### Prerequisites
Before using the SQL projects in this repository, ensure you have the following installed:

- A SQL database management system (e.g., PostgreSQL, MySQL)
- SQL client software (e.g., pgAdmin, MySQL Workbench)

### Installation
To get started with the SQL projects:
1. Clone this repository to your local machine:
```bash
  git clone https://github.com/UrSerghei/SQL.git
```
2.  Navigate to the directory containing the SQL projects:
```bash
cd SQL
```
## Projects Overview
### Project 1: Data Wrangling & AB Testing
Description: The overall goal was to analyse the results of A/B testing for a hypothetical online shopping company.
Files:
- task_1.sql: Compare this table to the assignment events we captured for user_level_testing. Does this table have everything you need to compute metrics like 30-day view-binary?
- task_2.sql: Reformat the final_assignments_qa to look like the final_assignments table, filling in any missing values with a placeholder of the appropriate data type.
- task_3.sql: Use this table to compute order_binary for the 30-day window after the test_start_date for the test named item_test_2
- task_4.sql: Use the final_assignments table to calculate the view binary, and average views for the 30-day window after the test assignment for item_test_2. 
- task_5.sql: Use the https://thumbtack.github.io/abba/demo/abba.html to compute the lifts in metrics and the p-values for the binary metrics (30-day order binary and 30-day view binary) using an interval of 95% confidence.


## Usage
Each project folder contains specific instructions and examples for using the SQL scripts. Refer to the README.md file in each project folder for detailed usage guidelines.


## Contributing
Contributions to enhance existing projects or add new SQL projects are welcome! Here's how you can contribute:

Fork the repository and create a new branch for your changes.
Make your modifications and test them thoroughly.
Submit a pull request with a clear description of your enhancements.
   
