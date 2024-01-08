<img width="920" alt="image" src="https://github.com/championel/Host-Static-Website-using-AWS-S3/assets/95048371/38511b7e-720b-45f2-ac1d-1c4a76308005">Hosting a static website on Amazon Web Services (AWS) Simple Storage Service (S3) is a cost-effective and scalable solution. This report outlines the process of hosting a static website on AWS S3 and highlights key features and benefits.
 Amazon S3 is a highly durable and scalable object storage service offered by AWS. It allows users to store and retrieve any amount of data at any time. S3 is commonly used to host static websites due to its simplicity, low cost, and reliability.

Steps to Host a Static Website on AWS S3:
   a. Create an S3 Bucket:
      - Log in to the AWS Management Console.
      - Navigate to the S3 service.
      - Create a new S3 bucket, ensuring the bucket name is unique across AWS.
![image](https://github.com/championel/Host-Static-Website-using-AWS-S3/assets/95048371/39344a91-4a42-42ec-b947-f13c2061c080)

 
   b. Configure the S3 Bucket for Website Hosting:
      - In the S3 bucket properties, enable static website hosting.
      - Specify the index document (e.g., "index.html") and error document (optional).
 ![image](https://github.com/championel/Host-Static-Website-using-AWS-S3/assets/95048371/894bb51d-26ef-4003-b569-907c35bc43d4)

   c. Upload Website Files to S3:
      - Upload your static website files (HTML, CSS, JavaScript, images, etc.) to the S3 bucket using  objects.
 ![image](https://github.com/championel/Host-Static-Website-using-AWS-S3/assets/95048371/23867559-aa90-4549-94d0-6dd2b75d765c)

   d. Set Permissions:
      - Adjust bucket policies and permissions to make the content publicly accessible.
      - Grant the necessary read permissions for anonymous users.
     ![image](https://github.com/championel/Host-Static-Website-using-AWS-S3/assets/95048371/848061c2-a954-4965-a06a-a2206acb8663)

   e. Enable Website Hosting:
      - Access the website endpoint provided by AWS once hosting is enabled.
      - Verify that the website is accessible through the generated URL.
 ![image](https://github.com/championel/Host-Static-Website-using-AWS-S3/assets/95048371/9cc0cd3d-e6b6-433e-b788-a17a4790dcb4)

Key Features and Benefits:
   a. Scalability:
      - S3 can handle any amount of traffic, making it suitable for websites with varying levels of demand.

   b. Cost-Effective:
      - S3's pay-as-you-go pricing model ensures that users only pay for the storage and bandwidth they use.

   c. Reliability:
      - S3 provides high durability and availability, ensuring that your website remains accessible with minimal downtime.

   d. Easy Configuration:
      - Configuring S3 for website hosting is straightforward, making it an accessible solution for users with varying levels of technical expertise.

Conclusion:
   Hosting a static website on AWS S3 offers a reliable, cost-effective, and scalable solution. The straightforward setup process and robust features make it an ideal choice for businesses and individuals looking to deploy static content with minimal hassle.

References:
   - AWS Documentation on S3: [https://docs.aws.amazon.com/s3](https://docs.aws.amazon.com/s3)

