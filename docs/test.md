---
layout: Conceptual
title: What is Microsoft Foundry? - Microsoft Foundry | Microsoft Learn
canonicalUrl: https://learn.microsoft.com/en-us/azure/foundry/what-is-foundry
breadcrumb_path: ../breadcrumb/azure-ai/toc.json
feedback_help_link_url: https://learn.microsoft.com/answers/tags/133/azure
feedback_help_link_type: get-help-at-qna
feedback_product_url: https://feedback.azure.com/d365community/forum/79b1327d-d925-ec11-b6e6-000d3a4f06a4
feedback_system: Standard
permissioned-type: public
recommendations: true
recommendation_types:
- Training
- Certification
uhfHeaderId: azure-ai-foundry
ms.suite: office
learn_banner_products:
- azure
ms.collection: ce-skilling-ai-copilot
ms.update-cycle: 90-days
ms.service: microsoft-foundry
description: Microsoft Foundry is a trusted platform that empowers developers to drive innovation and shape the future with AI in a safe, secure, and responsible way.
author: sdgilley
ms.author: sgilley
ms.reviewer: sgilley
ms.date: 2026-04-29T00:00:00.0000000Z
ms.subservice: foundry-platform
ms.topic: overview
ai-usage: ai-assisted
ms.custom:
- classic-and-new
- ignite-2023
- build-2024
- ignite-2024
- build-aifnd
- build-2025
- doc-kit-assisted
keywords:
- Foundry Tools
- cognitive
locale: en-us
document_id: 504e66a8-e6fe-bcc0-eff8-821aa73274b7
document_version_independent_id: bf9ba33d-9e34-cff5-001f-a64e5352a4d4
updated_at: 2026-05-27T22:15:00.0000000Z
original_content_git_url: https://github.com/MicrosoftDocs/azure-ai-docs-pr/blob/live/articles/foundry/what-is-foundry.md
gitcommit: https://github.com/MicrosoftDocs/azure-ai-docs-pr/blob/7325c679e5cda2f11f588622dab680e36a5c6455/articles/foundry/what-is-foundry.md
git_commit_id: 7325c679e5cda2f11f588622dab680e36a5c6455
site_name: Docs
depot_name: Learn.azure-ai
page_type: conceptual
toc_rel: toc.json
word_count: 1282
asset_id: foundry/what-is-foundry
moniker_range_name: 
monikers: []
item_type: Content
source_path: articles/foundry/what-is-foundry.md
cmProducts:
- https://microsoft-devrel.poolparty.biz/DevRelOfferingOntology/de19c5b8-e208-412e-9238-db3f631dea5b
- https://authoring-docs-microsoft.poolparty.biz/devrel/68ec7f3a-2bc6-459f-b959-19beb729907d
- https://microsoft-devrel.poolparty.biz/DevRelOfferingOntology/8a6e4dad-7050-4ce7-83f9-eb4123577a54
spProducts:
- https://microsoft-devrel.poolparty.biz/DevRelOfferingOntology/ea7bf5d6-7154-4ba9-8ebc-59117ccacd49
- https://authoring-docs-microsoft.poolparty.biz/devrel/90370425-aca4-4a39-9533-d52e5e002a5d
- https://microsoft-devrel.poolparty.biz/DevRelOfferingOntology/0a5fc323-00ce-4c20-9095-41948f54c83f
platformId: 86a0ca32-4cb3-f371-346b-152088b9f825
---

# What is Microsoft Foundry? - Microsoft Foundry | Microsoft Learn

**Microsoft Foundry** is a unified Azure platform-as-a-service offering for enterprise AI operations, model builders, and application development. This foundation combines production-grade infrastructure with friendly interfaces, enabling developers to focus on building applications rather than managing infrastructure.

Microsoft Foundry unifies agents, models, and tools under a single management grouping with built-in enterprise-readiness capabilities including tracing, monitoring, evaluations, and customizable enterprise setup configurations. The platform provides streamlined management through unified role-based access control (RBAC), networking, and policies under one Azure resource provider namespace.

Tip

- Coming from Azure OpenAI? [Upgrade your Azure OpenAI resource to a Foundry resource](how-to/upgrade-azure-openai) while preserving your endpoint, API keys, and existing state.
- Using hub-based projects? Hub-based projects are accessible in the [Foundry (classic) portal](../foundry-classic/what-is-foundry). New investments are focused on Foundry projects in the new portal.

## Evolution of Foundry

Foundry consolidates several previous Azure AI services and tools into a unified platform. The following table maps previous concepts to their current equivalents. For detailed guidance on transitioning, see [Navigate from classic to the new experience](how-to/navigate-from-classic).

