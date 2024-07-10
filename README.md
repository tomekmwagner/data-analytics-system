# Purpose
The purpose of this project is to learn:
1. How to build and maintain a system which will be able to serve milions of requests per day.
2. How to implement different software architectures: hexagonal, pipes & filters and microkernel.
3. Test interesting libs/tools which I haven't time to play with before for instance diagrams as markdown, architecture unit testing etc.

# Constraints
The constraints under which the system will be build are:
1. System will be implemented in Typescript, which will simplify the implementation - backend, infra and potential frontend - in the
same programming language as the coding itself isn't the goal.
2. System will be deployed on AWS - because I would like to get more familiar with this cloud.

# High Level Requirements
I used ChatGPT to generate an examplary project ideas which will meet my learning requirements.
The high level requirements are as follows:

## Business Idea:
Create an analytics system for an e-commerce platform that processes millions of requests daily. 
The system will collect, process, and analyze data such as user interactions, purchases, and browsing behaviors. 
This data will then be used to generate insights and reports for improving the business.

## Modules/Services:
### Data Collection Service (Microkernel Architecture):
This service will be responsible for collecting data from various sources, such as web traffic, mobile app interactions, and purchase transactions.

### Data Processing Service (Pipes & Filters Architecture):
This service will process the collected data, applying transformations, filtering out irrelevant information, and enriching data with additional context.

### Analytics and Reporting Service (Hexagonal Architecture):
This service will analyze processed data and generate reports, dashboards, and alerts. It will also provide APIs for querying data and integrating with other systems.
