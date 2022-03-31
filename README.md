# PROJECT 2

## Project Description

In this document, all requirements and required technologies pertaining the full stack group project of your training will be presented. All requirements are mandatory. The optional requirement of uploading receipt image is also to be completed. There is a shift in technologies as well. The Expense Reimbursement System will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.

## Technologies Used

* Spring
* Jenkins 
* EC2

## Features

* continuous deployment
* Fully Dockerized front and back end on EC2

To-do list:
* friendlier user ui, such as custom div for reimbursements
* renormalize DB, ORM implemented with limited knowledge of springs ORM implementation.

## Getting Started

Visit http://ec2-3-14-134-131.us-east-2.compute.amazonaws.com:3000/

## Usage

> Login username 1, password 1 for employee, username 4, password 4 for manager
* For Manager
  - select view Reimbursement
  - select pending, completed, or all options for which reimbursements to view
  - select the approve/deny buttons to approve/deny a reimbursement
  - select view employees to view employees 
  - select get Reimburesements to view that employees reimbursements
*  For Employee
  - select submit request and fill out to submit a request
  - select update/edit reimbursement to edit an reimbursement
  - select user Info to view employee info

## Contributors

> Tyler Boston
> Dimitri Luck
