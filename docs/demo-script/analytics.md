# Part 6: Monitor and Optimize AI Interactions with Analytics

Throughout this demo, we've seen how ZillaForge governs AI interactions, publishes AI-ready capabilities, and manages access to LLM providers. The final step is visibility.

As AI adoption grows, organizations need to understand how AI assistants, agents, MCP tools, and LLMs are being used across the enterprise. Interact Gateway provides analytics and observability that help teams monitor usage, investigate individual transactions, identify performance issues, and understand adoption trends.

These insights help ZillaForge not only govern AI interactions, but also continuously optimize and improve them as usage scales across the business.

---

## Step 1 — Navigate to the Interact Gateway MCP Catalog

**Action:** Back in API Connect, click the **Manage** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/c513e7e9-cf4f-4c1a-a6b0-2b3caeb43b4e/user_cropped_screenshot_b1e02058235e4b23bba1dcc8c7bef46a_text_export.jpeg)

**Action:** Click the **Interact Gateway MCP** catalog.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/4b40bdd3-98a5-488a-8de0-84d73e99da17/user_cropped_screenshot_966af909c8f940e4bb86d8543d44a493_text_export.jpeg)

---

## Step 2 — Open Analytics for the Inventory MCP Server

**Action:** Let's view the analytics for the Inventory MCP server. For the inventoryapis-server-ow85v server, click the **Analytics** icon.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/52cd1109-aeb2-42c3-8ace-7f69a24f6007/user_cropped_screenshot_3dd42e098d674643afeeae288398b818_text_export.jpeg)

---

## Narration — The Discover View

> This is the **Discover** view, which provides a real-time view of MCP and AI interaction activity.
>
> Here you can see interaction volume over time and a list of individual transactions, including status, method, response time, and other operational details. This allows ZillaForge teams to quickly identify activity patterns and drill into specific interactions for further investigation.

---

## Step 3 — Drill Into a Transaction

**Action:** Click a transaction to drill down and view more details.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-17/92134ee7-09db-4509-af3b-4b94794ef233/user_cropped_screenshot_2208422cee304f0b97c4c590ecdcadf8_text_export.jpeg)

---

## Narration — AI-Powered Insights

> Here we're looking at AI-Powered insights.
>
> Rather than teams manually inspecting logs and tracing requests through the gateway, ZillaForge can use AI-generated summaries to quickly understand what happened during an interaction. The analysis automatically highlights key information such as request status, latency, policy execution, client details, and potential bottlenecks.

---

## Step 4 — Review Backend Request and Response

**Action:** Click the **Backend request and response** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/defe04dd-0fea-4dd8-a950-792be0f784fa/user_cropped_screenshot_bc21993f74f647feb8834f8bea7816f5_text_export.jpeg)

---

## Narration — End-to-End Interaction View

> This section provides ZillaForge with an end-to-end view of what happened during the interaction, including the incoming consumer request, the request sent to the backend service, the backend response, and the final response returned to the consumer.

---

## Step 5 — Review Policy Flow Latencies

**Action:** Click the **Policy flow latencies** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/59ee5977-e9db-4d30-b5ab-21c4710e61b6/user_cropped_screenshot_e88418a921ca407ba2a577bab4aa318a_text_export.jpeg)

---

## Narration — Latency Breakdown

> This view shows the policy flow latency breakdown for a specific request, helping ZillaForge identify exactly where time was spent as the interaction moved through the gateway and pinpoint potential bottlenecks in the AI, MCP, or API processing pipeline.

---

## Step 6 — Review the Event Record

**Action:** Click the **Event record** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/57bd636f-e3b0-4f3c-92d3-6a4f94fd81aa/user_cropped_screenshot_8d6b6a59eac4417687b7d760671db861_text_export.jpeg)

---

## Narration — Raw Event Record

> This view shows the raw event record for the transaction, giving ZillaForge complete access to the underlying request, response, consumer, gateway, and operational metadata that was captured during the interaction for auditing, troubleshooting, and compliance purposes.

---

## Step 7 — Scroll the Event Record

