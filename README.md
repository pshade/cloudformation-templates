# cloudformation-templates
AWS CloudFormation templates

## aws cli example
aws cloudformation create-stack --capabilities CAPABILITY_IAM --stack-name helloworld-staging --template-body file://helloworld-staging.yml --parameters ParameterKey=KeyPair,ParameterValue=[ssh-key-name-here]
