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
