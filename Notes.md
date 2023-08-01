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
#### Menu version is nothing but it is the place we record the changes in homepage.
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

###  Apply the new menu version
 1. Type User. Open in the M3 Menu widget Search field. Search results display.
 2. Click the User. Open option. The User. Open (MNS150) program opens. Panel B1 displays.
 3. Click to highlight the row associated with [SRADWA49].
 4. Click Options > Change. Panel E displays.
 5. Click the Next button. Panel F displays.
 6. Type [SRADWA49] in the Menu version field.
 7. Click the Next button. Panel B1 displays again.
 8. Click the Close (X) button to close the User. Open (MNS150) program. The Infor M3 Training
    homepage displays.
 9. Note: Even though you have changed the menu display, you must log out 
    and sign back in to Infor OS to see the changes.
 10. Complete the following to log out: <br>
    a. Click the User Menu icon. A list displays. <br>
    b. Click the Sign out list item. The message, “Sign-out Successful” displays. <br>
    c. Click Close (X) to close the internet browser tab. The Training desktop displays. <br>
 11. Follow the steps in Exercise 2.1 Part 1 to log back in to Infor OS. The Infor M3 Training
     homepage displays.
 12. Review the displayed M3 Menu. It matches the sequence indicated in step 20 of part 2.
 13. <img width="222" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/080c39e8-b7ed-43ce-bfb9-160a3b0a8013">

 14. Complete the following: <br>
     a. Click the magnifying glass on the M3 Menu widget to display the Search field.<br>
     b. Type Company. Open (MNS095) in the M3 Menu widget Search field. <br>
     c. The menu is now updated and Company. Open no longer displays in the menu search 
     results as an option. <br>

### Revert to default menu version
 1. Type User. Open in the M3 Menu widget Search field. Results display.
 2. Click the User. Open option. The User. Open (MNS150) program opens. Panel B1 displays.
 3. Click to highlight the row associated with [SRADWA49] .
 4. Click Options > Change. Panel E displays.
 5. Click the Next button. Panel F displays.
 6. Click the Menu version arrow. The Browse window opens.
 7. Clear the Menu vsn positioning field.
 8. Press Enter.
 9. Click to highlight the row associated with M3 Standard in the Description field and a blank Menu 
    vsn field.
 10. Click the Select button. Panel F displays again. Note: M3 Standard does not display to the right 
    of the Menu version field yet.
 11. Click the Next button. Panel B1 displays again.
 12. Double-click the row associated with [SRADWA49] . Panel E displays.
 13. Click the Next button. Panel F displays, and M3 Standard displays to the right of the Menu 
     version field.
 14. Click the Next button. Panel B1 displays again.
 15. Click the Close (X) button to close the User.Open (MNS150) program. The Infor M3 Training
     homepage displays.
 16. Complete the following to log out: <br>
     a. Click the User Menu icon. A list displays. <br>
     b. Click the Sign out list item. The message, “Sign-out Successful” displays. <br>
     c. Click Close (X) to close the internet browser tab. The Training desktop displays. <br>
 17. Follow the steps in Exercise 2.1 Part 1 to log back in to Infor OS. The Infor M3 Training
     homepage displays.
 18. Complete the following: <br>
     a. Click the magnifying glass on the M3 Menu widget to display the Search field. <br>
     b. Type Company. Open in the M3 Menu widget Search field. <br>
     c. The menu is now updated and Company. Open displays in the menu search results again <br>
<img width="225" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/0918baa3-17f6-4a11-93e4-246709fc541d">

### User management
- **IFS** is the internal system of record for users in the system. This is where users are added and updated and where security roles are configured. IFS is responsible for storing user attributes that are retrieved as claims when a session is constructed during sign-in. Federated security and single sign on (SSO) are also configured in the IFS user interface.
- M3 CE Core is the central part of the ERP system, the application where the business logic resides.
- M3 CE Core maintains a mapping between IFS users and M3 CE Core users: each M3 CE Core user is mapped to the corresponding user in IFS.
- User information is synchronized between M3 CE Core and IFS through BODs.
- Because Infor Ming.le is the system of record for users, you must set up users in Infor Ming.le. 
#### You can perform the following user management tasks in Infor Ming.le:
- Create users, including manual import of users
- Update users
- Delete or deactivate users
- Reset passwords
- Monitor recent user activity and mobile sessions
##### When a new user is created in Infor Ming.le, the Sync.SecurityUserMaster BOD is published.

## Demo 2.3: Create a new user in IFS
###  Add the user in IFS
 1. Click the User Menu icon. A menu displays.
 2. Click the User Management menu item. The Users panel of Infor Federation Services tool opens.
 3. Click the Add new item icon (screenshot below). The Add Users window opens.
 4. Click to select the check box in the left-most cell.
 5. Type [your first initial] in the First Name field.
 6. Type [your last name initial_nn] in the Last Name field where nn represents the last two digits in 
    your assigned 009Tnn login.
 7. Type A_[your 009Tnn assigned user ID] in the User Name field. For example: If your assigned 
    user ID is 300T04, type A_300T04 in the User Name field.
 8. Type [the instructor’s email address] in the Email Address field.
 9. Verify the Send Invitation check box is selected.
 10. Click the Save button. A message, “Successfully Saved Your data has been updated.” displays in the upper right corner and the Users panel displays again. An email has been immediately sent to the email address (the instructor, in this case) and provides a link to verify the account. If the instructor clicks the link, they will be invited to verify the account and create a password. This is based on a system option. In some cases, companies choose not to send this initial email because there may be more setup required.
 11. Complete the following to populate the record with user specific data: <br>
     a. Type [your first initial] in the Search field. <br>
     b. Press Enter. <br>
     c. Locate the record added in step 10. <br>
     d. Click the User Details button in the second column. A panel opens and displays the 
        record the instructor added. <br>
     e. Verify the Details tab is selected. <br>
     f. Review the information displayed on the Details tab. <br>
     g. Type [exactly the same text as in the User Name field which is A_009Tnn] in the IFS IONPerson ID field. <br>
     h. Type B_[your assigned 009Tnn user ID] in the M3 User Alias field. <br>
        Note: Per company specifics, the additional fields can be populated based on how you 
        manage your employee information such as Title, Department, Manager, etc. <br>
     i. Click the Save Item icon. A message, “Successfully Saved Your data has been updated.” 
        displays in the upper right corner. <br>
 12. Complete the following to add associated accounting entities: <br>
     a. Click the Accounting Entities tab. There are no accounting entities assigned to the newly 
        created user. <br>
     b. Click the Add new item icon. The Select Accounting Entities window opens. <br>
     c. Click the Records per page drop-down arrow in the lower right corner. A list displays. <br>
     d. Click the 25 list item to display 25 records per page. <br>
     e. Click to select the check box associated with the following accounting entities: <br>
        - 009_ 
        - 009_AAA
        - 009_BBB
        - 009_ZZZ
     f. Click the Add & Close button. The Accounting Entities tab displays again with the newly 
        added accounting entities. <br>
     g. Click the Save Item icon. A message, “Successfully Saved Your data has been updated.” 
        displays in the upper right corner. <br>
 13. Complete the following to add the required security role:
     a. Click the Security Roles tab. <br>
     b. Click the Add new item button. <br>
     c. Type M3UI in the Search field. <br>
     d. Press Enter. Results display. <br>
     e. Click the check box preceding M3UI-User. <br>
     f. Click the Add & Close button. <br>
     g. Click the Save icon. A message, “Successfully Saved Your data has been updated.” 
        displays in the upper right corner. <br>
 14. Click the Back Arrow icon (screenshot below). The main Users panel displays.

