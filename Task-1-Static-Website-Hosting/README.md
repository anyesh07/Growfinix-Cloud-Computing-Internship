# Task 1: Static Website Hosting on AWS S3

## Objective

The objective of this task is to deploy and host a static website using Amazon S3.

## AWS Services Used

- Amazon S3

## Steps Performed

1. Created a React-based static website.
2. Generated the production build using Vite.
3. Created an Amazon S3 bucket.
4. Uploaded the production build files to the S3 bucket.
5. Enabled Static Website Hosting.
6. Configured `index.html` as the index document.
7. Configured public access permissions for the website.
8. Accessed and verified the deployed website using the S3 website endpoint.

## Implementation Screenshots

### 1. Static Website

![Static Website](Screenshot%202026-07-14%20151519.png)

### 2. Production Build

![Production Build](Screenshot%202026-07-14%20152148.png)

### 3. Amazon S3 Bucket Created

![S3 Bucket Created](Screenshot%202026-07-14%20153437.png)

### 4. Website Files Uploaded Successfully

![Upload Successful](Screenshot%202026-07-14%20154311.png)

### 5. Files Stored in S3 Bucket

![S3 Bucket Objects](Screenshot%202026-07-14%20154351.png)

### 6. Website Successfully Hosted on Amazon S3

![Deployed Website](Screenshot%202026-07-14%20183232.png)

## Amazon CloudFront Deployment

To improve website performance and content delivery, an Amazon CloudFront distribution was created using the S3 static website endpoint as the origin.

### Steps Performed

1. Created an Amazon CloudFront distribution.
2. Selected the Amazon S3 static website endpoint as the origin.
3. Configured the recommended origin and cache settings.
4. Deployed the CloudFront distribution.
5. Successfully accessed the static website using the CloudFront distribution domain.

### CloudFront Deployment Result

The static website was successfully delivered through Amazon CloudFront.

![CloudFront Deployment](Screenshot%202026-07-14%20194559.png)

## Result

The static website was successfully built, deployed, and hosted using Amazon S3 Static Website Hosting, and content delivery was enhanced using Amazon CloudFront.

## Website Endpoint

`http://growfinix-task1-anyesh.s3-website-us-east-1.amazonaws.com`
