## Setup Local Environment 

1. **Navigate to the lab directory**
*  **IMPORTANT:** Setup is done in each lab separately, but the instruction is the same.

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
     
4. **Install Lab Requirements**
   - Install the lab requirements specified in the `requirements.txt` file:
     ```sh
     pip install -r requirements.txt
     ```
5. **Create .env File for all API Keys**
    - We use one .env file at the root of all labs
   
6. **Install jupyter**
    ```sh
    pip install jupyter
    ```

7. **Start Jupyter Lab**
   - Start Jupyter UI with the command:
     ```sh
     jupyter lab
     ```