| Dimension | Previous | Current |
| --- | --- | --- |
| Brand | Azure AI Studio / Azure AI Foundry | Microsoft Foundry |
| Brand | Azure AI Services | Foundry Tools |
| Portal | [Foundry (classic)](/en-us/azure/foundry-classic/) | [Foundry](/en-us/azure/foundry) |
| Agent API | Assistants API (Agents v0.5/v1) | Responses API (Agents v2) |
| API versioning | Monthly `api-version` params | v1 stable routes (`/openai/v1/`) |
| Resource model | Hub + Azure OpenAI + Azure AI Services | Foundry resource (single, with projects) |
| SDKs & endpoints | Multiple packages (`azure-ai-inference`, `azure-ai-generative`, `azure-ai-ml`, `AzureOpenAI()`) against 5+ endpoints | Unified project client (`azure-ai-projects` 2.x) + `OpenAI()` against one project endpoint. |
| Terminology | Threads, Messages, Runs, Assistants | Conversations, Items, Responses, Agent Versions |

## Your first API call

**Get started now** — [Quickstart: Build with models and agents](quickstarts/get-started-code) | [Open Foundry portal](https://ai.azure.com) | [Get an Azure account](https://azure.microsoft.com/pricing/purchase-options/azure-account)

Send a prompt and get a response from a model in a few lines of code:

# [Python](#tab/python)
```python
from azure.identity import DefaultAzureCredential
from azure.ai.projects import AIProjectClient

# Format: "https://resource_name.ai.azure.com/api/projects/project_name"
PROJECT_ENDPOINT = "your_project_endpoint"

# Create project and openai clients to call Foundry API
project = AIProjectClient(
    endpoint=PROJECT_ENDPOINT,
    credential=DefaultAzureCredential(),
)
openai = project.get_openai_client()

# Run a responses API call
response = openai.responses.create(
    model="gpt-5-mini",
    input="What is the size of France in square miles?",
)
print(f"Response output: {response.output_text}")
```

# [C#](#tab/csharp)
```csharp
using Azure.Identity;
using Azure.AI.Projects;
using Azure.AI.Extensions.OpenAI;
using OpenAI.Responses;

#pragma warning disable OPENAI001

// Format: "https://resource_name.ai.azure.com/api/projects/project_name"
var ProjectEndpoint = "your_project_endpoint";

// Create project client to call Foundry API
AIProjectClient projectClient = new(
    endpoint: new Uri(ProjectEndpoint),
    tokenProvider: new DefaultAzureCredential());

// Run a responses API call
ProjectResponsesClient responseClient = projectClient.ProjectOpenAIClient.GetProjectResponsesClientForModel("gpt-5-mini"); 
ResponseResult response = await responseClient.CreateResponseAsync(
    "What is the size of France in square miles?");
Console.WriteLine(response.GetOutputText());
```

# [TypeScript](#tab/typescript)
```typescript
import { DefaultAzureCredential } from "@azure/identity";
import { AIProjectClient } from "@azure/ai-projects";

// Format: "https://resource_name.ai.azure.com/api/projects/project_name"
const PROJECT_ENDPOINT = "your_project_endpoint";

async function main(): Promise<void> {
    // Create project and openai clients to call Foundry API
    const project = new AIProjectClient(PROJECT_ENDPOINT, new DefaultAzureCredential());
    const openai = project.getOpenAIClient();

    // Run a responses API call
    const response = await openai.responses.create({
        model: "gpt-5-mini",
        input: "What is the size of France in square miles?",
    });
    console.log(`Response output: ${response.output_text}`);
}

main().catch(console.error);
```

# [REST API](#tab/rest)
Replace `YOUR-FOUNDRY-RESOURCE-NAME` with your values:

```console
curl -X POST https://YOUR-FOUNDRY-RESOURCE-NAME.services.ai.azure.com/api/projects/YOUR-PROJECT-NAME/openai/v1/responses \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $AZURE_AI_AUTH_TOKEN" \
-d '{
        "model": "gpt-5.1-mini",
        "input": "What is the size of France in square miles?"
}'
```

---

For the full walkthrough, see the [Microsoft Foundry quickstart](quickstarts/get-started-code).

## Available models

Foundry gives you access to over 1,900 models from Microsoft, OpenAI, Anthropic, Mistral, xAI, Meta, DeepSeek, Hugging Face, and more. The following table highlights popular model families to help you choose a starting point.

| Model family | Best for |
| --- | --- |
| **GPT-5** | Most capable — complex reasoning, multi-step tasks, and multimodal scenarios |
| **GPT-4.1** | Best balance of capability and cost for production workloads |
| **GPT-4.1 mini** | Fastest — low-latency, high-throughput scenarios |
| **Claude** | Advanced reasoning, code generation, and multimodal tasks |
| **Grok** | Reasoning, coding, and data extraction |
| **Mistral** | Code generation, multilingual, and general-purpose chat |
| **DeepSeek-R1** | Open-weight reasoning at scale |
| **Phi-4** | Small language model — on-device or resource-constrained environments |
| **Meta Llama** | Open models — customization and fine-tuning |

For help choosing between models, see the [GPT-5 vs GPT-4.1 model choice guide](foundry-models/how-to/model-choice-guide). Browse the full catalog in the [Foundry Models overview](concepts/foundry-models-overview).

## What's new

Foundry is evolving fast. Here are some of the latest additions:

- [Prompt Optimizer (preview)](observability/how-to/prompt-optimizer) — Automatically improve agent prompts based on evaluation results.
- [Task Adherence guardrails (preview)](guardrails/task-adherence) — Keep agentic workflows on track with built-in adherence controls.
- [LangChain and LangGraph integration](how-to/develop/langchain) — Build and trace agents with popular open-source frameworks.
- [Fireworks model import (preview)](how-to/fireworks/enable-fireworks-models) — Bring custom models into Foundry through Fireworks.

See [What's new in Microsoft Foundry](whats-new-foundry) for the full list.

## Choose your path

Foundry supports multiple developer surfaces. Use the following table to find the right starting point for your scenario.

| I want to... | Start here |
| --- | --- |
| Call a model from code | [Quickstart: Your first API call](quickstarts/get-started-code) |
| Build an agent with tools and memory | [Agent Service overview](agents/concepts/workflow) |
| Explore models in the browser | [Foundry portal playgrounds](concepts/concept-playgrounds) |
| Deploy and manage models at scale | [Foundry Models overview](concepts/foundry-models-overview) |
| Develop in VS Code | [Foundry for VS Code](how-to/develop/get-started-projects-vs-code) |
| Set up governance and security | [Foundry Control Plane](control-plane/overview) |

## Who is Foundry for?

Microsoft Foundry serves three primary audiences:

- **Application developers** building AI-powered products with agents, models, and tools. Start with the [quickstart](quickstarts/get-started-code).
- **ML engineers and data scientists** who [fine-tune models](openai/concepts/fine-tuning-considerations), [run evaluations](observability/concepts/trace-agent-concept), and [manage model deployments](foundry-models/how-to/monitor-models).
- **IT administrators and platform engineers** who govern AI resources, enforce policies, and manage access across teams. See [security](concepts/architecture#security-driven-separation-of-concerns) and governance and [Foundry Control Plane](control-plane/overview).

## Key capabilities

### Build agents

**[Multi-agent orchestration](agents/concepts/workflow)** — Build collaborative agent behavior and complex workflow execution using SDKs for C# and Python.

**[Tool catalog](agents/concepts/tool-catalog)** — Connect over 1,400 tools through public and private catalogs.

**[Memory](agents/concepts/what-is-memory)** — Retain and recall contextual information across interactions without requiring repeated input.

**[Foundry IQ knowledge integration](agents/concepts/what-is-foundry-iq)** — Ground agent responses in enterprise or web content with citation-backed answers.

**[Publishing](agents/how-to/publish-copilot)** — Publish agents to Microsoft 365, Teams, BizChat, or containerized deployments.

### Operate and govern

**[Real-time observability](observability/how-to/how-to-monitor-agents-dashboard#set-up-continuous-evaluation)** — Monitor performance and governance with built-in metrics and model tracking.

**Centralized AI asset management** — Manage all agents, models, and tools from the **Operate** section, including agents registered from other clouds.

**Enterprise controls** — Full authentication support for MCP and A2A, AI gateway integration, and Azure Policy integration.

## Microsoft Foundry API and SDKs

The [Microsoft Foundry API](/en-us/rest/api/aifoundry/) provides a consistent contract for building agentic applications across different model providers. [SDK client libraries](how-to/develop/sdk-overview) are available for:

- Python
- C#
- JavaScript/TypeScript (preview)
- Java (preview)

The [Microsoft Foundry for VS Code Extension](how-to/develop/get-started-projects-vs-code) helps you explore models and develop agents directly in your development environment.

## Foundry portal

The [Microsoft Foundry portal](https://ai.azure.com) is where you manage projects, deploy models, build agents, and monitor your AI assets. To use the current version, make sure the **New Foundry** toggle in the banner is set to on.

![](media/version-banner/new-foundry.png)

Tip

See [Find features in the Foundry portal](how-to/navigate-from-classic) if you're used to the Foundry (classic) portal and not sure where to find things now.

For details on switching between projects or finding resources created in Foundry (classic), see [Find features in the Foundry portal](how-to/navigate-from-classic).

## Pricing and billing

The platform is free to use and explore. Pricing occurs at the deployment level. Each product within Foundry (models, agents, tools) has its own billing model and price.

Using Foundry also incurs costs associated with the underlying services. To learn more, read [Plan and manage costs for Foundry Tools](concepts/manage-costs).

Use the [Total Economic Impact calculator for Foundry](https://aka.ms/Foundry-ROI-Calculator) to estimate your return on investment.

## Region availability

Foundry is available in most regions where Foundry Tools are available. For more information, see [region support for Microsoft Foundry](reference/region-support).

## How to get access

You need an [Azure account](https://azure.microsoft.com/pricing/purchase-options/azure-account?cid=msft_learn). Then sign in to [Microsoft Foundry](https://ai.azure.com?cid=learnDocs).