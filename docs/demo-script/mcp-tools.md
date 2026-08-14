# Part 2: Generating MCP Tools

So far, we've focused on the experience of the business user. We saw how employees can interact with ZillaForge's enterprise capabilities through a simple AI assistant and receive recommendations, insights, and answers drawn from systems across the organization.

In the second part of the demo, we'll look behind the scenes at how ZillaForge used IBM DataPower Interact Gateway to transform existing enterprise services into AI-ready capabilities. We'll see how MCP endpoints are created, how tools are published and governed, and how organizations can provide AI assistants with controlled access to enterprise systems without rebuilding existing applications or integrations.

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

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/9c3b83a4-9500-4eaf-be08-60d0e5197550/user_cropped_screenshot_02b2cedd40094e9f927ec3b8612891fe_text_export.jpeg)

!!! tip "Important"
    Once you open the project, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

---

## Step 2 — Switch to AI View

**Action:** Click **API View**, then select **AI View**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c4c921db-780c-4b42-803a-06a68e67b617/user_cropped_screenshot_fac5bd29692f46da97636d35ff7a7bb3_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/47573a9a-6a0d-4908-ab43-b18c4eb4780e/user_cropped_screenshot_d6ab9d9a46294dbfbecee66bacb8498a_text_export.jpeg)

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

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5dc0052a-88cb-428a-97b1-74bf5b147fed/user_cropped_screenshot_27287e708a5a461092d95e9ead234c12_text_export.jpeg)

---

## Narration — MCP Server Generation & Enhancement

> Here we're looking at one of the MCP servers created for ZillaForge's factory operations capabilities.
>
> When creating an MCP server, you can start from an existing API, import an external API definition, or use APIs that are already registered and governed through Federated API Management. In this example, ZillaForge started with a Factory API defined in a YAML specification.
>
> As part of the MCP generation process, API Connect analyzes the API definition and automatically discovers the available operations. Those operations are then converted into MCP tools that AI assistants and agents can understand and invoke. Teams can choose exactly which operations should be published as MCP tools. This ensures that only the business capabilities intended for AI consumption are exposed, while maintaining control over sensitive or unnecessary functionality.
>
> Once the tools have been generated, ZillaForge can further improve how those capabilities are presented to AI by using the **MCP Server Enhancer**.
>
> Tool names, descriptions, and parameter definitions can be refined to provide clearer instructions to AI assistants and agents. These enhancements help the AI better understand the purpose of each tool, when it should be used, and how it should be invoked.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/a2b2e250-2702-407c-a7e2-429600ca7ae7/user_cropped_screenshot_54f38746ebb74b72976eee7dd126e7e7_text_export.jpeg)

---

## Step 4 — Review Inventory and Order MCP Servers

> ZillaForge has also created MCP servers for its **Inventory API** and **Order API**, following the same approach.

**Action:** Click **inventoryapis-server-ow85v** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/015c50f5-1e9c-42f6-b179-1a7fd47ff7d1/user_cropped_screenshot_f254b91312304ae3a9f74611ef29239a_text_export.jpeg)

**Action:** Click **orderapis-server-lzsrh** and review the MCP tools.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/7a2212ca-9305-446b-b7c5-9be6fa71db82/user_cropped_screenshot_52a97299e5de46ad976c6ae956cf0a7d_text_export.jpeg)

---

## Narration — Applying Governance with Policy Flows

> The next step for ZillaForge is to apply governance.
>
> Here, we're looking at the **policy flow** associated with the MCP tools. ZillaForge uses policy sequences to govern how AI assistants and agents interact with enterprise services before requests ever reach the backend systems.
>
> These policies allow ZillaForge to apply security, transformation, rate limiting, authorization, and other controls consistently across AI interactions. Because the policies are applied at the gateway layer, the organization can enforce governance standards without changing the underlying APIs or business services.
>
> This is where IBM DataPower Interact Gateway moves beyond simply exposing APIs as AI tools. It becomes the governance layer that helps ZillaForge manage access, enforce policies, and maintain visibility across AI-driven interactions. The important point is that AI interactions can be governed using the same policy framework organizations already use for APIs, making it easier to extend existing governance practices into the AI era.

---

## Step 5 — Explore the Policy Sequence

**Action:** Under Policy sequences, click the policy **zfmcp-freeflowpolicysequence-lzsrh1.0**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5b008085-c426-48f5-8af4-e7078d7fd3d8/user_cropped_screenshot_3b747182abd748ccba4aae1fb6306156_text_export.jpeg)

**Action:** In the Assembly flow, click the **Invoke** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ca5171a2-e4bf-4aa3-bce9-c4c8119f9aa8/user_cropped_screenshot_d3ccad4a45ab429581a97fbdbfaf5103_text_export.jpeg)

---

## Narration — Reusing Existing API Management

