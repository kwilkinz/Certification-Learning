# 📗 Study Guide for Microsoft Azure Fundamentals exam (AZ-900)
This guide is intended to provide a list of pre-selected materials to help anyone starting in the  cloud computing career and/or discovering Azure be ready to the AZ-900 exam.
*Updated: 12/12/2023*

## 📋 Learning Path from [Microsoft Learn](https://aka.ms/learn) for Exam AZ-900
* [Microsoft Azure Fundamentals: Describe core Azure concepts](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-cloud-concepts/)
* [Microsoft Azure Fundamentals: Describe core Azure services](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-core-azure-services/)
* [Microsoft Azure Fundamentals: Describe core solutions and management tools on Azure](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-core-solutions-management-tools-azure/)
* [Microsoft Azure Fundamentals: Describe general security and network security features](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-general-security-network-security-features/)
* [Microsoft Azure Fundamentals: Describe identity, governance, privacy, and compliance features](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-identity-governance-privacy-compliance-features/)
* [Microsoft Azure Fundamentals: Describe Azure cost management and service level agreements](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-azure-cost-management-service-level-agreements/)

------
## 📋 What is Azure Fundamentals? 
* _Microsoft Azure is a cloud computing platform_
* _Azure also supports running fully virtualized computers managing your custom software solutions._
* _Azure provides cloud-based services like Remote Storage, Database Hosting, and Centralized Account Management._
* _Azure also now offers Artifical Intelligence (AI) and Internet of Things (loT) focused services._

------
### ☁️ Describe Cloud Computing (25-30% of Exam): 
#### Cloud Computing:
* Cloud Computing: is the delivery of computing services over the internet.
* Computing services include Common IT Infrastructure such as virtual machines, storage, databases, and networking.
* Cloud services also offer things like Internet of Things (loT), machine learning (ML), and Artificial Intelligence (AI).
* All Cloud Providers: are compute power and storage_
* **⚡Compute Power:** is how much processing your computer can do. You can remove and add compute power (kinda like ram) as you need it.
      & you only pay for the resouces you use.
* **📦Storage:** is the volume of data you can store on your computer. (think of it as a hard drive). But with coud you can request more
      storage as you need it. 
* Cloud providers mananage the upkeep of the computer so you don't have too.
* [🔗 Reference](https://learn.microsoft.com/en-us/training/modules/describe-cloud-compute/3-what-cloud-compute)
 
-------
### 🤝 Describe the shared responsibilty model: 
#### **Traditional Corporate Datacenter:** 
* company is responsible for maintaining the physical space, ensuring security, and maintaining or replacing the servers if anything happens
* The IT department is responsible for maintaining all the infrastructure and software needed to keep the datacenter up and running.
* Responsible for keeping all systems patched and on the correct version.
 
#### **Shared Responsibility Model:**
* these responsibilities get shared between the cloud provider and the consumer.
* Physical security, power, cooling, and network connectivity are the responsibility of the cloud provider.
* Consumer is responsible for the data and information stored in the cloud. Also access security, (meaning you only give access to those who need it).
  
#### **Provider Always Responsible For:**
* the physical datacenter
* physical network
* hosts
  
#### **Client Always Responsible For:**
* The information and data stored in the cloud
* Devices that are allowed to connect to your cloud (cell phones, computers, and so on)
* The accounts and identities of the people, services, and devices within your organization
 
#### **Depending on the Situation:**
* Provider: if SQL Database cloud provider would be responsible for the database maintence.
* Client: responsible for the data that gets ingested into the database.
* Client: deployed a virtual machine and installed an SQL database on it, you’d be responsible for database patches and updates, as well as maintaining the data and information stored in the database.
* Client: on-premises datacenter, you’re responsible for everything.
* ![image](https://github.com/kwilkinz/Certification-Learning/assets/105250570/dd129d6e-2b4a-4981-b0e6-27066a20b4f8) 
* [🔗 Reference](https://learn.microsoft.com/en-us/training/modules/describe-cloud-compute/4-describe-shared-responsibility-model)

-------
### 🌐 Define cloud models: 
#### **What are the 3 Types of Cloud Models:** 
* Public, Private, and Hybrid

#### **Public:**
* is built, controlled, and maintained by a 3rd party cloud provider.
* Anyone that wants to purchase cloud services can access and use resources.
* the general public availablity is the key difference

#### **Private:**
* its a cloud (delivering IT services over the internet) that's used by a single entity.
* Private cloud provides greater control for companies and its IT departments. However comes with a greater cost.
* Private may be also hosted from your site datacenter. Or hosted in a dedicated datacenter offsite, or even a third-party datacenter.

#### **Hybrid:**
* a hybrid is a computing environment that uses both public and private clouds in an inter-connected environment.
* can be used to allow a private cloud to surge for increased, temporary demand by deploying public cloud resources.
* Hybrid cloud can be used to provide an extra layer of security.
* users can flexibly choose which services to keep in public cloud and which to deploy to their private cloud infrastructure.

#### **Multi-Cloud:**
* multi-cloud environment you deal with two (or more) public cloud providers and manage resources and security in both environments.

#### **Azure Arc:**
* set of technologies that helps manage your cloud environment.
* Arc can help manage your cloud environment, whether its public cloud solely on Azure, a private cloud in your datacenter, a hybrid config, or even a multi-cloud running on multiple cloud providers at once.

#### **Azure VMware Solution:**
* if you’re already established with VMware in a private cloud environment but want to migrate to a public or hybrid cloud.
* lets you run your VMware workloads in Azure with seamless integration and scalability.

* ![image](https://github.com/kwilkinz/Certification-Learning/assets/105250570/1d8d993c-753c-4add-a245-1e9a9eb4d898)
-------

### **Describe the Consumption-based Model:**


-----
### 👤 Identity appropriate use cases for each cloud model: 
#### What are the different types of cloud computing?

#### Describe different cloud services

### Building blocks of cloud services



















#### * Compare cloud pricing model: 

### Describe Azure Architecture and Services (35-40% of Exam):

### Describe Azure Management and Governance (30-35% of Exam):
