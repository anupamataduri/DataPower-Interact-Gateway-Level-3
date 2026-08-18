# DataPower Interact Gateway Technical Sales Level 3 Demo Guide
#### [Made by Anupama Taduri with Scribe](https://scribehow.com/o/xahtdQVjS0CP_tfALhqR3A/viewer/DataPower_Interact_Gateway_Technical_Sales_Level_3_Demo_Guide__2ES4O8hsTMu4qBlAOSj7sA)
Anupama Taduri: anupama.taduri@ibm.com
Matthew Barnes: matthew.barnes1@ibm.com
Christian Kopecki: Christian.Kopecki@ibm.com

#### Introduction


1\. Welcome to the DataPower Interact Gateway Level 3 Enablement Demo Guide. This guide is designed to provide technical sales professionals and business partners with a comprehensive understanding of IBM DataPower Interact Gateway. Through a real-world enterprise AI adoption scenario, business-focused discussions, and a guided stand-and-deliver demonstration, this guide will equip learners with the knowledge and confidence needed to articulate how organizations can govern, secure, observe, and scale AI-initiated interactions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/b4429c6f-6b3a-4c4d-a20b-4ab0276eb290/matched_image_action_0_2a1a1976fc19403a90828f130944154e_text_export.jpeg)


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


6\. The DataPower Interact Gateway demo environment runs in the cloud and can be reserved using the steps outlined in the next section. Once provisioned, you’ll receive all necessary access credentials.

Because the platform is developed and updated continuously, its interface may evolve over time. Screenshots in this guide may differ slightly from what you see in the live environment, but the core functionality remains the same. If something looks different, take a moment to explore, it’s part of the learning experience.

**Disclaimer:**\
Please be careful to stay within the demo path. Do not deviate, as changes could affect other users and disrupt the demo environment. Let's ensure everything runs smoothly for everyone involved.


#### Environment Access Request


7\. Login to IBM TechZone at: <https://techzone.ibm.com/search>

Search for in the **Search bar** **(A)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/cfdcb999-c19b-4694-a70d-56bab4033e04/matched_image_action_8_5089d6ca5df94d12b2fdc05a44467d68_text_export.jpeg)


8\. Select the webMethods Hybrid Integration L3 Enablement in the results by clicking on **Explore this collection (B)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/b81cdbdd-9553-433e-8d39-6d62202e86aa/matched_image_action_9_44cc16aae5ee4a5db0b85cde20c26dd2_text_export.jpeg)


9\. Select **Environments ** **(C)** from the left-hand side menu.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/137241cd-3a47-4104-8eee-3f4c4f836021/matched_image_action_10_b219d1c5dfea40dbaeadac4c1dccfa3c_text_export.jpeg)


10\. Hover over the IBM Cloud environment button and click on **Reserve it (D)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/4d405ae1-7a2f-4aa3-a86d-776674fe6a77/matched_image_action_11_e692dae8cb3241a8ab1e3e7901f67e01_text_export.jpeg)


11\. Select the **Education **tile** (E)**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/ba1a8a10-515d-4f64-b64f-581b46b4cb19/matched_image_action_12_329c189cc689437aad9d0143d88e324f_text_export.jpeg)


12\. 

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/6d3a2c51-d291-4462-9bb7-945350e2e355/matched_image_action_13_2831a07a1243492584b42d0502a35f25_text_export.jpeg)


13\. Provide Description as self-enablement.

Choose other fields as below.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/42e68503-f27a-43bb-9a0a-73475fd056f1/matched_image_action_14_f079744daca94fd1ba303cce91c29934_text_export.jpeg)


14\. Select terms and conditions checkbox and click **Submit (** **F** **)** button.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/4cc0ea81-1978-459c-bec5-b98d15c23b6c/matched_image_action_15_a2c9617b9c8442779526aa3b487deaf7_text_export.jpeg)


15\. You will receive an email when the environment is provisioned with instructions on how to access the environment.

**Note to learners**: This action could take up to 15-20 minutes


#### Accessing the Environment via IBM Technology Zone


16\. Click on the **View** **My Reservations** **(A)** link in the email.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1bf22aa4-9032-48f8-8716-fcc059de0b33/matched_image_action_17_b58bd68c5eda49d998e7884651f3b75d_text_export.jpeg)


17\. Click on **Open this environment** **(B)** on the reservation card.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/6152ca1f-f75d-4abe-80d5-d550f50d8421/matched_image_action_18_8cf7204e9970429a81c82c165555f9db_text_export.jpeg)


18\. Scroll down on the reservation details page and you can find the webMethods Hybrid Integration URL and credentials for B2B and MFT WebClient as below.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/5bcbae50-b1e3-4b30-85f6-7ecf66a3158d/matched_image_action_19_0c0503de1f044347b3a929e29fcf0b34_text_export.jpeg)


19\. Once you connect, bookmark the IBM webMethods Hybrid Integration home page and you should see the screen below.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1b87ca4a-7806-4ac2-9276-927e7babb36c/matched_image_action_20_55272a848d294722b3ff3a55373a2a77_text_export.jpeg)


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

**Note to Learners**: The slides used in this section can be found [HERE](https://ibm.seismic.com/Link/Content/DC633F9fdp9cC89T3QDhmmmFGqWB).

**Narration:**

ZillaForge, a fictional global manufacturer of industrial automation equipment, is expanding its use of AI assistants and agents to improve productivity, automate decision-making, and accelerate business processes. The company has already invested heavily in APIs, integrations, workflows, and governance, creating a strong digital foundation of reusable business capabilities.

As AI adoption grows, ZillaForge faces a new challenge. AI assistants and agents need access to those same enterprise capabilities, but traditional governance models were designed for applications, not autonomous AI interactions. The company needs a way to maintain visibility, security, and operational control as AI-driven activity scales across the business.

To address these challenges, ZillaForge adopts IBM DataPower Interact Gateway. Acting as an AI mediation governance gateway, it helps the company govern AI interactions, expose existing enterprise capabilities to AI without rebuilding them, and apply consistent security, policy enforcement, and observability across AI-driven traffic. This demo follows ZillaForge's AI adoption journey, showing how Interact Gateway enables organizations to reuse existing APIs, integrations, and business services while bringing AI-initiated interactions under a consistent governance model.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/938d0203-4875-4a69-8b7c-f305b939f0f5/matched_image_action_24_b3aa70e273d54dea8fa56f41de6d2b77_text_export.jpeg)


24\. **Narration:**

This illustration represents the architecture used in the ZillaForge demo and the digital foundation the company established before introducing AI. It shows how years of investment in APIs, application integration, events, governance, and reusable business services created a platform of enterprise capabilities that can now be safely consumed by AI assistants and agents.

At the center of the architecture is the **ZillaForge Digital Business Platform**, governed through a **Hybrid Control Plane** that provides centralized visibility, management, analytics, and governance across cloud, on-premises, and edge environments. Around it are the core integration capabilities, including API management, application integration, event management, B2B integration, managed file transfer, and monitoring services, all working together as shared enterprise services.

Rather than creating new capabilities for AI, ZillaForge can reuse the APIs, integrations, workflows, and business services it has already built and expose them as governed AI-ready capabilities.

This architecture forms the foundation for the rest of the demo. Throughout the walkthrough, learners will see how ZillaForge extends its existing digital investments to support AI adoption while maintaining the governance, visibility, and operational control required at enterprise scale.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1ff74f4d-8d35-4945-b6a3-9818949d4611/matched_image_action_25_e9537164cdb84fda8f0b4db4bc27261c_text_export.jpeg)


