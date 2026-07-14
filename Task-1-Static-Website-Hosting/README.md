# Task 1: Static Website Hosting & CDN Delivery

## Objective

The objective of this task is to build a modern responsive frontend application and deploy it using Amazon S3 and Amazon CloudFront.

The project demonstrates static website hosting, cloud storage, Content Delivery Network (CDN) configuration, and secure HTTPS content delivery.

## Project

A responsive React login page was developed for a fictional real estate platform called **Manresa Real Estate**.

The application was built using React and Vite and deployed to AWS.

## Technologies and AWS Services Used

- React
- Vite
- HTML
- CSS
- JavaScript
- Amazon S3
- Amazon CloudFront
- GitHub

## Architecture

The deployment architecture used in this project is:

User → Amazon CloudFront CDN → Amazon S3 Static Website

## Steps Performed

### 1. React Website Development

Created a responsive React-based login page for Manresa Real Estate.

The application contains:

- Responsive user interface
- Email and password fields
- Remember Me option
- Forgot Password link
- Sign In button
- Responsive layout for different screen sizes

### 2. Production Build

Generated an optimized production build of the React application using Vite.

The following command was used:

`npm run build`

The production files were generated inside the `dist` directory.

### 3. Amazon S3 Bucket Creation

Created an Amazon S3 bucket named:

`growfinix-task1-anyesh`

The S3 bucket was used to store and host the production website files.

### 4. Website Files Uploaded to Amazon S3

Uploaded the generated production files to the S3 bucket.

The uploaded files included:

- `index.html`
- `assets` directory
- JavaScript production bundle
- CSS production bundle

### 5. Static Website Hosting Configuration

Enabled Amazon S3 Static Website Hosting.

The index document was configured as:

`index.html`

Public access permissions and the required S3 bucket policy were configured to allow access to the static website.

### 6. Website Deployment Verification

The website was successfully accessed and verified using the Amazon S3 Static Website Hosting endpoint.

## Implementation Screenshots

### 1. Manresa Real Estate React Website

![Static Website](Screenshot%202026-07-14%20151519.png)

### 2. Production Build Successfully Generated

![Production Build](Screenshot%202026-07-14%20152148.png)

### 3. Amazon S3 Bucket Created

![S3 Bucket Created](Screenshot%202026-07-14%20153437.png)

### 4. Production Files Uploaded Successfully

![Upload Successful](Screenshot%202026-07-14%20154311.png)

### 5. Website Files Stored in Amazon S3

![S3 Bucket Objects](Screenshot%202026-07-14%20154351.png)

### 6. Website Successfully Hosted Using Amazon S3

![S3 Hosted Website](Screenshot%202026-07-14%20183232.png)

## Amazon CloudFront CDN Deployment

To improve content delivery and provide HTTPS access, an Amazon CloudFront distribution was configured for the static website.

### CloudFront Configuration Steps

1. Opened the Amazon CloudFront service.
2. Created a new CloudFront distribution.
3. Selected the Amazon S3 static website endpoint as the origin.
4. Configured the recommended origin settings.
5. Configured the recommended cache settings for S3 content.
6. Created and deployed the CloudFront distribution.
7. Verified the deployment using the CloudFront distribution domain.
8. Successfully accessed the website using HTTPS through Amazon CloudFront.

### CloudFront Distribution Name

`growfinix-task1-cloudfront`

### CloudFront Deployment Result

The Manresa Real Estate website was successfully delivered through the Amazon CloudFront Content Delivery Network.

The website is accessible through a secure HTTPS CloudFront endpoint.

![CloudFront Deployment](Screenshot%202026-07-14%20194559.png)

## Result

The responsive Manresa Real Estate React application was successfully built and deployed using Amazon S3 Static Website Hosting.

Amazon CloudFront was successfully configured as the Content Delivery Network (CDN), providing HTTPS access and improving the delivery of the website content.

## Skills Learned

- React application development
- Vite production builds
- Amazon S3 bucket creation
- Static website hosting
- S3 bucket policies and public access configuration
- Amazon CloudFront distribution creation
- CDN configuration
- HTTPS content delivery
- Cloud deployment
- GitHub project documentation

## S3 Website Endpoint

`http://growfinix-task1-anyesh.s3-website-us-east-1.amazonaws.com`

## CloudFront HTTPS Endpoint

`https://dc81s0cl15for.cloudfront.net`

## Conclusion

Task 1 successfully demonstrates the development and deployment of a modern frontend application using Amazon S3 and Amazon CloudFront.

The application was deployed to cloud storage and distributed through a CDN with HTTPS access.
