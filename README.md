# AWS-S3---Permission-Public-Policy

```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "ARN/*"
        },
        {
            "Sid": "AllowWebAccess",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "ARN/*"
        }
    ]
}
```
