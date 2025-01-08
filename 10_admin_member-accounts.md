@autoHeader:10
# Member accounts
The `Member Accounts` module is used to administer the profile records of the club's members.

> <ins>**NOTE**</ins>\
The **`MEMBER ACCOUNTS`** module can only be accessed by security group members with the [`manage_member`](#manage_member) permissions. This would normally include the [`Admin`](#1031-admin-group) security group.

## ACCESSING MEMBER ACCOUNTS


To access the Member Accounts module, click on the navigation menu as follows : `Admin Menu` ->`Users` -> `Member Accounts`.

<video src="static/video/Member_Accounts.mp4" 
    width="400px" controls autoplay loop>
  <img src="static/images/9.1_Members_Menu.png"/>
</video>

 The landing page of the module is divived into 3 tabs: 
- [**`MEMBER PROFILES`**](#member-profiles) - to edit an individual member’s profile. It can be used to add new members or edit such records as Name, email address, account, profile image or address.
- [**`SECURITY GROUPS`**](#security-groups) - used to easily place login accounts into groups for which appropriate permissions can be assigned.
-  [**`ACCOUNTS`**](#accounts) - a container for member profiles. Allows several member profiles to belong to one account.

## MEMBER PROFILES TAB
The Member Profiles is used to manage an individual member’s login profile. It can be used to add new members or edit such records as Name, email address, account, profile image or address.

### Adding a New Member Profile
Click on the three vertical dot menu on the Member Accounts page and select the **`+ Profile`** option to open the New Profile dialog.

<video src="static/video/Create_New_Member.mp4" 
    width="400px" controls autoplay loop>
  <img src="static/images/9.2_New_Profile.png"/>
</video>

### Searching for a member profile

Use the search bar **`Search Members`** to find a particular member profile.Type a either a name, email address, phone number or part of the account number in the search field to find what you are looking for.

<video src="static/video/Search_Member_Profiles.mp4" 
    width="400px" controls autoplay loop>
  <img src="static/images/9.1_Profiles_search.png"/>
</video>

### Activate or Disable Members
To login and use the platform a member's profile needs to be **`Active`**. All member profiles have one of the following statuses:

  - **`Active`** - This is the status that all members who login to the system will normally have. The status is denoted by the colour green.
  - **`Pending`** - When a member initially registers into the system the member's profile is saved with this status. They will be unable to login until the administrator changes the status to **`Active`**. The admin cannot manually set an account to this status. The status is denoted by the colour orange.
  - **`Disabled`** - When a member leaves the investment club, the Administrator can disable the member's login by changing the status to **`Disabled`**. The member will be unable to login until the administrator changes the status to **`Active`**. The status is denoted by the colour red.

> <ins>**NOTE**</ins> \
> You cannot use the `ENABLE/DISABLE` button to change a member's status from something else to **`Pending`**. The **`Pending`** status is reserved for the system. A newly signed up member will automatically be marked as `pending`, until the admin changes this status. 
  
<video src="static/video/Enable_Disable_Profiles.mp4" 
    width="400px" controls autoplay loop>
  <!-- <img src="static/images/9.1.2_Disable_Active_Profiles.png"/> -->
</video>


<!-- tabs:start >
#### **Disble Profile **
To disable a member click on the  member's `Activate or Deactivate` button in the `Member Accounts` page.

![alt text](static/images/9.1.2_Disable_Active_Profiles.png "Disable Active Profile :size=400").

#### **Enable Profile **
To activate a member whose status is `pending` or `disabled` use the same member's `Activate or Deactivate` button.

![alt text](static/images/9.1.3_Enable_Disabled_Profile.png "Disable Active Profile :size=400").

<!-- tabs:end -->

### Participation Dates
<!-- embed:start:participation dates warning -->

[Participation Dates Warning](static/markdown/participation_dates_warning.md ':include')

<!-- embed:end:participation dates warning -->

**`PARTICIPATION DATES`** are a way to maintain exact date intervals for each individual member. This makes it possible to be able to determine when the respective member is expected to be an active, dues paying member of the fund. 

By recording exact date ranges, the system can then calculate how much everyone is expected to pay and from that determine arrears for each account. 

Add as many date ranges as necessary to fully describe the members dates of participation, especially if the member has had gaps in their membership.

<video src="static/video/Manage_Participation_Dates.mp4" 
    width="400px" controls autoplay loop>
  <img src="static/images/9.2.2_Participation_Dates.png"/>
</video>

####	Add Participation dates
To add a participation date click on the `Add Participation date` button.

<!-- ![alt text](static/images/9.2.4_Participation_Dates_Add_Button.png "Participation Dates Add Button :size=400"). -->

In the `New Date Range` page, provide the following information:


![Add Participation Dates](static/images/9.2.3_Participation_Dates_Add.png " :size=400").

- `Name` – This is pre-selected based on the member record under which the add button was clicked. It can not be changed.
- `Joined` – Select the date joined or the date rejoined after the member had previously left.
- `Left` – This is blank if the member is active under this date range.
- `Description` – Additional information regarding the participation date record.
- `Leave Memo` – Additional information that can be added when the participant left.


### Send Statements
As part of the regular updates given to members, the [**`Treasurer`**](#_1034-treasurer-group) or [**`Admin`**](#_1031-admin-group) can send a statement financial statement by email to any or all members so that they are kept up to date even if he or she does not access the system. Follow the steps outlined in the video below to to send statements by email to the members.

<video src="static/video/Email_Member_Statements.mp4" 
    width="400px" controls autoplay loop>
  <img src="static/images/9.3.0_Statements_Button.png"/>
</video>

<!-- tabs:start >
#### **Initiate  **
Click on the `STATEMENTS` button to start the process.

![alt text](static/images/9.3.0_Statements_Button.png "Statements Button :size=400").


![alt text](static/images/9.3.0_Statements_Loading_Progress.png "Statements Loading :size=400").


#### **Email Controls **
 Once the data is loaded and the controls become available, you can use them to select the profiles that you want to send  email statements to. 

![alt text](static/images/9.3.1_Email_Selected.png "Email Selection Controls :size=400").

#### ** Confirm dialog **
The email dialog is displayed with the member account(s) to send the email statement to. Before sending, you can preview the statement.


![alt text](static/images/9.3_Email_Statements.png "Email Statements Dialog :size=400").

#### **Preview Statement**

![alt text](static/images/9.3_Email_Preview.png "Email Statements preview :size=400").

#### **Send Statement**
When ready use the `Email Statements` -> `Send` buttons to send the statements the the selected members.
 
![alt text](static/images/9.3_Email_Statements_Send.png "Email Statements Send :size=400").
<!-- tabs:end -->

## SECURITY GROUPS TAB

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

<video src="static/video/Manage_Security_Groups.mp4" 
    width="400px" controls autoplay loop>
  <img src="static/images/9.4_Security_groups.png"/>
</video>

<!-- tabs:start >

#### **Groups List **

![alt text](static/images/9.4_Security_groups.png "Security groups :size=400").

#### **Admin Group **

![alt text](static/images/9.4_Security_groups_admin.png "Admin Security group :size=400").

#### **Committee Group **

![alt text](static/images/9.4_Security_groups_committee.png "Committee Security group :size=400").

#### **Secretary Group **

![alt text](static/images/9.4_Security_groups_secretary.png "Secretary Security group :size=400").

#### **Treasurer Group **

![alt text](static/images/9.4_Security_groups_treasurer.png "Treasurer Security group :size=400").

#### **Users Group **

![alt text](static/images/9.4_Security_groups_user.png "Users Security group :size=400").

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

## ACCOUNTS TAB
All paying members of the fund should be associated with an account. An account is the entity to which savings contributions, loans, and loan payments to or from the investment club are attributed to. An account can contain one or more member profiles. Although expected contributions depend on each individual in an account, the amounts and totals are reflected against the account.

![alt text](static/images/9.4_Accounts.png ":size=x300 Security groups")
 
### Adding or Editing an Account
Adding a new Account is usually done while creating a new Member Profile. If necessary, it can also be created from the `New Account` option the three vertical dot selection menu at the top right of the page.

To edit and account, click on the `Edit` button next to the respective Account's record.

<video src="static/video/Manage_Accounts.mp4" 
  width="400px" controls autoplay loop>
  <img src="static/images/9.4_New_Account_Menu.png"/>
</video>
