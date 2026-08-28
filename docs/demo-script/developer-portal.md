# Part 4: Discover and Consume AI Assets Through the Developer Portal

## Narration — The Consumer Experience

> So far, we've focused on how ZillaForge creates, governs, and publishes AI-ready capabilities. The next step is to look at the consumer experience.
>
> Now, we're moving into the **Developer Portal**, where published AI assets can be discovered and accessed by teams. This provides a central location for finding approved enterprise capabilities and understanding how they can be consumed.
>
> Just as the Developer Portal has traditionally been used to discover APIs, ZillaForge can now use it to publish and share governed AI assets, making it easier for teams to find and consume trusted capabilities while maintaining enterprise governance and control.

---

## Step 1 — Navigate to Manage

**Action:** From the left navigation menu, click **Manage**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/cb078ced-a0f6-4173-94a6-944d256d1bcc/user_cropped_screenshot_13f11a893acf4c419731a82211aee3e7_text_export.jpeg)

---

## Step 2 — Open the Interact Gateway MCP Catalog

**Action:** Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/11dcf64e-4343-4f1f-bf0f-80112b9921b3/user_cropped_screenshot_5e410cbf43b844208d4c612996de7ae5_text_export.jpeg)

---

## Step 3 — Access Catalog Settings

**Action:** Click the **Catalog settings** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/47acdc6b-228a-448c-97a6-a277ef8ec332/user_cropped_screenshot_5441c2c1343043d9b83b7ba05d3020cd_text_export.jpeg)

---

## Step 4 — Navigate to the Portal

**Action:** On the left pane, click **Portal**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/bc606c34-f154-407f-8965-1cc0835c321b/user_cropped_screenshot_deaea5f6e7af4232a604d8bf0a82fcca_text_export.jpeg)

---

## Step 5 — Open the Developer Portal

**Action:** Click the **Portal endpoint URL** link: <a href="https://prod773957.devportal.a-fra-c2.apiconnect.ipaas.ibmappdomain.cloud" target="_blank">https://prod773957.devportal.a-fra-c2.apiconnect.ipaas.ibmappdomain.cloud</a>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/9ba68e95-0772-4fdb-bc40-76bbd6e5b77a/user_cropped_screenshot_ed6fb5fa5a064e3a9d1b26d2e1c987d7_text_export.jpeg)

---

## Step 6 — Sign In to the Developer Portal

The Developer Portal is displayed. On the top bar, click **Sign in**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/87dbb946-5d15-4a31-8583-fc992753bb68/user_cropped_screenshot_565c24f4d3c549868f7e3b868a21a0d3_text_export.jpeg)

Sign in with the Developer Portal log in details you received in your **TechZone reservation email**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/48e04d5f-3e35-4bba-a70b-8277450e3448/user_cropped_screenshot_79256ec8308749168e89fa6aab437c7d_text_export.jpeg)

---

## Step 7 — Open the Asset Gallery

The Developer Portal home page is displayed.

**Action:** From the left navigation menu, click **Asset gallery**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/4ea36ee2-728c-497d-a32d-72ceca6b8c60/user_cropped_screenshot_f3e5e0f2f6cc4bf880c29813397be0ac_text_export.jpeg)

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

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/043e0399-f8b2-4fa0-8551-3f5270ab0efd/user_cropped_screenshot_8940c498c9eb4c8796b76c738b5a5aad_text_export.jpeg)

Here you can see the same four operations you noticed while registering the LLM and in the policy sequence.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/86dabc22-a72d-42d0-b698-79fc885f39ef/user_cropped_screenshot_dec0090a405c43e09e2566e250634ff2_text_export.jpeg)

---

## Narration — Testing the Models Operation

> Let's start by testing the Models operation. This operation retrieves the list of foundation models that are available through the AWS Bedrock provider. Applications, assistants, and agents can use this information to discover which approved models are available before they begin generating responses.
>
> For ZillaForge, this is a simple but important validation step. We're confirming that the gateway can successfully connect to the provider, authenticate the request, and return a valid response. If this operation succeeds, we know the connection and governance configuration are working as expected.

---

## Step 9 — Test the /models Operation

**Action:** On the left navigation pane, click **> /models** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/3bab6f78-77e9-486d-ac2b-11adcff763e6/user_cropped_screenshot_dd3e6a02263548cda475b61d9e512a89_text_export.jpeg)

**Action:** Click **GET**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/6545ab6c-3103-4f0b-8805-5c6643976a3a/user_cropped_screenshot_e46de1dcf5c348688d8b1645491b67cc_text_export.jpeg)

**Action:** Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/a1178fad-99e5-4a83-a062-3c72ca03582e/user_cropped_screenshot_83f311ef460a44b3a577b9751781d5c9_text_export.jpeg)

**Action:** Scroll down to view the response.

You are now looking at the response from Bedrock. In this case, we're retrieving the models that are available for use.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/6d24bc4c-788b-4845-a401-5f563690c462/user_cropped_screenshot_446a985b9fc84c78ab89d598fb006614_text_export.jpeg)

---

## Narration — Testing Chat Completions

> Next, let's test the **Chat Completions** operation, which is the capability the ZillaForge AI assistant uses to generate responses.
>
> Chat Completions sends a prompt to the foundation model and returns a generated answer. This is the same type of interaction that powers conversational assistants, AI agents, recommendations, and question-answering experiences.
>
> For ZillaForge, this test validates that a request can successfully pass through the Interact Gateway, have the appropriate governance policies applied, reach the approved LLM provider, and return a response. A successful result confirms that the end-to-end AI interaction is working as expected.

---

## Step 10 — Test Chat Completions

**Action:** On the left navigation pane, click **> /chat/completions** to expand it and click **POST**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/e07a15b6-1fbc-4461-9869-8a53cffbf0fe/user_cropped_screenshot_713e559b89d445a390734414454f4e17_text_export.jpeg)

**Action:** Click the **Request Body** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/4740b087-bd11-411c-8b16-8a378ca16af6/user_cropped_screenshot_5e614339e0a44d329498f1786cc38679_text_export.jpeg)

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

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-28/d2e5168d-ab88-414e-b6cf-a1d523c6be2b/user_cropped_screenshot_cabcd054051b4deda050fa3d09f47245_text_export.jpeg)

**Action:** Click **Send**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/5484b4f7-bbac-411c-93eb-8ec4a76d75d3/user_cropped_screenshot_332e7f9a9e064222a62a0287d2c58dd9_text_export.jpeg)

**Action:** Scroll down to review the generated response.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-18/a44ee566-3583-460b-98bc-6bd8c5331afa/user_cropped_screenshot_a074a87dbdd3436f90dadc0737a7f9bd_text_export.jpeg)

---

## Wrap-up

> We've seen how ZillaForge can securely connect to and govern external LLM providers through the Interact Gateway.
>
> We registered AWS Bedrock as a provider, applied governance policies, and validated the available model capabilities. We then tested both model discovery and chat completions to confirm that requests can be routed through a governed endpoint and successfully reach the approved foundation model provider.
>
> For ZillaForge, this provides a consistent way to manage, secure, and monitor access to foundation models while applying the same governance principles already used for APIs and enterprise services.

---

**Previous:** [← Part 3: Register and Govern LLM Providers](llm-governance.md) | **Next:** [Part 5 - Monitor and Optimize AI Interactions with Analytics →](analytics.md)
