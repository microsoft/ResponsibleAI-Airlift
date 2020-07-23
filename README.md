# ResponsibleAI-Airlift-July2020

<!-- 
Guidelines on README format: https://review.docs.microsoft.com/help/onboard/admin/samples/concepts/readme-template?branch=master

Guidance on onboarding samples to docs.microsoft.com/samples: https://review.docs.microsoft.com/help/onboard/admin/samples/process/onboarding?branch=master

Taxonomies for products and languages: https://review.docs.microsoft.com/new-hope/information-architecture/metadata/taxonomies?branch=master
-->

## Overview 
This repository contains content of a two-part workshop for using machine learning interpretability and fairness assessment (unfairness mitigation) to build fairer and more transparent models. The different components of the workshop are as follows:

- Part 1: [Interpretability with Explainable Boosting Machines (EBM)](https://github.com/microsoft/ResponsibleAI-Airlift-July2020)
- Part 2: [Explaining Blackbox Models with SHAP](https://github.com/microsoft/ResponsibleAI-Airlift-July2020)
- Part 3: [Fairness Assessment and Unfairness Mitigation with Fairlearn (Bonus: + Interpretability)](https://github.com/microsoft/ResponsibleAI-Airlift-July2020)


## Getting started with the workshop environment

1. Provision your personal Lab environment

    * Open **Registration URL**: http://bit.ly/2OjknZW
    * Enter **Activation Code** which should be provided by the instructors of the workshop.
    * Fill out registration form and Submit it.
    * On the next screen click **Launch Lab**.
    * Wait until your personal environment is provisioned. It should take approximatly 3-5 minutes.

2. Login to Azure ML studio

    * Once the workshop enviroment is ready, you can open new browser tab and navigate to Azure ML studio, using it's direct URL: [https://ml.azure.com](https://ml.azure.com). We recommend to use Private Browser window for the login to avoid conflicting credentials if you already have Azure subscription.
    * Use credentials provided in the workshop environment to sign-in to Azure ML studio.
    * In the Welcome screen select preprovisioned subcription and workspace similar to screenshot below:
    ![](images/studio-sign-in.png)
    * Click **Get started**!
    * In the welcome screen click on **Take a quick tour** button to familiarize yourself with Azure ML studio.

3. Create Azure Machine Learning Notebook VM

    * Click on **Compute** tab on the left navigation bar.
    * In the Notebook VM section, click **New**.
    * Enter Notebook VM name of your choice and click **Create**. Creation should take approximately 5 minutes.

4. Clone this repository to Notebook VM in your Azure ML workspace

    * Once Notebook VM is created and in Running state, click on the **Jupyter** link. This will open Jupyter web UI in new browser tab.
    * In Jupyter UI click **New > Terminal**.
    * In terminal window, type and execute command: `ls`
    * Notice the name of your user folder and use that name to execute next command: `cd <userfolder>`
    * Clone the repository of this workshop by executing following command: `git clone https://github.com/microsoft/responsibleai-airlift-july2020.git`

5. Open Part 1 of the workshop

    * Go back to the Jupyter window.
    * Open `EBM.ipynb` notebook.

You are ready to start your workshop! Have fun.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
