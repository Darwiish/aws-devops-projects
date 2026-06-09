# Assignment 3 - S3 Static Website + CloudFront CDN

## Overview

This project demonstrates how to host a static website using Amazon S3 and deliver content globally through Amazon CloudFront with HTTPS provided by AWS Certificate Manager (ACM).

## Architecture

User
↓
Cloudflare DNS
↓
CloudFront CDN
↓
Amazon S3

## Services Used

- Amazon S3
- Amazon CloudFront
- AWS Certificate Manager (ACM)
- Cloudflare DNS

## Outcome

The website is served securely over HTTPS and cached through CloudFront for improved performance.