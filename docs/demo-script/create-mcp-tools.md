# Part 3: Create and Publish MCP Tools from an Existing API

## Narration — Creating Governed MCP Tools

> In the first part of this demo, we explored how ZillaForge transformed existing enterprise APIs into governed AI-ready capabilities using the Interact Gateway.
>
> Now we will create governed MCP tools from an existing API. We'll discover API operations, select the capabilities to expose, apply enhancements, and prepare the tools for publication through the Interact Gateway. This workflow demonstrates how organizations can transform existing enterprise services into AI-ready capabilities without building new back-end systems.

---

## Step 1 — Open API Studio

**Action:** From the left navigation pane, click the **API Studio** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/118f69d1-1bec-493c-aa85-adb7f701c698/user_cropped_screenshot_03c4c19f75d54f2fb5be032b8f684eef_text_export.jpeg)

---

## Step 2 — Create a New Project

**Action:** On the right, click **New API project**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/669c9e20-3d16-44a4-b4a3-5978820c66e2/user_cropped_screenshot_7ce00c2447124fbabba746f761d3502a_text_export.jpeg)

**Action:** Click **Create a new project**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/765531f1-3a67-4b8e-95d6-f4a105d89d3a/user_cropped_screenshot_2933e5550d524651b3e04ca9e8541fcb_text_export.jpeg)

**Action:** In the Project name field, type **ZillaForge\<yourinitials\>\<MonthYear\>** — for example, **ZillaForgeATAug2026**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/3b71f395-e20d-4882-b300-cc90ac549a4c/user_cropped_screenshot_795627b2c82e44ff9ce3459f1651b8d7_text_export.jpeg)

**Action:** In the Description field, type an optional description.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/80712d72-4f5f-43ae-9bf8-52d5d2f67123/user_cropped_screenshot_6ac4ffde6ee04556a6ef79d5d3f31b2c_text_export.jpeg)

**Action:** Leave the default value for the Save to field and click **Create**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/22f17469-8cd4-4e86-a753-f9969207fd16/user_cropped_screenshot_9758ded412d34dbb9062cb4af193d7be_text_export.jpeg)

---

## Step 3 — Open the New Project

**Action:** Open the newly created project.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/0b2a5965-213b-4877-a9ed-3511ff9b3c0c/user_cropped_screenshot_4389319f1dae44eaa8cbb183e9f209ee_text_export.jpeg)

---

## Narration — Transforming an Existing API into MCP Tools

> Now, we will use an existing **Inventory API** and transform its operations into AI-ready MCP tools. The operations defined in the API specification are analyzed and converted into MCP tools.
>
> Before continuing, download the Inventory API YAML file needed for this step and save it to your local machine.

---

## Step 4 — Download the Inventory API YAML File

**Action:** Navigate to: <a href="https://github.com/anupamataduri/DataPower-Interact-Gateway-Level-3/blob/main/lab-files/InventoryAPIs.yaml" target="_blank">https://github.com/anupamataduri/DataPower-Interact-Gateway-Level-3/blob/main/lab-files/InventoryAPIs.yaml</a>

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/0a2263eb-2c63-4d3e-83a3-d7061d0f1bc0/screenshot_1f9181cfcc534cd686d45c577c32e153_text_export.jpeg)

**Action:** Click the **Download raw file** icon in the top-right corner of the page. Save the file to your local machine.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/4f5bea56-ba15-4b22-bdc5-aeb9821780ef/user_cropped_screenshot_05c33bf0fa6d46389b168d6ccc9e6389_text_export.jpeg)

!!! tip "Important"
    Once you open the project, if you're not in AI view, use the **view selector in the upper-right corner** to switch to the **AI view**. This reveals the AI-specific capabilities, including MCP tools and related AI assets that are not visible in the standard API development view.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/26d22f12-8c4e-47e0-bcf9-0522c68d7f3c/screenshot_4e96f224d9cb4dcd81f26936d40835af_text_export.jpeg)

---

## Step 5 — Generate MCP Tools

**Action:** Back in the ZillaForge project, click **Generate MCP tools**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/e4c9c2bb-13b9-4f8d-bb6e-0eda9726a0b3/user_cropped_screenshot_5373d9187874408a9f55af8d7433fd9b_text_export.jpeg)

