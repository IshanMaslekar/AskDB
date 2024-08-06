# AskDB LLM Web App

This project is a web application that leverages a Large Language Model (LLM) to convert natural language questions into SQL queries, execute them on an SQLite3 database, and provide answers along with various features to enhance user experience.

## Features

### AI-Powered Data Query Interface

#### Problem Statement
Organizations often struggle with efficiently accessing and understanding client data stored in internal databases. Traditional methods of data retrieval and analysis can be time-consuming and cumbersome, leading to delays in decision-making and inefficiencies in client management. There is a need for a streamlined and intuitive solution that allows organization members to query and receive timely, accurate insights from the database through a user-friendly interface.

#### Objective
Develop a chat interface that leverages a Large Language Model (LLM) to read and interpret client data from an internal database. This interface will enable organization members to query the database and receive accurate, contextually relevant responses about the data.



![image](https://github.com/user-attachments/assets/3f600e82-903a-43d2-9d51-e255696d798a)



### Natural Language to SQL Conversion

Users can input natural language questions regarding the data in their uploaded files. The input field is designed to understand natural language, making it user-friendly for those who are not familiar with SQL.

#### Example
- Question: "Which city has the most vehicles listed in the table?"
- Generated SQL Query: `SELECT city, COUNT(*) as vehicle_count FROM vehicles GROUP BY city ORDER BY vehicle_count DESC LIMIT 1;`


![image](https://github.com/user-attachments/assets/7ffcd576-32ba-456a-ad39-3e05ed2c89b6)


### Enter Files

Users can enter multiple CSV or Excel Files.


![image](https://github.com/user-attachments/assets/14363708-5524-4639-9be9-2d1084b11889)



### SQL Query Display

For transparency, the generated SQL queries are displayed to the user. This helps users understand how their natural language questions are being interpreted by the system.


![image](https://github.com/user-attachments/assets/7e47a6f0-612f-434c-92f6-f82c86934b95)




### Query History

The application maintains a history of all queries executed by the user for easy reference and repeated use. Users can view and re-execute previous queries without having to re-enter them.


![image](https://github.com/user-attachments/assets/2236331a-f35d-4b1c-9aa1-a422854c6d08)


### Multilingual Support

To cater to a diverse user base, the application supports multiple languages for both input and output. Users can select their preferred language, making the application accessible to non-English speakers.


![image](https://github.com/user-attachments/assets/3383fe5b-3e04-4be7-baef-7aec0317b883)



### Data Visualizations

The application includes a section dedicated to visualizing the data. It supports multiple types of visualizations using different libraries:
- **Matplotlib** for basic bar plots
- **Seaborn** for advanced bar plots
- **Plotly** for interactive bar plots


![image](https://github.com/user-attachments/assets/2e48d4fa-29f4-4b31-b751-28f636faa5ba)

