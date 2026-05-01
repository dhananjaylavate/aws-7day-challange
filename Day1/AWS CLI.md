**🖥️ What is AWS CLI?**


**AWS CLI (Command Line Interface) is a tool that lets you control and manage AWS services using commands in a terminal instead of the AWS console (website).**



**🧠 Simple Explanation**


Think of AWS Console as: 🖱️ “Clicking buttons on a website”

And AWS CLI as: ⌨️ “Typing instructions to AWS”

So instead of clicking: S3 → Bucket → Upload file

You can just type: `aws s3 cp file.txt s3://my-bucket/`


**⚙️ What can you do with AWS CLI?**

**You can manage almost everything in AWS, like:**

**☁️ S3 (Storage)**

`aws s3 ls`

`aws s3 cp file.txt s3://bucket/`

**🖥️ EC2 (Servers)**

`aws ec2 describe-instances`

**👤 IAM (Users & Roles)**

`aws iam list-users`

**🚀 Why AWS CLI is useful**

✔️ Faster than clicking in console

✔️ Useful for automation (scripts)

✔️ Used in DevOps and real-world jobs

✔️ Works with EC2, servers, CI/CD pipelines


**👉 AWS CLI = command-based way to control AWS**
