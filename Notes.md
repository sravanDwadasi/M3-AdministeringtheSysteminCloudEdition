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
## Exercise 2.1: Log in to Infor OS and launch Infor M3 and set user preferences
### Start an Infor M3 program from an open program
1. Press **CTRL+R**. The Search and Start dialog box opens.
2. Type  **Item. Open (MMS001)** in the Search and Start field.
3. what this program basically does is it has the info about the items and their details which we deal with the client.
4. Here we can create, delete or edit the item.

<img width="692" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/7978398e-5a66-4999-ab1b-c1301f268686">

## Exercise 2.2: Create a new menu on the Infor OS homepage
### Create a new menu version
1. Press **CTRL+R**. Type **Menu Version. Open (MNS080)**.
2. Type **[your assigned 009Tnn user ID]** in the Menu vsn filter field.
3. Click **Options > Create**. Panel E displays.
4. Type **[nn_your initials]** menu in the Name field where nn matches the last two digits in your assigned 009Tnn user ID.
5. Click the **Next** button. Panel B displays again and your newly created menu version displays in 
the list.
 ### Create a new function filter
 1. Press **CTRL+R**. Type **Function. Open (MNS110)**.
 2. Type *MNU* in the Function filter field.
 3. Press **Enter**. Search results display.
 4. Click to highlight the row with the description of **-M3 Standard**.
 5. Click **Options > Copy**. Panel C displays.
 6. Type **[your assigned 009Tnn user ID]** in the **Menu version** field.
 7. Click the **Next** button until *panel B1* displays again.
 8. Click to highlight the row associated with **[your assigned 009Tnn user ID]**.
 9. Click **Related > Menu**. The *Menu. Open (MNS111)* program opens. *Panel B1* displays.
 10. Click to highlight the row associated with **MNS095 Company. Open**.
 11. Click **Options > Delete**. The message, **“Confirm deletion of menu option 10”** displays in the bottom-left
     corner of the panel.
 12.  <img width="690" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/fdaf493d-8eaa-4b3b-9011-caef7b78f7e3">
 13. Click the **Next** button. Panel B1 displays again.
 14. Type *35* in the Opt filter field.
 15. Type *MNS405* in the Function filter field. Note: This is the Roles. Open program.
 16. Click **Options > Create**. Panel E displays.
 17. Click the **Next** button. Panel B1 displays.
 18. Clear the Opt field.
 19. Clear the Function field.
 20. Click **Actions > Refresh**. All options display again.
<img width="690" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/57beaf72-9df7-4fcb-af12-b78616d9ff62">

