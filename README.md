# AWS IAM + S3 Permissions Demo

## Overview
This project demonstrates how different AWS IAM users interact with an S3 bucket based on their permissions.  
Three users were created: AdminUser, AnalystUser, and InternUser, each with different access levels.

## IAM Users & Permissions
- **AdminUser:** Full access (upload, delete, read)  
- **AnalystUser:** Read-only access (can view/download, cannot upload/delete)  
- **InternUser:** List-only access (can see bucket name, cannot view/download)

## Screenshots
### AdminUser
- Upload succeeded  
![Admin Upload](screenshots/admin_upload.png)  
- Delete succeeded  
[![Admin Delete](screenshots/admin_delete.png)  ](https://github.com/molawal2/aws-iam-project/blob/main/admin%20user%20delete%20success.PNG)

### AnalystUser
- Upload failed (read-only)  
![Analyst Upload Fail](screenshots/analyst_upload_fail.png)  

### InternUser
- Can list bucket but cannot view files  
![Intern Bucket List](screenshots/intern_list.png)  
- File access denied  
![Intern File Fail](screenshots/intern_fail.png)  

## Learning Outcomes
- Hands-on experience managing IAM users and policies in AWS  
- Applied principle of least privilege in cloud security  
- Gained practical experience with Amazon S3
