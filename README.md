# customer-support-ticket-triage
Week-1 Internship Project
The Customer Support Ticket Triage System is a Python-based application developed as part of a Week-1 Internship Project.
The system automates the initial handling of customer support tickets by preprocessing text, identifying issue categories, assigning priority levels, and calculating SLA (Service Level Agreement) response times.
This project uses a rule-based approach, making it beginner-friendly while closely simulating real-world customer support operations.
Problem Statement

Organizations receive a high volume of customer support tickets daily.
Manually reviewing tickets to identify urgent issues and assign priorities is inefficient and error-prone.

This project automates the ticket triage process by:
- Classifying tickets into predefined issue types
- Assigning priority levels based on keywords
- Estimating SLA response time automatically
- This helps support teams respond faster and more effectively.

Tools and Technologies:
* Python
* Google Colab
* Pandas
* GitHub

Project Workflow:
+ Load the customer support ticket dataset
+ Explore and analyze the dataset
+ Clean and preprocess ticket descriptions
+ Classify tickets into issue categories:

LOGIN:
- PAYMENT
- DELIVERY
- REFUND
- BUG
- GENERAL

Assign priority levels:
P0 – Critical
P1 – High
P2 – Medium
P3 – Low

Calculate SLA response time based on priority
Export the processed data as a CSV report

Key Features:
* Text cleaning using Python
* Rule-based issue classification
* Priority assignment using keyword logic

SLA calculation in hours

Automated CSV report generation
