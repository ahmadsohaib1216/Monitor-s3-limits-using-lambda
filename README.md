# Monitor-s3-limits-using-lambda
To monitor the limits of s3 bucket using lambda

# 100, is the limits of s3 bucket which is default.
 You need to enter this value manully as there is no way to pull that value using AWS API.

# You will need to create a SNS topic and then enter it's ARN in the field 'TargetArn'.

# You can use the CloudWatch 'Rule/events' to run this lambda function once per day and which will invoke the SNS if s3 limits crosses the limit.