> The MCP tools used by the ZillaForge Operations Portal are connected to an existing API that is already hosted and managed in **webMethods API Gateway**.
>
> This reinforces an important principle behind ZillaForge's AI strategy: there is no need to build new back-end services specifically for AI. Instead, existing enterprise capabilities that are already exposed, managed, and governed through API management platforms can be reused and made available to AI assistants and agents through IBM DataPower Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/418732d1-7abb-4486-8e36-838ca6dcdd4a/user_cropped_screenshot_516a69b7b8144c6eafdb9bdbd6ee85dc_text_export.jpeg)

---

## Step 6 — Review Policy Nodes

**Action:** Click the **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/030cc10e-e154-4703-9928-5b16a2c9eaeb/user_cropped_screenshot_c00f2957ec5f40048c7eb2445c120b2f_text_export.jpeg)

This policy sets the required request headers to ensure the MCP tool sends properly formatted requests to the backend API.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/ee1a951f-594e-487c-beb7-93ed69a86425/user_cropped_screenshot_e635166d671a4214897347a1562cb015_text_export.jpeg)

**Action:** Click the next **Set** node.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/11a1b855-8b8f-42d2-964c-115548a0445d/user_cropped_screenshot_16f8445960834af594e2c52cdbfe3af2_text_export.jpeg)

Here we're supplying the required API key. The purpose here is simply to validate the API and confirm the capability is working correctly.

This is a good example of how existing security controls continue to apply. The MCP tool doesn't bypass the API's security requirements; it consumes the API using the same governance and authentication mechanisms already in place.

You can review the other policies as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/bcbefcbf-fb8b-43b4-90ce-993439f6ff51/user_cropped_screenshot_dfb3520d21304f3fa16d1be0948b4a5a_text_export.jpeg)

---

## Narration — Publishing MCP Tools

> Once the tools have been configured, enhanced, and governed, they can be published and made available for consumption by applications, AI assistants, and agents. During publishing, the MCP assets are deployed through the DataPower Nano Gateway, which serves as the runtime foundation for the Interact Gateway.
>
> This step takes the MCP tools from design-time assets and makes them available at runtime.

---

## Narration — Locating the MCP Endpoint

> Now that the MCP tools have been published, ZillaForge needs a way for applications, assistants, and agents to access them.
>
> Publishing creates the governed MCP endpoint that serves as the entry point for AI interactions. This endpoint is what the ZillaForge Operations Portal used earlier when the AI assistant accessed product, inventory, order, and operational capabilities.
>
> We'll now navigate to the catalog where the published assets reside and locate the MCP endpoint. This endpoint can then be configured in AI assistants, agent frameworks, and other AI applications, allowing them to securely connect to the governed capabilities exposed through IBM DataPower Interact Gateway.

---

## Step 7 — Navigate to the Catalog

**Action:** From the left navigation pane, click **Manage**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c7e6d65a-374b-432c-b031-aa4486c9923e/user_cropped_screenshot_dd1501fc88254e6486f65e68aae84a63_text_export.jpeg)

**Action:** Click **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/8337b7b8-fdd9-45a8-897b-b7c5dae5b9bc/user_cropped_screenshot_90845cd67c854888856810ca01c02739_text_export.jpeg)

You can see the list of all published assets. Scroll to the right to find the MCP endpoint.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/806aa96f-5d17-4bc7-8a16-57e23c2c02a1/user_cropped_screenshot_976bdb9bffb24bc3b89ae04f79d1854d_text_export.jpeg)

---

## Step 8 — View MCP Endpoints

**Action:** For the **factoryapis-server** MCP, click the three dots and click **View endpoints**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/0d3fe424-9e28-4bf7-b0cc-f50dbc8be863/user_cropped_screenshot_5682aa9e56054468ae2608dfdcc7dd2a_text_export.jpeg)

Here you can see the MCP endpoints that you can use with applications, assistants, or AI agents as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/25aa87fc-5479-4719-be6d-89b01aa847e6/user_cropped_screenshot_15466bf7de714ac986179630a4bdd23e_text_export.jpeg)

---

## Step 9 — Open the Developer Portal

**Action:** Click **Products**, then click **Catalog settings**, then click **Portal**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-13/994bf6b9-234a-4a82-8106-27fb8611667d/action-041c89c39dc34fb78718978e20d83c6c_a734276ad1d143bca8c8e5ab2ed38961_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-13/c7aff388-8874-43f6-b549-bc63348fee18/action-7d00cd777327444f814a8ba1408df9bc_7b73ac3e2892482ba16514790b6a53fe_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-13/b35c0b57-328f-425a-b848-1e941f06ee48/action-130a801956f440818b5464f05e6435d1_56f5034c9ef7432392fa4e2b341ae059_text_export.jpeg)

**Action:** Click the Developer Portal link.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-13/5a2d5d15-96b7-4436-9507-ae2890e42536/action-7be77ab873ef42c0977f439f639ef13c_029833979c0d413f84a1562728576afd_text_export.jpeg)

---

**Previous:** [← ZillaForge AI Assistant](ai-assistant.md) | **Next:** [LLM Governance →](llm-governance.md)
