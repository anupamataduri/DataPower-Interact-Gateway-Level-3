# ZillaForge AI Assistant for Internal Operations Queries

In the first part of the demo, you will explore the ZillaForge Operations Portal and interact with an AI-powered assistant. The assistant is connected to enterprise capabilities through an **MCP endpoint** exposed by IBM DataPower Interact Gateway, allowing users to ask business questions in natural language and receive answers from governed enterprise data and services.

The goal is to demonstrate how AI can safely access enterprise capabilities through a **controlled, observable interaction layer**.

---

## Narration — The Operations Portal

> ZillaForge employees access a centralized Operations Portal to interact with enterprise information and capabilities. Rather than navigating multiple systems, users can simply ask questions through an AI-powered assistant integrated directly into the portal.

---

## Step 1 — Navigate to the Operations Portal

**Action:** Navigate to [http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/](http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a1bd530-d04c-4428-89d4-91fa2cf62a68/action-9b94ee5d40b2468eaf5b516006a56eac_be211d99dbef44da913cf3a58c333979_text_export.jpeg)

---

## Narration — How the AI Assistant Works

> Now let's see how a business user interacts with enterprise capabilities through the AI assistant.
>
> Rather than searching through product documentation, CRM systems, knowledge bases, or multiple business applications, the user simply asks a question in natural language.
>
> What's important is that the AI assistant already has access to governed enterprise capabilities through the MCP endpoint exposed by IBM DataPower Interact Gateway. When the user submits the request, the assistant can discover and invoke the appropriate enterprise tools and services without requiring the user to know where the information resides or which systems need to be accessed.
>
> From the user's perspective, this is a simple conversational experience. Behind the scenes, however, the interaction is routed through a governed entry point where security, policies, credentials, and observability are applied consistently. This allows AI to safely access trusted enterprise capabilities while maintaining enterprise control and visibility.

---

## Step 2 — Open the AI Assistant

**Action:** Click the ZillaForge **AI assistant** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/379aecbf-b55d-4f2b-b4ba-b04db31f54e4/action-47a37337742d4670a9817f6c0e7a8d07_ae6a722f08a24681b1303922bdb257f6_text_export.jpeg)

---

## Query 1 — Product Discovery

**Action:** In the Input field, type:

> **"What products are offered for predictive maintenance and industrial monitoring?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/4a8722a5-8090-4dbd-8340-1d4d2db6a7c2/action-9b234e6d905d4de9a134ade5027d12e2_a6e2e043083042259f6c6e770b103fc8_text_export.jpeg)

Click the **Send** button.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/c1c3199f-58dc-4413-900c-90b3ba90bf20/action-456cf2dcfead4e0aa943618ad1738248_83d82bd952054d45b25685468d7ea723_text_export.jpeg)

The assistant has found the available products. Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/97165cff-f12b-4480-aeea-117828893427/action-2ab9c7b3dbb4475ebf87790a18beb8d9_644f10edec734b8b9a1eea72d23b7d0a_text_export.jpeg)

---

## Narration — Moving to Recommendations

> Let's take that a step further. Rather than simply finding information, we'll now ask the assistant to analyze what it knows about ZillaForge's products and make a recommendation based on a customer's business requirements.
>
> This allows the assistant to combine information from multiple ZillaForge capabilities, apply reasoning, and recommend the solution that best aligns with the customer's needs. Instead of just discovering available products, we're using enterprise knowledge to support a real business decision.

---

## Query 2 — Business Recommendation

**Action:** In the Input field, type:

> **"Which ZillaForge product would you recommend for a factory looking to reduce unplanned equipment downtime?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/473a113b-1bd5-4a8d-88d3-b3d7e8a1bb0a/action-43c22db194d24e7b9c2865fabdb2a69e_68226b7da7b345209c3cdd8e2a4b0c35_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/e3dc0adb-b778-4edd-8721-f0114bd35c8a/action-897481be711848bd995d413e2dbd1120_b09d4b8c0ecd42078ac1b44b3ee88428_text_export.jpeg)

Click **Show more** to see the entire response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/463871a7-bc46-4059-b166-2e258c0a14bf/action-b2de0b202d39408ab549c610242eb9cc_b817c28cd45041168bfcda511984044b_text_export.jpeg)

Notice that the assistant hasn't simply picked a product. It's recommended a **complete solution** and explained why the products work together.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/fc99f186-d320-446c-bcfd-91273b1abe68/action-dbda5401aee14446a2c906ad00f6340a_699f5e24bca749d4a70097158d3592cb_text_export.jpeg)

---

## Narration — Connecting to Operational Data