**Action:** Scroll down to view the complete record.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/6dc26ed3-063e-4749-95f3-220d0a79914a/screenshot_5af67a47a4ed4d6caa50a9ebcc10525c_text_export.jpeg)

---

## Narration — Moving to Reports

> Next, we'll move to reports.
>
> The Reports section helps ZillaForge move beyond individual transactions and understand broader usage trends across the platform.
>
> Using these built-in reports, ZillaForge can monitor AI, MCP, and API adoption over time, identify the most active consumers and applications, track consumption patterns, analyze call volumes, and understand how enterprise capabilities are being used across the organization. These insights help platform teams make informed decisions around capacity planning, governance, optimization, and future AI investments.

---

## Step 8 — Open the Reports Section

**Action:** In the Analytics side navigation, click **Reports** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/375799bb-7437-46e0-a188-269c649a9164/user_cropped_screenshot_3e465f7a1abd4991933ee8a520a05e1d_text_export.jpeg)

---

## Step 9 — Review the AI Platform Report

**Action:** Click **AI Platform report**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/eba8fe89-f735-48f6-9c47-6076b9552deb/user_cropped_screenshot_b232671ce8194e498990f2a9c74f2cde_text_export.jpeg)

---

## Narration — AI Platform Report

> The AI Platform Report gives ZillaForge a high-level view of how AI capabilities are being used across the organization.
>
> This report summarizes overall platform usage, including total AI calls, provider adoption, consumer activity, success rates, and response time trends. The built-in AI Insights & Analysis feature automatically highlights key observations and recommendations, helping teams quickly identify usage patterns, provider concentration, performance trends, and potential areas for optimization.

---

## Step 10 — View Detailed AI Insights

**Action:** On the AI Insights & analysis section of the report, click **Show detailed analysis**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/1f8a5d3d-3095-4c93-bbb2-ad12d6c856a0/user_cropped_screenshot_edccfd4038a94858969ac4f97d5dd0ec_text_export.jpeg)

Review Key Insights and recommendations. Scroll down to view other sections of the report.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/bdc886dd-c2d8-4703-89da-43394a744d3e/user_cropped_screenshot_8e85054a0955421c802d1781c5534532_text_export.jpeg)

---

## Step 11 — Review the Consumption Report

**Action:** When you're done reviewing the report, click **Consumption report**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/ddb82e61-e99b-4a5d-b83a-8eb789142cff/user_cropped_screenshot_6cbbdf2a0284484d8aca909473c561ae_text_export.jpeg)

---

## Narration — Consumption Report

> The Consumption Report helps ZillaForge understand overall platform usage and consumption trends across its AI, MCP, and API assets.
>
> By tracking call volumes and response status codes over time, ZillaForge can monitor platform adoption, identify growth patterns, and quickly spot increases in errors or unusual activity.

---

## Step 12 — Scroll the Consumption Report

**Action:** Scroll down to review all the sections of the report.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/d04863c5-735c-43a2-af22-f2b0b60f550f/user_cropped_screenshot_dcb450692bec4677a635a5fba13fe43c_text_export.jpeg)

---

## Narration — Moving to Dashboards

> Next, let's review some dashboards.
>
> Dashboards give ZillaForge a real-time operational view of its AI, MCP, and API ecosystem through a collection of role-based dashboards.
>
> Unlike reports, which focus on historical trends and analysis, dashboards provide quick access to key metrics such as usage, consumers, applications, MCP activity, LLM usage, status codes, response times, and consumption patterns.
>
> For ZillaForge, these dashboards provide a centralized view of enterprise AI adoption, helping teams make faster operational decisions and maintain visibility as AI usage continues to grow.

---

## Step 13 — Open the Dashboards Section

**Action:** In the Analytics side navigation, click **Dashboards** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/84d79fef-f07e-4070-a0c2-4d9cc756d07d/user_cropped_screenshot_a4cf6fb61b644b3d8c5d51c009f9848d_text_export.jpeg)

---

## Step 14 — Review the MCP Dashboard

**Action:** Click **MCP**.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/64237f71-ff5e-4cd1-a409-5d2d1b48c17d/user_cropped_screenshot_68e53bf182b741f1a99532b9d5b19237_text_export.jpeg)

