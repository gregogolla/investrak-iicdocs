# System Settings module
!> This page can only be accessed by the `Admin` or member with the `manage_site` permissions.

This module is used to administer the club specific settings. 

## Accessing the Systems Setting module
To access the  module, click on the navigation menu as follows : `Admin Menu` ->`System` ->    `App Settings`.

![alt text](images/11.1_System_Settings_Menu.png "System Settings menu")

There are several sections at the administrator’s disposal.

## Club Details
![alt text](images/11.2_Club_details.png "System Settings menu")

The `Club Details` is used to set  the name of the Club. The club name that is set in this section is what appears on the top banner of the application. There are 2 settings that can be changed:

1. `Club Name` - Will be displayed in the top banner of the screen as well as the 'from' field in notification emails.

1. `Abbreviated Name` - Will be name displayed on the top banner for smaller screens like mobile.

## Expected Monthly Contributions

!> **Caution** It is important that the administrator accurately records all `Expected Monthly Contribution` date ranges with no overlaps or gaps so that arrears and dues can be calculated correctly.

![alt text](images/11.3_Expected_monthly.png "Expected monthly payments")


The Expected monthly contribtions section enables to administrator to set  the data ranges and corresponding amounts for the date ranges that the system expects savings contributions from each dues paying member. The ranges are used to determine each members expected contribution and to calculate arrears. Comparing with each member's [participation dates](member-accounts.md?id=participation-dates), the system knows how much to expect every month.

### System will track arrears 
![alt text](images/11.2.2_Track_Arrears_Button.png "Track Arrears Button")

This is a master button to set whether or not the club will track arrears. If this is turned off, then no date ranges are expected and it is assumed that there is no required amount that the club expects from members.

### Date Range Table

If the system has been set to track arrears, the administrator will use this table to add, delete and maintain the range of dates and how much is expected monthly for each active member.

![alt text](images/11.3.1_Date_Range_Table.png "Date Range table")

### Edit Date Range
The Date ranges are added and managed using the `Edit Date Range` form. The form has the following fields: 

![alt text](images/11.3_Edit_Date_Range.png "Edit Date Ranges")

1. `Amount` - The amount that is expected every month for the period.
1. `Start` - The earliest month in the period. Note that these are stored as whole months.
1. `End` - The latest month in the period. This is left blank for the current on-going period.
1. `Description` - any additional information that provides additional information for the date range


## Loan Settings
This section is used by the administrator to set the default options that are applied to loans that the club provides to its members.

![alt text](images/11.4_Loan_settings.png "Loan Settings")

The following settings are availbale on how to manage loans:

1. `Interest Type` - There are two interest types - `Compound Interest` and `Simple Interest`. The Interest applied to loans will be determined by the interst type of the loan.

1. `Interest Rate` - This is the default Annual Percentage Rate (APR) that is applied to a loan. This setting only provides the default rate. The default rate can be changed for each individual loan by the loan committee or treasurer.

1. `Application fee Rate` - Some clubs charge an application fee when a loan is disbursed. Use the check box so that the system will charge a lona application fee. Use the Text Box to enter the rate (as a percentage of the loan amount) at which the fee will be charged.

1. `Insurance fee Rate` -  Some clubs charge an Insurance fee when a loan is disbursed. Use the check box so that the system will charge a lona application fee. Use the text Box to enter the rate (as a percentage of the loan amount) at which the insurance fee will be charged.