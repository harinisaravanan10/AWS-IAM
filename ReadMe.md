## Lab 1 - Introduction to AWS Identity and Access Management (IAM)
## NAME : HARINI S
## REGISTER NO: 212223040058
## Title
Introduction to AWS Identity and Access Management (IAM)

## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.

## Prerequisites
Basic understanding of cloud computing concepts
AWS Academy Lab access
Web browser with internet connectivity

## Tools Used
AWS Management Console
AWS Identity and Access Management (IAM)
Amazon EC2
Amazon S3

## Tasks Performed
## Task 1: Explore IAM Users and Groups
Reviewed pre-created IAM users: user-1, user-2, user-3
Explored IAM groups: EC2-Admin, EC2-Support, S3-Support
Inspected managed and inline policies attached to groups
Screenshot:
<img width="1350" height="592" alt="image" src="https://github.com/user-attachments/assets/48c945f0-abf7-40d9-9748-ae07263f285b" />

## Task 2: Add Users to Groups
Added user-1 to the S3-Support group
Added user-2 to the EC2-Support group
Added user-3 to the EC2-Admin group
Screenshot:
<img width="1338" height="596" alt="549927284-1ad45e18-13cf-46ef-8d8a-f205036ab135" src="https://github.com/user-attachments/assets/a02e5e77-8c73-4477-a143-3f852d78a7bc" />
<img width="1334" height="596" alt="549927466-7dfdc707-e4ff-48a3-b638-3b551c4f8547" src="https://github.com/user-attachments/assets/b9ee8211-cae0-47fa-a155-fc58a8c2971d" />
<img width="1336" height="592" alt="549927394-1cb60b5a-f6dc-4a4d-8b84-dea029abd825" src="https://github.com/user-attachments/assets/9a715983-7134-4264-95b8-1f5c35d5214e" />

## Task 3: Test IAM User Permissions
Logged in using IAM sign-in URL
Verified S3 access for user-1
Verified EC2 read-only access for user-2
Verified EC2 administrative access for user-3
Screenshot:
<img width="1344" height="590" alt="549927538-afc80bff-58fa-43c1-afeb-5c161d9bb8be" src="https://github.com/user-attachments/assets/a73c2d60-8767-4014-8025-6221e112aa40" />
<img width="1341" height="599" alt="549927618-74c1cbe1-1176-4045-ad1e-b01e0542ead4" src="https://github.com/user-attachments/assets/b3a73a91-f575-4e6d-b2fb-bef677498e6c" />

## Workflow
Accessed IAM console and reviewed users and groups.
Inspected policy permissions attached to groups.
Assigned users to groups based on their roles.
Logged in as each IAM user using the sign-in URL.
Validated permissions by accessing AWS services.

## Learning Outcomes
Understood the role of IAM in AWS security.
Learned how IAM users, groups, and policies interact.
Gained practical experience implementing role-based access control.
Verified permission enforcement through real-time service testing.

## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.
