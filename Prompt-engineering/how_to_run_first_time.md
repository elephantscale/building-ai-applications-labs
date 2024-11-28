## Setup Local Environment for Prompt-engineering

1. **Navigate to the Project Directory**

2. **Create a Virtual Environment**
   - Run the following command to create a virtual environment:
     ```sh
     python -m venv myenv
     ```

3. **Activate the Virtual Environment**
   - Activate the new virtual environment using:
     ```sh
     source myenv/bin/activate
     ```

4. **Install Jupyter Notebook**
   - Install Jupyter Notebook in the same virtual environment:
     ```sh
     pip install jupyter
     ```

5. **Install Lab Requirements**
   - Install the lab requirements specified in the `requirements.txt` file:
     ```sh
     pip install -r requirements.txt
     ```

6. **Create .env File for API Keys**
    ```sh
     LLM_MODEL=gpt-4o
     OPENAI_API_KEY=
     ```

9. **Start Jupyter Notebook**
   - Start Jupyter Notebook with the command:
     ```sh
     jupyter lab
     ```