## ION Desk
- The ION Desk is nothing but it acts as an interface between the things like M3 or other facilities and distribution things which is used to connect things.
- **EXAMPLE: -** start button -> Orderfull (Purchase order) -> (XML/XD) File -> ION -> Conditions -> (XML/XD) File -> M3. This can be done even in reverse.
- The above example is called the **Work Flow**.
- **Orderfull** works like tracking. Same as how Amazon order tracking works for example.
  
###  Access the ION Desk to review the entry
 1. Click the App Menu icon. A menu displays.
 2. Click the ION Desk menu item. The Status Overview panel displays.
 3. Click the Menu icon (screenshot below). A list displays.
 4. Click the OneView list item. The OneView panel displays. Note: Expand the Filters section if not 
    expanded.
 5. Click the Search button in the Filters section. Link options display under the Documents
    heading.
 6. Click the Sync.SecurityUserMaster link. Several documents and messages display and the 
    screen displays a list on the left and a list on the right.
 7. Click [the last event noted by the timestamp] in the list of messages on the left side.
 8. Click the paper icon (shown above). The Document Details display and if no errors exist, you 
    may proceed.
<img width="451" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/17308f24-2dc7-45f7-b53f-7ee626890ddf">
 9. The paper symbol in this is the XML/XD format file of the Outbound schema.
<img width="242" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/6996aea0-c6c2-459d-9546-9c39cc6e5f8c">

### Review the user in the Infor M3 application, and User Management program
 1. Complete the following back in the Infor M3 application: <br>
    a. Click the Infor icon. The Infor M3 Training homepage displays. <br>
    b. Click the M3 Menu widget’s magnifying glass icon to display the Search field. <br>
    c. Type User. Open in the M3 Menu widget Search field. Results display. <br>
    d. Click the User. Open link. The User. Open (MNS150) program opens. Panel B1 displays. <br>
    e. Collapse the Context app pane if currently expanded. <br>
    f. Type B_ in the User field. <br>
    g. Click the Apply button. <br>
    h. Click to highlight the row associated with B_[your assigned 009Tnn user ID] . <br>
    i. Click Options > Change. Panel E displays. The User status is 20-Active. <br>
    j. Click the Next button until panel B1 displays again. <br>
    
 3. Complete the following in User Management: <br>
    a. Click the User Menu icon. A menu displays. <br>
    b. Click the User Management menu item. <br>
    c. Click to select the check box associated with A_[your assigned 009Tnn user ID] . <br>
    d. Click the Action drop-down arrow. A menu displays. <br>
    e. Click the Disable menu item. The message, “Are you sure that you would like to disable 1 
    users?” displays. <br>
    f. Click the Yes button. <br>
    <img width="217" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/f476ca41-c48b-4b8c-a9f7-aa3919841a78"> <br>
### Review the result in the ION Desk and in the Infor M3 User. Open program
 1. Complete the following to go back to ION Desk: <br>
    a. Click the App Menu icon. A menu displays. <br>
    b. Click the ION Desk menu item. The OneView pane displays again. <br>
    c. If not in the One View pane, do the following: <br>
       - Click the Menu icon. A list displays.
       - Click the OneView list item. The OneView pane displays 
       - Click the Search button. Several document links display. <br>
    d. Click the Sync.SecurityUserMaster link twice. The messages on left refresh. <br>
    e. Click the scroll bar of the messages on the left.and scroll down. <br>
    f. Click the [last message] in the list on the left. <br>
    g. Double-click the Page icon. The Message Content window opens. <br>
    h. Press Ctrl + F. The Search for field opens. <br>
    i. Type disabled in the Search field. The details of your previous action to disable the new user 
       you created are highlighted. <br>
       It reads: <br>
    `<Code listID="Security User Status">Disabled</Code>` <br>
    j. Click the Close (X) button to close the Message Content window. The OneView displays 
       again. <br>
 2. Click the Infor icon. The Infor M3 Training homepage displays.
 3. Click the User. Open link in the M3 Menu widget. Panel B1 displays.
 4. Double-click the row associated with [your first and last name]. Panel E displays and shows 
    that the user status has changed to 90-Deactivated. This is based on the changes made in IFS.
 5. Click the Close (X) button to close all open Infor M3 programs. The Infor M3 Training homepage 
    displays.
### H5 Settings tab
- The first tab on the H5 Administration page is H5 Settings. You can make special settings assignments based on user roles by using the Infor M3 H5 settings tool. These special assignments are called rules.

## **Exercise 2.4:** Display credit limit script
### **Part 1:** Review a customer’s credit limit
 1. Type Customer Credit Limit. Open in the M3 Menu widget Search field. Results display.
 2. Click the Customer Credit Limit. Open option. The Customer Credit Limit. Open (CRS315) program opens. Panel B displays.
 3. Verify 1-Division, Payer displays in the Sorting order field.
 4. Type 3 in the Payer (positioning) field.
 5. Click the Apply button. The list refreshes.
 6. Click to highlight the row related to payer 30001.
 7. Click Options > Display. Panel E displays. The credit limit for the payer displays. This is in USD currency as indicated by the Currency field.
 8. Click the Close (X) button to close the Customer Credit Limit. Open (CRS315) program. The Infor M3 Training homepage displays.
### **Part 2:** Add the script to the appropriate panel
 1. Start the Customer Order. Open (OIS100) program. Panel A displays and here is currently no 
     credit limit information on this panel.
 2. Click Tools > Personalize > Scripts. The Scripts dialog box opens.
 3. Type OIS100A_SalesAndOverdue_H5_V1 in the Script field.
 4. Type 3, 40, 120, Credit limit in the Argument field. This represents the label position (3, 40), the 
    field width (120), and the label text (Credit limit).
 5. Click the Add button. The script displays in the Created Scripts field.
 6. Click the Save button. The Customer Order. Open (OIS100/A) program displays again.
 7. Click Actions > Refresh. The field with the credit limit information is added.
