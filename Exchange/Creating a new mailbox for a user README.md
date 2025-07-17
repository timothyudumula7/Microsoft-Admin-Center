# 📬 Microsoft Exchange Online – Mailbox Provisioning Guide

This documentation explains how mailbox creation works in Microsoft Exchange Online (M365) and clarifies why mailboxes cannot be created directly from the Exchange Admin Center.

> 📝 This guide is designed for IT support staff and Microsoft 365 administrators managing user mailboxes in Exchange Online.

---

## 🔒 Why Can't I Create a Mailbox Directly in Exchange?

When you open the **Exchange Admin Center**, you'll notice there is **no option to create a mailbox directly**.

This is by design—mailboxes are tied to Microsoft 365 user accounts. Therefore, the correct way to provision a mailbox is to **create a user** via the **Microsoft 365 Admin Center** first. Once the user is created and licensed, a mailbox is automatically provisioned.

![Exchange Admin Center – No Mailbox Creation Option](https://github.com/user-attachments/assets/206b908f-34cb-429a-80cc-7ecb35835ec0)

---

## ✅ How to Create a Mailbox the Right Way

1. Go to the [Microsoft 365 Admin Center](https://admin.microsoft.com).
2. Navigate to **Users > Active users**.
3. Click **"Add a user"**.
4. Fill out the necessary information.
5. Assign an appropriate **Exchange Online license**.
6. After creation, the user will automatically have a mailbox.

Once this is done, the user will appear under **Recipients > Mailboxes** in the Exchange Admin Center.

![Create User in Microsoft 365 Admin Center](https://github.com/user-attachments/assets/cd4feb89-e237-428e-b19b-7604f7ee265d)

---

## 📦 Summary

| Task                  | Where to Perform         | Notes                                          |
|-----------------------|--------------------------|------------------------------------------------|
| Create Mailbox        | M365 Admin Center        | Must create a user first                       |
| Assign License        | M365 Admin Center        | Ensure license includes Exchange Online        |
| Manage Mailboxes      | Exchange Admin Center    | Only after user is created                     |

---

> For more advanced mailbox tasks (e.g., shared mailboxes, mailbox delegation, PowerShell management), please refer to the future sections of this documentation.
