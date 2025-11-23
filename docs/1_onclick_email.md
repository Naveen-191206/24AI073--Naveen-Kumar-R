# 🚀 Manual Workflow Trigger to Send Email using n8n

## 1. 📌 Problem Statement  
Create a workflow in **n8n** that sends an email automatically when the user manually triggers the workflow (by clicking **Execute Workflow**).

---

## 2. 🛠️ Implementation Instructions  

### Step-by-step Setup  
1. Open **n8n** and create a **new workflow**.  
2. Drag and drop the **Manual Trigger** node → It shows as *“When clicking 'Execute workflow'”*.  
3. Add a **Gmail → Send Email** node.  
4. Connect the **Manual Trigger → Gmail node**.  
5. Open the **Gmail node settings** and configure:
   - **Authentication** → Sign in using **OAuth2** or Service Credential.
   - **To**: `recipient@example.com`
   - **Subject**: `Test Email from n8n`
   - **Message/Text**: `Hello from n8n workflow!`
6. Click **Save**.
7. Hit **Execute Workflow** to test.

---

## 3. 📸 Implementation Screenshot  

<img width="919" height="387" alt="Screenshot 2025-11-23 110201" src="https://github.com/user-attachments/assets/83d3a6c2-0417-4b8c-b4f4-57a1f3d6ad60" />


## 1. 📌 Problem Statement  
Create a workflow in **n8n** that sends an email automatically when the user manually triggers the workflow (by clicking **Execute Workflow**).

---

## 2. 🛠️ Implementation Instructions  

### Step-by-step Setup  
1. Open **n8n** and create a **new workflow**.  
2. Drag and drop the **Manual Trigger** node → It shows as *“When clicking 'Execute workflow'”*.  
3. Add a **Gmail → Send Email** node.  
4. Connect the **Manual Trigger → Gmail node**.  
5. Open the **Gmail node settings** and configure:
   - **Authentication** → Sign in using **OAuth2** or Service Credential.
   - **To**: `recipient@example.com`
   - **Subject**: `Test Email from n8n`
   - **Message/Text**: `Hello from n8n workflow!`
6. Click **Save**.
7. Hit **Execute Workflow** to test.

---

## 3. 📸 Implementation Screenshot  

![Uploading Screenshot 2025-11-23 110201.png…]()



---

## 4. 📤 Output Screenshot  
> You can attach the output email screenshot here after execution, e.g.:
> # 🚀 Manual Workflow Trigger to Send Email using n8n

## 1. 📌 Problem Statement  
Create a workflow in **n8n** that sends an email automatically when the user manually triggers the workflow (by clicking **Execute Workflow**).

---

## 2. 🛠️ Implementation Instructions  

### Step-by-step Setup  
1. Open **n8n** and create a **new workflow**.  
