# IAM(Identity and Access management)
- IAM plays a critical role in managing the access to AWS services and resources securely:
1. Users:it allows one to create individual IAM users to any user in need to the AWS account
2. Groups:IAM users can be grouped and their permissions defined for an entire group of users,comes in handy if users have similar roles
3. Roles:similar to users but they are used to access other AWS resources,for example a role that allows an EC2 instance to access an S3 bucket
4. Policies:these are JSON documents that define permissions,can be atatched to users,groups or roles to specify which actions they are allowed or denied on which AWS resources
  - Policies can be managed either inline or managed 