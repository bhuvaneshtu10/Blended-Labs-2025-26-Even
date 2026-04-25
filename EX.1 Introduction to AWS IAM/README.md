# Lab 1 - Introduction to AWS Identity and Access Management (IAM)
## Author
```
Name:Bhuvaneshwaran TU
Reg.no.: 212224040049
Course: Introduction to Cloud Computing
Slot: 25EV2059
```
## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**
   
<img width="1919" height="993" alt="cctask1" src="https://github.com/user-attachments/assets/ec44cb4f-8060-4bcf-8874-3b58f892c449" />

<img width="1917" height="988" alt="cctask1 2" src="https://github.com/user-attachments/assets/7842b95c-81ac-4632-ba5f-dac2a3a315fa" />

<img width="1914" height="990" alt="cctask1 3" src="https://github.com/user-attachments/assets/bd904e33-6252-4ec8-99f1-949d8b924e3f" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  

<img width="1919" height="976" alt="cc" src="https://github.com/user-attachments/assets/d447c273-e310-4ac9-a4c2-131f168c9a6c" />

### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**

<img width="1919" height="983" alt="cctask3 1" src="https://github.com/user-attachments/assets/ee638e32-416c-471e-bba9-7fa9fddbdc3c" />

<img width="1918" height="990" alt="cctask3 2" src="https://github.com/user-attachments/assets/30736bf1-2a3d-4f7c-9939-84432b1409a9" />

## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.

