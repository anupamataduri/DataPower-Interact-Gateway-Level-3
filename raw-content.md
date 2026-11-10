# DataPower Interact Gateway Technical Sales Level 3 Demo Guide
#### [Made by Anupama Taduri with Scribe](https://scribehow.com/o/xahtdQVjS0CP_tfALhqR3A/viewer/DataPower_Interact_Gateway_Technical_Sales_Level_3_Demo_Guide__2ES4O8hsTMu4qBlAOSj7sA)
Anupama Taduri: anupama.taduri@ibm.com
Matthew Barnes: matthew.barnes1@ibm.com
Christian Kopecki: Christian.Kopecki@ibm.com

#### Introduction


1\. Welcome to the DataPower Interact Gateway Level 3 Enablement Demo Guide. This guide is designed to provide technical sales professionals and business partners with a comprehensive understanding of IBM DataPower Interact Gateway. Through a real-world enterprise AI adoption scenario and a guided stand-and-deliver demonstration, this guide will equip learners with the knowledge and confidence needed to articulate how organizations can govern, secure, observe, and scale AI-initiated interactions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/b4429c6f-6b3a-4c4d-a20b-4ab0276eb290/matched_image_action_0_7ac24fd2ed924cd9be4fe9285b658a98_text_export.jpeg)


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


#### **Important Update: Demo Environment Availability**


Alert: The Interact Gateway environment as part of API Connect SaaS used to develop this course and demo has been retired for the time being. As a result, you will not be able to complete the exercises in a live TechZone environment. We are working on updating the course to the Interact Gateway stand-alone environment.

In the meanwhile, to ensure you can still complete the Level 3 enablement requirements, the **DataPower Interact Gateway Level 3 Clickthrough Demo** should be used as the primary demonstration experience. The clickthrough provides a guided walkthrough of the complete ZillaForge scenario and covers all screens and workflows included in the original live demo.

The objective remains the same: demonstrate the ability to position, explain, and showcase the capabilities of IBM DataPower Interact Gateway to a client audience.


6\. **Using the Clickthrough Demo** 

1. Launch the [**DataPower Interact Gateway Level 3 Clickthrough Demo**](https://yourlearning.ibm.com/activity/URL-D97B2BBEB1C5?planId=PLAN-B3CBC277DE69&sectionId=SECTION-A&planIdFromParentTab=PLAN-B3CBC277DE69&sectionIdFromParentTab=SECTION-A&planIdForChildTab=PLAN-B3CBC277DE69).
2. You can turn off the dialog boxes and beacons while presenting.
3. Progress through each section of the ZillaForge scenario in sequence.
4. Use the provided narration and seller talking points from this guide when presenting.
5. Advance through the clickthrough screens while explaining the business challenge, solution, and outcomes.
6. Use the Demo Evaluation Checklist to verify that all required topics have been covered.


#### Demo Guideline


7\. **Use Case Introduction**\
\
ZillaForge, a fictional global leader in industrial automation, is entering a new phase of digital transformation by adopting AI assistants and agents to automate work, accelerate decision-making, and interact directly with enterprise systems. While the company has already invested in APIs, integrations, and reusable business services, it now faces a new challenge: how to safely expose those capabilities to AI while maintaining security, governance, and visibility.

To address this challenge, ZillaForge adopts IBM DataPower Interact Gateway. 

This transformation story forms the foundation of the Level 3 course. Through a guided stand-and-deliver demonstration, learners will see how organizations like ZillaForge can safely scale AI adoption by governing AI-initiated interactions without rebuilding existing systems or creating a separate AI governance stack.


8\. **Demo Overview**

This demo provides a guided walkthrough of IBM DataPower Interact Gateway in the context of ZillaForge's AI adoption journey. It highlights how organizations can govern AI-initiated interactions while continuing to reuse existing APIs, integrations, and workflows.

Learners will observe how key capabilities, such as governed interaction entry points, policy enforcement, enterprise asset reuse, and runtime observability, work together to provide security, visibility, and operational control for AI-driven interactions. Each stage of the demo aligns to a business challenge, showing how interaction governance helps organizations scale AI adoption with confidence.

The experience is read-only and follows a structured stand-and-deliver format, allowing learners to explore the interaction flow, governance controls, and observability views without performing any setup, configuration, or administration tasks.


#### Demo Script


9\. **Overview and Architecture**

**Note to Learners**: The slides used in this section can be found [HERE](https://ibm.seismic.com/Link/Content/DCR6bJQ9J86M8GWP7cR79QJPG8J3).

**Narration:**

ZillaForge, a fictional global manufacturer of industrial automation equipment, is expanding its use of AI assistants and agents to improve productivity, automate decision-making, and accelerate business processes. The company has already invested heavily in APIs, integrations, workflows, and governance, creating a strong digital foundation of reusable business capabilities.

As AI adoption grows, ZillaForge faces a new challenge. AI assistants and agents need access to those same enterprise capabilities, but traditional governance models were designed for applications, not autonomous AI interactions. The company needs a way to maintain visibility, security, and operational control as AI-driven activity scales across the business.

To address these challenges, ZillaForge adopts IBM DataPower Interact Gateway. Acting as an AI mediation governance gateway, it helps the company govern AI interactions, expose existing enterprise capabilities to AI without rebuilding them, and apply consistent security, policy enforcement, and observability across AI-driven traffic. This demo follows ZillaForge's AI adoption journey, showing how Interact Gateway enables organizations to reuse existing APIs, integrations, and business services while bringing AI-initiated interactions under a consistent governance model.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/938d0203-4875-4a69-8b7c-f305b939f0f5/matched_image_action_24_68efee6a947840c48e133f62a77310f8_text_export.jpeg)


10\. **Narration:**

This illustration represents the architecture used in the ZillaForge demo and the digital foundation the company established before introducing AI. It shows how years of investment in APIs, application integration, events, governance, and reusable business services created a platform of enterprise capabilities that can now be safely consumed by AI assistants and agents.

At the center of the architecture is the ZillaForge Digital Business Platform, governed through a Hybrid Control Plane that provides centralized visibility, management, analytics, and governance across cloud, on-premises, and edge environments. Around it are the core integration capabilities, including API management, application integration, event management, B2B integration, managed file transfer, and monitoring services, all working together as shared enterprise services.

Rather than creating new capabilities for AI, ZillaForge can reuse the APIs, integrations, workflows, and business services it has already built and expose them as governed AI-ready capabilities.

This architecture forms the foundation for the rest of the demo. Throughout the walkthrough, learners will see how ZillaForge extends its existing digital investments to support AI adoption while maintaining the governance, visibility, and operational control required at enterprise scale.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1ff74f4d-8d35-4945-b6a3-9818949d4611/matched_image_action_25_b0d6c87ceeda4012aa26f51ea3a36c02_text_export.jpeg)


11\. **Narration:**

ZillaForge has already begun adopting AI across different parts of the business. Teams are experimenting with AI services, connecting them to business applications, and enabling access to enterprise capabilities. In the early stages, these initiatives are often managed independently, with individual teams using their own model access, credentials, and integration approaches. While this works for small-scale experimentation, it quickly becomes difficult to manage as AI adoption expands across the organization.

As more AI assistants and agents begin interacting with enterprise systems, new governance challenges emerge. Organizations need to understand who is using which models, what business capabilities are being accessed, what policies are being applied, and how AI-driven activity can be monitored and controlled. Traditional governance models were designed for applications and APIs, not autonomous AI interactions. This creates a governance gap that requires a consistent control point where security, policies, credentials, monitoring, and visibility can be applied across all AI interactions. IBM DataPower Interact Gateway is designed to address that gap.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/9d4f4ba8-3c1a-417e-a161-0d3bd48d3d13/matched_image_action_26_ddf611bead11494c979d968e8e4d12d2_text_export.jpeg)


