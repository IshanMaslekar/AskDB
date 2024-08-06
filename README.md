# LLM Web App

This project is a web application that leverages a Large Language Model (LLM) to convert natural language questions into SQL queries, execute them on an SQLite3 database, and provide answers along with various features to enhance user experience.

## Features

### AI-Powered Data Query Interface

#### Problem Statement
Organizations often struggle with efficiently accessing and understanding client data stored in internal databases. Traditional methods of data retrieval and analysis can be time-consuming and cumbersome, leading to delays in decision-making and inefficiencies in client management. There is a need for a streamlined and intuitive solution that allows organization members to query and receive timely, accurate insights from the database through a user-friendly interface.

#### Objective
Develop a chat interface that leverages a Large Language Model (LLM) to read and interpret client data from an internal database. This interface will enable organization members to query the database and receive accurate, contextually relevant responses about the data.

![AI-Powered Data Query Interface](![image](https://github.com/user-attachments/assets/addbe7bd-2e48-4c17-afab-679e996df9a7))


### Natural Language to SQL Conversion

Users can input natural language questions regarding the data in their uploaded files. The input field is designed to understand natural language, making it user-friendly for those who are not familiar with SQL.

#### Example
- Question: "Which city has the most vehicles listed in the table?"
- Generated SQL Query: `SELECT city, COUNT(*) as vehicle_count FROM vehicles GROUP BY city ORDER BY vehicle_count DESC LIMIT 1;`

![Natural Language to SQL Conversion](![image](https://github.com/user-attachments/assets/7399ed75-2ade-4d82-8f0e-86fa6713faad)
)

### Enter Files

Users can enter multiple CSV or Excel Files.

![Entering Files](![image](https://github.com/user-attachments/assets/cdc170fa-dc2b-4b48-861d-6ab9ec6bc4ec)


### SQL Query Display

For transparency, the generated SQL queries are displayed to the user. This helps users understand how their natural language questions are being interpreted by the system.

![SQL Query Display](![image](https://github.com/user-attachments/assets/68b10117-be1b-4cc8-a6dc-286ca9a6398d)
)



### Query History

The application maintains a history of all queries executed by the user for easy reference and repeated use. Users can view and re-execute previous queries without having to re-enter them.

![Query History](![image](https://github.com/user-attachments/assets/25d6b060-5460-4cc7-8bbc-1b7814c4ed07)
)

### Multilingual Support

To cater to a diverse user base, the application supports multiple languages for both input and output. Users can select their preferred language, making the application accessible to non-English speakers.

![Multilingual Support](![image](https://github.com/user-attachments/assets/4d6a72ea-de00-4d1d-9755-267634c873fa)
)


### Data Visualizations

The application includes a section dedicated to visualizing the data. It supports multiple types of visualizations using different libraries:
- **Matplotlib** for basic bar plots
- **Seaborn** for advanced bar plots
- **Plotly** for interactive bar plots

![Data Visualizations](![image](https://github.com/user-attachments/assets/a3941ed1-7dd0-45a6-95b4-e2a0057b7ac2)
)
