# AWS S3 Static Website Hosting

## Project Overview

This project demonstrates hosting a static website using Amazon S3 Static Website Hosting and integrating a custom domain using Amazon Route 53.

### Live Website

http://muyarchi.in

---

## Architecture

User
↓
Route 53
↓
Amazon S3 Static Website

---

## AWS Services Used

- Amazon S3
- Amazon Route 53
- AWS IAM

---

## Features

- Static Website Hosting
- Custom Domain Integration
- Public Access Configuration
- DNS Resolution using Route 53

---

## Implementation Steps

### 1. Purchased Domain

Domain: muyarchi.in

Registrar: Hostinger

### 2. Created S3 Bucket

Bucket Name:

muyarchi.in

### 3. Uploaded Website Files

- index.html

### 4. Enabled Static Website Hosting

Index Document:

index.html

### 5. Configured Public Access

- Disabled Block Public Access
- Configured Bucket Policy

### 6. Created Route 53 Hosted Zone

Hosted Zone:

muyarchi.in

### 7. Updated Nameservers

Updated Hostinger nameservers to Route 53 nameservers.

### 8. Created Route 53 Alias Record

Mapped:

muyarchi.in

to

Amazon S3 Static Website Endpoint

---

## Challenges Faced

### Bucket Policy Error

Issue:

Policy has invalid resource

Root Cause:

Incorrect bucket ARN used in bucket policy.

Resolution:

Updated the bucket ARN with the correct bucket name.

---

## Outcome

Successfully hosted a static website using Amazon S3 and Route 53 and mapped it to a custom domain.

Website:

http://muyarchi.in

## Screenshots

### Website Working

screenshots/Browsing%20Page.png

### S3 Bucket

![S3 nshots/Bucket.png

### Static Website Hosting

screenshots/static%20website%20Hosting.png

### Bucket Policy

screenshots/Bucketpolicy.png

### Route 53 Hosted Zone

![Route 53 /Route53%20Hosted%20Zone.png

