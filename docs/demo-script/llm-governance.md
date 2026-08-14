# LLM Governance

In this section, we explore how ZillaForge governs access to Large Language Model (LLM) providers through IBM DataPower Interact Gateway. Just as MCP tools govern AI interactions with enterprise services, Interact Gateway also governs how AI applications and agents access LLM capabilities — applying security, credential management, and policy enforcement at the gateway layer.

---

## Step 1 — Open IBM API Studio

**Action:** Click **IBM API Studio** from the navigation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/49d35161-8aa0-482c-8cb1-a33e94b32ac9/action-9c6fcca6f3c74553847fe76fa2aeb13f_01409570623240bd8e92222e0594cc47_text_export.jpeg)

---

## Step 2 — Access Instance Settings

**Action:** Click **Instance Settings**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/6077d8f2-2867-41de-8c54-230c587127a0/action-e06327e80da44429a74e75e54f52f1bb_b4fafc38bf1e48c8971c609ad7559793_text_export.jpeg)

---

## Step 3 — View Secrets

**Action:** Click **Secrets**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/77e3a0d2-6737-43d0-864f-72898aa31c9e/action-fad51b944c834fd094bbd77c2c07a5eb_c3c0ecb3a68042bdabd5bff3f8bb8653_text_export.jpeg)

---

## Step 4 — Add a Secret

**Action:** Click **Add Secret**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/8dc0cff8-6f06-4ad5-9607-6475184362d5/action-a7f3dc5abade4db4ab077dcff5ac0778_2b954e8d7b4b45588b3a672a15381da6_text_export.jpeg)

**Action:** Click the icon to configure the secret.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/7bbdf073-9176-447c-ae39-04aba4827e83/action-953ac5ac75f74a9d94398b61b95a8262_8203e1972d7d47fdb8b1c44ee22a0c3b_text_export.jpeg)

**Action:** Click **Back**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/6142d9f7-8525-4030-bb72-7bee49493008/action-d78c579a606b4165b4ba951e51af3d22_b10b65020fce497ab3c759b4cf1cac8d_text_export.jpeg)

---

## Step 5 — Open the ZFwatsonx Project

**Action:** Click **ZFwatsonx**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/df12fdc3-c574-4a98-b81a-723cf3932ab3/action-7e9e7db1ecdc4093bd99bf941b6afde9_cccbaeb215fd43b096bfc6063de41cda_text_export.jpeg)

---

## Step 6 — Review the watsonx Connection

**Action:** Click **watsonx-conn**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/8fb4ba72-c0cd-4402-98b2-3ac775c37ac2/action-8481a8a685d84c9cb71978853c7e3159_947f7538f0194ee489db644330aa3f86_text_export.jpeg)

**Action:** Review the LLM provider configuration, including the base path and selected operations to expose.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/8c9a2796-2e8d-4b36-a5fb-7a67ae7f58b0/action-0e5b437327904125b6c6146a1d312410_9486f316283d48c18bf3426537b8400e_text_export.jpeg)

---

## Step 7 — Configure Operations to Expose

**Action:** Click **Select operations to expose** and review the available operations.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/f6ad361d-8555-4258-8409-97c8632e215b/action-6eb892f879914c9fa53ce0f15971d800_fb550a7caa2b4a31889c807850104526_text_export.jpeg)

Review the full operations configuration.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/2745a133-bc3c-4cb5-b066-f70871b4d751/action-2c61e5229ee84acc821755be2ae179b2_775fa33652c3420a91ef0fd4b709707a_text_export.jpeg)

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/9b8ad9e5-4fdb-46b6-a994-f2fc8449db6f/action-1c7f0a9d1f6e4d669c10d3268bdd718e_b2d738d69e39469dbce424d70848b7f3_text_export.jpeg)

---

## Step 8 — Open the Policy Sequence

**Action:** Click **freeflowpolicysequence-watsonx-conn-t0al8**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/a001f87d-9970-498a-b6b1-6bec9168b88b/action-1b061fab3af146ed83fbd0123330de66_c3420f97e3b04b1c8bfe11498fe6d0d4_text_export.jpeg)

---

## Step 9 — Review Identity Extraction Policy

**Action:** Click **ExtractIdentity**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/fcb25051-f400-492c-80b0-cf113170214e/action-f09f09eaa28743078f150ed5e449aab1_15be6df6c7c7467b90d24cc249d48999_text_export.jpeg)

**Action:** Click the button to view the policy configuration.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/6ff594eb-47c0-4116-9b0f-dec8a9763b00/action-8e7f2c6e9e074c0b8276397b06892507_4b271051396d430fbb8400aeda0ad777_text_export.jpeg)

---

## Step 10 — Explore the Full Policy Flow

**Action:** Review the complete assembly policy flow, including the Operation Switch and route-specific policies for each LLM operation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/5abf76a2-4ca7-4dbc-bb80-9d4ebe29b082/action-8f2d78db0eb34021ac762212a109ab89_33c443d066024d72a0b653b2a6426588_text_export.jpeg)

Review additional policy nodes in the flow.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-14/e99a81a5-5175-4454-a9e3-bb3dae75d8e4/action-7b368b02ebfa4aa9806d70d357a9d7f5_a2b8edbacb384db99642bc302b4ac4d9_text_export.jpeg)

---

**Previous:** [← Part 2: Generating MCP Tools](mcp-tools.md) | **Next:** [Analytics →](analytics.md)
