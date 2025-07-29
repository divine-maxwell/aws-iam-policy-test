# Beginner IAM Project – AWS IAM Group Policy with Least Privilege Enforcement

✅ Created a group called "Testers"  
✅ Attached the AmazonS3ReadOnlyAccess policy  
✅ Tested with two users to verify read-only S3 access  
✅ Verified policy blocks upload/delete actions  

**Tech Used:** AWS IAM, S3, Managed Policies  
**Skills:** Identity-based access control, Least Privilege, IAM Group Permissions  

# IAM Group Policy Assignment & Least Privilege Enforcement

## 🔐 Project Description
This beginner AWS IAM project demonstrates how to assign group-based permissions using IAM policies, and how to validate the principle of Least Privilege through hands-on testing. The goal was to ensure that users could only perform actions explicitly allowed — no more, no less.

## 🛠️ Tools Used
- AWS IAM Console
- IAM Policy: `AmazonS3ReadOnlyAccess`
- GitHub (for documentation)
- IAM user login test (via browser)

## ✅ What I Did
1. Created a group named `Testers`
2. Attached the AWS-managed policy `AmazonS3ReadOnlyAccess`
3. Added IAM users (`Tomiwa.Addict`, `IsraelOriade`) to the group
4. Logged in as one of the users and tested:
   - ✅ View S3 buckets
   - ❌ Attempt to upload or delete — blocked (as expected)
## 📸 Screenshots

### 1. IAM Group Creation
![IAM Group](screenshots/s3-access-group.jpg)

### 2. Users Added to Group
![Users Added](screenshots/s3-users.JPEG)

### 3. Permissions Attached
![Permissions](screenshots/s3-permissions.JPEG)

### 4. S3 Access Test (Success)
![S3 Access Granted](screenshots/s3-access-granted.JPG)

### 5. S3 Access Test (Denied)
![S3 Access Denied](screenshots/s3-access-denied.jpg)

## 🔍 Test Results

### ✅ Successful Action
User could access and view S3 buckets:
![S3 Access Success](screenshots/s3-access-granted.png)

### ❌ Denied Action
User was blocked from uploading/deleting files:
![S3 Access Denied](screenshots/s3-access-denied.png)

## 🔒 Security Concepts Practiced
- IAM group-based permission assignment
- Managed policies vs inline
- Least Privilege enforcement
- Identity-based access control

## 📁 Project Structure