Part 3: Test the script
1. Type 30001 in the Customer field.
2. Press Enter. A message, “Confirm” displays on the lower left hand corner. The credit limit field is 
populated. The credit limit from Part 1 displays along with the currency symbol.
3. Click the Close (X) button to close the Customer Order. Open (OIS100) program. The Infor M3 
Training homepage displays.

## 1. Describe the features of Infor M3 H5.
- Secure path for the future
- Low TCO
- No more upgrades
- Fast access to new innovations
- Flexibility and scalability
- Security
- Best-in-class resilience
- Openness to support needs
## 2. Describe each unique M3 CE MT customer environment.
- Each unique customer environment is known as a tenant. Each tenant gets a unique and isolated segment of the solution – all hosted in the Infor M3 multi-tenant     cloud on AWS. 
- Tenants cohabit and share the application server resources but cannot “see” each other. 
- Databases are separate for manageability purposes.
## Introducing companies and divisions
Infor M3 uses companies and divisions to organize data. The Infor M3 standard database schema (library) contains database tables, views, and indexes for up to 999 companies and their divisions.
### Infor M3 companies
- An Infor M3 company relates to your own organization’s structure. For some organizations, a single company represents their entire world-wide organization; for others, using a company to represent the
- Infor M3 companies provide a means of separating sets of data. Multiple companies can run within the same database schema and operating environment. This is useful when a business organization consists of two or more unique entities.
- Organization in each country may more effectively meet business needs.
  
### Infor M3 divisions
- companies are the major structural unit and divisions are the minor structural unit.
- Since the division identifier is a three-character alphanumeric field, a company can have several divisions.
- A blank division is always created. This is sometimes referred to by Infor M3 consultants as the central division.
### There are three special ASJs:
- **CMNGJOB:–** This job is responsible for taking jobs from the Java job queues and delivering them to the system for processing. If this job is not active, no                    batch jobs will be processed.
- **CSCHJOB :–** This is the Infor M3 job scheduler. It is responsible for starting jobs at their scheduled dates and times.
- **SES900:–** This job maintains role-based security settings.
### Routing jobs to job queues
- Jobs can be routed to specific job queues according to settings you define in **Job. Connect Job Queue (MNS310)**.
### Queuing priority:-
- 1 to 9 where 1 = highest priority, 9 = lowest.
- Unassigned jobs go to QBATCH with a default priority of 5.
### Jobs are checked for definitions in the following order:
- Job and user
- Job and role or user group
- Job
- User
- User group
### Monitoring job processing
Use **Job. Display History (MNS320)** to perform the following tasks:
- View job queues: Only jobs not yet started or jobs ended and Job History requested
- View or change priority
- View or change queue
### View job status:
- 00 – Waiting to be run
- 15 – Not able to run (CMNGJOB failed to start the job)
- 20 – Currently active
- 25 – Job ended abnormally
- 30 – Job has finished
## Exercise 3.1: Manage jobs:-
### Part 1: Create a job queue:-
1. Type Job Queue. Open in the M3 Menu widget Search field. Results display.
2. Click the Job Queue. Open option. The Job Queue. Open (MNS300) program opens. Panel B1 displays.
3. Type [your 009Tnn assigned user ID] in the Job queue filter field.
4. Click Options > Create. Panel E displays.
5. Type [your 009Tnn assigned user ID] job queue in the Description field.
6. Type 5 in the Max active jobs field.
7. Click the Next button. Panel B1 displays again.
8. Click the Close (X) button to close the Job Queue. Open (MNS300) program. The Infor M3 Training homepage displays again.
### Part 2: Create a new job entry
Type Job. Connect Job Queue in the M3 Menu widget Search field. Results display.
Click the Job. Connect Job Queue option. The Job. Connect Job Queue (MNS310) program 
opens. Panel B1 displays.
Type MMS631CL in the Job field.
Type [your 009Tnn assigned user ID] in the User/group field.
Click Options > Create. Panel E displays.
Type [your 009Tnn job queue in part 1] in the Job queue field.
Click to select the Save job history check box.
Click the Next button. Panel B1 displays again.
Click the Close (X) button to close the Job. Connect Job Queue (MNS310) program. The Infor 
M3 Training homepage displays again.
### Part 3: Run a batch job to confirm the new job queue is used
1. Type Item. Print in the M3 Menu widget Search field. Results display.
2. Click the Item. Print option. The Item. Print (MMS630) program opens. Panel E displays.
3. Click the Next button. The message, “Job MMS631CL has been submitted” displays in the 
   bottom-left margin of the panel.
4. Click the Close (X) button to close the Item. Print (MMS630) program. The Infor M3 training
   homepage displays.
5. Type Job. Display History in the M3 Menu widget Search field. Results display.
6. Click the Job. Display History option. The Job. Display History (MNS320) program opens.
   Panel B1 displays.
7. Click the Filter Options drop-down arrow (see screenshot below). Filtering options expand.
8. Click the Sorting Order drop-down arrow. A list displays.
9. Click the 3-Changed by, Status, Job Queue, Job q prt list option.
10. Type [your 009Tnn assigned user ID] in the Changed by filter field.
11. Click the Apply button. The job queue associated with [your assigned 009Tnn user ID] displays. This confirms the job was sent to the correct queue of QBATCH.
12. Click the Close (X) button to close the Job. Display History (MNS320) program. The Infor M3 Training homepage displays.
## Exercise 3.2: Working with job scheduler
### Part 1: Create a job scheduling calendar
1. Type Job Schedule Calendar. Open in the M3 Menu widget Search field. Results display.
2. Click the Job Schedule Calendar. Open option. The Job Schedule Calendar. Open (SHS060) program opens. Panel B1 displays.
3. Type CAL_[your 009Tnn assigned user ID] in the Job sch cal filter field.
4. Click Options > Create. Panel E displays.
5. Type [your first and last name] in the Name field.
6. Type [your three letter initials] job scheduling calendar in the Description field.
7. Click the Next button. Panel F displays.
8. Verify [today’s date in YYMMDD format] displays in the From Date field.
9. Type [one month from today in YYMMDD format] in the To Date field.
10. Click to select the following check boxes:
    • Monday
    • Wednesday
    • Friday