12\. **Narration:**

IBM DataPower Interact Gateway sits between AI consumers and enterprise systems, providing a controlled interaction layer that governs and secures AI-driven interactions.

Think of Interact Gateway much like an API gateway for the AI era. It doesn't build the applications, models, or agents. Instead, it governs how they interact with enterprise services. APIs provide capabilities, events provide awareness, workflows provide guardrails, and policies provide trust. Together, these elements enable organizations to scale AI interactions with the visibility, security, and control required for enterprise adoption.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/96c28c7f-bb98-4aaf-bc1d-57e753df459f/screenshot_b0b0d75c095849edb6fc3e61dba5152b_text_export.jpeg)


#### Part 1: ZillaForge AI Assistant for Internal Operations Queries


13\. **Narration:**

ZillaForge employees access a centralized Operations Portal to interact with enterprise information and capabilities. Rather than navigating multiple systems, users can simply ask questions through an AI-powered assistant integrated directly into the portal.

The assistant is connected to enterprise capabilities through an MCP endpoint exposed by the Interact Gateway, allowing users to ask business questions in natural language and receive answers from governed enterprise data and services.

The goal is to demonstrate how AI can safely access enterprise capabilities through a controlled, observable interaction layer.


14\. **Actions:**

Navigate to <http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a1bd530-d04c-4428-89d4-91fa2cf62a68/action-9b94ee5d40b2468eaf5b516006a56eac_ddfe585d843748e490ba932179a27785_text_export.jpeg)


15\. **Narration:**

Now let's see how a business user interacts with enterprise capabilities through the AI assistant.

From the user's perspective, this is a simple conversational experience. Behind the scenes, however, the interaction is routed through a governed entry point where security, policies, credentials, and observability are applied consistently.


16\. **Actions:**

Click the ZillaForge **AI assistant** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/560bc599-d52f-495e-9fc0-63671268bda8/user_cropped_screenshot_e6ecc1d15803420d8118dfb93fb501c5_text_export.jpeg)


17\. Let's start with a few business questions. In the Input field, type the first question "**What products are offered for predictive maintenance and industrial monitoring?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/824e5cf5-0417-445f-a709-27c7e5d539af/user_cropped_screenshot_2a24a7bfdd2345e5a3ca4ecf4e32f518_text_export.jpeg)


18\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/39500f3f-c311-4c44-ae4a-35075daa3d72/user_cropped_screenshot_4f41340d8cda457897a3137c2c7cc8c2_text_export.jpeg)


19\. The assistant has found the available products.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0adcc52b-9cea-44a8-bd18-46f76b49c09c/user_cropped_screenshot_3d7b30e320b149f597bf5f1107d0b7b7_text_export.jpeg)


20\. **Narration:**

Let's take that a step further. Rather than simply finding information, we'll now ask the assistant to analyze what it knows about ZillaForge's products and make a recommendation based on a customer's business requirements.

This allows the assistant to combine information from multiple ZillaForge capabilities, apply reasoning, and recommend the solution that best aligns with the customer's needs. Instead of just discovering available products, we're using enterprise knowledge to support a real business decision.


21\. **Actions:**

In the Input field, type the question "**Which ZillaForge product would you recommend for a factory looking to reduce unplanned equipment downtime?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/89485a69-19cb-4eeb-be0f-df6c8c1d0c4b/user_cropped_screenshot_d1ae48c34d9144c5a99dd6472b6173ae_text_export.jpeg)


22\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/33364435-7b54-401a-b562-d62ad704102c/user_cropped_screenshot_c7e7adbee43b4d86b7f79c83d9f04043_text_export.jpeg)


23\. Click **Show more** to see the entire response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/948adec9-784c-4179-bc70-5a7729d669f1/user_cropped_screenshot_2410f137f2e9401fa52a4c97ab2f7074_text_export.jpeg)


24\. Notice that the assistant hasn't simply picked a product. It's recommended a complete solution and explained why the products work together.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/206803c5-6667-42af-b53d-6ff5820e8ef6/user_cropped_screenshot_2011de6bf8cf4597bc15b4988b2d686f_text_export.jpeg)


25\. **Narration:**

Let's now see if the assistant can connect recommendations to operational data across the business.

Within ZillaForge, product information, customer demand, and fulfilment activity exist across multiple enterprise systems. The real value comes when the assistant can combine information from those different capabilities to provide meaningful business context and actionable insights.


26\. **Actions:**

In the Input box, type **"Which customer orders related to predictive maintenance solutions are currently awaiting fulfilment?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/96f80c47-9360-4453-a456-2358008dbc09/user_cropped_screenshot_9765d8c8655d47a5b35249dd6ada02ff_text_export.jpeg)


27\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/2fcc5813-7f88-4863-b064-eec19a75701d/user_cropped_screenshot_95aaf0a484d443f69fd14dbdb4e4aa9c_text_export.jpeg)


28\. Click **Show more** to see the full response.