25\. **Narration:**

ZillaForge has already begun adopting AI across different parts of the business. Teams are experimenting with AI services, connecting them to business applications, and enabling access to enterprise capabilities. In the early stages, these initiatives are often managed independently, with individual teams using their own model access, credentials, and integration approaches. While this works for small-scale experimentation, it quickly becomes difficult to manage as AI adoption expands across the organization.

As more AI assistants and agents begin interacting with enterprise systems, new governance challenges emerge. Organizations need to understand who is using which models, what business capabilities are being accessed, what policies are being applied, and how AI-driven activity can be monitored and controlled. Traditional governance models were designed for applications and APIs, not autonomous AI interactions. This creates a governance gap that requires a consistent control point where security, policies, credentials, monitoring, and visibility can be applied across all AI interactions. IBM DataPower Interact Gateway is designed to address that gap

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/9d4f4ba8-3c1a-417e-a161-0d3bd48d3d13/matched_image_action_26_3d5c4c0955a74ad2b4922dcb2d5bfa15_text_export.jpeg)


26\. **Narration:**

As you saw earlier, ZillaForge already has APIs, integrations, events, and workflows that expose valuable business capabilities across the enterprise. The challenge is not creating new capabilities but allowing AI assistants and agents to access those capabilities safely and under enterprise control. That's where IBM DataPower Interact Gateway fits. It sits between AI consumers and enterprise systems, providing a controlled interaction layer that governs and secures AI-driven interactions. 

Think of Interact Gateway much like an API gateway for the AI era. It doesn't build the applications, models, or agents. Instead, it governs how they interact with enterprise services. APIs provide capabilities, events provide awareness, workflows provide guardrails, and policies provide trust. Together, these elements enable organizations to scale AI interactions with the visibility, security, and control required for enterprise adoption.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1a2652e8-eaf4-4a2d-b9b8-74bd3557b110/matched_image_action_27_29382ada22734bcd8b66ed4df4e53d50_text_export.jpeg)


#### Part 1: ZillaForge AI Assistant for Internal Operations Queries


27\. In the first part of the demo, you will explore the ZillaForge Operations Portal and interact with an AI-powered assistant. The assistant is connected to enterprise capabilities through an MCP endpoint exposed by IBM DataPower Interact Gateway, allowing users to ask business questions in natural language and receive answers from governed enterprise data and services.

The goal is to demonstrate how AI can safely access enterprise capabilities through a controlled, observable interaction layer.


28\. **Narration:** \
ZillaForge employees access a centralized Operations Portal to interact with enterprise information and capabilities. Rather than navigating multiple systems, users can simply ask questions through an AI-powered assistant integrated directly into the portal.


29\. **Actions:**

Navigate to <http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a1bd530-d04c-4428-89d4-91fa2cf62a68/action-9b94ee5d40b2468eaf5b516006a56eac_82b91a0e5b2b470bbe699649c6e9e20c_text_export.jpeg)


30\. **Narration:**

Now let's see how a business user interacts with enterprise capabilities through the AI assistant.

Rather than searching through product documentation, CRM systems, knowledge bases, or multiple business applications, the user simply asks a question in natural language. 

What's important is that the AI assistant already has access to governed enterprise capabilities through the MCP endpoint exposed by IBM DataPower Interact Gateway. When the user submits the request, the assistant can discover and invoke the appropriate enterprise tools and services without requiring the user to know where the information resides or which systems need to be accessed.

From the user's perspective, this is a simple conversational experience. Behind the scenes, however, the interaction is routed through a governed entry point where security, policies, credentials, and observability are applied consistently. This allows AI to safely access trusted enterprise capabilities while maintaining enterprise control and visibility.


31\. **Actions:**

Click the ZillaForge **AI assistant** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/560bc599-d52f-495e-9fc0-63671268bda8/user_cropped_screenshot_46c2f17d0e0a471eb5939fd1ebee24d0_text_export.jpeg)


32\. Let's start with a few business questions. In the Input field, type the first question "**What products are offered for predictive maintenance and industrial monitoring?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/53a34139-fd50-48c5-842d-f50afe481de1/user_cropped_screenshot_56cb906cf5d8402eb27051ad79067ca6_text_export.jpeg)


33\. Click the **Send** button.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/39500f3f-c311-4c44-ae4a-35075daa3d72/user_cropped_screenshot_b60e4be372644ec585dbf5836e7dc9a3_text_export.jpeg)


34\. The assistant has found the available products.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0adcc52b-9cea-44a8-bd18-46f76b49c09c/user_cropped_screenshot_a5c590f1d6224113b387f02a718be1a9_text_export.jpeg)


35\. **Narration:**

Let's take that a step further. Rather than simply finding information, we'll now ask the assistant to analyze what it knows about ZillaForge's products and make a recommendation based on a customer's business requirements.

This allows the assistant to combine information from multiple ZillaForge capabilities, apply reasoning, and recommend the solution that best aligns with the customer's needs. Instead of just discovering available products, we're using enterprise knowledge to support a real business decision.


36\. **Actions:**

In the Input field, type the question "**Which ZillaForge product would you recommend for a factory looking to reduce unplanned equipment downtime?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/3c09775d-c481-450e-aad5-b42d6f48b50e/user_cropped_screenshot_dbc184b84e79449d9885927b2fef7f1e_text_export.jpeg)


37\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/33364435-7b54-401a-b562-d62ad704102c/user_cropped_screenshot_3ea967371725429ca2187fadbb4d0ec5_text_export.jpeg)


38\. Click **Show more** to see the entire response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/948adec9-784c-4179-bc70-5a7729d669f1/user_cropped_screenshot_3b49aca6f85e456f98ee7b35843ce1c3_text_export.jpeg)


39\. Notice that the assistant hasn't simply picked a product. It's recommended a complete solution and explained why the products work together.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/206803c5-6667-42af-b53d-6ff5820e8ef6/user_cropped_screenshot_f89f68db7a3b48e5993ceb7d4b5e9208_text_export.jpeg)


40\. **Narration:**

Let's now see if the assistant can connect recommendations to operational data across the business.

Within ZillaForge, product information, customer demand, and fulfilment activity exist across multiple enterprise systems. The real value comes when the assistant can combine information from those different capabilities to provide meaningful business context and actionable insights.


41\. **Actions:**

In the Input box, type **"Which customer orders related to predictive maintenance solutions are currently awaiting fulfilment?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/752948a8-2bb6-4d65-a0ce-c24f0371cf17/user_cropped_screenshot_55233e7ae6764b2ab8e89eef52f22644_text_export.jpeg)


42\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/2fcc5813-7f88-4863-b064-eec19a75701d/user_cropped_screenshot_1fddb9fc38ec4c5aa280a0c9d6a5025d_text_export.jpeg)


