# Cloud Based-APP development

A cloud-based application is a software solution that runs the processing logic and data storage between two different systems: client-side and server-side.

**TWO APPS**

* APP1: 连接安卓端和服务器
* APP2: 对于安卓端和APP1的状态进行检测和分析



**APP1的主要功能**

Transfer data

* get the request and data from user
* send data to user

Handle data

* handle data with machine learning and other methods



**APP2的主要功能**

Monitor

* Session length、Session interval、Retention rate、MAU/DAU
* App crashes、API latency、 End-to-end application latency、App load per period、Network errors

Analysis

* analyze data above
* optimize/adjust the app1 manully  (or automatically )





## Computation

Amazon EC2

服务器端



## Database

Amazon Relational Database Service (RDS)  MySQL

储存数据（主要是用户数据）



## Storage

Amazon S3

储存图片（主要是人工智能需要的图片）



## Programming & Development

**SDK:**

* AWS SDK for Java (Android app相关)

  The AWS SDK for Java provides a Java API for AWS infrastructure services. Using the SDK, you can build applications on top of Amazon S3, Amazon EC2, Amazon DynamoDB, and more.

* AWS Amplify

  AWS Amplify enables developers to develop and deploy cloud-powered mobile and web apps. The Amplify Framework is a comprehensive set of SDKs, libraries, tools, and documentation for client app development. The Amplify Console provides a continuous delivery and hosting service for web applications.

* Amplify Android (AWS Mobile SDK for Android)

* AWS SDK for C++（一些云端的程序）
* AWS SDK for Python (Boto3) （人工智能可能会用到）
* AWS Command Line Interface

The AWS Command Line Interface (AWS CLI) is a unified tool that provides a consistent interface for interacting with all parts of AWS. 



## Machine Learning

* Amazon Machine Learning

 The powerful algorithms of Amazon Machine Learning create machine learning (ML) models by finding patterns in your existing data. The service uses these models to process new data and generate predictions for your application.

数据库中数据的分析



## Portability

* Amazon Elastic Container Service

Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster of Amazon EC2 instances.

(a container consists of an entire runtime environment: an application, plus all its dependencies, libraries and other binaries, and configuration files needed to run it, bundled into one package. )



## Security

* AWS Secrets Manager

  AWS Secrets Manager helps you to securely encrypt, store, and retrieve credentials for your databases and other services. Instead of hardcoding credentials in your apps, you can make calls to Secrets Manager to retrieve your credentials whenever needed.

保证数据的安全性，对传输的隐私数据进行加密等等

* Amazon AppFlow (Data tansfer)

  Amazon AppFlow is a fully managed API integration service that you use to connect your software as a service (SaaS) applications to AWS services, and securely transfer data. Use Amazon AppFlow flows to manage and automate your data transfers without needing to write code.



## Reference

AWS document：https://docs.aws.amazon.com/

Introduction to cloud: https://www.clariontech.com/blog/cloud-computing-architecture-what-is-front-end-and-back-end

Back-end & Front-end performance: https://techbeacon.com/app-dev-testing/understanding-front-end-vs-back-end-performance-metrics-mobile-apps

16 metrics to ensure mobile app success: https://www.appdynamics.com/media/uploaded-files/1432066155/white-paper-16-metrics-every-mobile-team-should-monitor.pdf

