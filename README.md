📌 Project Title

Multi-Cloud CI/CD Pipeline with Azure DevOps, AWS EC2, and Hybrid Artifact Storage

📄 Project Description

Designed and implemented an end-to-end CI/CD pipeline leveraging Azure DevOps for source control and automation, AWS EC2 (Ubuntu) as a build artifact processing server, and multi-cloud storage using Amazon S3 and Azure Blob Storage. The solution enables developers to push code to Azure Repos, trigger automated pipelines, generate artifacts on a Linux-based AWS server, and store artifacts securely across cloud platforms for redundancy, accessibility, and scalability.

The architecture ensures faster deployments, centralized artifact management, and seamless integration between Azure and AWS environments.

🛠 Technologies Used

Azure DevOps (Boards, Repos, Pipelines, Agents)

AWS EC2 (Ubuntu Linux)

Amazon S3

Azure Blob Storage

Git

Bash/Shell Scripting

YAML Pipelines

Linux Administration

🏗 Architecture Flow

Developer pushes code to Azure Repos

Azure DevOps Pipeline triggers automatically

Pipeline agent transfers build artifacts to AWS Ubuntu EC2 server

Artifacts are validated and processed on EC2

Final artifacts are uploaded to:

Amazon S3 Bucket

Azure Blob Storage Account



<img width="1554" height="649" alt="AWS+Azure+AzureDevOps+Linux" src="https://github.com/user-attachments/assets/6b34f218-88fc-48c7-8a76-f683d5a2964d" />


