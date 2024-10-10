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

1. User Accounts: 
   - Users can sign up, log in, and manage their profiles.
   - Admins manage the system, customers shop and configure builds.

2. PC Components Catalog:
   - Detailed listings of components (CPUs, GPUs, etc.) with prices, stock, and images.

3. Custom PC Configuration:
   - Users build custom PC setups, calculate total price, and save configurations.

4. Order Management:
   - Users can place orders, track statuses, and view order history.
   - Admins can manage and update order statuses.

5. Ratings & Reviews:
   - Customers can rate and review components.
   - Admins can moderate reviews.

6. Inventory Management:
   - Real-time stock tracking with admin alerts for low inventory.

7. Action Logs:
   - Logs track user and admin actions with timestamps for auditing.

8. Search & Filters:
   - Search components by name, type, or brand, and filter by price, rating, etc.

9. Admin Dashboard:
   - Admins view metrics, manage orders, inventory, and users from a central dashboard.

10. **Mobile-Friendly**:
    - Responsive design for mobile and desktop users.

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
[https://www.figma.com/file/OXqoeVy3G1U1d3NSjdelYO/UMAK-LIBRARY-ERD?node-
id=0%3A1&t=rUvRxPi6Dcy35dHu](https://online.visual-paradigm.com/app/diagrams/?lightbox=1&target=blank&highlight=0000ff&edit=https%3A%2F%2Fonline.visual-paradigm.com%2Fapp%2Fdiagrams%2F%23diagram%3Aproj%3D0%26id%3D1%26type%3DERDiagram%26width%3D11%26height%3D8.5%26unit%3Dinch&editBlankUrl=https%3A%2F%2Fonline.visual-paradigm.com%2Fapp%2Fdiagrams%2F%23diagram%3Aproj%3D0%26vpov%3D16.3%26vpob%3D20220410%26client%3D1%26edit%3D_blank&layers=1&nav=1&title=PC%20BUILD%20HUB%20ERD&vpov=16.3&vpob=20220410#R3cU2FsddGVkX1G%2BbCRtUV8NaI9k7YsulWb8Sa5cC2txElgOTBIHqU%3DT8GhRRn5SCseRlO4BGoCyOiKESJkImKD0tkbdKC71aWkNlFxir7ob6dzzCz7VphnN%2FhvXR%2BwiwgiKPvims6qH7CZeeFHbAqp2vUgC2E53L0zdnoPsvZW4FSBbDvTo5yC7uYpq6BXaLiJroHzVyOnStVJxp9SflDZUhlL4a5OtrtWR0zaStrwT37RfxWH8aqQwlHrb5BzshAy3NKfPVmQNhFlwovfykOkHYfKCE5xzseSiKWBirTc3s3zqdPW2Ltf1LDRKawj3n7pxbdsNAquCSB8WN20m65cwuUAHRg30qQalL%2Bw8USXwZGXDigbUWS2XlVfugBmc%2F0rR4RfZr0%2FddHGcYEoasC2uyEMtNswMHwS7xb1A0uGRhgyiaPkcUeepYpcW0fL5FcahuDAYPjhT6oJ0cNzZXckTDYGkDEiUuIggZx1teGwZlX%2Bh%2BKmztrnCrRiBuxMs%2BLKxaZSRWxAMMUEBpgPzELgr%2FpDpsZ4Nb3tWQvBJKH967UII%2FblZaafVMMQT8IhRXLbaH7P%2FKCke1M6zNqUsw63zNgj5JxsvLHZgrzEQ0zwH%2ByehI88m1HDAfj8u1NJ75LsyogNBqdoYDs7TQRUmH34E%2Bd%2BOMR0%2FQWrgYRCsq0RdKR0tjWQHviBkiMdqp%2BUFnObo6GxLqxzowcu08e2mDUoCg91TJYcVFYsdpdRZKyLK%2BohZ2ZM2LIPqZfm%2B17rkX3GJVT8bgDfwEYS2rfaAe8gvOBsgwvVkHknBF2WYnQQsUeOaChVynlMGVHjj%2BCMHGltQovi7mXtiIRIyjge7vKHS8K%2B%2BWN%2BwUg%2BtLN5UkWLA73BHeFsVrhuXZAf1dApgCwsCE11ErvbVjqCu4FqJ7RBCtbRpxos3EhYnTk7cwtOif2tMFJRJTMuVec%2B9z8pXi67uAf%2FOMgWiF6q2dPdeJqnXEHK0sXzivlr4Zwy40angrHWopB7ybGsmixfwUlGjFe2ENjuXi2QSTfq4A%2Br%2F8brtMLXkzBLQKVp9DZRfS%2B3OlOiaQAq3%2FfYAY4hsQu5Ty6d9tRBg2mtpGCwi8JhDOcCiprKshlEh0v9O6BroHUGQ%2FzcsrPSDhXKGHqDZ3030R0je282mL0VioRyqD1GOiPHblU4ZDasUH8tPfL3y73JGepJLvmFYigH1vuLUSZwk%2BYp%2B2guwe0%2Bfhwb1nwKri8zyvou6uiSksTdK5v7oX%2Bcombvl5OE89MIJGOpA%2Boagf8%2FEVWAvoH9oiL6hAlg%2B2%2FfCwB4LltjuZe520%2BcoMJbxGosTNIIl3LeTiy44f4jBdV%2Bx5e4bO%2F4Fco1hYiLryfwO0i%2FCQoV0%2B9nlF6%2BGwuIvtMWmwEajxGMAusmcO3d9ozxEWbrOyvYOn664SQvLsPvijwMNXp8SKJlUU%2Bbv2ZSW2yCKiNK4z4Se%2B0vB4ULQUz9PKgOJANeoNFHoXLQT%2Fm96Nwhyg4bYNZT4bx2ud8Ckr8vQ9SVrc%2F0A4WouPYKN%2FUtl4Nkei4d%2Bj3mycgwPCPdDk9dzYxVMEAMAoj2WXJk9Nwhqg0dkfhNTleX1AHEFyEuuQtGNm2X%2BDpSzLpbBHN%2FUh%2BQaxxwOi7C3AeAhbTlU1av9VrK%2FqTrvx8QXQ0jeGFYO3YNKkwuEHKo2b2PKpqvaVbnXV2eIM1pciJ9ClLGOuEoD2aKgkL%2FYVYbhinK74%2ByQQBFYeUu0HHxKmGo3zQonL%2BkdFbtJ1pAKjCurvmOk9R%2FUDWknmLnXW9m5gr33fpdZb3d2v5HXEEi%2BWrYA8XGx62lvXHyZ3vmNkBrQUc56ahwV67ouIZ%2FSzx1gsRRKlMinkyqOyEyzuZIYdmsnHwRKSi60mjb63NV7cNEJbak%2FEDtY1tTblFUMBzAlvioMwi2VjW5QLzVCJiFgPTSiJTo%2Bvp3Vd27PBCZYlKtTyTnm%2FDZOY7Jt1sDym%2BZlL%2BNHFBaSxZCkCgcXB%2BDdkJ8Q8JsAzQDZXn1yY8yhgDDRGFetEDDOesLIbxxT5Pppu0fzeoBmryfkVRobl8ifzFdPby4NmFPY%2BOLG2mYcL76fd59okDdwxZGi2DkiY7ZJDrqAOlAXyMfgy4zvBs6KIZT0HlVN9MRkQiR37w6cnqfYaD%2FEF%2FWeiw%2FtPbg6OE8SocRtG3G47SPHTmJ4UigYUeQ%2FerOwcDcqyuuu2EChPau73NoP%2ByRktlXAttZ1J4opkZk26c2ogA4enm3f%2BlOpwWj8J96VYs3cp7bWyP6jrp81O6f3NFda3h3LaLHy%2FDhawYw6csSu4C%2FrKKM18s3cwTQHpdXRRDEIslp2yI3RcOTRMNomR1vIaTJpQFi4qA%2Bx5rOu0wTJLopJsIT%2FuTiVGw1g03Y8mYKIJ%2F%2F0ZbTuAxu4EPRKnsZy9cBkO8Txl2d1diwVuY09WDawMzRA%2FFw3%2FwvJWwfcVbfKy31rxTlmeLGKqOw928t46ND1hjBic8L%2B4aDsgmRAkuSGdJ4jsU28Jwq4xOOVpzLESia1Nsv2wijpbmErXVWx9Ma6HN6%2FtqUMjUGmd56EkAEa3Yf4P9x672A68QrP6FJIwiFxFj5TM1Yh9GL3UnKWhoGwPaaEaR5OWFjjgiaemHWjpUnkoYfPH0xTa9hj4BWyHO3Lz9lz7PfJls5LJQXyM3DDOqigTg9bVSuA3QcRrWW7PzznbvzMHgv2KATnHjSGKJOB6yANJIKRdXwhL%2BOSbdEV7aCb1IB1Zei%2BDvJZma78IGjLMyJ00MUAG30m1D9VppnMo%2Fj93ImL1P5rqFBhzecOEMkOEwGVetXOt1Oh2gUkAibPiOWGsecy739ojeDBBEw%2B4NZr3TEzp6ay99MDPIP%2BubvoYd7%2BQNlS7R5AjksQwAqUlUPaU0N8g2632Na3zmuk7Zb3b8NwgjGJAluCX6OzCeRM7IaVrOC3wzqXT1ImBhxbKo2psoBMnMu8PcMgjsAsmgq%2FAyfKwUeSFHmJLwuomPWTOznjSfnP9zlX%2BBT0hfGsfNqViW9uBvvYXGWLvm86LpMF1nUSOnrnYAAOQuXVpR9J4TTbO%2Fr6Zudco1JyTKrI%2Fc2Zmo1ayG53fSIO8%2F%2BG1Jr%2F0ewkiX9I%2FXMQ98FaTfZmqYkucFF4d%2F2j7KU4ord%2B%2F%2FTQyK127%2By1B5j%2FXh8a4sGarfLtDc%2BprAgcjFrBBv28bX3GUSTDZaK9EvjxLmeVyUQaI5xeEQOGgUEAD7ACHGRUL%2FFFeAi9KWA3j%2B%2B%2BB90%2FOwEMGbKbqKQ9z0faxdwA8iZ02RYNvMpfVU5pqg8QvL79xina9PCa5oaXCKPcTy%2FFSbZp80T2gLEwwuBqaPcyL1kFNZ9XrJ4DgzxKE%2BZr9JzmDDSsn%2BFU6IYRdzSKhV0%2FNy6feLyv1tPMt7w%2F8sFLZyanLIA3GaGoKQlMApgwMo2moZcy3n1I0ASH51O9mQ8jCon2RmVxn80Ph8SmtfdCjiNUX7xW5Vfo5hIm%2FWaxeLQ05O3PLaH2U%2F9sX0WsWXn8ftn84l872RH5YeZmN3lep8Rmu0YB7w%2FovcQ4RJcs3HNU75J8O5deSmkRM4Cu7fB%2FsuyTzUp1sawdWcUDHtPjecuV01gTH%2FxFG%2BYf1WHIqyFi1BkFd3nwWYeBofDJwMTyHZU1XxMpUAWzN6BKiVSSIhZSo%2F9Fe1VJ0mcottnl0wPHlWBX%2B3ARNcI8UDrOBV7XQ3cjDPI%2F1BfNCrwMNbYANzAiGK11YsW6iRyFgGJiXemAlMmxh9X9tFuA1j71Pygw9IVGpXMC3z1R98G8dTYpmVkBMGaB%2FDYrxWkUg9Chn82UkabGXkdtEZr3V0lAKAaFpcFF%2BUUIpL73ClRMeGWz7hiO6nTUDo1d%2FwoTckKr9ZgA16WFCsmhxOFPOQfGEq22vrERKx3KselO4stRdKg66BjePhX3UQJhyQRkuuNhf%2B%2BOpcuxpFh%2BiT%2BeKWcj6QHv%2FwlpDRNPDX3Ewb%2Bzg8x6k1MwFOWHFSQe6JcrviXNP56aQsaDpBG7h0Nl7Px2iCVEwVGkxEMEDWMwFLrYkb4rvcLb5IGQyGxVwIFkjCjfT33MtfvE8nc6xRI0uyajH4IA1gh9lGisfo5X2%2BASFE%2BWhBfZJ8%2BKikEGYKLVAVWhTCVpK5LNUzyI6xr8VAfIjZAmL1x83rvvOg%2FzOlSyo9KaL2d0gey9LppdHA%2Fv8iMGP%2F9MqymrxFrUmwQWLrY7q2fubM78GGl2CHcqGbjfBiOPc2cgw1kb1rVp6FCwvzsPlDM7ZWBQ2TJ5jnGa3si3upTFrtWQozZvj8dseRK4cHcNBMjhvxRRuhzuUi0Y4ojCkITSINOfeUNRRVVyJFJuCZgy5%2ByZ0Z%2BBfbqayyj624qcN44%2Bi0IlSXRw8LT%2FtLkmEcBUyLsSMvjMDzf8Yo8gJrTzWysOe8va%2B0Uv%2F36sEmuEZElD2XSpchHiAxzyA8jZVOasn%2FTTtxaCEVqnIxO7QEUMMai3CfHFsVjUjgAXm2LWi73mf7B6m2xkEH7MAvc%2BCSmPsBH3CnC6sNP1sNpRfqFZubJ%2Ba9E1tUDY4nIlYGr74UeNleQyqGBM8nJ%2F%2FT14JAGyZxeEzX3H8d%2Fayx4MIi5zPAe2FfUO1iEOjVJivtGCRIJKoMWwiNlI3liw4L9LLow1U2s6aLQGvYHXwboqV0BXSMy0doAzxFVQ5vF%2FzOrfEawHJ%2FTkBvlW7D7MWkAzTN%2FpnlsXYpAz5kLAIx5eEjFiOHsiJkuxEnhgm7L1KBmdYuzmiQ%2FYwi4exKQnasV%2FXKJsjtrOFvdkgZ1K0MMKkpIipoYUzJKumiUvmtI5Q5LEBZKa0MXK9MZihmzlO87te3dlO7A82S57Qd9Q42J40wlXNdpAptpwznAyWFnm51aNbi0E6p6G9CZD5%2FW%2F0wX1bD8P6M4oIvpmtbBVPDsI0ChAWtYRrKlCyOxAO%2F1r22uCvjpAL9PmrE3nT6EO%2BOlFetlvG5XI%2BZ5sjCrOo3JAuUZgPSfLDOKdK3YaH5zwk13PafgBlDlOVTmWSrEBntStDQ3eBoDxOp%2ByTXct3nyhZjjka7pptyOjEgVdvJCPo4kgNdNwvAJ%2BZV0d3ucX28N%2BZPtWxlTHFBQGZeL96TdcEkifBRDR4KnqdzXLUMNuXoGjVEfj%2BFos4XOFHenQk1UwWVwmU%2BzVoDprrt3TVzeOV%2BfgWVrefM1fV9B%2F5QUaJTxjTdfiZBOTWJt7oEnHjalDDQxwIh7Ec0r3qrMyxE23cE0DqH4qPI22L82qkDiHTtiS6r6s%2FumJINtMjWXDRdWt%2FfXYyvPXqYYJdPkuIcSTyxRsoumbVcfrfpcqt35MKqZtX5K%2Fco7NG73b%2FcVS%2FHjAzF86o4x4srsgNCXdWpTI0Z0oHVOeeFWeCzWK26uN24fYO1cBQ8iq2zX1vuSG78Z896mKUJ54lyf2uQMN7OEKEg%2B%2BviTgJkW%2BT7zc4j5T4sDokY2%2BIDX3PU3%2FoXiD8O%2FnCck9%2B7JPPYXrPCs0O8UMFgF2uxRFjH7orI1suMWIQuFiJ9jWWLQT%2FkdIXNMYdrGgaqvTBcYvyW2oRf7BBie%2FbLHxUWTTts6HtulxHfiroV5lQCnFkjUAvT%2BMP5AkXdjHCbWZ26G6v%2FZ%2Fb75YIEeaH7n1pYG8zLUu4aVl%2BafFyldRZsiYV5%2Fr44Ic91zGBQUXphebRBU031%2BRsZx3FjnBOn9u%2FClMuwDftNTvCJwbkX7smNaOu%2BJtsOa7Z4jGJkkXF%2FgqqadJIRCDTQVEhw%2Bi45mi%2BnbTAZt37WHkMWV6Zy18qJH7XFecCG9l0F9oKwEE570gXB5vrhoLv7HO0KgGBbRNf%2BzI6elpLcofjReqnC%2FeiW3U1ya3yGXGH6g0BNMoDqkXnc95puHvuSyFU58P%2F4vD%2BWGHBk1uOxCmb7kSguCdxG230bWY9UyNb4rpeFop37XpXu%2BFkf%2BzNb4OUPRrjml4OJLGaPd%2Bps%3D18KiGUf4)


![image](https://github.com/user-attachments/assets/7d2c94e8-2cd1-4fba-be88-4c701fd16cd3)



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
