# DataPower Interact Gateway Technical Sales Level 3 Demo Guide
#### [Made by Anupama Taduri with Scribe](https://scribehow.com/o/xahtdQVjS0CP_tfALhqR3A/viewer/DataPower_Interact_Gateway_Technical_Sales_Level_3_Demo_Guide__2ES4O8hsTMu4qBlAOSj7sA)
Anupama Taduri: anupama.taduri@ibm.com
Matthew Barnes: matthew.barnes1@ibm.com
Christian Kopecki: Christian.Kopecki@ibm.com

#### Introduction


1\. Welcome to the DataPower Interact Gateway Level 3 Enablement Demo Guide. This guide is designed to provide technical sales professionals and business partners with a comprehensive understanding of IBM DataPower Interact Gateway. Through a real-world enterprise AI adoption scenario, business-focused discussions, and a guided stand-and-deliver demonstration, this guide will equip learners with the knowledge and confidence needed to articulate how organizations can govern, secure, observe, and scale AI-initiated interactions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/b4429c6f-6b3a-4c4d-a20b-4ab0276eb290/matched_image_action_0_1a968a884c264553991c650cce2a9ee5_text_export.jpeg)


#### About this Demo


2\. This demo guide is intended for professionals preparing to present IBM DataPower Interact Gateway to clients and internal stakeholders. It focuses on the emerging challenge of governing AI-initiated interactions as organizations adopt AI agents, models, tools, and other AI-driven interaction patterns across existing enterprise systems.

The guide covers the key concepts and business outcomes behind interaction governance, including governed AI interaction entry points, policy enforcement at the interaction boundary, reuse of existing APIs and integration assets, and runtime observability. Learners will follow a structured stand-and-deliver demonstration that shows how IBM DataPower Interact Gateway acts as an AI mediation governance gateway for governing, securing, routing, and observing AI-driven interactions before they reach enterprise services.

By following this guide, learners will be able to confidently articulate why AI interaction governance matters, explain where IBM DataPower Interact Gateway fits within the enterprise architecture, and demonstrate how organizations can securely scale AI adoption while maintaining control, visibility, and operational confidence.


#### Prerequisites


3\. Before diving into the DataPower Interact Gateway Level 3 Demo Guide, it's essential to meet the following prerequisites to ensure a smooth and effective learning experience.

## Complete Rethinking API Gateways for the Age of AI Agents Level 1

Learn how AI agents are changing the way organizations consume APIs, data, applications, and enterprise services—and why traditional API gateway strategies must evolve to support governed AI interactions.

- For IBMers: <https://yourlearning.ibm.com/activity/PLAN-EB2D00BC5EA6>
- For Business Partners: <https://learn.ibm.com/course/view.php?id=18910> 

**Complete DataPower Interact Gateway Level 2**

Following Level 1, this course explores how IBM DataPower Interact Gateway helps organizations govern, secure, and observe AI interactions while extending existing API and integration investments.

- For IBMers: <https://yourlearning.ibm.com/activity/PLAN-9354C9DCF412>
- For Business Partners: <https://learn.ibm.com/course/view.php?id=18943>


#### IBM DataPower Interact Gateway Overview


4\. IBM DataPower Interact Gateway is an AI mediation governance gateway that governs, secures and observes all interactions between agents, models and tools with enterprise APIs and data.​

At its core, Interact Gateway provides:

- **Unified Control & Governance​:** Provides a single governance layer for both AI and API traffic. Policies, security controls, and runtime governance can be applied consistently across all interactions.​
- **Enterprise Tool &​ Data Access**​: Enables AI agents and applications to securely access existing APIs, integrations, and business capabilities. Organizations can leverage current enterprise assets without rebuilding them for AI.​
- **Visibility & Observability​**: Delivers unified visibility into interactions between AI systems and enterprise services. Teams can monitor activity, understand access patterns, and govern AI usage at runtime.​
- **Built for the Enterprise​**: Uses a lightweight, high-performance architecture designed for real-time AI workloads. Governance and observability are applied without creating operational bottlenecks.


