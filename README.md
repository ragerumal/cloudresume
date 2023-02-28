# cloudresume
<br />

<p align="center">
  <a href="img/">
    <img src="CloudArchitecture.jfif" alt="Architecture" width="821" height="527">
  </a>
  <h3 align="center">Cloud Resume Challenge</h3>
  <a href="https://raghuerumal.link">Project URL !</a>
<p align="center">

    Website using AWS/Cloud Resume Challenge
I made this <a href="https://raghuerumal.link">website</a> as part of the Cloud Resume Challenge. Below are the resources that I used. This website is hosted on AWS using a serverless architecture. The visitor counter uses a API which was created in the AWS service API gateway. Every time a person visits my website the API gets provoked which then invokes a lambda function that writes the value to a Dynamodb table <a href="https://s9p5m2afg2.execute-api.us-east-1.amazonaws.com/cloud">Get Page Count !</a>. I also used github actions with terraform to create a CI/CD deployment of this website. CloudResumeChallengeWebsite

Resources used:

AWS services:
S3,
Cloudfront,
Route 53,
Lambda,
Api gateway,
Dynamodb.
  
Programming languages:
Python,
Javascript,
HTML.
    <br />
  </p>




