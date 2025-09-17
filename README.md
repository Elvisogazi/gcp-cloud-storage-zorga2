# GCP Cloud Storage Bucket – Zorga2

This project demonstrates how I created and managed a **Google Cloud Storage bucket** using both the **Google Cloud Console** and **Cloud Shell**.  
It’s a simple but essential project that highlights my ability to work with cloud storage in Google Cloud.

---

## 🚀 Project Overview
- **Bucket name**: `zorga2`
- **Tools used**: Google Cloud Console & Cloud Shell
- **Objective**: Create a bucket, upload files via both console and CLI, and verify successful storage.

---

## 🔧 Steps Taken

### 1. Bucket Creation (Console)
- Opened **Google Cloud Console**
- Navigated to **Storage → Buckets → Create Bucket**
- Set bucket name: `zorga2` (globally unique)
- Selected region and default storage class
- Created the bucket successfully

### 2. Uploading Files (Console)
- From the **Cloud Console**, uploaded a sample image (`sample-image.png`)  
- Verified the file appeared in the bucket

### 3. Uploading Files (Cloud Shell)
- Launched **Cloud Shell**
- Ran the following command:
  ```bash
  gsutil cp sample-image.png gs://zorga2/
