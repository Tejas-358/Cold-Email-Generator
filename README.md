# Cold Email Generator

This project is a Cold Email Generator built with Python, Streamlit, and LangChain. The application takes a job description and company information to generate a cold email using AI, helping business development teams reach out to potential clients efficiently.

## Features

- **Streamlit Web App**: The project uses Streamlit to create a web-based user interface.
- **LangChain Integration**: Utilizes LangChain for natural language processing to generate cold email content based on job descriptions and portfolio links.
- **Web-Based Content Loader**: Ability to fetch content from external URLs to help generate customized emails.
- **Automated Email Drafting**: Generates tailored cold emails based on the input job description and portfolio details.

# Project documentation

### `main.py`

- The main entry point for the Streamlit app.
- Users can input a job description URL and generate a customized cold email based on the input.
  
### `chains.py`

- Contains the cold email generation logic using LangChain.
- Defines the template and chain of logic for producing the email content.

### `portfolio.py`

- Manages portfolio-related functionalities, allowing the system to add relevant achievements to the email.
  
### `utils.py`

- Provides utility functions like text cleaning to ensure the job description is properly formatted before being processed.

# Clone

git clone https://github.com/Tejas-358/Cold-Email-Generator.git

## Change the API KEY in .env




