# Text-To-SQL-Chainlit

## Overview

Text-To-SQL-Chainlit is a Python-based application that leverages the power of LangChain, Chainlit, and the OpenAI API to convert natural language text into SQL queries. The application uses environment variables for configuration management.

## Features

- **LangChain**: A library for building and interacting with language models.
- **Chainlit**: A framework for creating and debugging chat applications.
- **OpenAI API**: Integration with OpenAI for natural language processing.
- **dotenv**: Management of environment variables.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:

   ```
   git clone https://github.com/patelshehbaz/Text-To-SQL-Chainlit.git
   ```

2. **Create a virtual environment**:

   ```
   conda create -p venv python=3.10 -y
   conda activate venv
   ```

3. **Install the dependencies**:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. **Set up environment variables**: Create a `.env` file in the root directory of the project and add your OpenAI API key.

   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

2. **Run the application**:
   ```
   chainlit run app.py
   ```
