# Route53_Backup

This is an AWS CloudFormation Template designed as a serverless Route53 Backup using Lambda and S3.<p>

Two Parameters
     <p>
     -- Bucket Name - Required<p>
     -- IAM Role Name - Optional (Template already uses a recommended Role Name)<p>
What the Template Does<p>
     -- Everything. (Designed to be drag and dropped on any account)<p>
What to check for after creation  (Currently set to run on any Route53 Adjustments and two week intervals)<p>
     -- New Log Group Created after first run <p>
     -- S3 Bucket has been created <p>
     -- IAM Role has been created <p>
     -- CloudWatch Event has been created <p>
     -- Lambda Function Created <p>