43\. Click **Show more** to see the full response.

Here the assistant has identified the customer orders that are currently awaiting fulfilment and related to predictive maintenance solutions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/248ad69c-22e8-44bf-9886-6b462f7b74dd/user_cropped_screenshot_3d40fa535d4a453b90c73b8f85ccc887_text_export.jpeg)


44\. **Narration:**

So far, we've seen how the assistant can help answer questions about ZillaForge products and connect those recommendations to customer demand and fulfilment activity.

Let's now move from business demand into operational performance. One of the key priorities for ZillaForge customers is improving asset reliability across manufacturing environments while reducing unplanned downtime and maintenance costs.

To answer this question, the assistant needs to do more than look up product information. It must understand the customer's business objective, evaluate the available ZillaForge solutions, and recommend the option that best aligns with operational needs.


45\. **Actions:**

In the Input box, type "**A customer wants to improve asset reliability across multiple manufacturing sites. Which ZillaForge solution would you recommend and why?“**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/1a1ec765-da6d-4d43-aa28-0095057ee727/user_cropped_screenshot_41dafa790f404dafb07191e00b13b111_text_export.jpeg)


46\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/93ade370-b968-4dc2-b5a6-0ba9d182987f/user_cropped_screenshot_160b35cafdb244cab4851330aef92d58_text_export.jpeg)


47\. The recommendation is supported by operational information. You can see several assets with elevated failure risk. The assistant is also identifying a pattern across multiple sites rather than highlighting an isolated device issue.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0cbd481a-02d7-4e7b-a353-189fdd79738d/user_cropped_screenshot_fdb55aed75d64716b21250740df83db4_text_export.jpeg)


48\. **Narration:**

Let's finish with our most comprehensive scenario. A customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation and wants to understand which ZillaForge solution best support that strategy.

This question requires the assistant to bring together multiple sources of information. It needs to understand the available ZillaForge products, consider existing customer demand, and factor in planning and deployment considerations before making a recommendation.

Rather than looking at a single system or data source, the assistant must combine information from across the business to provide a complete answer.


49\. **Actions:**

In the Input field, type "**A manufacturing customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation. Which ZillaForge products best support this strategy, and what existing customer demand should the business be aware of before planning deployment?**"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/dabc326d-07ea-483a-92fd-fef5f3f21a53/user_cropped_screenshot_9751c0f2160b45e0abdc05ef64ea0fd5_text_export.jpeg)


50\. Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/40a45308-5a99-4f0a-b594-243fd8ebd130/user_cropped_screenshot_e6b344fd20854972972538ba6b1481db_text_export.jpeg)


51\. The assistant has recommended the ZillaForge solutions that best align with the customer's digital transformation objectives while also highlighting existing customer demand that should be considered during planning.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/faf5b7b4-0e18-49d4-acbe-00c6e7fa6324/action-2db327eb64144416ba441953340d13c4_2933d5edc1ed4d728fe2e1a71984e6d4_text_export.jpeg)


52\. **Narration:**

We've seen how the ZillaForge Operations Portal allows users to interact with enterprise capabilities through a simple AI-powered experience.

The assistant isn't just retrieving information from a single system. It's combining knowledge from across ZillaForge's products, customer demand, fulfilment, and operational data to provide more informed recommendations and business insights.

Let's look behind the scenes and see how ZillaForge exposed these enterprise capabilities as AI-ready tools and how IBM DataPower Interact Gateway governs and secures those interactions.


#### Part 2: Explore Governed MCP Tools


53\. So far, we've focused on the experience of the business user. We saw how employees can interact with ZillaForge's enterprise capabilities through a simple AI assistant and receive recommendations, insights, and answers drawn from systems across the organization.

Now, we'll look behind the scenes at how ZillaForge used IBM DataPower Interact Gateway to transform existing enterprise services into AI-ready capabilities.


54\. **Narration:**

Here we're in **API Connect,** looking at the existing enterprise APIs that provide business data..

One of the key concepts behind IBM DataPower Interact Gateway is that ZillaForge isn't creating new back-end services specifically for AI. Instead, the company is reusing the APIs it has already invested in and exposing them in a way that AI assistants and agents can safely consume.

This approach allows ZillaForge to leverage existing enterprise assets while maintaining the governance, security, and operational controls already established across the organization.

To do that, ZillaForge created a project dedicated to its MCP tools. Let's open that project and see how existing enterprise capabilities are transformed into AI-ready tools that can be consumed through Interact Gateway.


55\. **Actions:**

Click the project **ZFmcp**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/9c3b83a4-9500-4eaf-be08-60d0e5197550/user_cropped_screenshot_9508a87196894324a3108fe622e1eb83_text_export.jpeg)


Tip: **Important:** Once you open the project, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.


56\. Click **API View**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c4c921db-780c-4b42-803a-06a68e67b617/user_cropped_screenshot_042ad074ba214e9f925e8930ef4c9f27_text_export.jpeg)


57\. Select **AI View**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/47573a9a-6a0d-4908-ab43-b18c4eb4780e/user_cropped_screenshot_e045d5739e0c46f285add20a110930ee_text_export.jpeg)


58\. **Narration:**

What we're looking at here are the MCP servers that ZillaForge created from its existing enterprise APIs and services.

The underlying APIs haven't changed. ZillaForge is still using the same product, inventory, order, and operational services that already exist within the business. The difference is that those capabilities have now been exposed as MCP tools that AI assistants and agents can discover, understand, and invoke.

In the first part of the demo, we saw the AI assistant answering questions about ZillaForge products, customer demand, fulfilment activity, and operational performance. Those answers were made possible because the underlying enterprise capabilities were exposed as MCP tools that the assistant could access through Interact Gateway.

Let's open the MCP servers and see how ZillaForge transformed existing enterprise APIs into an AI-ready capability.


59\. **Actions:**

Under MCP servers, click **factoryapis-server-n9ipb.**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5dc0052a-88cb-428a-97b1-74bf5b147fed/user_cropped_screenshot_86580bb365e54ff3bca7e4b8012c8b19_text_export.jpeg)


60\. **Narration:**

Here we're looking at one of the MCP servers created for ZillaForge's factory operations capabilities.

When creating an MCP server, you can start from an existing API, import an external API definition, or use APIs that are already registered and governed through Federated API Management. In this example, ZillaForge started with a Factory API defined in a YAML specification.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/a2b2e250-2702-407c-a7e2-429600ca7ae7/user_cropped_screenshot_f2eac3561f1a4609a37183173df84ff4_text_export.jpeg)


61\. **Narration:** 

ZillaForge has also created MCP servers for its **Inventory API** and **Order API**, following the same approach.


62\. **Actions:**

Click **inventoryapis-server-ow85v** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/015c50f5-1e9c-42f6-b179-1a7fd47ff7d1/user_cropped_screenshot_3432d3fdac5a42caaf024d04ad3c42fe_text_export.jpeg)


63\. Click **orderapis-server-lzsrh** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/7a2212ca-9305-446b-b7c5-9be6fa71db82/user_cropped_screenshot_af71585586504fb391df042801625a7d_text_export.jpeg)


