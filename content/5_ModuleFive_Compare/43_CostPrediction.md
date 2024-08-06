---
title: "Cost Prediction Calculation" # MODIFY THIS TITLE
chapter: true
weight: 3 # MODIFY THIS VALUE TO REFLECT THE ORDERING OF THE MODULES
---

# Cost Prediction Calculation <!-- MODIFY THIS HEADING -->
## Overview

The Cost Prediction for Inference feature aims to enhance user experience by providing transparency and predictability in terms of the costs incurred during language model inference. Users can now estimate the financial implications of their inferencing activities within LLM Lab.

**How to see the cost prediction?**

In the meantime, we only support cost prediction for OpenAI and Azure OpenAI models.
- Open your LLM Application.
- Write your prompt query, and the predicted cost from your prompt templates will be shown.


![cost prediction 1](/images/costprediction1.png) 
*Cost Prediction Calculation*

The cost prediction will **calculate the cost based on your available prompt template,** the more prompt template you have the cost will be more expensive.

**View Prediction Details**
To see the prediction details, you just have to click the cost prediction. It will show you a dialog of the detailed cost.
![prediction details](/images/predictiondetails.png) 
*Detailed Cost Prediction for Prompt*

You can also break down and compare the cost prediction based on your available prompt template.
![prediction details](/images/cpprompt1.png) 
*Breakdown Cost Prediction for Prompt Template 1*
![breakdown 2](/images/breakdown2.png) 

