# Overview and Architecture

!!! note "Slide Resources"
    The slides used in this section can be found <a href="https://ibm.seismic.com/Link/Content/DC633F9fdp9cC89T3QDhmmmFGqWB" target="_blank">HERE</a>.

---

## Narration 1 — The ZillaForge Challenge

> ZillaForge, a fictional global manufacturer of industrial automation equipment, is expanding its use of AI assistants and agents to improve productivity, automate decision-making, and accelerate business processes. The company has already invested heavily in APIs, integrations, workflows, and governance, creating a strong digital foundation of reusable business capabilities.
>
> As AI adoption grows, ZillaForge faces a new challenge. AI assistants and agents need access to those same enterprise capabilities, but traditional governance models were designed for applications, not autonomous AI interactions. The company needs a way to maintain visibility, security, and operational control as AI-driven activity scales across the business.
>
> To address these challenges, ZillaForge adopts IBM DataPower Interact Gateway. Acting as an AI mediation governance gateway, it helps the company govern AI interactions, expose existing enterprise capabilities to AI without rebuilding them, and apply consistent security, policy enforcement, and observability across AI-driven traffic. This demo follows ZillaForge's AI adoption journey, showing how Interact Gateway enables organizations to reuse existing APIs, integrations, and business services while bringing AI-initiated interactions under a consistent governance model.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/938d0203-4875-4a69-8b7c-f305b939f0f5/matched_image_action_24_36787e5f921b4cc793adb1c0eb0c9cad_text_export.jpeg)

---

## Narration 2 — The Digital Business Platform

> This illustration represents the architecture used in the ZillaForge demo and the digital foundation the company established before introducing AI. It shows how years of investment in APIs, application integration, events, governance, and reusable business services created a platform of enterprise capabilities that can now be safely consumed by AI assistants and agents.
>
> At the center of the architecture is the ZillaForge Digital Business Platform, governed through a Hybrid Control Plane that provides centralized visibility, management, analytics, and governance across cloud, on-premises, and edge environments. Around it are the core integration capabilities — including API management, application integration, event management, B2B integration, managed file transfer, and monitoring services — all working together as shared enterprise services.
>
> Rather than creating new capabilities for AI, ZillaForge can reuse the APIs, integrations, workflows, and business services it has already built and expose them as governed AI-ready capabilities.
>
> This architecture forms the foundation for the rest of the demo. Throughout the walkthrough, learners will see how ZillaForge extends its existing digital investments to support AI adoption while maintaining the governance, visibility, and operational control required at enterprise scale.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/1ff74f4d-8d35-4945-b6a3-9818949d4611/matched_image_action_25_d86275b958534f46a36fb7d041c017af_text_export.jpeg)

---

## Narration 3 — The Governance Gap

> ZillaForge has already begun adopting AI across different parts of the business. Teams are experimenting with AI services, connecting them to business applications, and enabling access to enterprise capabilities. In the early stages, these initiatives are often managed independently, with individual teams using their own model access, credentials, and integration approaches. While this works for small-scale experimentation, it quickly becomes difficult to manage as AI adoption expands across the organization.
>
> As more AI assistants and agents begin interacting with enterprise systems, new governance challenges emerge. Organizations need to understand who is using which models, what business capabilities are being accessed, what policies are being applied, and how AI-driven activity can be monitored and controlled. Traditional governance models were designed for applications and APIs, not autonomous AI interactions. This creates a governance gap that requires a consistent control point where security, policies, credentials, monitoring, and visibility can be applied across all AI interactions. IBM DataPower Interact Gateway is designed to address that gap.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-12/9d4f4ba8-3c1a-417e-a161-0d3bd48d3d13/matched_image_action_26_ffc9cee1186248b68cd2658139d45a24_text_export.jpeg)

---

## Narration 4 — Where Interact Gateway Fits

> IBM DataPower Interact Gateway sits between AI consumers and enterprise systems, providing a controlled interaction layer that governs and secures AI-driven interactions.
>
> Think of Interact Gateway much like an API gateway for the AI era. It doesn't build the applications, models, or agents. Instead, it governs how they interact with enterprise services. APIs provide capabilities, events provide awareness, workflows provide guardrails, and policies provide trust. Together, these elements enable organizations to scale AI interactions with the visibility, security, and control required for enterprise adoption.

![](https://colony-recorder.s3.us-west-1.amazonaws.com/files/2026-08-19/96c28c7f-bb98-4aaf-bc1d-57e753df459f/screenshot_f3d0dd339f4242c0abe884134ea0b0e4_text_export.jpeg)

---

**Next:** [Part 1 - ZillaForge AI Assistant →](ai-assistant.md)
