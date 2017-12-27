# Serverless Route53_Backup CloudFormation Template

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

References: 
http://boto3.readthedocs.io/en/latest/reference/services/lambda.html
http://boto3.readthedocs.io/en/latest/reference/services/s3.html
http://boto3.readthedocs.io/en/latest/reference/services/route53.html
http://docs.aws.amazon.com/Route53/latest/APIReference/API_ListHostedZones.html
http://docs.aws.amazon.com/Route53/latest/APIReference/API_ListResourceRecordSets.html
http://grahamm.uk/post/147536460855/backup-route53-to-s3-using-lambda
https://www.reddit.com/r/aws/comments/6xcm06/route_53_backup_tools/
https://www.aaronmedacco.com/blog/post/2017/01/03/automating-backups-of-your-route-53-hosted-zone-dns-records
http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-ref.html
http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/pseudo-parameter-reference.html


Bitcoin Donation:   16CowvxvLSR4BPEP9KJZiR622UU7hGEce5
Ethereum Donation:	0xf75278bd6e2006e6ef4847c9a9293e509ab815c5