#### About ZillaForge


5\. ZillaForge is the fictional enterprise featured throughout this course. The company has already modernized its integration landscape by investing in APIs, hybrid integration, and event-driven connectivity across cloud and on-premises environments. These investments provide the foundation for the organization's next phase of transformation: adopting AI agents to automate work, accelerate decision-making, and interact directly with business services and systems.

ZillaForge uses Interact Gateway to:

- Reuse existing APIs as AI-ready capabilities. 
- Govern AI-initiated interactions through a dedicated control point. 
- Apply security and policy enforcement before AI interactions reach backend systems. 
- Scale AI initiatives without rebuilding existing enterprise systems


#### Access the Environment


6\. The DataPower Interact Gateway demo environment runs in the cloud and can be reserved using the steps outlined in the next section. Once provisioned, you'll receive all necessary access credentials.

Because the platform is developed and updated continuously, its interface may evolve over time. Screenshots in this guide may differ slightly from what you see in the live environment, but the core functionality remains the same. If something looks different, take a moment to explore, it's part of the learning experience.

**Disclaimer:**\
Please be careful to stay within the demo path. Do not deviate, as changes could affect other users and disrupt the demo environment. Let's ensure everything runs smoothly for everyone involved.


#### Environment Access Request


7\. Login to IBM TechZone at: <https://techzone.ibm.com/search>

Search for in the **Search bar** **(A)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/cfdcb999-c19b-4694-a70d-56bab4033e04/matched_image_action_8_51ae3835669043dc83a0870a009a7f3b_text_export.jpeg)


8\. Select the webMethods Hybrid Integration L3 Enablement in the results by clicking on **Explore this collection (B)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/b81cdbdd-9553-433e-8d39-6d62202e86aa/matched_image_action_9_829410f336ca4b88a4fd6efa6f30d0ac_text_export.jpeg)


9\. Select **Environments ** **(C)** from the left-hand side menu.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/137241cd-3a47-4104-8eee-3f4c4f836021/matched_image_action_10_859a0769461f4493818e55f6d8cd193c_text_export.jpeg)


10\. Hover over the IBM Cloud environment button and click on **Reserve it (D)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/4d405ae1-7a2f-4aa3-a86d-776674fe6a77/matched_image_action_11_457759f8eec14392b097a70011d66da5_text_export.jpeg)


11\. Select the **Education **tile** (E)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/ba1a8a10-515d-4f64-b64f-581b46b4cb19/matched_image_action_12_3d1c451f0d4b4cf6970fc37c3e5a13cf_text_export.jpeg)


12\. 

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/6d3a2c51-d291-4462-9bb7-945350e2e355/matched_image_action_13_6de6652ec3dd4b13ac9e36f71d07bd09_text_export.jpeg)


13\. Provide Description as self-enablement.

Choose other fields as below.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/42e68503-f27a-43bb-9a0a-73475fd056f1/matched_image_action_14_d18cea97d48e44c983f8e031ff4b23b7_text_export.jpeg)


14\. Select terms and conditions checkbox and click **Submit (** **F** **)** button.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/4cc0ea81-1978-459c-bec5-b98d15c23b6c/matched_image_action_15_835009499ff74c738b09ee141d98796e_text_export.jpeg)


15\. You will receive an email when the environment is provisioned with instructions on how to access the environment.

**Note to learners**: This action could take up to 15-20 minutes


#### Accessing the Environment via IBM Technology Zone


16\. Click on the **View** **My Reservations** **(A)** link in the email.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1bf22aa4-9032-48f8-8716-fcc059de0b33/matched_image_action_17_89ba192fc29346cfb7dc48837f4cd0ad_text_export.jpeg)


