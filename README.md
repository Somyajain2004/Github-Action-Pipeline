# Github-Action-Pipeline

This repository contains a basic GitHub Actions workflow that sets up a Node.js environment and prints a greeting message:  
**`Hello from @Somyajain2004`**


### Steps to Trigger the Workflow

1. Go to the **[Actions tab](../../actions)** of this repository.
2. Click on the workflow titled **"Node.js Greet Workflow"** in the left sidebar.
   
   <img src="https://github.com/user-attachments/assets/4ed6d4f1-3c24-4bda-b75a-32ff5f31ea00" width="600"/>
4. Click the **"Run workflow"** own (top right).

   <img src="https://github.com/user-attachments/assets/f536984b-13aa-4ca9-89d7-e92d6ee740f9" width="600"/>
   
6. Select the branch (default is `main`) and click **Run workflow**.

---

## How to Check the Output

After the workflow runs:

1. Click on the latest workflow run (e.g., `#3 Node.js Greet Workflow`).
2. Click on the job titled `greet`.
3. Find and expand the step: **"Log greeting message"**.
4. You will see an output like this:
