# Prerequisites
```
<Question>|<Time>|<Difficulty>|<Type>|<Points>|Reference
```

# Introduction
## Brief intro that related to the role

please answer the following questions in point form with three level of answer (beginner, intermediate, expert)
```
# Platform/SRE General Questions
```
## What is change and how you do change
Change refers to making something different from what it is. In software development, it could mean modifying code, updating a system, or implementing a new feature.

Change in ITIL (Information Technology Infrastructure Library) and other IT service management frameworks is a formal process with steps that include: Request for Change (RFC), Change Advisory Board (CAB) review, change scheduling, change implementation, and Post Implementation Review (PIR).

Change should be managed in a controlled manner, including risk assessment, impact analysis, comprehensive testing, and should have a rollback plan in case the change doesn't go as planned.

## What is SLA/SLO/SLI
Beginner:

SLA: Service Level Agreement, a contract between a service provider and a user that defines the level of service expected.
SLO: Service Level Objective, a key element of an SLA where specific aspects of the service - such as availability, performance, capacity, etc. - are agreed upon.
SLI: Service Level Indicator, a measure used to define the SLOs, like error rate, latency, or system uptime.

Intermediate:

SLA: A detailed agreement between a service provider and customer that outlines both the services and the performance standards the provider is obligated to meet.
SLO: Objectives within an SLA that aim to maintain the agreed level of service. SLOs are often used as key performance indicators (KPIs) for service management.
SLI: Metrics that provide evidence of how well the service level is being maintained. They help measure the quality of service and are used to create performance benchmarks.

Expert:

SLA: A legally binding contract or part of a contract where the level of service is formally defined. It may include penalties for not meeting targets and bonuses for exceeding them.
SLO: A specific measurable characteristic of the SLA such as availability, throughput, frequency, response time, or quality. SLOs are designed to support the end-to-end delivery of the service.
SLI: A carefully defined quantitative measure of some aspect of the level of service that is provided. SLIs are used to calculate whether an SLO is being met.

## What is RTO/RPO
Beginner:

RTO: Recovery Time Objective, the targeted duration of time within which a business process must be restored after a disaster.
RPO: Recovery Point Objective, the maximum targeted period in which data might be lost due to a major incident.

Intermediate:

RTO: The maximum acceptable length of time that can elapse before the lack of a business function severely impacts the business. It's a measure of the time taken to recover after receiving a disaster notification.
RPO: The maximum age of files that an organization must recover from backup storage for normal operations to resume if a computer, system, or network goes down as a result of a hardware, program, or communications failure.

Expert:

RTO: A business continuity parameter that represents the point in time following an outage when the operations must be resumed. It's a function of the extent to which the interruption disrupts normal operations and the amount of revenue lost per unit time as a result of the disaster.
RPO: A measure of the ability to recover files by specifying a point in time restore of the backup copy. It's a function of how much data loss is tolerable, measured in time.
```

# Platform/SRE Concept
```
What will happen when you search in google and access to a website thru that
- local browser cache
- local dns cache
- local dns resolver
- local network
- isp dns resolver
- isp network
- google dns resolver
- google network
- google search engine
- HTTPS handshake
- Key exchange
- access a website
- website server
- website server cache
- website server database
- website server network
- website server response



What is TLS/SSL and how it works
- TLS (Transport Layer Security) and its predecessor SSL (Secure Sockets Layer) are cryptographic protocols that provide secure communication over a computer network. They are commonly used to secure web traffic, email, and other data transfers.
- TLS/SSL works by encrypting the data transmitted between two parties, ensuring that it cannot be intercepted or tampered with by unauthorized users. It uses a combination of symmetric and asymmetric encryption algorithms to establish a secure connection and verify the identity of the parties involved.

What is L4/L7 load balancer and how it works
- L4 (Layer 4) and L7 (Layer 7) load balancers are network devices that distribute incoming network traffic across multiple servers to ensure high availability and reliability of applications.
- L4 load balancers operate at the transport layer of the OSI model and use information such as IP addresses and port numbers to make routing decisions.
- L7 load balancers operate at the application layer of the OSI model and can make routing decisions based on application-specific data, such as HTTP headers or cookies.
- Load balancers work by receiving incoming requests, distributing them to backend servers based on a set of rules, monitoring server health, and adjusting traffic distribution as needed to ensure optimal performance and availability.
- Load balancers can also provide features such as SSL termination, caching, and content-based routing to enhance application performance and security.

What is DNS and how it works
- DNS (Domain Name System) is a hierarchical decentralized naming system that translates domain names into IP addresses, allowing users to access websites and other resources using human-readable names.
- DNS works by mapping domain names to IP addresses through a distributed network of DNS servers. When a user enters a domain name in a web browser, the browser queries a DNS resolver to find the corresponding IP address.
- The resolver then queries a series of DNS servers, starting with the root servers, to resolve the domain name to an IP address. The resolved IP address is then used to establish a connection to the desired resource.
- DNS also supports other types of records, such as MX records for email routing, TXT records for domain verification, and SRV records for service discovery.

What is OSI layer, can you name some of it (optional)
- The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a telecommunication or computing system into seven distinct layers.
- The seven layers of the OSI model are: Physical, Data Link, Network, Transport, Session, Presentation, and Application.
- Each layer of the OSI model performs specific functions related to data communication, such as encoding and decoding data, routing packets, establishing connections, and presenting data to the user.

```

# Cloud Security
```
How you secure the cloud workload
How you secure the access of the system access
How you evaluate the cloud security of your platform
How you notify the security incident
```


# Kubernetes
```
what are the basic components of a vanilla kuberenetes cluster
What has to be done in order to run kubernetes and application properly
How you do monitoring in kubernetes
How you do logging in kubernetes
How you do security in kubernetes
What core components you usually use for a kubernetes setup
What command / utils you usually troubleshoot kubernetes

- Bar raiser
What is the minimal unit in kubernetes and how it works ()
What is pod and deployment
How kubernetes networking works
Service Mesh
```

# DevOps
```
How you design the CI/CD pipeline as detail as you can
What components are included in DevOps
What is gitops

- Bar raiser
How you handle devops security
```

# Data Platform
```
Do you know airflow and how it works
Do you know spark and how it works
Do you know kafka and how it works
Do you know metastore and how it works

- Bar raiser
What is your idea implementation of a data platform
``` 

# Coding pratice
```
What is your favorite programming language
What is your favorite framework
What is your favorite design pattern
What is SOLID principle
What is DRY principle
What is KISS principle

How you use Git
```

# Linux / OS
```
What is the difference between linux and windows
What Os Distribution you usually use
What usual command you use

```

# Microservice
```
12 factor app
```

# Closure
```
Any question
```