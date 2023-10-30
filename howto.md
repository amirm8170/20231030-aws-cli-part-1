
### install aws-cli and unzip then install with sudo on mac with 1 command
```bash
curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"
unzip awscli-bundle.zip
sudo ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws
```

### configure
```bash
aws configure
``` 
### describe instance 
```bash
- aws ec2 describe-instances --output [json,text,table,yaml,yaml-stream]
```bash