11. Click the Next button. Panel B displays with a list of dates.
12. Right-click the first date on the first row. The row is highlighted and a list displays.
13. Click the Add Text to Quicknote list item.
14. Click Options > Delete. Panel D displays with the message, “Confirm deletion of schedule date YYMMDD” in the bottom-left corner of the panel.
15. Click the Next button. Panel B displays and the top row you deleted appears as a blank, grayedout row.
16. Type [the deleted schedule date] in the Schedule Date filter field.
17. Click Options > Create. The [created schedule date] now displays in the list.
18. Click the Close (X) button to close all open Infor M3 programs. The Infor M3 Training homepage displays.
### Part 2: Create a job schedule category
1. Type Job Schedule Category. Open in the M3 Menu widget Search field. Results display.
2. Click the Job Schedule Category. Open option. The Job Schedule Category. Open (SHS050) 
   program opens. Panel B displays.
3. Type A[nn] in the Cat filter field where nn represents your student number.
4. Click Options > Create. Panel E displays.
5. Type [your assigned 009Tnn user ID] all times of day in the Description field.
6. Type 000000 in the Fr time field.
7. Type 235959 in the To time field.
8. Click the Next button. Panel B displays with a new line for your category.
9. Click the Close (X) button to close the Job Schedule Category. Open (SHS050) program. The Infor M3 Training homepage displays.
### Part 3: Set the job schedule configuration
1. Type Job Schedule Function. Open in the M3 Menu widget Search field. Results display.
2. Click the Job Schedule Function. Open option. The Job Schedule Function. Open (SHS030/) program opens. Panel B1 displays.
3. Type MMS630 in the Function filter field.
4. Type [your assigned 009Tnn user ID] in the User filter field.
5. Click Options > Create. Panel E displays.
6. Click the JS allowed drop-down arrow. A List displays.
7. Click the 1-Can sch or run list item.
8. Type A[your assigned student number] in the JS category field.
9. Type MMS630 in the Program field.
10. Type MMS631CL in the Job field.
11. Click the Application drop-down arrow. A list displays.
12. Click the MPM list item.
13. Click the Next button. The Job Schedule Program. Open (SHS031) program opens. Panel B 
    displays.
14. Verify that MMS630 displays in the Program field.
15. Click Options > Create. Panel E displays.
16. Click the Next button. The Job Schedule Field. Open (SHS035) program opens. Panel B 
    displays.
17. Click the Previous button until the Job Schedule Program. Open (SHS031/B) program displays again. The row related to MMS630 displays in the list.
18. Click the Close (X) button until the Infor M3 Training homepage displays.



### The system maintenance run
- There are several functions in Infor M3 BE that are controlled by date, and when the date changes several checks and updates must be done.
- The system maintenance run executes several programs which “clean up” certain elements of the M3 database.
- Some of the programs are always executed when the system maintenance run starts, while others are started optionally.
- The system maintenance run is an alternative to the normal night run.
- It adds flexibility since you can define your own runs.
- **Note:*** Infor recommends running the system maintenance run each night.
-  For a function to run on a schedule, the system maintenance run must be defined in the M3 Business Engine Job Scheduler as a scheduled job.


### Introducing Infor M3 document and media solutions
Infor M3 can generate several types of output. The three categories of output are Ad Hoc Reporting output, Infor M3 Standard Reports output, and Infor M3 Standard Documents output.
### Output solutions available for Infor M3 include the following:
- Infor M3 Output Solution (MOS)
- Infor M3 XML Configurable Output Management (COM)
- IDM Output Management (with Infor M3 XML Configurable)

### Infor M3 Output Solution (MOS)
- Documents to be read by users are managed via output servers such as the Infor M3 Output Solution (MOS) which is also known as OpenText StreamServe.
- A stream file is a structured file that is sent to a specified port on the Infor M3 Output Solution server.
- It is sent via TCP/IP from the Infor M3 application server.
- In the MOS, each stream file received triggers a predefined document layout.
 <img width="444" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/9a005317-a4c1-41ce-bfd9-6fe76696090b">
<br>

### Infor M3 XML Configurable Output Management (COM)
- Infor M3 Configurable Output Management (COM) uses existing Infor M3 output functions to generate XML files as an alternative to stream files.

#### The key benefits of Infor M3 COM include:
- A modern and flexible format in the form of XML instead of stream files
- A modern layout design engine tool of OpenText StoryTeller
- A way to change output data without the need of Java code modification
- An easier connection to Infor’s IDM tool integrating with the OpenText StreamServe solution
  
#### Long-term benefits include:
- Less time and effort when performing Infor M3 software upgrades in the future
- Less overall maintenance
- Less human errors creating document.
  
<img width="456" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/f9c17a0a-c2c3-4e73-b926-007dc935d4fd"> <br>

### Exercise 4.1: Work with Infor M3 COM

#### Part 1: Review components Infor M3 COM
1. Type List and Printer programs. Configure in the M3 Menu widget Search field. Results display.
2. Click the List and Printer programs. Configure option. The List and Printer programs. Configure (CMS005) program opens. Panel B1 displays.
3. Click the Filter Options link (screenshot below). The Sorting order field displays.
4. Click the Sorting order drop-down arrow. A list displays.
5. Click the 3-Printer file list item.
6. Type APS in the Prnt file field.
7. Press Enter.
8. Click to highlight the APS print file row associated with [your assigned user ID number]. For example, if your user number is 04, click to highlight the fourth row down from the first listed APS print file.
9. Click Related > XML structure. The XML Structure. Open (CMS006) program opens. Panel B1 displays.<br>
**Note:** Several versions of the same record display here.
10. Click to highlight [the first row].
11. Click Related > XML Structure. Open Section. The XML Structure. Open Section (CMS007) program opens. Panel B1 displays.<br>
**Note:** The elements column represents fields used.
12. Click to highlight the row associated with sequence number 4.
13. Click Related > XML Structure Section. Open Element. The XML Structure Section. Open Element (CMS009) program opens. Panel B1 displays. From here you can add related tables, virtual fields, section tables, and field groups.
14. Complete the following to review Output. Manage per Job and help text: <br>
 a. Press CTRL+R. The Search and Start window opens. <br>
 b. Type MNS270 in the Search and Start field. The Output. Manage per Job (MNS270) program opens. Panel B1 displays. <br>
 c. Click Tools > User Settings. The User Settings window opens. <br>
 d. Verify the Display help tooltips check box is selected. <br>
 e. Click the Save button. <br>
 f. Hover your mouse over the Sts column header. A detailed explanation of different status types displays. <br>
 
