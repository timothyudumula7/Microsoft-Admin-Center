## 🔐 Managing Permissions in SharePoint Sites

Even after associating a site with a Hub Site, **each individual site retains its own permission model**. This allows you to tailor access levels depending on your needs.

---

### ⚙️ Step 1: Configure Sharing Settings (Policy Blade)

In the SharePoint Admin Center, you can set sharing permissions for all sites using the **Policy Blade**. This defines the baseline sharing behavior from **most permissive** (anyone with the link) to **least permissive** (only site members).

> ![Sharing settings via policy blade](https://github.com/user-attachments/assets/a9376376-cb34-4504-a8b4-97b8d9a30514)

> **Best Practice:** Use the least permissive setting globally and adjust individually as needed.

---

### 🧾 Step 2: Modify Permissions per Site

You can override the global settings at the **individual site level**.

1. Navigate to **Active Sites** in SharePoint Admin Center.
2. Select the site you want to update.
3. Go to the **Permissions** tab.
4. Edit access settings for members, owners, and visitors.

> ![Adjust site-specific permissions](https://github.com/user-attachments/assets/630a64c4-e709-455a-8cbb-d1c7e907248b)

> **Tip:** This is especially helpful when certain team members need broader access to their own department site without affecting the rest of the hub.

---

## 🔐 Summary

| Scope             | Control Location                  | What You Can Do                          |
|------------------|-----------------------------------|------------------------------------------|
| Global Sharing   | Policy Blade (Admin Center)       | Set max link-sharing policies            |
| Site Permissions | Individual Site Settings          | Control team membership and access       |
| Hub Association  | Admin Center > Hub Site Settings  | Controls branding & navigation only      |

---

✅ Keep your organization secure by combining **least privilege principles** with SharePoint’s flexible permission structure.
