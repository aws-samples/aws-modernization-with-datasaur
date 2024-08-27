---
title: "Cost Prediction Calculation" # MODIFY THIS TITLE
chapter: true
weight: 2 # MODIFY THIS VALUE TO REFLECT THE ORDERING OF THE MODULES
---

# Cost Prediction Calculation <!-- MODIFY THIS HEADING -->
## Overview

The Cost Prediction for Inference feature aims to enhance user experience by providing transparency and predictability in terms of the costs incurred during language model inference. Users can now estimate the financial implications of their inferencing activities within LLM Lab. 

When looking at the responses that were returned from your prompt, you’ll see a cost indication for each return.
![cost prediction 1](/images/costprediction1.png) 
*Cost Prediction Calculation*

The cost prediction will **calculate the cost based on your available prompt template,** the more prompt template you have the cost will be more expensive.

**View Prediction Details**

Below we have an example of how much it will cost to utilize Llama 3b from Amazon Bedrock. Note the cost prediction breaks down multiple factors for the estimation including tokens, context, prompt, and more.
![prediction details](/images/predictiondetails.png)
