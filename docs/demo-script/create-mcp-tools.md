# Part 3: Create and Publish MCP Tools from an Existing API

In the first part of this demo, we explored how ZillaForge transformed existing enterprise APIs into governed AI-ready capabilities using IBM DataPower Interact Gateway.

Now we will **create** governed MCP tools from an existing API. We'll discover API operations, select the capabilities to expose, apply enhancements, and prepare the tools for publication through IBM DataPower Interact Gateway. This workflow demonstrates how organizations can transform existing enterprise services into AI-ready capabilities without building new back-end systems.

---

## Step 1 — Open API Studio

**Action:** From the left navigation pane, click the **API Studio** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/118f69d1-1bec-493c-aa85-adb7f701c698/user_cropped_screenshot_dda745e96e184b1683063644ad5b1eb8_text_export.jpeg)

---

## Step 2 — Create a New Project

**Action:** On the right, click **New API project**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/669c9e20-3d16-44a4-b4a3-5978820c66e2/user_cropped_screenshot_e1b0f884dc8345889829f91188e75f3c_text_export.jpeg)

**Action:** Click **Create a new project**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/765531f1-3a67-4b8e-95d6-f4a105d89d3a/user_cropped_screenshot_b85dd4b09a6d4a4db901abe7d3cc9c13_text_export.jpeg)

**Action:** In the Project name field, type **ZillaForge\<yourinitials\>\<MonthYear\>** — for example, **ZillaForgeATAug2026**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/3b71f395-e20d-4882-b300-cc90ac549a4c/user_cropped_screenshot_55af1c2fcc044497bdf9215db763572a_text_export.jpeg)

**Action:** In the Description field, type an optional description.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/80712d72-4f5f-43ae-9bf8-52d5d2f67123/user_cropped_screenshot_da760979cd6044fc966b03ccfa498006_text_export.jpeg)

**Action:** Leave the default value for the Save to field and click **Create**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/22f17469-8cd4-4e86-a753-f9969207fd16/user_cropped_screenshot_518004cebe374479a094dc5ba8f9882f_text_export.jpeg)

---

## Step 3 — Open the New Project

**Action:** Open the newly created project.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/0b2a5965-213b-4877-a9ed-3511ff9b3c0c/user_cropped_screenshot_5d835f95d8b74d5da96744c385b036a0_text_export.jpeg)

!!! tip "Important"
    Once you open the project, if you're not in AI view, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/26d22f12-8c4e-47e0-bcf9-0522c68d7f3c/screenshot_e7c7b6e3820e4694b144473c3f8dc813_text_export.jpeg)

---

## Narration — Transforming an Existing API into MCP Tools

> Now, we will use an existing **Inventory API** and transform its operations into AI-ready MCP tools. The operations defined in the API specification are analyzed and converted into MCP tools.

---

## Step 4 — Generate MCP Tools

**Action:** Click **Generate MCP tools**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/e4c9c2bb-13b9-4f8d-bb6e-0eda9726a0b3/user_cropped_screenshot_9cdf7f5eb8f04bde9cdd2bf3d72d904c_text_export.jpeg)

**Action:** Click **Generate from REST API**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/8ecf30cd-ced8-4c25-b617-d724d7a3ae3a/user_cropped_screenshot_8232e708c33544128fe9d8c2785bb88a_text_export.jpeg)

**Action:** Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/06b95f49-17d4-4d65-b369-4ab11f8c37c2/user_cropped_screenshot_914b265fda8848809ae76cc431584387_text_export.jpeg)

---

## Narration — Importing the API Definition

> When creating an MCP server, you can start from an existing API, import an external API definition, or use APIs that are already registered and governed through Federated API Management. In this example, we will use an existing Inventory API defined in a YAML specification.

---

## Step 5 — Import the API File

**Action:** Click **From external**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/56ce3068-90e9-4879-9076-b87dbd9f2f62/user_cropped_screenshot_f2f8a525bcc641a0abf3942d01715ade_text_export.jpeg)

