# Deploy Static Website on AWS
The whole project has two major Objectives: 
* Hosting a static website on AWS S3 
* Accelerated access to the static Website content using CloudFront propretory content delivery network for AWS. CloudFronts helps to bring the content closer to the user via edge location caching and this helps  in reducing latency and thus increasing transfer speed 

KEY STEPS FOR PROJECCT COMPLETION - Created an S3 bucket and makes it public so that it can serve the static content over the internet - Uploaded the staic contents to the S3 bucket - Set appropried Iam policies for the bucket and also configure the bucket to servce static content - Configure the CloudFront to cache the static content closer to the users - Tested website in a browser using the unique CloudFront endpoint
