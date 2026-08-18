# Part 2: Explore Governed MCP Tools

So far, we've focused on the experience of the business user. We saw how employees can interact with ZillaForge's enterprise capabilities through a simple AI assistant and receive recommendations, insights, and answers drawn from systems across the organization.

Now, we'll look behind the scenes at how ZillaForge used IBM DataPower Interact Gateway to transform existing enterprise services into AI-ready capabilities.

---

## Narration — Reusing Existing Enterprise APIs

> Here we're in **API Connect**, looking at the existing enterprise APIs that provide business data.
>
> One of the key concepts behind IBM DataPower Interact Gateway is that ZillaForge isn't creating new back-end services specifically for AI. Instead, the company is reusing the APIs it has already invested in and exposing them in a way that AI assistants and agents can safely consume.
>
> This approach allows ZillaForge to leverage existing enterprise assets while maintaining the governance, security, and operational controls already established across the organization.
>
> To do that, ZillaForge created a project dedicated to its MCP tools. Let's open that project and see how existing enterprise capabilities are transformed into AI-ready tools that can be consumed through Interact Gateway.

---

## Step 1 — Open the ZFmcp Project

**Action:** Click the project **ZFmcp**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/9c3b83a4-9500-4eaf-be08-60d0e5197550/user_cropped_screenshot_9508a87196894324a3108fe622e1eb83_text_export.jpeg)

!!! tip "Important"
    Once you open the project, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

---

## Step 2 — Switch to AI View

**Action:** Click **API View**, then select **AI View**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c4c921db-780c-4b42-803a-06a68e67b617/user_cropped_screenshot_042ad074ba214e9f925e8930ef4c9f27_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/47573a9a-6a0d-4908-ab43-b18c4eb4780e/user_cropped_screenshot_e045d5739e0c46f285add20a110930ee_text_export.jpeg)

---

## Narration — MCP Servers Overview

> What we're looking at here are the MCP servers that ZillaForge created from its existing enterprise APIs and services.
>
> The underlying APIs haven't changed. ZillaForge is still using the same product, inventory, order, and operational services that already exist within the business. The difference is that those capabilities have now been exposed as MCP tools that AI assistants and agents can discover, understand, and invoke.
>
> In the first part of the demo, we saw the AI assistant answering questions about ZillaForge products, customer demand, fulfilment activity, and operational performance. Those answers were made possible because the underlying enterprise capabilities were exposed as MCP tools that the assistant could access through Interact Gateway.
>
> Let's open the MCP servers and see how ZillaForge transformed existing enterprise APIs into an AI-ready capability.

---

## Step 3 — Explore the Factory APIs MCP Server

**Action:** Under MCP servers, click **factoryapis-server-n9ipb**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5dc0052a-88cb-428a-97b1-74bf5b147fed/user_cropped_screenshot_86580bb365e54ff3bca7e4b8012c8b19_text_export.jpeg)

---

## Narration — MCP Server Generation

> Here we're looking at one of the MCP servers created for ZillaForge's factory operations capabilities.
>
> When creating an MCP server, you can start from an existing API, import an external API definition, or use APIs that are already registered and governed through Federated API Management. In this example, ZillaForge started with a Factory API defined in a YAML specification.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/a2b2e250-2702-407c-a7e2-429600ca7ae7/user_cropped_screenshot_f2eac3561f1a4609a37183173df84ff4_text_export.jpeg)

---

## Step 4 — Review Inventory and Order MCP Servers

> ZillaForge has also created MCP servers for its **Inventory API** and **Order API**, following the same approach.

**Action:** Click **inventoryapis-server-ow85v** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/015c50f5-1e9c-42f6-b179-1a7fd47ff7d1/user_cropped_screenshot_3432d3fdac5a42caaf024d04ad3c42fe_text_export.jpeg)

**Action:** Click **orderapis-server-lzsrh** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/7a2212ca-9305-446b-b7c5-9be6fa71db82/user_cropped_screenshot_af71585586504fb391df042801625a7d_text_export.jpeg)

---

## Narration — Applying Governance with Policy Flows

> The next step for ZillaForge is to apply governance.
>
> Here, we're looking at the **policy flow** associated with the MCP tools. ZillaForge uses policy sequences to govern how AI assistants and agents interact with enterprise services before requests ever reach the backend systems.
>
> These policies allow ZillaForge to apply security, transformation, rate limiting, authorization, and other controls consistently across AI interactions. This is where IBM DataPower Interact Gateway moves beyond simply exposing APIs as AI tools.

---

## Step 5 — Explore the Policy Sequence

**Action:** Under Policy sequences, click the policy **zfmcp-freeflowpolicysequence-lzsrh1.0**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5b008085-c426-48f5-8af4-e7078d7fd3d8/user_cropped_screenshot_5d06ebec83454fddacc7f4b3fc10dde7_text_export.jpeg)

**Action:** In the Assembly flow, click the **Invoke** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ca5171a2-e4bf-4aa3-bce9-c4c8119f9aa8/user_cropped_screenshot_fe00f4789f9144db87ddefe24c3dde08_text_export.jpeg)

---

## Narration — Reusing Existing API Management

> The MCP tools used by the ZillaForge Operations Portal are connected to an existing API that is already hosted and managed in **webMethods API Gateway**.
>
> This reinforces an important principle behind ZillaForge's AI strategy: there is no need to build new back-end services specifically for AI. Instead, existing enterprise capabilities that are already exposed, managed, and governed through API management platforms can be reused and made available to AI assistants and agents through IBM DataPower Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/418732d1-7abb-4486-8e36-838ca6dcdd4a/user_cropped_screenshot_4f465d14b06c4658ac95b5578da38699_text_export.jpeg)

---

## Step 6 — Review Policy Nodes

**Action:** Click the **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/030cc10e-e154-4703-9928-5b16a2c9eaeb/user_cropped_screenshot_5e629cc6c083431abb725de189010af4_text_export.jpeg)

This policy sets the required request headers to ensure the MCP tool sends properly formatted requests to the backend API.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ee1a951f-594e-487c-beb7-93ed69a86425/user_cropped_screenshot_5963553d35924a4ea036001afbecb548_text_export.jpeg)

**Action:** Click the next **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/11a1b855-8b8f-42d2-964c-115548a0445d/user_cropped_screenshot_112252034e9d4302bbad979ad4b26b4a_text_export.jpeg)

Here we're supplying the required API key. The MCP tool doesn't bypass the API's security requirements — it consumes the API using the same governance and authentication mechanisms already in place.

You can review the other policies as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/bcbefcbf-fb8b-43b4-90ce-993439f6ff51/user_cropped_screenshot_021f0ddc04d54cb4aa6580c977947ee6_text_export.jpeg)

---

## Narration — Summary

> At this point, ZillaForge has transformed existing enterprise APIs into AI-ready capabilities by generating MCP tools, enriching them for AI consumption, and applying the appropriate governance policies.
>
> The final step is to publish those capabilities through the Interact Gateway. Publishing creates the governed MCP endpoint that serves as the entry point for AI interactions. This endpoint is what the ZillaForge Operations Portal used earlier when the AI assistant accessed product, inventory, order, and operational capabilities.

---

**Previous:** [← Part 1: ZillaForge AI Assistant](ai-assistant.md) | **Next:** [Part 3 - Create and Publish MCP Tools →](create-mcp-tools.md)
