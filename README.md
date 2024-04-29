<h1>Highly Available and Secure Serverless Web Application on AWS</h1>

<h2>Description</h2>
The project focuses on creating a contemporary web application architecture using AWS cloud services. The project emphasizes the importance of achieving high availability, scalability, and security while keeping operational overhead to a minimum.

<br />Key aspects include:

- Serverless Architecture: the application architecture was designed with serverless computing services like AWS Lambda, which eliminates the hassle of server management and allows for seamless infrastructure scaling based on demand.
- High Availability: Using redundant components and distributed systems across multiple availability zones within the AWS infrastructure, the architecture maximizes availability.
- Scalability: The application is designed to effortlessly handle fluctuating levels of user traffic while maintaining optimal performance. This is made possible by leveraging the flexibility of serverless services and the ability to automatically scale as needed.
- Security: Security is always a top priority. To achieve this, AWS Cognito handles user authentication and authorization, ensuring that only authorized users can acces the system. AWS Key Management Service (KMS) is used to encrypt data, providing an extra layer of protection. In addition, AWS Web Application Firewall (WAF) to safeguard against common web exploits. These measures work together to ensure system security and protect users' data.
- Data Management: Amazon DynamoDB is used to efficiently manage both structured and unstructured data for NoSQL database requirements. Additionally, Amazon S3 is utilized for storing user-uploaded files and static assets.
- Monitoring and Logging: The architecture has strong monitoring and logging solutions using AWS CloudWatch for real-time monitoring and AWS CloudTrail for auditing API calls.

This project aims to showcase the implementation of best practices in building modern web applications on AWS, providing a foundation for highly available, scalable, and secure cloud-native applications. This project is designed to demonstrate how to build modern web applications on AWS using best practices. It serves as a basis for creating cloud-native applications that are highly available, scalable, and secure.

<h2>Architectural Diagram: </h2>

<img width="1008" alt="Screenshot 2024-04-29 at 8 57 37 PM" src="https://github.com/clintonsenaye/Highly-Available-and-Secure-Serverless-Web-Application/assets/57267374/90997bb3-eb88-4678-a3ad-d28e6ef71070">

<h3>Services:</h3>

Frontend:
- Hosted on Amazon S3 for static web hosting.
- Utilize Amazon CloudFront as a content delivery network (CDN).

Backend API:
- AWS Lambda will provide serverless compute for running application code in response to events.
- Amazon API for creating and managing APIs that trigger Lambda functions.
- AWS Cognito for user authentication and authorization.
- AWS Key Management Service (KMS) for managing encryption keys for data at rest and in transit.

Data Storage:
- Amazon DynamoDB will serve as NoSQL database service for storing and retrieving application data with high scalability and performance..
- Amazon S3 for storing user-uploaded files and static assets.

Security:
- AWS Identity and Access Management (IAM) for fine-grained access control.
- AWS Web Application Firewall (WAF) to protect against common web exploits.
- AWS CloudTrail for auditing API calls.

Monitoring and Logging:
- Amazon CloudWatch for monitoring Lambda functions, API Gateway, and other AWS services.
- AWS CloudTrail for logging API calls and monitoring AWS resource usage.

<h3>Data Flow:</h3>


