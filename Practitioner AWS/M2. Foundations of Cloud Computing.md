# Foundation
- [Interactive Design 1](https://acloudguru.visme.co/view/mxz10wwn-s01-l00-table-of-contents)

#### What is Cloud Computing? 
> _cloud computing is the delivery of computing services over the internet_
> * Your "cloud" is using aws server farms. 

#### Virtual Machines
> virtualization lets you divide hardware resources on a single **physical** server into smaller units. 

#### Usage
> **your usage is placed on a meter**. You only pay when you access it and only for what you use. 
> * **On Demand** : no long-term commitmments or upfront payments 
> * **Pay as you go** : Pay by the hour or the second for only what you use

#### High Availability 
> Highly available systems are designed to operate continuously without failure for a long time. These systems avoid loss of service by reducing or managing failures. 

#### Elasticity 
> With elasticity, you don't have to plan ahead of time how much capacity you need. You can provision only what you need, and then grow and shrink based on demand. 

#### Agility  
> The cloud gives you increased agility. All services you have access to help you innovate faster, giving you speed to market. 

#### Durability 
> is all about the long term data protection. This means your data will remain intact without corruption. 

#### Infrastructure as a Service (IaaS)
> most basic and building blocks that can be rented and great for web hosting, monthly subscribtion to have a hosting company serve your website. 

#### Software as a Service (SaaS)
> Complete Application : someone that offers a complete application to users <br/>
> Email Provider : your personal email that you access through a web browser is SaaS

#### Platform as a Service (PaaS)
> Used by Developers : software using web-based tools without worrying about the underlying infrastructure <br/> 
> Storefront Website : tools provided to build a storefront application that runs on another company's server. 

#### Cloud Deployment Models 
> **1. Private Cloud** : 
> * aka "on-premises"
> * exists in your internal data center
> * Doesn't offer the advantages of cloud computing <br/>
> **2. Public Cloud**
> * Offered by AWS 
> * You aren't responsible for the physical hardware 
> * Provides all the advantages of Cloud Computing (Elasticity, Agility, Durability, etc) <br/>
> **3. Hybrid Cloud**
> * a combination of Public and private clouds
> * Sample architecture for a hybrid solution (highly sensitive data stays local while the data app runs through AWS) 
> * Web application runs on AWS infrastructure 
> * AWS provides tools so they can talk to each other (directConnect Service) 

#### Regions
> region is a physical region (Ohio, US East location, US West, Africa, South America, Europe) <br/> 
> AWS logically groups its regions into geographical locations. <br/>
> Want your region to be closest to your users

#### Availability Zones 
> consists of one or more physically seperated data centers, each with redundant power, networking, and connectivity, housed in seperate facilities.<br/> 
> Availability Zones = multiple data centers <br/>
> US-EAST-1A, US-EAST-1B 

#### Edge Locations 
> edge locations cache content for fast delivery to your users <br/> 
> Reduce Latency : is the time that passes between a user request and the resulting reponse <br/> 
> High Latency = Bad (long time for website to load) 

#### AWS Management Console 
> allows you to access your AWS account and manage applications running in your account from a web browser 


## CCP Quiz: Foundations 
1. Which of the following are attributes of multiple Availabity Zones in a given Region? 
> AZs within a single Region are isolated but connected to each other through low-latency links. <br/> 
> They are fault toleratnt
<br/> 

2. Which benefit of cloud computing helps you innovate and build faster? 
> Agility <br/> 

3. Which of the following is a true statement about edge locations?
> Edge locations can cache data for your user. <br/> 

4. Which of the following is a geographic area containing multiple Availability Zones (AZs)?
> A **Region** is a physical location that is grouped into a larger geographic area for ease of management. A Region is a collection of AZs. <br/> 

5. Which cloud deployment model allows you to connect public cloud resources to on-premises infrastructure?
> Applications made available through **hybrid** deployments connect cloud resources to on-premises infrastructure and applications. For example, you might have an application that runs in the cloud but accesses data stored in your on-premises data center. <br/> 

6. Which cloud computing model means you are using a complete application or software suite hosted on someone else’s servers?
> **SaaS** provides you access to full applications running on someone else's servers. <br/> 

7. Which of the 6 advantages of cloud computing can often allow you to achieve a lower cost than you would get if you built your own infrastructure?
> You're able to stop spending money running and maintaining data centers. <br/> 
> Increase speed and agility. <br/> 
> Benefit from massive economies of scale <br/> 
> Stop guessing capacity <br/> 
> Trade capital expense for variable expense. <br/> 

8. Which type of expense includes upfront purchases toward fixed assets?
> Capital expenditures (CapEx) are upfront purchases toward fixed assets.

9. Which of the following contains 1 or more physically separated data centers?
> An **Availabilty Zone (AZ)** contains 1 or more data centers that are physically separated.
