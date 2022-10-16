# Manage Savings
!> This page can only be accessed by the `Admin`, `Treasurer` or member with the `finance_read_all` permission.

This module provides the treasurer with the ability to be able to add contributions for members or to edit existing contributions.


## Accessing the Manage Savings module

If your account has the required authorization (Committee member or `finance_read_all` permission) you can access the manage savings module in one of two ways:

1. Click on the three vertical dot menu on the Savings page and select the `Manage Mode` option

<p align="center">
    <img src="images/3.1.2_Manage_Savings_Page.png" width="600px" style="object-fit:contain" alt="Manage Savings Page">
</p>

2. Alternatively, you can access the module by clicking on the `Manage Savings` button located in the Quick menu in the [Top Banner arear](access-the-site/navigate-the-app?id=the-top-banner-area)


<p align="center">
    <img src="images/3.2_Manage_savings_quick_menu.png"  width="600px" style="object-fit:contain" alt="Manage Savings Menu">
</p>

The Manage Savings module page displays the list of member transactions, a section on savings totals and a section on the monthly chart of all contributions.

<p align="center">
    <img src="images/3.3_Manage_Savings_Page.png" height="400px" style="object-fit:contain" alt="Manage Savings Page">
</p>

## Edit Savings Transaction
- From the `Manage Savings` landing page, click on a Savings record to view its details.
- The `Edit Payment` dialog page is displayed with the Savings details. The details of the fields on the dialog are as follows:
    1. `Transaction Date` - A text field to capture the date when the transaction happened.
    1. `Amount` - The cash amount for the transaction.
    1. `Account` - A drop down field to select the member account associated with the savings transaction
    1. `Ref Voucher` - This is a text field that is used by some club to attach a reference voucher to a transaction.
    1. `Description` - A memo field that is used to capture any additional free text information about the transaction.
    1. `Arrears` - This line will only appear if the [Track arrears](admin-modules/app-settings?id=system-will-track-arrears) setting is turned on. It indicates the amount that the member owes in arrears. Clicking on it will open the [Arrears](user-modules/arrears.md) module.


<p align="center"> 
    <img src="images/3.3.1_Edit_Savings_Page.png"  height="400px" alt="Edit Savings Page">
</p>

## Manage Savings options

Click on the three vertical dot menu on the Manage Savings page and select any of the following options:

<p align="center">
    <img src="images/3.1.4_Manage_Savings_Menu.png" height="400px" style="object-fit:contain;" alt="Manage Savings Menu Options">
</p>

### New Savings
- `New Savings` option is used to create a new savings transaction.
- The fields are exactly the same as described in the `Edit Savings Trnasaction` section above.

<p align="center">
    <img src="images/3.3.4_New_Savings.png" height="400px" alt="New Savings">
</p>

### New Withdrawal
- `New Withdrawal` option is used to create a new withdrawal transaction.
- The fields are exactly the same as described in the `Edit Savings Trnasaction` section above.
- The difference with the options above is that the amount is deducted rather than added.

<p align="center">
    <img src="images/3.3.4_New_Withdrawal.png" height="400px" alt="New Savings Withdrawal">
</p>

### New Transfer
`New Transfer` option is used to create a new transfer between two members
<p align="center">
    <img src="images/3.3.4_New_Transfer.png" height="400px" alt="New Savings Transfer">
</p>

- The difference with the `New Savings` and `New Withdrawal` options is that there is a FROM field and a TO field. The amount is deducted from the FROM account and added to the TO account.
- For the TO account, in addition to Member Savings accounts, money cn also be transfered to the following accounts:
    - The corresponding loan account of the FROM account (to pay outstanding loans with existing savings).
    - Share Capital account.

### Close Manage Mode
`Close Manage Mode` option to go back to the savings page
  

## Savings Documents
Each Savings record has the abilty to load associated documents (e.g. Bank Deposit slip etc.). 

<p align="center">
    <img src="images/3.3.2_Edit_Savings_Documents.png" height="400px" alt="Edit Savings Documents">
</p>

1. From the `Manage Savings` landing page, click on an Savings record to view its details.
1. The `Edit Payment` dialog page is displayed with the Savings details.
1. Click on the `Documents` Tab to view the transactions.

Details on adding and working with documents can be found on the [`Documents`](user-modules/documents.md) page.


