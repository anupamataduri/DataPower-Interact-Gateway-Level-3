# Part 1: ZillaForge AI Assistant for Internal Operations Queries

In the first part of the demo, you will explore the ZillaForge Operations Portal and interact with an AI-powered assistant. The assistant is connected to enterprise capabilities through an **MCP endpoint** exposed by IBM DataPower Interact Gateway, allowing users to ask business questions in natural language and receive answers from governed enterprise data and services.

The goal is to demonstrate how AI can safely access enterprise capabilities through a **controlled, observable interaction layer**.

---

## Narration — The Operations Portal

> ZillaForge employees access a centralized Operations Portal to interact with enterprise information and capabilities. Rather than navigating multiple systems, users can simply ask questions through an AI-powered assistant integrated directly into the portal.

---

## Step 1 — Navigate to the Operations Portal

**Action:** Navigate to [http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/](http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a1bd530-d04c-4428-89d4-91fa2cf62a68/action-9b94ee5d40b2468eaf5b516006a56eac_82b91a0e5b2b470bbe699649c6e9e20c_text_export.jpeg)

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

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/560bc599-d52f-495e-9fc0-63671268bda8/user_cropped_screenshot_46c2f17d0e0a471eb5939fd1ebee24d0_text_export.jpeg)

---

## Query 1 — Product Discovery

**Action:** In the Input field, type:

> **"What products are offered for predictive maintenance and industrial monitoring?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/53a34139-fd50-48c5-842d-f50afe481de1/user_cropped_screenshot_56cb906cf5d8402eb27051ad79067ca6_text_export.jpeg)

Click the **Send** button.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/39500f3f-c311-4c44-ae4a-35075daa3d72/user_cropped_screenshot_b60e4be372644ec585dbf5836e7dc9a3_text_export.jpeg)

The assistant has found the available products. Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0adcc52b-9cea-44a8-bd18-46f76b49c09c/user_cropped_screenshot_a5c590f1d6224113b387f02a718be1a9_text_export.jpeg)

---

## Narration — Moving to Recommendations

> Let's take that a step further. Rather than simply finding information, we'll now ask the assistant to analyze what it knows about ZillaForge's products and make a recommendation based on a customer's business requirements.
>
> This allows the assistant to combine information from multiple ZillaForge capabilities, apply reasoning, and recommend the solution that best aligns with the customer's needs. Instead of just discovering available products, we're using enterprise knowledge to support a real business decision.

---

## Query 2 — Business Recommendation

**Action:** In the Input field, type:

> **"Which ZillaForge product would you recommend for a factory looking to reduce unplanned equipment downtime?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/3c09775d-c481-450e-aad5-b42d6f48b50e/user_cropped_screenshot_dbc184b84e79449d9885927b2fef7f1e_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/33364435-7b54-401a-b562-d62ad704102c/user_cropped_screenshot_3ea967371725429ca2187fadbb4d0ec5_text_export.jpeg)

Click **Show more** to see the entire response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/948adec9-784c-4179-bc70-5a7729d669f1/user_cropped_screenshot_3b49aca6f85e456f98ee7b35843ce1c3_text_export.jpeg)

Notice that the assistant hasn't simply picked a product. It's recommended a **complete solution** and explained why the products work together.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/206803c5-6667-42af-b53d-6ff5820e8ef6/user_cropped_screenshot_f89f68db7a3b48e5993ceb7d4b5e9208_text_export.jpeg)

---

## Narration — Connecting to Operational Data

> Let's now see if the assistant can connect recommendations to operational data across the business.
>
> Within ZillaForge, product information, customer demand, and fulfilment activity exist across multiple enterprise systems. The real value comes when the assistant can combine information from those different capabilities to provide meaningful business context and actionable insights.

---

## Query 3 — Fulfilment Status

**Action:** In the Input box, type:

> **"Which customer orders related to predictive maintenance solutions are currently awaiting fulfilment?"**

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/752948a8-2bb6-4d65-a0ce-c24f0371cf17/user_cropped_screenshot_55233e7ae6764b2ab8e89eef52f22644_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/2fcc5813-7f88-4863-b064-eec19a75701d/user_cropped_screenshot_1fddb9fc38ec4c5aa280a0c9d6a5025d_text_export.jpeg)

Click **Show more** to see the full response. The assistant has identified the customer orders that are currently awaiting fulfilment and related to predictive maintenance solutions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/248ad69c-22e8-44bf-9886-6b462f7b74dd/user_cropped_screenshot_3d40fa535d4a453b90c73b8f85ccc887_text_export.jpeg)

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

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/1a1ec765-da6d-4d43-aa28-0095057ee727/user_cropped_screenshot_41dafa790f404dafb07191e00b13b111_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/93ade370-b968-4dc2-b5a6-0ba9d182987f/user_cropped_screenshot_160b35cafdb244cab4851330aef92d58_text_export.jpeg)

The recommendation is supported by operational information. You can see several assets with elevated failure risk. The assistant is also **identifying a pattern across multiple sites** rather than highlighting an isolated device issue.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0cbd481a-02d7-4e7b-a353-189fdd79738d/user_cropped_screenshot_fdb55aed75d64716b21250740df83db4_text_export.jpeg)

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

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/dabc326d-07ea-483a-92fd-fef5f3f21a53/user_cropped_screenshot_9751c0f2160b45e0abdc05ef64ea0fd5_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/40a45308-5a99-4f0a-b594-243fd8ebd130/user_cropped_screenshot_e6b344fd20854972972538ba6b1481db_text_export.jpeg)

The assistant has recommended the ZillaForge solutions that best align with the customer's digital transformation objectives while also highlighting existing customer demand that should be considered during planning.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/faf5b7b4-0e18-49d4-acbe-00c6e7fa6324/action-2db327eb64144416ba441953340d13c4_2933d5edc1ed4d728fe2e1a71984e6d4_text_export.jpeg)

---

## Narration — Summary

> We've seen how the ZillaForge Operations Portal allows users to interact with enterprise capabilities through a simple AI-powered experience.
>
> The assistant isn't just retrieving information from a single system. It's combining knowledge from across ZillaForge's products, customer demand, fulfilment, and operational data to provide more informed recommendations and business insights.
>
> Let's look behind the scenes and see how ZillaForge exposed these enterprise capabilities as AI-ready tools and how IBM DataPower Interact Gateway governs and secures those interactions.

---

**Previous:** [← Overview and Architecture](architecture.md) | **Next:** [Part 2 - Explore Governed MCP Tools →](mcp-tools.md)