**Action:** Click **Generate from REST API**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/8ecf30cd-ced8-4c25-b617-d724d7a3ae3a/user_cropped_screenshot_3882b84b50f34c4da0e2a823cd35913f_text_export.jpeg)

**Action:** Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/06b95f49-17d4-4d65-b369-4ab11f8c37c2/user_cropped_screenshot_690122622cb948ed8ca04bd50900e67b_text_export.jpeg)

---

## Narration — Importing the API Definition

> When creating an MCP server, you can start from an existing API, import an external API definition, or use APIs that are already registered and governed through Federated API Management. In this example, we will use the existing Inventory API defined in a YAML specification.

---

## Step 6 — Import the API File

**Action:** Click **From external**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/56ce3068-90e9-4879-9076-b87dbd9f2f62/user_cropped_screenshot_bd4fbeb926b8456cabd71a4113f5a073_text_export.jpeg)

**Action:** To upload the YAML file, click **Drag and drop an API file here or click to upload** and navigate to the **InventoryAPIs.yaml** file you downloaded earlier.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/eb1a868c-7300-4cb1-ba71-a1b156142ea1/user_cropped_screenshot_040877eac3bc420583f7972df43753c6_text_export.jpeg)

**Action:** Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/f12476fe-efe1-428c-b7fe-473ad0944af8/user_cropped_screenshot_eb7e76336a3646aba853b379e5d06d8a_text_export.jpeg)

---

## Narration — Selecting Operations to Expose

> As part of the MCP tool creation process, the operations defined in the API specification are identified and made available for conversion into MCP tools. Teams can choose exactly which operations should be exposed to AI, ensuring that only the intended business capabilities are available to assistants and agents while retaining control over sensitive or unnecessary functionality.

---

## Step 7 — Select API Operations

**Action:** Click the **expand** icon to expand the /productcatalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/faeebd1a-b5e0-4565-9a58-55247880e987/user_cropped_screenshot_ac92e137cb084df2bf036bba52adfdd5_text_export.jpeg)

**Action:** Click the **expand** icon to view the /inventories.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2af5eac0-e872-4906-9fc9-6b682a7e372a/user_cropped_screenshot_bfa462d3ea6f4528bf6c812b6a5b5fc8_text_export.jpeg)

**Action:** Select the top-level checkbox to include all the paths and methods.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/abc8d8fd-9e5e-4624-ad61-7ab48f615e20/user_cropped_screenshot_db79a5663ca348b18125d7136aea870a_text_export.jpeg)

**Action:** Click **Next**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/1545883d-ef8a-4fad-9e19-d5ff36623fa6/user_cropped_screenshot_47c0ff8d5e8d409f8795251dda36e28d_text_export.jpeg)

---

## Narration — Enhancing MCP Tools for AI

> Once the tools have been generated, you can further improve how those capabilities are presented to AI by using the **MCP Server Enhancer**.
>
> Tool names and descriptions can be refined to provide clearer instructions to AI assistants and agents. These enhancements help the AI better understand the purpose of each tool, when it should be used, and how it should be invoked.

---

## Step 8 — Enhance the Tools

**Action:** Click **Enhance tools**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/eca2757d-918e-47af-bb33-01c25093a789/user_cropped_screenshot_dc0e8b1ea54f4b3597c977f4ab8946f5_text_export.jpeg)

You can see the enhanced tool names and descriptions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/074c2d14-5ac1-4fb6-9031-cf842e3f7179/user_cropped_screenshot_95f89f3decca4894b9a994e3a9494153_text_export.jpeg)

**Action:** Click **Apply all**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/90e4b2e9-17aa-4d72-af39-6efa8dbab0aa/user_cropped_screenshot_36d212a501684532b5386546f3554535_text_export.jpeg)

**Action:** Review all the details and once you're done, click **Generate**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fbdf140c-039c-4257-9290-719cfa63a73d/user_cropped_screenshot_237b593daf134d46bb3b52539ad7493b_text_export.jpeg)

---

## Narration — Reviewing the Generated Policy Sequence

