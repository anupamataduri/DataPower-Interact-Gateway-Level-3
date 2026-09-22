# Part 2: Explore Governed MCP Tools

## Narration — Reusing Existing Enterprise APIs

> So far, we've focused on the experience of the business user. We saw how employees can interact with ZillaForge's enterprise capabilities through a simple AI assistant and receive recommendations, insights, and answers drawn from systems across the organization.
>
> Now, we'll look at how ZillaForge used IBM DataPower Interact Gateway to transform existing enterprise services into AI-ready capabilities.

---

## Narration — We're Now in API Connect

> We're now in API Connect. Here we're looking at the existing enterprise APIs that provide the business capabilities used across the ZillaForge environment.
>
> One of the key concepts behind Interact Gateway is that ZillaForge isn't creating new back-end services specifically for AI. Instead, the company is reusing the APIs it has already invested in and exposing them in a way that AI assistants and agents can safely consume.
>
> This approach allows ZillaForge to leverage existing enterprise assets while maintaining the governance, security, and operational controls already established across the organization.
>
> To do that, ZillaForge created a project dedicated to its MCP tools. Let's open that project and see how existing enterprise capabilities are transformed into AI-ready tools that can be consumed through Interact Gateway.

---

## Step 1 — Open the ZFmcp Project

**Action:** In API Connect, click the project **ZFmcp**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/9c3b83a4-9500-4eaf-be08-60d0e5197550/user_cropped_screenshot_537c1e65d62e4d27afeabb30b6e1b2f6_text_export.jpeg)

!!! tip "Important"
    Once you open the project, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

---

## Step 2 — Switch to AI View

**Action:** Click **API View**, then select **AI View**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c4c921db-780c-4b42-803a-06a68e67b617/user_cropped_screenshot_0ee5b60919d04d4aac175f84c3ae037d_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/47573a9a-6a0d-4908-ab43-b18c4eb4780e/user_cropped_screenshot_58f2148f68cd4cef8ac20085b36be75b_text_export.jpeg)

---

## Narration — MCP Servers Overview

> Here are the MCP servers that ZillaForge created from its existing enterprise APIs and services.
>
> The underlying APIs haven't changed. ZillaForge is still using the same product, inventory, and order services that already exist within the business. The difference is that those capabilities have now been exposed as MCP tools that AI assistants and agents can discover, understand, and invoke.
>
> In the first part of the demo, we saw the AI assistant answering questions about ZillaForge products, customer demand, fulfilment activity, and operational performance. Those answers were made possible because the underlying enterprise capabilities were exposed as MCP tools that the assistant could access through the Interact Gateway.
>
> Let's open the MCP servers and see how ZillaForge transformed existing enterprise APIs into an AI-ready capability.

---

## Step 3 — Explore the Factory APIs MCP Server

**Action:** In the Explorer pane, under MCP servers, click **factoryapis-server-n9ipb**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5dc0052a-88cb-428a-97b1-74bf5b147fed/user_cropped_screenshot_7dd987e1bee949e1ba6ec09d9ea16283_text_export.jpeg)

---

## Narration — MCP Server Tools

> Here we can see the MCP server that was generated from the Factory API. The operations defined in the original API have been converted into AI-ready MCP tools, such as list_device and list_service_request.
>
> Each MCP tool represents a business capability that AI assistants and agents can discover and invoke.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/4e36a056-1169-4b85-9adb-48752628a1db/user_cropped_screenshot_10ca7935cc83409ba412dee38d61293b_text_export.jpeg)

---

## Step 4 — Review Inventory and Order MCP Servers

> ZillaForge has also created MCP servers for its **Inventory API** and **Order API**, following the same approach.

**Action:** Click **inventoryapis-server-ow85v** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/015c50f5-1e9c-42f6-b179-1a7fd47ff7d1/user_cropped_screenshot_0ced61aa00f54e67a6f19e6225fa30cd_text_export.jpeg)

**Action:** Click **orderapis-server-lzsrh** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/7a2212ca-9305-446b-b7c5-9be6fa71db82/user_cropped_screenshot_e02d2df44e6e42e98c57a78a06c34f7f_text_export.jpeg)

---

## Narration — Applying Governance with Policy Flows

> The next step for ZillaForge is to apply governance.
>
> Here, we're looking at the policy flow associated with the MCP tools. ZillaForge uses policy sequences to govern how AI assistants and agents interact with enterprise services before requests ever reach the backend systems.
>
> These policies allow ZillaForge to apply security, transformation, rate limiting, authorization, and other controls consistently across AI interactions. This is where IBM DataPower Interact Gateway moves beyond simply exposing APIs as AI tools.

---

## Step 5 — Explore the Policy Sequence

**Action:** Under Policy sequences, click the policy **zfmcp-freeflowpolicysequence-lzsrh1.0**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5b008085-c426-48f5-8af4-e7078d7fd3d8/user_cropped_screenshot_9c5af65b04624258b59bfd139217f271_text_export.jpeg)

