# HHA504_assignment_storage
Working with cloud storage in Azure and GCP


### 1. Upload Files Using the GUI
- **Azure Blob Storage:**
  - Navigate to the Azure portal and create a new Storage Account.

<img width="825" alt="image" src="https://github.com/user-attachments/assets/67995e0c-0d2b-4792-b726-c226ac17bb42">

  - Create a Blob container within the Storage Account.
<img width="634" alt="image" src="https://github.com/user-attachments/assets/8855790a-736d-4c9d-9607-f01029f1ec78">

  - Upload a sample file (e.g., a text file or image) to the Blob container using the Azure portal.

<img width="1212" alt="image" src="https://github.com/user-attachments/assets/abebdf13-ff2f-4219-a460-cbabeca9aebd">

<img width="1376" alt="image" src="https://github.com/user-attachments/assets/4faceaf2-7aa0-4b6c-aa05-dd44a263ff7e">

  
- **GCP Cloud Storage:**
  - Access the Googlnewe Cloud Console and create a new Cloud Storage bucket.

<img width="1062" alt="image" src="https://github.com/user-attachments/assets/e9f5f591-38e6-4be1-9df8-7b5f60a9ad6c">

  - Upload a similar sample file to the bucket using the GCP Console.

<img width="1377" alt="image" src="https://github.com/user-attachments/assets/77865a9f-6b52-42ed-9a4d-a8b2af155405">


### 2. Upload Files Using Python

- **Azure Blob Storage:**
  - Write a Python script that uploads a file to the Blob container you created. Use the `azure-storage-blob` library to handle the upload.

- **GCP Cloud Storage:**

  1. Under IAM & Admin, create a service account. 
  2. Provide a name under "Service account details"
  3. Select "Compute storage admin" under "Grand this service account access to this project"
  4. Click Done. 
  5. Click the 3 dots under Actions for the service account. 
  6. Click; Manage Keys. Add Key. Create New Key. JSON key type. Create. Download. 
  7. The code I created is under "/workspaces/HHA504_assignment_storage/gcp.py"
  8. I came across an error here. I returned to my bucket in GCP. Went back to IAM & Admin; Edit Permissions; Add another role; Storage Object Admin; Add another role; Storage Admin; Save.
  9. I re-ran my code and was able to successfully upload the fake image into the bucket. 

<img width="1405" alt="image" src="https://github.com/user-attachments/assets/acd24db6-7498-4e32-85b7-a98e13fd666e">


### 3. Explore Storage Features
- **Azure:**
  - Explore and document the options for managing and securing data in Azure Blob Storage (e.g., access policies, tiers).
  
- **GCP:**
  - Explore and document the options for managing and securing data in GCP Cloud Storage (e.g., IAM permissions, lifecycle rules).


