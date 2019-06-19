# spring-cloud-function"

Dev Testing
- Run CloudfunctionApplication class curl localhost:8080/reverseString/hello

AWS Lambda Deployment
- Open Lambda Console
- Upload your -aws.jar 
- Set your handler as com.test.cloud.function.MyHandler
- Set following environment variables
  1. FUNCTION_NAME - reverseString
  2. MAIN_CLASS - com.test.cloud.function.CloudFunctionApplication
- Save your function
- Run test, add value as any string and run.