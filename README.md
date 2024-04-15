# Personal Curriculum

## **Personal Details**

**Name:** Luis Filipe Vilela Silva <br>
**Email:** luisvilela54@outlook.com  <br>
**Date of birth:** 31/05/1985  <br>
**Nationality:** Portugal  <br>
**Marital Status:** Maried  <br>


## Summary
A passionate Software Architect, who over the years has specialized in web and platform solutions development, with a special focus on new technologies with a DevOps mindset. 
In life, I love a good time with family, travelling around the world and with a dirty bike always in mind.

## Skills

### **Medium level** <br>
C#, Python, Go, Lua, Git, Cassandra, Redis, ETCD, SQLServer, Kubernetes, Docker, Containerd, Terraform, Nginx, Kong, HAProxy, Consul, ArgoCD, Vault, Helm, Azure Cloud.

### **Beginner level** <br>
Prometheus, Salt, Ansible, Digital Ocean

## Certifications

### **CKS**<br>
The Certified Kubernetes Security Specialist (CKS) program provides assurance that a CKS has the skills, knowledge, and competence on a broad range of best practices for securing container-based applications and Kubernetes platforms during build, deployment and runtime. CKA certification is required to sit for this exam.
<br>
[Credential ID](https://www.credly.com/badges/821dc402-c312-4dd8-8aef-4cf480d0e0f7/public_url)
* Fev2022<br>

### **CKA**<br>
The Certified Kubernetes Administrator (CKA) program has been developed by the Cloud Native Computing Foundation (CNCF), in collaboration with The Linux Foundation, to help expand the Kubernetes ecosystem through standardized training and certification. 
<br>
[Credential ID](https://www.credly.com/badges/39782d11-f39d-4867-a549-67802490b3c2?source=linked_in_profile)<br>
* Nov2021<br>

### **CKAD** <br>
The Certified Kubernetes Application Developer (CKAD) program has been developed by the Cloud Native Computing Foundation (CNCF), in collaboration with The Linux Foundation, to help expand the Kubernetes ecosystem through standardized training and certification. <br>
[Credential ID](https://www.credly.com/badges/37cde8cc-d012-4d6b-9192-4b09a355c65c?source=linked_in_profile)<br>
* Fev2021<br>

### **MCTS: .NET Framework 4, Data Access** <br>
Microsoft
<br>
* Jan2015<br>

### **MS: Programming in C# Specialist** <br>
Microsoft<br>
[Credential ID](https://www.credly.com/badges/97fc2898-9d9f-4629-9718-caabea775758/public_url)<br>
* Jan2015<br>

### **MCPS: Microsoft Certified Professional** <br>
Microsoft<br>
* Mar2014<br>

## Learning
### **Azure Learning**<br>
* LEVEL 9 (975 /34199 XP)<br>

### **Udemy** <br>

## Projects
### **Developers Productivity**<br>
In this project, we get the opportunity to review all Software Development Lifecycle (SDLC) to improve Teams Efficiency, Software quality, best practices and security concerns to support a large scale business.
Start from self-service and Declarative Builds and Tests, supported by standard functional requirements to guarantee all controls like Naming conventions, Code Analysis, security checks and docker signatures.
Testing Strategy we focus in review all test phases, Unit Test, "Mock Test", Contract Test, Integration Test and Smoke Test. Finally, with all of these states, we can build an ephemeral environment to support the daily basis for Eng Teams.
As an Architect for this initiative, I´ve been responsible for designing the long term vision, supporting all decisions with References Architectures and putting hands-on POCs and team support.

* CI Pipeline (PCI-DSS Compliance, Thrust of Origin by Design)
* Build Base and Parent docker images
* Declarative Build and Tests
* Declarative Compliance NFRs (Name Check, Code Analysis, Security Checks)
* Development Handbook ( All about SDLC )
* Testing Strategy (Unit Test, Contract Test, Mock Test, Integration Test ...)
<br>
<br>
**Tech Types:** Kubernetes, Docker, Jenkins, Python, Groovy, Prometheus, Grafana
<br>
<br>
* Fev2020 - present ( 2 yrss )<br>

### **Build Large Scale Platform with Kubernetes**<br>
The main goal of this project was to leverage the platform for the next level. In a fast and Scalable Bussines, the platform should be ready to scale with even more resilience and availability capacity. 
We create a new platform to support our services with three main layers, L1 Security, L2 Traffic Management, L3 Kubernetes Orchestrator in a self-service and declarative mindset. The platform should be prepared for service migration and support all tech and security requirements from Eng. Teams.
As an Architect for this initiative, I´ve been responsible for designing the long term vision, supporting all decisions with References Architectures and putting hands-on POCs and team support.

* CD Pipeline (Gitops, ArgoCD)
* Canary / Blue Green Deployments
* Vertical / Horizontal Scale
* Secret Management
* Network Policies 
* External DNS
* Azure Firewall
* Multi-Cluster Management
* Ship Logging Events
<br>
<br>
**Tech Types:** Kubernetes, Helm, ArgoCD, Docker, Jenkins, Python, Groovy, Go, Consul, Fluentbit, Salt, Terraform, Event Hub, Az Firewall, NSG, Calico, Prometheus, Grafana<br>
<br>
* Fev2020 - present ( 2 yrss ) <br>

### **Build Scalable Traffic Management Platform**<br>
Support a large scale inbound traffic layer where we expose all of our Public API. In a growing business, we need to have a scalable, resilient and heigh available system to support all platform requests. The system was built on top of Azure Scale Sets with two different layers, one for Public API rules (Ingress OpenAPI with Kong) and a second layer responsible for orchestrating the request to a set of Kubernetes clusters that as the applications workloads.
In these layers, we create all the tools and rules to expose Public APIs, protection with authentication (IDP) and safe mechanisms like throttling and rate-limit.
As an Architect for this initiative, I´ve been responsible for designing the long term vision, supporting all decisions with References Architectures and putting hands-on POCs and team support.
* Traffic Shaping/Shadowing
* Api Gateway - Kong / OpenAPI
* Kong Authentication
* Service Discovery / Registry with Consul
* DNS Management
* Network Policies
<br>
<br>
**Tech Types:** Az Scale Sets, Docker, Jenkins, Python, Lua, Salt, Az Firewall, Prometheus, Grafana, Kong, Nginx, HA Proxy<br>
<br>
* Fev2020 - present ( 2 yrss )<br>

### **Build User Data Geo-Distribution Regulation**<br>
This project aims to achieve the new User Data Personally Identifiable Information regulation for a set of countries like (Russia and China).
Since we work in a Geo-distributed system where the User Data flows to all the available regions, we need to support a set of rules based on User Data Regulation. To achieve that goal we create a set of workflows based on the Country of Origin of the User and split the cross-cutting data from Users Data. With Cassandra as a data store we where able to defined the replication strategy and replication factor by country.

* Segregate User Data by Country Law
* Geo-Distribution
* Manage Personal Identifiable Information (PII)
* OpenID AuthN & AuthZ
* Pipes & Filter Pattern
* User Audit
<br>
<br>
**Tech Types:** C#, Rest, CQS, Cassandra, Kafka, Microsoft IIS, Jenkins,ELK<br>
<br>
* Sept2019 - Fev2020 (5 mos )<br>

### **Build Geo-distributed Platform**<br>
The goal of this project is to achieve an active-active multi-datacenter geo-distributed platform. Starting with service foundations, for the data store, we adopt Cassandra to do the data replication across the available zones and replicate the platform events with Kafka replicator.
In this challenge, I was responsible for supporting all the requirements to the Public APIs, creating the foundation to support Cassandra as a Database and guaranteeing the availability of all Public API in 3 Azure Datacenters.
As an Architect for this initiative, I´ve been responsible for designing the long term vision, supporting all decisions with References Architectures and working together with the team to achieve that requirement as soon as possible.

* Geo-redundacy
* Platform Geodistribution Active-Active, multi-zone
* Reliable and High Available Platform
* Cassandra Tunning
* Akamain Configurations including GTM (Global Traffic Manager)
* Kafka Authentication SASL Authentication
* Redis caching layer
* Azure Cloud
* ELK (Logging)
* User Data Obfuscation Framework (PII)
<br>
<br>
**Tech Types:** C#, Rest, CQS, Cassandra, Kafka, Akamai, Redis, Microsoft IIS, Team City<br>
<br>
* Jan2017 - Ago2019 ( 2 yrss 8 mos )<br> 

### **Build Public API Platform ( commerce )**<br>
This project aims to expose a public interface for the commerce platform to support partners use cases and mobile applications. Since the goal had an extremely hard date, we decided to go with a Gateway Pattern with REST architectural constraints supported with current Monolithics and build new services to support new capabilities.
As a Software Developer and Team Lead for this project, I´ve been responsible for designing the long term-vision, supporting all decisions with References Architectures. As a leader, I try to have a motivated team, create a collaborative mindset and support all team needs.
* Convert Monolithic to Service Oriented Architecture
* Build Public API ( Gateway Pattern with REST)
* PCI-DSS Dy Design (CDE Environment)
* CQS / CQRS
* Create service Foundations ( Frameworks Redis, Rest, CQS, Logging, Kafka, Tracing, Metrics)
* Build and Governance of REST Guidelines
* Build and Governance of Logging Guidelines
* ELK (Logging)
<br>
<br>
**Tech Types:** C#, .NET Framework 3.5, MySQL, Redis, MongoDB, MemCache, Elastic Search, CQS, CQRS, Kafka, REST, OpenAPI, Rabbit MQ, PACT.IO, JMeter, New Relic, Kibana<br>
<br>
* Jan2016 - Dez2016 ( 1 yrs )<br>

## Education
### **Master Degree Computer Science** <br>
ISEP - Instituto Superior de Engenharia do Porto<br>
* Sept 2009<br>

## **Professional Experience**

**Sept 2012 - present** <br>
* Farfetch
    * **Principal Software Architect**<br>
    Mar 2021 – Present<br>
    Employment Duration - 11 mos<br>
    * **Senior Software Architect**<br>
    Apr 2018 – Present<br>
    Employment Duration - 3 yrs<br>
    * **Software Architect**<br>
    Jan 2016 – Mar 2018<br>
    Employment Duration - 2 yrs 3 mos<br>
    * **Software Developer**<br>
    Sep 2012 – Jan 2016<br>
    Employment Duration - 3 yrs 5 mos<br>

**May 2011 - Sept 2012** <br>
* Eticadata
    * **Software Developer**<br>
    Employment Duration - 1 yrs 5 mos<br>

**Mar 2009 - May 2011** <br>
* VP Consulting
    * **Software Developer**<br>
    Apr 2018 – Present<br>
    Employment Duration - 2 yrs 3 mos<br>

**Sept 2008 - Mar 2009** <br>
* A&P Consulting
    * **Software Developer**<br>
    Apr 2018 – Present<br>
    Employment Duration - 7 mos<br>
