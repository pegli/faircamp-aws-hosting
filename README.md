# faircamp-aws-hosting

Host a music distribution web site on AWS using Faircamp, S3, and CloudFront.

## Overview

[Faircamp](https://simonrepp.com/faircamp/) is an open-source tool that helps musicians and
music labels create rich, engaging sites for distributing songs and albums.  It creates a static
web site that can be hosted anywhere.

This project provides resources for deploying a Faircamp site to AWS using low-cost services.
With this solution, the files are hosted on [Amazon S3](https://aws.amazon.com/s3/) and served
to the world through [Amazon CloudFront](https://aws.amazon.com/cloudfront/).  

## Prerequisites

1. An AWS account.  When you [sign up](https://aws.amazon.com/free/) for AWS, there are no recurring
charges; you only pay for the services you use.  Most of the service configurations in this solution
are part of the AWS Free Tier.
2. Your account must have permissions to run CloudFormation templates and to manage the resources created
by this solution (primarily S3, CloudFront, Route 53, and Certificate Manager).
4. A registered domain name hosted on Amazon Route 53 (e.g. `example.com`).   For more information, see
[Configuring Amazon Route 53 as your DNS service](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/dns-configuring.html).

## Installation


## Disclaimer

By running this project, you are creating configurations in AWS that may result in charges to the
payment method you provided when you signed up for an account.  You are responsible for all charges
incurred as part of running this solution. Use at your own risk, and
[monitor your account spend](https://aws.amazon.com/aws-cost-management/aws-budgets/)!