#### Part 2: Access Infor Document Management
1. Click the App menu icon. A menu displays.
2. Click the Document Management menu item. Infor Document Management (IDM) displays.
3. Click the Search Document Management drop-down arrow. A menu displays.
4. Click the Document Type drop-down arrow. A list displays.
5. Click the M3 Layout Template list item.
6. Click the Property or Attribute drop-down arrow. A list displays.
7. Click the Title list item.
8. Click the = Equal drop-down arrow. A list displays.
9. Click the Like list item.
10. Type PPS608PF in the Search field.
11. Click the Search button.
12. Click the PPS608PF thumbnail.
13. Click the Display button. Details related to the PPS608PF purchase order template display.
14. Review the details.
15. Click the Infor icon. The Infor M3 Training homepage displays.
16. Type XML Structure. Open in the M3 Menu widget Search field. Results display.
17. Click the XML Structure. Open option. The XML Structure. Open (CMS006) program opens. Panel B1 displays.
18. Type PPS608 in the Printer file filter field.
19. Press Enter.
20. Click to highlight the row related to PPS608PF.
21. Click Related > XML Structure. Open Section. The XML Structure. Open Section (CMS007) program opens. Panel B1 displays the same information we saw in the IDM template.
22. Click the Close (X) button to close all open Infor M3 programs. The Infor M3 Training homepage displays.

### MOS vs COM

<img width="443" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/41f9a31b-f6a9-494f-97e5-8342bc6601ab">
<br>

### IDM output management
- IDM output management is the built-in output management solution for Infor M3 CE.
- The solution takes layout templates and combines them with data to produce PDF documents and later Excel spreadsheets.
- Customers can also customize the layout templates and store them in IDM.

#### IDM and M3 CE Core are integrated by M3 CE Core using Infor Document Management APIs. The integration supports the following output media types:
- Printing and sending the document in PDF format by e-mail
- Saving the PDF document in Infor Document Management

#### IDM and M3 CE Core are integrated via:
- ION API (REST enabled)
- Context Business Messages
- BOD nouns

#### The Capture Document BOD is an outbound BOD that is sent by IDM when capturing different types of documents

![image](https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/bae09aba-264d-4f87-8669-30cfc904413a)

### Output solutions in Infor M3 CE

<img width="371" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/46b95378-30f7-4bc2-99fe-fa089ea160e9">

### Infor Enterprise Collaborator (IEC)
- Infor Enterprise Collaborator (IEC) is an Infor M3 software component that enables you to create, send,and receive electronic documents in XML and flat file formats.
- IEC provides message-based collaboration between functions in the Infor M3 enterprise management system and other external applications, in 
order to enable business process collaboration within and across enterprises.
- IEC includes enabling technology, flexible development tools, and several ready-made industry standard interfaces.

### Messages
- The Messages tab provides features for searching messages based on status and retrieving messagespecific details. You can view messages, message-related activities, and filter message views.
- Depending on the state of a message, links provide access to related tasks.

### Server
- The Server tab provides server activity monitoring of IEC. It allows you to view different properties and reports.

### Communication
The Communication tab provides a way to manage communication channels.

### Events
On the Events tab you can search for IEC application logs.

### Utilities
On the Utilities tab you can perform tasks relating to reloading, property checks, and translation data utilities.

### Settings
Tenant administrators can change the date format and time zone settings for the Enterprise Collaborator Administration pages by using the Date/Format settings link. Changes will take effect immediately.

### About
The About link displays version information for Infor Enterprise Collaborator.

## Infor Event Hub and Event Analytics
-  Event Hub and Event Analytics are managed by Tenant Administrators and are not used by regular M3 CE users.

<img width="445" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/1743baa6-2c63-4cab-b445-d1510c99f70c">


### Event Hub
- The Event Hub is a generic grid extension for sending events between Infor applications.
-  The Event Hub is a publisher-subscriber framework, that is, an application framework that allows applications to expose historical data to other applications   
  that are interested in receiving this data.
- The Event Hub contains two primary tabs:
   1. **Browse Events:** This tab shows events based on subscriptions and time.
   2. **Administration:** This tab shows the publishers, subscribers, and subscriptions.
  
<img width="437" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/005125ba-0aec-41f9-98f0-21bf4231c735">

-  Event Analytics is used for filtering events for outbound M3 CE BODs and FBMs.

  <img width="434" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/6b56b950-b749-41a3-8a79-8df7df5b142e">

### Data Lake Publisher
- Data Lake Publisher enables M3 BE to publish data to Infor Data Lake.
-  By selecting documents (equivalent to Infor M3 tables), Event Hub subscriptions are created and events from the selected documents are published to Infor Data      Lake through ION Messaging Service.

  <img width="431" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/eafd650f-ea32-4df1-95cb-50db040bf6d1">

### Exercise 5.1: Navigate business process management tools
### Part 1: Navigate the BOD Processor Administration tool
1. Click the App menu icon. A menu displays.
2. Click the Infor M3 menu item. Infor M3 H5 displays.
3. Verify the menu is expanded on the left.
4. Click Administration Tools > BOD Processor Administration. The BOD Processor Administration page displays. Here is where one can define and use BODs and make    
   BODs available to different companies and divisions.
5. Click the BODs tab.
6. Review the information displayed.
7. Click the Master AE tab.
8. Review the information displayed.
   
### Part 2: Navigate the Enterprise Collaborator Administration tool
1. Click Administration Tools > Enterprise Collaborator Administration. The Enterprise Collaborator Administration page displays.
2. Click the Advanced Search link.
3. Review the information displayed.
4. Click the CPU Usage link.
5. Review the information displayed.
6. Click the Retry/Redetect link.
7. Review the information displayed.
8. Click the Agreement Retry/Redetect Messages link.
9. Review the information displayed.
10. Click the Ordered link.
11. Review the information displayed.
12. Click the Variation ID link.
13. Review the information displayed.
14. Click the Suppressed Error Reports link.
15. Review the information displayed.
16. Click the Status link.
17. Click the Show link related to the first row.
18. Click the Log icon.

<img width="263" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/ab4d6ab8-f837-402a-9561-f0782481685f">

19. Review the information displayed.
20. Click the Close (X) button to close the Enterprise Collaborator Administration tab. The BOD Processor Administration page displays again.

### Part 3: Navigate the Event Hub tool
1. Click Administration Tools > Event Hub. The Event Hub page displays.
2. Review the information displayed.
3. Click the Administration tab.
4. Review the information displayed.
   
### Part 4: Navigate the Event Analytics Rules tool
1. Click Administration Tools > Event Analytics Rules. The Event Analytics Rules page displays.
2. Review the information displayed.

### Part 5: Navigate the Data Lake Publisher tool
1. Click Administration Tools > Data Lake Publisher. The Data Lake Publisher page displays.
2. Review the information displayed.
3. Click the Close (X) button to close all administration tools and any open Infor M3 programs. The Infor M3 Training homepage displays.

