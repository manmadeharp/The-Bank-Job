# the-bank-job

Before we even start, Git is essential in this project. It must be used throughout with branches, issues etc. Figma is essential for design, it must be used before coding.

You have been hired by the owner of a international bank. They have many services that they offer to the public:

- Current Accounts
- Savings Accounts **(No overdraft facility)**
- Joint Accounts **with an already existing customer**
- Junior Accounts **(No overdraft facility)**
- Mortgages **(Minimum 10-year contract)**
- Interest-Loans **(Low interest)**
- Payday-Loans **(scandalously high interest)**

---

## Things to think about

1. A customer may want to select one or multiple options when signing up. They will be assigned a customer number and an **account number** with a **sort code** for each account that they take out
2. They need to be able to withdraw, deposit, check their balance, change their pin number for the accounts that they have access to
3. An overdraft will add interest for each day that it is active. You can choose the interest rates
4. A junior account can be taken out in a child's name but will be associated with an adult current / savings account. It cannot be opened on its own.
5. An interest-loan / payday-loan can only be taken out if they have a current or savings account.
6. Hashing passwords
7. Sessions (security restrictions)
8. Error handling
9. User interface / Experience
10. Testing
11. Documentation (User guide / walkthrough && readme)
12. Deployment via Heroku

---

## The customer

- The customer should be able to signup for one / multiple accounts with the bank, if they so wish. The process of signing them up will take the usual details down, all fabricated, of course. Upon registration, the customer will be assigned a customer number and will be asked to save a password related to the customer number with a security question.

- The customer can forget their password and use the **password reset** feature which will ask them for their customer number and 2 of the following:
  - DOB
  - first line of address and postcode
  - security question
- The customer, upon signing in, will be presented with their accounts in a bitesize display. If they wish to see activity on a particular account, they can access that by clicking on the account they'd like to see.

---

## The Admin portal

- Approve / Deny / Send back account status
- Approval of overdraft
- View accounts and details
- Mortgage approval / deny etc.
- Delete / Modify accounts
- Lock accounts (suspicious activity etc.)
- Report on new customers, finances, etc.

## Technologies needed:

- Vanilla JS
- React
- Node w/ Express
- SQL

## Readme && instructions

- Description
- Goals and aims
- Contributors
- Technology used

```
npm i // for all dependencies to be installed
any .env variables
```
