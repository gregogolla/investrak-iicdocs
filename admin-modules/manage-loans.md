# Manage Loans
The Manage Loans  module is an extention of the [Loans](user-modules/loans.md) module. IT is used to perform additional functions like approving and disbursing loans.

## Accessing Manage Loans
If your login has the required authorization (Committee Membership or [`finance_read_all`](admin-modules/member-accounts.md#finance_read_all) permissions) then you will be able to access the module  in one of two ways:

1. Click on the three vertical dot menu on the Loans page and select the `Manage Mode` option

<!-- ![alt text](../images/4.6.1_Manage_Loans_menu.png ":size=x150 Manage Lonas menu") -->
<p align="center">
    <img src="images/4.6.1_Manage_Loans_menu.png" height="200px" style="object-fit:contain;" alt="Manage Loans menu">
</p>

2. Alternatively, you can access the module by clicking on the `Manage Loans` button located in the Quick menu in the [Top Banner arear](access-the-site/navigate-the-app?id=the-top-banner-area)

<!-- ![alt text](../images/4.6.2_Manage_Loans_quick_menu.png ":size=x150 Manage Loans menu") -->

<p align="center">
    <img src="images/4.6.2_Manage_Loans_quick_menu.png"  width="600px" style="object-fit:contain" alt="Manage Loans Menu">
</p>

The Manage Loans module page displays the list of individual loan applications and a section showing a chart of top borrowers.

<!-- ![alt text](../images/4.6.3_Manage_Loans_page.png ":size=x300 Manage Loans page") -->
<p align="center">
    <img src="images/4.6.3_Manage_Loans_page.png"  width="600px" style="object-fit:contain" alt="Manage Loans Page">
</p>

## Approving a loan
!> This function can only be done by club committee

After a member has submitted a loan request, an email notification will go out to all committee members. At least two committee members are required to approve the loan before it can be marked as approved. 

![alt text](../images/4.4.3_Apply_Loan_Approval.png ":size=x300 Apply Loan approval")

The system expects at least two committe members to approve a loan. Once there are two approvals the loan approval status will automatically change form '`Pending` to `Approved`.

![alt text](../images/4.4.3.2_Loan_Approved.png ":size=x300 Loan Approved")

## Disbursing a loan
!> This function can only be done by club treasurer

After a loan has been marked as approved, the treasurer will then disburse the loan. The process of disbursement will add the various transactions (loan amount as well as any of the applied interest, processing fees and/or insurance charges).
!>For Treasurers only

![alt text](../images/4.4.4_Apply_Loan_Disburse.png ":size=x300 Apply Loan disburse")

>**Note** \
After a lona has been disbursed all loan  records (including type, charges and guarantors) approval will become read-only

## Loan Transactions
Once a loan has been approved and disbursed you can track the individual transactions on this tab
![alt text](../images/4.4.5_Loan_Transactions.png ":size=x300 Apply Loan disburse")