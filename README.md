Deploy Static Website on AWS

In this project, I deployed a static website to AWS using S3, CloudFront, and IAM.

<!-- TABLE OF CONTENTS -->
## Table of Contents

* index.html - The Index document for the website.
* /img - The background image file for the website.
* /vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
* /css - CSS files for the website.

## Steps
1- I created an S3 bucket:

![alt text](https://github.com/shimaa829/Deploy-Static-Website-On-AWS/blob/master/ScreenShots/1.png)

2- I uploaded the website files to my bucket:

![alt text](https://github.com/shimaa829/Deploy-Static-Website-On-AWS/blob/master/ScreenShots/2.png)

3- Secure it using IAM policies:

![alt text](https://github.com/shimaa829/Deploy-Static-Website-On-AWS/blob/master/ScreenShots/3.png)

4- Configure the bucket for website hosting:

![alt text](https://github.com/shimaa829/Deploy-Static-Website-On-AWS/blob/master/ScreenShots/4.png)

5- Speed up content delivery using AWS’s content distribution network service, CloudFront:

![alt text](https://github.com/shimaa829/Deploy-Static-Website-On-AWS/blob/master/ScreenShots/5.png)

6- I access my website in a browser using the unique S3 endpoint:
CloudFront endpoint URL for my project:
http://d121eq4w97k1r8.cloudfront.net/index.html

![alt text](https://github.com/shimaa829/Deploy-Static-Website-On-AWS/blob/master/ScreenShots/6.png)

