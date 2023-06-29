# M3: Administering the System in Cloud Edition
## Day-1 (29/06/2023)
### Infor Operating Services (OS) : -
- Infor OS is the technology that powers your entire enterprise, bringing together **Enterprise resource 
planning (ERP)** software (Infor M3, LN, EAM, etc.), for collaboration, artificial intelligence, analytics, 
integration, mobility, and document management in a single platform.
### Infor M3 Cloud Edition (CE) : -
- The Infor M3 CE map is built on a foundation of cloud-delivered, always up-to-date, easy-to-integrate 
micro-vertical suites and cross-industry applications; in-context business intelligence; and an intuitive user 
experience that is mobile and empowers meaningful business collaboration.
- Infor M3 CE delivers **Software as a Service (SaaS)**, offering complete flexibility in operations, technology, 
and scale.
- Infor M3 CE is deployed and provisioned on **Amazon Web Services® (AWS)**, providing you with a secure 
environment and a **low Total Cost of Ownership (TCO)**.
#### Infor M3 CE allows you to transform your business in the following ways : -
- A secure path for the future
- Low TCO
- No more upgrades
- Fast access to new innovations
- Flexibility and scalability
- Security
- Best-in-class resilience
- Openness to support your needs
### Infor M3 CE architecture
Infor M3 has three types of CE architecture: single-tenant (ST), multi-tenant (MT), and hybrid.
### Single-Tenant
Cloud single-tenant architecture uses a single instance of the software and supporting infrastructure to 
serve a single customer. With single tenancy, each customer has their own independent database and 
instance of the software. There is no sharing with other customers.
- Only one system is hosted in a cloud instance.
- Each tenant has their own environment of the software and their own database.
### Multi-Tenant
Cloud multi-tenant architecture uses a single instance of the software and its supporting infrastructure to 
serve multiple customers. Each customer shares the software application and a single database. Each 
tenant’s data is isolated and remains invisible to other tenants. Data is separated and secured logically, 
but no customizations are allowed.
### Hybrid
A hybrid architecture is a deployment of both single-tenant and multi-tenant applications, and the 
customer may also have on-premises applications. Clients including browsers, desktops, handheld devices, and printers are all on-premises, managed by 
the customer, for example : OpenText StreamServe integration is certified but optional. It is not included in 
Infor M3 CE nor hosted by Infor.
### 1. How does Infor M3 CE allow you to transform your business?
- Secure path for the future
- Low TCO
- No more upgrades
- Fast access to new innovations
- Flexibility and scalability
- Security
- Best-in-class resilience
- Openness to support needs
### 2. Describe each unique M3 CE MT customer environment.
Each unique customer environment is known as a tenant. Each tenant gets a unique and isolated segment of the solution – all hosted in the Infor M3 multi-tenant cloud on AWS. Tenants cohabit and share the application server resources but cannot “see” each other. Databases are separate for manageability purposes.
