# Arrears Module
 if the [Track arrears](admin-modules/app-settings?id=system-will-track-arrears) setting is turned on, the system automatically calculates and tracks how much each club member is supposed to pay every month. The expected amount is compared to the total amount that the member has contributed and if it is less then the club member is in arrears.

!>**Note.** \
For accurate calculation of arrears, every club member must have their [Participation Dates](admin-modules/member-accounts?id=participation-dates) correctly entered by the administrator. Additionally the [Expected Contributions](admin-modules/app-settings?id=expected-monthly-contributions) records must be accurately maintained.

## Accessing the arrears module
>**Note.** \
>For the arrears module to be visible, the system must have the [Track arrears](admin-modules/app-settings?id=system-will-track-arrears) setting turned on. 

The arrears for a member can be accessed in one of two ways:

1. Click on the arrears link from the [Savings](user-modules/savings) page. 

![alt text](../images/3.4_My_Arrears_Link.png ":size=x100 My arrears link")


2. (Requires `finance_read_all` permissions). From the [Manage Savings](admin-modules/manage-savings.md) page do the following:
    - Search for any transaction for the  member that you want to reveiew the arrears. 
    - Click on the transaction to poen the [Edit Payment Dialog](admin-modules/manage-savings?id=edit-savings-transaction).
    - Under the Transaction amount you will find the arrears link
    
![alt text](../images/3.3.2_Edit_Savings_Arrears.png ":size=x200 arrears link from edit savings")


## Arrears Module Tabs

### Arrears

![alt text](../images/3.5_Arrears_Tab.png ":size=x300 Arrears Tab")

### Allocations

![alt text](../images/3.6_Allocations_Tab.png ":size=x300 Allocations Tab")

`Allocations` are useful when a single large payment was made for an account. If the payment is larger than the [expected contribution](admin-modules/app-settings?id=expected-monthly-contributions) for the month, then it will be distributed for several months. The single payment is saved as one contribution. Allocations are then used to apportion the single contribution payment to different months.

The system automatically handles the allocation of payments distrubted accross the months. You can use this tab to track how far ahead or behind the account is with expected payments.