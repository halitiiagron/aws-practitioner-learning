## IAM Lab: Created IAM user with S3 access
- Created IAM user with AmazonS3FullAccess policy
- Verified full access to S3 bucket: upload, delete, view

## IAM Lab 2 – S3 Read-Only Custom User
- Created IAM user: s3-readonly-user
- Created custom policy: read-only access to haliti-agron-static-site bucket
- Verified:
  - ✅ Can list bucket and read files via CLI
  - ❌ Cannot upload or delete (AccessDenied as expected)

