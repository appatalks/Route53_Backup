# Route53_Backup

This is an AWS CloudFormation Template designed as a serverless Route53 Backup using Lambda and S3.

Two Parameters
     -- Bucket Name - Required
     -- IAM Role Name - Optional (Template already uses a recommended Role Name)

What the Template Does
     -- Everything. (Designed to be drag and dropped on any account)

What to check for after creation  (Currently set to run on any Route53 Adjustments and two week intervals)
     -- New Log Group Created after first run
     -- S3 Bucket has been created
     -- IAM Role has been created
     -- CloudWatch Event has been created
     -- Lambda Function Created
