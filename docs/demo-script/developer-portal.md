# Part 5: Discover and Consume AI Assets Through the Developer Portal

So far, we've focused on how ZillaForge creates, governs, and publishes AI-ready capabilities. The next step is to look at the consumer experience.

Now, we're moving into the **Developer Portal**, where published AI assets can be discovered and accessed by teams. This provides a central location for finding approved enterprise capabilities and understanding how they can be consumed.

Just as the Developer Portal has traditionally been used to discover APIs, ZillaForge can now use it to publish and share governed AI assets, making it easier for teams to find and consume trusted capabilities while maintaining enterprise governance and control.

---

## Step 1 — Navigate to Manage

**Action:** From the left navigation menu, click **Manage**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/cb078ced-a0f6-4173-94a6-944d256d1bcc/user_cropped_screenshot_a4f17727136a49fb92b718d7d0547304_text_export.jpeg)

---

## Step 2 — Open the Interact Gateway MCP Catalog

**Action:** Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/11dcf64e-4343-4f1f-bf0f-80112b9921b3/user_cropped_screenshot_e67eb55abe1642eb8f06dcb3644b0e58_text_export.jpeg)

---

## Step 3 — Access Catalog Settings

**Action:** Click the **Catalog settings** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/47acdc6b-228a-448c-97a6-a277ef8ec332/user_cropped_screenshot_6da9e9b1dcc448b0961634c337446277_text_export.jpeg)

---

## Step 4 — Navigate to the Portal

**Action:** On the left pane, click **Portal**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bc606c34-f154-407f-8965-1cc0835c321b/user_cropped_screenshot_647e1431242d4eb48ef7849ac7783fb5_text_export.jpeg)

---

## Step 5 — Open the Developer Portal

**Action:** Click the **Portal endpoint URL** link: <a href="https://prod773957.devportal.a-fra-c2.apiconnect.ipaas.ibmappdomain.cloud" target="_blank">https://prod773957.devportal.a-fra-c2.apiconnect.ipaas.ibmappdomain.cloud</a>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/9ba68e95-0772-4fdb-bc40-76bbd6e5b77a/user_cropped_screenshot_0a372749890445baa583bcd9f71ad80c_text_export.jpeg)

---

## Step 6 — Sign In to the Developer Portal

The Developer Portal is displayed. On the top bar, click **Sign in**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/87dbb946-5d15-4a31-8583-fc992753bb68/user_cropped_screenshot_d115861dee754f11b37f864c19d579d6_text_export.jpeg)

You can sign in with your account details or with IBM WHI credentials. Here we are using **Sign in with IBM WHI**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/b38c37a3-ec54-4e50-b2c8-28f65101ecfb/user_cropped_screenshot_0f2b093749b043b2aa03166f266af9ba_text_export.jpeg)

---

## Step 7 — Open the Asset Gallery

The Developer Portal home page is displayed.

**Action:** From the left navigation menu, click **Asset gallery**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/4ea36ee2-728c-497d-a32d-72ceca6b8c60/user_cropped_screenshot_7f098f6a81074467a3198305c778384b_text_export.jpeg)

---

## Narration — Discovering Published AI Assets

> The Asset Gallery is where published AI assets become discoverable to consumers. We can see the MCP servers and capabilities that have been made available through the platform.
>
> Think of this as the catalog where applications, assistants, and agents can discover the capabilities they're allowed to use.
>
> Now that ZillaForge has registered and governed access to AWS Bedrock, we will validate the provider and its available model capabilities.

---

## Step 8 — Try Out the Bedrock Provider

**Action:** On the api-bedrock-conn-75rtd tile, click the **Tryout** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/043e0399-f8b2-4fa0-8551-3f5270ab0efd/user_cropped_screenshot_eeca206171014ac99c69bb3896970b33_text_export.jpeg)

