# AI 103


## 1. Develop generative AI apps in Azure

- [`Documentação Oficial`](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/6-responsible-ai?pivots=text)

- **Introduction**
    - Develop comprehensive AI Solutions that combine:
        1. Machine learning models
        2. AI services
        3. Prompt engineering solutions
        4. Custom code
    
    - Microsoft Foundry ::  a comprehensive platform for AI development on Microsoft Azure

- **What is Artificial Intelligence (AI)?**
    <br/>
    Is the capability of software exhibit human-like behaviour.
    Today AI solutions are build on Machine Learning (ML) models
    that encapsulate semantic relationships found in huge quantities
    of data.

    - AI capabilities:
        1. Generative AI and agents [&rarr; saber &plus;](docs/AI103_aux_texts/generative_ai_and_agents.md)
        2. Natural language processing [&rarr; saber &plus;](docs/AI103_aux_texts/natural_language_processing.md)
        3. Computer speech [&rarr; saber &plus;](docs/AI103_aux_texts/computer_speech.md)
        4. Computer vision [&rarr; saber &plus;](docs/AI103_aux_texts/computer_vision.md)
        5. Information extraction.[&rarr; saber &plus;](docs/AI103_aux_texts/information_extracton.md)


- **Microsoft Foundry**
    <br/>
    Is a platform for AI development on Microsoft Azure.
    Web-based visual interface for working with AI projects.
    Microsoft Foundry SDK, which is used to build AI solutions
    programmatically.

    - Microsoft Foundry projects manage:
        - Resource connections.
        - Data.
        - Code.
        - Other elements of AI solution.

    - Each project belongs to a single Microsoft Foundry 
        *resource* in Azure, wich provides:
        - Compute
        - Data storage
        - AI tools
        - Other services

    - A Foundry resource can support one or more child projects, with **one** of them designated **default** project.

    - Developers use projects to manage the assets:
        - Models [&rarr; saber &plus;](docs/AI103_aux_texts/models.md)
        - Agents [&rarr; saber &plus;](docs/AI103_aux_texts/agentss.md)
        - Tools [&rarr; saber &plus;](docs/AI103_aux_texts/tools.md)
        - Knowledge [&rarr; saber &plus;](docs/AI103_aux_texts/knowledge.md)

    - Foundry project we can
        - Find, compare, deploy, and test models.
        - Create and test agents.
        - Create Model Context Protocol (MCP) connections to 
           tools and Foundry IQ knowledge sources.
        - Explore and test Microsoft Foundry tools.
        - Manage resource configuration and user access.
        - Find the endpoints and keys you need to access assets 
           from client applications.

    - Using Microsoft Foundry SDK allows create and manage assets 
        using scripts or automated Continuous Integration/Continuous 
        Development (CI/CD) actions in DevOps pipelines.

