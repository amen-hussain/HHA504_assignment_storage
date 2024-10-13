# HHA504_assignment_storage
Working with cloud storage in Azure and GCP


### 1. Upload Files Using the GUI
- **Azure Blob Storage:**
  - Navigate to the Azure portal and create a new Storage Account.
  - Create a Blob container within the Storage Account.
  - Upload a sample file (e.g., a text file or image) to the Blob container using the Azure portal.
  
- **GCP Cloud Storage:**
  - Access the Google Cloud Console and create a new Cloud Storage bucket.
  - Upload a similar sample file to the bucket using the GCP Console.
  - Example repo of what we did during class: ['Class Repo'](https://github.com/hantswilliams/gcp-cloud-storage-demo)

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
