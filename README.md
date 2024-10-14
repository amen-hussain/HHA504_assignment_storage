# HHA504_assignment_storage
Working with cloud storage in Azure and GCP


### 1. Upload Files Using the GUI
- **Azure Blob Storage:**
  - Navigate to the Azure portal and create a new Storage Account.

<img width="1404" alt="image" src="https://github.com/user-attachments/assets/72be0919-5c7c-44dd-8e86-4189bb0c9c5e">

  - Create a Blob container within the Storage Account.

<img width="1407" alt="image" src="https://github.com/user-attachments/assets/48b6cc97-aa13-4656-b035-a6f5776d34a5">

  - Upload a sample file (e.g., a text file or image) to the Blob container using the Azure portal.

<img width="1406" alt="image" src="https://github.com/user-attachments/assets/cfe10809-c57b-4a76-805b-7c3f7787ea60">

  
- **GCP Cloud Storage:**
  - Access the Googlnewe Cloud Console and create a new Cloud Storage bucket.

<img width="1062" alt="image" src="https://github.com/user-attachments/assets/e9f5f591-38e6-4be1-9df8-7b5f60a9ad6c">

  - Upload a similar sample file to the bucket using the GCP Console.

<img width="1377" alt="image" src="https://github.com/user-attachments/assets/77865a9f-6b52-42ed-9a4d-a8b2af155405">


### 2. Upload Files Using Python

- **Azure Blob Storage:**
  - Write a Python script that uploads a file to the Blob container you created. Use the `azure-storage-blob` library to handle the upload.

- Copy code from "https://colab.research.google.com/drive/1-TiNuRFiGucvnLgTlyp4bsdtR4_TduAT?usp=sharing#scrollTo=ZKgCaehp9NqN"
- Storage account > Access Keys > Update account URL link
- Create "text" file > upload Access Key > Rename .env
- Run "source /workspaces/HHA504_assignment_storage/.venv/bin/activate" and "pip install azure-storage-blob azure-identity python-dotenv" in terminal 
- Create "amen-data.txt" file in codespaces > run azure_storage_example.py > refresh blob container

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


