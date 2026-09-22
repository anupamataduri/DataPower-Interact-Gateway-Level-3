# Part 3: Register and Govern LLM Providers

## Narration — Governing LLM Providers

> So far, we've seen how ZillaForge exposes enterprise capabilities as governed MCP tools that can be consumed by AI assistants and agents. ZillaForge also needs a way to manage and control access to the foundation models and LLM providers that power its AI experiences.
>
> To address this, ZillaForge uses the Interact Gateway to register and govern LLM providers. In this demo, we'll use **Amazon Bedrock** as an example, but the same approach can be applied to other providers such as watsonx.ai, Azure OpenAI, Google Gemini, and other supported model providers.
>
> Rather than allowing applications and agents to connect directly to external model endpoints, requests can be routed through Interact Gateway, where consistent security, access controls, policies, and observability can be applied.
>
> This gives ZillaForge a centralized approach to AI governance. The organization can manage which models are available, control access to approved providers, monitor usage, and apply the same governance principles already used for APIs and enterprise services to its LLM interactions.

---

## Narration — Managing Credentials for LLM Providers

> Before registering an LLM provider, ZillaForge performs a one-time setup activity to securely manage credentials and access tokens.
>
> Organizations can securely store and manage secrets using AWS Secrets Manager, Azure Key Vault, or HashiCorp Vault.
>
> This approach improves security, simplifies credential management, and allows ZillaForge to securely authenticate with external LLM providers.

---

## Step 1 — Open Instance Settings

**Action:** On the top right corner, click **Instance Settings**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/cdf08e5c-de48-4eed-b9bb-173e0d3037c4/user_cropped_screenshot_94f6cbee1cfd46909ab8952d7c91ffae_text_export.jpeg)

---

## Step 2 — View the Secrets Tab

**Action:** On the Instance settings page, click the **Secrets** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b0be1fa-802d-4868-b832-58276669d5ae/user_cropped_screenshot_5846df9652304381afbd5759f55bc8a4_text_export.jpeg)

Here you can connect to AWS Secrets Manager, Azure Key Vault, or HashiCorp Vault to manage secrets for your Interact Gateway.

**Action:** Click **Back** once you are done.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/6b20fa92-0d5d-46da-a67c-90fb43610a2e/user_cropped_screenshot_a177701361a94a459c34a3e9802691cf_text_export.jpeg)

---

## Narration — Registering the AWS Bedrock Provider

> Let's now look at how ZillaForge manages access to external foundation models. In this demo, ZillaForge has registered **AWS Bedrock** as an LLM provider.
>
> We'll open the Bedrock project and examine how the provider was configured. In addition to the provider registration itself, you'll see the policy sequence associated with the LLM endpoint. Just as we saw with MCP tools, ZillaForge can apply governance controls before requests are sent to the model provider.

---

## Step 3 — Open the ZFBedrock Project

**Action:** In API Studio, click the **ZFBedrock** project.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bb8644da-2f70-4d97-b1a1-655c7fc4091a/user_cropped_screenshot_f4f70f0abe054400b64e7840ff2e1f8f_text_export.jpeg)

!!! tip "Important"
    Once you open the project, if you're not in AI view, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/26d22f12-8c4e-47e0-bcf9-0522c68d7f3c/screenshot_6e4f24a6b9ca48638c00ae77511bf7f2_text_export.jpeg)

---

## Step 4 — Open the Bedrock LLM Provider

**Action:** On the Explorer pane, under LLM providers, click **bedrock-conn | 1.0**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/ff941500-fe41-4dee-8230-38123bf8e5ee/user_cropped_screenshot_7784d32b5f7745f7abbeabc34f85ed84_text_export.jpeg)

---

## Narration — Reviewing the Provider Configuration

> Here we're looking at the configuration of a registered LLM provider.
>
> ZillaForge defined the connection details for the provider, including the base path and the specific model operations that should be exposed and available for use. In this example, four operations have been selected for consumption.
>
> This gives ZillaForge control over which model capabilities are available to applications, assistants, and agents, ensuring that only approved operations are exposed through the Interact Gateway.

---

## Step 5 — View Exposed Operations

