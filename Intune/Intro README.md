# 📘 Intune Device Enrollment & Entra ID Join

This README provides a step-by-step guide to setting up Microsoft Intune device enrollment and joining a Windows machine to Microsoft Entra ID (formerly Azure Active Directory).

---

## 🔐 Step 1: Assign Device Administrator Role

1. Navigate to **Intune > Device Settings**
   
   ![Intune Device Settings Overview](https://github.com/user-attachments/assets/b61454f7-7132-4dbe-b65b-fee6f0832b0f)

2. Click on **Manage additional device administrators**

   ![Manage Additional Device Administrators](https://github.com/user-attachments/assets/2c690918-74d8-4667-92c5-851f2680a213)

3. Add **Mohan** as a device administrator.

   ![Add Mohan](https://github.com/user-attachments/assets/ad5891ff-3b0d-4b20-b496-65582db0bf70)

4. Confirm **Mohan** is added.

   ![Mohan Added](https://github.com/user-attachments/assets/30471b79-9b32-446c-98d9-2dee5f2b7c6d)

---

## ⚙️ Step 2: Configure Device Enrollment Restrictions

5. Navigate to **Device Enrollment > Windows Enrollment**

   ![Device Enrollment Intro](https://github.com/user-attachments/assets/e875e9a1-37de-45e9-8096-e79f9d88ea18)

6. Review or create **Enrollment Restrictions**.

   ![Restrictions Intro](https://github.com/user-attachments/assets/0613ccf0-6bc9-47c5-811e-7835bcc00a2e)

7. Adjust **Platform Settings** as needed.

   ![Platform Restrictions](https://github.com/user-attachments/assets/9a7414d3-4a6c-4072-b91b-9cc6cdb45771)

8. Assign restrictions to a user group (e.g., Mohan).

   ![Assign Group](https://github.com/user-attachments/assets/cd0d8b66-4ea8-430e-b724-c8d07ecb2607)

9. Confirm the restriction settings.

   ![Summary](https://github.com/user-attachments/assets/d30d0ea5-b7f9-4436-abe0-a5629e834ff2)

---

## 💻 Step 3: Join Windows Device to Entra ID

10. On the Windows device, go to:
    - **Settings > Accounts > Access work or school > Connect**

11. Enter the user’s work email.

    ![Enter Email](https://github.com/user-attachments/assets/4c9dc09b-3a15-4feb-baf3-eeb5291a4012)

12. Verify the organization information.

    ![Verify Org](https://github.com/user-attachments/assets/d710cbf0-c647-4358-b336-e7a2801a4195)

13. Let it complete the registration process.

    ![Loading](https://github.com/user-attachments/assets/39a5f573-f317-4f3c-a4b3-11a5b5126739)

14. You should see a success confirmation.

    ![All Set](https://github.com/user-attachments/assets/8068eec1-f911-4ed3-8e51-0f557240d51a)

15. Confirm the device is now listed in Entra ID.

    ![Device in Entra ID](https://github.com/user-attachments/assets/e3fe8e7c-cc65-4240-a99f-385220d8d604)

---

📌 *This setup ensures that user devices are securely enrolled into Intune and connected to your organization through Microsoft Entra ID.*

Let me know if you want this integrated with your larger Office 365 or Teams admin guide!