**Action:** Click **Drag and drop an API file here or click to upload** and navigate to the **InventoryAPIs.yaml** file you downloaded earlier in the lab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/eb1a868c-7300-4cb1-ba71-a1b156142ea1/user_cropped_screenshot_d281f53ed01b4df2a8b4fe4234195268_text_export.jpeg)

**Action:** Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/f12476fe-efe1-428c-b7fe-473ad0944af8/user_cropped_screenshot_edcc89013c744bd5852134a6ab954fdf_text_export.jpeg)

---

## Narration — Selecting Operations to Expose

> As part of the MCP tool creation process, the operations defined in the API specification are identified and made available for conversion into MCP tools. Teams can choose exactly which operations should be exposed to AI, ensuring that only the intended business capabilities are available to assistants and agents while retaining control over sensitive or unnecessary functionality.

---

## Step 6 — Select API Operations

**Action:** Click the **expand** icon to view the /productcatalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/faeebd1a-b5e0-4565-9a58-55247880e987/user_cropped_screenshot_1acd407d5802453895bd58a32c72e83e_text_export.jpeg)

**Action:** Click the **expand** icon to view the /inventories.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2af5eac0-e872-4906-9fc9-6b682a7e372a/user_cropped_screenshot_d35e9bd43dfc4e53900b6da88b0c7809_text_export.jpeg)

**Action:** Select the top-level checkbox to include all the paths and methods.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/abc8d8fd-9e5e-4624-ad61-7ab48f615e20/user_cropped_screenshot_c021fb9f9c66449ca5b3286ebeb83855_text_export.jpeg)

**Action:** Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/1545883d-ef8a-4fad-9e19-d5ff36623fa6/user_cropped_screenshot_9e29c4e4aa2745498bca7ae88feadc64_text_export.jpeg)

---

## Narration — Enhancing MCP Tools for AI

> Once the tools have been generated, you can further improve how those capabilities are presented to AI by using the **MCP Server Enhancer**.
>
> Tool names, descriptions, and parameter definitions can be refined to provide clearer instructions to AI assistants and agents. These enhancements help the AI better understand the purpose of each tool, when it should be used, and how it should be invoked.

---

## Step 7 — Enhance the Tools

**Action:** Click **Enhance tools**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/eca2757d-918e-47af-bb33-01c25093a789/user_cropped_screenshot_c597185d435f44c09e7394f16c95962a_text_export.jpeg)

You can see the enhanced tool names and descriptions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/074c2d14-5ac1-4fb6-9031-cf842e3f7179/user_cropped_screenshot_4fe673feed9c4a3cb67c691f5c9e6527_text_export.jpeg)

**Action:** Click **Apply all**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/90e4b2e9-17aa-4d72-af39-6efa8dbab0aa/user_cropped_screenshot_02bdbeed18784f379709c6a84d2ce021_text_export.jpeg)

**Action:** Review all the details and once you're done, click **Generate**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fbdf140c-039c-4257-9290-719cfa63a73d/user_cropped_screenshot_fe4fa9dcbe454576bd145a8ecaa66328_text_export.jpeg)

---

## Narration — Reviewing the Generated Policy Sequence

> The MCP server has now been generated, and the selected API operations have been converted into AI-ready tools.
>
> You'll notice that, in addition to the MCP tools, a **policy sequence** has also been created. If you're familiar with API Connect, this should look familiar. The policy sequence defines what happens when the gateway receives an MCP request, just as it would for a traditional API request.
>
> The next step is to review and enrich this policy flow. These policies allow you to apply security, transformation, rate limiting, authorization, and other controls before a request reaches the backend service. Because governance is applied at the gateway layer, organizations can enforce consistent standards across AI interactions without modifying the underlying APIs or services.
>
> This is where Interact Gateway moves beyond simple tool generation and becomes a governance layer for AI interactions. The key point is that AI requests can be governed using the same policy framework organizations already use for APIs.

---

## Step 8 — Review the Policy Flow

**Action:** From the Explorer pane, click the policy under MCP servers.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/25b815c2-4f92-4189-8a96-b6f92f874f90/user_cropped_screenshot_eeadec39d0374ad8bbb8c8f19e585b72_text_export.jpeg)

