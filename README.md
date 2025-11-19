# 1. Data Space Introduction

<p align="justify">A data space is a federated, decentralized infrastructure that allows organizations to share data securely and govern its usage according to mutually agreed-upon rules. </p>

<p align="justify">A European data space is an EU-wide initiative to create a secure, interoperable ecosystem for sharing data across different European projects and sectors.
These spaces are designed to allow businesses, organizations, and citizens to share and access data in a way that respects privacy, security, and European laws, while enabling innovation and cross-sector collaboration. 
The goal is to create a trusted, common market/ network for data where organizations retain control over their own data. </p>

The IDSA initiative introduces the Data Space Protocol that defines the concept, structure, components the principles that should characterize European Data spaces : [IDSA documentation](https://internationaldataspaces.org/) 

</br>

## 1.1 IDSA protocol core components
<p align="justify">The Data Space structure omprises of two main components: Control Plane and Data Plane, each playing a crucial role in data management and
exchange </p>
<p align="justify">

- <b>Control Plane</b>: Ensures data access and sovereignty management and interoperability at the dataspace level. Its core functionalities are:
  - Cataloguing: To display available data and associated services.
  - Contract Negotiation: Allows data providers to set or negotiate terms of data usage.
  - Data plane configuration and coordination.
  
- <p align="justify"><b>Data Plane</b>: Handles the actual data transfer, implementing various communication protocols like HTTP, to suit specific use cases. This plane manages the practical aspects of data transfer once policies are negotiated.</p>

</br>

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
</br>

## 1.3 IDSA key features and principles

The list of key features and principles of a common European data space, are: 
- Trust
- Security & Data Sovereignty
- Ecosystem of Data
- Standardised Interoperability
- Value-Adding Apps
- Data Markets

<b>Following the Data Space Protocol it is possible to deploy private Data Spaces that can be used for private or public projects such as Enpower</b>

</br>
</br>

# 2. Data Space within Enpower

<p align="justify">Enpower Data Space aims to create a secure and privacy-preserving infrastructure to pool, access, share, process and use data. 
The Enpower Data Space is a clear and practical structure for access to and use of data in a fair, transparent, proportionate 
and/non-discriminatory manner and clear and trustworthy data governance mechanisms as they are defined by European rules and values. 
Data holders/providers have the capability, in the data space, to grant access to or to share certain personal or non-personal data under their control and restrictions. 
Data consumers have the capability, to participate, search, discover and request access to the available data. </p>

<p align="justify">The participants of the Enpower Data Space can participate both as Data providers and Data consumers. 
Additionally the data access policy and rules within Enpower Data Space are implemented through a traditional Subscription system routine that includes the Data exchange Subscription request from the Data Consumer and the Data exchange Subscription response from the Daata Provider. </p>

<b>The Core components that compose the Enpower Data Space ecosystem is the Middleware and the Connector. </b>

</br>

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

A demo presentation of the functionality of the Enpower Middleware is accessed in: [Enpower Middleware Demo](https://epuntuagr.sharepoint.com/:f:/r/sites/ENPOWERconsortium/Document%20Library/4-Other%20Material/TRUE%20Connector%20Short%20Demo%20of%20Installation%20%26%20Walkthrough?csf=1&web=1&e=KgwXdo)

</br>

## 2.2 Enpower Connector (IDSA Data Plane)

<p align="justify">The Connector is a complex structure composed of several key elements, including one or more
physical or virtual machines and the Connector Services layered on top of it. 
The Connector is the core component of the Enpower Data Space for implementing the concept of Data Space. It serves as the gateway for secure connecting participants and the secure exchange of raw/actual data within the Data Space ecosystem. 
A key benefit of this approach is the decentralization that enables data sovereignty—ensuring organizations retain full control over how their data is accessed and used. 

<b>Simply, Enpower Connector a dockerized piece of software that operates as a node the enables the distributed data exchange within the Data Space on behalf of a user. This dockerized software can be deployed locally in a server from any user that wants to connect to the Enpower Data Space ecosystem. </b>

The Deployment and the Configuration of the Enpower Connector is described in the process below:
</p>

</br>
</br>

# 3. Deployment and Configuration of the Enpower Connector Guide

## 3.1 Prerequisites 

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

## 3.2 Deployment of the Enpower Connector

<img width="24" height="24" alt="image" src="https://github.com/user-attachments/assets/637a0907-246e-4300-be84-1d6136feb794" />   For the scope of the following instructions, we suppose you built a server that runs under the local <code style="color : #FF0000">http://my-local-server</code> and your public domain under <code style="color : #FF0000">https://my-public-domain.com</code> .

</br>

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/ceb41791-d6b1-4f1c-ba2f-eff7f5320d8f" /> You need to upload the appropriate files ("Enpower Connector Docker Files" & .env) either directly through <b>Filezilla</b> or through the <b>Command Prompt</b>. 
You can directly upload the folders&files or clone the folders&files of "Enpower Connector Docker Files":

```
cd /enpower-connector/
git clone https://github.com/Enpower-project/Enpower-Data-Space-Connector-Deployment-and-Configuration-Guide.git
cd /enpower-connector/Enpower Connector Docker Files
```

<img width="24" height="24" alt="image" src="https://github.com/user-attachments/assets/637a0907-246e-4300-be84-1d6136feb794" />   In this stage you need to make sure to put the <code style="color : #FF0000">.env</code> file (from the European Dynamics) in that folder. 

</br>

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/98bfc605-56a2-49a4-9948-f37e490b7a59" />   You need to connect in your local server through the <b>Command Prompt</b>, install Docker (the Docker application has to be downloaded and installed accordingly to the OS of the server to host the deployment) and the needed libraries as shown below:

For the needed Libraries

```
$ sudo yum update
$ sudo yum install ca-certificates
$ sudo yum install curl
$ sudo yum install -y yum-utils
```

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

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/4561eec8-c259-4404-8e81-4c2dbecf6707" /> Completing this step you are an inactive part of the Enpower Data Space. In order to be an active part of the Data space that can exchange data with the other users, you should define the appropriate ports of the Connector and register them through the Middleware to the Data Space. 

The next steps are responsible to configure the deployed Connector, in a way that will be able to communicate with the rest Connectors and will be integrated in the Enpower Middleware.

</br>

## 3.3 Configuration of the Connector

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/488642d8-bfea-4559-ab01-982a1881d45d" /> This step aims to open the appropriate ports in order to make the connector able to reach and be reached by the other connectors in order to share data. Specifically you need to define and expose (make https:// some of them) following URLs:

</br>

* <b>Local API:</b>

Data App Must Be Publicly Exposed In A Static Ip Via Https, before saved on the connection settings. This happens because Data App is served as an endpoint for peer to peer file transfer between you and other Enpower users. For the Local API URL, you should expose port <code style="color : #FF0000">:30001</code> of the local server to an https domain. For example, I would expose it as below:

<code style="color : #FF0000">https://enpower-localapi.my-public-domain.com</code> ➡️ <code style="color : #FF0000">http://my-local-server.com:30001
</code>

It is very important to expose this port to an https domain, using your F5 configuration or a reverse proxy.

</br>

* <b>ECC URL:</b>

Ecc Url Must Be Publicly Exposed In A Static Ip Via Https, before saved on the connection settings. This happens because Ecc Url is served as an endpoint for peer to peer file transfer between you and other Enpower users. For the ECC URL, you should expose port <code style="color : #FF0000">:8889</code> of the local server to an https domain. For example you can expose it as below:

<code style="color : #FF0000">https://enpower-ecc.my-public-domain.com</code>  ➡️ <code style="color : #FF0000">http://my-local-server.com:8889</code>

It is very important to expose this port to an https domain, using your F5 configuration or a reverse proxy. 

</br>

* <b>Broker Url:</b>

You do not need to expose this. You just need to use on the Middleware UI, this local URL:  <code style="color : #FF0000">http://my-local-server.com:1026</code>

</br>

* <b>Data APP:</b>

You do not need to expose this. You just need to use on the Middleware UI, this local URL:  <code style="color : #FF0000">https://be-dataapp-provider:8083</code>

</br>
</br>

Please ensure that:

1. Each URL is correctly mapped through your F5 or reverse proxy.
2. Regarding the URLs that need to be exposed, you can use NGINX. If this does not work please make a question to your IT responsible for networks.
3. All public URLs use HTTPS for secure external access.
4. The local ports (8889, 1026, 30001) are exposed from your Docker containers and reachable by the proxy.
5. DNS entries for your public domains are properly configured to route traffic to your exposed endpoints.

If you use any different domain naming conventions or internal network structures, simply maintain the same logical mapping between your local URLs and public URLs.

</br>

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/0f593396-f1d0-463e-b570-7a991a55af61" /> In this stage you should request from ED the creation of users and the provision of the corresponding credentials.

</br>

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/9e3b8c52-916d-49f7-aaa3-185665120868" /> After that you need to Log In to the Middleware and we recommend you to navigate to its functionality.

<img width="859" height="458" alt="image" src="https://github.com/user-attachments/assets/a8aac87d-cb99-438f-85ce-8528519f1d81" />

</br>
</br>

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/81547cb2-3aea-48d5-83a2-15affd6fc9e8" /> The final step of the configuration if to set the Connector settings within the Enpower Middleware's "Connector Settings" page, in order to be configured within the Data space as shown below:

</br>

* Local API   : You need to use on the Middleware UI, this URL : https://enpower-localapi.my-public-domain.com/api
* ECC URL     : You need to use on the Middleware UI, this URL : https://enpower-ecc.my-public-domain.com/data
* Broker URL  : You just need to use on the Middleware UI, this local URL:  http://my-local-server.com:1026
* Data APP    : You just need to use on the Middleware UI, this local URL:  https://be-dataapp-provider:8083

<img width="959" height="603" alt="Connectors Settings_" src="https://github.com/user-attachments/assets/c6b322e5-6e59-4c4b-9158-23a642393f3d" />

</br>
</br>
</br>

# 4. API libraries

<p align="justify">The API tools/Commands can be used as an alternative for the actions that can be performed within the Enpower Middleware. These can be used for the programmatical exploitation of and integration with the Enpower Middleware with an external application. </p>

The user can have access in the API tools through the URL:

<code style="color : #FF0000">http://my-local-server.com</code> <code style="color : #FF0000">:30001/api/swagger-ui/index.html?configUrl=/api/v3/api-docs/swagger-config#/</code>
  
<p align="justify">The functionalities that can be executed through the API libraries include, the user Log In & Authorization, the owned Data Offering List, Data Provision & Data Consumption, as shown in the following image. Some extra functionalities are he Data Offering Service Discovery (Data Offering Service Catalogue list), Data Offering Service Subscription requests and Data Offering Service Subscription responses.</p>

</br>
</br>
<img width="1901" height="1145" alt="Swagger finished" src="https://github.com/user-attachments/assets/7bb13e02-a27c-44ed-b19b-13adb65be814" />

</br>
</br>

## 4.1 User Login & Authorization
<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/e48c87da-9ab3-4fce-8ebb-e038ba1bf409" />    In this stage the user posts its credentials and the system returns back an Authorization token.

</br>

<img width="1352" height="637" alt="Log In   Authenticate Parameters" src="https://github.com/user-attachments/assets/ac5ad3bb-9145-44a9-8de7-ad6d0a2c6d87" />

</br>

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/8e659562-7f5e-450f-b93d-6fc2082aef11" />    The user copies the Token within the "Access token" field

</br>

<img width="1582" height="597" alt="image" src="https://github.com/user-attachments/assets/4fc26810-630a-44ff-b0b1-f7ecf3003c5c" />

</br>

and proceeds to the Authorization as shown below:

</br>

<img width="1360" height="702" alt="Authorize" src="https://github.com/user-attachments/assets/ceb48926-73d5-419b-8c59-4eed0adb34a6" />

</br>
</br>

## 4.2 My Data Offerings List 

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/13bda268-b86f-49bc-bbf5-0ec13952c18f" />The user can retrieve the list of the Data Offerings services that have created through the corresponding API:

</br>

<img width="1371" height="622" alt="My offered services" src="https://github.com/user-attachments/assets/b1ad4ac5-19e1-48f4-8a43-9094b6b720c8" />

</br>

The user can use the ID of a Dta Offering service in order to Provide Data to all the Subsribed users to it.

</br>
</br>

## 4.3 Data Provide 

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/a56b5d31-3324-463f-bb35-452c8986f8d9" />In order to provide data the user should have the ID of its Data Offering that desires to post data about. This can be done or through its Data Offering list from the API calls either through the Middleware UI as shown below.

</br>



</br>

## 4.4 Data Consume

<img width="28" height="28" alt="image" src="https://github.com/user-attachments/assets/f9995fb4-ae88-44d1-9f5c-76f38d55b87a" />

</br>
