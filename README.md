# Reverse Engineering of Legacy Code using GenAI

## Authors

- ***Uppalapati Suchith Chowdary***
- ***Gowreesh Sai Mididoddi***
- ***Jayanth Prathipati***

## Project Overview

This project focuses on analyzing and understanding outdated software systems to improve their readability, maintainability, and performance. By leveraging advanced Gen AI techniques, the project aims to modernize the legacy codebase through comprehensive documentation, refactoring, translation, and security vulnerability detection.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** openai, os, dotenv, streamlit, shutil
- **Tools:** OpenAI API, Streamlit, Neo4j

## Libraries Imported

- `openai`: For interacting with the OpenAI API.
- `os`: For file and directory handling.
- `dotenv`: For loading environment variables from a `.env` file.
- `streamlit`: For creating the Q/A bot interface.
- `shutil`: For high-level file operations such as copying, moving, and removing files and directories.
- `py2neo` : For graph database operations.

## Installations

1. **Python and Pip**: Ensure Python and Pip are installed.
2. **OpenAI Library**:

   ```bash
   pip install openai
   ```
3. **Streamlit**: For creating a UI for the Question Answering Chatbot.

   ```bash
   pip install streamlit
   ```
4. **Environment Set up**: Create a `.env` file to load OpenAI Access key, End point, Version, Chat Deployment.

   ```bash
   pip install python-dotenv
   ```
5. **Py2Neo**: For using the Neo4J Graph Database.

```bash
   pip install py2neo
```

## Input and Output

- **Input Code Folder**: Contains 3 different folders with Android, iOS, and Angular code bases.
- **Output Folder**: Contains sample output folders and files for code documentation, code refactoring, code translation, and code security vulnerability report generation.

## Features

#### 1.Code Translation

###### Translating Swift to JavaScript

- Define a Function to translate code using the OpenAI API.
- Read the Input Code from the specified input file path.
- Translate the Code from Swift to JavaScript.
- Save the Translated Code to the specified output file path.

#### 2.Code Refactoring

###### Refactoring Code for Readability and Performance

- Define a Function to refactor code for improved readability and performance using the OpenAI API.
- Read the Input Code from the specified input file path.
- Refactor the Code.
- Save the Refactored Code to the specified output file path.

#### 3.Code Documentation

###### Generating Code Documentation

- Define a Function to generate documentation for the given code using the OpenAI API.
- Read the Input Code from the specified input file path.
- Generate the Documentation using OpenAI's natural language processing capabilities.
- Save the Documentation to the specified output file path.

#### 4.Code Security Vulnerability Report Generation

###### Generating Security Vulnerability Reports

- Define a Function to analyze the given code for potential security vulnerabilities using the OpenAI API.
- Read the Input Code from the specified input file path.
- Generate the Vulnerability Report using OpenAI's analysis capabilities.
- Save the Report to the specified output file path.

## Streamlit Chat Q/A Bot

### Creating an Interactive Q/A Bot

- Setup the Streamlit Interface for user input and interaction.
- Integrate OpenAI API to handle user queries and provide responses.
- Run the Streamlit Application to interact with the Q/A bot.

## Execution Steps

1. **Install Required Libraries**:

   ```bash
   pip install -r requirements.txt
   ```
2. **Create and Configure the `.env` File** with your OpenAI API credentials.
3. **Setup Input and Output Directories** for code translation, refactoring, documentation, and security report generation.
4. **Run the Documentation and Security Report Generation Scripts** to analyze and document the code.
5. **Run the Translation and Refactoring Scripts** to process the code files.
6. **Launch the Streamlit Q/A Bot** for interactive querying.

## Quick Start 🚀

1. Clone the repository:

   ```bash
   git clone https://github.com/Suchith-2002/Reverse-Engineering-Legacy-Code.git
   ```
2. Navigate to the project directory:

   ```bash
   cd Reverse-Engineering-Legacy-Code
   ```
3. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

## Note on Data and Resources

- This project was conducted under an organization and thus, the datasets and resources used are proprietary and cannot be shared publicly.
- All input code files and generated outputs are stored in secure organizational repositories.