**Action:** By default, there is only 1 operation. Click the **Invoke** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2140d5d2-fbb1-40c0-8491-b6f410cd11cb/user_cropped_screenshot_f2a8b6fc6a9e42bca42ad59504c6a614_text_export.jpeg)

In the Invoke Policy pane, you can see that this existing API is hosted and managed in another environment through a webMethods API Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/79a0d25b-4d2f-431b-ae90-d578f8d75ad1/user_cropped_screenshot_b1b8bc5c74be47d0abc0b1d8d645fb8a_text_export.jpeg)

---

## Step 9 — Add an API Key Policy

**Action:** Click the **plus** icon on the left of the Invoke operation to add a new operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/293b486d-e4a8-46f2-ba14-6a6026750f88/user_cropped_screenshot_c18ce47913f04e77aef0095fb8d21392_text_export.jpeg)

**Action:** Scroll down the assembly flow and click the **Set** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/0eee002a-88cf-4e68-961f-0ddd4c940a75/user_cropped_screenshot_7b774562b3494395a51f71f2174587a0_text_export.jpeg)

Here we're supplying the required API key to validate the API and confirm the capability is working correctly.

**Action:** In the Header name field, type **x-Gateway-APIKey**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/82d483cf-507b-4c91-b10e-f7ce15593dd8/user_cropped_screenshot_19a5e77567814069a84e220f79f4b1dc_text_export.jpeg)

**Action:** In the Value field, type **2d6bea7d-76d5-4b3f-8c6a-9dd2d5dc7bd7**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/56120cf7-ba9c-428c-942e-d9d9158a5b8e/user_cropped_screenshot_a0dfdb202cba4895929609f020055947_text_export.jpeg)

**Action:** Click the **close** icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/d4939fa9-4c60-4c71-86f9-c835820ae2a7/user_cropped_screenshot_874f6a6db0384391bc48738827079800_text_export.jpeg)

---

## Step 10 — Add a Content-Type Policy

**Action:** Click the **plus** icon on the left of the Set operation to add another operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/045f9cd5-40af-4da9-adcb-b04a0e8e3cb0/user_cropped_screenshot_a6044ae66b8d409d89e77db99cc352f1_text_export.jpeg)

**Action:** Scroll down the assembly flow and click the **Set** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/a68b94be-94fc-4883-b2cd-3e444d245634/user_cropped_screenshot_5dbb572aecec4d4897c92c2e937ab8ce_text_export.jpeg)

**Action:** In the Header-name field, type **Content-Type**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4f6df508-1dbf-4151-ae27-07d766e2102a/user_cropped_screenshot_66c50fdea87249be8010a81d4449aeff_text_export.jpeg)

**Action:** In the Value field, type **application/json**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2d6c2e70-31c7-461a-9d2e-cd87fb463dd1/user_cropped_screenshot_cb6cd6eda3394cf1ae1ee5dfa9a17f89_text_export.jpeg)

**Action:** Click the **close** icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fab3fba2-51c6-4d76-a016-d49d3ca3e101/user_cropped_screenshot_5da937ac31784bc99baef0ad3a81e85a_text_export.jpeg)

---

## Step 11 — Publish the MCP Tools

**Action:** Click **Publish** to publish the MCP tools through the Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4de26a1b-7913-4efb-b51b-6ad2ae7c2d62/user_cropped_screenshot_333bfffa44774a25887374a23298fce1_text_export.jpeg)

**Action:** From the Catalog list, select **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/65cbf8ea-c8d0-4d0f-a738-bf60a6aa57c9/user_cropped_screenshot_c9b6f706c1b64c03905501ce82458727_text_export.jpeg)

**Action:** Click **Next** to continue.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/991a56f0-223e-42a6-b22b-7b9146dfc079/user_cropped_screenshot_f276589617a54e90a2190ac0acfe9e24_text_export.jpeg)