> The MCP server has now been generated, and the selected API operations have been converted into AI-ready tools.
>
> In addition to the MCP tools, a **policy sequence** has also been created. If you're familiar with API Connect, this should look familiar. The policy sequence defines what happens when the gateway receives an MCP request, just as it would for a traditional API request.
>
> The next step is to review and enrich this policy flow. These policies allow you to apply security, transformation, rate limiting, authorization, and other controls before a request reaches the backend service. Because governance is applied at the gateway layer, organizations can enforce consistent standards across AI interactions without modifying the underlying APIs or services.
>
> This is where Interact Gateway moves beyond simple tool generation and becomes a governance layer for AI interactions. The key point is that AI requests can be governed using the same policy framework organizations already use for APIs, making it easier to extend existing governance practices to AI assistants and agents.

---

## Step 9 — Review the Policy Flow

**Action:** From the Explorer pane, click the policy under MCP servers.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/25b815c2-4f92-4189-8a96-b6f92f874f90/user_cropped_screenshot_7b38430142564a139d44c558ce0fdff8_text_export.jpeg)

**Action:** By default, there is only one operation. Click the **Invoke** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2140d5d2-fbb1-40c0-8491-b6f410cd11cb/user_cropped_screenshot_7eda064cc8f743a28e0145bf24493f96_text_export.jpeg)

In the Invoke Policy pane, you can see that this existing API is hosted and managed in another environment through a webMethods API Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/79a0d25b-4d2f-431b-ae90-d578f8d75ad1/user_cropped_screenshot_63abdad58e4c458296588a958cad1369_text_export.jpeg)

---

## Step 10 — Add an API Key Policy

**Action:** Click the **plus** icon on the left of the Invoke operation to add a new operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/293b486d-e4a8-46f2-ba14-6a6026750f88/user_cropped_screenshot_d8a4277dc0a14f4c8699490f9221ef63_text_export.jpeg)

**Action:** Scroll down the assembly flow and click the **Set** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/0eee002a-88cf-4e68-961f-0ddd4c940a75/user_cropped_screenshot_abc18eb3387e42f0a02bb80b22378e65_text_export.jpeg)

Here we're supplying the required API key. The purpose here is simply to validate the API and confirm the capability is working correctly.

**Action:** In the Header name field, type **x-Gateway-APIKey**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/82d483cf-507b-4c91-b10e-f7ce15593dd8/user_cropped_screenshot_ad21e7f740ed4b2393eb36d57c975955_text_export.jpeg)

**Action:** In the Value field, type **2d6bea7d-76d5-4b3f-8c6a-9dd2d5dc7bd7**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/56120cf7-ba9c-428c-942e-d9d9158a5b8e/user_cropped_screenshot_d9099c46863e4f328bd676244e4265b3_text_export.jpeg)

**Action:** Click the **close** icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/d4939fa9-4c60-4c71-86f9-c835820ae2a7/user_cropped_screenshot_168352ea02f14b75bdaec5aa66597daa_text_export.jpeg)

---

## Step 11 — Add a Content-Type Policy

**Action:** Click the **plus** icon on the left of the Set operation to add another operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/045f9cd5-40af-4da9-adcb-b04a0e8e3cb0/user_cropped_screenshot_e8815b87ee7949d7a852892c7a24aafc_text_export.jpeg)

**Action:** Scroll down the assembly flow and click the **Set** operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/a68b94be-94fc-4883-b2cd-3e444d245634/user_cropped_screenshot_73f1902bcc714cacb87f2b39ec4224de_text_export.jpeg)

**Action:** In the Header-name field, type **Content-Type**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4f6df508-1dbf-4151-ae27-07d766e2102a/user_cropped_screenshot_8754d4120c6946f68a23711a142d21b9_text_export.jpeg)

**Action:** In the Value field, type **application/json**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2d6c2e70-31c7-461a-9d2e-cd87fb463dd1/user_cropped_screenshot_96e84e2ae0784ad08e1a4c47ad5f4bad_text_export.jpeg)

**Action:** Click the **close** icon to close the policy pane.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fab3fba2-51c6-4d76-a016-d49d3ca3e101/user_cropped_screenshot_2472f1a899ec4b4d93f620be339f7001_text_export.jpeg)

---

## Step 12 — Publish the MCP Tools

**Action:** Click **Publish** to publish the MCP tools through the Interact Gateway.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4de26a1b-7913-4efb-b51b-6ad2ae7c2d62/user_cropped_screenshot_5a8c157401b2465ca0a1b850c555f7f6_text_export.jpeg)

