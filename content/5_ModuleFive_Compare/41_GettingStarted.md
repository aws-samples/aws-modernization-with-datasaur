---
title: "Getting Started with the Sandbox" # MODIFY THIS TITLE
chapter: true
weight: 1 # MODIFY THIS VALUE TO REFLECT THE ORDERING OF THE MODULES
---

# Getting Started with the Sandbox <!-- MODIFY THIS HEADING -->
## Step 1: Create Your Sandbox


![Create Sandbox](/images/step1.png) 

Create Sandbox
- Click on "Create Sandbox" to establish your dedicated workspace.
- You can assign a descriptive name to your sandbox for easy identification.

## Step 2: Configure the Sandbox Application

![Configure Sandbox](/images/step2.png) 

Configure the Application
- Access the "Models Configuration" section.
- You can adjust various parameters for the connected LLM model, such as temperature or token settings.
- Here we will test multiple Amazon Bedrock models to discover the best performing and cost efficient model. 

Experiment with different configurations to observe their impact on the model's responses. 

## Step 3: Run Prompts
![Run Prompts](/images/step3.png) 

- Enter your desired prompt within the designated area.
- This prompt can be a question, a task instruction, or any text input you want the LLM model to process.
- Click "Run" to trigger the model's response based on your prompt.

### RAG Example: Healthcare Assistant
Here is how Vector Store can streamline the development of a Retrieval-Augmented Generation (RAG) based Healthcare Assistant in LLM Labs:

Create the [Sandbox](https://docs.datasaur.ai/llm-projects/sandbox) with the User Instruction and System Instruction you've prepared.

![Healthcare Assistant](/images/healthcareassistant.png) 

From the Vector stores dropdown, select the vector store you created.

![none](/images/none.png) 
![demo](/images/demo.png) 
![prompt1](/images/prompt1.png) 

You can then compare other models to your initial choice by selecting "+ Add Application".

![Add Application](/images/addapplication.png)

You can keep adding “applications” to test different LLMs against your prompt on the right side of your interface.

Simply select: “Add Prompt” and then type your query/prompt while making sure all of your “applications” are selected.

Once you select “Run All” – you will receive responses from all of the Amazon models, receiving their response, inference time, and estimated cost.

![Compare models](/images/compareall.png)