**Action:** In the Assembly flow, click the **Invoke** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ca5171a2-e4bf-4aa3-bce9-c4c8119f9aa8/user_cropped_screenshot_3f29af54a2dc479dbe37c6477394ab9e_text_export.jpeg)

---

## Narration — Reusing Existing API Management

> The MCP tools used by the ZillaForge Operations Portal are connected to an existing API that is already hosted and managed in webMethods API Gateway.
>
> This reinforces an important principle behind ZillaForge's AI strategy: there is no need to build new back-end services specifically for AI. Instead, existing enterprise capabilities that are already exposed, managed, and governed through API management platforms can be reused and made available to AI assistants and agents through the Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/418732d1-7abb-4486-8e36-838ca6dcdd4a/user_cropped_screenshot_655d906897ee44fc85fc7213cf9134d0_text_export.jpeg)

---

## Step 6 — Review Policy Nodes

**Action:** Click the **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/030cc10e-e154-4703-9928-5b16a2c9eaeb/user_cropped_screenshot_dfed7d6d593a47dfa6ad13643f8c9c93_text_export.jpeg)

This policy sets the required request headers to ensure the MCP tool sends properly formatted requests to the backend API.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ee1a951f-594e-487c-beb7-93ed69a86425/user_cropped_screenshot_a2f13a3b2350491ea3f5c855ef48eed5_text_export.jpeg)

**Action:** Click the next **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/11a1b855-8b8f-42d2-964c-115548a0445d/user_cropped_screenshot_efccda5ba5974b69b3214e1bbfee36fc_text_export.jpeg)

> Here we're supplying the required API key. The purpose here is simply to validate the API and confirm the capability is working correctly.
>
> This is a good example of how existing security controls continue to apply. The MCP tool doesn't bypass the API's security requirements; it consumes the API using the same governance and authentication mechanisms already in place.

Review the policy details and click the **Close** icon to close the pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/b2a47711-ef7e-46ec-b294-933909c62895/user_cropped_screenshot_82d32a5f3abf4750ba9b993a512d24e4_text_export.jpeg)

You can review the other two policies and see how they are set up.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/eddd7f01-9ad9-4cb3-84c3-067090db7fcf/user_cropped_screenshot_731dfac2f0ef4934a48f2b3578bd0aa1_text_export.jpeg)

---

## Narration — Locating the Published MCP Endpoint

> Once the MCP tools have been published, they are exposed through a governed MCP endpoint that can be consumed by AI assistants, agents, and applications.
>
> We'll now navigate to the catalog to locate the published MCP endpoint.

---

## Step 7 — Navigate to the Catalog

**Action:** On the left navigation pane, click the **Manage** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/1efcefd4-e199-4bb1-a300-78377b6ea9e7/user_cropped_screenshot_05c13d96977a4cb592e9313a17b1f2c9_text_export.jpeg)

**Action:** Click **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/1a16ffbe-afdc-4ffd-8b62-8e754812bb8d/user_cropped_screenshot_dfeb2bcd49064fa8b7f2e14b2bc804e0_text_export.jpeg)

You can see all the published assets in the Interact Gateway MCP catalog. If the list is long, you can choose to filter to view only MCP Servers.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/b6cb9f9d-2917-48a5-b83f-ed53fcd4c5f1/user_cropped_screenshot_1b2b74b8c0964e1d8d69ed398ab731bd_text_export.jpeg)

---

## Step 8 — View the MCP Endpoint

**Action:** For the inventoryapis-server-ow85v, click the **three dots** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/0e920588-84ab-4e84-b8b4-8f9a85340585/user_cropped_screenshot_12303d67acf1422bbaed31495aa398a0_text_export.jpeg)

**Action:** Click **View endpoints**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/f33f9e4a-64a6-4d86-911a-b96a7fac87cb/user_cropped_screenshot_b5f7b4b6433a4b38bb14a16d416194d3_text_export.jpeg)

**Action:** Click **Copy** to copy the endpoint. You can use this MCP endpoint with applications, assistants, or AI agents as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-27/ce92a78f-e4b3-4da7-baec-055d09bd9878/user_cropped_screenshot_45e2f444ead04f1abc7e9ec6361eadf9_text_export.jpeg)

---

## Wrap-up

> Rather than building new services for AI, ZillaForge reused existing enterprise APIs, applied governance policies, and published the resulting MCP tools through the Interact Gateway.
>
> By following this approach, organizations can safely make enterprise capabilities available to AI assistants and agents while maintaining the security, control, and observability required for enterprise-scale AI adoption.

---

**Previous:** [← Part 1: ZillaForge AI Assistant](ai-assistant.md) | **Next:** [Part 3 - Register and Govern LLM Providers →](llm-governance.md)