**Action:** Click the **Select operations to expose** menu to view the list of operations.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/dbe9a9c8-181a-4796-b9ed-fbf496373982/user_cropped_screenshot_be16adb21afa47c0ba24fd3c468bc473_text_export.jpeg)

You can see four operations exposed through the Interact Gateway that will be available for assistants, agents, etc.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/fa6184a9-06eb-4686-8dd8-e6cc6c6a4c9d/user_cropped_screenshot_606a7960e4e54e9bbea4f1b33706dc2e_text_export.jpeg)

**Action:** Click the **menu** to collapse it.

---

## Narration — Reviewing Connection Details

> You can also view the connection details. This configuration defines how Interact Gateway connects to the external LLM service. You can see the provider URL, the authentication configuration, and the secret that will be used to securely authenticate requests.
>
> Notice the API key secret name field. This references the secret that was configured earlier in the Secrets section.

---

## Step 6 — View Connection Details

**Action:** Scroll down to view the connection details.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/dc822367-ef12-40be-afaf-15784401bf9f/user_cropped_screenshot_75ea59b2530c4a7cac7257efe741724e_text_export.jpeg)

The TLS client profile defines the TLS configuration used when establishing secure connections to the external provider.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5b45059f-29dd-469d-8205-5a8d8946f1d7/user_cropped_screenshot_f19e8924ec1b4381bd743791426eaa3d_text_export.jpeg)

---

## Narration — Reviewing the LLM Policy Sequence

> Now let's look at the **policy sequence** associated with the Bedrock provider.
>
> Just as we applied governance to MCP tools, ZillaForge can apply governance to LLM interactions. The policy sequence defines what happens when a request is sent to AWS Bedrock, allowing the organization to inspect, secure, transform, monitor, or control requests before they reach the external model provider.

---

## Step 7 — Open the Bedrock Policy Sequence

**Action:** Under LLM providers, click **freeflowpolicysequence-bedrock-conn-75trd**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/7d4b6c7a-74fd-4665-a77c-66027ab19ba1/user_cropped_screenshot_c32b46bdd1e649059b98a482b4977679_text_export.jpeg)

---

## Step 8 — Inspect the ExtractIdentity Policy

**Action:** Click **ExtractIdentity**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5e646565-b687-45a8-8fd5-e8288713d1d7/user_cropped_screenshot_7bf919f2eb5344f88f30f91a3dc8bcb3_text_export.jpeg)

This operation extracts the client credentials from the incoming request by reading the **X-IBM-Client-Id** and **X-IBM-Client-Secret** HTTP headers. The identity information can then be used by subsequent policies for authentication, authorization, rate limiting, auditing, and other governance controls.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/fd06fa54-9383-4396-83dc-c387de165a5d/user_cropped_screenshot_f6166301684d43f98f2112b30e126ff9_text_export.jpeg)

**Action:** Click the **close** icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/0787bffe-310c-4fc6-a2fd-802f642a6109/user_cropped_screenshot_ae2692f32b9d4f479ef1f949e07cceba_text_export.jpeg)

---

## Step 9 — Review Additional Policy Operations

**Action:** Scroll to the right to view other operations.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/b245f547-7a54-4144-b392-84cfaee48a13/user_cropped_screenshot_0a145553b8e143618f8fc13ef1b352df_text_export.jpeg)

Here you can see separate operations have been configured for **chat completions**, **embeddings**, and **model discovery**. Each operation represents a specific model capability that can be invoked through the governed provider endpoint.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/1121b197-9d4b-473a-ad53-120b6f990009/user_cropped_screenshot_b181cc6b43e54865b3c83aeb2ddd086d_text_export.jpeg)

---

## Wrap-up

> We've seen how ZillaForge can register external LLM providers, securely manage credentials and connectivity, and apply governance controls through policy sequences before requests reach the model provider.
>
> By managing LLM access through the Interact Gateway, organizations can centralize security, enforce governance policies, control which model capabilities are exposed, and gain greater visibility into how foundation models are used across the enterprise.

---

**Previous:** [← Part 2: Explore Governed MCP Tools](mcp-tools.md) | **Next:** [Part 4 - Discover and Consume AI Assets Through the Developer Portal →](developer-portal.md)