**Action:** Expand the MCP Server to view all the associated assets and policy sequence.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/c93aa912-dcd9-4641-b7f1-25a62b727b2a/user_cropped_screenshot_0044e5e85f334a81a4bc9fcd0681c92a_text_export.jpeg)

**Action:** Click **Publish**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/115eb5df-5142-4f5b-8a77-88e1ec44cf99/user_cropped_screenshot_61a28f9f1e7d4fa68c2b9d29bb0a0dd5_text_export.jpeg)

---

## Narration — Locating the MCP Endpoint

> Once the MCP tools have been published, they are exposed through a governed **MCP endpoint** that can be consumed by AI assistants, agents, and applications.
>
> We'll now navigate to the catalog to locate the published MCP endpoint. This endpoint can then be configured in AI applications, allowing them to securely access the enterprise capabilities exposed through IBM DataPower Interact Gateway.

---

## Step 12 — View the Published MCP Endpoint

**Action:** In the Publish successful notification, click **Catalog**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2c975c2e-277e-442a-b507-0f2e16c50f26/action-4ffb9d5a4cb049ceaf666b894da04b80_ce93949b4bd7463ab7861e0648fb210a_text_export.jpeg)

!!! tip
    You can also locate the MCP endpoint by navigating to **Manage > Interact Gateway MCP** catalog.

You can see all the published assets in the Interact Gateway MCP catalog. If the list is long, you can choose to filter by type.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fb12d17b-e293-4067-b2f2-3872f8506e67/user_cropped_screenshot_17f3143677d841e6b3e37b718b47fcc1_text_export.jpeg)

**Action:** Drag the scrollbar to scroll to the right.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/cec9e458-e23d-47ee-a34c-aa69664c25dc/user_cropped_screenshot_87524f6ae57f47869964fe3970dbed44_text_export.jpeg)

**Action:** For the newly published inventoryapis-server, click the **three dots** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/c5aeeb69-be05-42a8-8eb9-6dea5e25f970/user_cropped_screenshot_f628d6b7ae184e5db7575ce417453284_text_export.jpeg)

**Action:** Select **View endpoints**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/59a9dbb7-d048-4d11-bdce-8049ae97203f/user_cropped_screenshot_4d57510c65fd47c29b9cf73fc5e8a703_text_export.jpeg)

Here you can see the MCP endpoints that you can use with applications, assistants, or AI agents as needed.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/7cf30fc7-5043-49a9-bdf9-54e06430548b/action-37f386a01f9547559a316f8f9f9b7bee_9e7d237bcf994fbda7f50233d5c11ebd_text_export.jpeg)

---

!!! warning "Important — Cleanup Required"
    After you have finished testing your MCP endpoint with an AI assistant, agent framework, or other AI application, please take a few moments to **delete the project you created** during this exercise.

    Removing unused projects helps keep the shared environment clean and available for future learners. It also prevents the accumulation of unnecessary MCP servers, policies, and published assets.

    Only delete the project and assets **you created** during this exercise. Do **not** modify, delete, or republish any of the preconfigured **ZillaForge** projects, MCP servers, policies, catalogs, or other shared assets.

    **Cleanup Tasks:**

    1. Return to the project you created for this exercise.
    2. Delete the MCP assets you published.
    3. Delete the project.
    4. Verify that the project has been removed from the project list.

    ![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/020b8287-4f3f-4574-9064-7d17e2137553/screenshot_c842dd435c4e428bb082592f72597175_text_export.jpeg)

---

## Step 13 — Navigate to the Catalog

**Action:** From the left navigation pane, click **Manage**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/c7e6d65a-374b-432c-b031-aa4486c9923e/user_cropped_screenshot_a5902a4158c94ed383895d63767b73f6_text_export.jpeg)

**Action:** Click **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/8337b7b8-fdd9-45a8-897b-b7c5dae5b9bc/user_cropped_screenshot_9ad83c1749254438bda93bf6dc563040_text_export.jpeg)

---

**Previous:** [← Part 2: Explore Governed MCP Tools](mcp-tools.md) | **Next:** [Part 4 - Register and Govern LLM Providers →](llm-governance.md)
