# Part 6: Monitor and Optimize AI Interactions with Analytics

Throughout this demo, we've seen how ZillaForge governs AI interactions, publishes AI-ready capabilities, and manages access to LLM providers. The final step is **visibility**.

As AI adoption grows, organizations need to understand how AI assistants, agents, MCP tools, and LLMs are being used across the enterprise. IBM DataPower Interact Gateway provides analytics and observability that help teams monitor usage, investigate individual transactions, identify performance issues, and understand adoption trends.

These insights help ZillaForge not only govern AI interactions, but also continuously optimize and improve them as usage scales across the business.

---

## Step 1 — Open the Analytics View

**Action:** Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b40bdd3-98a5-488a-8de0-84d73e99da17/user_cropped_screenshot_507380de945b45d1af2893120847db16_text_export.jpeg)

We'll focus on the analytics for the Inventory MCP server. Scroll to the right to view the analytics options.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/274031ac-60ef-40e3-bd6f-e87737e26603/user_cropped_screenshot_51b4da1efd6342b1a2b48986faf1f649_text_export.jpeg)

**Action:** For the **inventoryapis-server-ow85v** server, click the **analytics** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/b846290f-9c06-4976-b4c4-4dc235e07e32/user_cropped_screenshot_4952b65ac13a4839a21d26a7472029d3_text_export.jpeg)

---

## Narration — The Discover View

> This is the **Discover** view, which provides a real-time view of MCP and AI interaction activity.
>
> Here you can see interaction volume over time and a list of individual transactions, including status, method, response time, and other operational details. This allows ZillaForge teams to quickly identify activity patterns and drill into specific interactions for further investigation.

---

## Step 2 — Drill Into a Transaction

**Action:** Click a transaction to drill down and view more details.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/92134ee7-09db-4509-af3b-4b94794ef233/user_cropped_screenshot_890b4b67b9f046268741deed2ca22044_text_export.jpeg)

---

## Step 3 — Explore Latency Analysis

**Action:** Click **Latency analysis**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/3583deaf-bbad-47e8-ae8c-ecc09a4f3a67/user_cropped_screenshot_8e0f94b0f24e4c0da57e000a291526aa_text_export.jpeg)

**Action:** Review the AI insights panel.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/d8d7daf9-4391-442c-9844-c8d61f7d5719/action-3e9f534384834722ba2ba19cef457930_ddc83ed2ab384f8685d180a2b8c26465_text_export.jpeg)

**Action:** Review the event detail fields.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/aed91671-7438-4ef3-aa53-ed90e0238de4/action-0e6469bcc97549ec88a69ba9e6dd2dc8_e96e7d0f814449789ba5c000ebcdff2d_text_export.jpeg)

---

## Step 4 — Review Backend and Consumer Request Details

**Action:** Click **Backend request and response**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5c9acc2f-a0a5-4a94-9308-9e6ba2b6b083/action-97c5e664ff6b4747a1488eb1c8e85d4a_0a936fd27c1548298189d14a90143ac7_text_export.jpeg)

**Action:** Click **Consumer request**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/f2fd9572-1e60-4bc7-9920-893c2921bd10/action-29d0c2cd2d644b4eb1283d23ed725182_a2d5681c304943ccacf0bb5ec32d5e65_text_export.jpeg)

**Action:** Click **Policy flow latencies**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/28ace2b7-b5b4-4f05-9758-ec8245cb2276/action-3cdaea003f614cd193b340896e2591b4_fe4847213ed54b209476da1f274a0f4a_text_export.jpeg)

**Action:** Review the API policy flow latencies diagram.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/e80b6dbc-d714-4bc5-bc2d-49146f59120f/user_cropped_screenshot_6a1be765f0524fe3a92bfb4b09de7edb_text_export.jpeg)

---

## Step 5 — View Event Record

**Action:** Click **Event record**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/47595183-c63a-43e6-949f-3ab9f803613a/action-a81406c4f22c46f89c4f6871bc566360_e79fd5fbfc2a43ebb0096741fbe6c484_text_export.jpeg)

**Action:** Click the datetime stamp to view raw event details.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/b2067e67-d609-4d21-a279-53ed874dedfa/action-f4ebde646bc340449c63904627fbb64e_b0930ce813df41ee94fbb1a2986dcfa5_text_export.jpeg)

---

## Step 6 — Explore the AI Platform Report

**Action:** Click **Analytics side navigation**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/63472ab1-17cc-4558-acd0-2daf168870ea/action-77530ee5377c4ee89dc160d05002fd74_d5a8c72ff927410881bdcde5d5c866cb_text_export.jpeg)

**Action:** Click **AI Platform report**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/475b94a1-ef0c-49ef-a6c9-4b580795ad9c/user_cropped_screenshot_bcac79fda45d4fa081f26a30caea4ab1_text_export.jpeg)

**Action:** Review the AI Platform report overview.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/2a505bc2-3cb3-46fa-86fb-912b324851bf/action-bdbb524d90494e81a33a4c68306180ec_a77e3dd9cbad44b3b5fa36f0e56d6806_text_export.jpeg)

**Action:** Click **Show detailed analysis**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/4a534673-8399-4a34-a912-3c68e9f58d86/action-6074c5144f1f48a0b1db3e88e0583925_24af8b79e8bb46aab99e454caab57eb4_text_export.jpeg)

