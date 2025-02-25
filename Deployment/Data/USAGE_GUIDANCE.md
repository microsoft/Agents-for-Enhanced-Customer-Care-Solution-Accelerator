# Usage Guidance

To see the key capabilities of this accelerator in action after completing the installation, follow the execution step guidance included below.
 
Note that the steps follow a sequence between the following two personas:
 * **Nicole**, a marketing manager at a tech firm, who is a customer of Contoso Telecom, and has an issue with her 5G home internet
 * **Sam**, a customer service representative in the Contoso Telecom contact center

Nicole calls Contoso Telecom, engages with an AI Agent for intelligent support and troubleshooting, then is transferred to Sam, to complete a transaction on an upgrade to her service.

**Important Note**: Because this accelerator leverages Generative AI capabilities, the specific dialog and steps may vary from one usage instance to another.
 
## Execution steps for Customer <> AI Agent interaction:

 Acting as Nicole, use your mobile phone (which should have the same phone number as Nicole's contact record) to call the phone number you have set up for your Voice workstream in Dynamics.

 * **AI Agent**: Hi, Nicole! Thanks for calling Contoso Telecom. I’m your AI companion. I can help with account issues, billing queries, technical assistance, and more. How can I help you?
 * **Customer**: I can't connect to my Home Internet.
 * **AI Agent**: I’m sorry to hear that. Let’s see if we can get it back up and running quickly. Just to confirm, are you currently at home?
 * **Customer**: Yes, I am.
 * **AI Agent**: Great, I’ve got your location. I see you have a CT 1000 5G Home internet Gateway. Let me check the status of the network near you and look for any active maintenance on the network.
 * **AI Agent**: So, everything seems fine on the network side.
 * **AI Agent**: May I communicate with your device to gather some information to help me investigate further?
 * **Customer**: Sure.
 * **AI Agent**: OK, I've connected to your device and am investigating further. 
 * **AI Agent**: According to our diagnostic information, you may have too many devices connected to your gateway for optimal performance.
 * **AI Agent**: Wait just a moment while I prepare some troubleshooting steps.  As we go through them, you can say next, stop, go back, or start over.
 * *(note: The specific steps are dynamically generated, so responding with “next” after each step should allow you to progress through all of them)*
 * **AI Agent**: Ok, let’s try disconnecting a couple devices to see if that fixes your issue. You can do this by disconnecting or turning off other devices like your TV gaming system, Smart Home devices or any other devices using the Internet. 
 * **Customer**: Next.
 * **AI Agent**: OK, next try connecting the device that's having trouble to the Internet again, see if it can connect now. 
 * **Customer**: Next.
 * **AI Agent**: Did we manage to solve your issue?
 * **Customer**: Yes, thank you.
 * **AI Agent**: Is there anything else I can assist you with?
 * **Customer**: No thanks.
 * **AI Agent**: Based on what we discussed today, you may want to consider a Contoso Mesh 1500. The Contoso Mesh system offers more device connection capacity and greater signal coverage within your home. Would that interest you? 
 * **Customer**: Maybe.   
 * **AI Agent**: Can I connect you to a live agent who can discuss the details with you?
 * **Customer**: Sure. 
 * **AI Agent**: One moment while I transfer you to a member of our team.

At this point in the conversation, an escalation should be triggered, and the escalated call will be routed based on the routing rules that you have configured in your **Workstream**.

## Execution steps for Customer Service Representative in Dynamics 365 Customer Service workspace:

While logged into the **Customer Service workspace** with a user who is **Available**, has capacity, and is configured to receive the escalated conversation, you should receive a **Notification**, which will allow you to accept the escalated phone call from the customer.

Once engaged in the phone call with the customer, there are many in-built customer service representative enablement capabilities available to you, including:
 * Conversation summarization via Copilot
 * Timeline summarization via Copilot
 * Real-time call transcription, with real-time sentiment analysis
 * Real-time translation
 * and more

 There are specific **Copilot in Dynamics 365 Customer Service** capabilities that have been included within this accelerator. To make use of these, open Copilot in D365 in the right-hand pane, and enter these prompts.

 * **"What devices are compatible with the Mesh 1500?"**
    * This prompt should cause Copilot to provide a response by summarizing one of the provided knowledgebase articles included in the sample data you imported.
 * **"What is Nicole Swanson's data usage?"**
    * This prompt should invoke the included **Prompt Plugin**, and summarize the most recent usage data in the Cell Data Usage Dataverse table for customer Nicole Swanson.
 * **"Provision the Mesh 1500 for customer Nicole Swanson"**
    * This prompt should invoke the included **Custom Connector Plugin**, and make a request to the simulated service provisioning service, via the Custom Connector included in the solution you imported.