# Deploying a resume using AWS S3, CloudFront and Route 53

## overview

The purpose of this project is to write a resume in CSS, to host it in an AWS S3 bucket, use Amazon CloudFront to secure connection to the website and ensure all connections are HTTPS and to finally use Amazon Route 53 for DNS management.

## Editing the CSS template to add personal information

The first step is to edit the index.html file in the second resume template to include relevant personal information to be included in the resume.
The information should be formatted appropriately to include name, educational background, contact information and skills.

## Hosting a static website on Amazon S3

* Create an S3 bucket and give it a globally unique name.
* Upload all files related to the static website to be hosted into the S3 bucket.
* Review permissions and block all direct public access from the internet.