Here the assistant has identified the customer orders that are currently awaiting fulfilment and related to predictive maintenance solutions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/248ad69c-22e8-44bf-9886-6b462f7b74dd/user_cropped_screenshot_18413f9043ae423a8c954e7ce7cf06b7_text_export.jpeg)


29\. **Narration:**

So far, we've seen how the assistant can help answer questions about ZillaForge products and connect those recommendations to customer demand and fulfilment activity.

Let's now move from business demand into operational performance. One of the key priorities for ZillaForge customers is improving asset reliability across manufacturing environments while reducing unplanned downtime and maintenance costs.

To answer this question, the assistant needs to do more than look up product information. It must understand the customer's business objective, evaluate the available ZillaForge solutions, and recommend the option that best aligns with operational needs.


30\. **Actions:**

In the Input box, type "**A customer wants to improve asset reliability across multiple manufacturing sites. Which ZillaForge solution would you recommend and why?“**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/a53441fd-e7e0-4fe8-94ad-6fceda4a3ceb/user_cropped_screenshot_a6f183047c7a4b7994c7fde8ddcf4cf2_text_export.jpeg)


31\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/93ade370-b968-4dc2-b5a6-0ba9d182987f/user_cropped_screenshot_3071807474ed458eb04cf071ea433c37_text_export.jpeg)


32\. The recommendation is supported by operational information. You can see several assets with elevated failure risk. The assistant is also identifying a pattern across multiple sites rather than highlighting an isolated device issue.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0cbd481a-02d7-4e7b-a353-189fdd79738d/user_cropped_screenshot_006576a6ad7e4f449a5cee54ef4798ec_text_export.jpeg)


33\. **Narration:**

Let's finish with our most comprehensive scenario. A customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation and wants to understand which ZillaForge solution best supports that strategy.

This question requires the assistant to bring together multiple sources of information. It needs to understand the available ZillaForge products, consider existing customer demand, and factor in planning and deployment considerations before making a recommendation.

Rather than looking at a single system or data source, the assistant must combine information from across the business to provide a complete answer.


34\. **Actions:**

In the Input field, type "**A manufacturing customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation. Which ZillaForge products best support this strategy, and what existing customer demand should the business be aware of before planning deployment?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/8abd49d9-883b-417c-aa0d-73c2e5a7c63d/user_cropped_screenshot_0a2957db451043faa3c6d13e26d8d144_text_export.jpeg)


35\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/40a45308-5a99-4f0a-b594-243fd8ebd130/user_cropped_screenshot_a2c95e592c7740278de29f29bd5ca577_text_export.jpeg)


36\. The assistant has recommended the ZillaForge solutions that best align with the customer's digital transformation objectives while also highlighting existing customer demand that should be considered during planning.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/53f13ebd-25f0-454b-b62e-855d64343560/user_cropped_screenshot_4104742940b4469ea5fb5d4218762464_text_export.jpeg)


37\. **Wrap-up:**

We've seen how the ZillaForge Operations Portal allows users to interact with enterprise capabilities through a simple AI-powered experience.

The assistant isn't just retrieving information from a single system. It's combining knowledge from across ZillaForge's products, customer demand, fulfilment, and operational data to provide more informed recommendations and business insights.

Let's look behind the scenes and see how ZillaForge exposed these enterprise capabilities as AI-ready tools and how IBM DataPower Interact Gateway governs and secures those interactions.


#### Part 2: Explore Governed MCP Tools


38\. **Narration:**

So far, we've focused on the experience of the business user. We saw how employees can interact with ZillaForge's enterprise capabilities through a simple AI assistant and receive recommendations, insights, and answers drawn from systems across the organization.

Now, we'll look at how ZillaForge used IBM DataPower Interact Gateway to transform existing enterprise services into AI-ready capabilities.


39\. **Narration:**

We're now in API Connect. Here we're looking at the existing enterprise APIs that provide the business capabilities used across the ZillaForge environment.

One of the key concepts behind Interact Gateway is that ZillaForge isn't creating new back-end services specifically for AI. Instead, the company is reusing the APIs it has already invested in and exposing them in a way that AI assistants and agents can safely consume.

This approach allows ZillaForge to leverage existing enterprise assets while maintaining the governance, security, and operational controls already established across the organization.

To do that, ZillaForge created a project dedicated to its MCP tools. Let's open that project and see how existing enterprise capabilities are transformed into AI-ready tools that can be consumed through Interact Gateway.


40\. **Actions:**

In API Connect, click the project **ZFmcp**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/9c3b83a4-9500-4eaf-be08-60d0e5197550/user_cropped_screenshot_0590c3369a8149c89e33ec94513f9ab7_text_export.jpeg)


Tip: **Important:** Once you open the project, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.


41\. Click **API View**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c4c921db-780c-4b42-803a-06a68e67b617/user_cropped_screenshot_eee88bc3719440f2995d4c7eed91117b_text_export.jpeg)


42\. Select **AI View**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/47573a9a-6a0d-4908-ab43-b18c4eb4780e/user_cropped_screenshot_a5574f289b3f4b90aa0f7312be22c0ee_text_export.jpeg)


43\. **Narration:**

Here are the MCP servers that ZillaForge created from its existing enterprise APIs and services.

The underlying APIs haven't changed. ZillaForge is still using the same product, inventory, and order services that already exist within the business. The difference is that those capabilities have now been exposed as MCP tools that AI assistants and agents can discover, understand, and invoke.

In the first part of the demo, we saw the AI assistant answering questions about ZillaForge products, customer demand, fulfilment activity, and operational performance. Those answers were made possible because the underlying enterprise capabilities were exposed as MCP tools that the assistant could access through the Interact Gateway.

Let's open the MCP servers and see how ZillaForge transformed existing enterprise APIs into an AI-ready capability.


44\. **Actions:**

In the Explorer pane, under MCP servers, click **factoryapis-server-n9ipb.**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5dc0052a-88cb-428a-97b1-74bf5b147fed/user_cropped_screenshot_0a60625054494bebb2a9bc09eaef8c7d_text_export.jpeg)


45\. **Narration:**

Here we can see the MCP server that was generated from the Factory API. The operations defined in the original API have been converted into AI-ready MCP tools, such as list_device and list_service_request.

Each MCP tool represents a business capability that AI assistants and agents can discover and invoke.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/4e36a056-1169-4b85-9adb-48752628a1db/user_cropped_screenshot_0269be1a3c4542f88f83e487d860a92c_text_export.jpeg)


