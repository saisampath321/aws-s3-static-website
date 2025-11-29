AWS S3 Static Website Hosting
This project showcases the process of hosting a fully static website using Amazon S3. The deployment leverages S3's built-in bucket hosting feature, enabling users to access the website via a public, AWS-generated endpoint.
📌 Project Overview
The following steps were undertaken to successfully host the static website:
   S3 Bucket Creation: An S3 bucket was specifically created for the purpose of hosting a static website.
   Public Access Configuration:
   The "Block Public Access" setting was disabled to permit public viewing of the website content.
   An IAM Bucket Policy was applied to grant public read-only access to the bucket's objects.
   Static Website Hosting Enablement:
   Static Website Hosting was enabled within the S3 bucket settings.
   index.html was designated as the entry point for the website.
   Content Deployment: A custom HTML webpage was uploaded to the S3 bucket.
   Deployment Verification: The website was successfully deployed and accessed through AWS's static site endpoint.
   Browser Access: The website was verified and accessed via a web browser using its public URL.
🛠 Technologies &amp; AWS Services Used
This project utilized a combination of technologies and AWS services:
   Amazon S3: The primary service for storing and hosting the static website content.
   IAM (Identity and Access Management): Used for defining and applying the necessary bucket policy to control access.
   Static Website Hosting: A feature within S3 that allows buckets to serve web content.
   HTML: The language used to create the custom webpage.
   AWS Global Edge Network: Leveraged for content delivery and improved website performance.
🚀 Skills Learned
Through the execution of this project, valuable skills were acquired and reinforced:
   Hosting Static Websites on AWS: Gained practical experience in deploying static websites using AWS infrastructure.
   Managing S3 Bucket Permissions: Developed proficiency in configuring and managing access controls for S3 buckets.
   Applying IAM Policies: Learned how to create and implement IAM policies to grant specific permissions.
   Understanding Public vs. Private Cloud Access: Enhanced comprehension of the distinctions and implications of public and private access within a cloud environment.
   Working with AWS Console &amp; Regional Endpoints: Became more familiar with navigating the AWS Management Console and understanding regional endpoints.
   Basics of Cloud Deployment Workflow: Gained insight into the fundamental steps involved in deploying applications to the cloud.
🌐 Live Website Link
The live website can be accessed at the following public URL:
http://my-static-site-sampath.s3-website-ap-southeast-2.amazonaws.com