17\. Click on **Open this environment** **(B)** on the reservation card.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/6152ca1f-f75d-4abe-80d5-d550f50d8421/matched_image_action_18_071c216dbbd24a6a9e2f43e869e257b3_text_export.jpeg)


18\. Scroll down on the reservation details page and you can find the webMethods Hybrid Integration URL and credentials for B2B and MFT WebClient as below.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/5bcbae50-b1e3-4b30-85f6-7ecf66a3158d/matched_image_action_19_aa7d434ab0274e0e8f539552b1ccad7e_text_export.jpeg)


19\. Once you connect, bookmark the IBM webMethods Hybrid Integration home page and you should see the screen below.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1b87ca4a-7806-4ac2-9276-927e7babb36c/matched_image_action_20_202a32caf76849cbbd414b756a8c4e60_text_export.jpeg)


#### Demo Guideline


20\. This guide is designed to help you demonstrate the DataPower Interact Gateway in front of the clients or internal stakeholders.


21\. **Use Case Introduction**\
\
ZillaForge, a fictional global leader in industrial automation, is entering a new phase of digital transformation by adopting AI agents to automate work, accelerate decision-making, and interact directly with enterprise systems. While the company has already invested in APIs, hybrid integration, and event-driven connectivity, it now faces a new challenge: governing AI-initiated interactions as they move across business applications, integrations, and services.

To address these challenges, ZillaForge adopts IBM DataPower Interact Gateway.

This transformation story forms the foundation of the Level 3 course. Through a guided stand-and-deliver demonstration, learners will see how organizations like ZillaForge can safely scale AI adoption by governing AI-initiated interactions without rebuilding existing systems or creating a separate AI governance stack.


22\. **Demo Overview**

This demo provides a guided walkthrough of IBM DataPower Interact Gateway in the context of ZillaForge's AI adoption journey. It highlights how organizations can govern AI-initiated interactions while continuing to reuse existing APIs, integrations, and workflows.

Learners will observe how key capabilities, such as governed interaction entry points, policy enforcement, enterprise asset reuse, and runtime observability, work together to provide security, visibility, and operational control for AI-driven interactions. Each stage of the demo aligns to a business challenge, showing how interaction governance helps organizations scale AI adoption with confidence.

The experience is read-only and follows a structured stand-and-deliver format, allowing learners to explore the interaction flow, governance controls, and observability views without performing any setup, configuration, or administration tasks.


#### Demo Script


23\. **Overview and Architecture**

**Note to Learners**: The slides used in this section and usage analytics can be found [HERE](https://ibm.seismic.com/Link/Content/DC633F9fdp9cC89T3QDhmmmFGqWB).

**Narration:**

ZillaForge, a fictional global manufacturer of industrial automation equipment, is expanding its use of AI assistants and agents to improve productivity, automate decision-making, and accelerate business processes. The company has already invested heavily in APIs, integrations, workflows, and governance, creating a strong digital foundation of reusable business capabilities.

As AI adoption grows, ZillaForge faces a new challenge. AI assistants and agents need access to those same enterprise capabilities, but traditional governance models were designed for applications, not autonomous AI interactions. The company needs a way to maintain visibility, security, and operational control as AI-driven activity scales across the business.

To address these challenges, ZillaForge adopts IBM DataPower Interact Gateway. Acting as an AI mediation governance gateway, it helps the company govern AI interactions, expose existing enterprise capabilities to AI without rebuilding them, and apply consistent security, policy enforcement, and observability across AI-driven traffic. This demo follows ZillaForge's AI adoption journey, showing how Interact Gateway enables organizations to reuse existing APIs, integrations, and business services while bringing AI-initiated interactions under a consistent governance model.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/938d0203-4875-4a69-8b7c-f305b939f0f5/matched_image_action_24_08aa7bff03484e888102d1821b06afbc_text_export.jpeg)


24\. **Narration:**

This illustration represents the architecture used in the ZillaForge demo and the digital foundation the company established before introducing AI. It shows how years of investment in APIs, application integration, events, governance, and reusable business services created a platform of enterprise capabilities that can now be safely consumed by AI assistants and agents.

At the center of the architecture is the **ZillaForge Digital Business Platform**, governed through a **Hybrid Control Plane** that provides centralized visibility, management, analytics, and governance across cloud, on-premises, and edge environments. Around it are the core integration capabilities, including API management, application integration, event management, B2B integration, managed file transfer, and monitoring services, all working together as shared enterprise services.

Rather than creating new capabilities for AI, ZillaForge can reuse the APIs, integrations, workflows, and business services it has already built and expose them as governed AI-ready capabilities.

This architecture forms the foundation for the rest of the demo. Throughout the walkthrough, learners will see how ZillaForge extends its existing digital investments to support AI adoption while maintaining the governance, visibility, and operational control required at enterprise scale.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1ff74f4d-8d35-4945-b6a3-9818949d4611/matched_image_action_25_21894fc2285841fb855c9a9d462d3066_text_export.jpeg)


