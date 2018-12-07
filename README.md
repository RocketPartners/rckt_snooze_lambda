# AWS Lambda Adapter for the "Snooze" API as a Service Platform

Work in progress.

Need to work on connection pooling code so that you don't actually have to use a pool w/ Lambda since a single
lambda does not service concurrent requests.

See the main [Snooze API as a Service](https://github.com/RocketPartners/rckt_snooze) page or the [Spring Boot Quickstart Template](https://github.com/RocketPartners/rckt_snooze_spring) for more information.

 * https://docs.aws.amazon.com/lambda/latest/dg/vpc.html
 * https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-lambda-function-vpcconfig.html
 * https://docs.aws.amazon.com/apigateway/latest/developerguide/set-up-lambda-proxy-integrations.html
 * https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-create-api-as-simple-proxy-for-lambda.html