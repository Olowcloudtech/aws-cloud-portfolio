# Static Website Hosting with Amazon S3

This project demonstrates how to host a static website using Amazon S3 static website hosting.

## Architecture
User Browser → Internet → S3 Static Website Endpoint → HTML/CSS/JS files

## AWS Services Used
- Amazon S3
- S3 Static Website Hosting
- Bucket Policy / Public Access Controls

## What I Built
- Created an S3 bucket for website hosting
- Uploaded static website files
- Enabled static website hosting
- Configured permissions to allow public reads
- Validated the site using the S3 website endpoint

## Key Learnings
- How S3 can host a website without servers
- How public access settings and bucket policies affect access
- Basic cloud deployment workflow (upload → test → iterate)

## Future Improvements
- Add CloudFront CDN + HTTPS (ACM)
- Add custom domain with Route 53
- Add CI/CD deployment (GitHub Actions)
