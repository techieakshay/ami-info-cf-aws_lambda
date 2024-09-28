# ami-info-cf-aws_lambda
Lambda that basically gives you the ami image id for the provided release version


This aws lambda give the information about the AMI of the pass release version

Payload :: 
 
 {"releaseVersion" : "YOUR AMI RELEASE VERSION"}

 ex 
 { "releaseVersion"  : "al2023-ami"}


Response :: 
    It will output the information about the AMI id.