64\. **Narration:**

The next step for ZillaForge is to apply governance.

Here, we're looking at the **policy flow** associated with the MCP tools. ZillaForge uses policy sequences to govern how AI assistants and agents interact with enterprise services before requests ever reach the backend systems.

These policies allow ZillaForge to apply security, transformation, rate limiting, authorization and other controls consistently across AI interactions. This is where IBM DataPower Interact Gateway moves beyond simply exposing APIs as AI tools.


65\. **Actions:**

Under Policy sequences, click the policy **zfmcp-freeflowpolicysequence-lzsrh1.0.**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5b008085-c426-48f5-8af4-e7078d7fd3d8/user_cropped_screenshot_5d06ebec83454fddacc7f4b3fc10dde7_text_export.jpeg)


66\. **Actions:**

In the Assembly flow, click the **Invoke** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ca5171a2-e4bf-4aa3-bce9-c4c8119f9aa8/user_cropped_screenshot_fe00f4789f9144db87ddefe24c3dde08_text_export.jpeg)


67\. **Narration:**

The MCP tools used by the ZillaForge Operations Portal are connected to an existing API that is already hosted and managed in **webMethods API Gateway**.

This reinforces an important principle behind ZillaForge's AI strategy: there is no need to build new back-end services specifically for AI. Instead, existing enterprise capabilities that are already exposed, managed, and governed through API management platforms can be reused and made available to AI assistants and agents through IBM DataPower Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/418732d1-7abb-4486-8e36-838ca6dcdd4a/user_cropped_screenshot_4f465d14b06c4658ac95b5578da38699_text_export.jpeg)


68\. **Actions:**

Click the Set node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/030cc10e-e154-4703-9928-5b16a2c9eaeb/user_cropped_screenshot_5e629cc6c083431abb725de189010af4_text_export.jpeg)


69\. This policy sets the required request headers to ensure the MCP tool sends properly formatted requests to the backend API.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ee1a951f-594e-487c-beb7-93ed69a86425/user_cropped_screenshot_5963553d35924a4ea036001afbecb548_text_export.jpeg)


70\. Click the next **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/11a1b855-8b8f-42d2-964c-115548a0445d/user_cropped_screenshot_112252034e9d4302bbad979ad4b26b4a_text_export.jpeg)


71\. Here we're supplying the required API key. The purpose here is simply to validate the API and confirm the capability is working correctly.

This is a good example of how existing security controls continue to apply. The MCP tool doesn't bypass the API's security requirements; it consumes the API using the same governance and authentication mechanisms already in place.

You can review the other policies as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/bcbefcbf-fb8b-43b4-90ce-993439f6ff51/user_cropped_screenshot_021f0ddc04d54cb4aa6580c977947ee6_text_export.jpeg)


72\. **Narration:**

At this point, ZillaForge has transformed existing enterprise APIs into AI-ready capabilities by generating MCP tools, enriching them for AI consumption, and applying the appropriate governance policies.

The final step is to publish those capabilities through the Interact Gateway. Publishing creates the governed MCP endpoint that serves as the entry point for AI interactions. This endpoint is what the ZillaForge Operations Portal used earlier when the AI assistant accessed product, inventory, order, and operational capabilities.


#### Part 3: Create and Publish MCP Tools from an Existing API


73\. **Narration:**

In the first part of this demo, we explored how ZillaForge transformed existing enterprise APIs into governed AI-ready capabilities using IBM DataPower Interact Gateway.

Now we will create governed MCP tools from an existing API. We'll discover API operations, select the capabilities to expose, apply enhancements, and prepare the tools for publication through IBM DataPower Interact Gateway. This workflow demonstrates how organizations can transform existing enterprise services into AI-ready capabilities without building new back-end systems.


74\. **Actions:**

From the left navigation pane, click the **API Studio** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/118f69d1-1bec-493c-aa85-adb7f701c698/user_cropped_screenshot_dda745e96e184b1683063644ad5b1eb8_text_export.jpeg)


75\. We will first create a new project. On the right, click **New API project**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/669c9e20-3d16-44a4-b4a3-5978820c66e2/user_cropped_screenshot_e1b0f884dc8345889829f91188e75f3c_text_export.jpeg)


76\. Click **Create a new project.**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/765531f1-3a67-4b8e-95d6-f4a105d89d3a/user_cropped_screenshot_b85dd4b09a6d4a4db901abe7d3cc9c13_text_export.jpeg)


77\. In the Project name field, type **ZillaForge<yourinitials><MonthYear>**. For example, **ZillaForgeATAug2026**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/3b71f395-e20d-4882-b300-cc90ac549a4c/user_cropped_screenshot_55af1c2fcc044497bdf9215db763572a_text_export.jpeg)


78\. In the Description field, type an optional description.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/80712d72-4f5f-43ae-9bf8-52d5d2f67123/user_cropped_screenshot_da760979cd6044fc966b03ccfa498006_text_export.jpeg)


79\. Leave the default value for the Save to field and click **Create**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/22f17469-8cd4-4e86-a753-f9969207fd16/user_cropped_screenshot_518004cebe374479a094dc5ba8f9882f_text_export.jpeg)


80\. Open the newly created project.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/0b2a5965-213b-4877-a9ed-3511ff9b3c0c/user_cropped_screenshot_5d835f95d8b74d5da96744c385b036a0_text_export.jpeg)


Tip: **Important:** Once you open the project, if you're not in AI view, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/26d22f12-8c4e-47e0-bcf9-0522c68d7f3c/screenshot_e7c7b6e3820e4694b144473c3f8dc813_text_export.jpeg)


81\. **Narration:**

Now, we will use an existing **Inventory API** and transform its operations into AI-ready MCP tools. The operations defined in the API specification are analyzed and converted into MCP tools.


82\. **Actions:**

Click **Generate MCP tools**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/e4c9c2bb-13b9-4f8d-bb6e-0eda9726a0b3/user_cropped_screenshot_9cdf7f5eb8f04bde9cdd2bf3d72d904c_text_export.jpeg)


83\. Click **Generate from REST API**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/8ecf30cd-ced8-4c25-b617-d724d7a3ae3a/user_cropped_screenshot_8232e708c33544128fe9d8c2785bb88a_text_export.jpeg)


84\. Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/06b95f49-17d4-4d65-b369-4ab11f8c37c2/user_cropped_screenshot_914b265fda8848809ae76cc431584387_text_export.jpeg)


85\. **Narration:**

When creating an MCP server, you can start from an existing API, import an external API definition, or use APIs that are already registered and governed through Federated API Management. In this example, we will use an existing Inventory API defined in a YAML specification.


86\. **Actions:**

Click **From external**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/56ce3068-90e9-4879-9076-b87dbd9f2f62/user_cropped_screenshot_f2f8a525bcc641a0abf3942d01715ade_text_export.jpeg)


87\. To upload the YAML file, click **Drag and drop an API file here or click to upload** and navigate to the **InventoryAPIs.yaml** file you downloaded earlier in the lab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/eb1a868c-7300-4cb1-ba71-a1b156142ea1/user_cropped_screenshot_d281f53ed01b4df2a8b4fe4234195268_text_export.jpeg)


