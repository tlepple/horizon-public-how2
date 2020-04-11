#  CDP Sandbox - Create New Environment 

---
---
### Notes:
---

*  The below videos were recorded in 30 second segments to keep file sizes small (a requirement from github).
*  Follow the instructions in order.

---
---

1.  Navigate to the CDP Sandbox Management Console and click the blue button `Register Environment`:

*  Environment Name --> `zzuser-01`
*  Credential Name  --> `zzuser-sandbox-cred`

---

![](./images/createCDPenv-1.gif)

---


2.  Copy the JSON for the `Create Cross-account Access Policy` and open AWS console in IAM Service and create a new policy:

*  Cross Account Policy Name -->  `zzuser-crossaccount-policy`

---

![](./images/createXactPolicy.gif)

---

3. Save user credentials to your computer.

---

![](./images/saveCredLarge.gif)

---

4.  Add new user to the `Admins` group

![](./images/addUser2AdminsGroupLarge.gif)

---

5.  Verify that your user is part of group `Admins`

*  the previous step will appear to error out but that is a permission screen issue only

![](./images/verifyUserGroupLarge.gif)

---

6.  Create a Key Pair in the EC2 Service

![](./images/createKPlarge.gif)

---
---

####  Return to setup steps:  [Creating your IAM roles from terraform](https://github.com/tlepple/horizon-public/blob/master/aws_readme.md)

