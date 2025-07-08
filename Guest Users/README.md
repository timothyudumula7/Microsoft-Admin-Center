### 🤝 Creating Guest Users in Microsoft Entra ID (Azure AD)

In Microsoft 365, **guest users** can only be added via **Microsoft Entra ID** (formerly Azure Active Directory). These users are external collaborators — often contractors, partners, or vendors — who need limited access to internal resources.

In this example, we demonstrate:
- Navigating to Entra ID
- Adding guest users by **manual creation** and **email invitation**
- Verifying their presence in the directory

---

#### 1️⃣ Step 1: Navigate to Entra ID

From the **Microsoft 365 Admin Center**, go to **Microsoft Entra ID (Azure AD)**.  
You can choose to either:
- **Invite** a guest via email  
- Or **manually create** a guest profile

<img src="https://github.com/user-attachments/assets/f99e3db3-1b43-4987-afed-70e955e8b959" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/a96080af-e205-4df6-ac4a-186e275d89ed" width="600"/>

---

#### 2️⃣ Step 2: Manually Create Guest User – Kim Green

We manually create a guest user named **Kim Green** by filling out her profile in Entra ID.

<img src="https://github.com/user-attachments/assets/2d1585f8-0143-48fb-8bab-c1aed28b8ca1" width="600"/>

---

#### 3️⃣ Step 3: Confirmation of Creation

The system confirms successful creation of Kim Green.

<img src="https://github.com/user-attachments/assets/36a791a3-be87-4814-8722-b794255fb82d" width="600"/>

---

#### 4️⃣ Step 4: View All Guest Users

After both methods are used, you can now see:
- **Kim Green** (manually created)
- **Chris** (added via invitation)

Both are visible under the **"Users > Guest users"** tab in Entra ID.

<img src="https://github.com/user-attachments/assets/d99fed89-5202-47ec-911b-d11fe20aa2c1" width="600"/>

---

### ✅ Summary:

| Method | Description |
|--------|-------------|
| Invite Guest | Sends an email invite to an external user |
| Manual Guest Creation | Adds a guest profile without email confirmation |
| Portal | All guest users are managed via **Microsoft Entra ID** |

---

### 📌 Tip:
Guest users can be granted access to:
- Microsoft Teams
- SharePoint files
- Specific apps (with assigned roles)

Manage their permissions via **Groups**, **App assignments**, or **Conditional Access** after they are added.
