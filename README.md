# awscodedeploy

sudo yum update -y

sudo yum install -y ruby wget

wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install

chmod +x ./install

sudo ./install auto

sudo service codedeploy-agent status

