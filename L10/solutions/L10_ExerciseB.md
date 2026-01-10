# Step 1
Created the workflow.

![](/aux/L10/B/init.png)

# Step 2
Created the Webhook call node and configured as specified.

![](/aux/L10/B/WebhookCall.png)

# Step 3
Created the HTTP request node to `Jina.ai` and configured it.

![](/aux/L10/B/HTTPJina.png)

# Step 4
Created the HTTP request node to `groq` and configured it.

> [!IMPORTANT]
> `n8n` doesn't allow for environment variables to be viewed by end users, the workflow however, can read and use them.

![](/aux/L10/B/HTTPGroq1.png)
![](/aux/L10/B/HTTPGroq2.png)

# Step 5
Created the Respond to Webhook node and configured it as provided.

![](/aux/L10/B/Respond.png)

# Step 6
Used CUrl to test the workflow on the [Elements of Matrix protocol/specification](https://matrix.org/docs/matrix-concepts/elements-of-matrix/).

![](/aux/L10/B/Test.png)
