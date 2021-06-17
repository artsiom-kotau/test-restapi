https://us-east-2.console.aws.amazon.com/ecs/home?region=us-east-2#/firstRun
aws cloudformation create-stack --stack-name staging-vpc --template-body file://vpc.yaml --parameters ParameterKey=EnvironmentName,ParameterValue=staging
