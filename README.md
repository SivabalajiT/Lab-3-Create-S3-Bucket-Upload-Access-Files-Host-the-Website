

# **Lab 3: Create S3 Bucket, Upload Files, Access Files & Host a Website**

## **Overview**
This project demonstrates the steps to:
1. Create an S3 bucket in AWS.
2. Upload files to the S3 bucket.
3. Access files from the bucket.
4. Configure the bucket to host a static website.

---

## **Technologies Used**
- **AWS S3**: For file storage and hosting.
- **HTML/CSS**: For the static website files.
- **AWS Management Console**: To configure the bucket.

---

## **Steps Covered**
### **1. Create an S3 Bucket**
- Log in to AWS.
- Navigate to the S3 service.
- Create a bucket with a unique name.
- Configure bucket permissions and settings.

### **2. Upload Files**
- Upload HTML, CSS, and any other necessary files for your website.
- Set the files' permissions to "Public Read" for access.

### **3. Access Files**
- Generate the file URL and test it in a browser.
- Ensure files are accessible to the public (depending on use case).

### **4. Host a Static Website**
- Enable **Static Website Hosting** in the bucket settings.
- Set the **index document** (e.g., `index.html`) and error document (if applicable).
- Access your website using the bucket’s static website endpoint.

---

## **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Replace the provided sample website files with your own.
3. Follow the steps mentioned above to set up your S3 bucket.

---

## **Expected Output**
1. Publicly accessible files through URLs.
2. A fully hosted static website via the S3 bucket's static website hosting feature.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