Review the recommendations, including provider concentration alerts and optimization suggestions.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5a682e7e-2f94-4a52-89fa-374e2bbecd1b/action-2f0b451e44ba4df6afdf82016061b4f0_928fdae0e93c46ffbbca2cbd1f00b670_text_export.jpeg)

**Action:** Review the full AI Platform report with long-term trend data.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/6de6d948-63c7-4b2e-89d2-4a279c9b9072/action-3ad02322cc824df2bb2b44c6be635213_2ff7a07707544cd980802691c01fad7f_text_export.jpeg)

---

## Step 7 — View the Consumption Report

**Action:** Click **Consumption report**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/fa22da95-3588-4cf9-90a4-335f9edd3c89/action-f2ea63c8b3764451a2192356f40ba905_13636ccd5a9b48a79d16352f05a29d1b_text_export.jpeg)

Review the long-term trend data for API calls processed by the gateways at this scope.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/deabec29-d225-401e-ab33-7e5acdef0cc8/action-158d17c6efd444078eb065994c467f2e_98bb818fd46a4c80afefc6c9d70cd7d4_text_export.jpeg)

---

## Step 8 — Review MCP Usage Analytics

**Action:** Click **Analytics side navigation**, then click **MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/668e6ffd-3835-4fa3-b9df-1b83dc8bc107/action-f0dcc062f7b24e04a770cfc81f084f55_c87032aff83143f9945387b67207271e_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/3328f750-830e-4f0b-8924-bee615cd9a69/user_cropped_screenshot_204eb8d1b38e4e44b5fc5d87c2d8f342_text_export.jpeg)

Review the MCP usage report — see who is using your AI MCP services the most, track tool and prompt counts and usage patterns.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/596e39fa-2300-48f5-98ea-e034d7ff60fc/action-c7ad140e05e24d91806f2eb14864a1d0_581e950bd21142d2ac9f57c777c94248_text_export.jpeg)

**Action:** Scroll through the MCP usage details.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/698a3dfa-59a9-4a5e-a84e-50003a92fade/action-458fa04b8b334d0dbdd088b51af63576_53fc7415aa3b44b989963f95a58af6f4_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/77392631-4c3a-4021-b134-888a8f52c296/action-cbfcb3c21fee4596bdb1de3656dc7404_92029f58b1b94be891c374e8daf9762b_text_export.jpeg)

---

## Step 9 — Review AI LLM Usage Analytics

**Action:** Click **AI LLM**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/02ed45af-c810-4db4-b136-9d0d0c878ad5/action-df7a0e4b13d046eb912bb923b5536e28_2da98cf5e4364eac978114b7a91fd2c4_text_export.jpeg)

Review the AI LLM usage overview — see who is using your AI LLM services the most, track token counts and LLM model usage.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/d79e9a10-dbe4-47ca-bd26-5237c1cb19aa/action-dcdbddf40e2b405f94b11791d3f6fa8a_1aa1199252af4e45a31e4d65694fd954_text_export.jpeg)

**Action:** Click **Detailed usage**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/04bb03ed-6603-4a20-8644-59f216892ccb/action-2f7aabbed5224ea8aea2307cdcdbfbb1_c7c1132199d94928a06bfb9a459f1696_text_export.jpeg)

Review token consumption trends over time.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5e0e738c-bd09-4069-9865-a3339ae1c300/action-4f9160e903f24bfcb6ce858accafce5d_ab5cf183b2f04b7eb59aa0efc231c5b0_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/13eea699-bdef-4927-9107-cc81fcfe43ca/action-f8fa1140b8b9481882eeb7d28ac3b62a_754a006d94634eb0996f89ee9e0d545b_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/a8563aa8-9f8e-4cef-9b4c-90f130179f84/action-f2458a394dc74c7f9207622491c7585a_ff2c93aaa2f9438e806f9e20612fb75b_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/eb23b8ff-ad99-46b0-b1c5-1062b2bf2d0d/action-decddde8c36044699727df7454faf93e_6f4fe0033eba42db8ab16cc9c4f481ca_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5a72300f-8780-401e-960f-e8848f4f8e5c/action-fde414e0376d4aa9b6ed1e92081db780_34ebf3bb3ae14abcb13ebe17eee47ef8_text_export.jpeg)

---

## Step 10 — Review Gateway Operations

**Action:** Click **Gateway**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/04027263-2a88-4e3c-a7d0-345a649931be/action-a479237b59264ff0a8b3375fdc03f4ef_229101b8a73a45f1bd64ce49083675a6_text_export.jpeg)

**Action:** Click the gateway operations link.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/42279635-4225-44b7-adf0-0a3d0795619c/action-4e155fe8bde6464ab354945d00459a69_b9911db29ff34bf68cd4286ee282a79d_text_export.jpeg)

Review the **Gateway operations** report — call volume and latency information for each gateway in each gateway service. This view can be used to determine if load is being distributed effectively across gateway instances.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/449ffcee-c1d2-43e9-947b-820733c46325/action-f49783411b8b4b0b93f677f817d742f4_858185df1e3c42c4b48da5fa41cf1d44_text_export.jpeg)

**Action:** Click **Analytics side navigation** to return to the main analytics view.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/25539567-82a3-407f-afdb-e0db16a6fe20/action-14e68e11228447b395a2293a19a669a0_be841e3366614882a1c64a876c284551_text_export.jpeg)

---

**Previous:** [← Part 5: Developer Portal](developer-portal.md)