88\. Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/f12476fe-efe1-428c-b7fe-473ad0944af8/user_cropped_screenshot_edcc89013c744bd5852134a6ab954fdf_text_export.jpeg)


89\. **Narration:**

As part of the MCP tool creation process, the operations defined in the API specification are identified and made available for conversion into MCP tools. Teams can choose exactly which operations should be exposed to AI, ensuring that only the intended business capabilities are available to assistants and agents while retaining control over sensitive or unnecessary functionality.


90\. **Actions:**

Let's select all the methods. Click the **expand** icon to view the /productcatalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/faeebd1a-b5e0-4565-9a58-55247880e987/user_cropped_screenshot_1acd407d5802453895bd58a32c72e83e_text_export.jpeg)


91\. Click the **expand** icon to view the /inventories.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2af5eac0-e872-4906-9fc9-6b682a7e372a/user_cropped_screenshot_d35e9bd43dfc4e53900b6da88b0c7809_text_export.jpeg)


92\. Select the top level checkbox to include all the paths and methods.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/abc8d8fd-9e5e-4624-ad61-7ab48f615e20/user_cropped_screenshot_c021fb9f9c66449ca5b3286ebeb83855_text_export.jpeg)


93\. Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/1545883d-ef8a-4fad-9e19-d5ff36623fa6/user_cropped_screenshot_9e29c4e4aa2745498bca7ae88feadc64_text_export.jpeg)


94\. **Narration:**

Once the tools have been generated, you can further improve how those capabilities are presented to AI by using the **MCP Server Enhancer**.

Tool names, descriptions, and parameter definitions can be refined to provide clearer instructions to AI assistants and agents. These enhancements help the AI better understand the purpose of each tool, when it should be used, and how it should be invoked.


95\. **Actions:**

Click **Enhance tools**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/eca2757d-918e-47af-bb33-01c25093a789/user_cropped_screenshot_c597185d435f44c09e7394f16c95962a_text_export.jpeg)


96\. You can see the enhanced tools names and descriptions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/074c2d14-5ac1-4fb6-9031-cf842e3f7179/user_cropped_screenshot_4fe673feed9c4a3cb67c691f5c9e6527_text_export.jpeg)


97\. Click **Apply all**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/90e4b2e9-17aa-4d72-af39-6efa8dbab0aa/user_cropped_screenshot_02bdbeed18784f379709c6a84d2ce021_text_export.jpeg)


98\. Review all the details and once you're done, click **Generate**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fbdf140c-039c-4257-9290-719cfa63a73d/user_cropped_screenshot_fe4fa9dcbe454576bd145a8ecaa66328_text_export.jpeg)


99\. **Narration:**

The MCP server has now been generated, and the selected API operations have been converted into AI-ready tools.

You'll notice that, in addition to the MCP tools, a **policy sequence** has also been created. If you're familiar with API Connect, this should look familiar. The policy sequence defines what happens when the gateway receives an MCP request, just as it would for a traditional API request.

The next step is to review and enrich this policy flow. These policies allow you to apply security, transformation, rate limiting, authorization, and other controls before a request reaches the backend service. Because governance is applied at the gateway layer, organizations can enforce consistent standards across AI interactions without modifying the underlying APIs or services.

This is where Interact Gateway moves beyond simple tool generation and becomes a governance layer for AI interactions. The key point is that AI requests can be governed using the same policy framework organizations already use for APIs, making it easier to extend existing governance practices to AI assistants and agents.


100\. **Actions:**

From the Explorer pane. click the policy under MCP servers.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/25b815c2-4f92-4189-8a96-b6f92f874f90/user_cropped_screenshot_eeadec39d0374ad8bbb8c8f19e585b72_text_export.jpeg)


101\. By default, there is only 1 operation. Click the **Invoke** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2140d5d2-fbb1-40c0-8491-b6f410cd11cb/user_cropped_screenshot_f2a8b6fc6a9e42bca42ad59504c6a614_text_export.jpeg)


102\. In the Invoke Policy pane, you can see that this existing API is hosted and managed in another environment through a webMethods API Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/79a0d25b-4d2f-431b-ae90-d578f8d75ad1/user_cropped_screenshot_b1b8bc5c74be47d0abc0b1d8d645fb8a_text_export.jpeg)


103\. Let's now add a new operation. Click the **plus** icon on the left of the Invoke operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/293b486d-e4a8-46f2-ba14-6a6026750f88/user_cropped_screenshot_c18ce47913f04e77aef0095fb8d21392_text_export.jpeg)


104\. Scroll down the assembly flow and click the **Set** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/0eee002a-88cf-4e68-961f-0ddd4c940a75/user_cropped_screenshot_7b774562b3494395a51f71f2174587a0_text_export.jpeg)


105\. Here we're supplying the required API key. The purpose here is simply to validate the API and confirm the capability is working correctly. 

In the Header name field, type **x-Gateway-APIKey**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/82d483cf-507b-4c91-b10e-f7ce15593dd8/user_cropped_screenshot_19a5e77567814069a84e220f79f4b1dc_text_export.jpeg)


106\. In the Value field, type **2d6bea7d-76d5-4b3f-8c6a-9dd2d5dc7bd7.**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/56120cf7-ba9c-428c-942e-d9d9158a5b8e/user_cropped_screenshot_a0dfdb202cba4895929609f020055947_text_export.jpeg)


107\. Click the close icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/d4939fa9-4c60-4c71-86f9-c835820ae2a7/user_cropped_screenshot_874f6a6db0384391bc48738827079800_text_export.jpeg)


108\. Let's add another operation to provide the required content type information expected by the API. . Click the **plus** icon on the left of the Set operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/045f9cd5-40af-4da9-adcb-b04a0e8e3cb0/user_cropped_screenshot_a6044ae66b8d409d89e77db99cc352f1_text_export.jpeg)


109\. Scroll down the assembly flow and click the **Set** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/a68b94be-94fc-4883-b2cd-3e444d245634/user_cropped_screenshot_5dbb572aecec4d4897c92c2e937ab8ce_text_export.jpeg)


110\. In the Header-name field, type **Content-Type**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4f6df508-1dbf-4151-ae27-07d766e2102a/user_cropped_screenshot_66c50fdea87249be8010a81d4449aeff_text_export.jpeg)


111\. In the Value field, type **application/json**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2d6c2e70-31c7-461a-9d2e-cd87fb463dd1/user_cropped_screenshot_cb6cd6eda3394cf1ae1ee5dfa9a17f89_text_export.jpeg)


112\. Click the **close** icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fab3fba2-51c6-4d76-a016-d49d3ca3e101/user_cropped_screenshot_5da937ac31784bc99baef0ad3a81e85a_text_export.jpeg)


113\. Finally, click **Publish** to publish the MCP tools through the Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4de26a1b-7913-4efb-b51b-6ad2ae7c2d62/user_cropped_screenshot_333bfffa44774a25887374a23298fce1_text_export.jpeg)


114\. From the Catalog list, select **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/65cbf8ea-c8d0-4d0f-a738-bf60a6aa57c9/user_cropped_screenshot_c9b6f706c1b64c03905501ce82458727_text_export.jpeg)