**Action:** From the Catalog list, select **Interact Gateway MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/65cbf8ea-c8d0-4d0f-a738-bf60a6aa57c9/user_cropped_screenshot_09c0fdb48b514a298aa2ffbd37a113f6_text_export.jpeg)

**Action:** Ensure the DataPower Nano gateway service is selected. Click **Next** to continue.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/991a56f0-223e-42a6-b22b-7b9146dfc079/user_cropped_screenshot_d628967ad9674a9f87bbb0c48a8a8fc1_text_export.jpeg)

**Action:** Expand the MCP Server to view all the associated assets and policy sequence.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/c93aa912-dcd9-4641-b7f1-25a62b727b2a/user_cropped_screenshot_f9614233414d47bf8192ac74ca61f323_text_export.jpeg)

**Action:** Click **Publish**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/115eb5df-5142-4f5b-8a77-88e1ec44cf99/user_cropped_screenshot_e06a71193909441db2652cd468ba1d1f_text_export.jpeg)

---

## Narration — Locating the MCP Endpoint

> Once the MCP tools have been published, they are exposed through a governed **MCP endpoint** that can be consumed by AI assistants, agents, and applications.
>
> We'll now navigate to the catalog to locate the published MCP endpoint.

---

## Step 13 — View the Published MCP Endpoint

**Action:** In the Publish successful notification, click **Catalog**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/2c975c2e-277e-442a-b507-0f2e16c50f26/action-4ffb9d5a4cb049ceaf666b894da04b80_b22c73c0c1f643a8b48fb38b4dcf4200_text_export.jpeg)

!!! tip
    You can also locate the MCP endpoint by navigating to **Manage > Interact Gateway MCP** catalog.

You can see all the published assets in the Interact Gateway MCP catalog. If the list is long, you can choose to filter by type.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/fb12d17b-e293-4067-b2f2-3872f8506e67/user_cropped_screenshot_6070371cf5734cefaa6c6c51c565f0ea_text_export.jpeg)

**Action:** For the newly published inventoryapis-server, click the **three dots** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/c5aeeb69-be05-42a8-8eb9-6dea5e25f970/user_cropped_screenshot_6ca61bf3dac04a85a83b631042abd63a_text_export.jpeg)

**Action:** Click **View endpoints**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/59a9dbb7-d048-4d11-bdce-8049ae97203f/user_cropped_screenshot_98736aaffaab4b458423baa88be54811_text_export.jpeg)

Here you can see the MCP endpoint that you can use with applications, assistants, or AI agents as needed. Click **Copy** to copy the endpoint.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/afa89cc2-df73-4dcb-821b-ab3bfb354fd9/user_cropped_screenshot_7702920e2e9a41c8a5e1d848adf05235_text_export.jpeg)

---

!!! warning "Important — Cleanup Required"
    After you have finished testing your MCP endpoint with an AI assistant, agent framework, or other AI application, please take a few moments to **delete the project you created** during this exercise.

    Removing unused projects helps keep the shared environment clean and available for future learners. It also prevents the accumulation of unnecessary MCP servers, policies, and published assets that are no longer needed.

    Only delete the project and assets **you created** during this exercise. Do **not** modify, delete, or republish any of the preconfigured **ZillaForge** projects, MCP servers, policies, catalogs, or other shared assets, as these are required by other learners and demo scenarios.

    **Cleanup Tasks:**

    1. Return to the project you created for this exercise.
    2. Delete the MCP assets you published.
    3. Delete the project.
    4. Verify that the project has been removed from the project list.

    ![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/904fcefb-a638-453f-80ff-39dd25763d6a/user_cropped_screenshot_569cf7f898ae49c9843b2b8302a477d4_text_export.jpeg)

---

## Wrap-up

> Rather than building new services for AI, we reused existing enterprise APIs, selected the operations to expose, applied governance policies, and published the resulting MCP tools through the Interact Gateway.
>
> By following this approach, organizations can safely make enterprise capabilities available to AI assistants and agents while maintaining the security, control, and observability required for enterprise-scale AI adoption.

---

**Previous:** [← Part 2: Explore Governed MCP Tools](mcp-tools.md) | **Next:** [Part 4 - Register and Govern LLM Providers →](llm-governance.md)
