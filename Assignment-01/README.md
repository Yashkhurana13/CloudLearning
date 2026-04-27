# AWS EC2 Static Website Hosting with IAM Access Control

## 👤 Student Details

* **Name:** Yash Khurana
* **Registration Number:** 12324617

## 🌐 Deployed Link

http://54.236.133.138

---

## 📌 Project Description

This project demonstrates hosting a static website on AWS EC2 and implementing IAM-based access control.

---

## ⚙️ Steps Performed

* Launched EC2 instance (Ubuntu)
* Installed Apache2 web server
* Deployed static website (HTML, CSS, JS)
* Attached Elastic IP for stable access
* Created IAM users with different permissions

---

## 👤 IAM Users

### User1

* No permissions
* Cannot access EC2

### User2

* AmazonEC2FullAccess
* Can access EC2 dashboard

---

## 📸 Screenshots

### EC2 Instance

![EC2](screenshot/ec2.png)

### Website Running

![Website](screenshot/website.png)

### User1 Login

![User1](screenshot/user1.png)

### User2 Login

![User2](screenshot/user2.png)

---

## ⚠️ Challenges Faced

* SSH connection issues
* Key permission errors
* File transfer using SCP

---

## ✅ Conclusion

Successfully deployed a static website on AWS EC2 and implemented IAM access control.