Here you can see the same four operations you noticed while registering the LLM and in the policy sequence.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/f93c5828-ac65-4c92-8108-03370dce7050/user_cropped_screenshot_5c3cecc912a948669eb836d8f1c87793_text_export.jpeg)

---

## Narration — Testing the Models Operation

> Let's start by testing the Models operation. This operation retrieves the list of foundation models that are available through the AWS Bedrock provider. Applications, assistants, and agents can use this information to discover which approved models are available before they begin generating responses.
>
> For ZillaForge, this is a simple but important validation step. We're confirming that the gateway can successfully connect to the provider, authenticate the request, and return a valid response. If this operation succeeds, we know the connection and governance configuration are working as expected.

---

## Step 9 — Test the /models Operation

**Action:** On the left navigation pane, click **> /models** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5081035c-b54f-45bd-ac39-026f60db10c6/user_cropped_screenshot_134a45e9ac8b419bb71b47b40159776f_text_export.jpeg)

**Action:** Click **GET**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5881cebf-601c-4ba0-add9-1b75373e4c29/user_cropped_screenshot_884a66275e6d4f1daba43716a02772da_text_export.jpeg)

**Action:** Click the **Headers** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/40683c02-3333-4c06-8bf9-23375abf73ac/user_cropped_screenshot_a86b39523a1a40039416858ce7e7d4eb_text_export.jpeg)

We need to add the required headers.

**Action:** In the Key field, type **X-IBM-Client-Id**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/9cae2fef-28f6-49ae-a529-b3e9f6825242/user_cropped_screenshot_8bf4218524634bc6868177f460fc2ca2_text_export.jpeg)

**Action:** In the Value field, type **9d7f0a40739fcb334edf5beccb5ce744**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/c82f6bbc-93be-4b47-a5bb-a8997e7157d6/user_cropped_screenshot_f53d7819e3ae4d23a97130769cb3ca17_text_export.jpeg)

**Action:** Click **Add new**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/89c2f43f-287d-41a4-9532-deac8176b56d/user_cropped_screenshot_51382f5936164ee4b3f1b7fc8ab1aa73_text_export.jpeg)

Next we need to add the client secret.

**Action:** In the Key field, type **X-IBM-Client-Secret**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/2c197c6d-c354-496a-a989-14803bac4215/user_cropped_screenshot_9e04e5cd5d734f34aabf17c3a962afc1_text_export.jpeg)

**Action:** In the Value field, type **260c4607b62e4a4607fbac8289a7c6a9**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/a4a1eb97-1c60-43c0-bcfe-bbb8f2e5649b/user_cropped_screenshot_9e980340512645f48b298cb514691a87_text_export.jpeg)

**Action:** Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/714d93f3-c9f0-467e-983e-c60e89c76cfc/user_cropped_screenshot_a5ab5ab30633464c865f4088a2710fa2_text_export.jpeg)

**Action:** Scroll down to view the response.

You are now looking at the response from Bedrock. In this case, we're retrieving the models that are available for use.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/fe15a6cd-2f1e-4761-adda-e5da4511383a/user_cropped_screenshot_2ecd51739a9a4f868ee00a84c5063808_text_export.jpeg)

---

## Narration — Testing Chat Completions

> Next, let's test the **Chat Completions** operation, which is the capability the ZillaForge AI assistant uses to generate responses.
>
> Chat Completions sends a prompt to the foundation model and returns a generated answer. This is the same type of interaction that powers conversational assistants, AI agents, recommendations, and question-answering experiences.
>
> For ZillaForge, this test validates that a request can successfully pass through the Interact Gateway, have the appropriate governance policies applied, reach the approved LLM provider, and return a response. A successful result confirms that the end-to-end AI interaction is working as expected.

---

## Step 10 — Test Chat Completions

**Action:** On the left navigation pane, click **> /chat/completions** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/6a4017c8-a1c2-4425-8b88-f89a79bc4087/user_cropped_screenshot_1e928a920f224ba68f175c1c8fa7f584_text_export.jpeg)