115\. Click **Next** to continue.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/991a56f0-223e-42a6-b22b-7b9146dfc079/user_cropped_screenshot_f276589617a54e90a2190ac0acfe9e24_text_export.jpeg)


116\. Expand the MCP Server to view all the associated assets and policy sequence.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/c93aa912-dcd9-4641-b7f1-25a62b727b2a/user_cropped_screenshot_0044e5e85f334a81a4bc9fcd0681c92a_text_export.jpeg)


117\. Click **Publish**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/115eb5df-5142-4f5b-8a77-88e1ec44cf99/user_cropped_screenshot_61a28f9f1e7d4fa68c2b9d29bb0a0dd5_text_export.jpeg)


118\. **Narration:**

Once the MCP tools have been published, they are exposed through a governed **MCP endpoint** that can be consumed by AI assistants, agents, and applications.

We'll now navigate to the catalog to locate the published MCP endpoint. This endpoint can then be configured in AI applications, allowing them to securely access the enterprise capabilities exposed through IBM DataPower Interact Gateway.


119\. **Actions:**

In the Publish successful notification, click **Catalog**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2c975c2e-277e-442a-b507-0f2e16c50f26/action-4ffb9d5a4cb049ceaf666b894da04b80_ce93949b4bd7463ab7861e0648fb210a_text_export.jpeg)


Tip: You can also locate the MCP endpoint by navigating to Manage > Interact Gateway MCP catalog.


120\. You can see all the published assets in the Interact Gateway MCP catalog. If the list is long, you can choose to filter by type.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fb12d17b-e293-4067-b2f2-3872f8506e67/user_cropped_screenshot_17f3143677d841e6b3e37b718b47fcc1_text_export.jpeg)


121\. Drag the scrollbar to scroll to the right.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/cec9e458-e23d-47ee-a34c-aa69664c25dc/user_cropped_screenshot_87524f6ae57f47869964fe3970dbed44_text_export.jpeg)


122\. For the newly published inventoryapis-server, click the **three dots** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/c5aeeb69-be05-42a8-8eb9-6dea5e25f970/user_cropped_screenshot_f628d6b7ae184e5db7575ce417453284_text_export.jpeg)


123\. Select **View endpoints**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/59a9dbb7-d048-4d11-bdce-8049ae97203f/user_cropped_screenshot_4d57510c65fd47c29b9cf73fc5e8a703_text_export.jpeg)


124\. Here you can see the MCP endpoints that you can use with applications, assistants or AI agents as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/7cf30fc7-5043-49a9-bdf9-54e06430548b/action-37f386a01f9547559a316f8f9f9b7bee_9e7d237bcf994fbda7f50233d5c11ebd_text_export.jpeg)


Alert: Important:

After you have finished testing your MCP endpoint with an AI assistant, agent framework, or other AI application, please take a few moments to delete the project you created during this exercise.

Removing unused projects helps keep the shared environment clean and available for future learners. It also prevents the accumulation of unnecessary MCP servers, policies, and published assets that are no longer needed.

Only delete the project and assets that you created during this exercise. Do **not** modify, delete, or republish any of the preconfigured **ZillaForge** projects, MCP servers, policies, catalogs, or other shared assets, as these are required by other learners and demo scenarios.

**Cleanup Tasks**

1. Return to the project you created for this exercise.
2. Delete the MCP assets you published.
3. Delete the project.
4. Verify that the project has been removed from the project list.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/020b8287-4f3f-4574-9064-7d17e2137553/screenshot_c842dd435c4e428bb082592f72597175_text_export.jpeg)


125\. **Actions:**

From the left navigation pane, click **Manage**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c7e6d65a-374b-432c-b031-aa4486c9923e/user_cropped_screenshot_a5902a4158c94ed383895d63767b73f6_text_export.jpeg)


126\. Click **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/8337b7b8-fdd9-45a8-897b-b7c5dae5b9bc/user_cropped_screenshot_9ad83c1749254438bda93bf6dc563040_text_export.jpeg)


#### Part 4: Register and Govern LLM Providers


127\. **Narration:**

So far, we've seen how ZillaForge exposes enterprise capabilities as governed MCP tools that can be consumed by AI assistants and agents. ZillaForge also needs a way to manage and control access to the foundation models and LLM providers that power its AI experiences.

To address this, ZillaForge uses IBM DataPower Interact Gateway to register and govern LLM providers. In this demo, we'll use **Amazon Bedrock** as an example, but the same approach can be applied to other providers such as watsonx.ai, Azure OpenAI, Google Gemini, and other supported model providers.

Rather than allowing applications and agents to connect directly to external model endpoints, requests can be routed through Interact Gateway, where consistent security, access controls, policies, and observability can be applied.

This gives ZillaForge a centralized approach to AI governance. The organization can manage which models are available, control access to approved providers, monitor usage, and apply the same governance principles already used for APIs and enterprise services to its LLM interactions.

In this section, we'll look at how LLM providers can be registered and managed through Interact Gateway and how this helps organizations maintain control as AI adoption continues to grow.


128\. **Narration:**

Before registering an LLM provider, ZillaForge performs a one-time setup activity to securely manage credentials and access tokens.

Organizations can securely store and manage secrets using AWS Secrets Manager, Azure Key Vault, or HashiCorp Vault. Rather than embedding API keys directly in applications, gateways, or agent configurations, sensitive credentials are stored and managed centrally.

This approach improves security, simplifies credential management, and allows ZillaForge to securely authenticate with external LLM providers.


129\. Actions:

On the top right corner, click **Instance Settings**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/cdf08e5c-de48-4eed-b9bb-173e0d3037c4/user_cropped_screenshot_6d99ee6782754a24bfbc6f1b38ce003f_text_export.jpeg)


130\. On the Instance settings page, click the **Secrets** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b0be1fa-802d-4868-b832-58276669d5ae/user_cropped_screenshot_17bede4138b642a8a31f6b5ce7771c1d_text_export.jpeg)


131\. Here you can connect to AWS Secrets Manager, Azure Key Vault or HashiCorp Vault to manage secrets for your Interact Gateway.

Click **Back** once you are done.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/6b20fa92-0d5d-46da-a67c-90fb43610a2e/user_cropped_screenshot_d586f95cb6844a0e8194648acdcf02a7_text_export.jpeg)


132\. **Narration:**

Let's now look at how ZillaForge manages access to external foundation models.

For this example, ZillaForge has registered **AWS Bedrock** as an LLM provider, although the same process can be used for other providers such as watsonx.ai, Azure OpenAI, Google Gemini, Anthropic, or any supported model platform.

We'll open the Bedrock project and examine how the provider was configured. In addition to the provider registration itself, you'll see the policy sequence associated with the LLM endpoint. Just as we saw with MCP tools, ZillaForge can apply governance controls before requests are sent to the model provider.

This allows the organization to enforce security, authentication, usage policies, observability, and other controls consistently across LLM interactions. Rather than connecting directly to external model endpoints, applications and agents can access approved models through a governed entry point managed by IBM DataPower Interact Gateway.

