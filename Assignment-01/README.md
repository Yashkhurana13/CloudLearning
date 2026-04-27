# 🌐 AWS S3 Static Website Hosting with Versioning & Lifecycle Management

## 👤 Student Details

* **Name:** Yash Khurana
* **Registration Number:** 12324617

---

## 📌 Assignment Objective

This assignment demonstrates the use of Amazon S3 for:

* Object storage fundamentals
* Static website hosting
* Version control using S3 Versioning
* Storage cost optimization using Lifecycle Rules

---

## 🚀 Project Overview

A static website is hosted using an Amazon S3 bucket. The bucket is configured to allow public access, enabling the website to be accessed via a public URL. Versioning is enabled to maintain multiple versions of files, and lifecycle rules are applied to optimize storage cost by transitioning and deleting objects automatically.

---

## 🌍 Live Website Link

👉 **S3 Website URL:**
http://yash-s3-assignment-aws-942852434311-us-east-1-an.s3-website-us-east-1.amazonaws.com

---

## ⚙️ Features Implemented

### ✅ 1. S3 Bucket Creation

* Created a globally unique S3 bucket
* Configured necessary permissions for public access

### ✅ 2. Static Website Hosting

* Enabled static website hosting
* Set `index.html` as the entry point
* Website successfully accessible via public URL

### ✅ 3. Versioning

* Enabled versioning on the bucket
* Uploaded multiple versions of `index.html`
* Verified different versions using the S3 console

### ✅ 4. Lifecycle Management

* Created lifecycle rule to:

  * Transition objects to **Standard-IA** after 30 days
  * Delete non-current versions after 60 days

---

## 📂 Project Structure

```
Assignment-02/
│── index.html
│── styles.css
│── script.js
│── screenshots/
```

---

## 📸 Screenshots

### 🔹 S3 Bucket (Objects View)

<img src="screenshots/bucket.png" width="700">

---

### 🔹 Versioning Enabled

<img src="screenshots/versioning.png" width="700">

---

### 🔹 Static Website Hosting

<img src="screenshots/hosting.png" width="700">

---

### 🔹 Lifecycle Rule Configuration

<img src="screenshots/lifecycle.png" width="700">

---

### 🔹 Live Website

<img src="screenshots/website.png" width="700">

---

## ⚠️ Challenges Faced

* Faced issue with **Access Denied (403 error)** while accessing the website
* Resolved by:

  * Disabling "Block Public Access"
  * Adding correct **bucket policy with `/*`**

---

## 📚 Key Learnings

* Understanding of S3 object storage and bucket configuration
* Hands-on experience with static website deployment
* Importance of version control in cloud storage
* Cost optimization using lifecycle policies

---

## ✅ Conclusion

This assignment helped in gaining practical experience with AWS S3 services including hosting, versioning, and lifecycle management. It provided insights into real-world cloud storage solutions and cost optimization strategies.

---

⭐ **Thank You**