**Action:** Click **POST**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/c68c3570-0026-48f2-ae11-9150af430838/user_cropped_screenshot_dfbf5c8966274f83a56d6bcd2955d291_text_export.jpeg)

**Action:** Under the Headers tab, click **Add new**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/00016703-b6b7-4cec-8071-b83111a08ef4/user_cropped_screenshot_9424498371974ceabd82684934750c77_text_export.jpeg)

Let's add the required headers again.

**Action:** In the Key field, type **X-IBM-Client-Id**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/135b9e82-1372-4b4c-a0fc-3b3f164a35dc/user_cropped_screenshot_56685d2b8aad4bcc87f6d6656bfcecc9_text_export.jpeg)

**Action:** In the Value field, type **9d7f0a40739fcb334edf5beccb5ce744**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/e8ed1c1f-a907-4846-a267-729491f80aa8/user_cropped_screenshot_012bf7aa99d04a9487053ffe93b73ec1_text_export.jpeg)

**Action:** Click **Add new** to add the client secret.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/80663c8a-09e2-4f3f-af74-6b0aea665b1b/user_cropped_screenshot_7ffae90e76e14d938d830627690e2b98_text_export.jpeg)

**Action:** In the Key field, type **X-IBM-Client-Secret**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/0151bbab-0380-40d2-8cde-d2029a480609/user_cropped_screenshot_dc66dbb1a99d49bdbb02d27eaf322193_text_export.jpeg)

**Action:** In the Value field, type **260c4607b62e4a4607fbac8289a7c6a9**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/104a551c-a435-4b96-a2ea-c460c3b8ef7e/user_cropped_screenshot_01782947ecf746c8ab98577dfd94cbc9_text_export.jpeg)

**Action:** Click the **Request Body** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/319cf3fb-0bea-436e-9813-0b6cc2f5e3af/user_cropped_screenshot_12a6e1aa949e451ab08eda7e57a403db_text_export.jpeg)

---

## Narration — Sending a Chat Completions Prompt

> Now we will provide the prompt that will be sent to the model. In this case we are asking a simple question: "What is Amazon Bedrock? Explain in 3 short bullet points."
>
> The goal isn't the question itself — it's simply to prove we can send a prompt through the gateway and get a response back.

---

## Step 11 — Submit the Chat Completions Request

**Action:** Copy and paste the following into the request body.

```json
{
  "model": "openai.gpt-oss-120b",
  "messages": [
    {
      "role": "user",
      "content": "What is Amazon Bedrock? Explain in 3 short bullet points."
    }
  ],
  "max_tokens": 512
}
```

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/4db95d7d-2a40-40b5-97c2-34bf2ad9af28/user_cropped_screenshot_a6143d5a3d3642a0ae959ddad6a57e88_text_export.jpeg)

**Action:** Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5484b4f7-bbac-411c-93eb-8ec4a76d75d3/user_cropped_screenshot_785df10257844feda1b1be5cb00bff9d_text_export.jpeg)

**Action:** Scroll down to review the generated response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/a44ee566-3583-460b-98bc-6bd8c5331afa/user_cropped_screenshot_fd4cf3fe242a45178d295f3951fd8b66_text_export.jpeg)

---

## Part 5 Summary

We've seen how ZillaForge can securely connect to and govern external LLM providers through the Interact Gateway.

We registered AWS Bedrock as a provider, applied governance policies, and validated the available model capabilities. We then tested both model discovery and chat completions to confirm that requests can be routed through a governed endpoint and successfully reach the approved foundation model provider.

For ZillaForge, this provides a consistent way to manage, secure, and monitor access to foundation models while applying the same governance principles already used for APIs and enterprise services.

---

**Previous:** [← Part 4: Register and Govern LLM Providers](llm-governance.md) | **Next:** [Part 6 - Monitor and Optimize AI Interactions with Analytics →](analytics.md)
