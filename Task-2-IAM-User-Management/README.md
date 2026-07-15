# Task 2 – IAM User Management

## Objective

Create IAM user groups, assign appropriate AWS managed policies, create IAM users, and add each user to the appropriate group following AWS security best practices.

---

## Services Used

- AWS IAM (Identity and Access Management)

---

## User Groups Created

| Group Name | Permission |
|------------|------------|
| Developers | AmazonEC2FullAccess |
| Billing | Billing |
| Auditors | ReadOnlyAccess |

---

## IAM Users Created

| User | Group |
|------|-------|
| developer1 | Developers |
| Billing1 | Billing |
| auditor1 | Auditors |

---

## Steps Performed

1. Opened AWS IAM Console.
2. Created three IAM groups:
   - Developers
   - Billing
   - Auditors
3. Attached AWS managed policies to each group.
4. Created three IAM users.
5. Enabled AWS Management Console access.
6. Added each user to the correct IAM group.
7. Verified all users were created successfully.

---

## Screenshots

### 1. IAM Dashboard

![IAM Dashboard](Screenshot1.png)

### 2. IAM Groups Created

![IAM Groups](Screenshot2.png)

### 3. Developers Group Permission

![Developers](Screenshot3.png)

### 4. Billing Group Permission

![Billing](Screenshot4.png)

### 5. Auditors Group Permission

![Auditors](Screenshot5.png)

### 6. IAM Users Created

![Users](Screenshot6.png)

---

## Result

Successfully implemented AWS IAM user management by creating user groups, assigning permissions, creating users, and organizing them according to their roles using AWS IAM best practices.