> Let's now see if the assistant can connect recommendations to operational data across the business.
>
> Within ZillaForge, product information, customer demand, and fulfilment activity exist across multiple enterprise systems. The real value comes when the assistant can combine information from those different capabilities to provide meaningful business context and actionable insights.

---

## Query 3 — Fulfilment Status

**Action:** In the Input box, type:

> **"Which customer orders related to predictive maintenance solutions are currently awaiting fulfilment?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/e19226b1-3b67-4f03-bd5e-0684c96a0b16/action-3a46243684b2481a9ee486afda23e63f_860feedc61d64864bda1e01698efd2d2_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/390d78d4-cbf6-4a89-a133-7d2d718737fa/action-15698ff5ddb54e6088de7b8bc6f1a5b8_b309013556dc4cb4a8b151dda74a94fb_text_export.jpeg)

Click **Show more** to see the full response. The assistant has identified the customer orders that are currently awaiting fulfilment and related to predictive maintenance solutions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/8fd185b8-1197-42da-9c1c-d7454885a800/user_cropped_screenshot_69a7a00fb68c4c0092c9863790b47ed1_text_export.jpeg)

---

## Narration — Asset Reliability

> So far, we've seen how the assistant can help answer questions about ZillaForge products and connect those recommendations to customer demand and fulfilment activity.
>
> Let's now move from business demand into operational performance. One of the key priorities for ZillaForge customers is improving asset reliability across manufacturing environments while reducing unplanned downtime and maintenance costs.
>
> To answer this question, the assistant needs to do more than look up product information. It must understand the customer's business objective, evaluate the available ZillaForge solutions, and recommend the option that best aligns with operational needs.

---

## Query 4 — Asset Reliability Recommendation

**Action:** In the Input box, type:

> **"A customer wants to improve asset reliability across multiple manufacturing sites. Which ZillaForge solution would you recommend and why?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/cb25d1f4-d6cf-4724-b3a6-7ad4e708cf88/action-8cc2ebc2e83c4b0eb5c62e2214704a6d_6d8b13f853a4415aac7cda40c31e3595_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a000052-d231-4007-a044-d3044c5463a2/action-d4bc59b8d1b148b785ef24e4abd973d0_c6802518622941adb298f84d560da2c0_text_export.jpeg)

The recommendation is supported by operational information. You can see several assets with elevated failure risk. The assistant is also **identifying a pattern across multiple sites** rather than highlighting an isolated device issue.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/2b11415b-5f7b-4d67-acdf-8b56b3e475be/action-8a750d631ec04bb4be294979381a5a94_48161908905041c89ee82e53262654fc_text_export.jpeg)

---

## Narration — Digital Transformation Scenario

> Let's finish with our most comprehensive scenario. A customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation and wants to understand which ZillaForge solutions best support that strategy.
>
> This question requires the assistant to bring together multiple sources of information. It needs to understand the available ZillaForge products, consider existing customer demand, and factor in planning and deployment considerations before making a recommendation.
>
> Rather than looking at a single system or data source, the assistant must combine information from across the business to provide a complete answer.

---

## Query 5 — Digital Transformation Strategy

**Action:** In the Input field, type:

> **"A manufacturing customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation. Which ZillaForge products best support this strategy, and what existing customer demand should the business be aware of before planning deployment?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/86238b1b-3926-4493-b524-cec8d24b09eb/action-f9e0479ecc544ef3a706cd5c694b8fb4_23675cd80b6b426b805a4ae3b2c32a09_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/24621245-8028-4dc0-9ec0-24cfe9b093e1/action-bedea4e375c0482c8246d949dd7e3013_f68b93780a4f44dba722eb2550e96fbd_text_export.jpeg)

The assistant has recommended the ZillaForge solutions that best align with the customer's digital transformation objectives while also highlighting existing customer demand that should be considered during planning.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/faf5b7b4-0e18-49d4-acbe-00c6e7fa6324/action-2db327eb64144416ba441953340d13c4_73018282050a4a2a8880c9e82eaa5093_text_export.jpeg)

---

## Narration — Summary

> We've seen how the ZillaForge Operations Portal allows users to interact with enterprise capabilities through a simple AI-powered experience.
>
> The assistant isn't just retrieving information from a single system. It's combining knowledge from across ZillaForge's products, customer demand, fulfilment, and operational data to provide more informed recommendations and business insights.
>
> Let's look behind the scenes and see how ZillaForge exposed these enterprise capabilities as AI-ready tools and how IBM DataPower Interact Gateway governs and secures those interactions.

---

**Previous:** [← Overview and Architecture](architecture.md)
