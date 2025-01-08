<h1>Host a Website on Amazon S3</h1>
 
<h2>What is Amazon S3</h2>
Amazon Simple Storage Service (S3) is Amazon Web Services' scalable object storage service designed to store and retrieve large amounts of data. It's useful to a wide range of industries due to it's reliability, flexibility and cost-efficiency.
<br />


<h2>AWS Services Used</h2>

- <b>Amazon Simple Storage Service (S3)</b> 

<h2>How I used Amazon S3 in this project</h2>

- <b>I used Amazon S3 to store website objects that enabled me to host a website online publicly</b>

<h2>Project Walk-through:</h2>

<h2>Setting up an S3 bucket</h2>

- <b>Creating an S3 bucket took me 3 minutes. The region I selected for my S3 bucket was Europe(London) because it's close to home :-) S3 bucket names are globally unique. This means that each bucket name must be one-of-a-kind across all AWS accounts and regions within a partition.</b> 

<img src="https://i.imgur.com/n8YUDR0.png"/>
<br />
<h2>Upload Website Files to S3</h2>

- <b>I uploaded two files to my S3 bucket, they were; index.html and imageassets.zip. Both files are necessary for this project as the html file relates to the structure/setup of the website and the zip file contains images which are the content to be displayed on/within the website</b>

<img src="https://i.imgur.com/AknckWq.png"/>
<br />
<h2>Static Website Hosting on S3</h2>

- <b>Website hosting means storing a website's files, objects, applications on a server and making the website accessible to the public on the internet. To enable website hosting with my S3 bucket I edited Static website hosting and set to 'Enabled' in my S3 bucket properties. ACL's have been enabled for the purpose of this project. An ACL (Access Control List) in Amazon S3 is a control mechanism that allows you to manage permissions for your S3 bucket and objects.</b>

<img src="https://i.imgur.com/QpU7zHm.png"/>
<br />
<h2>Bucket Endpoints</h2>

- <b>Once static website is enabled, S3 produces a bucket endpoint URL which is the location on the internet that allows public access. When I first visited the bucket endpoint URL I observed/received an access denited 403 forbidden exception message. The reason for this error was due to my objects in my S3 bucket being set to private (by default) when I initially
 uploaded them.</b>

<img src="https://i.imgur.com/8vVGSHn.png"/>
<br />

- <b>To resolve the connection error, I selected the objects in my S3 bucket, went into 'Actions' drop down menu and clicked 'Make public using ACL'. Confirmed this action by selecting 'Make public' and my objects were updated to allow public read access.
- SUCCESSFUL Website hosted using Amazon S3!</b>

<img src="https://i.imgur.com/XpZdCiG.png"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
