# AWS-Static-Website-Deployment
A Step-by-Step Implementation on how to deploy a simple static website using AWS services
***Hosting the Static Website
A step-by-step look at how I set up my static website using AWS S3 and CloudFront:
Step 1: Create an S3 Bucket
I started by creating an S3 bucket, the foundation for my static website. To host the static site, I configured the following settings:
·      Log in: AWS Management Console.
·      Navigate: To S3 and create a new bucket
·      Bucket name: I chose a globally unique name for my bucket.
·      Static website hosting: I enabled static website hosting.

Step 2: Upload Website Files
With the bucket created, I uploaded all my static website files (HTML, CSS, and JavaScript) directly into the S3 bucket.

Step 3: Create Cloud CloudFront Distribution
To enhance my website’s performance and reliability, I created a CloudFront distribution:
Go to the CloudFront console and create a new distribution.
Origin: I selected the S3 bucket as the origin for my CloudFront distribution

Step 4: Set Permissions
Allowing read access to CloudFront origin access

Step 5: Set Up Cloudwatch Metrics
To enhance my website’s performance and reliability.
Cloudfront: To help track CloudFront’s activities, I selected the CloudFront metrics.

Step 6: Test the Website
After setting up everything, I tested my website using the CloudFront distribution domain name, which worked flawlessly. The content was served globally, fast, and securely.

**What I Learned Along the Way
The experience of hosting my static website on AWS using S3 and CloudFront was great. It helped me:
1. Understand how AWS S3, CloudFront, and other services work together to deliver fast, reliable, and scalable websites.
2. To understand how you can scale automatically, reduce latency, and distribute content globally without managing physical servers is a game-changer for developers.
3. The few hurdles on this journey taught me more about cloud architecture and paying attention to detail.

Conclusion
This milestone has been an exciting one in my journey in the cloud. I look forward to exploring more AWS services, building simpler systems to complex systems, and expanding my knowledge of cloud-based technologies.
Let’s connect and share ideas.

