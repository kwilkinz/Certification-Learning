# Technology - Chapter 3 - 33% on the Exam 

## Compute Services 
### --------------- EC2 ----------------
### Elastic Compute Cloud (EC2) 
> * EC2 allows you to rent and manage virtual servers in the cloud. <br/> 
> * EC2 is a foundataional service used for managing your virtual instances. 
> * You get Elastic Compute Power : it can grow and shrink based on the needs or load of the application <br/> 
> * Also Virtual servers in the cloud : compute or processing power in the cloud 

### Region, AZ, Data Center  
> * **Region** a single region contains multiple AZ (availabilty zone) 
> * **AZ** a single AZ contains multiple data centers
> * **Data Center** a single data center contains multiple servers.

### EC2 inside Data Centers
> * **Data Center** contains multiple servers 
> * **Servers within data centers** are the physical compute hardware running in a data center. 
> * **EC2 instances** are the virtual servers running on these physical servers. 

### When do you want to use a EC2? 
> * **Deploy a Database** deploying a database to EC2 gives you full control over the database
> * **Deploy a Web Application** Deploy to multiple AZs to make the web application highly available. 

### EC2 Pricing Options 
> * **On Demand** Fixed price, billed down to the second. Pay for what you use. Use when you have unpredictable workloads. 
> * **Spot** lets you take advantage of unused EC2 capacity. Your request is fufilled only if capacity is available. Cheapest Option. Pay upfront each hour
> * **Reserved Instances** RIs allow you to commit to a specific instance type in a particular Region for 1- 3 years. Pay upfront, to recive a discount on Demand prices. You can pay All, Partial, or No Upfront. All earns the highest discount. 
> * **Dedicated Hosts** allows you to pay for a physical server that is fully dedicated to running your instances. Uses: When you want to bring your own server-bound software license from vendors like Microsoft or Oracle. Bring existing per-socket, per-core, or per-VM software licesnse. 
> * **Saving Plans** allows you to commit to compute usage (measured per hour) for 1 or 3 years. 

### Features of EC2 
> * Elastic Load Balancing : automatically distributes your incoming application traffic accross EC2 instances. 
> * Auto Scaling : adds or replaces EC2 instances across AZ based on need and changing demand. 
<br/> 

### --------------- AWS Lambda ----------------
### AWS Lambda 
> * is a serverless compute service that lets you run code without managing servers. 
> * Your author application code, called function. 
> * scales automatically 
> * Serverless means you dont have to worry about managing servers like EC2

### The Bigger Picture of Lambda 
> * allows developers to focus on core buisness logic for apps they are developing 
> * **Real-time file proessing** sending a file upload to S3 bucket -> Trigger Lambda function -> stores data in DynamoDB
> * **Sending email notifications** 

### Features 
> * Suppports pop programming languages (Go, Powershell, Node, Python, Ruby)
> * You author code using your fav. development enviroment or via console. 
> * Lambda can execute your code in response to events 
> * Lambda functions have 15-min timeout. 

### Pricing 
> * you pay only for the compute time used - time your code begins and terminates 
> * Request Count : counts each time it starts execution. Test function as well 
> * Always free 
