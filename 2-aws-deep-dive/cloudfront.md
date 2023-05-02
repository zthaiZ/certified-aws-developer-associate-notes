# CloudFront: Command Line Interface

* Content Delivery Network (CDN). Provides content quicker to customers by caching it in edge locations. ie customer 1 watches a video from s3. s3 bucket is in Ireland but user is in Sydney. The content flows Ireland -----> Sydney. CloudFront caches it locally near Sydney so the second time its accessed the content flows, CloudFront Sydney -> Sydney.

* Edge locations can be used for write as well as read.

* Objects are cached for ther life of their TTL. TTL can be 0 seconds to 365 days. Default is 24 hours.

* Origin can be S3, EC2, ELB, Route53 and non AWS server ie on-prem

* Restrict viewer access by signed URL or Signed Cookies

* Restrict content based on geo location (whitelist and blacklist)
