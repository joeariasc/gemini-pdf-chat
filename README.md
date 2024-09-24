# Chat with PDF using Gemini

This project is a Python application that uses **Streamlit** for running the app.

## Prerequisites

-   **Python 3.11** is recommended for the best compatibility.
-   Ensure that either **Conda** or Python's built-in **venv** is installed for creating a virtual environment.

## Setting up the environment

### Setting up the `.env` file
Before running the project, you need to create a `.env` file in the root of the project directory and add your Google API Key.

1. In the root directory of the project, create a .env file:
    ```bash
    touch .env
    ```
2. Add the following line to the .env file with your actual Google API Key:
    ```env
    GOOGLE_API_KEY=your_google_api_key_here
    ```

### Using Conda

1. Create a new Conda environment with Python 3.11:

    ```bash
    conda create --name myenv python=3.11
    ```

2. Activate the Conda environment:
    ```bash
    conda activate myenv
    ```

### Using Python's venv

1. Create a virtual environment:

    ```bash
    python3 -m venv venv
    ```

2. Activate the virtual environment:
    
    ```bash
    source venv/bin/activate
    ```

## Install Dependencies
Install the required dependencies (if there's a requirements.txt file):
    
```bash
source venv/bin/activate
```
    

## Run the project

```bash
streamlit run app.py
```