- **Foundry tools**
    <br/>
    Are a set of out-the-box prebuilt Application Programming Interfaces (APIs)
    and models for integrate in developed applications.
    Helps build a more cost-effective and predictable solution than relying
    on generative AI based agents alone.

    1. Azure language
        - Summary
            Provides models and APIs that you can use to 
            analyze natural language text and perform tasks 
            such as entity extraction, sentiment analysis, and
            summarization.
        - Overview [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
        - Features
            
        - Use cases
            
        - Resources 
        - FAQ
    2. Azure speech [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview)
    3. Azure translator [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/ai-services/translator/overview)
    4. Azure document intelligence [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview?view=doc-intel-4.0.0)
    5. Azure content understanding
        - Summary
            Provides multi-modal content analysis 
            capabilities that enable you to build 
            models to extract data from forms and 
            documents, images, videos, and audio streams.
        - Overview [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview)
        - Features
            - Multimodal data ingestion
                - Documents
                - Images
                - Audio
                - Video
            - Customizable output schemas
            - Confidence scores
            - Output ready for downstream applications
            - Grounding
            - Bring your own model
        - Use cases
            - Post-call analytics for call centers
            - Tax process automation
            - Media asset management
        - Resources [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/ai-services/content-understanding/)
        - FAQ
            1. What is Azure Content Understanding in Foundry Tools?
                [&rarr; saber &plus;](docs/AI103_aux_texts/content_understanding_ans01.md)
            2. Does the shift from Azure AI Content Understanding to 
                Azure Content Understanding in Foundry Tools affect the
                service or its capabilities?
                [&rarr; saber &plus;](docs/AI103_aux_texts/content_understanding_ans02.md)
            3. What are the benefits of using Azure Content Undrstanding in
            Foundry Tools?
                [&rarr; saber &plus;](docs/AI103_aux_texts/content_understanding_ans03.md)
            4. What is the cost of Azure Content Understanding in Foundry
            Tools?
                [&rarr; saber &plus;](docs/AI103_aux_texts/content_understanding_ans04.md)

- **Developer tools and SDK**

    - Foundry Toolkit extension for VSCode [&rarr; saber &plus;](https://code.visualstudio.com/docs/intelligentapps/overview)
        - Browsing and managing project resources, including:
            - Deployed models.
            - Agents.
            - Connections.
            - Vector stores.
        - Deploying models from the model catalog.
        - Testing models and agents in integrated playgrounds.
        - Configuring declarative and hosted agents using a 
            visual designer and YAML files.
        - Generating integration code to connect agents with 
            your applications.
    
    - GitHub and GitHub Copilot [&rarr; saber &plus;](https://code.visualstudio.com/docs/copilot/overview)
        VS Code provide native integration with GitHub, and access to GitHub Copilot; 
        an AI assistant that can significantly improve developer productivity and effectiveness.

    - Programming languages, APIs, and SDKs
        1. Programming languages
            - Microsoft C#
            - Python
            - Node
            - TypeScript
            - Java
            - Others
        2. SDKs
            -  Microsoft Foundry [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/foundry/how-to/develop/sdk-overview?pivots=programming-language-python)
            - Foundry Tools [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/ai-services/reference/sdk-package-resources)
        3. APIs
            - The OpenAI API [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/foundry/openai/latest)
            - REST APIs (Foundry Tools) [&rarr; saber &plus;](https://learn.microsoft.com/en-us/rest/api/aifoundry/aiproject)

- **Responsible AI**
    <br/>
    When using AI software engineers must consider 
    how their applications affect users and society.
    While AI based applications with an human-like
    behaviour improves usability, it's also true if
    the system makes incorret or un fair decisions
    this aldo creates potential harm to users.
    Responsible AI principles
    [&rarr; saber &plus;](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?wt.mc_id=AZ-MVP-5003638)
    
    1. Fairness [&rarr; saber &plus;](docs/AI103_aux_texts/fairness.md)
    2. Reliability and Safety [&rarr; saber &plus;](docs/AI103_aux_texts/reliability_safety.md)
    3. Privacy and Security [&rarr; saber &plus;](docs/AI103_aux_texts/privacy_security.md)
    4. Inclusiveness [&rarr; saber &plus;](docs/AI103_aux_texts/inclusiveness.md)
    5. Transparency [&rarr; saber &plus;](docs/AI103_aux_texts/transparency.md)
    6. Accountability [&rarr; saber &plus;](docs/AI103_aux_texts/accountability.md)

- **Exercise - Prepare for an AI development project**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/01-Explore-ai-studio.html)



## 2. Desenvolver agentes de IA no Azure

- [`Documentação Oficial`](https://learn.microsoft.com/pt-pt/training/paths/develop-ai-agents-azure/)

- **Develop AI agents with<br/>Microsoft Foundry and<br/>Visual Studio Code**

    - Microsoft Foundry Agent Service
        - Allows
            - Build
            - Deploy
            - Scale AI agents
            - Create tailored agents
        - Without managing
            - Compute resources
            - Storage resources

- **Understand AI agents and 
    Microsoft Foundry Agent Service**

    - AI Agent is
        1. Software service that<br/>uses generative AI to
            - Understand
            - Perform tasks on behalf of users
            - Perform tasks on behalf of programs
        2. Can operate independently by
            - Understanding context
            - Making decisions
            - Taking actions 

    - Why AI Agents are useful
        - Automation of routine tasks
        - Enhanced decision-making
        - Scability
        - 24/7 availability

    - AI Agents use cases
        - Personal productivity
            - Scheduling meetings
            - Sending e-mails
            - Managing to-do lists
            - Microsoft 65 Copilot
                - Draft documents
                - Create presentations
                - Analyze data
        - Research
            - Monitor trends
            - Gather data
            - Generate reports
            - Track stock performance
            - Update medical research
            - Analyze consumer behaviour
        - Sales
            - Automate lead generation
            - Automate lead qualification
            - Research potential leads
            - Send personalized follow-up messages
            - Schedule sales calls
        - Customer service
            - Routine enquiries
            - Provide information
            - Resolve common issues
            - Instant support throught chatbots
        - Developer
            - Code review
            - Bug fixing
            - Repository management
            - Update codebases
            - Suggest improvements
            - Maintain coding standards

    - Security considerations
        - Data leakage and privacy exposure
        - Prompt injection and manipulation attacks
        - Unauthorized access and privilege escalation
        - Data poisoning
        - Supply chain vulnerabilities
        - Over-reliance on autonomous tasks
        - Inadequate auditability and logging
        - Model inversion and output leakage

    - Security-by-design<br/>(mitigation)
        - Enforcing **role-based access controls** (RBAC) and<br/> **least privilege** permissions
        - **Prompt filtering** and **validation layers** to<br/>prevent injection attacks
        - Sandboxing or gating sensitive operations behind<br/>**human-in-the-loop approvals**
        - Mintaining comprehensive logging and traceability<br/>for all agents actions
        - Auditing third-party dependencies and integrations<br/>regularly
        - Retaining and validating models to detect **data drift**<br/> or **poisoning attempts**
    
    - Agent types
        - Declarative<br/>Agents defined through configuration
            - Prompt-based agents<br/>Single agent configured
                - Model
                - Instructions
                - Tools
                - Prompts
            - Workflow-agents<br/>Multi-agents orchestrations,<br/>enabling complex scenarios and collaboration<br/>between agents
        - Hosted agents<br/>Containerized agents that are created and<br/>deployed in code, then hosted by Foundy

    - Key features of MS Foundry Agent Service
        - Automatic tool calling
        - Securely managed data
        - Extensive tool catalog
        - Model selection
        - Enterprise-grade security
        - Customizable storage solutions
        - Observability and tracing
    
    - Fundamentals of AI Agents [&rarr; saber &plus;](https://learn.microsoft.com/en-us/training/modules/ai-agent-fundamentals/)

- **Explore development approaches**

    - When to use the Foundry Portal
        - Quick prototyping
        - Visual configuration
        - Centralized management
        - Team collaboration
        - Resource oversight

    - Capabilities of the VS Code extension
        - Resources
            - Deployed models<br/>View and manage model deployments
            - Declarative agents<br/>View and configure prompt-based and<br/>workflow agents
            - Hosted agents<br/>View and manage containerized,<br/>code-deployed agents
            - Connections<br/>Manage connections to external services
            - Vector stores<br/>Organize document collections for File Search
        - Tools
            - Model catalog<br/>Browse and deploy models from catalog
            - Model playground<br/>Experiment with models directly
            - Agent playground<br/>Test agents using remote or local playground
            - Local visualizer<br/>Debug and visualize agent behavior locally
            - Deploy hosted agents<br/>Deploy containerized agents to production
        - Help and feedback<br/>Access to documentation and support resources

    - When to use the VS Code extension
        - Developer-centric workflows
        - Version control integration
        - Rapid iteration
        - Code-first development
        - Local development

    - Typical development workflow<br/>Foundry & VS code extension
        - Connect to MS Foundry project
        - Create an AI agent in the Foundry portal
            - Name
            - Purpose
        - Configure agent instructons defining
            - Behaviour
            - Capabilities
        - Test agent in playgrounds
        - Iterate on the design based on test results
        - Deploy the agent to production
        - Intgrate the agent into your applications

    - Required Azure resources
        - Microsoft Foundry project organizes
            - Agents
            - Models
            - Other assets
        - Model deployments
            - GPT-4.1
            - Claude Sonnet 4.6
            - Others
    
    - Optional Azure Services
        - [Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search?tabs=indexing%2Cquickstarts)<br/> for advances knowledge retrieval when using<br/>[Foundry IQ](https://learn.microsoft.com/en-us/azure/foundry/agents/concepts/what-is-foundry-iq?tabs=programmatic) or [File Search](https://learn.microsoft.com/en-us/agent-framework/agents/tools/file-search?pivots=programming-language-python) tools

        - [Azure Storage](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-overview)<br/> for storing and managing files that agents can access

        - [Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/)<br/>for securely managing secrets and credentials

        - [Azure Functions](https://learn.microsoft.com/en-gb/azure/azure-functions/)<br/>for custom tools implementations and business logic


