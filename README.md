# Agents for Enhanced Customer Care

This solution elevates customer care with an AI-powered Contact Center by identifying customer intent, creating dynamic action plans, leveraging organizational knowledge and providing customer specific AI insights which lead to increased customer satisfaction. The solution leverages Copilot Studio, Dynamics 365 Contact Center, Power Platform and Azure Maps.

<br/>

<div align="center">
  
[**SOLUTION OVERVIEW**](#solution-overview)  \| [**QUICK DEPLOY**](#quick-deploy)  \| [**BUSINESS USE CASE**](#business-use-case)  \| [**SUPPORTING DOCUMENTATION**](#supporting-documentation)

</div>
<br/>

<h2><img src="./Deployment/Images/solution-overview.png" width="48" />
Solution overview
</h2>

The Agents for Enhanced Customer Care solution accelerator leverages agents in the context of customer engagement, to provide delightful customer experiences, and empower agents in the contact center, in the context of a Telecommunications organization. Agent AI capabilities are used to engage directly with customers on the voice/phone channel, as well as to provide contextual and organization-specific insights to contact center employees. This results in increased customer satisfaction, cost reduction and increased revenue for targeted business impact.

The solution accelerator leverages Dynamics 365 Contact Center, Copilot Studio, Copilot in Dynamics 365 Customer Service, and Power Platform as the core components for the solution.

Customers of the organization are able to speak with an AI-powered agent on the voice channel as the first point of interaction. The AI agent understands customer intent and dynamically formulates and executes a plan of action, using Generative AI-based orchestration to assemble the appropriate knowledge, topics, and actions to drive to resolution. When necessary, troubleshooting steps can be dynamically prepared, and stepped through with the customer, personalized to the customer's technical aptitude. If needed, the AI agent seamlessly escalates the conversation to a human customer service representative, where Copilot in Dynamics 365 Customer Service is leveraged to enhance the employee's productivity by giving them intelligently-summarized information about the customer and their conversation with the AI agent, their past interaction history, and natural-language access to organization-specific data and applications. This results in higher agent productivity, and higher customer satisfaction, by reducing the time it takes to resolve the customer call, and increasing the accuracy of the service representative.

**NOTE:** This accelerator is not intended to be a production ready solution. The components can be extended through customization & configuration as desired to create a production ready solution. All components packaged have been done through a unmanaged solution which allows users to be able to customize & extend the components post deployment.

### Solution architecture

![Architecture](./Deployment/Images/architecture.png)

### How to customize

This solution is designed to be easily customizable. All configuration and customizations to this solution will be done in Dynamics 365, Power Platform and Copilot Studio.

<br/>

### Additional resources

This accelerator focuses on harnessing the following key capabilities:

* [GenAI-based planning and orchestration](https://learn.microsoft.com/en-us/microsoft-copilot-studio/advanced-generative-actions) in Copilot Studio
* Dynamic and contextual troubleshooting in Copilot Studio
* Extending Copilot in Dynamics 365 Customer Service to be industry- and organization-specific through [Prompt Plugins and Connector Plugins](https://learn.microsoft.com/en-us/dynamics365/customer-service/administer/enable-copilot-plugins-for-generative-ai)

Additional details on how these capabilities are leveraged in this accelerator can be found here:

* [GenAI-based Orchestration of Topics and Actions in Copilot Studio](./Deployment/Differentiators/DIFFERENTIATORS.md#genai_orchestration)
* [Dynamically-generated Adaptive Cards in Topics and Actions](./Deployment/Differentiators/DIFFERENTIATORS.md#adaptive_cards)
* [Dynamically-generated Azure Maps Images in Adaptive Cards](./Deployment/Differentiators/DIFFERENTIATORS.md#azure_maps)
* [Dynamically-generated Troubleshooting Steps in Copilot Studio Topics](./Deployment/Differentiators/DIFFERENTIATORS.md#troubleshooting_steps)
* [Prompt Plugins for Copilot in D365 Customer Service](./Deployment/Differentiators/DIFFERENTIATORS.md#prompt_plugins)
* [Connector Plugins for Copilot in D365 Customer Service](./Deployment/Differentiators/DIFFERENTIATORS.md#connector_plugins)

<br/>

## Key features

<details open>
  <summary>Click to learn more about the key features this solution enables</summary>

  - **Identify customer intent** <br/>
  Agents use natural language understanding and AI capabilities to determine customer intent, and take the appropriate actions.
  
  - **Create dynamic action plans** <br/>
  Intent-driven action plans with Generative AI-powered language understanding, automatically created and executed based on customer intent.
  
  - **Orchestrate multi-step tasks** <br/>
  Agents use contextual insights to intelligently choose the best sequence of actions, knowledge and topics to address customer needs.
  
  - **Organization specific knowledge** <br/>
  Employees empowered with domain-specific knowledgebase content, summarized by Generative AI to accurately answer customer queries.
  
  - **Customer specific AI insights** <br/>
  AI-powered, actionable insights based on sentiment, summarization, natural-language access to organizational systems, and more.
       
</details>

<br /><br />
<h2><img src="./Deployment/Images/quick-deploy.png" width="48" />
Quick deploy
</h2>

### How to install or deploy

Please click this [**Link to Deployment Guide**](Deployment/README.md) for instructions on how to deploy and set up the solution accelerator.

[**Usage Guidance**](Deployment/Data/USAGE_GUIDANCE.md) has been provided to assist you in executing the steps required to see the included capabilities of this accelerator in action.

<br/>

### Prerequisites and Costs

To deploy this solution accelerator, ensure you have access to the following

- [Microsoft Power Platform license](https://learn.microsoft.com/en-us/power-platform/admin/pricing-billing-skus) with System Administrator, Omnichannel agent and Omnichannel admin access.
- [Dynamics 365 Contact Center (Digital + Voice) license](https://www.microsoft.com/en-us/dynamics-365/products/contact-center)
- [Dynamics 365 Customer Service Enterprise license](https://www.microsoft.com/en-us/dynamics-365/topics/customer-service/customer-service-software)
- Ensure this appsource app is installed in the Power Platform environment Business Apps.
- [Copilot Studio license](https://learn.microsoft.com/en-us/microsoft-copilot-studio/billing-licensing).
- End users having [Dataverse access](https://www.microsoft.com/en-us/power-platform/dataverse).
- [AI prompts](https://learn.microsoft.com/en-us/power-platform/release-plan/2025wave1/ai-builder/prompt-builder) (formerly called AI builder) credits
- Azure portal access and ability to create [Key Vault](https://azure.microsoft.com/en-us/products/key-vault/) & [Azure Maps](https://azure.microsoft.com/en-us/products/azure-maps/) resources.


<br/>

| Product | Description | Cost |
|---|---|---|
| [Microsoft Power platform](https://learn.microsoft.com/en-us/power-platform/) | Microsoft Power Platform is a suite of applications, connectors, and a data platform (Dataverse) that provides a rapid application development environment to build custom apps, automate workflows, and analyze data. | [Pricing](https://www.microsoft.com/en-us/power-platform/pricing/) |
| [Microsoft Dynamics 365 contact center platform](https://www.microsoft.com/en-us/dynamics-365/products/contact-center) | his solution offers a comprehensive, AI-powered contact center platform that enables businesses to deliver personalized, omnichannel customer support. | [Pricing](https://www.microsoft.com/en-us/dynamics-365/products/contact-center/pricing) |
| [Microsoft Dynamics 365 customer service](https://www.microsoft.com/en-us/dynamics-365/topics/customer-service/customer-service-software) | This solution focuses on providing exceptional customer service experiences through a unified platform. It includes features like case management, knowledge base, and AI-driven insights to help agents resolve issues quickly and effectively. | [Pricing](https://www.microsoft.com/en-us/dynamics-365/products/customer-service/pricing) |
| [Microsoft copilot studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/) | Microsoft Copilot Studio is a graphical, low-code tool designed for building AI-driven agents and agent flows. | [Pricing](https://learn.microsoft.com/en-us/microsoft-copilot-studio/billing-licensing) |
| [Azure key valut](https://learn.microsoft.com/en-us/azure/key-vault/keys/quick-create-portal) | Azure Key Vault is a cloud service that provides a secure store for secrets, such as API keys, passwords, certificates, and cryptographic keys. | [Pricing](https://azure.microsoft.com/en-us/pricing/details/key-vault/) |
| [Azure maps](https://azure.microsoft.com/en-us/products/azure-maps/) | Azure Maps is a suite of geospatial mapping services that enable developers and organizations to build intelligent location-based experiences for web and mobile applications. | [Pricing](https://azure.microsoft.com/en-us/pricing/details/azure-maps/|


<br /><br />
<h2><img src="./Deployment/Images/business-scenario.png" width="48" />
Business Use Case
</h2>

Below is an image of the solution accelerator.

![Key Features](./Deployment/Images/solutionoverview.png)

A customer calls the customer support number of their telecommunications service provider to try to resolve an ongoing 5G home internet connectivity issue, and receives a personalized greeting by an AI agent. The customer describes the home internet connectivity issue, and the agent is able to intelligently understand the customer's intent. The AI agent intelligently and dynamically creates an action plan to investigate and resolve the issue. A series of actions are intelligently assembled, to determine if there is a network issue at the customer's network node. Upon identifying that the network is operating as expected, the agent assembles and walks through a set of troubleshooting steps to help identify and resolve the problem on the customer's end. Upon resolution, the AI agent identifies an upsell opportunity that will prevent the issue from impacting the customer in the future, and asks the customer if they would be interested.

Once the customer confirms interest and agrees to speak with a representative, the AI agent transfers the conversation to a contact center employee who receives a Copilot-provided summary of the conversation between the customer & the AI agent, empowering him to best assist the customer. From there, the representative is empowered with organization-specific insights from Copilot, enabling him to use natural language to retrieve data usage history, provision products and services, and take other actions in industry-specific line-of-business applications.

The call is wrapped up with an intelligently-drafted email sent to the customer that summarizes the interaction between the customer, AI agent and representative.

### Business value
<details>
  <summary>Click to learn more about what value this solution provides</summary>

  - **Increased customer satisfaction** <br/>
  Delight customers with effortless self-service, frictionless experiences across channels, and personalized interactions.
  
  - **Scaling service & reducing Cost** <br/>
  Do more with less by leveraging intelligent agents to address customer issues, and by supercharging productivity of service representative.
  
  - **Empower Employees** <br/>
  Route interactions to the right team member, and empower them with AI-driven insights, to provide accurate, timely, and personalized resolutions.
  
  - **Increased Revenue** <br/>
  AI-driven insights and automation enable agents and representatives to add value for both organization and customer in revenue-focused opportunities.
     
</details>

<br /><br />

<h2><img src="./Deployment/Images/supporting-documentation.png" width="48" />
Supporting documentation
</h2>

1. [Microsoft Power Platform](https://learn.microsoft.com/en-us/power-platform/)
2. [Microsoft Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)
3. [Dynamics 365 Contact Center ](https://learn.microsoft.com/en-us/dynamics365/contact-center/)

### Security guidelines

This template uses Azure Key Vault to store the credentials for Azure Maps. You can find more details in section 1.9 of [deployment guide](./Deployment/README.md).

You may want to ensure that you configure any Copilot Studio actions, and any Connections used in Power automate flows, to use the authentication that is appropriate for your organization and scenario.

Depending on your desired security model, you may wish to select user authentication for actions rather than agent author authentication. For power automate flows, you may wish to configure connections to use the credentials of run-only users, or with a specific connection that you create.

Please note that this solution leverages a custom Dataverse table called 'Cell Data Usage' which stores sample data usage of customers. Creation of a security role to manage Case, Contact, and Cell Data Usage table access for end users is recommended based on organizational best practices and needs.

See these resources for more details on setting up authentication:

* [Configure user authentication for actions](https://learn.microsoft.com/en-us/microsoft-copilot-studio/configure-enduser-authentication)
* [Manage owners and users in your flows with Power automate](https://learn.microsoft.com/en-us/sharepoint/dev/business-apps/power-automate/guidance/manage-list-flows)

### Frequently asked questions

[Click here](./FAQs.md) to learn more about common questions about this solution.

<br/>

### Cross references
Check out similar solution accelerators
 
{🟨TODO: Identify related accelerators - fill in the name and a one sentence description. The name should have non-breaking spaces in them to make sure the layout doesn't break.}

| Solution Accelerator | Description |
|---|---|
| [Conversation knowledge mining](https://github.com/microsoft/Conversation-Knowledge-Mining-Solution-Accelerator) |This solution accelerator enables customers with large amounts of conversational data to improve decision-making by leveraging intelligence to uncover insights, relationships, and patterns from customer interactions. |

<br/>   


## Provide feedback

Have questions, find a bug, or want to request a feature? [Submit a new issue](https://github.com/microsoft/Agents-for-Enhanced-Customer-Care-Solution-Accelerator/issues/new/choose) on this repo and we'll connect.

<br/>

## Responsible AI Transparency FAQ
Please refer to [Transparency FAQ](./TRANSPARENCY_FAQ.md) for responsible AI transparency details of this solution accelerator.

<br/>

## Disclaimers

To the extent that the Software includes components or code used in or derived from Microsoft products or services, including without limitation Microsoft Azure Services (collectively, “Microsoft Products and Services”), you must also comply with the Product Terms applicable to such Microsoft Products and Services. You acknowledge and agree that the license governing the Software does not grant you a license or other right to use Microsoft Products and Services. Nothing in the license or this ReadMe file will serve to supersede, amend, terminate or modify any terms in the Product Terms for any Microsoft Products and Services. 

You must also comply with all domestic and international export laws and regulations that apply to the Software, which include restrictions on destinations, end users, and end use. For further information on export restrictions, visit https://aka.ms/exporting. 

You acknowledge that the Software and Microsoft Products and Services (1) are not designed, intended or made available as a medical device(s), and (2) are not designed or intended to be a substitute for professional medical advice, diagnosis, treatment, or judgment and should not be used to replace or as a substitute for professional medical advice, diagnosis, treatment, or judgment. Customer is solely responsible for displaying and/or obtaining appropriate consents, warnings, disclaimers, and acknowledgements to end users of Customer’s implementation of the Online Services. 

You acknowledge the Software is not subject to SOC 1 and SOC 2 compliance audits. No Microsoft technology, nor any of its component technologies, including the Software, is intended or made available as a substitute for the professional advice, opinion, or judgement of a certified financial services professional. Do not use the Software to replace, substitute, or provide professional financial advice or judgment.  

BY ACCESSING OR USING THE SOFTWARE, YOU ACKNOWLEDGE THAT THE SOFTWARE IS NOT DESIGNED OR INTENDED TO SUPPORT ANY USE IN WHICH A SERVICE INTERRUPTION, DEFECT, ERROR, OR OTHER FAILURE OF THE SOFTWARE COULD RESULT IN THE DEATH OR SERIOUS BODILY INJURY OF ANY PERSON OR IN PHYSICAL OR ENVIRONMENTAL DAMAGE (COLLECTIVELY, “HIGH-RISK USE”), AND THAT YOU WILL ENSURE THAT, IN THE EVENT OF ANY INTERRUPTION, DEFECT, ERROR, OR OTHER FAILURE OF THE SOFTWARE, THE SAFETY OF PEOPLE, PROPERTY, AND THE ENVIRONMENT ARE NOT REDUCED BELOW A LEVEL THAT IS REASONABLY, APPROPRIATE, AND LEGAL, WHETHER IN GENERAL OR IN A SPECIFIC INDUSTRY. BY ACCESSING THE SOFTWARE, YOU FURTHER ACKNOWLEDGE THAT YOUR HIGH-RISK USE OF THE SOFTWARE IS AT YOUR OWN RISK.  