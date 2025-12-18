# Step 1
Created a new workflow with the name provided.

![](/aux/L9/C/Init.png)

# Step 2
Created the initial/trigger node `Webhook` and configured is as provided.

![](/aux/L9/C/WebhookNew.png)

# Step 3
Created a `Code` node after the `Webhook` trigger/initial node and configured is as provided.

![](/aux/L9/C/CodeNew.png)

# Step 4
Created a `Read/Write Files from Disk` node after the `Code` node and configured it as provided.

![](/aux/L9/C/AppendFile.png)

# Step 5
Created a `Respond to Webhook` node after the `Read/Write Files from Disk` node and configured it as provided.

![](/aux/L9/C/WebhookResponse.png)

# Step 6
Used `CUrl` to test the workflow, both with and without the parameter.

> [!NOTE]
> `CUrl` is using `localhost`, because the `n8n` instance is in the same environment as the terminal

![](/aux/L9/C/Execute.png)

# Step 7
Verified that the notes are being saved by opening the file in the editor.

![](/aux/L9/C/Verify.png)

# Step 8

> [!NOTE]
> Workflow activation has been replaced by prod/test system in newer `n8n` versions

Activated/Published the workflow and used `CUrl` to call the production webhook endpoint.

![](/aux/L9/C/Activate.png)