The result is a centralized approach to LLM governance that gives ZillaForge visibility and control over how foundation models are used across the enterprise.


133\. In API Studio, click the **ZFBedrock** project.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bb8644da-2f70-4d97-b1a1-655c7fc4091a/user_cropped_screenshot_0b9a8df35266412e879362e2ad690f7c_text_export.jpeg)


#### Part 5: Discover and Consume AI Assets Through the Developer Portal


134\. **Narration:** 

So far, we've focused on how ZillaForge creates, governs, and publishes AI-ready capabilities. The next step is to look at the consumer experience.

Here we're moving into the **Developer Portal**, where published AI assets can be discovered and accessed by teams. This provides a central location for finding approved enterprise capabilities and understanding how they can be consumed.

Just as the Developer Portal has traditionally been used to discover APIs, ZillaForge can now use it to publish and share governed AI assets, making it easier for teams to find and consume trusted capabilities while maintaining enterprise governance and control.


135\. Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/11dcf64e-4343-4f1f-bf0f-80112b9921b3/user_cropped_screenshot_7754337693ef4fd4a223ce1be7a75a1d_text_export.jpeg)


136\. Click the **Catalog settings** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/47acdc6b-228a-448c-97a6-a277ef8ec332/user_cropped_screenshot_96b9f710afcb41249869330a170f74a0_text_export.jpeg)


137\. On the left menu list, click **Portal**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bc606c34-f154-407f-8965-1cc0835c321b/user_cropped_screenshot_c4c9c2b60d0449fc8cab48b5e71823db_text_export.jpeg)


138\. Click the **Portal endpoint URL**<https://prod773957.devportal.a-fra-c2.apiconnect.ipaas.ibmappdomain.cloud>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/9ba68e95-0772-4fdb-bc40-76bbd6e5b77a/user_cropped_screenshot_53eecf74dc4a46ac8baaf05d3a99fb73_text_export.jpeg)


#### Part 6: Monitor and Optimize AI Interactions with Analytics


139\. **Narration:**

Throughout this demo, we've seen how ZillaForge governs AI interactions, publishes AI-ready capabilities, and manages access to LLM providers. The final step is visibility.

As AI adoption grows, organizations need to understand how AI assistants, agents, MCP tools, and LLMs are being used across the enterprise. IBM DataPower Interact Gateway provides analytics and observability that help teams monitor usage, investigate individual transactions, identify performance issues, and understand adoption trends.

These insights help ZillaForge not only govern AI interactions, but also continuously optimize and improve them as usage scales across the business.


140\. Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b40bdd3-98a5-488a-8de0-84d73e99da17/user_cropped_screenshot_507380de945b45d1af2893120847db16_text_export.jpeg)


141\. We'll focus on the analytics for the Inventory MCP server. Scroll to the right to view the analytics options.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/274031ac-60ef-40e3-bd6f-e87737e26603/user_cropped_screenshot_51b4da1efd6342b1a2b48986faf1f649_text_export.jpeg)


142\. For the inventoryapis-server-ow85v server, click the **analytics** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/b846290f-9c06-4976-b4c4-4dc235e07e32/user_cropped_screenshot_4952b65ac13a4839a21d26a7472029d3_text_export.jpeg)


143\. **Narration:** 

This is the **Discover** view, which provides a real-time view of MCP and AI interaction activity.

Here you can see interaction volume over time and a list of individual transactions, including status, method, response time, and other operational details. This allows ZillaForge teams to quickly identify activity patterns and drill into specific interactions for further investigation.


144\. **Actions:**

Click a transaction to drill-down and view more details. Here we are

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/92134ee7-09db-4509-af3b-4b94794ef233/user_cropped_screenshot_890b4b67b9f046268741deed2ca22044_text_export.jpeg)


145\. Click "Latency analysis"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/3583deaf-bbad-47e8-ae8c-ecc09a4f3a67/user_cropped_screenshot_8e0f94b0f24e4c0da57e000a291526aa_text_export.jpeg)


146\. Click "FiltersTime range: Last 7 daysReset filtersAPI eventTransaction ID: 0000000000000000001eb3047ff7ba53Datetime: 8/14/2026, 8:20:22 AMAI insightsBa..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/d8d7daf9-4391-442c-9844-c8d61f7d5719/action-3e9f534384834722ba2ba19cef457930_ddc83ed2ab384f8685d180a2b8c26465_text_export.jpeg)


147\. Click "FiltersTime range: Last 7 daysReset filtersAPI eventTransaction ID: 0000000000000000001eb3047ff7ba53Datetime: 8/14/2026, 8:20:22 AMAI insightsBa..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/aed91671-7438-4ef3-aa53-ed90e0238de4/action-0e6469bcc97549ec88a69ba9e6dd2dc8_e96e7d0f814449789ba5c000ebcdff2d_text_export.jpeg)


148\. Click "Backend request and response"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5c9acc2f-a0a5-4a94-9308-9e6ba2b6b083/action-97c5e664ff6b4747a1488eb1c8e85d4a_0a936fd27c1548298189d14a90143ac7_text_export.jpeg)


149\. Click "Consumer request"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/f2fd9572-1e60-4bc7-9920-893c2921bd10/action-29d0c2cd2d644b4eb1283d23ed725182_a2d5681c304943ccacf0bb5ec32d5e65_text_export.jpeg)


150\. Click "Policy flow latencies"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/28ace2b7-b5b4-4f05-9758-ec8245cb2276/action-3cdaea003f614cd193b340896e2591b4_fe4847213ed54b209476da1f274a0f4a_text_export.jpeg)


151\. Click "AI insightsBackend request and responsePolicy flow latenciesEvent recordAPI policy flow latenciesThe diagram below shows the increasing latency ..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/e80b6dbc-d714-4bc5-bc2d-49146f59120f/user_cropped_screenshot_6a1be765f0524fe3a92bfb4b09de7edb_text_export.jpeg)


152\. Click "Event record"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/47595183-c63a-43e6-949f-3ab9f803613a/action-a81406c4f22c46f89c4f6871bc566360_e79fd5fbfc2a43ebb0096741fbe6c484_text_export.jpeg)


153\. Click "Datetime: 8/14/2026, 8:20:22 AM"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/b2067e67-d609-4d21-a279-53ed874dedfa/action-f4ebde646bc340449c63904627fbb64e_b0930ce813df41ee94fbb1a2986dcfa5_text_export.jpeg)


154\. Click "Analytics side navigation"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/63472ab1-17cc-4558-acd0-2daf168870ea/action-77530ee5377c4ee89dc160d05002fd74_d5a8c72ff927410881bdcde5d5c866cb_text_export.jpeg)


155\. Click "AI Platform report"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/475b94a1-ef0c-49ef-a6c9-4b580795ad9c/user_cropped_screenshot_bcac79fda45d4fa081f26a30caea4ab1_text_export.jpeg)


156\. Click "Insufficient data for forecastingAt least 14 days of non-zero historical data are required for accurate forecasting. Please adjust your time ran..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/2a505bc2-3cb3-46fa-86fb-912b324851bf/action-bdbb524d90494e81a33a4c68306180ec_a77e3dd9cbad44b3b5fa36f0e56d6806_text_export.jpeg)


