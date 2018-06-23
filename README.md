
Lubuntu w w/aws-lambda-2/

npm install -g serverless
serverless create -t aws-lambda-2

sudo chmod 777 serverless.yml 
sudo chmod 777 handler.js 

serverless help

sudo chown -R $USER:$(id -gn $USER) /home/fab/.config

--> go to aws Name/My Security Credentials/Access keys

serverless config credentials --provider aws --key XXXXXXXXXXXXX --secret xxxxxxxxxxxxxxxxxx

cat /home/fab/.aws/credentials 

serverless deploy
https://cgl78o9a0d.execute-api.us-east-1.amazonaws.com/dev/users/create


