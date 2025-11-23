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
![Workflow Setup](# 🚀 Manual Workflow Trigger to Send Email using n8n

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
![Workflow Setup](./Screenshot%202025-11-23%20110831.png)

*(This screenshot shows the connected Manual Trigger and Gmail node in n8n.)*

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
