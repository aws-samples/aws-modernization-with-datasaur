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

Select [+ Add Application], Applications are a configured LLM that you’ll be able to test against prompts and eventually deploy. You can create multiple Applications in the Sandbox and test them against the same prompt.  

Select from the list of deployed models for your Application. 

![Create Sandbox246](/images/sandbox246.png) 

## Step 2: Configure the Sandbox Application

![Configure Sandbox](/images/hyperparamconfig.png) 

Configure the Application
- Access the "Models Configuration" section.
- You can adjust various parameters for the connected LLM model, such as temperature or token settings.
- Here we will test multiple Amazon Bedrock models to discover the best performing and cost efficient model. 

Experiment with different configurations to observe their impact on the model's responses. 

Make sure to attach the knowledge base you created to your Application to the LLM can reference your database. 

![Create testyour](/images/testyourapp.png) 

## Step 3: Run Prompts
![Run Prompts](/images/prompt.png) 

- Enter your desired prompt within the designated area.
- This prompt can be a question, a task instruction, or any text input you want the LLM model to process.
- Click "Run" to trigger the model's response based on your prompt.

Once you have run the prompt against one or more applications you’ll be able to read the output and the corresponding chunks used for the answer. 

You will also find the cost and inference team for each of your applications. 

![Run Prompt2](/images/prompt2.png) 

You can also add files and a URL to your prompt. 

![Run Prompt3](/images/prompt3.png) 