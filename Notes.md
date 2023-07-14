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