46\. **Narration:**

ZillaForge has also created MCP servers for its Inventory API and Order API, following the same approach.


47\. **Actions:**

Click **inventoryapis-server-ow85v** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/015c50f5-1e9c-42f6-b179-1a7fd47ff7d1/user_cropped_screenshot_5046e724d38f4df8a413ffa80113689b_text_export.jpeg)


48\. Click **orderapis-server-lzsrh** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/7a2212ca-9305-446b-b7c5-9be6fa71db82/user_cropped_screenshot_38c8c5f6e71c424996636951785ffb47_text_export.jpeg)


49\. **Narration:**

The next step for ZillaForge is to apply governance.

Here, we're looking at the policy flow associated with the MCP tools. ZillaForge uses policy sequences to govern how AI assistants and agents interact with enterprise services before requests ever reach the backend systems.

These policies allow ZillaForge to apply security, transformation, rate limiting, authorization and other controls consistently across AI interactions. This is where IBM DataPower Interact Gateway moves beyond simply exposing APIs as AI tools.


50\. **Actions:**

Under Policy sequences, click the policy **zfmcp-freeflowpolicysequence-lzsrh1.0.**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5b008085-c426-48f5-8af4-e7078d7fd3d8/user_cropped_screenshot_eca356531dca4549866af6350efc799b_text_export.jpeg)


51\. **Actions:**

In the Assembly flow, click the **Invoke** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ca5171a2-e4bf-4aa3-bce9-c4c8119f9aa8/user_cropped_screenshot_d51e1f70f93c4df98a5e47fbd3519a73_text_export.jpeg)


52\. **Narration:**

The MCP tools used by the ZillaForge Operations Portal are connected to an existing API that is already hosted and managed in webMethods API Gateway.

This reinforces an important principle behind ZillaForge's AI strategy: there is no need to build new back-end services specifically for AI. Instead, existing enterprise capabilities that are already exposed, managed, and governed through API management platforms can be reused and made available to AI assistants and agents through the Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/418732d1-7abb-4486-8e36-838ca6dcdd4a/user_cropped_screenshot_38f3f62dc2a5416c9f4417e8838c1112_text_export.jpeg)


53\. **Actions:**

Click the **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/030cc10e-e154-4703-9928-5b16a2c9eaeb/user_cropped_screenshot_28f5f21faeed4262bff62e80ee7be397_text_export.jpeg)


54\. This policy sets the required request headers to ensure the MCP tool sends properly formatted requests to the backend API.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ee1a951f-594e-487c-beb7-93ed69a86425/user_cropped_screenshot_695dd9aa0cc74a11995da180daf8cd83_text_export.jpeg)


55\. Click the next **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/11a1b855-8b8f-42d2-964c-115548a0445d/user_cropped_screenshot_bbd718414e2d4a5ba68bff0c5b83f730_text_export.jpeg)


56\. **Narration:**

Here we're supplying the required API key. The purpose here is simply to validate the API and confirm the capability is working correctly.

This is a good example of how existing security controls continue to apply. The MCP tool doesn't bypass the API's security requirements; it consumes the API using the same governance and authentication mechanisms already in place.


57\. Review the policy details and click the **Close** icon to close the pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/b2a47711-ef7e-46ec-b294-933909c62895/user_cropped_screenshot_03ed85c7b8e144a4a1eec144a2b3512d_text_export.jpeg)


58\. You can review the other two policies and see how they are set up.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/eddd7f01-9ad9-4cb3-84c3-067090db7fcf/user_cropped_screenshot_f3330851852b4d27b8fdd727f0fc0915_text_export.jpeg)


59\. **Narration:** 

Once the MCP tools have been published, they are exposed through a governed MCP endpoint that can be consumed by AI assistants, agents, and applications.

We'll now navigate to the catalog to locate the published MCP endpoint.


60\. **Actions:**

On the left navigation pane, click the **Manage** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/1efcefd4-e199-4bb1-a300-78377b6ea9e7/user_cropped_screenshot_516bda7148c34f0eae1b97d557a464cf_text_export.jpeg)


61\. Click **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/1a16ffbe-afdc-4ffd-8b62-8e754812bb8d/user_cropped_screenshot_f052129bb5f74dc9aa478fa4b8924f90_text_export.jpeg)


62\. You can see all the published assets in the Interact Gateway MCP catalog. If the list is long, you can choose to filter to view only MCP Servers.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/b6cb9f9d-2917-48a5-b83f-ed53fcd4c5f1/user_cropped_screenshot_03efed5b938f4daa98f1da6600db90df_text_export.jpeg)


63\. For the inventoryapis-server-ow85v, click the **three dots** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/0e920588-84ab-4e84-b8b4-8f9a85340585/user_cropped_screenshot_4f79f1a4ecc847aea01e13cb336a62b1_text_export.jpeg)


64\. Click **View endpoints**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/f33f9e4a-64a6-4d86-911a-b96a7fac87cb/user_cropped_screenshot_203da1f4df4a48eb9a19d339948eb9d2_text_export.jpeg)


65\. Click **Copy** to copy the endpoint. You can use this MCP endpoint with applications, assistants or AI agents as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/ce92a78f-e4b3-4da7-baec-055d09bd9878/user_cropped_screenshot_54497562631f47feab2cbad14ea15e63_text_export.jpeg)


66\. **Wrap-up:**

Rather than building new services for AI, ZillaForge reused existing enterprise APIs, applied governance policies, and published the resulting MCP tools through the Interact Gateway.

By following this approach, organizations can safely make enterprise capabilities available to AI assistants and agents while maintaining the security, control, and observability required for enterprise-scale AI adoption.


#### Part 3: Register and Govern LLM Providers


67\. **Narration:**

So far, we've seen how ZillaForge exposes enterprise capabilities as governed MCP tools that can be consumed by AI assistants and agents. ZillaForge also needs a way to manage and control access to the foundation models and LLM providers that power its AI experiences.

To address this, ZillaForge uses the Interact Gateway to register and govern LLM providers. In this demo, we'll use **Amazon Bedrock** as an example, but the same approach can be applied to other providers such as watsonx.ai, Azure OpenAI, Google Gemini, and other supported model providers.

Rather than allowing applications and agents to connect directly to external model endpoints, requests can be routed through Interact Gateway, where consistent security, access controls, policies, and observability can be applied.

