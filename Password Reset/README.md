### 🔑 Resetting a Forgotten Password via Admin Portal (User: Nick)

In this scenario, the user **Nick** forgot his password and **self-service password reset** is **not enabled**. As a result, the administrator must reset the password through the Microsoft 365 Admin Center. This section demonstrates the end-to-end process — from the failed attempt by the user to successful login after admin reset.

---

#### 1️⃣ Step 1: User Attempts to Reset Password

Nick clicks on the **“Forgot password?”** link at the login page.

<img src="https://github.com/user-attachments/assets/6b9749ee-c3f9-4462-a8e4-be745a9b5ff1" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/64c75455-a1f1-4087-b974-c655eef15d54" width="600"/>

---

#### 2️⃣ Step 2: User Is Instructed to Contact Admin

Because self-service password reset is not enabled, Nick is prompted to **contact the administrator** for help.

<img src="https://github.com/user-attachments/assets/8b8e491b-da99-4086-af33-4ca348d33f39" width="600"/>

---

#### 3️⃣ Step 3: Admin Resets the Password

The admin signs into the Microsoft 365 Admin Center, navigates to **Active Users**, clicks on Nick's profile, and selects the **Reset password** option (key icon).

<img src="https://github.com/user-attachments/assets/8c346792-f0e8-45fc-832c-21389096ac79" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/0bd3db84-7d72-4d80-90e0-8bc0b220ac57" width="600"/>

---

#### 4️⃣ Step 4: User Logs In with New Password

Nick is now able to log in using the **newly assigned password** provided by the admin.

<img src="https://github.com/user-attachments/assets/09ce32c0-edf6-45f6-8eda-1a1949f30e8f" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/bfac2d75-6b8e-4eca-b265-0c2f1d32e62b" width="400"/>
<br/>
<img src="https://github.com/user-attachments/assets/65d4133f-c983-4afb-a77d-3427d1497902" width="600"/>

---

### ✅ Summary:

- User Nick forgot his password and could not reset it on his own.
- The admin successfully reset the password from the admin center.
- Nick was able to **log in again securely** using the new credentials and complete MFA.

---

### 📌 Tip:
To allow users to reset passwords on their own in the future, enable **Self-Service Password Reset (SSPR)** in Azure AD > Password Reset settings.
