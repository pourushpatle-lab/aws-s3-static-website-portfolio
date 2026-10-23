
# AWS S3 Static Website Hosting

## Project Overview

This project demonstrates how to host a static website using
Amazon Simple Storage Service (Amazon S3).

The website is built with HTML and CSS and is hosted directly
from an S3 bucket without provisioning a web server.

## Architecture

Visitor's Browser
        |
        v
Amazon S3 Static Website Hosting
        |
        v
HTML, CSS and Website Assets

## AWS Services Used

- Amazon S3: Stores and serves the website files.
- S3 Static Website Hosting: Configures the bucket to serve
  the index document.
- S3 Bucket Policy: Allows public read-only access to website
  objects for this demonstration.

## Technologies

- HTML5
- CSS3
- Amazon Web Services
- GitHub

## Implementation Steps

1. Created an S3 bucket in the selected AWS Region.
2. Developed the website using HTML and CSS.
3. Uploaded website files to the S3 bucket.
4. Enabled static website hosting with index.html.
5. Configured a bucket policy for public read access.
6. Tested the website endpoint in a browser.


## Screenshots

Add screenshots of:
- S3 bucket configuration
- Uploaded website files
- Static website hosting settings
- Bucket policy
- Live website

## Security Considerations

- Used a dedicated bucket for public website content.
- Granted public read access only, not public write access.
- Did not store credentials or private information in the bucket.
- Recognized that direct S3 website hosting uses HTTP.
- For production hosting, consider CloudFront with a private
  S3 bucket and Origin Access Control (OAC).

## Cost Management

- Monitored AWS billing and usage.
- Used a budget alert.
- Planned to delete AWS resources after testing if no longer needed.

## Learning Outcomes

- Learned how Amazon S3 stores website objects.
- Practised static website hosting.
- Learned how bucket policies control object access.
- Documented a cloud deployment for a GitHub portfolio.

## Future Improvements

- Deploy using AWS CLI or AWS SAM where appropriate.
- Automate deployment with GitHub Actions.
- Add CloudFront for HTTPS and private S3 origin access.
- Add a custom domain if required.
