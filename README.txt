This directory contains the following files:

1. creatingBucket.png - Screenshot of completing the step of creating a bucket.
2. uploadingFiles.png - Screenshot of completing the step of uploading files.
3. staticWebsiteHosting.png - Screenshot of completing the step of static website hosting.
4. iamBucketPolicy.png - Screenshot of completing the step of updating the iam bucket policy and making it accessible via www. 
5. cloudFrontDistribution.png - Screenshot of completing the step of cloud front cloud front distribution
6. websiteScreenshotFromCloudFrontURL.png - Screenshot of completing the step of accessing the website using cloud front endpoint.

The static website is accessible via the following endpoint https://d34pmdoiw3a3e6.cloudfront.net/index.html

When you access the website you will notice that the name of the blog has been changed and also a different background image
is added on the homepage.  To achieve this step, I uploaded the new files onto S3 and then had to invalidate the cache on cloud
front so that my changes would be reflected when I access the endpoint.