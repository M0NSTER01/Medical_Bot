# README: Setting Up Your Environment with Pipenv

## Prerequisite: Install Pipenv
Follow the official Pipenv installation guide to set up Pipenv on your system:  
[Install Pipenv Documentation](https://pipenv.pypa.io/en/latest/installation.html)

---

## Important: Add Your API Token

Before setting up the environment, please add your API token to the `.env` file in the root directory of your project. This token is required for authentication with the necessary services.

1. **Create a `.env` File:**  
   If it doesn't already exist, create a file named `.env` in your project's root directory.

2. **Insert Your API Token:**  
   Open the `.env` file and add your API token in the following format:
   ```env
   API_TOKEN=your_api_token_here   (remeber to put the api token in double quotes)



## Steps to Set Up the Environment

### Install Required Packages
Run the following commands in your terminal (assuming Pipenv is already installed):

```bash
pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pipenv install huggingface_hub
pipenv install streamlit
```

### If the pipenv is not working
Run the following commands in you terminal (assuming Pipenv is already installed):

```bash
pip install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pip install huggingface_hub
pip install streamlit
```
