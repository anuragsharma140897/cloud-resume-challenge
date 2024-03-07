Hosting a static website on AWS using-
AWS S3, AWS Lambda, AWS Cloudfront, AWS ACM, AWS ROUTE 53,AWS IAM, Terraform, Github, YAML.

1) Infrastructure as Code (IaC) with Terraform: Define the infrastructure required for hosting the website using Terraform. This includes resources like S3 bucket, CloudFront distribution, ACM certificate, Route 53 
   hosted zone, and Lambda function.

2) Version Control with Git: Keep track of changes to the website's codebase using Git. This allows for collaboration and version management.

3) Static Website Deployment: Upload the website's files to an S3 bucket. Utilize AWS CloudFront as a content delivery network (CDN) to distribute content globally.

4) HTTPS Setup with ACM and CloudFront: Secure the website using HTTPS by provisioning an ACM certificate and associating it with the CloudFront distribution.

5) Custom Domain Setup with Route 53: Map a custom domain to the CloudFront distribution's URL using Route 53.

6) View Count Functionality with Lambda: Develop a Python script to count website views and display them on the website. Deploy this script as a Lambda function.

7) Continuous Integration and Continuous Deployment (CI/CD) with GitHub Actions: Automate the deployment process using GitHub Actions. Define workflows in YAML files to trigger updates to the S3 bucket whenever changes are pushed to the GitHub repository.

By combining these technologies and services, i have efficiently deployed, managed a static website on AWS, ensuring security, reliability, and seamless user experience.