### Infor M3CE About
- Infor M3CE About is a non-tenant-aware tool that shows change log information for a given M3CE environment.
-  M3CE About shows you the Infor M3 components available and the recent versions released.
-   Each component will show multiple recent and current versions along with any important information on these versions.
![image](https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/0204d2a1-3d91-44c7-ac8b-64d06b9f16ee)

### Managing M3 Business Engine product version
- Use the Feature List. Open (CMS975) program to view a detailed list of features.

### Managing feature lists
- In the Feature List. Open (CMS975) program, records are automatically created every time the system is updated.
- Every feature (NCR) is represented by one record.
     1. Select sorting order 01 to display all features included in a specific product version.
     2. Select sorting order 02 to display all features regardless of product version.
     3. Select sorting order 03 or 04 to display features based on review progress (“Under review” or “Review completed”).
        
### Managing the feature toggle
- The feature toggle is managed in the Feature List. Open (CMS975) program.
- The **Update schedule** field indicates in what system update the feature is forced to be activated.
- Until this update the feature can be activated and deactivated as desired.
- The **Forced activation date** field indicates the installation date of the update that forced the feature to be active.
- After this date the feature cannot be deactivated.

### Managing a feature review
- All feature review fields are managed in the Feature List. Open (CMS975) program.
-  The Review progress field indicates the two major steps in the review progress:
     1. 1 - Under review
     2. 2 - Review completed
- The field is automatically updated based on the Feature status field where:
     1. Status 10-49 indicates “Under review”
     2. Status 50-90 indicates “Review completed”
- Using the feature status, you can define several minor review steps within the two major review steps. 
- The feature statuses are defined per customer, but status 10 – “New,” 50 – “Confirmed,” and 90 –“Completed” are system-defined and cannot be deleted.
- The feature statuses combined with the **Responsible** field enables you to build customer-defined workflows.

### Fix programs
- Infor M3 delivers a new standard for fix programs that enables database updates with full traceability, and the capability to monitor the run’s progress.
<img width="433" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/f3b6ef8f-06cf-4f37-9c35-702cbd9e7e20">

### MCE packages
- The MCE packages related to the new fix programs released for a correction may contain the fix program itself and an updated version of migration utility     
  cCMMigrationMetadata.
- The updated version of the utility contains an array element of newly added fix programs.
- This means that after you install the MCE package and correctly configure the database update manager, the new fix program automatically appears in the list in   
  status 05 (Ready).

### Logging increments
- The logging increment is a feature that lets you track the progress of tables that have a high importance. 
- This feature adds the functionality to log the number of records read and the record updated/written/deleted in runtime.
- With every increment, the program calls a utility and updates the migration table.
- In addition, logging is used for the pause option.
- If the program has the pause option set and the logging increment is set to a value greater than zero, then for every increment the fix program listens for a 
  pause signal to pause its operation.

### CMS950MI - API for database update manager
- The database update manager comes with an API that has the same full functionality as the Db Update Manager(CMS950) program itself.

### Reviewing the details of a feature release
- To see the details of the feature, right-click the feature in the Feature List.
- Open (CMS975/B1) program. 
- Then select Related > Display in Infor Support Portal. Infor Support Portal opens in a new tab and displays the detail of the knowledge base article related to   
  the feature.
<img width="438" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/bc9de46d-a8da-42b6-a6f3-0212b2852413">

## Exercise 6.1: Work with service maintenance tools and programs
### Part 1: Add the M3 Product Updates widget to the homepage
1. Click the Ellipses icon in the Infor M3 Training homepage banner (see screenshot below). A menu displays.
2. Click the Edit Page Layout link. The widgets are now editable, and a new set of tools display in the Infor M3 Training homepage banner.
3. Click the Add Widget link. The Widget Catalog window opens.
4. Click the Search icon (magnifying glass). The Search field displays.
5. Type M3 Product Updates in the Search field.
6. Press Enter. Search results display.
7. Click the + icon associated with the M3 Product Updates widget. A message displays indicating the widget was added.
8. Click the Close (X) button to close the Widget Catalog. The Editing Infor M3 Training page displays again.
9. Click the Save button. The Infor M3 Training homepage displays again with the newly added M3 Product Updates widget (depending on your screen resolution, you 
   may need to scroll down).
10. Click the Configure Widget button in the M3 Product Updates widget. The Configure Widget window opens.
11. Click the Product drop-down arrow. A list displays.
12. Click the M3 Business Engine list item.
13. Click to select the Latest update check box.
14. Click to select the Feature review status check box.
15. Click to select the Current product version check box.
16. Click the Save button. The Infor M3 Training homepage displays and the M3 Product Updates widget is populated with information.

### Part 2: Review programs about features and updates
1. Click [the first] Details link under the Feature review status heading. The Feature List. Open (CMS975) program opens. Panel B1 displays all features and  
   feature details.
2. Complete the following to start, review and close the Db Update Manager:<br>
    a. Press CTRL+R. The Search and Start window opens.<br>
    b. Type CMS950 in the Search and Start field. The Db Update Manager (CMS950) program opens. Panel B1 displays details about migrations.<br>
    c. Review panel B1.<br>
    d. Click the Close (X) button to close the Db Update Manager (CMS950) program.<br>
3. Complete the following the start,and review the System Update. Open program:<br>
    e. Press CTRL+R. The Search and Start window opens.<br>
    f. Type CMS965 in the Search and Start field. The System Update. Open (CMS965) program opens. Panel B1 displays details relating to installations.<br>
    g. Review panel B1.<br>
4. Click the CMS975 Feature List. Open tab.
5. Click to highlight [the first row in the list].
6. Click Related > Display in Infor Support Portal. The Infor Support Portal opens in a new browser tab.
7. Review the information displayed.
8. Click the Close (X) button to close the Infor Support Portal tab. The Feature List. Open (CMS975/B1) program displays again.
9. Click to highlight [the first row in the list].
10. Click Options > Display. Panel E displays and details additional feature information.
11. Complete the following the start and review the Product Update. Open (CMS970) program:<br>
     h. Press CTRL+R. The Search and Start window opens.<br>
     i. Type CMS970 in the Search and Start field. The Product Update. Open (CMS970) program opens. Panel B1 displays additional details about product updates.<br>
     j. Review panel B1.<br>
12. Click the Close (X) button to close all open Infor M3 programs. The Infor M3 Training homepage displays.