This gives ZillaForge a centralized approach to AI governance. The organization can manage which models are available, control access to approved providers, monitor usage, and apply the same governance principles already used for APIs and enterprise services to its LLM interactions.


68\. **Narration:**

Before registering an LLM provider, ZillaForge performs a one-time setup activity to securely manage credentials and access tokens.

Organizations can securely store and manage secrets using AWS Secrets Manager, Azure Key Vault, or HashiCorp Vault. 

This approach improves security, simplifies credential management, and allows ZillaForge to securely authenticate with external LLM providers.


69\. **Actions:**

On the top right corner, click **Instance Settings**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/cdf08e5c-de48-4eed-b9bb-173e0d3037c4/user_cropped_screenshot_525f423749054bfc917f020aa9bc255f_text_export.jpeg)


70\. On the Instance settings page, click the **Secrets** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b0be1fa-802d-4868-b832-58276669d5ae/user_cropped_screenshot_c1896bfc14ba4928823a37a09967f29e_text_export.jpeg)


71\. Here you can connect to AWS Secrets Manager, Azure Key Vault or HashiCorp Vault to manage secrets for your Interact Gateway.

Click **Back** once you are done.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/6b20fa92-0d5d-46da-a67c-90fb43610a2e/user_cropped_screenshot_b7450098205f4cde9b52aee6a90861b2_text_export.jpeg)


72\. **Narration:**

Let's now look at how ZillaForge manages access to external foundation models. In this demo, ZillaForge has registered **AWS Bedrock** as an LLM provider.

We'll open the Bedrock project and examine how the provider was configured. In addition to the provider registration itself, you'll see the policy sequence associated with the LLM endpoint. Just as we saw with MCP tools, ZillaForge can apply governance controls before requests are sent to the model provider.


73\. **Actions:**

In API Studio, click the **ZFBedrock** project.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bb8644da-2f70-4d97-b1a1-655c7fc4091a/user_cropped_screenshot_390838e91dd04f1db6a0b9ee66888475_text_export.jpeg)


Tip: **Important:** Once you open the project, if you're not in AI view, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/26d22f12-8c4e-47e0-bcf9-0522c68d7f3c/screenshot_2e5ae0ce20204683befa6753533c23c0_text_export.jpeg)


74\. On the Explorer pane, under LLM providers, click **bedrock-conn | 1.0**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/ff941500-fe41-4dee-8230-38123bf8e5ee/user_cropped_screenshot_01a339c193a24b868d4efe01d17d6e2c_text_export.jpeg)


75\. **Narration:**

Here we're looking at the configuration of a registered LLM provider.

ZillaForge defined the connection details for the provider, including the base path and the specific model operations that should be exposed and available for use. In this example, four operations have been selected for consumption.

This gives ZillaForge control over which model capabilities are available to applications, assistants, and agents, ensuring that only approved operations are exposed through the Interact Gateway.


76\. **Actions:**

In the **Select operations to expose** drop-down, you can see that four operations have been selected. These are the operations exposed through the Interact Gateway that will be available for assistant, agents etc.

**Note**: You cannot view the operations here, since the environment is read-only. However you will be able to test them later in the demo.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/dbe9a9c8-181a-4796-b9ed-fbf496373982/user_cropped_screenshot_89633a39adbf477bbec26e6338219fa5_text_export.jpeg)


77\. **Narration:**

You can also view the connection details. This configuration defines how Interact Gateway connects to the external LLM service. You can see the provider URL, the authentication configuration, and the secret that will be used to securely authenticate requests.

Notice the API key secret name field. This references the secret that was configured earlier in the Secrets section.


78\. **Actions:**

Scroll down to view the connection details.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/dc822367-ef12-40be-afaf-15784401bf9f/user_cropped_screenshot_f75f458db4e943b1a265efd16cf8485f_text_export.jpeg)


79\. The TLS client profile, defines the TLS configuration used when establishing secure connections to the external provider.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5b45059f-29dd-469d-8205-5a8d8946f1d7/user_cropped_screenshot_24d6c4df2b0a47ab98b92571e6afdffe_text_export.jpeg)


80\. **Narration:**

Now let's look at the **policy sequence** associated with the Bedrock provider.

Just as we applied governance to MCP tools, ZillaForge can apply governance to LLM interactions. The policy sequence defines what happens when a request is sent to AWS Bedrock, allowing the organization to inspect, secure, transform, monitor, or control requests before they reach the external model provider.


81\. **Actions:**

Under LLM providers, click **freeflowpolicysequence-bedrock-conn-75trd**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/7d4b6c7a-74fd-4665-a77c-66027ab19ba1/user_cropped_screenshot_42afc80be0264101b7591edbef9ec00c_text_export.jpeg)


82\. Click **ExtractIdentity**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5e646565-b687-45a8-8fd5-e8288713d1d7/user_cropped_screenshot_53bdb31dada14aa4a839c4f09d52b506_text_export.jpeg)


83\. This operation extracts the client credentials from the incoming request by reading the **X-IBM-Client-Id** and **X-IBM-Client-Secret** HTTP headers. The identity information can then be used by subsequent policies for authentication, authorization, rate limiting, auditing, and other governance controls.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/fd06fa54-9383-4396-83dc-c387de165a5d/user_cropped_screenshot_85121fbb982b46d189a65828b0eb2c01_text_export.jpeg)


84\. Click the close icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/0787bffe-310c-4fc6-a2fd-802f642a6109/user_cropped_screenshot_cd5d673e726c49e68902ade2b12347e4_text_export.jpeg)


85\. Scroll to the right to view other operations.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/b245f547-7a54-4144-b392-84cfaee48a13/user_cropped_screenshot_32882767102d473f98829325a2092819_text_export.jpeg)


86\. Here you can see separate operations have been configured for **chat completions**, **embeddings**, and **model discovery**. Each operation represents a specific model capability that can be invoked through the governed provider endpoint.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/1121b197-9d4b-473a-ad53-120b6f990009/user_cropped_screenshot_8596d40a3e4546c489287161649f7b2e_text_export.jpeg)


87\. **Wrap-up:**

We've seen how ZillaForge can register external LLM providers, securely manage credentials and connectivity, and apply governance controls through policy sequences before requests reach the model provider.

By managing LLM access through the Interact Gateway, organizations can centralize security, enforce governance policies, control which model capabilities are exposed, and gain greater visibility into how foundation models are used across the enterprise.


