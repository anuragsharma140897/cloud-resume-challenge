Hosting a static website on AWS using-
AWS S3, AWS Lambda, AWS Cloudfront, AWS ACM, AWS ROUTE 53,AWS IAM, Terraform, Github, YAML.

1- Static Website Deployment: Uploaded the website's files to an S3 bucket. Utilized AWS CloudFront as a content delivery network (CDN) to distribute content globally.

2- HTTPS Setup with ACM and CloudFront: Secured the website using HTTPS by provisioning an ACM certificate and associating it with the CloudFront distribution.

3- Custom Domain Setup with Route 53: Mapped a custom domain (resume.anurag.online) to the CloudFront distribution's URL using Route 53.

4- View Count Functionality with Lambda: Deployed a Lambda function using Python script to count website views and display them on the website.

5- Version Control with Git: used to track changes to the website's codebase using Git. This allowed us for collaboration and version management.

6- Continuous Integration and Continuous Deployment (CI/CD) with GitHub Actions: Automated the deployment process using GitHub Actions. Defined workflows in YAML files to trigger updates to the S3 bucket whenever 
   changes are pushed to the GitHub repository.

7- Infrastructure as Code (IaC) with Terraform: Defined the complete front end and Back end infrastructure required for hosting the website using Terraform.

   By combining these technologies and services, i have efficiently deployed, managed a static website on AWS, ensuring security, reliability, and seamless user experience.
  














