# Step 1
Created a new workflow with the name provided.

![](/aux/L9/B/Init.png)

# Step 2
Created a new initial/trigger `Webhook` node with provided configuration.

![](/aux/L9/B/WebhookNew.png)

# Step 3
Created a new `HTTP request` node after the `Webhook` trigger, and configured it as provided.

![](/aux/L9/B/HTTPNew.png)

# Step 4
Created new `Respond to Webhook` node after the `HTTP Request` node, and configured it as provided.

![](/aux/L9/B/WebhookRespond.png)

# Step 5
Used `CUrl` to trigger the webhook, to test the workflow.

> [!NOTE]
> `CUrl` uses `localhost`, because the `n8n` instance is in the same environment as the terminal

> [!CAUTION]
> During testing the domain `quotes.domiadi.com` didn't exist.
> As such the correct response couldn't be reproduced

![](/aux/L9/B/Test.png)

# Step 6
> [!IMPORTANT]
> Workflow activation has been replaced by prod/testing system in newer versions

Published/Activated the workflow and used `CUrl` to call the permanent/production webhook endpoint.

![](/aux/L9/B/Activate.png)
