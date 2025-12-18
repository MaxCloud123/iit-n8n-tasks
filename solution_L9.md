# Exercise A
## Step 1
Created a new workflow.

![](/aux/L9/A/L9_ExerciseA_Init.png)

## Step 2
Created the initial `Webhook` node and configured it as per the instructions.

![](/aux/L9/A/L9_ExerciseA_InitNodeNew.png)

## Step 3
Created the new `Code` node after the `Webhook` node and configured it as per the instructions.

![](/aux/L9/A/L9_ExerciseA_CodeNodeNew.png)

## Step 4
Created the new `Respond to Webhook` node and configured it as per the instructions.

![](/aux/L9/A/L9_ExerciseA_RespondNodeNew.png)

## Step 5
Tested the workflow with and without the `event` parameter by calling the Webhook via `CUrl`.

> [!NOTE]
> Since the `n8n` instance and the terminal run in the same environment,
> `localhost` can and is used to call the Webhook; easier to type.

![](/aux/L9/A/L9_ExerciseA_WorkflowTest.png)

## Step 6
> [!CAUTION]
> Step 6 doesn't exist in the exercise.

## Step 7
Made the workflow "Active" and respond to production webhook requests.

> [!WARNING] 
> In the latest `n8n` version, activating workflows has been replaced by `Publishing`.

![](/aux/L9/A/L9_ExerciseA_WorkflowProd.png)

# Exercise B
## Step 1
Created a new workflow with the name provided.

![](/aux/L9/B/Init.png)

## Step 2
Created a new initial/trigger `Webhook` node with provided configuration.

![](/aux/L9/B/WebhookNew.png)

## Step 3
Created a new `HTTP request` node after the `Webhook` trigger, and configured it as provided.

![](/aux/L9/B/HTTPNew.png)

## Step 4
Created new `Respond to Webhook` node after the `HTTP Request` node, and configured it as provided.

![](/aux/L9/B/WebhookRespond.png)

## Step 5
Used `CUrl` to trigger the webhook, to test the workflow.

> [!NOTE]
> `CUrl` uses `localhost`, because the `n8n` instance is in the same environment as the terminal

> [!CAUTION]
> During testing the domain `quotes.domiadi.com` didn't exist.
> As such the correct response couldn't be reproduced

![](/aux/L9/B/Test.png)

## Step 6
> [!IMPORTANT]
> Workflow activation has been replaced by prod/testing system in newer versions

Published/Activated the workflow and used `CUrl` to call the permanent/production webhook endpoint.

![](/aux/L9/B/Activate.png)

# Exercise C
## Step 1
Created a new workflow with the name provided.

![](/aux/L9/C/Init.png)

## Step 2
Created the initial/trigger node `Webhook` and configured is as provided.

![](/aux/L9/C/WebhookNew.png)

## Step 3
Created a `Code` node after the `Webhook` trigger/initial node and configured is as provided.

![](/aux/L9/C/CodeNew.png)

## Step 4
Created a `Read/Write Files from Disk` node after the `Code` node and configured it as provided.

![](/aux/L9/C/AppendFile.png)

## Step 5
Created a `Respond to Webhook` node after the `Read/Write Files from Disk` node and configured it as provided.

![](/aux/L9/C/WebhookResponse.png)

## Step 6
Used `CUrl` to test the workflow, both with and without the parameter.

> [!NOTE]
> `CUrl` is using `localhost`, because the `n8n` instance is in the same environment as the terminal

![](/aux/L9/C/Execute.png)

## Step 7
Verified that the notes are being saved by opening the file in the editor.

![](/aux/L9/C/Verify.png)

## Step 8

> [!NOTE]
> Workflow activation has been replaced by prod/test system in newer `n8n` versions

Activated/Published the workflow and used `CUrl` to call the production webhook endpoint.

![](/aux/L9/C/Activate.png)
