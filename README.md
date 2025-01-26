# HealthBot


HealthBot is a Streamlit application designed to provide health-related functionalities. Follow the steps below to set up the environment and get started.

## Steps to Set Up the Environment

1. **Install Required Packages**  
   Run the following commands to install the necessary dependencies:
   ```bash
   pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
   pipenv install huggingface_hub
   pipenv install streamlit
   ```

2. **Activate the Pipenv Shell**  
   Start the Pipenv virtual environment:
   ```bash
   pipenv shell
   ```

3. **Run the Streamlit Application**  
   Launch the Streamlit app by running:
   ```bash
   streamlit run <main_file_path>
   ```
   Replace `<main_file_path>` with the relative path to your Streamlit application file (e.g., `app.py`).

## Notes

- Ensure you have Python 3.8 or later installed on your system.
- If you encounter any issues, refer to the official documentation of the respective libraries.

---

Enjoy using HealthBot!
``
