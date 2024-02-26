# Disease-Detector
Dataset : https://drive.google.com/drive/folders/15eJk0j0YdEKVLUYT6EYO-HvJPEPNipqX?usp=sharing

## Python Setup:
1. Install Python
2. Install Python packages
   ```
   pip3 install -r training/requirements.txt
   pip3 install -r api/requirements_api.txt
   ```
## Training the Model:
1. Download the data from the google drive link.
2. Run Jupyter Notebook.
3. Open the ipynb file in Jupyter Notebook.
4. Update the path to the dataset.
5. Run all cells.
   
## To run the API:
1. Select the api folder.
2. Run the FastAPI Server using uvicorn
   ```
   uvicorn main:app --reload --host 0.0.0.0
   ```
3. Your API is now running.   
