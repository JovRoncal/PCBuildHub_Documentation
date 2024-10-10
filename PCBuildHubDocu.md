# PC BUILD HUB: Ecommerce and PC Build Management

## INTRODUCTION

Building a PC remains one of the seemingly complex operations for people setting out. This involves choosing the best parts,
assembling them correctly, and ensuring that the final build works as it should. PC Build Hub seeks to overcome these challenges 
by providing a simple platform through which one can buy PC parts with instructions on building one's own PCs. 
This system will enable users to choose parts that work, check compatibility and, through video tutorials, guide them step by step on how to assemble parts.

PC Build Hub is designed as an ecommerce website from where individuals can simply buy their computer parts and have an educational site which provides video tutorials on assembling a computer. 
The system should reduce part selection errors and, additionally, shall provide the users with the best tools to build computers. 
It also provides order tracking and compatibility check tools in addition to a community forum where advice shall be available.

The system will be automated and intelligently designed so that one can manage building his or her PC efficiently-from parts to assembly without deep technical knowledge. 
It allows users to create profiles and save their builds so that they can purchase their components from a trusted marketplace 
to make the process of building a custom PC as easy and streamlined as possible.

## Project Features and Characteristics
The proposed project Umak Library Mobile App consists of the following features:
1. PC Parts Catalog - It provides a huge collection of computer components with live prices and availability.
It features different categories of parts; processors, graphics cards, motherboards, and others.
2.Build Configuration Tool- Assists user with a tailor-made PC by choosing parts which could couple with each other. 
In case the user's chosen parts fail to match, recommendations are provided by the tool.
Video Tutorial Module-Provides video guides to enable a user to assemble his or her own PC from scratch, hence assuring proper assembly.
3. User Profiles and Build Saving – This feature allows users to create user profiles, save custom PC builds, and track past purchases or wishlists.
4. Order Tracking and Payment Module – The module has real-time order tracking with secure online payments, allowing users to track the purchase and delivery status.
5. Community Forum – This is a feature that enables users to be part of a community of PC builders,
   where they can seek advice, share builds, and get tips from experienced builders.
6. Reports Module – Informs the admin-users of the daily, weekly, monthly and yearly sales reports, user activity reports and popular builds reports. 

## Project Scope

The PC Build Hub App, therefore proposes an easy process when purchasing and assembling a computer. 
That would offer an all-in-one platform where users can browse, select, and purchase all the parts required in building a custom PC; whilst following video tutorials in the assembling of their computer. 
The application would be especially designed for first-time and more veteran builders who would be supported in finding and sourcing all the PC parts and assembling instructions along with ecommerce.

There will be two major groups that use the system.

End-users (PC-builders): They shall have access to the parts catalog. 
They can also use the build configuration tool which checks for compatibility, save builds, track orders, and watch video tutorials on assembling the PC. 
In case of any questions or even wish to share his/her build, they can join the community discussions.
Admins/Management Team of PC Build Hub: The admins will be able to see all kinds of reports 
on sales and user activities and will also be able to administer or have control over inventory management, orders, and user interactions via the system.



## Work breakdown Structure


