# AskDB LLM Web App

This project is a web application that leverages a Large Language Model (LLM) to convert natural language questions into SQL queries, execute them on an SQLite3 database, and provide answers along with various features to enhance user experience.

## Features

### AI-Powered Data Query Interface

![image](https://github.com/user-attachments/assets/46912afc-7f9f-40ff-baa2-0f83c5c1dd2e)

### Natural Language to SQL Conversion

Users can input natural language questions regarding the data in their uploaded files. The input field is designed to understand natural language, making it user-friendly for those who are not familiar with SQL.

#### Example
- Question: "Which city has the most vehicles listed in the table?"
- Generated SQL Query: `SELECT city, COUNT(*) as vehicle_count FROM vehicles GROUP BY city ORDER BY vehicle_count DESC LIMIT 1;`

<img src="https://github.com/user-attachments/assets/7ffcd576-32ba-456a-ad39-3e05ed2c89b6" alt="Natural Language to SQL Conversion" width="400">

### Enter Files

Users can enter multiple CSV or Excel Files.

<img src="https://github.com/user-attachments/assets/14363708-5524-4639-9be9-2d1084b11889" alt="Enter Files" width="400">

### SQL Query Display

For transparency, the generated SQL queries are displayed to the user. This helps users understand how their natural language questions are being interpreted by the system.

<img src="https://github.com/user-attachments/assets/7e47a6f0-612f-434c-92f6-f82c86934b95" alt="SQL Query Display" width="400">

### Query History

The application maintains a history of all queries executed by the user for easy reference and repeated use. Users can view and re-execute previous queries without having to re-enter them.

<img src="https://github.com/user-attachments/assets/2236331a-f35d-4b1c-9aa1-a422854c6d08" alt="Query History" width="400">

### Multilingual Support

To cater to a diverse user base, the application supports multiple languages for both input and output. Users can select their preferred language, making the application accessible to non-English speakers.

<img src="https://github.com/user-attachments/assets/3383fe5b-3e04-4be7-baef-7aec0317b883" alt="Multilingual Support" width="400">

### Data Visualizations

The application includes a section dedicated to visualizing the data. It supports multiple types of visualizations using different libraries:
- **Matplotlib** for basic bar plots
- **Seaborn** for advanced bar plots
- **Plotly** for interactive bar plots

<img src="https://github.com/user-attachments/assets/2e48d4fa-29f4-4b31-b751-28f636faa5ba" alt="Data Visualizations" width="400">






## Installation

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/llm-web-app.git

2. **Navigate to the project directory**:
   ```bash
   cd llm-web-app

3. **Create a virtual environment**:
   ```bash
   python -m venv env

4. **Activate the virtual environment**:
   ```bash
   .\env\Scripts\activate
5. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
6. **Run the application**:
   ```bash
   streamlit run app.py

   

