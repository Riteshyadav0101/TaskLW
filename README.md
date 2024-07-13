AWS Automation Scripts

A collection of Python scripts for automating various AWS tasks using Boto3.

## Scripts Included

1. **S3 File Uploader:** Uploads files to an Amazon S3 bucket.
2. **Event-Driven S3 to Transcribe:** Converts uploaded audio files in S3 to text using AWS Transcribe.
3. **MongoDB Connector:** Connects to AWS DocumentDB from a Lambda function.
4. **Email Sender via SES:** Retrieves email IDs from S3 and sends emails using SES.

## Usage

1. Configure your AWS credentials using environment variables or the AWS CLI.
2. Update each script with your specific parameters (e.g., bucket names, file paths).
3. Run the scripts to perform the desired tasks.
