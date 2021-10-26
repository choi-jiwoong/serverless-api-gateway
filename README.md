# serverless-api-gateway
JWT tokens Amazon DynamoDB Lambda function Amazon API Gateway [Serverless](serverless.com)


## install 
### [install](https://www.serverless.com/framework/docs/providers/aws/guide/installation)

```shell
$ npm install -g serverless
:
:
$ serverless --version
```

### AWS - [Credentials](https://www.serverless.com/framework/docs/providers/aws/guide/credentials)

1. Login to your AWS account and go to the Identity & Access Management (IAM) page.

2. Click on Users and then Add user. Enter a name in the first field to remind you this User is related to the Serverless Framework, like serverless-admin. Enable Programmatic access by clicking the checkbox. Click Next to go through to the Permissions page. Click on Attach existing policies directly. Search for and select AdministratorAccess then click Next: Review. Check to make sure everything looks good and click Create user.

3. View and copy the API Key & Secret to a temporary place. You'll need it in the next step.


### add configuration 

- Develop : ./config/config.dev.json
- Stage : ./config/config.stage.json
- Production : ./config/config.prod.json

### build 
- edit deplay file 
- vi deplay_dev.sh

### edit user
- vi ./aws-api-gateway/lub/users.js 