#### Part 4: Discover and Consume AI Assets Through the Developer Portal


88\. **Narration:**

So far, we've focused on how ZillaForge creates, governs, and publishes AI-ready capabilities. The next step is to look at the consumer experience.

Now, we're moving into the **Developer Portal**, where published AI assets can be discovered and accessed by teams. This provides a central location for finding approved enterprise capabilities and understanding how they can be consumed.

Just as the Developer Portal has traditionally been used to discover APIs, ZillaForge can now use it to publish and share governed AI assets, making it easier for teams to find and consume trusted capabilities while maintaining enterprise governance and control.


89\. **Actions:**

From the left navigation menu, click **Manage.**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/cb078ced-a0f6-4173-94a6-944d256d1bcc/user_cropped_screenshot_39cd9d102036410ea0bcb2a0bd87c26e_text_export.jpeg)


90\. Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/11dcf64e-4343-4f1f-bf0f-80112b9921b3/user_cropped_screenshot_b57e26dc9ded40f5bcbf5d8db16fb505_text_export.jpeg)


91\. Click the **Catalog settings** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/47acdc6b-228a-448c-97a6-a277ef8ec332/user_cropped_screenshot_4a4c0ddc5e214d9cb1d0ac4128ed7dae_text_export.jpeg)


92\. On the left pane, click **Portal**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bc606c34-f154-407f-8965-1cc0835c321b/user_cropped_screenshot_bbe3808910c04392b03f32d8afd0d227_text_export.jpeg)


93\. Click the **Portal endpoint URL** link.<https://prod773957.devportal.a-fra-c2.apiconnect.ipaas.ibmappdomain.cloud>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/9ba68e95-0772-4fdb-bc40-76bbd6e5b77a/user_cropped_screenshot_7053ba36a380408ebbf2b9c1222a9ea1_text_export.jpeg)


94\. The Developer Portal is displayed. On the top bar, click **Sign in**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/87dbb946-5d15-4a31-8583-fc992753bb68/user_cropped_screenshot_ee940f080d7d422fa9c1198bf688896f_text_export.jpeg)


95\. Sign in with the Developer Portal log in details you received in your Techzone reservation email.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/48e04d5f-3e35-4bba-a70b-8277450e3448/user_cropped_screenshot_d26f0b0d4b6647e498a03a2c4378c5b0_text_export.jpeg)


96\. The Developer Portal home page is displayed. 

From the left navigation menu, click **Asset gallery**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/4ea36ee2-728c-497d-a32d-72ceca6b8c60/user_cropped_screenshot_a50a723a84764d84a38161a4f679be06_text_export.jpeg)


97\. **Narration:**

The Asset Gallery is where published AI assets become discoverable to consumers. We can see the MCP servers and capabilities that have been made available through the platform.

Think of this as the catalog where applications, assistants, and agents can discover the capabilities they're allowed to use.

Now that ZillaForge has registered and governed access to AWS Bedrock, we will validate the provider and its available model capabilities.


98\. **Actions:**

On the api-bedrock-conn-75rtd tile, click the **Tryout** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/043e0399-f8b2-4fa0-8551-3f5270ab0efd/user_cropped_screenshot_c20accf2e436488a9a7aa90aa0640a6f_text_export.jpeg)


99\. Here you can see the same four operations you noticed while registering the LLM and in the policy sequence.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/86dabc22-a72d-42d0-b698-79fc885f39ef/user_cropped_screenshot_347e7d67ae284b0ebceb35299fa1d7d4_text_export.jpeg)


100\. **Narration:**

Let's start by testing the Models operation. This operation retrieves the list of foundation models that are available through the AWS Bedrock provider. Applications, assistants, and agents can use this information to discover which approved models are available before they begin generating responses.

For ZillaForge, this is a simple but important validation step. We're confirming that the gateway can successfully connect to the provider, authenticate the request, and return a valid response. If this operation succeeds, we know the connection and governance configuration are working as expected.


101\. **Actions:**

On the left navigation pane, click **> /models** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/3bab6f78-77e9-486d-ac2b-11adcff763e6/user_cropped_screenshot_f8f788b0e78a4bd0a0c5ec506d8826e9_text_export.jpeg)


102\. Click **GET**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/6545ab6c-3103-4f0b-8805-5c6643976a3a/user_cropped_screenshot_ce5953a4a79347688cdbf04de806b2af_text_export.jpeg)


103\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/a1178fad-99e5-4a83-a062-3c72ca03582e/user_cropped_screenshot_a4cdabed61464179a6b0852202a5b8d7_text_export.jpeg)


104\. Scroll down to view the response.

You are now looking at the response from Bedrock. In this case, we're retrieving the models that are available for use.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/6d24bc4c-788b-4845-a401-5f563690c462/user_cropped_screenshot_38651eb9a286484dbe340be7a8364528_text_export.jpeg)


105\. **Narration:**

Next, let's test the **Chat Completions** operation, which is the capability the ZillaForge AI assistant uses to generate responses.

Chat Completions sends a prompt to the foundation model and returns a generated answer. This is the same type of interaction that powers conversational assistants, AI agents, recommendations, and question-answering experiences.

For ZillaForge, this test validates that a request can successfully pass through the Interact Gateway, have the appropriate governance policies applied, reach the approved LLM provider, and return a response. A successful result confirms that the end-to-end AI interaction is working as expected.


106\. **Actions:**

On the left navigation pane, click **> /chat/completions** to expand it and click **POST**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/e07a15b6-1fbc-4461-9869-8a53cffbf0fe/user_cropped_screenshot_8d1eeceaf3e64aea8b51baedc4aeaee0_text_export.jpeg)


107\. Click the **Request Body** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/4740b087-bd11-411c-8b16-8a378ca16af6/user_cropped_screenshot_0491d21ef8ce46e1a1937e6601777553_text_export.jpeg)


108\. **Narration:**

Now we will provide the prompt that will be sent to the model. In this case we are asking a simple question: "What is Amazon Bedrock? Explain in 3 short bullet points.“

The goal isn't the question itself, it's simply to prove we can send a prompt through the gateway and get a response back.


109\. **Actions:**

Copy and paste the following into the request body.

