# Deploying a HTML resume using AWS S3, CloudFront and Route 53
# Welcome to CloudMyTribe community project challenges!

# Table of Contents
1. [Introduction](#introduction-)
2. [How to Get Started](#how-to-get-started)
3. [Your Cloud Resume Challenge: Host Your Static Website on AWS](#your-cloud-resume-challenge-host-your-static-website-on-aws)
   - [Milestone 1: Deploying with the AWS Console](#milestone-1--deploying-with-the-aws-console-)
     - [Step-by-Step Guide](#step-by-step-guide)
       - [Review the Challenge Requirements](#review-the-challenge-requirements)
       - [Explore AWS Documentation](#explore-aws-documentation)
       - [Build Your Architecture Diagram](#build-your-architecture-diagram)
       - [Create Your HTML Resume](#create-your-html-resume)
       - [Deploy Your Resume as a Static Website on S3](#deploy-your-resume-as-a-static-website-on-s3)
       - [Enable HTTPS with CloudFront](#enable-https-with-cloudfront)
       - [Set Up Custom DNS with Route 53](#set-up-custom-dns-with-route-53)
       - [Configure IAM for Access Management](#configure-iam-for-access-management)
       - [Document Your Progress](#document-your-progress)
       - [Create a Screen Recording or Deploy a Live Website (Optional)](#create-a-screen-recording-or-deploy-a-live-website-optional)
     - [Deliverables](#deliverables-)

## Introduction

The purpose of this challenge by CloudMyTribe is to write a resume in HTML, to host it in an AWS S3 bucket, use Amazon CloudFront to secure connection to the website and ensure all connections are HTTPS and to finally use Amazon Route 53 for custom DNS management. This challenge is designed for beginners in cloud or anyone looking to sharpen their skills on AWS services.

## Step-by-Step Guide

### How to Get Started
1. **Prepare Your Tools**
   - Ensure you have the necessary tools and accounts set up, including an **AWS account**, **GitHub account**, and a **gitpod** or your preferred IDE for a connected and seamless deployment experience.

#### 2. Explore AWS Documentation
- **Action**: Dive into AWS documentation to familiarize yourself with the services needed for this challenge. Focusing heavily on:
 - [Amazon S3 (for static website hosting)](https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html)
 -  - [AWS CloudFront (for CDN)](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
 - [Route 53 (for DNS management)](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
 - [IAM (for access management)](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- **Outcome**: Knowledge of the services you'll be using, including best practices and configurations.

   

diting the html template to add personal information

The first step is to edit the index.html file in the second resume template to include relevant personal information to be included in the resume.
The information should be formatted appropriately to include name, educational background, contact information and skills.

### Hosting a static website on Amazon S3

*
* Create an S3 bucket and give it a globally unique name.
* Upload all files related to the static website to be hosted into the S3 bucket.
* Review permissions and block all direct public access from the internet.