25\. **Narration:**

ZillaForge has already begun adopting AI across different parts of the business. Teams are experimenting with AI services, connecting them to business applications, and enabling access to enterprise capabilities. In the early stages, these initiatives are often managed independently, with individual teams using their own model access, credentials, and integration approaches. While this works for small-scale experimentation, it quickly becomes difficult to manage as AI adoption expands across the organization.

As more AI assistants and agents begin interacting with enterprise systems, new governance challenges emerge. Organizations need to understand who is using which models, what business capabilities are being accessed, what policies are being applied, and how AI-driven activity can be monitored and controlled. Traditional governance models were designed for applications and APIs, not autonomous AI interactions. This creates a governance gap that requires a consistent control point where security, policies, credentials, monitoring, and visibility can be applied across all AI interactions. IBM DataPower Interact Gateway is designed to address that gap

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/9d4f4ba8-3c1a-417e-a161-0d3bd48d3d13/matched_image_action_26_cd8ccec1c77347168442dc78dfae6559_text_export.jpeg)


26\. **Narration:**

As you saw earlier, ZillaForge already has APIs, integrations, events, and workflows that expose valuable business capabilities across the enterprise. The challenge is not creating new capabilities but allowing AI assistants and agents to access those capabilities safely and under enterprise control. That's where IBM DataPower Interact Gateway fits. It sits between AI consumers and enterprise systems, providing a controlled interaction layer that governs and secures AI-driven interactions. 

Think of Interact Gateway much like an API gateway for the AI era. It doesn't build the applications, models, or agents. Instead, it governs how they interact with enterprise services. APIs provide capabilities, events provide awareness, workflows provide guardrails, and policies provide trust. Together, these elements enable organizations to scale AI interactions with the visibility, security, and control required for enterprise adoption.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1a2652e8-eaf4-4a2d-b9b8-74bd3557b110/matched_image_action_27_c48b14f6f9d7422b85c24bf281b52be0_text_export.jpeg)


#### ZillaForge AI Assistant for Internal Operations Queries


27\. In the first part of the demo, you will explore the ZillaForge Operations Portal and interact with an AI-powered assistant. The assistant is connected to enterprise capabilities through an MCP endpoint exposed by IBM DataPower Interact Gateway, allowing users to ask business questions in natural language and receive answers from governed enterprise data and services.

The goal is to demonstrate how AI can safely access enterprise capabilities through a controlled, observable interaction layer.


28\. **Narration:** \
ZillaForge employees access a centralized Operations Portal to interact with enterprise information and capabilities. Rather than navigating multiple systems, users can simply ask questions through an AI-powered assistant integrated directly into the portal.


29\. **Actions:**

Navigate to <http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a1bd530-d04c-4428-89d4-91fa2cf62a68/action-9b94ee5d40b2468eaf5b516006a56eac_be211d99dbef44da913cf3a58c333979_text_export.jpeg)


30\. **Narration:**

