# Exercise A
## Step 1
Created the new workflow.

![](/aux/L10/A/Init.png)

## Step 2
Created the webhook node and configured it.

![](/aux/L10/A/WebhookCall.png)

## Step 3
Created the HTTP request node and configured it.

> [!NOTE]
> `n8n` does not allow environment variables to be shown in node edits,
> but during executions, code does have full access to them.

![](/aux/L10/A/HTTPReq.png)

## Step 4
Created and configured Modify Fields (Set) and Repond to webhook nodes.

> [!IMPORTANT]
> A node named exactly "Set" doesn't exist, so the "Modify Fields" node has been chosen instead
> as it's a close match.

> [!WARNING]
> Set field mappings expressions had to be slightly changed in order for them to work correctly.

![](/aux/L10/A/SetNode.png)
![](/aux/L10/A/RespondNode.png)

## Step 5
Used CUrl to test the workflow.

> [!IMPORTANT]
> The CUrl commands had to be modified, because the instructions in the exercise make the workflow only accept search query parameters.

![](/aux/L10/A/Test.png)

## Step 6
Activated/Published the workflow and used the production URL via CUrl.

> [!NOTE]
> As mentioned in all previous week solutions, workflow activation has been replaced by publishing.

![](/aux/L10/A/Activated.png)

# Exercise B
## Step 1
Created the workflow and named it as instructed.

![](/aux/L10/B/Init.png)

## Step 2
Created the Webhook call node and configured as specified.

![](/aux/L10/B/WebhookCall.png)

## Step 3
Created the HTTP request node to `Jina.ai` and configured it.

![](/aux/L10/B/HTTPJina.png)

## Step 4
Created the HTTP request node to `groq` and configured it.

> [!IMPORTANT]
> `n8n` doesn't allow for environment variables to be viewed by end users, the workflow however, can read and use them.

![](/aux/L10/B/HTTPGroq1.png)
![](/aux/L10/B/HTTPGroq2.png)

## Step 5
Created the Respond to Webhook node and configured it as provided.

![](/aux/L10/B/Respond.png)

## Step 6
Used CUrl to test the workflow on the [Elements of Matrix protocol/specification](https://matrix.org/docs/matrix-concepts/elements-of-matrix/).

![](/aux/L10/B/Test.png)
