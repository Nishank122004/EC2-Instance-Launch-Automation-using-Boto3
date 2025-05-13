# EC2 Instance Launch Automation using Boto3

This mini project demonstrates how to automate the process of launching an EC2 instance on AWS using Python and the Boto3 SDK.

# Features
- Launches a **t2.micro** EC2 instance
- Uses a specific **Amazon Machine Image (AMI)**
- Automatically adds a **Name tag** to the instance
- Uses your AWS **default profile**

# Requirements
- Python 3.x
- Boto3 library
- AWS CLI configured with a profile named `default`
  
# Setup
1. Install Boto3:
   ```bash
   pip install boto3
