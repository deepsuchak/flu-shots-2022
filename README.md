# Healthcare Analytics Project: Massachusetts Flu Shots

Table of Contents
Overview
Data Collection
Data Extraction
Data Loading
Server Configuration
Visualization
Directory Structure
Dependencies
Getting Started
Contributing
License

Overview
This project focuses on healthcare analytics, specifically analyzing the number of flu shots given in the state of Massachusetts. The data has been generated using Synthea, a tool that emulates real-world healthcare data, and PostgreSQL is used for querying and extracting relevant information. The extracted data is then visualized using Tableau Server to create informative dashboards.

Data Collection
The healthcare data for this project has been generated using Synthea, a powerful tool for simulating realistic patient histories and medical records. The Synthea-generated data includes various healthcare events, including flu shots, which forms the basis for our analysis.

Data Extraction
PostgreSQL is utilized for querying and extracting relevant data from the Synthea-generated dataset. SQL queries are designed to filter and aggregate the information necessary for the objectives of this project.

Data Loading
The extracted data is loaded into the PostgreSQL database, creating a structured environment for further analysis. This step ensures that the data is organized and ready for integration with other tools and platforms.

Server Configuration
PostgreSQL drivers are connected to Tableau Server, enabling seamless communication between the data source and the visualization platform. This setup ensures that the latest data is accessible in Tableau for creating dynamic and informative dashboards.

Visualization
Tableau Server is employed to create interactive and visually appealing dashboards that provide insights into the number of flu shots given in Massachusetts. The dashboards offer a user-friendly interface for exploring trends, patterns, and key metrics related to flu shot distribution.

Directory Structure
/healthcare-analytics-project
|-- data/
|   |-- Immunizations.txt
|   |-- Patients.txt
|   |-- conditions.txt
|   |-- final_data_for_viz.csv
|-- data_extraction_queries.sql
|-- tableau_dashboard.twb
|-- README.md


Dependencies
Synthea
PostgreSQL
Tableau Server
Getting Started
Clone this repository: git clone https://github.com/deepsuchak/flu-shots-2022

Follow the steps in Data Collection, Data Extraction, Data Loading, and Server Configuration to set up and configure the project.
Open Tableau and import the provided dashboard file from the tableau/ directory.
Explore the dashboards and gain insights into the flu shot distribution in Massachusetts.

Contributing
Contributions are welcome! Feel free to open issues to enhance the functionality, documentation, or address any bugs.

License
This project is licensed under the MIT License.
