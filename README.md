# codepipeline-project
## End-to-End CI/CD Setup with GitHub and AWS CodePipeline

# My Scenario:
Our team at RootsTech was tasked with automating the deployment of a website. This required collaboration with developers on a static site URL and making code modifications in the Git repository to validate the pipeline's functionality.
CI/CD Pipeline Overview:
A CI/CD pipeline leverages automation to boost productivity in software development, ensuring higher code quality, faster deployment times, and enhanced security. Automating certain development processes enables seamless integration and delivery.
Key Components:
Amazon S3 Bucket: A secure storage container for data files (objects).
GitHub: A platform that developers use to manage and store code repositories.
AWS CodePipeline: A service that automates the steps necessary for continuous integration and delivery (CI/CD) of software updates.

Project Prerequisites:
AWS S3 Bucket Configuration:
Block Public Access: Keep access restricted until the static site is ready for review to ensure secure operations.
Enable Static Website Hosting: Configure the bucket to host the website, allowing it to store and serve the necessary data files.

Implementation Plan:
The project begins with a simple HTML file provided to us, which we'll store in a GitHub repository. This setup in GitHub will enable us to manage and track modifications effectively throughout the pipeline.

![Screenshot 2024-11-13 223811](https://github.com/user-attachments/assets/d23557f2-9fe6-4c75-934e-1c726f0aca0d)