157\. Click "Show detailed analysis"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/4a534673-8399-4a34-a912-3c68e9f58d86/action-6074c5144f1f48a0b1db3e88e0583925_24af8b79e8bb46aab99e454caab57eb4_text_export.jpeg)


158\. Click "RecommendationsMedium priorityMonitor provider concentration as product-bedrock-conn-75trd:1.0 handles majority of calls (82.35%).Low priorityRe..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5a682e7e-2f94-4a52-89fa-374e2bbecd1b/action-2f0b451e44ba4df6afdf82016061b4f0_928fdae0e93c46ffbbca2cbd1f00b670_text_export.jpeg)


159\. Click "FiltersTime range: Previous 7 daysReset filtersAI Platform reportReview long term trends in AI Platform call volume for AI Platform providers an..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/6de6d948-63c7-4b2e-89d2-4a279c9b9072/action-3ad02322cc824df2bb2b44c6be635213_2ff7a07707544cd980802691c01fad7f_text_export.jpeg)


160\. Click "Consumption report"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/fa22da95-3588-4cf9-90a4-335f9edd3c89/action-f2ea63c8b3764451a2192356f40ba905_13636ccd5a9b48a79d16352f05a29d1b_text_export.jpeg)


161\. Click "FiltersTime range: Previous 7 daysReset filtersConsumption reportReview long term trends for API calls at this scope processed by the gateways o..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/deabec29-d225-401e-ab33-7e5acdef0cc8/action-158d17c6efd444078eb065994c467f2e_98bb818fd46a4c80afefc6c9d70cd7d4_text_export.jpeg)


162\. Click "Analytics side navigation"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/668e6ffd-3835-4fa3-b9df-1b83dc8bc107/action-f0dcc062f7b24e04a770cfc81f084f55_c87032aff83143f9945387b67207271e_text_export.jpeg)


163\. Click "MCP"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/3328f750-830e-4f0b-8924-bee615cd9a69/user_cropped_screenshot_204eb8d1b38e4e44b5fc5d87c2d8f342_text_export.jpeg)


164\. Click "FiltersTime range: Last 7 daysReset filtersMCP usage See who is using your AI MCP (Artificial Intelligence Model Context Protocol) services the ..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/596e39fa-2300-48f5-98ea-e034d7ff60fc/action-c7ad140e05e24d91806f2eb14864a1d0_581e950bd21142d2ac9f57c777c94248_text_export.jpeg)


165\. Click "MCP usage See who is using your AI MCP (Artificial Intelligence Model Context Protocol) services the most, track tool and prompt counts and usag..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/698a3dfa-59a9-4a5e-a84e-50003a92fade/action-458fa04b8b334d0dbdd088b51af63576_53fc7415aa3b44b989963f95a58af6f4_text_export.jpeg)


166\. Click "MCP usage See who is using your AI MCP (Artificial Intelligence Model Context Protocol) services the most, track tool and prompt counts and usag..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/77392631-4c3a-4021-b134-888a8f52c296/action-cbfcb3c21fee4596bdb1de3656dc7404_92029f58b1b94be891c374e8daf9762b_text_export.jpeg)


167\. Click "AI LLM"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/02ed45af-c810-4db4-b136-9d0d0c878ad5/action-df7a0e4b13d046eb912bb923b5536e28_2da98cf5e4364eac978114b7a91fd2c4_text_export.jpeg)


168\. Click "AI LLM usage See who is using your artificial intelligence large language model (AI LLM) services the most, track token counts and LLM model usa..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/d79e9a10-dbe4-47ca-bd26-5237c1cb19aa/action-dcdbddf40e2b405f94b11791d3f6fa8a_1aa1199252af4e45a31e4d65694fd954_text_export.jpeg)


169\. Click "Detailed usage"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/04bb03ed-6603-4a20-8644-59f216892ccb/action-2f7aabbed5224ea8aea2307cdcdbfbb1_c7c1132199d94928a06bfb9a459f1696_text_export.jpeg)


170\. Click "OverviewDetailed usageTop AI LLM consumers by token counts over time 3b133ce0-2f96-...02004006008001,000Count12 Aug, 09 am12 pm03 pm06 pm09 pm13..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5e0e738c-bd09-4069-9865-a3339ae1c300/action-4f9160e903f24bfcb6ce858accafce5d_ab5cf183b2f04b7eb59aa0efc231c5b0_text_export.jpeg)


171\. Click "OverviewDetailed usageTop AI LLM consumers by token counts over time 3b133ce0-2f96-...02004006008001,000Count12 Aug, 09 am12 pm03 pm06 pm09 pm13..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/13eea699-bdef-4927-9107-cc81fcfe43ca/action-f8fa1140b8b9481882eeb7d28ac3b62a_754a006d94634eb0996f89ee9e0d545b_text_export.jpeg)


172\. Click "OverviewDetailed usageTop AI LLM consumers by token counts over time 3b133ce0-2f96-...02004006008001,000Count12 Aug, 09 am12 pm03 pm06 pm09 pm13..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/a8563aa8-9f8e-4cef-9b4c-90f130179f84/action-f2458a394dc74c7f9207622491c7585a_ff2c93aaa2f9438e806f9e20612fb75b_text_export.jpeg)


173\. Click "OverviewDetailed usageTop AI LLM consumers by token counts over time 3b133ce0-2f96-...02004006008001,000Count12 Aug, 09 am12 pm03 pm06 pm09 pm13..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/eb23b8ff-ad99-46b0-b1c5-1062b2bf2d0d/action-decddde8c36044699727df7454faf93e_6f4fe0033eba42db8ab16cc9c4f481ca_text_export.jpeg)


174\. Click "OverviewDetailed usageTop AI LLM consumers by token counts over time 3b133ce0-2f96-...02004006008001,000Count12 Aug, 09 am12 pm03 pm06 pm09 pm13..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5a72300f-8780-401e-960f-e8848f4f8e5c/action-fde414e0376d4aa9b6ed1e92081db780_34ebf3bb3ae14abcb13ebe17eee47ef8_text_export.jpeg)


175\. Click "Gateway"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/04027263-2a88-4e3c-a7d0-345a649931be/action-a479237b59264ff0a8b3375fdc03f4ef_229101b8a73a45f1bd64ce49083675a6_text_export.jpeg)


176\. Click here.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/42279635-4225-44b7-adf0-0a3d0795619c/action-4e155fe8bde6464ab354945d00459a69_b9911db29ff34bf68cd4286ee282a79d_text_export.jpeg)


177\. Click "Gateway operations Call volume and latency information for each gateway in each gateway service. This can be used to determine if load is being ..."

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/449ffcee-c1d2-43e9-947b-820733c46325/action-f49783411b8b4b0b93f677f817d742f4_858185df1e3c42c4b48da5fa41cf1d44_text_export.jpeg)


178\. Click "Analytics side navigation"

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/25539567-82a3-407f-afdb-e0db16a6fe20/action-14e68e11228447b395a2293a19a669a0_be841e3366614882a1c64a876c284551_text_export.jpeg)