Now let's see how a business user interacts with enterprise capabilities through the AI assistant.

Rather than searching through product documentation, CRM systems, knowledge bases, or multiple business applications, the user simply asks a question in natural language. 

What's important is that the AI assistant already has access to governed enterprise capabilities through the MCP endpoint exposed by IBM DataPower Interact Gateway. When the user submits the request, the assistant can discover and invoke the appropriate enterprise tools and services without requiring the user to know where the information resides or which systems need to be accessed.

From the user's perspective, this is a simple conversational experience. Behind the scenes, however, the interaction is routed through a governed entry point where security, policies, credentials, and observability are applied consistently. This allows AI to safely access trusted enterprise capabilities while maintaining enterprise control and visibility.


31\. **Actions:**

Click the ZillaForge **AI assistant** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/379aecbf-b55d-4f2b-b4ba-b04db31f54e4/action-47a37337742d4670a9817f6c0e7a8d07_ae6a722f08a24681b1303922bdb257f6_text_export.jpeg)


32\. Let's start with a few business questions. In the Input field, type the first question "**What products are offered for predictive maintenance and industrial monitoring?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/4a8722a5-8090-4dbd-8340-1d4d2db6a7c2/action-9b234e6d905d4de9a134ade5027d12e2_a6e2e043083042259f6c6e770b103fc8_text_export.jpeg)


33\. Click the **Send** button.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/c1c3199f-58dc-4413-900c-90b3ba90bf20/action-456cf2dcfead4e0aa943618ad1738248_83d82bd952054d45b25685468d7ea723_text_export.jpeg)


34\. The assistant has found the available products.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/97165cff-f12b-4480-aeea-117828893427/action-2ab9c7b3dbb4475ebf87790a18beb8d9_644f10edec734b8b9a1eea72d23b7d0a_text_export.jpeg)


35\. **Narration:**

Let's take that a step further. Rather than simply finding information, we'll now ask the assistant to analyze what it knows about ZillaForge's products and make a recommendation based on a customer's business requirements.

This allows the assistant to combine information from multiple ZillaForge capabilities, apply reasoning, and recommend the solution that best aligns with the customer's needs. Instead of just discovering available products, we're using enterprise knowledge to support a real business decision.


36\. **Actions:**

In the Input field, type the question "**Which ZillaForge product would you recommend for a factory looking to reduce unplanned equipment downtime?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/473a113b-1bd5-4a8d-88d3-b3d7e8a1bb0a/action-43c22db194d24e7b9c2865fabdb2a69e_68226b7da7b345209c3cdd8e2a4b0c35_text_export.jpeg)


37\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/e3dc0adb-b778-4edd-8721-f0114bd35c8a/action-897481be711848bd995d413e2dbd1120_b09d4b8c0ecd42078ac1b44b3ee88428_text_export.jpeg)


38\. Click **Show more** to see the entire response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/463871a7-bc46-4059-b166-2e258c0a14bf/action-b2de0b202d39408ab549c610242eb9cc_b817c28cd45041168bfcda511984044b_text_export.jpeg)


39\. Notice that the assistant hasn't simply picked a product. It's recommended a complete solution and explained why the products work together.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/fc99f186-d320-446c-bcfd-91273b1abe68/action-dbda5401aee14446a2c906ad00f6340a_699f5e24bca749d4a70097158d3592cb_text_export.jpeg)


40\. **Narration:**

Let's now see if the assistant can connect recommendations to operational data across the business.

Within ZillaForge, product information, customer demand, and fulfilment activity exist across multiple enterprise systems. The real value comes when the assistant can combine information from those different capabilities to provide meaningful business context and actionable insights.


41\. **Actions:**

In the Input box, type **"Which customer orders related to predictive maintenance solutions are currently awaiting fulfilment?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/e19226b1-3b67-4f03-bd5e-0684c96a0b16/action-3a46243684b2481a9ee486afda23e63f_860feedc61d64864bda1e01698efd2d2_text_export.jpeg)