![image](https://github.com/user-attachments/assets/9be82d3f-7156-405b-acbf-9e2dbef4ec9d)

For better view https://www.figma.com/design/AGRTYcqHsYlPiwQF9KIATa/Untitled?node-id=0-1&node-type=canvas&t=tTrqhhi1S46zY8D8-0


## Functional Requirements

### User Requirements

| No. | Users      | System Features                                          | Requirement                                                                                                                                                |
|-----|------------|----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Admin      | A. User Management Module - Register Users               | 1. 1. The system must allow the Admin to register users on the platform by entering:                                                                       |
|     |            |                                                          |    a. Email address                                                                                                                                        |
|     |            |                                                          |    b. Name                                                                                                                                                 |
|     |            |                                                          |    c. Password                                                                                                                                             |
|     |            |                                                          |    d. Address                                                                                                                                              |
|     |            |                                                          |    e. Phone Number                                                                                                                                         |
|     |            |                                                          |    f. Preferred PC specs                                                                                                                                   |
|     |            |                                                          |    g. Role (User/Admin)                                                                                                                                    |
|     |            |                                                          |                                                                                                                                                            |
|     |            | B. User Management Module - View User Details            | 2. The system must allow the Admin to view user details:                                                                                                   |
|     |            |                                                          |    a. User ID                                                                                                                                              |
|     |            |                                                          |    b. Order history                                                                                                                                        |
|     |            |                                                          |    c. Activity logs                                                                                                                                        |
|     |            |                                                          |    d. Account status                                                                                                                                       |                  
|     |            | C. User Management Module - User Activity History        | 3. The system must allow the Admin to view the history of user activities such as:                                                                         |
|     |            |                                                          |    a. User Name                                                                                                                                            |
|     |            |                                                          |    b. Components ordered/built                                                                                                                             |
|     |            | D. Catalog Module - Manage PC Components                 | 4. The system must allow the Admin to add new PC components by entering:                                                                                   |
|     |            |                                                          |    a. Component name                                                                                                                                       |
|     |            |                                                          |    b. Manufacturer                                                                                                                                         |
|     |            |                                                          |    c. Specifications                                                                                                                                       |
|     |            |                                                          |    d. Price                                                                                                                                                |
|     |            |                                                          |    e. Stock availability                                                                                                                                   |
|     |            |                                                          |    f. Category (CPU, GPU, RAM, etc.)                                                                                                                       |                  
|     |            | E. Circulation Management Module                         | 5. The system must allow the Admin to process orders by entering:                                                                                          |
|     |            |                                                          |    a. User name                                                                                                                                            |
|     |            |                                                          |    b. Order ID                                                                                                                                             |
|     |            |                                                          |    c. Component details                                                                                                                                    |
|     |            |                                                          |    d. Payment status                                                                                                                                       |
|     |            |                                                          |    e. Borrower Section                                                                                                                                     |
|     |            |                                                          |    f. Shipping details                                                                                                                                     |
|     |            | F. Report Module                                         | 6. The system must allow the Admin to view sales reports with:                                                                                             |
|     |            |                                                          |    a. Daily                                                                                                                                                |
|     |            |                                                          |    b. Weekly                                                                                                                                               |
|     |            |                                                          |    c. Monthly                                                                                                                                              |
|     |            |                                                          |    d. Yearly breakdown                                                                                                                                     |
| 2   | Borrowers  | A. User Management Module - Login                        | 1. 1. The system must allow users to log in by entering:                                                                                                   |
|     |            |                                                          |    a. Email address                                                                                                                                        |
|     |            |                                                          |    b. Password                                                                                                                                             |
|     |            | B. Product Catalog - View Components                     | 2. The system must allow users to view available components, including:                                                                                    |
|     |            |                                                          |    a. Name                                                                                                                                                 |
|     |            |                                                          |    b. Specifications                                                                                                                                       |
|     |            |                                                          |    c. Price                                                                                                                                                |
|     |            |                                                          |    d. Popular/recommended components                                                                                                                       |
|     |            | C. Product Catalog - Search                              | 3. The system must allow users to search for components by:                                                                                                |
|     |            |                                                          |    a. Component name                                                                                                                                       |
|     |            |                                                          |    b. Manufacturer                                                                                                                                         |
|     |            |                                                          |    c. Category                                                                                                                                             |
|     |            | D. Build Configuration Module                            | 4. The system must allow users to configure and simulate their PC builds by:                                                                               |
|     |            |                                                          |    a. Selecting components                                                                                                                                 |
|     |            |                                                          |    b. Ensuring compatibility                                                                                                                               |
|     |            |                                                          |    c. Calculating total price                                                                                                                              |
|     |            |	E. Order Management Module                               | 5. The system must allow users to place orders and generate:                                                                                               |
|     |            |                                                          |    a. Order confirmation                                                                                                                                   |
|     |            |                                                          |    b. Payment status                                                                                                                                       |
|     |            |                                                          |    c. Delivery tracking                                                                                                                                    |
|     |            | F. Video Tutorials Module                                | 6. The system must allow users to access video tutorials on building their PCs using purchased components.                                                 |

### use case

![image](https://github.com/user-attachments/assets/32032259-80b4-4c31-8dec-5403738a76e7)

For best view: https://www.figma.com/design/gDnp740G80bjTRiuNtwzaq/Untitled?node-id=0-1&node-type=canvas&t=Ds8ATXg6EvT5qoHJ-0


## Database Architecture

### Data Dictionary
### Table 1: USER
  
| FIELD NAME  | DESCRIPTION                          | DATA TYPE | LENGTH | SAMPLE        |
|-------------|--------------------------------------|-----------|--------|---------------|
| USER_ID     | Unique Identification of User        | String    | 255    | ABC1234       |
| NAME        | Full name of the user                | String    | 255    | Roel Lungayan |
| EMAIL       | User email                           | String    | 255    | roel@gmail.com|
| PASSWORD    | Encrypted user password              | String    | 255    | encrypted_pass|
| ACCOUNT_TYPE| Type of user (Admin, Customer)       | String    | 255    | Admin         |
| CREATED     | Date the user account was created    | String    | Date   | 12/12/2023    |

### Table 2: PC_COMPONENT

| FIELD NAME        | DESCRIPTION                             | DATA TYPE | LENGTH | SAMPLE                |
|-------------------|-----------------------------------------|-----------|--------|-----------------------|
| COMPONENT_ID      | Unique ID for each component            | String    | 255    | CPU1234               |
| NAME              | Name of the component                   | String    | 255    | Intel i7 Processor    |
| TYPE              | Type of component (e.g., CPU, RAM, GPU) | String    | 255    | CPU                   |
| BRAND             | Brand of the component                  | String    | 255    | Intel                 |
| PRICE             | Price of the component                  | Float     |        | 350.00                |
| STOCK             | Number of components available          | Int       |        | 20                    |

### Table 3: ORDER

| FIELD NAME   | DESCRIPTION                                | DATA TYPE | LENGTH | SAMPLE                   |
|--------------|--------------------------------------------|-----------|--------|--------------------------|
| ORDER_ID     | Unique ID for each order                   | String    | 255    | ORDER1234                |
| USER_ID      | ID of the user who placed the order        | String    | 255    | ABC1234                  |
| TOTAL_AMOUNT | Total amount of the order                  | Float     | -      | 750.00                   |
| STATUS       | Order status (Pending, Shipped, Delivered) | String    | 255    | Pending                  |
| CREATED      | Date the order was placed                  | Date      | -      | 12/12/2023               |

### Table 4: ORDER_ITEMS 


| FIELD NAME       | DESCRIPTION                                   | DATA TYPE | LENGTH | SAMPLE      |
|------------------|-----------------------------------------------|-----------|--------|-------------|
| ORDER_ITEM_ID    | Unique ID for the order item                  | String    | 255    | ITEM1234    |
| ORDER_ID         | ID of the related order                       | String    | 255    | ORDER1234   |
| COMPONENT_ID     | ID of the purchased component                 | String    | 255    | CPU1234     |
| QUANTITY         | Quantity ordered                              | Int       | -      | 2           |
| UNIT_PRICE       | Price per unit of the component               | Float     | -      | 350.00      |

### Table 5: CONFIGURATION

| FIELD NAME         | DESCRIPTION                                         | DATA TYPE | LENGTH | SAMPLE                     |
|--------------------|-----------------------------------------------------|-----------|--------|----------------------------|
| CONFIGURATION_ID    | Unique ID for each configuration                   | String    | 255    | CONFIG1234                 |
| USER_ID             | ID of the user who created the configuration       | String    | 255    | ABC1234                    |
| COMPONENT_LIST      | List of components selected (IDs)                  | String    | 255    | [CPU1234, RAM5678]         |
| TOTAL_PRICE         | Total price of the selected components             | Float     | -      | 700.00                     |
| CREATED             | Date the configuration was created                 | Date      | -      | 12/12/2023                 |

### Table 6: LOGS

| FIELD NAME   | DESCRIPTION                                    | DATA TYPE | LENGTH | SAMPLE               |
|--------------|------------------------------------------------|-----------|--------|----------------------|
| LOG_ID       | Unique ID for each log entry                   | String    | 255    | LOG1234              |
| USER_ID      | ID of the user who performed the action        | String    | 255    | ABC1234              |
| ACTION       | Description of the action                      | String    | 255    | Placed Order         |
| TIMESTAMP    | Date and time of the action                    | Date      | -      | 12/12/2023 12:00:00  |


### Table 8: RATINGS

| FIELD NAME      | DESCRIPTION                                 | DATA TYPE  | LENGTH | SAMPLE               |
|-----------------|---------------------------------------------|------------|--------|----------------------|
| RATING_ID       | Unique ID for the rating                    | String     | 255    | RATE1234             | 
| USER_ID         | ID of the user who rated                    | String     | 255    | ABC1234              | 
| COMPONENT_ID    | ID of the rated component                   | String     | 255    | CPU1234              | 
| RATING_VALUE    | Rating given (1-5)                          | Int        | -      | 5                    |
| COMMENT         | User comment on the component               | String     | 255    | Great performance!   |
| CREATED         | Date the rating was submitted               | Date       | -      | 12/12/2023           |


## ERD

For Best View
https://www.figma.com/file/OXqoeVy3G1U1d3NSjdelYO/UMAK-LIBRARY-ERD?node-
id=0%3A1&t=rUvRxPi6Dcy35dHu


![image](https://github.com/user-attachments/assets/d4f53445-c2bd-4a6f-830f-5dd8e2177959)


## Non Functional Requirements

### Product Requirement (PLEASE SKIP THIS)

### Organizational Requirement (PLEASE SKIP THIS)


### External Requirements  (PLEASE SKIP THIS)


## System Testing and Evaluation   (PLEASE SKIP THIS)

### Functional Testing Procedure   (PLEASE SKIP THIS)

### Functional Testing Summary

### Evaluation Procedure

### Recommendation






### Wireframe (PLEASE SKIP THIS)



### High Fidelity (PLEASE SKIP THIS)



### System Screenshot (PLEASE SKIP THIS)
