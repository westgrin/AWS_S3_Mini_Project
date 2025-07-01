# # AWS S3 Mini Project

## Project Overview
This 2-hour mini-project explores Amazon S3 for data storage, covering bucket creation, object upload, versioning, permissions, and lifecycle policies, executed on Ubuntu (WSL) with VS Code via Ubuntu.

## Setup
- Initiated on Jul 01, 2025, 03:46 PM WAT.
- Used Ubuntu terminal (WSL) with VS Code, documented in ~/Documents/Workspace/AWS_S3_Mini_Project.

## Project Execution

### 1. Log In and Navigate to S3 Dashboard
- Logged into AWS Management Console and accessed S3 dashboard.

### 2. Part 1 - Create an S3 Bucket
- Created bucket `my-first-s3-bucket-071` with “Block all public access” enabled.

### 3. Part 2 - Upload an Object
- Created `welcome.txt` with “Welcome to the AWS world” and uploaded to the bucket.

### 4. Part 3 - Enable Versioning
- Enabled versioning, uploaded an updated `welcome.txt` (“Updated AWS world”), and viewed versions.

### 5. Part 4 - Configure Permissions for Public Access
- Unblocked public access, created a bucket policy allowing `s3:GetObject` and `s3:GetObjectVersion` for all, and verified with object URL.

### 6. Part 5 - Implement Lifecycle Policies
- Added a lifecycle rule to transition objects to Standard-IA after 30 days.

### Project Reflection
- **Hands-On Experience**: Gained practical skills in managing S3 buckets and objects.
- **Key Concepts**: Learned versioning for data recovery, permissions for access control, and lifecycle policies for cost optimization.
- **S3 Features**: Understood durability, scalability, and security benefits.
- **Real-World Application**: Acquired skills to optimize storage costs and ensure data reliability in scenarios like backups or websites.

## Tools Used
- **Ubuntu Terminal (WSL)**: For file creation and documentation.
- **VS Code**: For editing `README.md`.
- **Git Bash**: For version control and GitHub push.
- **AWS Management Console**: For S3 management.

## Project Deliverables
- **Documentation**: This `README.md` details the process and reflection.
- **Script Link**: [GitHub Repository](https://github.com/westgrin/AWS_S3_Mini_Project)

## Conclusion
This project successfully implemented S3 features, providing a foundation for scalable and secure data storage, with practical skills applicable to real-world use cases.