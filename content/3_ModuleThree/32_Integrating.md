---
title: "Integrating LLMs Provider" # MODIFY THIS TITLE
chapter: true
weight: 2 # MODIFY THIS VALUE TO REFLECT THE ORDERING OF THE MODULES
---

# Integrating LLMs Provider <!-- MODIFY THIS HEADING -->
You can also integrate into several LLMs providers such as Amazon SageMaker JumpStart, OpenAI, and Azure OpenAI by clicking the Manage providers button.

![Manage](/images/manage.png) 
To integrate the LLMs provider, you will need to set up and add their providers credentials in Datasaur.
![Credentials](/images/credentials.png) 

Once the provider is integrated, you can deploy and use their own models in Datasaur.
![Explore Models](/images/exploremodels.png) 

### Deploy the models
After integrating the LLMs provider, you can deploy your own model in Datasaur. To deploy the model, click on 'Deploy model'. The Deploy model dialog will be shown. In this dialog, you need to input your specific endpoint name.
![Deploy Model](/images/deploymodel.png) 

Once you've clicked the Deploy model button, you will need to wait several minutes for deployment to complete. You can monitor the latest status of the deployment through model status information at the top right.
![Model Status](/images/modelstatus.png) 

After the deployment process is complete, the model status will change to Available in the status information.
![Available](/images/available.png) 


{{% notice info %}}
<p style='text-align: left;'>
**REMOVE:** With the exception of _index.md, the module folders and filenames should be changed to better reflect their content, i.e. 1_Planning as the folder and 11_HowToBegin as the first submodule. Changing the "weight" value of the header is ultimately what reflects the order the modules are presented.
</p>
{{% /notice %}}

