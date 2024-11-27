
# Project Title

A brief description of what this project does and who it's for

# Usage

## Step 1: Retrieve the Data Folder from the Server
First, you need to retrieve the data folder located on the server. The folder is stored in the following path on the server:
```javascript
/server/data
```
## Step 2: Upload the Data to Kaggle
Upload the data folder to Kaggle by following these steps:
1. In your Kaggle notebook environment, click the "Add Data" button.
2. Select "New Dataset".
3. Drag and drop your data folder into the "Drag & Drop" area, or click to select the folder from your file explorer.
4. Set the Title of the dataset to "data-hand" for easy identification.
5. This will upload the folder containing your data, and you will be able to access it directly in your notebook.

![Kaggle Data Upload](server\images\to_chuc_data_tren_kaggle.png)

## Step 3: After Training is Complete
Once the training is finished on Kaggle, follow these steps to download the model weights to your local machine:

1. Locate the Model Files: After training, the model will automatically save two important files:
- ```best_model.pth (best performing model)```
- ```last_model.pth (last saved model)```
2. Download the Model Files:
In the Kaggle notebook, navigate to the "Output" tab. Find the saved model files (best_model.pth and last_model.pth) listed there. Click on each file to download them to your local machine. \

3. Create a Folder for Weights on Local: On your local machine, create a directory named "weights" in `/server.data` to store the downloaded model files.

4. Save the Files: Move the downloaded model files into the "weights" folder you just created.