# Task 2 – IAM User Management

## Objective

Create IAM user groups, attach appropriate AWS managed policies, create IAM users, and assign each user to the correct group following AWS security best practices.

---

## Services Used

- AWS IAM (Identity and Access Management)

---

## Implementation Steps

### Step 1: Open AWS IAM Dashboard

Access the AWS IAM service from the AWS Management Console.

![IAM Dashboard](Screenshot%202026-07-15%20113236.png)

---

### Step 2: Create IAM User Groups

Created three IAM user groups:

- Developers
- Billing
- Auditors

![IAM Groups Created](Screenshot%202026-07-15%20113643.png)

---

### Step 3: Attach Permissions to User Groups

Assigned AWS managed policies to each group.

#### Developers Group
- AmazonEC2FullAccess

![Developers Policy](Screenshot%202026-07-15%20113850.png)

#### Billing Group
- Billing

![Billing Policy](Screenshot%202026-07-15%20114102.png)

---

### Step 4: Verify Group Permissions

Verified that all IAM groups have their respective permissions attached.

![Groups with Policies](Screenshot%202026-07-15%20122245.png)

---

### Step 5: Create IAM Users

Created IAM users according to their job roles.

Example: Creating **developer1**

![Create User](Screenshot%202026-07-15%20122534.png)

---

### Step 6: Assign Users to Groups

Assigned each IAM user to the appropriate IAM group.

- developer1 → Developers
- Billing1 → Billing
- auditor1 → Auditors

![Assign User to Group](Screenshot%202026-07-15%20122701.png)

---

### Step 7: Verify IAM Users

Verified that all IAM users were successfully created and added to their respective groups.

![Final IAM Users](Screenshot%202026-07-15%20122724.png)

---

## Result

Successfully implemented IAM User Management by:

- Creating IAM user groups
- Assigning AWS managed policies
- Creating IAM users
- Adding users to the appropriate groups
- Following AWS Identity and Access Management best practices