**{**

**"model": "openai.gpt-oss-120b",**

**"messages": \[**

**{**

**"role": "user",**

**"content": "What is Amazon Bedrock? Explain in 3 short bullet points."**

**}**

**\],**

**"max_tokens": 512**

**}**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/d2e5168d-ab88-414e-b6cf-a1d523c6be2b/user_cropped_screenshot_79c2d4b2520a45d7859a703967a020cc_text_export.jpeg)


110\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5484b4f7-bbac-411c-93eb-8ec4a76d75d3/user_cropped_screenshot_4a74de0702064db9846ab3fbacb5538e_text_export.jpeg)


111\. Scroll down to review the generated response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/a44ee566-3583-460b-98bc-6bd8c5331afa/user_cropped_screenshot_05699ed081234763bfcbe59861184e58_text_export.jpeg)


112\. **Wrap-up:**

We've seen how ZillaForge can securely connect to and govern external LLM providers through the Interact Gateway.

We registered AWS Bedrock as a provider, applied governance policies, and validated the available model capabilities. We then tested both model discovery and chat completions to confirm that requests can be routed through a governed endpoint and successfully reach the approved foundation model provider.

For ZillaForge, this provides a consistent way to manage, secure, and monitor access to foundation models while applying the same governance principles already used for APIs and enterprise services.


#### Part 5: Monitor and Optimize AI Interactions with Analytics


113\. **Narration:**

Throughout this demo, we've seen how ZillaForge governs AI interactions, publishes AI-ready capabilities, and manages access to LLM providers. The final step is visibility.

As AI adoption grows, organizations need to understand how AI assistants, agents, MCP tools, and LLMs are being used across the enterprise. Interact Gateway provides analytics and observability that help teams monitor usage, investigate individual transactions, identify performance issues, and understand adoption trends.

These insights help ZillaForge not only govern AI interactions, but also continuously optimize and improve them as usage scales across the business.


114\. **Actions:**

Switch back to API Connect. Click the **Manage** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/c513e7e9-cf4f-4c1a-a6b0-2b3caeb43b4e/user_cropped_screenshot_636fdc4ebada4d8ea4d988d1092e569e_text_export.jpeg)


115\. Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b40bdd3-98a5-488a-8de0-84d73e99da17/user_cropped_screenshot_a943a2fd0fbc410dbe931cf20bb6c184_text_export.jpeg)


116\. Let's view the analytics for the Inventory MCP server. For the inventoryapis-server-ow85v server, click the **Analytics** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/52cd1109-aeb2-42c3-8ace-7f69a24f6007/user_cropped_screenshot_127669bd2772453fb0839d42ead28423_text_export.jpeg)


117\. **Narration:** 

This is the **Discover** view, which provides a real-time view of MCP and AI interaction activity.

Here you can see interaction volume over time and a list of individual transactions, including status, method, response time, and other operational details. This allows ZillaForge teams to quickly identify activity patterns and drill into specific interactions for further investigation.


118\. **Actions:**

Click a transaction to drill-down and view more details.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/92134ee7-09db-4509-af3b-4b94794ef233/user_cropped_screenshot_852b46947f4c4f8ea0a06880a9943c31_text_export.jpeg)


119\. **Narration:**

Here we're looking at AI-Powered insights.

Rather than teams manually inspect logs and trace requests through the gateway, ZillaForge can use AI-generated summaries to quickly understand what happened during an interaction. The analysis automatically highlights key information such as request status, latency, policy execution, client details, and potential bottlenecks.


120\. **Actions:**

Click the **Backend request and response** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/defe04dd-0fea-4dd8-a950-792be0f784fa/user_cropped_screenshot_7c3dc6d9174f4e64a5120a3e225cb94a_text_export.jpeg)


121\. **Narration:**

This section provides ZillaForge with an end-to-end view of what happened during the interaction, including the incoming consumer request, the request sent to the backend service, the backend response, and the final response returned to the consumer.


122\. **Actions:**

Click the **Policy flow latencies** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/59ee5977-e9db-4d30-b5ab-21c4710e61b6/user_cropped_screenshot_784eea141b9f4389a31a78bb9cdf4b1a_text_export.jpeg)


123\. **Narration:**

This view shows the policy flow latency breakdown for a specific request, helping ZillaForge identify exactly where time was spent as the interaction moved through the gateway and pinpoint potential bottlenecks in the AI, MCP, or API processing pipeline.


124\. **Actions:**

Click the **Event record** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/57bd636f-e3b0-4f3c-92d3-6a4f94fd81aa/user_cropped_screenshot_2b87940bb0a44610adb2a9f4b64ed2c8_text_export.jpeg)


125\. **Narration:**

This view shows the raw event record for the transaction, giving ZillaForge complete access to the underlying request, response, consumer, gateway, and operational metadata that was captured during the interaction for auditing, troubleshooting, and compliance purposes.


126\. **Actions:**

Scroll down to view the complete record.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/6dc26ed3-063e-4749-95f3-220d0a79914a/screenshot_4b788ec5aa6b48219c5250bab1a3ae2a_text_export.jpeg)


127\. **Narration:**

Next, we'll move to reports. 

The Reports section helps ZillaForge move beyond individual transactions and understand broader usage trends across the platform.

Using these built-in reports, ZillaForge can monitor AI, MCP, and API adoption over time, identify the most active consumers and applications, track consumption patterns, analyze call volumes, and understand how enterprise capabilities are being used across the organization. These insights help platform teams make informed decisions around capacity planning, governance, optimization, and future AI investments.


128\. **Actions:**

In the Analytics side navigation, click **Reports** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/375799bb-7437-46e0-a188-269c649a9164/user_cropped_screenshot_3a8b9e8c3e0e455eae170aca9b8fd692_text_export.jpeg)


129\. Let's look at a few reports. Click **AI Platform report**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/eba8fe89-f735-48f6-9c47-6076b9552deb/user_cropped_screenshot_866c4e0a0fbf4aa0a8699cd918c67db5_text_export.jpeg)


130\. **Narration:**

The AI Platform Report gives ZillaForge a high-level view of how AI capabilities are being used across the organization.

This report summarizes overall platform usage, including total AI calls, provider adoption, consumer activity, success rates, and response time trends. The built-in AI Insights & Analysis feature automatically highlights key observations and recommendations, helping teams quickly identify usage patterns, provider concentration, performance trends, and potential areas for optimization.


131\. **Actions:**

On the AI Insights & analysis section of the report, click **Show detailed analysis**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/1f8a5d3d-3095-4c93-bbb2-ad12d6c856a0/user_cropped_screenshot_9558d277ae0940c4a233083b5a6fffa7_text_export.jpeg)


