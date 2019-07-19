# Group-Expense-Tracker
Progressive Web App to keep track of your expenses

## Brief:  
\<app name\> is a group expense tracker app. It is a progressive web app which allows users to organize group expenses, and reimburse debts. It also allows individuals to track their expenses.

## Assumptions:
\<app name\> will be used in android, ios platform
User will install PWA if he wants to use it offline.

## User cases:
- Sign in
- Create group
- View transactions
- Create transaction
- View balance sheet
- Reimburse in app
- Supporting standard payment gateways to reimburse debts

## Requirements
### Functional Requirements
- sign in
  - create account
  - google
   - facebook
- create group
  - add member by username
  - share link to join
- open my group
  - view latest transaction of group members
  - filters for transactions
    - show my transaction
    - sort by
      - title :arrow_up: :arrow_down:
      - amount :arrow_up: :arrow_down:
      - date of creation :arrow_up: :arrow_down:
      - date of expense :arrow_up: :arrow_down:
      - payer :arrow_up: :arrow_down:
    - click to view details and edit if created by the user
    - :heavy_plus_sign: button to add expense
      - title
      - date
      - payer
      - paid for
        - username
        - amount
        - currency
      - image (useful in case of bill, tickets)
   - view balance sheet
      - graphical representation of member status (debt/profit)
      - suggest reimbursement
      - click on suggestion to open payment options
        - cash
          - manually add reimbursement and approve by the reciever
        - paytm
          - carry out transaction using paytm api
          - if successful then automatically add reimbursement and approve
 
 ### Non-functional Requirements
 - option to push notification, email to all members
    
   
  