## Infor M3 Metadata Publisher (MDP)
- Infor M3 Metadata Publisher (MDP) is a data dictionary – that is, a dictionary of all files and fields that are inside the files, along with the programs they are related to.
-  MDP makes it possible to generate metadata for a unique Infor M3 BE installation.
-   It provides the following functionality:
    1. Access to Infor M3 BE-related metadata
    2. Metadata for programs, database tables, and out files including:
       - Parameter lists<br>
       - Data structures<br>
       - Table columns<br>
       - Table indices<br>
       - Utility programs<br>
    3. Ability to search in any market or customer component (in an on-premise version)
    4. Comparison of different Infor M3 BE installations
    5. Many search, sorting, and filter options
    6. Ability to export to Microsoft Excel
    7. Ability to view/search BE APIs

### Exercise 7.1: Navigate MDP

1. Click the App menu icon. A menu displays.
2. Click the Infor M3 menu item. Infor M3 H5 displays.
3. Verify the menu is expanded on the left.
4. Click Administration Tools > M3 Metadata Publisher. The M3 Metadata Publisher page displays.
5. Click the M3 API Repository drop-down arrow. A list displays.
6. Click the Search API list item.
7. Type CRS610 in the Program Name filter field.
8. Press Enter. Search results display.
9. Click the CRS610MI link. A list of transactions options display.
10. Click the Add link in the first row. The Add – Create a New Customer Record window opens.
11. Click the Outbound fields tab.
12. Review the information displayed.
13. Click the Close (X) button to close the Add – Create a new customer record window. The M3 Metadata Publisher page displays again.
14. Click the GetBasicData link. The GetBasicData – Retrieve Customer Basic Data window opens.
15. Click the Outbound fields tab.
16. Review the information displayed.
17. Click the Close (X) button to close the GetBasicData – Retrieve customer basic data window. The M3 Metadata Publisher page displays again.
18. Click the M3 API Repository drop-down arrow. A list displays.
19. Click the Test API list item.
20. Type CRS610MI in the Program field. The Select button is activated.
21. Click the Select button. The Transaction field is activated.
22. Click the Transaction drop-down arrow. A list displays.
23. Click the GetBasicData list item. Additional fields display.
24. Type 009 in the CONO Integer field.
25. Type 10001 in the CUNO Alpha field.
26. Click the Run button. Test API results display on the right side of the page. Note: It may take a minute to display the results.
27. Click the M3 Function drop-down arrow. A list displays.
28. Click the Fnc Development Client list item.
29. Type CRS008 in the Program field. CRS008Fnc – Manage Facility displays below the Program field.
30. Click the CRS008Fnc – Manage Facility link.
31. Click the REST Call drop-down arrow. A list displays.
32. Click [the first item in the list]. Search results display.
33. Click the heading Search drop-down arrow. A list displays.
34. Click the Search By System Configuration list item.
35. Type MMS001 in the Keywords field. List items display below the Keywords field.
36. Click the MMS001 MPT list item. Additional fields display.
37. Click the Search button. Search results display on the right side of the page.
38. Click the Source Code icon associated with [the first row]. The View Source Code window opens.
39. Click the View link. The source code displays in a new window.
40. Review the source code.
41. Click the Close (X) button to close the code window.
42. Click the Close (X) button to close the View source code window. The M3 Metadata Publisher page displays again.
43. Click the Close (X) button to close all open programs. The Infor M3 Training homepage displays.

## Infor M3 BE Interactive Program Services (IPS)
- It is a tool built in M3 BE that enables you to automate the execution of interactive M3 BE programs.
- To execute a program or a series of programs automatically, you can create a service that contains all the required metadata through the IPS Designer.
- IPS replaces M3 Web Services M3 Program Definition (MPD). IPS also supports legacy web services, that is, in the form of MDPs from the M3 Web Service tool, through REST API.

### Introducing IPS Designer
- Use the IPS Designer to create, update, and test web services and all sub-components that belong to a web service.
- Before creating a web service, you should first determine the M3 BE functionality that should be exposed as a web service.
![image](https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/8df78557-56a8-474d-b901-e3099477b9b7)

### Demo 7.2: Work with IPS
1. Click the App menu icon. A menu displays.
2. Click the Infor M3 menu item. Infor M3 H5 displays.
3. Verify the menu is expanded on the left.
4. Click Administration Tools > Business Engine Interactive Program Services. The Business Engine Interactive Program Services page displays.
5. Click the New drop-down arrow. A list displays.
6. Click the New Service list item. The New Service window opens.
7. Type TestA[your assigned 900Tnn user ID] in the Name field.
8. Click the System Configuration drop-down arrow. A list displays.
9. Click the MVX list item.
10. Click the Create button. The Business Engine Interactive Program Services page displays again.
11. Click the New drop-down arrow. A list displays.
12. Click the New Method list item.
13. Type TestA[your assigned 900Tnn user ID] in the Name field.
14. Click the Create button. The Business Engine Interactive Program Services page displays again.
15. Click the Add button. The Add Program window opens.
16. Click the Program drop-down arrow. A list and search field display.
17. Type CRS055 in the Search field. CRS055 displays at the top of the list.
18. Click the CRS055 list item.
19. Click the Add button. The message, “The program CRS055 has a corresponding MI program. Please use that instead of creating a service if possible. Do you still want to add this program?” displays.
20. Click the Add button. The Business Engine Interactive Program Services page displays again with the service method test method for CRS055.
21. Click the Expand icon associated with Panel Sequence for CRS055.
22. Click the Add button. The Add Panel window opens.
23. Click the Panel drop-down arrow. A list displays.
24. Click the A list item.
25. Click the Function Key drop-down arrow. A list displays.
26. Click the ENTER-ENTER list item.
27. Click the Add button. The Business Engine Interactive Program Services page displays again.
28. Click the Add button. The Add Panel window opens.
29. Click the Panel drop-down arrow. A list displays.
30. Click the E list item.
31. Click the Function Key drop-down arrow. A list displays.
32. Click the F3-End list item.
33. Click the Add button. The Business Engine Interactive Program Services page displays again.
34. Click the Expand icon associated with Input to CRS055.
35. Click to select the following check boxes:<br>
    • WQCUCD<br>
    • WWOPT2<br>
    • WWPSEQ<br>
