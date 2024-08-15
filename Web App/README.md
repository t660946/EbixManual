# Ebix Mobile Application

## Master Configuraion Index
1. System Setup
    1. [Organization](#organizations)
    1. [Portfolios](#portfolios)
    1. [Products](#products)
    1. Buckets
    1. Fees
    1. Currencies
    1. Reasons
    1. Transactions
    1. Employers
    1. Block Codes
1. [System Parameters](#system-parameters)
    1. [System](#system)
        - [Allocation Types](#allocation-types)
        - Allocation Base
        - Availability Hierarchy
        - EOD Process Statuses
        - Escalation Types
        - Dedupe Identification Types
        - Allocation Logic
        - Allocation Category
        - Authroization Types
        - PTP Statuses
        - Fee Request Types
        - Collateral Tracking Level
        - Fee Status
        - Sort Criteria
        - Amt Convert Operators
        - RPS Statuses
        - Calculation Types
        - Account Statuses
        - CNI Statuses
        - Excel Upload Status
        - Receipt Transactions
        - Receipt Statuses
        - CNI Search XREF
        - Receipt Type
        - Income TaxID Type
    1. Admin
        - Global Parameters
        - Request Type
        - Report Generation Parameters
        - RPS Parameter
        - EOD Process Controls
        - Password Policy
        - Communication Class
        - Relationship
        - Address Type
        - Communication Type
        - Mail Categories
        - EOD Interface
        - Bad Address Markings
        - Market Segment
        - Mail Template
        - Receipt Categories
        - Mail Types
        - Report Output Formats
        - Report Scheduling Frequency
        - Dailer Jobs
        - CSV Record Type
        - Dialer Campaign
        - CSV Delimiters
        - Report Column QUalifier
        - Mail Configuration
        - Time Zone
        - Login Failure Reason
        - CNI Types
        - Deposit Slip Type
        - Receipt Amount Limit
        - Deposit Limit
    1. Follow Up
        - Mobile App Params
        - Collector Categories
        - Collector Types
        - Agency Categories
        - Agency Types
        - Help Script Category
        - [Group Types](#group-types)
        - Action Category
        - Mode of Contact
        - Place of Contact
        - Notes Types
        - Reason Types
        - Asset Condition
        - Valuer Type
        - Payment Frequencies
        - Workflow Events
        - [Delegation Codes](#delegation-codes)
        - Default Collector Profile
        - BSC Calculation Methods
        - Workflow Types
    1. Legacy
        - Transaction Types
        - Card Statuses
        - Resolution Statuses
        - Receipt Code
        - Card Types
        - Action Status
        - Payment Head Group
        - Mail Server
        - FTP Server
        - Letter Server
        - SMS Server
        - External Upload
    1. [Business Unit Wise](#business-unit-wise)
        - [Weekly Holiday](#weekly-holiday)
        - [Document Type](#document-type)
        - [Product Type](#product-type)
        - [Product Categories](#product-categories)
1. Business Unit (Global Level Parameters)
    1. Host Code   
    1. Business Unit Setup
        - [Business Unit Criteria](#business-unit-criteria)
        - [Business Unit Area Code](#business-unit-area-code)
        - [Business Unit Holiday](#business-unit-holiday)
        - [Business Unit Parameters](#business-unit-parameters)
        - [Business Unit Strategy manager](#business-unit-strategy-manager)
        - [Business Unit Policy Rules](#business-unit-policy-rules)
        - [Business Unit Polices](#business-unit-polices)
            - Promise Policy
            - Authorization Policy
            - Waiver Policy
            - Exclusion Policy
            - Settlement Policy
            - Fee Charge Policy
        - Non Members
        - Host Code
        - [Delegation](#business-unit-delegation)

    1. Portfolios
    1. Products
        - Product Code
        - Product Type
        - Product Category
1. User Management

1. [Groups](#groups)    
    1. [Group Parameters](#group-parameters)
    1. [Group Criteria](#group-criteria)
    1. [Group Allocation](#group-allocation)
    1. [Group Non Members](#group-non-members)
    1. Group Performance Summary View
    1. [Group Priorities](#group-priorities)
    1. [Group Sequence](#group-sequence)
    1. [Group Advanced](#group-advanced)
    1. [Group Dialer](#group-dialer)
    1. [Workflow Groups](#workflow-groups)
    1. [Group Rule](#group-rule)
    1. [Group Delegation](#group-delegation)
1. [Strategy](#strategy)
    1. [Segmentation](#segmentation)
    1. [Dunning / Mail Master](#dunning--mail-master)
    1. [Strategy Actions](#strategy-actions)
    1. [Strategy Action Limits](#strategy-action-limits)
    1. [Collection Strategy](#collection-strategy)
    1. [Collection Strategy - Add Schedule](#collection-strategy---add-schedule)
    1. [Collection Strategy - Add Rule](#collection-strategy---add-rule)

1. Allocation

1. [Workflow](#workflow)
    1. Workflow Configurations
        1. [Phases](#phases)
        1. [Workflow Management](#workflow-management)
        1. [Action Types](#action-types)
        1. [Result Categories](#result-categories)
        1. [Global States](#global-states)
        1. [Global Actions](#global-actions)
        1. [Global Results](#global-results)
        1. [Workflow Rules](#workflow-rules)
    1. Workflow List 
        1. Early
        1. Late
        1. Settlement
1. [Other Configurations](#other-configurations)
    1. [Rules Configuration](#rule-configuration)
    1. Buckets
___

## System Setup

### Organizations
**Path:** Configuration --> System Setup --> Organizations

![Organizations](/Web%20App/Images/System%20Setup/Organization.png)

### Portfolios
**Path:** Configurations --> System Setup --> Portfolios

![Portfolios](/Web%20App/Images/System%20Setup/Portfolios.png)

### Products
**Description:** One Portfolios can have multiple Products. The Products defined here are used for categorization of portfolio into smaller groups.
**Path:** Configurations --> System Setup --> Products 

![Products](/Web%20App/Images/System%20Setup/Products.png)

### Buckets
**Description:** One Portfolio consists of multiple Buckets and the Buckets are based on Overdue Days.
**Path:** Configurations --> System Setup --> Buckets

![Bucekts](/Web%20App/Images/System%20Setup/Buckets.png)

### Fees
**Description:** This master allows you to define fee codes for the predefined Fee Type. In addition to configuring fees that can be charged or waived, you can also map the respective payment heads to the fee. All the fee codes with the same payment heads will be grouped and the same will be used when Settlement is done for an account. If Payment head is not defined against the Fee Code, then system will consider "Other Charges" as default payment head for that fee code.
**Path:** Configurations --> System Setup --> Fees

![Fees](/Web%20App/Images/System%20Setup/Fees.png)

### Reasons
**Description:**
**Path:** Configurations --> System Setup --> Reasons

![Reaons](/Web%20App/Images/System%20Setup/Reasons.png)

#### Fields
**Reason Type:** The reason types are defined in the system through system parameter (Configuration --> System Parameters --> Followup --> Reason Types). 

___
## Business Unit
A Business Unit is an organization or a subset of organization. Every business unit has a supervisor/manager who can configure Strategies, Policies, Holidays, etc which are specific to the business unit and/or can be inherited by the subordinate business unit.

### Business Unit Criteria

### Business Unit Area Code

### Business Unit Holiday
**Path:** Configuration --> Collection Hierarchy --> Business Unit Setup --> Holiday
![Business Unit Holiday](/Web%20App/Images/Business_Unit/BU_Holiday.png)

### Business Unit Parameters
**Description:** Configuration of global level Business-Unit level parameters.
**Path:** Configuration --> Collection Hierarchy --> Business Setup --> Parameters

![Business Unit Parameters](/Web%20App/Images/Business_Unit/BU_Parameters_1.png)

#### Fields
**Branched**
The system displays the arrow that identifies whether the parameter definition is:
- **Red Arrow Forward:** It is branched out at this level as well as at lower level.
- **Red Arrow Up:** At this BU its pointing to parent group, but in lower BU's its branched out.
- **Blue Arrow Forward:** It is branched out to the current level.
- **Blue Arrow UP:** It is pointing to parent group.

**User Group (Access Control)**
Configure Access Control to User Profiles of each Parameter.
![User Group (Access Control)](/Web%20App/Images/Business_Unit/BU_Parameters_2.png)

**Parameter Type**
The Parameter Type can be either of the following types:
- **Boolean expression (Y or N):** Similar to 'Query Builder'
    ![Boolean Expression](/Web%20App/Images/Business_Unit/BU_Parameters_3.png)
    
        Example:
        If a Parameter Code is defined as Area = ‘West’; then for all those cases that satisfy the above defined parameter; 
        the value will be assigned as ‘Y’ else the value returned would be ‘N’.
    
- **Expression:** If the value of a Parameter is fixed expression. Define many expressions and define which expression to use based on criteria. 
    ![Expression](/Web%20App/Images/Business_Unit/BU_Parameters_4.png)

        Example:
        - Expression 1 for cases of portfolio A 
        - Expression 2 for cases of portfolio B

- **Same as another parameter:** The Parameter is defined to be the same as one of the existing parameters.
    ![Same as another parameter](/Web%20App/Images/Business_Unit/BU_Parameters_5.png)

- **List of Values:** Define list of values then the Parameter is selected from the list of values.
![List of Values](/Web%20App/Images/Business_Unit/BU_Parameters_6.png)

**Parameter Details**
The Parameter Details can be defined as the followings:
- Value Range
    ![Valule Range 1](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Value_Range_1.png)
    ![Valule Range 2](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Value_Range_2.png)

- Grid/Matrix
If you want to customize a parameter based on 2 inputs then select Grid/Matrix.
    ![Grid Matrix 1](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Grid_Matrix_1.png)
    ![Grid Matrix 2](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Grid_Matrix_2.png)

- Criteria Based
    ![Criteria Based 1](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Criteria_Based_1.png)
    ![Criteria Based 2](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Criteria_Based_2.png)

- Tabular View
    ![Tabular View 1](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Tabular_View_1.png)
    ![Tabular View 2](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Tabular_View_2.png)

**Calculated by system**
For parameters that need calculation.

<u>Recalculation Options</u>
- Specific Events
- Daily 

![Recalculation Options](/Web%20App/Images/Business_Unit/BU_Parameters_Details_Recalculation_Options.png)

### Business Unit Strategy Manager
**Description:** Mapping Stragegies to Business Unit.
**Path:** Configuration --> Collection Hierarchy --> Business Unit Setup --> Strategy Manager
![Strategy Manager](/Web%20App/Images/Business_Unit/BU_Strategy_Manager_1.png)

### Business Unit Policy Rules
**Description:** Define Policy Rules at Business Unit level.
**Path:** Configuration --> Collection Hierarchy --> Business Unit Setup --> Policy Rules
![BU Policy Rules](/Web%20App/Images/Business_Unit/BU_Policy_Rules_1.png)

Rules Configuration
![Rule Configuration](/Web%20App/Images/Business_Unit/BU_Policy_Rules_Configuration.png)


### Business Unit Policies
**Path:** Configuration --> Collection Hierarchy --> Business Unit Setup --> Policies
![BU Policies 1](/Web%20App/Images/Business_Unit/BU_Policies_1.png)
![BU Policies 2](/Web%20App/Images/Business_Unit/BU_Policies_2.png)
![BU Policies 3](/Web%20App/Images/Business_Unit/BU_Policies_3.png)

### Business Unit Delegation
**Path:** Configuration --> Collection Hierarchy --> Business Unit Setup --> Delegation

![Business Unit Delegation](/Web%20App/Images/Business_Unit/BU_Delegation_1.png)

### Business Unit Wise
#### Weekly Holiday

#### Document Type
**Path:** Configuration --> Parameters --> System Parameters --> Business Unit Wise --> Document Type
![BU Wise Product Categories](/Web%20App/Images/Business_Unit/BU_Wise_Product_Document_Type_1.png)

#### Product Type
**Description:** Configuration of Product Types
**Path:** Configuration --> Parameters --> System Parameters --> Legacy Tab --> Product Types

![Product Type](/Web%20App/Images/Business_Unit/BU_Product_Type_1.png)

#### Product Categories
**Path:** Configuration --> Parameters --> System Parameters --> Business Unit Wise --> Product Categories
![BU Wise Product Categories](/Web%20App/Images/Business_Unit/BU_Wise_Product_Categories_1.png)
___

## System Parameters

### System
#### Allocation Types
**Path:** Configuration --> Parameters -->System Parameters --> System Tab --> Allocation Types 
![System Parameter Allocation Types](/Web%20App/Images/System%20Parameters/Systems/Parameters_System_Allocation_Types_1.png)



### Delegation Codes
**Description:** These are predefined Delegation Codes. 
> These Delegation Codes are non-editable and users are not allow to add or delete the Delegation Codes.

![Delegation Codes](/Web%20App/Images/System%20Parameters/Delegation_Codes_1.png)

**Usage:**
The Delegate Codes are used in:
- [Groups Delegation](#group-delegation)
- [Business Unit Delegation](#business-unit-delegation)

### Group Types
**Description:** Define of Group Types.
**Path:** Configuration --> Parameters --> System Parameters --> Followup Tab --> Group Types
![Group Types](/Web%20App/Images/System%20Parameters/Group_Types_1.png)

## User Management
___

## Groups
Groups are logical organization structure where Collectors/Users are configured based on the Roles that they perform for the group.

![Groups](/Web%20App/Images/Groups/Groups_1.png)
___



### Group Parameters

### Group Criteria
**Description:** Group's Accounts assignment logic. 

**Path:** Configuration --> Collection Hierarchy --> Groups --> Criteria

![Group Criteria](/Web%20App/Images/Groups/Group_Criteria_1.png)

**Fields**
- **Type:** types defined in [Group Types](#group-types). 

### Group Allocation
**Description:**
**Path:** Configuration --> Collection Hierarchy --> Groups --> Allocation

<u>Group Allocation Criterias</u>
1. Criteria-Based Sub Groups
    The Criteria based Sub Groups automatically distributes cases in the selected group to further sub-groups based on criteria. 

    ![Criteria-Based Sub Groups](/Web%20App/Images/Groups/Group_Criteria_Based_Sub_Groups.png)

2. Percentage-Based Sub Groups
    Percentage based Sub-Groups automatically distributes accounts to the sub-groups of the same group randomly based on Percentage.

    ![Percentage-Based Sub Groups](/Web%20App/Images/Groups/Group_Percentage_Based_Sub_Groups.png)

3. Percentage-Based Collector Allocation
    ![Percentage-Based Collector Allocation](/Web%20App/Images/Groups/Group_Percentage_Based_Collector_Allocation.png)

    **Allocation Logic**
    - None - If this option is selected then the accounts will not get allocated amongst the Collectors and would require manual allocation.

    - Max Cases - If this option is selected, then the accounts will be allocated based on the "Max Cases" specified for the Collector. If the total cases allocated to the group are more than the total "Max Cases" configured for all the collectors of the group, then the additional/extra cases of the group will be allocated based on the Overlimit Behavior option selected. 

    - % of New Cases - If the option is selected then the new accounts will be allocated based on the Effective % defined for each collector.

    - % of New Cases + Max Limit - If the option is selected then the new accounts will be allocated based on the Effective % defined for each collector considering the Maximum cases configured for the collector

    - % of Total Cases - If the option is selected then the new accounts + existing accounts total will be considered and the accounts will be allocated based on the Effective % defined for each collector.

    - % of Total Cases + Max Limit - If the option is selected then the new accounts + existing accounts total will be considered and the accounts will be allocated based on the Effective % defined for each collector considering the Maximum cases configured for the collector

    **Allocation Based On**
    This feature helps deciding the parameter based on which accounts can be allocated to the collectors of the group. There are three options available:
    - Outstanding Balance: If this option is selected then the allocation is based on the total outstanding balance.
    - Overdue Amount: If this option is selected then the allocation is based on the amount which is overdue 
    - Number of Cases: If this option is selected then the allocation is done on the basis of number of accounts.  

    **Overlimit Behavior**
    If the cases are beyond the limit allocated then depending on the option selected, system will behave. 
    - Keep Unallocated - The accounts will be allocated to the group but collector will not be allocated to these accounts.
    - Allocate to Exception Collector - The accounts will be allocated to the exception collector.
    - Move to Parent Group - The accounts will be moved to the parent group.

    **Exception Collector**
    If the overlimit behavior is selected as exception collector then select the exception collector from available list.
   
    **Hold Cases in these sub-groups for authorizationbefore further allocation**
    Select this check box to send all the accounts for authorization before they are allocated to the collectors of the sub groups.
    
    **Retain cases in these sub-groups till days from**
    Enter the number of days till when the accounts will remain in the same group from the option selected.
    
    **Continue with round robin allocation among these sub-groups after the retention period** 
    To use the round robin allocation after retention period, select the check box. If the check box is checked and accounts are allocated to the same group after re-queue then new collector will be identified and previous collector will not be working on this account. If the check box is unchecked and accounts are allocated to the same group after re-queue then same collector will be allocated to work on the account.

    > For a group working on Early Collection this can be checked and groups working on Late and Legal Collection, this option can be unchecked. 
    
    **Collector Code**
    The list of collectors will be visible in the grid based on the hierarchy. You can search specific collector by entering the collector code. Click Fetch button to view the result.
    
    You can add the collector using ">>" button and you can remove the collector using "<<" button.

    **Max Cases**
    Maximum number of accounts that can be allocated to a collector of a group.

    **Effective %**
    The percentage of accounts that can be allocated to a collector.


4. Criteria-Based Collector Allocation
    **Allocation Logic**
    This feature helps you to define the logic which would be used for allocation of accounts to the Collectors in the Group. The following options are available:
    - None - If this option is selected then the accounts will not get allocated amongst the Collectors and would require manual allocation.
    - Max Cases - If this option is selected, then the accounts will be allocated based on the "Max Cases" specified for the Collector. If the total cases allocated to the group are more than the total "Max Cases" configured for all the collectors of the group, then the additional/extra cases of the group will be allocated based on the Overlimit Behavior option selected. 
    - % of New Cases - If the option is selected then the new accounts will be allocated based on the Effective % defined for each collector.
    - % of New Cases + Max Limit - If the option is selected then the new accounts will be allocated based on the Effective % defined for each collector considering the Maximum cases configured for the collector
    - % of Total Cases - If the option is selected then the new accounts + existing accounts total will be considered and the accounts will be allocated based on the Effective % defined for each collector.
    - % of Total Cases + Max Limit - If the option is selected then the new accounts + existing accounts total will be considered and the accounts will be allocated based on the Effective % defined for each collector considering the Maximum cases configured for the collector

    **Allocation Based On**
    This feature helps deciding the parameter based on which accounts can be allocated to the collectors of the group. There are three options available:
    - Outstanding Balance: If this option is selected then the allocation is based on the total outstanding balance.
    - Overdue Amount: If this option is selected then the allocation is based on the amount which is overdue 
    - Number of Cases: If this option is selected then the allocation is done on the basis of number of accounts.  

    **Overlimit Behavior**
    If the cases are beyond the limit allocated then depending on the option selected, system will behave. 
    - Keep Unallocated - The accounts will be allocated to the group but collector will not be allocated to these accounts.
    - Allocate to Exception Collector - The accounts will be allocated to the exception collector.
    - Move to Parent Group - The accounts will be moved to the parent group. 
    
    **Exception Collector**
    If the overlimit behavior is selected as exception collector then select the exception collector from available list. <br>
    **Hold Cases in these sub-groups for authorization before further allocation**
    Select this check box to send all the accounts for authorization before they are allocated to the collectors of the sub groups. <br>
    **Retain cases in these sub-groups till days from**
    Enter the number of days till when the accounts will remain in the same group from the option selected activation date. <br>
    **Continue with round robin allocation among these sub-groups after the retention period**
    To use the round robin allocation after retention period, select the check box. If the check box is checked and accounts are allocated to the same group after re-queue then new collector will be identified and previous collector will not be working on this account. If the check box is unchecked and accounts are allocated to the same group after re-queue then same collector will be allocated to work on the account. <br>   

    > For a group working on Early Collection this can be checked and groups working on Late and Legal Collection, this option can be unchecked. 

    **Collector Code**
    The list of collectors will be visible in the grid. You can search specific collector by entering the collector code. Click Fetch button to view the result.<br>

    >You can add the collector using ">>" button and you can remove the collector using "<<" button.<br>  
    
    **Max Cases**
    Enter maximum number of accounts that can be allocated to a collector of a group. <br>  
    **Prefilter**
    Criteria is to be defined. 
    - If criteria is defined then accounts will be allocated to the collector of the selected group.
    - If criteria is not defined the accounts will not be allocated to the collector of the selected group. 
    <br> 

5. Manual Allocation
    The accounts will be allocated to the group but not to the collectors. The accounts should be manually allocated to the members of the group by the supervisor (Push method - Allocation Function / Menu /Upload) or collectors can claim the accounts when followup is taken (Pull method - Dynamic Allocation Stamp Owner on Followup). <br>
    For each of the members you also define the maximum number of cases that can be handled.
    
    ![Manual Allocation](/Web%20App/Images/Groups/Group_Manual_Allocation.png)

### Group Non Members
**Description:** Configuraiton of Non Members. Non Members will get supervisory access to this and all other groups in the below hierarchy.
**Path:** Configuration --> Collection Hierarchy --> Groups --> Non Members

![Group Non Members](/Web%20App/Images/Groups/Group_Non_Member.png)

### Group Priorities
**Description:** Define the priorities based on which the accounts will be prioritized and displayed to the collector using Prompt Mode.
**Path:** Configuraiton --> Collection Hierarchy --> Groups --> Priorities

![Group Priorities](/Web%20App/Images/Groups/Group_Priorities_1.png)

### Group Sequence
**Description:** Configuration of Accounts Sequencing. Based on this configuration, Accounts will be visible accordingly in the Prompt Mode.
**Path:** Configuraiton --> Collection Hierarchy --> Groups --> Sequence

![Group Sequence](/Web%20App/Images/Groups/Group_Sequence_1.png)

### Group Advanced
**Description:** Configuration of Accounts Movement.
**Path:** Configuraiton --> Collection Hierarchy --> Groups --> Advance

![Group Advanced](/Web%20App/Images/Groups/Group_Advance_1.png)

#### Fields
**Automated Reassignment Parameters**
You select the type of criteria to be defined in order to re-assign accounts. Re-assign means moving accounts of same customer. 
- Accept fresh accounts of existing delinquent customers from lower queues: This option helps is moving the accounts of existing delinquent customer from lower level groups to this group (assuming it’s level is higher).  
- Allow automatic reassignment of fresh accounts of existing delinquent customers to higher queues: This option helps is moving the accounts of existing delinquent customer from this group to the groups with higher level.

**Transfer Parameters**
You need to select the type of transfer criteria that needs to be defined at the group level.
- Allow others to transfer accounts in this queue: If this check box is selected, then accounts can be re allocated to this group  
    - Authorization required for Transfer (Access Control): Check box is checked: 
        ```
        Example:
        Logged in user profile is either of PDGIC ADMIN or Supervisor. The user is trying to re-allocate the accounts to PUNE_DTC group. In this case, the transaction will be saved, and authorization will be raised because "Authorization required for Transfer" check box is checked in Group --> Advance screen.
        ```
    - Authorization required for Transfer (Access Control): Check box is un checked: 
        ```
        Example:
        Logged in user profile is other than PDGIC ADMIN or Supervisor. The user is trying to re-allocate the account to PUNE_DTC group. In this case, the transaction will be saved, and re-allocation will be done (As authorization is not required. "Authorization required for Transfer" check box is unchecked in Group --> Advance screen.)
        ```
- Allow transfer of accounts out of this queue: If this check box is selected, then the accounts from this group can be re allocated to other group  <br>
    For each criteria specified above, the conditions can also be specified.

### Group Dialer
**Description:** To setup criteria for groups of accounts to be downloaded as a file for Auto-Dialer.
**Path:** Configuration --> Collection Hierarchy --> Groups --> Dialer
![Group Dialer](/Web%20App/Images/Group_Dialer_1.png)

**Parameters:**
- <u>Do not download accounts for this group to auto-dialer:</u> No cases from the selected group would be downloaded into the file being sent to auto-dialer.

- <u>Download accounts of this group to auto-dialer where:</u> This is used when the cases of the selected group are to be downloaded to the auto-dialer.
    - <u>Global Download Criteria AND:</u> The criteria configured globally using Auto Dialer menu will be considered.

    - <u>Criteria:</u> Pre Filters can be defined in addition to global download criteria.

### Workflow Groups
**Description:** Attaching Workflow to a Group.
> A Group can work on single or multiple Workflows.

**Path:** Configuration --> Collection Hierarchy --> Groups --> Workflows
![Workflow Groups](/Web%20App/Images/Work_Flow_Group_1.png)

> **Note:** 
> - The Workdlows must be defined in the Workflow Master.

### Group Rule
**Description:** Configuration of Rules at Group Level, attaching Rules to a Group.
**Path:** Configuration --> Collectin Hierarchy --> Groups --> Rules

![Group Rule](/Web%20App/Images/Group_Rule_1.png)

### Group Delegation
**Description:** Define allowed Policies of individual Group.
**Path:** Configuration --> Collectin Hierarchy --> Groups --> Delegation

![Group Delegation](/Web%20App/Images/Group_Delegation_1.png)

## Strategy

### Segmentation
**Description:** This screen can be used to configure the Segments based on certain parameters that are defined in the [Parameter Master](#business-unit-parameters).
หน้าจอการสร้าง Segment โดย condition ของ [Business Unit Parameters](#business-unit-parameters) จะเป็นตัวกำหนด Segment
**Path:** Configuration --> Strategy Configuration --> Segmentation

![Strategy Segmentation](/Web%20App/Images/Strategy/Strategy_Segmentation_1.png)

### Dunning / Mail Master
**Description:** This screen allows to configure different type of mail codes which will be used in the application. The templates for the corresponding mail codes will be defined through Manage Template. The mail codes defined here can be Manual or Auto Triggered. The mails defined here will range from soft reminder mails, hard reminder mails, informing the customer about legal notice, repossession mails, internal communication and so on. 
หน้าจอสำหรับการบรหิหารจัดการ Mail (Letter, SMS, Email, Voice Broadcast) และ Template ของ Mail โดยสามารถกำหนดให้ส่ง Mail ได้ทั้งแบบ Manual และ Auto
**Path:** Configuration --> Strategy Configuration --> Dunning --> Mail Master

![Mail Master](/Web%20App/Images/Strategy/Strategy_Dunning_Mail_Master_1.png)

#### Field Description
**Mail Category**
The options available for selection are like Reminder Notification, Adhoc Notification, and so on. There can be multiple mail codes defined for a single category. The values available in this field can differ based on the option added through Configurations --> Legacy Configuration --> System Parameters --> Admin --> Mail Category.
ประเภทของ Mail (Mail Category) โดยสามารถกำหนดประเภทของ Mail ได้จากเมนู Mail Category (onfigurations --> Legacy Configuration --> System Parameters --> Admin --> Mail Category) 
ตัวอย่างของ Mail Category เช่น Reminder Notification, Adhoc Notification เป็นต้น

**Communication Class**
Communication Class จะถูกคอนฟิกที่เมนู Configuration --> System Parameters
Communication มี 3 Class คือ 
- Mandatory - ระบบจะไม่สนใจ Communication Preference ที่ระบุไว้ใน Customer Information และ Mail จะถูก Generate ที่ Account Level
- Promotional - ระบบจะสนใจ Communication Preference ที่ระบุไว้ใน Customer Information และ Mail จะถูก Generate ที่ Account Level
- Informational - ระบบจะสนใจ Communication Preference ที่ระบุไว้ใน Customer Information และ Mail จะถูก Generate ที่ Account Level

**Template**
User สามารถสร้าง Template ได้หลายภาษา

Template มีสถานะ ดังนี้
- Red คือ ยังไม่มี Template
- Blue คือ มี Template แล้ว แต่ยังไม่ได้ Publish
- Green คือ มี Template แล้ว และ Template ถูก Publish แล้ว

### Strategy Actions
**Description:** This screen allows you to define strategy actions. There are three type of actions that can be defined as strategy actions (a) Initiate Workflow (b) Change Workflow (c) Generate Mail. The actions configured as strategy actions can be used in different strategies as per business requirement. 
หน้าจอสำหรับการจัดการ Action ของ Stragegy โดยมีชนิดของ Action ดังนี้
- Initiate Workflow
- Change Workflow
- Generate Mail
**Path:** Configuration --> Strategy Configuration --> Strategy Actions

![Strategy Actions](/Web%20App/Images/Strategy/Strategy_Actions_1.png)

#### Field Descrption
**Action Definition Type**
เป็นตัวกำหนดประเภทของ Action ว่าเป็น Action ประเภทอะไร และจะถูกใช้ตอนกำหนด Rules:
- Generate Mail คือ Action ที่เมื่อถูกกำหนดว่าเป็น Generate Mail จะไปปรากฎให้เลือกว่าเป็น Generate Mail Action ตอนกำหนด Rule
- Initiate Workflow คือ Action ที่เมื่อถูกกำหนดว่าเป็น Initiate Workflow จะไปปรากฎให้เลือกว่าเป็น Initiate Workflow Action ตอนกำหนด Rule
- Change Workflow คือ Action ที่เมื่อถูกกำหนดว่าเป็น Change Workflow จะไปปรากฎให้เลือกว่าเป็น Change Workflow Action ตอนกำหนด Rule

Example:

![Strategy Action Example 1](/Web%20App/Images/Strategy/Strategy_Actions_Example_1.png)
![Strategy Action Example 2](/Web%20App/Images/Strategy/Strategy_Actions_Example_2.png)

The value field depends on the type of action selected.
- If the type is selected as Initiate Workflow/Change Workflow then the values will be fetched from Workflow **Master (Early and Late Workflows)**.
- If the type is selected as Generate Mail, then the values will be fetched from Mail Master. It will display all the Mail Codes that are active in the system.

**Depends On**
กำหนดการขึ้นต่อกันระหว่าง Action โดยเป็นการกำหนด Minimum number of days ระหว่าง Action

Example:
    Action EMAIL2 should be performed only after action SMS1. Then SMS1 is should be configured as dependent action for EMAIL2. 
    Dependency between SMS1 & EMAIL2 is 1 day. Then system ensures that the gap between SMS1 and EMAIL2 is 1 day.

**Successor**
กำหนด Action ที่เป็นตัวแทน คือ ถ้า Action ที่เป็น Successor ถูกทำไปแล้ว Action นี้ไม่ต้องทำ

**Exclude Cases With**
กำหนด Accounts ที่ไม่ต้องทำ
![Strategy Exclude Cases With](/Web%20App/Images/Strategy/Strategy_Actions_Exclude_Cases_With_1.png)

**Include Cases With**
กำหนด Accounts ที่ต้องทำ

**Access Control**
กำหนด Access Profile ของ User ที่สามารถสั่งทำ Action นี้ได้
![Strategy Access Control](/Web%20App/Images/Strategy/Strategy_Access_Control_1.png)

### Strategy Action Limits
**Description:** This function allows you to define limits for [Strategy Actions](#strategy-actions). While Generating Mail / Initiating Workflow / Changing Workflow, the system will check the limits and if limit exceeds, then it will not perform action.
หน้าจอสำหรับกำหนด Limit ของ Action ว่าจะอนุญาติให้มีการ set ค่าต่างๆของ Action ได้มาก/น้อย เพียงใด โดยเมื่อ Startegy มีการเรียก Action ไม่ว่าจะเป็น Generating Mail / Initiating Workflow / Changing Workflow ระบบจำทำการเช็ค Limit ของ Action ที่กำลังทำว่าเกินกว่าที่กำนดไว้หรือไม่ หากเกิน ระบบจะไม่อนุญาติให้ทำ Action นั้นๆ
**Path:** Configuration --> Strategy Configuration --> Strategy Action Limits

![Strategy Action Limits](/Web%20App/Images/Strategy/Strategy_Action_Limits_1.png)
### Fields Description
**Code**
คือ Code จาก [Strategy Action](#strategy-actions)
**Type**
ประเภทของ Action ซึ่งจะมี 3 ประเภทให้เลือกคือ
- Initiate Workflow
- Change Workflow
- Generate Mail; Action ส่ง SMS/Letter/Email
**Segment**
Segment ที่ข้อกำหนดนี้มีผล 
**Product Code**
Product Code ที่ข้อกำหนดนี้มีผล
**Day of Week**
วันในอาทิตย์ทีี่ข้อกำหนดนี้มีผล
**Limits for Collection**
จำนวนครั้งที่ให้ทำ Action นั้นในแต่ละวัน
**Limits for Manual**
จำนวนครั้งที่อนุญาติให้ทำ Action นั้นในแต่ละวัน แบบ Manual
**Limits for Others**
จำนวนครั้งที่อนุญาติให้ทำ Action นั้นในแต่ละวันโดย Source อื่น

### Collection Strategy
**Description:** Collection Strategy คือลำดับของการทำ Action ในแต่ละวัน
**Path:** Configuration --> Strategy Configuration --> Collection Strategies

![Collection Strategy](/Web%20App/Images/Strategy/Strategy_Collection_Strategy_1.png)

#### Collection Strategy - Add Schedule
**Description:** หน้าจอสำหรับการเพิ่ม แก้ไข และลบ Collection Strategy
**Path:** Configuration --> Strategy Configuration --> Collection Strategies --> Add --> Schedule
![Collection Strategy - Add Schedule](/Web%20App/Images/Strategy/Strategy_Add_Schedule_1.png)

**Field Description**
**Action**
เลือก Action ที่สร้างไว้ที่ [Strategy Actions](#strategy-actions)

### Collection Strategy - Add Rule
**Description:** หน้าจอสำหรับการเพิ่ม Rule ของ Strategy
**Path:** Configuration --> Strategy Configuration --> Collection Strategies --> Add --> Schedule --> Rules
![Collection Strategy - Add Rule](/Web%20App/Images/Strategy/Strategy_Add_Rule_1.png)

___

## Allocation
___

## Workflow

### Phases
**Description:** This master allows you to define various phases of the account life cycle. The phases defined will be stamped on the account based on the collection strategy configuration.
**Path:** Configuration --> Workflow Configuration --> Phases

![Workflow Phases](/Web%20App/Images/Workflows/Workflow_Phases_1.png)

### Workflow Management
**Description:** Workflow is defined as sequence of action to be performed to collect the pending dues. Using this screen you can configure Early Collections Workflow and Rules for Late and Legal Workflow.
**Path:** Configuration --> Collection Organization --> Workflow 

![Workflow](/Web%20App/Images/Workflows/Workflow_Workflow_1.png)

### Action Types
**Description:** Define category of Action Types taken in the Workflow.
**Path:** Configuration --> Workflow Configuration --> Action Types

![Workflow Action Types](/Web%20App/Images/Workflows/Workflow_Action_Types_1.png)

### Result Categories
**Description:** This master allows you to maintain various result categories for the results defined through Result Master. The result categories configured as Successful, PTP, Right Party Contacted can be used for calculating collector effectiveness. 
**Path:** Configuration --> Workflow Configuration --> Result Categories

![Workflow Result Categories](/Web%20App/Images/Workflows/Workflow_Workflow_Result_Categories_1.png)

### Global States
**Description:** define the state of the account in early stage workflow. The states defined here will be used for workflow configuration (Workflow Master - States).
**Path:** Configuration --> Workflow Configuration --> Global States

![Workflow Global States](/Web%20App/Images/Workflows/Workflow_Global_States_1.png)

**Usage:**
- Workflow Master - States.

### Global Actions
**Description:** Configuratiion of Actions. These Actions will be used during Follow Up.
หน้าจอสำหรับการกำหนด Actions ซึ่งจะถูกนำไปใช้ตอนการบันทึก Follow Up
**Path:** Configuration --> Workflow Configuration --> Global Action

![Workflow Global Action](/Web%20App/Images/Workflows/Workflow_Global_Action_1.png)

### Global Results
**Description:** Define all the results that will be available to a collector while taking followup on an account.
หน้าจำสำหรับกำหนด Result ที่ Collector สามารถเลือกได้ระหว่างการบันทึก Follow Up 

**Path:** Configuration --> Workflow Configuration --> Global Result

![Workflow Global Result](/Web%20App/Images/Workflows/Workflow_Global_Result_1.png)

#### Fields
**Category**
The values are defined through Configuration --> Workflow Configuration --> [Result Categories](#result-categories).
```
    Example - The collector calls the customer and the call is connected but no one picks up call, or call is connected but wrong number. These are two different results with the same category and hence the category should be defined as "Unsuccessful".
```

### Workflow Rules
**Description:** Configuration of Rules at Workflow Level.

**Path:** Configuration --> Workflow Configuration --> Workflows --> Rules

![Workflow Rules](/Web%20App/Images/Rules/Rule_Workflow_Rules_1.png)

#### Field Description
**Description:** The Description created during Policy Rule will be displayed.
___

## Other Configurations
___
### Rule Configuration
**Description:** หน้าจอจัดการ Configuration ของ Rules
![Rule Configuration](/Web%20App/Images/Rules/Rule_Configuration_1.png)