42\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/390d78d4-cbf6-4a89-a133-7d2d718737fa/action-15698ff5ddb54e6088de7b8bc6f1a5b8_b309013556dc4cb4a8b151dda74a94fb_text_export.jpeg)


43\. Click **Show more** to see the full response.

Here the assistant has identified the customer orders that are currently awaiting fulfilment and related to predictive maintenance solutions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/8fd185b8-1197-42da-9c1c-d7454885a800/user_cropped_screenshot_69a7a00fb68c4c0092c9863790b47ed1_text_export.jpeg)


44\. **Narration:**

So far, we've seen how the assistant can help answer questions about ZillaForge products and connect those recommendations to customer demand and fulfilment activity.

Let's now move from business demand into operational performance. One of the key priorities for ZillaForge customers is improving asset reliability across manufacturing environments while reducing unplanned downtime and maintenance costs.

To answer this question, the assistant needs to do more than look up product information. It must understand the customer's business objective, evaluate the available ZillaForge solutions, and recommend the option that best aligns with operational needs.


45\. **Actions:**

In the Input box, type "**A customer wants to improve asset reliability across multiple manufacturing sites. Which ZillaForge solution would you recommend and why?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/cb25d1f4-d6cf-4724-b3a6-7ad4e708cf88/action-8cc2ebc2e83c4b0eb5c62e2214704a6d_6d8b13f853a4415aac7cda40c31e3595_text_export.jpeg)


46\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a000052-d231-4007-a044-d3044c5463a2/action-d4bc59b8d1b148b785ef24e4abd973d0_c6802518622941adb298f84d560da2c0_text_export.jpeg)


47\. The recommendation is supported by operational information. You can see several assets with elevated failure risk. The assistant is also identifying a pattern across multiple sites rather than highlighting an isolated device issue.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/2b11415b-5f7b-4d67-acdf-8b56b3e475be/action-8a750d631ec04bb4be294979381a5a94_48161908905041c89ee82e53262654fc_text_export.jpeg)


48\. **Narration:**

Let's finish with our most comprehensive scenario. A customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation and wants to understand which ZillaForge solution best support that strategy.

This question requires the assistant to bring together multiple sources of information. It needs to understand the available ZillaForge products, consider existing customer demand, and factor in planning and deployment considerations before making a recommendation.

Rather than looking at a single system or data source, the assistant must combine information from across the business to provide a complete answer.


49\. **Actions:**

In the Input field, type "**A manufacturing customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation. Which ZillaForge products best support this strategy, and what existing customer demand should the business be aware of before planning deployment?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/86238b1b-3926-4493-b524-cec8d24b09eb/action-f9e0479ecc544ef3a706cd5c694b8fb4_23675cd80b6b426b805a4ae3b2c32a09_text_export.jpeg)


50\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/24621245-8028-4dc0-9ec0-24cfe9b093e1/action-bedea4e375c0482c8246d949dd7e3013_f68b93780a4f44dba722eb2550e96fbd_text_export.jpeg)


51\. The assistant has recommended the ZillaForge solutions that best align with the customer's digital transformation objectives while also highlighting existing customer demand that should be considered during planning.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/faf5b7b4-0e18-49d4-acbe-00c6e7fa6324/action-2db327eb64144416ba441953340d13c4_73018282050a4a2a8880c9e82eaa5093_text_export.jpeg)


52\. **Narration:**

We've seen how the ZillaForge Operations Portal allows users to interact with enterprise capabilities through a simple AI-powered experience.

The assistant isn't just retrieving information from a single system. It's combining knowledge from across ZillaForge's products, customer demand, fulfilment, and operational data to provide more informed recommendations and business insights.

Let's look behind the scenes and see how ZillaForge exposed these enterprise capabilities as AI-ready tools and how IBM DataPower Interact Gateway governs and secures those interactions.
