# Part 1: ZillaForge AI Assistant for Internal Operations Queries

## Narration — The Operations Portal

> ZillaForge employees access a centralized Operations Portal to interact with enterprise information and capabilities. Rather than navigating multiple systems, users can simply ask questions through an AI-powered assistant integrated directly into the portal.
>
> The assistant is connected to enterprise capabilities through an MCP endpoint exposed by the Interact Gateway, allowing users to ask business questions in natural language and receive answers from governed enterprise data and services.
>
> The goal is to demonstrate how AI can safely access enterprise capabilities through a controlled, observable interaction layer.

---

## Step 1 — Navigate to the Operations Portal

**Action:** Navigate to <a href="http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/" target="_blank">http://zillaforge-env.eba-xavdcupg.us-east-1.elasticbeanstalk.com/</a>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-11/1a1bd530-d04c-4428-89d4-91fa2cf62a68/action-9b94ee5d40b2468eaf5b516006a56eac_064d3275912a4a1d83342269bad7f097_text_export.jpeg)

---

## Narration — How the AI Assistant Works

> Now let's see how a business user interacts with enterprise capabilities through the AI assistant.
>
> From the user's perspective, this is a simple conversational experience. Behind the scenes, however, the interaction is routed through a governed entry point where security, policies, credentials, and observability are applied consistently.

---

## Step 2 — Open the AI Assistant

**Action:** Click the ZillaForge **AI assistant** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/560bc599-d52f-495e-9fc0-63671268bda8/user_cropped_screenshot_b7ecb4f0c2604925a3646232b2984f1b_text_export.jpeg)

---

## Query 1 — Product Discovery

**Action:** In the Input field, type:

```text
What products are offered for predictive maintenance and industrial monitoring?
```

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/824e5cf5-0417-445f-a709-27c7e5d539af/user_cropped_screenshot_bec51a3e3add4f349994225eb474c54e_text_export.jpeg)

Click the **Send** button.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/39500f3f-c311-4c44-ae4a-35075daa3d72/user_cropped_screenshot_3450943182ff4fb1b721a615cb0a5b55_text_export.jpeg)

The assistant has found the available products. Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0adcc52b-9cea-44a8-bd18-46f76b49c09c/user_cropped_screenshot_1ed742c2a1b14540956633d34e400807_text_export.jpeg)

---

## Narration — Moving to Recommendations

> Let's take that a step further. Rather than simply finding information, we'll now ask the assistant to analyze what it knows about ZillaForge's products and make a recommendation based on a customer's business requirements.
>
> This allows the assistant to combine information from multiple ZillaForge capabilities, apply reasoning, and recommend the solution that best aligns with the customer's needs. Instead of just discovering available products, we're using enterprise knowledge to support a real business decision.

---

## Query 2 — Business Recommendation

**Action:** In the Input field, type:

```text
Which ZillaForge product would you recommend for a factory looking to reduce unplanned equipment downtime?
```

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/89485a69-19cb-4eeb-be0f-df6c8c1d0c4b/user_cropped_screenshot_7b09c9133f0a4b078ef38e68bbb0cb8b_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/33364435-7b54-401a-b562-d62ad704102c/user_cropped_screenshot_33a0cb72497e4917bb39cd99d2b82361_text_export.jpeg)

Click **Show more** to see the entire response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/948adec9-784c-4179-bc70-5a7729d669f1/user_cropped_screenshot_bbd7823e2df149fb8b2c1b42da351d70_text_export.jpeg)

Notice that the assistant hasn't simply picked a product. It's recommended a **complete solution** and explained why the products work together.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/206803c5-6667-42af-b53d-6ff5820e8ef6/user_cropped_screenshot_7814cbda75844596b9376b1831d425fc_text_export.jpeg)

---

## Narration — Connecting to Operational Data

> Let's now see if the assistant can connect recommendations to operational data across the business.
>
> Within ZillaForge, product information, customer demand, and fulfilment activity exist across multiple enterprise systems. The real value comes when the assistant can combine information from those different capabilities to provide meaningful business context and actionable insights.

---

## Query 3 — Fulfilment Status

**Action:** In the Input box, type:

```text
Which customer orders related to predictive maintenance solutions are currently awaiting fulfilment?
```

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/96f80c47-9360-4453-a456-2358008dbc09/user_cropped_screenshot_14ad4ad0f829404eb9cfd71fd676f359_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/2fcc5813-7f88-4863-b064-eec19a75701d/user_cropped_screenshot_edc73df5a2fb4c7fb8f896a0581ac53b_text_export.jpeg)

Click **Show more** to see the full response. The assistant has identified the customer orders that are currently awaiting fulfilment and related to predictive maintenance solutions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/248ad69c-22e8-44bf-9886-6b462f7b74dd/user_cropped_screenshot_570ebaba9c7b48b9a625f5840599ecb9_text_export.jpeg)

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

```text
A customer wants to improve asset reliability across multiple manufacturing sites. Which ZillaForge solution would you recommend and why?
```

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/a53441fd-e7e0-4fe8-94ad-6fceda4a3ceb/user_cropped_screenshot_7f81a6a2405b45eb9093306ca06a91b4_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/93ade370-b968-4dc2-b5a6-0ba9d182987f/user_cropped_screenshot_3e4aefacbd924a379fe970ef719f83cb_text_export.jpeg)

The recommendation is supported by operational information. You can see several assets with elevated failure risk. The assistant is also **identifying a pattern across multiple sites** rather than highlighting an isolated device issue.

Click **Show more** to see the full response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0cbd481a-02d7-4e7b-a353-189fdd79738d/user_cropped_screenshot_5c833b467fc546529dafa8b5c8f4a412_text_export.jpeg)

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

```text
A manufacturing customer is planning a digital transformation initiative focused on IoT, predictive maintenance, and automation. Which ZillaForge products best support this strategy, and what existing customer demand should the business be aware of before planning deployment?
```

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/8abd49d9-883b-417c-aa0d-73c2e5a7c63d/user_cropped_screenshot_fca0ae050ab34b269dbd0adbe4a11642_text_export.jpeg)

Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/40a45308-5a99-4f0a-b594-243fd8ebd130/user_cropped_screenshot_a24b9073fa8d4aecbb1fce4722a3215b_text_export.jpeg)

The assistant has recommended the ZillaForge solutions that best align with the customer's digital transformation objectives while also highlighting existing customer demand that should be considered during planning.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/53f13ebd-25f0-454b-b62e-855d64343560/user_cropped_screenshot_cbcbcae31bf74f008b893796ee86cf7d_text_export.jpeg)

---

## Wrap-up

> We've seen how the ZillaForge Operations Portal allows users to interact with enterprise capabilities through a simple AI-powered experience.
>
> The assistant isn't just retrieving information from a single system. It's combining knowledge from across ZillaForge's products, customer demand, fulfilment, and operational data to provide more informed recommendations and business insights.
>
> Let's look behind the scenes and see how ZillaForge exposed these enterprise capabilities as AI-ready tools and how IBM DataPower Interact Gateway governs and secures those interactions.

---

**Previous:** [← Overview and Architecture](architecture.md) | **Next:** [Part 2 - Explore Governed MCP Tools →](mcp-tools.md)
