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
- For this section, if you want to make it more realistic, I recommend finding some open source open source x-ray images and uploading them to the cloud storage. This though is not a requirement, just a suggestion. Potential sites where you can find medical images: 
  - [Stanford - Center for Ai and Machine Learning](https://aimi.stanford.edu/shared-datasets)
  - [Kaggle - Xray COVID images](https://www.kaggle.com/datasets/andyczhao/covidx-cxr2)
  - [NLM - Open Access Biomedical images search engine](https://openi.nlm.nih.gov/)
  - [Cancer - Imaging Archive](https://www.cancerimagingarchive.net/browse-collections/)

- **Azure Blob Storage:**
  - Write a Python script that uploads a file to the Blob container you created. Use the `azure-storage-blob` library to handle the upload.

- **GCP Cloud Storage:**
  - Write a Python script that uploads a file to the GCP Cloud Storage bucket you created. Use the `google-cloud-storage` library to handle the upload.
  1. Under IAM & Admin, create a service account. 
  2. Provide a name under "Service account details"
  3. Select "Compute storage admin" under "Grand this service account access to this project"
  4. Click Done. 
  5. Click the 3 dots under Actions for the service account. 
  6. Click; Manage Keys. Add Key. Create New Key. JSON key type. Create. Download. 

### 3. Explore Storage Features
- **Azure:**
  - Explore and document the options for managing and securing data in Azure Blob Storage (e.g., access policies, tiers).
- **GCP:**
  - Explore and document the options for managing and securing data in GCP Cloud Storage (e.g., IAM permissions, lifecycle rules).

### 4. Submit Your Work
- Create a Markdown document that includes:
  - Screenshots of the file upload process in both Azure Blob Storage and GCP Cloud Storage using the GUI.
  - The Python code used to upload files to both Azure and GCP.
  - Documentation of the storage management and security features you explored.
