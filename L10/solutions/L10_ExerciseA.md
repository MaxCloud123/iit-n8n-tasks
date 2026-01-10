# Step 1
Created the new workflow.

![](/aux/L10/A/Init.png)

# Step 2
Created the webhook node and configured it.

![](/aux/L10/A/WebhookCall.png)

# Step 3
Created the HTTP request node and configured it.

> [!NOTE]
> `n8n` does not allow environment variables to be shown in node edits,
> but during executions, code does have full access to them.

![](/aux/L10/A/HTTPReq.png)

# Step 4
Created and configured Modify Fields (Set) and Repond to webhook nodes.

> [!IMPORTANT]
> A node named exactly "Set" doesn't exist, so the "Modify Fields" node has been chosen instead
> as it's a close match.

> [!WARNING]
> Set field mappings expressions had to be slightly changed in order for them to work correctly.

![](/aux/L10/A/SetNode.png)
![](/aux/L10/A/RespondNode.png)

# Step 5
Used CUrl to test the workflow.

> [!IMPORTANT]
> The CUrl commands had to be modified, because the instructions in the exercise make the workflow only accept search query parameters.

![](/aux/L10/A/Test.png)

# Step 6
Activated/Published the workflow and used the production URL via CUrl.

> [!NOTE]
> As mentioned in all previous week solutions, workflow activation has been replaced by publishing.

![](/aux/L10/A/Activated.png)
