
### install aws-cli and unzip then install with sudo on mac with 1 command
```bash
curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"
unzip awscli-bundle.zip
sudo ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws
```

### install aws-cli with step by step
```bash
- Download the latest version: curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"
- Extract file: unzip awscli-bundle.zip
- Run the install:sudo ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws
- Verify that the AWS CLI installed:aws --version
```
### configure aws-cli
- use your own credentials.
- try this line of code to check if your credentials are correct: aws ec2 describe-instances 
