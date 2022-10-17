# Member accounts
!> This page can only be accessed by the [`Admin`](#admin-group), [`Treasurer`](#treasurer-group) or member with the [`finance_write`](#finance_write) or [`manage_member`](#manage_member) permissions.

<p align="center">
    <img src="images/9.0_Members_Banner.png" width="600px" style="object-fit:contain" alt="Members Banner">
</p>

This section is used to administer the records of the fund members. There are several sections at the administrator’s disposal.

## Accessing the Member accounts module

To access the Member Accounts module, click on the navigation menu as follows : `Admin Menu` ->`Users` -> `Member Accounts`.

<p align="center">
    <img src="images/9.1_Members_Menu.png" height="400px" style="object-fit:contain" alt="Member Accounts Menu">
</p>

## Member Profiles
The Member Profiles is used to edit an individual member’s profile. It can be used to add new users or edit such records as Name, email address, account, profile image or address.

<!-- ![alt text](../images/9.1_Member_Profiles.png ":size=x300 Member profiles") -->
<p align="center">
    <img src="images/9.1_Member_Profiles.png" height="400px" style="object-fit:contain" alt="Member Profiles">
</p>

### Searching for a member profile

Use the search bar `Search profiles` to find a particular member profile.Type a either a name, email address, phone number or part of the account number in the search field to find what you are looking for.

![alt text](../images/9.1_Profiles_Search.png ":size=x300 Member profiles search")


### Activate or disable Users
To login and use the platform a user's login needs to be active. All user accounts have one of the following statuses:

  - `Active` - This is the status that all members who login to the system will normally have. The status is denoted by the colour green.
  - `Pending` - When a member initially registers into the system the user's account is saved with this status. They will be unable to login until the administrator changes the status to `Active`. The admin cannot manually set an account to this status. The status is denoted by the colour orange.
  - `Disabled` - When a user leaves the investment club, the Administrator can disable the user's login by changing the status to `Disabled`. The member will be unable to login until the administrator changes the status to `Active`. The status is denoted by the colour red.
  
<!-- tabs:start -->
#### **Disable Profile**
![alt text](../images/9.1.2_Disable_Active_Profiles.png ":size=x200 Disable profile")
<div>
To disable a user click on the  users `Activate or Deactivate` button in the `Member Accounts` page. 
</div>

#### **Enable Profile**
![alt text](../images/9.1.3_Enable_Disabled_Profile.png ":size=x200 Enable profile") 
<div>
To activate a user whose status is `pending` or `disabled` use the same users `Activate or Deactivate` button.
</div>
<!-- tabs:end -->

?> **Note** You cannot use the `status` button to change a user's status from something else to `pending`. The `pending` status is reserved for the system. A newly signed up user will automatically be marked as `pending`, until the admin changes this status. 

### Create and edit profiles
![alt text](../images/9.2_New_Profile.png "New profile page")

### Participation Dates
!> **Note** It is important that the Administrator accurately records all members' `Participation Dates` so that arrears and dues can be calculated correctly.

`Participation Dates` provide exact date intervals for which a specific member is expected to be an active, dues paying member of the fund. By recording exact date ranges, the system can then calculate how much everyone is expected to pay and from that determine arrears for each account. Add as many date ranges as necessary to fully describe the members dates of participation, especially if the member had many gaps in their membership.

![alt text](../images/9.2.2_Participation_Dates.png "participation dates")

####	Add Participation dates
To add a participation date click on the `Add Participation date` button.
![alt text](../images/9.2.4_Participation_Dates_Add_Button.png ":size=x100 participation dates tab")

In the `New Date Range` page, provide the following information:

![alt text](../images/9.2.3_Participation_Dates_Add.png ":size=x300 Add participation dates")

- `Name` – This is pre-selected based on the member record under which the add button was clicked. It can not be changed.
- `Joined` – Select the date joined or the date rejoined after the member had previously left.
- `Left` – This is blank if the member is active under this date range.
- `Description` – Additional information regarding the participation date record.
- `Leave Memo` – Additional information that can be added when the participant left.

<!-- ?> **Note** If there are no participation date records that include the current date, the member's account will be marked as `inactive`. -->

### Send Statements
<!-- tabs:start -->
#### **Select Recipients **
 To send multiple email statements use the checkboxes to select the members and the `Email statements` button. 

 ![alt text](../images/9.3.1_Email_Selected.png "Email statements to selected") 
 
 To email statements to an individual member use the Send email button next to each member's name.

![alt text](../images/9.3.2_Email_Individual.png ":size=x100 Email statements to individual")

#### ** Email confirm dialog **
The email dialog is displayed with the member account(s) to send the email statement to. Before sending, you can preview the statement.

![alt text](../images/9.3_Email_Statements.png ":size=x200 send statements dialog")

#### **Preview Statement**
 ![alt text](../images/9.3_Email_Preview.png ":size=x300 statement preview")

<!-- tabs:end -->

## Security Groups

Security groups are used to easily place login accounts into groups for which appropriate permissions can be assigned.

The following Security groups are setup by default for the club

### Admin Group
The Admin Group is designed to provide overall site administartion for the club. By default it has been setup to have all the [`Security permisions`](#security-permissions) described below.

### Committee Group
The committee group is designed to provide visibility to all the club's records without neccessarily being able to add, delete or change the records. This is suited for committee members who are expected to review and discuss all matters of the club and contribute to  working level decisions. By default the committee group has the [`finance_read_all`](#finance_read_all) permission.

### Secretary Group
The committee group is designed to manage the club's documentation. By default the secretary group has the [`manage_docs`](#manage_docs) permission.

### Treasurer Group
The Treasurer group is designed to manage the club's financial information. Treasurers are ususally By default the Treasurer group has the  [`finance_read_all`](#finance_read_all),  [`finance_write`](#finance_write)  [`manage_docs`](#manage_docs) permissions.

### Users Group
The Users group includes all authenticated members of the club. Users can log into the system and view their own finances - savings, loans and arrears. Users can also view fund transactions and fund investments. By Default there are no additional elevated permissions provided to this group. 

<!-- tabs:start -->

#### **Groups List **
<p align="center">
    <img src="images/9.4_Security_groups.png" height="400px" style="object-fit:contain" alt="Security groups">
</p>

#### **Admin Group **

<p align="center">
    <img src="images/9.4_Security_groups_admin.png" height="400px" style="object-fit:contain" alt="Admin Security group">
</p>

#### **Committee Group **

<p align="center">
    <img src="images/9.4_Security_groups_committee.png" height="400px" style="object-fit:contain" alt="Committee Security groups">
</p>

#### **Secretary Group **

<p align="center">
    <img src="images/9.4_Security_groups_secretary.png" height="400px" style="object-fit:contain" alt="Secretary Security groups">
</p>

#### **Treasurer Group **

<p align="center">
    <img src="images/9.4_Security_groups_treasurer.png" height="400px" style="object-fit:contain" alt="Treasurer Security groups">
</p>

#### **Users Group **

<p align="center">
    <img src="images/9.4_Security_groups_user.png" height="400px" style="object-fit:contain" alt="Users Security groups">
</p>


<!-- tabs:end -->

### Security Permissions

#### finance_read_all
Authenticated club members who have this permission can read all the club's financial information. This includes all savings, all loans, all arrears, all dividend distributions and fund transactions. This permission goves read only permission.

#### finance_write
Authenticated club members who have this permission can read and write all the club's financial information. In addition to the [`finance_read_all`](#finance_read_all) permission, members with this permission will be able to add, edit and delete savings records,  loan records, investment records and fund transactions.

#### manage_docs
Authenticated club members who have this permission can add, edit and delete club documents.

#### manage_member
Authenticated club members who have this permission can read and manage member profile information. This includes adding/editing a new profile or a new member account, adding/editing participation dates for a member

#### manage_site
Can read and write site settings that control the functioning of the site. This includes provisioning of permissions to different secirty groups.

## Accounts
All paying members of the fund should be associated with an account. An account is the entity to which savings contributions, loans, and loan payments to or from the fund are attributed to. An account can contain one or more users. Although expected contributions depend on each individual in an account, the amounts are reflected against the account.

![alt text](../images/9.4_Accounts.png ":size=x300 Security groups")
 
