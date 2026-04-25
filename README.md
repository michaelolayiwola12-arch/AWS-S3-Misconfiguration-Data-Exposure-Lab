# AWS-S3-Misconfiguration-Data-Exposure-Lab

##  Overview

This project demonstrates how improper configuration of cloud storage can lead to **public data exposure** and how such vulnerabilities can be identified and remediated.

Using AWS S3, I simulated a real-world scenario where a storage bucket was misconfigured, allowing unauthorized public access to sensitive files.

---

##  Objectives

* Understand AWS S3 access control mechanisms
* Simulate a cloud misconfiguration scenario
* Identify publicly exposed data
* Implement security controls to mitigate the risk

---

##  Tools & Technologies

* Amazon S3
* AWS IAM (Identity and Access Management)
* Bucket Policies
* AWS CloudTrail (basic monitoring)

---

##  Lab Steps

### 1. Created S3 Bucket

* Configured a new S3 bucket in AWS
* Enabled default security settings (Block Public Access)

---

### 2. Uploaded Test File

* Uploaded a sample file to simulate stored data

---

### 3. Simulated Misconfiguration

* Disabled Block Public Access
* Applied a bucket policy granting public read access

---

### 4. Verified Exposure

* Accessed the file via its public URL in a web browser
* Confirmed that the file was accessible without authentication

---

### 5. Remediated the Vulnerability

* Removed the public access policy
* Re-enabled Block Public Access
* Verified that access was denied

---

##  Security Insight

This lab highlights a common cloud security risk where **misconfigured access controls** can expose sensitive data to the public.

It reinforces key security principles:

* Least privilege access
* Proper configuration of storage permissions
* Continuous monitoring of cloud resources

---

##  Key Skills Demonstrated

* Cloud security fundamentals
* Access control management
* Misconfiguration detection
* Risk analysis and remediation
* Practical AWS experience

---

##  Learning Outcome

Through this lab, I gained hands-on experience in identifying and fixing cloud security vulnerabilities, particularly those related to storage misconfiguration in AWS environments.

---

## 👤 Author

Michael Olayiwola
Cybersecurity / Application Security Professional