132\. Review Key Insights and recommendations. Scroll down to view other sections of the report.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/bdc886dd-c2d8-4703-89da-43394a744d3e/user_cropped_screenshot_b85a04576bb747dbb4a3b38f58b43647_text_export.jpeg)


133\. When you're done reviewing the report, click **Consumption report**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/ddb82e61-e99b-4a5d-b83a-8eb789142cff/user_cropped_screenshot_b9ae0a9e32f34b06b37603e4933a999e_text_export.jpeg)


134\. **Narration:**

The Consumption Report helps ZillaForge understand overall platform usage and consumption trends across its AI, MCP, and API assets.

By tracking call volumes and response status codes over time, ZillaForge can monitor platform adoption, identify growth patterns, and quickly spot increases in errors or unusual activity.


135\. **Actions:**

Scroll down to review all the sections of the report.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/d04863c5-735c-43a2-af22-f2b0b60f550f/user_cropped_screenshot_fe30826868df4bdc9b3fc165a3d862d2_text_export.jpeg)


136\. ### Narration:

Next, let's review some dashboards.

Dashboards gives ZillaForge a real-time operational view of its AI, MCP, and API ecosystem through a collection of role-based dashboards.

Unlike reports, which focus on historical trends and analysis, dashboards provide quick access to key metrics such as usage, consumers, applications, MCP activity, LLM usage, status codes, response times, and consumption patterns.

For ZillaForge, these dashboards provide a centralized view of enterprise AI adoption, helping teams make faster operational decisions and maintain visibility as AI usage continues to grow.


137\. **Actions:**

In the Analytics side navigation, click **Dashboards** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/84d79fef-f07e-4070-a0c2-4d9cc756d07d/user_cropped_screenshot_d1a2e077977e4935acd5f0e19ddab0d5_text_export.jpeg)


138\. Let's look at a few dashboards. Click **MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/64237f71-ff5e-4cd1-a409-5d2d1b48c17d/user_cropped_screenshot_3c4c746fcb9e4cd88baf10191e8f05c3_text_export.jpeg)


139\. **Narration:**

The MCP Dashboard gives ZillaForge visibility into how AI assistants, agents, and applications are using MCP-based capabilities across the organization.

From a single view, teams can track total MCP requests, monitor MCP server adoption, identify the most frequently used tools, and understand which MCP servers are generating the most activity. The usage trends and call patterns help ZillaForge understand which enterprise capabilities are delivering the most value and where demand is growing.


140\. **Actions:**

Scroll down to review various sections of the dashboard.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/14c339ed-1424-4505-a5a0-3e6c6c4b7adb/user_cropped_screenshot_5aa739fba3b84c81834ed5b44fc89726_text_export.jpeg)


141\. When you're done, click the **AI LLM** dashboard from the side navigation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/f89718a3-b839-4383-a199-ed0a4b2eacd1/user_cropped_screenshot_53cb3aa8c0a7428c9efa98154469c99d_text_export.jpeg)


142\. ### Narration:

The AI LLM Dashboard gives ZillaForge visibility into how foundation models are being used across the organization.

From a single dashboard, teams can track total LLM requests, token consumption, model utilization, response times, and usage patterns across consumers and applications. ZillaForge can see which applications are generating the most traffic, which consumers are using the most tokens, and which models are being used most frequently.

These insights are especially valuable for governance and cost management.


143\. **Actions:**

Review sections of the Overview tab. When you're done, click the **Detailed usage** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/9acfff80-584b-4d73-9012-56d7d7dd6fb2/user_cropped_screenshot_3efeeaf9d51748bfa177e8489d3e91b1_text_export.jpeg)


144\. Scroll down to review various sections describing detailed usage.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/584d10db-03fa-41b8-ba07-6097d788968e/user_cropped_screenshot_881ff071c859424b8b9a0d6ff142e66f_text_export.jpeg)


145\. When you're done, click the **Gateway** dashboard from the left navigation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/64134873-191c-457b-9fc8-d1d8902e85a5/user_cropped_screenshot_26e5d0ae698a49e78a3888ffd744413d_text_export.jpeg)


146\. **Narration:**

The Gateway Dashboard gives ZillaForge visibility into the health and performance of the gateway infrastructure that powers its AI, MCP, and API interactions.

From this dashboard, operations teams can monitor request volumes and latency for individual gateway instances and services. This helps ZillaForge determine whether traffic is being distributed evenly across the environment, identify underperforming gateways, and quickly spot potential performance bottlenecks.

By tracking gateway utilization and response times over time, ZillaForge can make informed scaling decisions, troubleshoot infrastructure issues faster, and ensure that AI and API workloads continue to perform reliably as adoption grows across the enterprise.


147\. **Actions:**

Click the gateway **Service** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/368586d6-23a2-4fd6-b448-5512bd4141f4/user_cropped_screenshot_674cf51852b6437e9ebadd9e43c9565d_text_export.jpeg)


148\. Scroll down to review various sections of the dashboard.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/cbd5408a-0e48-47f5-a68b-c817bb5df403/user_cropped_screenshot_b971119945a74447ad8c7c01c20fe19b_text_export.jpeg)


149\. **Wrap-up**

We've seen how ZillaForge uses analytics to gain visibility into AI, MCP, and API interactions across the organization.

For ZillaForge, analytics completes the governance story. It's not enough to expose and secure AI capabilities. Organizations also need the visibility to monitor usage, optimize performance, identify issues, and make informed decisions as AI adoption continues to scale across the enterprise.


#### Conclusion


150\. Throughout this demo, we followed ZillaForge's journey as it expanded the use of AI across the enterprise while maintaining the governance, security, and operational control required for enterprise-scale adoption.

What started as a simple business user experience, an AI assistant helping employees answer questions about products, inventory, orders, and operations, demonstrated a much larger story. Behind every interaction, ZillaForge used IBM DataPower Interact Gateway to govern how AI assistants, agents, enterprise services, and foundation models interact with one another.

Rather than building new back-end systems for AI, ZillaForge reused existing APIs and enterprise capabilities, exposed them as MCP tools, applied governance policies, securely connected to external LLM providers, and made those capabilities available for consumption through governed endpoints. Finally, analytics provided the visibility needed to monitor, troubleshoot, optimize, and scale AI interactions across the organization.