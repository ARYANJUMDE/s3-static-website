# AWS S3 Static Website Hosting with CloudFront

## 📌 Project Overview
This project demonstrates hosting a static website using **Amazon S3** and improving its performance and security using **Amazon CloudFront (CDN)**.

The website is deployed without servers and uses AWS-managed infrastructure, making it scalable, secure, and cost-effective.

---

## 🛠 Technologies Used
- Amazon S3 (Static Website Hosting)
- Amazon CloudFront (Content Delivery Network)
- HTML
- AWS IAM (Bucket Policy)

---

## 🚀 Features
- Static website hosting using Amazon S3
- Public access enabled using bucket policy
- Global content delivery using CloudFront CDN
- HTTPS support via CloudFront
- Low-cost, serverless architecture (Free Tier friendly)

---

## 🧩 Steps Followed

### Day 8 – S3 Static Website Hosting
1. Created an S3 bucket
2. Uploaded `index.html`
3. Enabled static website hosting
4. Disabled block public access
5. Added bucket policy to allow public read access

### Day 9 – CloudFront Integration
6. Created a CloudFront distribution
7. Set S3 bucket as the origin
8. Configured default root object as `index.html`
9. Enabled HTTPS via CloudFront
10. Accessed website using CloudFront distribution URL
    
## 🚀 Deployment on AWS EC2 (Day 12)

This project was deployed on an AWS EC2 instance using Apache.

### Steps Performed:

1. Launched EC2 (Amazon Linux 2023)
2. Connected via SSH
3. Installed Apache (httpd)
4. Started and enabled Apache service
5. Cloned GitHub repository into EC2
6. Copied project files to `/var/www/html`
7. Restarted Apache
8. Accessed website using EC2 Public IP

### Live EC2 URL:
http://43.205.253.17/

---

## 🌐 Live Website

### 🔹 S3 Website URL
http://aryan-static-site-123.s3-website.ap-south-1.amazonaws.com/

### 🔹 CloudFront URL (Recommended)
https://d2ugi1t2ahablk.cloudfront.net/

---

## 📸 Screenshots
Screenshots of S3 configuration and CloudFront distribution are available in the `screenshots` folder.

---

## 💡 Learning Outcomes
- Understood static website hosting using Amazon S3
- Learned how CloudFront improves performance and security
- Gained hands-on experience with AWS bucket policies and CDN concepts
- Built a real-world cloud deployment project

---

## 👤 Author
Aryan


