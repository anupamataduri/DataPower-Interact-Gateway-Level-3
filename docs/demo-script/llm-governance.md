# Part 4: Register and Govern LLM Providers

So far, we've seen how ZillaForge exposes enterprise capabilities as governed MCP tools that can be consumed by AI assistants and agents. ZillaForge also needs a way to manage and control access to the foundation models and LLM providers that power its AI experiences.

To address this, ZillaForge uses IBM DataPower Interact Gateway to register and govern LLM providers. In this demo, we'll use **Amazon Bedrock** as an example, but the same approach can be applied to other providers such as watsonx.ai, Azure OpenAI, Google Gemini, and other supported model providers.

Rather than allowing applications and agents to connect directly to external model endpoints, requests can be routed through Interact Gateway, where consistent security, access controls, policies, and observability can be applied. This gives ZillaForge a centralized approach to AI governance — managing which models are available, controlling access to approved providers, and applying the same governance principles already used for APIs to LLM interactions.

---

## Narration — Managing Secrets for LLM Access

> Before registering an LLM provider, ZillaForge performs a one-time setup activity to securely manage credentials and access tokens.
>
> Organizations can securely store and manage secrets using AWS Secrets Manager, Azure Key Vault, or HashiCorp Vault. Rather than embedding API keys directly in applications, gateways, or agent configurations, sensitive credentials are stored and managed centrally.
>
> This approach improves security, simplifies credential management, and allows ZillaForge to securely authenticate with external LLM providers.

---

## Step 1 — Open Instance Settings

**Action:** On the top right corner, click **Instance Settings**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/cdf08e5c-de48-4eed-b9bb-173e0d3037c4/user_cropped_screenshot_6d99ee6782754a24bfbc6f1b38ce003f_text_export.jpeg)

---

## Step 2 — View the Secrets Tab

**Action:** On the Instance settings page, click the **Secrets** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b0be1fa-802d-4868-b832-58276669d5ae/user_cropped_screenshot_17bede4138b642a8a31f6b5ce7771c1d_text_export.jpeg)

Here you can connect to **AWS Secrets Manager**, **Azure Key Vault**, or **HashiCorp Vault** to manage secrets for your Interact Gateway.

Click **Back** once you are done.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/6b20fa92-0d5d-46da-a67c-90fb43610a2e/user_cropped_screenshot_d586f95cb6844a0e8194648acdcf02a7_text_export.jpeg)

---

## Narration — Registering an LLM Provider

> Let's now look at how ZillaForge manages access to external foundation models.
>
> For this example, ZillaForge has registered **AWS Bedrock** as an LLM provider, although the same process can be used for other providers such as watsonx.ai, Azure OpenAI, Google Gemini, Anthropic, or any supported model platform.
>
> We'll open the Bedrock project and examine how the provider was configured. In addition to the provider registration itself, you'll see the policy sequence associated with the LLM endpoint. Just as we saw with MCP tools, ZillaForge can apply governance controls before requests are sent to the model provider.
>
> This allows the organization to enforce security, authentication, usage policies, observability, and other controls consistently across LLM interactions. Rather than connecting directly to external model endpoints, applications and agents can access approved models through a governed entry point managed by IBM DataPower Interact Gateway.
>
> The result is a centralized approach to LLM governance that gives ZillaForge visibility and control over how foundation models are used across the enterprise.

---

## Step 3 — Open the ZFBedrock Project

**Action:** In API Studio, click the **ZFBedrock** project.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bb8644da-2f70-4d97-b1a1-655c7fc4091a/user_cropped_screenshot_0b9a8df35266412e879362e2ad690f7c_text_export.jpeg)

---

**Previous:** [← Part 3: Create and Publish MCP Tools](create-mcp-tools.md) | **Next:** [Part 5 - Developer Portal →](developer-portal.md)