36. Click the Add to Selected Inputs icon.
37. Click the Constraints field associated with WQCUCD. A drop-down arrow displays in the field.
38. Click the drop-down arrow. A list displays.
39. Click the Mandatory list item.
40. Click the Constraints field associated with WWOPT2. A drop-down arrow displays.
41. Click the Constant list item.
42. Click the Constraints field associated with WWPSEQ. A drop-down arrow displays.
43. Click the Constant list item.
44. Type 5 in the Default Value field associated with WWOPT2.
45. Type E in the Default Value field associated with WWPSEQ.
46. Click the Expand icon associated with Output from CRS055.
47. Click to select the WTTX40 check box.
48. Click the Add to Selected Outputs icon.
49. Click the File drop-down arrow (at the top of the Business Engine Interactive Program Services page). A list displays.
50. Click the Save list item. A Changes window opens.
51. Type Changes to [your assigned 900Tnn user ID]-Test1 in the Description field.
52. Click the Save button. The message, “Service test successfully saved” displays.
53. Click the OK button.
54. Click the New drop-down arrow. A list displays.
55. Click the New Test Case list item. The New Test Case window opens.
56. Type [your assigned 900Tnn user ID]TestCaseTest1 in the Name field.
57. Type [your assigned 009Tnn user ID] first test case in the Description field.
58. Click the Create button.
59. Click the Company/Division drop-down arrow. A list displays.
60. Click the 9/ BBB list item.
61. Type USD in the Currency (WQCUCD) – string field.
62. Click the Execute Service button. Test results display in the Test Result field.
63. Review the test result information.
64. Click the Close (X) button to close all open Infor M3 programs. The Infor M3 Training homepage displays.

### Business Engine Field Audit Trail
- The Business Engine Field Audit Trail is used to set up audits of data changes made to specific BE database fields.
- It enables you to keep track of when the changes were made, what the previous value was prior to the change, and which user made the change.
<img width="423" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/a0271844-d0dc-4ba5-9290-d81d778b3720">

### Exercise 7.3: Navigate the Business Engine Field Audit Trail tool
1. Click the App menu icon. A menu displays.
2. Click the Infor M3 menu item. The Infor M3 H5 thin client displays.
3. Verify the menu is expanded on the left.
4. Click Administration Tools > Business Engine Field Audit Trail. The Business Engine Field Audit Trail page displays.
5. Click the New button. The New Audit window opens.
6. Type MMSNPR in the Table field. MMSNPR (MVXJDTA) displays in a list below the Table field.
7. Click the MMSNPR (MVXJDTA) list item.
8. Click to select the following check boxes:<br>
   • Active<br>
   • Insert<br>
   • Update<br>
   • Delete<br>
9. Click to highlight the SNLVDT – Valid to in the Non-audited fields column of the table at the bottom of the window.
10. Click the Select icon. SNLVDT – Valid to now displays in the Audited fields column of the table at the bottom of the window.
11. Click the Save button.
12. Click to highlight the MMSNPR current audit row. The Edit and Delete buttons activate.
13. Click the Show More link under the History (changes to Audit settings) heading. Additional details about the table, fields, keys, and data display.
14. Review the information displayed.
15. Click the Show Less link.
16. Click the Close (X) button to close all open Infor M3 programs. The Infor M3 Training homepage displays.

### Infor M3 function search
- Infor M3 function search is a generic search tool using Infor Enterprise Search (IES) that supports searching any field for any value in the Infor M3 database.
- IES is a deeply integrated, intuitive search application for Infor M3 and non-Infor M3 data to help organizations search and find relevant information securely and quickly.
<img width="437" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/70a36aef-db32-467a-aa63-72bb522a2e56">

### Defining system settings
- You can define system settings in the System Settings. Open (MNS090) program.
<img width="435" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/9da8eafe-efd6-4178-8b77-310d92e9ef49">

### Infor M3 function search administration tasks
- Use the M3 Function Search Administration page to manually activate or deactivate applicable tables.
<img width="438" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/d0326802-9558-4794-ba5a-cd89e290ce75">

### Introducing Infor M3 CE security
- Infor M3 CE security consists of three parts:<br>
   • **User access to Infor M3 functionality:** It guarantees the access to Infor M3 or any other products and the access security.<br>
   • **General security:** It is applied over the application to control areas such as access to Infor M3 functions and individual fields. The system 
     administrator or the security officer maintains general security.<br>
   • **Application security:** It is built-in and exists as an integral part of the logic flow in some areas of the system, such as in the financial accounts and 
     purchasing modules. Each user maintains his/her own application security.<br>
![image](https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/bc8528ef-140d-4620-b4c3-b7bc19c8e2c0)

### Infor M3 security feature
- Infor M3 BE provides the following methods to manage security for Infor M3 API:<br>
     • Authorization by transaction - Function. Connect API Authorization (SES005)<br>
     • Authorization by roles - Function. Connect Authorization by Role (SES400) and API Transaction. Connect Security Option (SES405)<br>
     • User authentication<br>
     • Infor M3 users are authenticated through the platform mechanism for user authentication. The user must also be registered in M3 using MNS150.<br>

### System Settings. Open (MNS090)
- The API security for authorization by transaction is activated by selecting option **1 – Security via authorization** in the **API security** field.
- When you select alternative 1, users that are authorized to use API transactions must be added in the **Function. Connect API Authorization (SES005)** program.
- If no entries for the user exist in the **Function. Connect API Authorization (SES005)** program the APItransaction is denied.
- The security through authorization by roles for API is activated by selecting option **2 – Security via roles** in the **API security** field.
- **Note:** Before this alternative can be selected, every API transaction and default security option must be generated in the **API Transaction. Connect 
  Security Option (SES405)** program.
- A transaction that does not exist or with a blank security option in the **API Transaction. Connect Security Option (SES405)** program is considered restricted 
  and denied for all users.

### Infor Federation Services (IFS)
- IFS provides the following capabilities:<br>
   • Single sign-on / single sign-out<br>
   • Multi-factor authentication<br>
   • User management<br>
   • User inactivity timeout (in association with Infor OS)<br>
   • User provisioning and user synchronization<br>
   • Synchronization of security roles<br>
   • User-to-role mapping<br>
   • Synchronization of users across different security domains<br>

### Adding IFS security roles
- If any of the required IFS security roles are missing, you must add these roles manually through the User Management menu in Infor Ming.le.
<img width="433" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/90679752-106a-4776-9b4c-98c20ff90c1c">

## Exercise 8.1: Add the IDM security role to a user in IFS
1. Click the User Menu icon. A menu displays.
2. Click the User Management menu item. The Users panel of Infor Federation Services (IFS) tool opens.
3. Click the User Details button associated with [your name]. The [your name] user panel opens.
4. Click the Security Roles tab.
5. Click the Add New Item icon (screenshot below). The Select Security Roles window opens.
  <img width="131" alt="image" src="https://github.com/sravanDwadasi/M3-AdministeringtheSysteminCloudEdition/assets/53566313/318fc2e0-4721-4924-abb2-26a6c618c9f5">

6. Click to select the check box associated with IDM-User.
7. Click the Add & Close button. The Security Roles tab displays again with the newly added roles.
8. Click the Save Item button.
9. Click the Close (X) button to close all open Infor M3 programs. The Infor M3 Training homepage displays.