---

## Narration — MCP Dashboard

> The MCP Dashboard gives ZillaForge visibility into how AI assistants, agents, and applications are using MCP-based capabilities across the organization.
>
> From a single view, teams can track total MCP requests, monitor MCP server adoption, identify the most frequently used tools, and understand which MCP servers are generating the most activity. The usage trends and call patterns help ZillaForge understand which enterprise capabilities are delivering the most value and where demand is growing.

---

## Step 15 — Scroll the MCP Dashboard

**Action:** Scroll down to review various sections of the dashboard.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/14c339ed-1424-4505-a5a0-3e6c6c4b7adb/user_cropped_screenshot_0097575916fc44e39dafe68134b53d02_text_export.jpeg)

---

## Step 16 — Review the AI LLM Dashboard

**Action:** When you're done, click the **AI LLM** dashboard from the side navigation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/f89718a3-b839-4383-a199-ed0a4b2eacd1/user_cropped_screenshot_dd0cfac49314444388975a084b6d839e_text_export.jpeg)

---

## Narration — AI LLM Dashboard

> The AI LLM Dashboard gives ZillaForge visibility into how foundation models are being used across the organization.
>
> From a single dashboard, teams can track total LLM requests, token consumption, model utilization, response times, and usage patterns across consumers and applications. ZillaForge can see which applications are generating the most traffic, which consumers are using the most tokens, and which models are being used most frequently.
>
> These insights are especially valuable for governance and cost management.

---

## Step 17 — Review Detailed LLM Usage

**Action:** Review sections of the Overview tab. When you're done, click the **Detailed usage** tab.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/9acfff80-584b-4d73-9012-56d7d7dd6fb2/user_cropped_screenshot_ec4e735b153442fb98f09ec74a75741e_text_export.jpeg)

**Action:** Scroll down to review various sections describing detailed usage.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/584d10db-03fa-41b8-ba07-6097d788968e/user_cropped_screenshot_fa3ae5c6305445cf9c55dcd88985912b_text_export.jpeg)

---

## Step 18 — Review the Gateway Dashboard

**Action:** When you're done, click the **Gateway** dashboard from the left navigation.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/64134873-191c-457b-9fc8-d1d8902e85a5/user_cropped_screenshot_865b0e4db9454166b4c4c954b91d0458_text_export.jpeg)

---

## Narration — Gateway Dashboard

> The Gateway Dashboard gives ZillaForge visibility into the health and performance of the gateway infrastructure that powers its AI, MCP, and API interactions.
>
> From this dashboard, operations teams can monitor request volumes and latency for individual gateway instances and services. This helps ZillaForge determine whether traffic is being distributed evenly across the environment, identify underperforming gateways, and quickly spot potential performance bottlenecks.
>
> By tracking gateway utilization and response times over time, ZillaForge can make informed scaling decisions, troubleshoot infrastructure issues faster, and ensure that AI and API workloads continue to perform reliably as adoption grows across the enterprise.

---

## Step 19 — Explore the Gateway Dashboard

**Action:** Click the gateway **Service** to expand it.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/368586d6-23a2-4fd6-b448-5512bd4141f4/user_cropped_screenshot_f8d1e203c82c43ca91c38d4ba5d5937c_text_export.jpeg)

**Action:** Scroll down to review various sections of the dashboard.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/cbd5408a-0e48-47f5-a68b-c817bb5df403/user_cropped_screenshot_2e449a4c98cd4e0985880a010ba9bbb4_text_export.jpeg)

---

## Part 6 Summary

We've seen how ZillaForge uses analytics to gain visibility into AI, MCP, and API interactions across the organization.

For ZillaForge, analytics completes the governance story. It's not enough to expose and secure AI capabilities. Organizations also need the visibility to monitor usage, optimize performance, identify issues, and make informed decisions as AI adoption continues to scale across the enterprise.

---

**Previous:** [← Part 5: Discover and Consume AI Assets Through the Developer Portal](developer-portal.md) | **Next:** [Conclusion →](conclusion.md)
