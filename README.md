# 1. Data Space Introduction

<p align="justify">A data space is a federated, decentralized infrastructure that allows organizations to share data securely and govern its usage according to mutually agreed-upon rules. </p>

<p align="justify">A European data space is an EU-wide initiative to create a secure, interoperable ecosystem for sharing data across different European projects and sectors.
These spaces are designed to allow businesses, organizations, and citizens to share and access data in a way that respects privacy, security, and European laws, while enabling innovation and cross-sector collaboration. 
The goal is to create a trusted, common market/ network for data where organizations retain control over their own data. </p>

<p align="justify">The IDSA initiative introduces the Data Space Protocol that defines the concept, structure, components the principles that should characterize European Data spaces [IDSA documentation](https://internationaldataspaces.org/) .

## 1.1 IDSA protocol core components
<p align="justify">The Data Space structure omprises of two main components: Control Plane and Data Plane, each playing a crucial role in data management and
exchange </p>
<p align="justify">

- <b>Control Plane</b>: Ensures data access and sovereignty management and interoperability at the dataspace level. Its core functionalities are:
  - Cataloguing: To display available data and associated services.
  - Contract Negotiation: Allows data providers to set or negotiate terms of data usage.
  - Data plane configuration and coordination.
  
- <b>Data Plane</b>: Handles the actual data transfer, implementing various communication
protocols like HTTP, to suit specific use cases. This plane manages the practical aspects of
data transfer once policies are negotiated.
</p>
  
## 1.2 IDSA protocol core goals

The list of business goals, concepts and technologies that are involved within the IDSA Data Space
are the:
- Data driven Business ecosystems,
- Data sovereignty as a key capability,
- Data as an economicgood,
- Data exchange and data sharing,
- Meaningful data,
- Industrial Cloud Platforms,
- Big data an AI,
- IoT and industrial IoT,
- Blockchain,
- Federated frameworks for data sharing agreements and terms of use,
- General Data Protection Regulation and
- the Data Economy and Privacy in the connected world.

## 1.3 IDSA key features and principles

The list of key features and principles of a common European data space, are: 
- Trust
- Security & Data Sovereignty
- Ecosystem of Data
- Standardised Interoperability
- Value-Adding Apps
- Data Markets

<b>Following the Data Space Protocol it is possible to deploy private Data Spaces that can be used for private or public projects such as Enpower</b>


# 2. Data Space within Enpower

<p align="justify">Enpower Data Space aims to create a secure and privacy-preserving infrastructure to pool, access, share, process and use data. 
The Enpower Data Space is a clear and practical structure for access to and use of data in a fair, transparent, proportionate 
and/non-discriminatory manner and clear and trustworthy data governance mechanisms as they are defined by European rules and values. 
Data holders/providers have the capability, in the data space, to grant access to or to share certain personal or non-personal data under their control and restrictions. 
Data consumers have the capability, to participate, search, discover and request access to the available data. </p>

<p align="justify">The participants of the Enpower Data Space can participate both as Data providers and Data consumers. 
Additionally the data access policy and rules within Enpower Data Space are implemented through a traditional Subscription system routine that includes the Data exchange Subscription request from the Data Consumer and the Data exchange Subscription response from the Daata Provider. </p>

<b>The Core components that compose the Enpower Data Space ecosystem is the Middleware and the Connector. </b>

## 2.1 Enpower Middleware (IDSA Control Plane)

The Enpower Middleware is a central Graphical User Interface that operates as the Control Plane component that aims to configures and coordinates the Data Space organizations and Connectors and set the ground rules of the Data Access control and restrictions. The core functionalities of the Enpower Middleware are the following:

1.	Configuration (Onboarding) 
2.	Creation of Data Offering (Indexing)
    - Enable Data Offering Interopearbility (Semantic and technical Interopeability)
    - Enable Data Offering Access control (Specific Restrictions and rules)
5.	Data Offering Catalogue (Discovery)
6.	Subscription and access management (Negotiation)
7.	Provisioning and Consuming Data (Data Exchange)

<br/>

Some important definitions about the Enpower Middleware are:

<p align="justify"> <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/63fb679b-1412-4989-9a79-89b2b8b85354" /><b>   Data Offering Service type</b>: Is a predefined contextual frame that characterizises every data exchange (Data Provision & Consumption) within Enpower Middleware. Every Data Offering service type is followed by three attributes (Generic Category > Sub-category > Specific Business Object) that construct a defined «Topic» that describes the content of the data that will be exchanged.</p>

<p align="justify"><img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/63fb679b-1412-4989-9a79-89b2b8b85354" /><b>   Data Offering Service</b> : Is the initial entity that is created by a Data Provider, that defines the Content of the Data that will be shared among the Subscribed (to the Data OFfering) Users. The user selects a Data Offering Service Type among the defined Data Offering Service Type Catalogue that is presented on the Middleware. Every Data Provision is under an «umbrella» of a specific Data Offering service.</p>

<p align="justify"><img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/63fb679b-1412-4989-9a79-89b2b8b85354" /><b>   Subscription</b> : Is an agreement between a Data Provider and one or more Data Consumers regarding a Data Offering Service. A subscription is performed following the sequential steps: </br> </p>

1. Data Offering Service Discovery by Data Consumer
2. Subscription Request
3. Request Response by the Data Provider
4. Upon accepting the Subscription is enabled 
  

<p align="justify"><img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/63fb679b-1412-4989-9a79-89b2b8b85354" /><b>   Data Entity</b> : Is every Data file (assigned in the «umbrella» of a Data Offering Service) that is shared by the Data provider with the Subscribed users of this specific Data offering service</p>

<p align="justify"><img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/63fb679b-1412-4989-9a79-89b2b8b85354" /><b>   API libraries</b> : Are API tools/Commands the can be used as an alternative for the actions that can be performed within the Enpower Middleware. These can be used for the programmatical exploitation of and integration with the Enpower Middleware with an external application. These actions include, the Data Offering Service Discovery (Data Offering Service Catalogue list), Data Offering Service Subscription requests, Data Provision & Consumption etc. </p> 

<br/>

<p align="justify">
<img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/637a0907-246e-4300-be84-1d6136feb794" /><b>   The creation & activation of a user account for the Enpower Middleware is processed upon the request to European Dynamics</b> (please contact dimitrios.apostolidis@eurodyn.com)

<img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/637a0907-246e-4300-be84-1d6136feb794" /><b>   The creation of a new Data offering Service type or the attributes that compose that (Category, Sub-Category, Business Object), that serve a specific use case and is missing from the Enpower Middleware, is processed upon the request to European Dynamics</b> (please contact dimitrios.apostolidis@eurodyn.com)
</p>

The Enpower Middleware can be found in: [Enpower Middleware](https://enpower.eurodyn.com/)

A demo presentation of the functionality of the Enpower Middleware is accessed in: [Enpower Middleware Demo]()

## 2.2 Enpower Connector (IDSA Data Plane)

The Connector is a complex structure composed of several key elements, including one or more
physical or virtual machines and the Connector Services layered on top of it. 
The Connector is the core component of the Enpower Data Space for implementing the concept of Data Space. It serves as the gateway for secure connecting participants and the secure exchange of raw/actual data within the Data Space ecosystem. 
A key benefit of this approach is the decentralization that enables data sovereignty—ensuring organizations retain full control over how their data is accessed and used. 

<b>Simply, Enpower Connector a dockerized piece of software that operates as a node the enables the distributed data exchange within the Data Space on behalf of a user. This dockerized software can be deployed locally in a server from any user that wants to connect to the Enpower Data Space ecosystem. </b>

The Deployment and the Configuration of the Enpower Connector is described in the process below:

# 3. Deployment and Configuration of the Enpower Connector Guide

## 3.1 Prerequisites and Installation

The hardware and operating system prerequisites are:

- A 2-core processor
- 4GB RAM Memory
- 50GB of disk space or more

The software prerequisites include:

- Centos 7 or Windows Server Operative System (OS);
- Docker and docker-compose;

Enpower Connector software and its components will be delivered utilizing the Docker containers of the folder <code style="color : #FF0000">"Enpower Connector Docker Files"</code> of this repository. </br>

<img width="24" height="24" alt="image" src="https://github.com/user-attachments/assets/637a0907-246e-4300-be84-1d6136feb794" />   Additionally to those folders and file within the <code style="color : #FF0000">"Enpower Connector Docker Files"</code> you need to contact and request the mandatory <code style="color : #FF0000">.env</code> file from the European Dynamics. 

</br>

<img width="24" height="24" alt="image" src="https://github.com/user-attachments/assets/637a0907-246e-4300-be84-1d6136feb794" />   For the scope of the following instructions, we suppose you built a server that runs under the local <code style="color : #FF0000">http://my-local-server</code> and your public domain under <code style="color : #FF0000">https://my-public-domain.com</code> .

</br>
</br>

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/ceb41791-d6b1-4f1c-ba2f-eff7f5320d8f" />   First, you need to connect in your local server through the <b>Command Prompt</b>, install Docker (the Docker application has to be downloaded and installed accordingly to the OS of the server to host the deployment) and the needed libraries as shown below:

</br>

For the Docker

```
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg

$ sudo yum-config-manager \
  --add-repo \
  https://download.docker.com/linux/centos/docker-ce.repo

$ sudo yum install docker-ce docker-ce-cli containerd.io
$ sudo systemctl start docker
$ sudo systemctl enable docker
```

Maybe you will need to login to a docker account

```
$ sudo docker login
$ sudo docker compose up -d
```

</br>
For the needed Libraries

```
$ sudo yum update
$ sudo yum install ca-certificates
$ sudo yum install curl
$ sudo yum install -y yum-utils
```





either by <b>Filezilla</b> or through the <b>Command Prompt</b>.


<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/98bfc605-56a2-49a4-9948-f37e490b7a59" />   You need to upload the appropriate files ("Enpower Connector Docker Files" & .env) either directly through <b>Filezilla</b> or through the <b>Command Prompt</b>. 
You can directly upload the folders&files or clone the folders&files of "Enpower Connector Docker Files":

```

```


<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/3c92f612-98f9-4910-8628-28e2185159d7" />a


<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/7e6e96ec-53c5-4ab6-9121-279941d69173" />a


<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/829c5cfe-f828-4129-b245-7bd9af64247a" />a


<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/44b963e4-654d-46c5-bd67-f2736f8100fb" />a


<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/b6e8a377-b67c-4647-a88c-66d9c77f10a4" />a

<img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/637a0907-246e-4300-be84-1d6136feb794" />a


# 4. API libraries
