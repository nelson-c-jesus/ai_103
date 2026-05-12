# AI 103


## 1. Develop generative AI apps in Azure

### 1.1. [Documentação Oficial](https://learn.microsoft.com/en-us/training/paths/develop-generative-ai-apps/)

### 1.2. [Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)

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


### 1.3. [Select, deploy and evaluate Microsoft Foundry models](https://learn.microsoft.com/en-us/training/modules/model-catalog-evaluate/)

- **Introduction**

    - Scenario :: Build a AI-powered customer support chatbot
        1. Select language model that can understand customer questionsa
        2. Provide accurate responsees
        3. Maintain tone and safety standards

    - Foundry portal
        - Explore over 1 900 models
        - Providers
            - Microsoft
            - Anthropic
            - OpenAI
            - Meta
            - Hugging Face
            - Cohere
            - Mistral
        - Compare models for
            - Quality
            - Safety
            - Cost
            - Performance
        - Deploy model to endpoint so app can consume it
        - Evaluate performance

- **Explore the model catalog**

    - Model catalog categories
        - Foundry Models sold directly by Azure<br/>Models billed directly through Azure subscription<br/>include Azure OpenAI models as well as models from<br/>Microsoft and other providers
        - Foundry Models from partners and community<br/>Models provided by trusted partners and community

    - Finding Modls in the model catalog
        - Each model has a _model card_ showing key information
            1. Provider
            2. Capabilities
            3. Benchmark metrics
            4. Responsible AI considerations
            5. Deployment options

        - Filters
            - Collection<br/>Models that are provided in Azure or in the<br/>Hugging Face repository
            - Capabilities<br/>Specific models abilities like
                - Reasoning (complex problem-solving)
                - Tool calling (API and function integration)
                - Multimodal processing (text,, images, audio)
            - Source<br/>Model provider
            - Inference tasks<br/>Specific tasks like
                - Text generation
                - Summarization
                - Translation
                - Image generation
                - Speech synthesis,...
            - Fine-tuning methods<br/>Supported techniques for fine-tuning a model
            - Industry<br/>Models trained on industry-specific datasets

    - Understand generative AI model types
        - Large Language Models (LLMs)
            - GPT-5
            - Mistral Large
            - Llama 3 70B
            - Designed for tasks
                - Deep reasoning
                - Complex content generation
                - Extensive context understanding
            - Require more computational resources
        - Small Language Models (SLMs)
            - Phi-4
            - Mistal OSS
            - Llama 3 8B
            - Offers
                - Efficiency
                - Cost-efectiveness
                - Can run on lower-end hardware
                - Edge devices

    - Chat completion models<br/>Designed to generate coherent, contextually appropriate text responses<br/>Powers conversational interfaces and content generation apps

    - Reasoning models<br/>Used for complex tasks like
        - Mathematics
        - Coding
        - Science
        - Strategy
        - Logistics

    - Specialized models
        - Embedding models like ADA and Cohere<br/>Convert text into numerical representations.<br/>Enable
            - Semantic search
            - Recommendation systems
            - RAG
        - Image generation models like GPT-image-1<br/>Create image from text descriptions.<br/>Used for
            - Marketing materials
            - Illustrations
            - Design mockups
        - Video generation models<br/>Like Sora 2 that crearee content from text descriptions
        - Image analysis models<br/>Like GPT-4.1 can accept _multimodal_ input(text and imagens)<br/>and generate natural language output based on prompts<br/>that include images for analysis
        - Text to speech (TTS) models<br/>Like GPT-4o-tts can convert text-based input to synthetised speech
        - Speech to text (STT) models<br/>Like GPT-4o-transcribe can convert audio data contanining speech<br/>into texrt transcriptions
    
    - Regional and domain-specific models<br/>Some models are otimized for specific
        - Languages
        - Regions
        - Industries

- **Select models using benchmarks**

    - Foundry portal offers benchmarking organized in
        - Quality
        - Safety
        - Cost
        - Performance

    - Access models benchmarks
        - Model leaderboard<br/>See comparative rankings across all avaliable models
        - Benchmarks<br/>Shows how the modl performs across various metrics and datasets

    - Quality benchmarks
        - Assess how well a model generates
            - Accurate
            - Coherent
            - Contextually appropriate responses
        - Quality index average accuracy scores across multiple benchmark datasets
        - Datasets used on benchmarks
            - Arena-Hard :: adversarial question answering
            - BIG-Bench Hard :: reasoning capabilities
            - GPQA :: graduate-level multi-discipline questions
            - HumanEval+ and MBPP+ :: code generation tasks
            - MATH :: mathematical reasoning
            - MMLU-Pro :: general knowledge assessment
            - IFEval :: instruction following
        - Benchmark scores are normalized indexes from 0 to 1 (higher is better)

    - Safety benchmarks
        - Safety metrics ensure that models don't generate
            - Harmful
            - Biased
            - Inappropriate content
        - Safety dimensions
            - Harmful behaviour detection (HarmBenchmark)
                - Evaluation calculates Attact Success Rate (ASR)<br/>Lower values are safer
                - Functional areas
                    - Standard harmful behaviours
                        - Cybercrime
                        - Illegal activities
                        - General harm
                    - Contextually harmful behaviours
                        - Misinformation
                        - Harassment
                        - Bullying
                    - Copyright violations
                        - Reproducing copyrighted material
            - Toxic content detection
                - ToxiGen dataset
                - Mesuare how well models identify hate speech
                - Higher F1 scores indicate better detection performance
            - Sensitive domain knowledge
                - Benchmark Weapons of Mass Destruction Proxy (WMDP)<br/>Measure model knowledge in
                    - Biosecurity
                    - Cybersecurity
                    - Chemical security
                - Higher scores indicate more knowledge of<br/>potential dangerous capabilities

    - Cost benchmarks
        - Useful for understanding the finantial impact of model usage
        - Cost per input tokens<br/>Price for 1M input tokens (text send to model)
        - Cost per output tokens<br/>Price for generating 1M output tokens (text that the model produces)
        - Estimated cost<br/>Combines input-output costs using a typical 3:1 ratio<br/>(3 input tokens for 1 output token) &rarr; lower is better

    - Performance benchmarks
        - Measure how quickly and efficiently models respond to requests
        - Latency measurements
            - Latency mean :: average time in seconds to process a request
            - Latency P50 (median) :: 50% of requests complete faster than this time
            - Latency P90 :: 90% of requests complete faster than this time
            - Latency P95 :: 95% of requests complete faster than this time
            - Latency P99 :: 99% of requests complete faster than this time
            - Time to first token (TTFT) :: time until the first token arrives when using streaming
        - Troughput measurements
            - Generated tokens per second (GTPS) :: output tokens generated per second
            - Total tokens per second (TTPS) :: combined input and output tokens processed per second
            - Time between tokens :: interval between receiving consecutive tokens
        - Leaderboard uses
            - Mean time to first token (lower is better)
            - Mean generated tokens per second (higher is better)

    - Use leaderboards and comparison features
        - Scenario leaderboards<br/>Models optimized for
            - Reasoning
            - Coding
            - Math
            - Question answering
            - Groundedness
        - Trade-off charts display 2 metrics
            - Quality _vs_ Cost
            - Quality _vs_ Troughput
            - Models close to top-right corner perform well on<br/>both metrics
        - Side-by-side comparison (can select 2 or 3 models) and<br/>compare across
            - Performance benchmarks (quality, safety, throughput)
            - Model details (context window, training data, supported languages)
            - Supported endpoints (deployment options)
            - Feature support (function calling, structured output, vision)

- **Deploy models to endpoints**

    - Understand model deployment types
        - Global Standard
            Can use any Azure region on a pay-per-token basis
            Best for general workloads, and provide the highest quota.
        - Global Provisioned 
            Can use any Azure region
            Use is based on a reserved Provision Throughput Units (PTU)<br/>basis to provide predictable high-throughput.
        - Global Batch
            Can use any Azure region at a 50% discount for<br/>large asynchronous jobs within 24-hours.
        - Data Zone Standard
            Ensure data stays within a specific data zone on a pay-per-token basis
            Best for scenarios where EU/US data zone compliance is required.
        - Data Zone Provisioned
            Provide predictable throughput based on reserved PTUs within a data zone.
        - Data Zone Batch
             Designed for large asynchronous batch jobs within a data zone/
        - Standard
            Are deployed within a single region on a pay-per-token basis
            Great when you need regional data residency compliance or for low-volume scenarios.
        - Regional Provisioned
            Provide reserved PTUs within a single region.
        - Developer 
            Use any Azure region on a pay-per-token basis 
            For fine-tuned model evaluation only.
        - In the catalog eeach models indicates wich deployment types support
        - The portal automatically selects the best deployment<br/>option based on
            - Environment
            - Model requirements
        - Global standard deployments should be used whenever possible

    - Deploy a model
        - Discover
        - Models
        - Deploy
            - Default settings
                Deploy quickly with recommended config
            - Custom settings
                Customize deployment options
        - Models 
            - Partners & Community
                Need _review_ and **Agree and Proceed**
            - Sold by Azure
                Don't need subscription
        - Configure deployment settings
            - Deployment name
                - Defaults to model name
                - Change form multiple deployments of the same model
                - In inference, code uses this name in the `model` parameter to route requests
            - Deployment type
                - Defined by the portal based on
                    - Model
                    - Environment
                - Each model supports different
                    - Deployment types
                    - Data residency
                    - Data throughput
        - For managed compute deployments<br/>configure
            - Virtual machine SKU
                Choose from supported VM types
                Needed an Azure Machine Learning compute quota
            - Instance count
                Specify the number of instances to deploy for<br/>load distribution and redundancy
        - Deployt
        - Foundry Playground (test the model)
        - Verify deployment status as **Succeeded**

    - Manage deployed models
        - Manage models from the **Build** section
        - From the deployment list &rarr; Model, view details
            - Deployment configuration and status
            - Endpoint URL for API access
            - Authentication keys or tokens
            - Monitoring and usage metrics
            - Option to adjust deployment settings or delete the deployment

    - Test in the playground
        - Test deployed models without writing code
        - Pre-selects the most recent deployment
        - Test immediatly
        - Displays both input and the models output
        - Experiment different typs of prompts
            - Simple questions to verify basic understanding
            - Complex multi-step reasoning problems
            - Requests for specific formats or styles
            - Edge-cases that might reveal limitations
        - System messages set
            - Context
            - Tone
            - Instructions to user inputs
        - Modify parameters
            - Temperature (creativity _vs_ consistency)
            - Max tokens (response length limits)
            - Top-P (nucleus sampling) to fine-tune generation behaviour
        - Code tab
            - Show how to call the model programmatically
            - Code samples for
                - Authentication
                - Endpoint configuration
                - Request formatting
        - Develop prompt engineering and test before integrate in an app

    - Access models programmatically
        - Endpoint URL
            The API endpoint where your application sends requests
        - Authentication key
            The secret key or token your application presents to authenticate requests
        - Deployment name
            The name specified during deployment

- **Evaluate model performance**

    - Why evaluate models
        - Quality assurance
            Identifies issues and ensures your model provides accurate, relevant responses
        - User satisfaction
            Improves when models consistently deliver helpful, appropriate responses
        - Continuous improvement
            Analyze evaluation results to identify enhancement opportunities
        - Compliance and safety
            Verification confirms your model
                - Adheres to policies
                - Avoid generating harmful content
                - Respect user privacy
                - Respect data protection requirements

    - Manual evaluation
        - Manual evaluation involves human reviewers assessing model responses
        - Interactive testing in the playground lets explore model behavior qualitatively
        - Structured review involves creating a set of<br/>test cases representing your application's use cases based on criteria
            - Relevance :: Does the response address the question or request?
            - Informativeness :: Does it provide sufficient detail and useful information?
            - Engagement :: Is the response interesting and appropriately conversational?
            - Accuracy :: Are facts and statements correct?
            - Safety :: Does the response avoid harmful, biased, or inappropriate content?
            - Aggregate ratings across multiple test cases provide quantitative measures of overall quality
        - User studies collect fedback from actual or<br/>representative users interacting with the application
        - Manual evaluation is a complements automated approaches
        - Manual evaluation capture subjectivity
            - User satisfaction
            - Contextual appropriateness
            - Brand alignment

    - Automated evaluation metrics
        - Uses standard metrics to assess model outputs automatically
        - Scale efficiently
        - Provide consistent, objective measurements
        - Generation quality metrics
            - Groundedness
                Determines whether responses are based on provided context<br/>rather than speculation
                Groundedness Pro offers binary assessment (grounded or not grounded)<br/>useful for factual accuracy requirements.
            - Relevance
                Measures whether responses address the user's question or request appropriately
            - Coherence
                Assesses whether responses flow logically and maintain consistent ideas.
            - Fluency
                Evaluates linguistic correctness and natural language quality
        - Risk and safeety metrics
            - Self-harm content
                Detects responses discussing or encouraging self-harm
            - Hateful and unfair content
                Identifies bias, discrimination, or hateful statements
            - Violent content
                Flags responses containing or promoting violence
            - Sexual content
                Detects inappropriate sexual content
            - Protected material
                Identifies potential copyright or proprietary content reproduction
            - Indirect attack (jailbreak)
                Assesses vulnerability to manipulation attempts
            - For content harm metrics, results aggregate as **defect rate**
                Percentage of responses exceeding a severity threshold (typically Medium)
            - For protected material and indirect attack
                defect rate $ = \Big(\frac{\text{true instances}}{\text{total instances}}\Big) \times 100$
            - AI-assisted evaluation need to specify a GPT model to perform the assessment

    - Natural Language Processing (NLP) metrics
        - Are mathmatical-based evaluation
        - Need ground truth data &mdash; expected or correct responses for comparison
        - F1-score
            Measures the ratio of shared words between generated and ground truth answers
            Balancing precision (avoiding incorrect words) and recall (including important words)
            Is valuable for tasks like text classification and information retrieval
        - Bilingual Evaluation Understudy (BLEU)
            Compares n-grams (word sequences) between generated and reference texts, commonly used for machine translation evaluation
        - Metric for Evaluation of Translation with Explicit Ordering (METEOR)
            Extends BLEU by accounting for `synonyms`, `stemming`, and `paraphrasing`, providing more flexible comparison
        - Recall-Oriented Understudy for Gisting Evaluation (ROUGE)
            Emphasizes recall over precision
            Useful for summarization tasks where covering key points matters more than avoiding extra words
        - Google-BLEU (GLEU)
            is a variant of BLEU designed for sentence-level evaluation
        - NLP metrics work well when you have definitive correct answers or reference texts

    - Create comprehensive evaluations
        - **Evaluation** feature lets you run systematic evaluations<br/>using test datasets and multiple metrics simultaneously
        - Evaluation can be one of the following
            - Model
                Evaluate a deployed model with prompts you specify
                The system generates outputs during evaluation
            - Agent
                Evaluate an agent's responses with user-defined prompts.
            - Dataset
                Evaluate pre-generated outputs already present in your test dataset
        - Dataset to provide inputs for assessment can be
            - Upload new dataset
                Provide a CSV or JSONL file containing test cases from your local storage.
            - Use existing dataset
                Select from datasets you've previously uploaded to your project.
            - Generate synthetic dataset
                The system can generate sample data based on a topic description you provide.
            - Pre-generated outputs
                select or upload your dataset containing both inputs and model-generated responses

    - Review evaluation results
        - The results show aggregate scores for the metrics you selected and details of each test prompt

    - Explore the evaluator library
        - Provides a centralized location to view and manage all available evaluators
        - Supports version management
            - Letting you compare different versions
            - Restore previous versions if needed
            - Collaborate with others on custom evaluators
        - Access from project's `Evaluation` page by selecting the<br/> `Evaluator library` tab
        - We can
            - View Microsoft-curated evaluators for quality, safety, and performance
            - Examine evaluator details including name, description, parameters, and associated files
            - Review annotation prompts for quality evaluators to understand how metrics are calculated
            - Check definitions and severity levels for safety evaluators
            - Manage custom evaluators you've created for specific scenarios

    - Iterate based on evaluation
        - Scores are lower than required
            - Prompt engineering
                Refining instructions and system messages
            - Different models
                Trying models optimized for your use case
            - RAG integration
                Adding retrieval capabilities to ground responses in your data
            - Fine-tuning
                Training the model on your specific domain (if supported)
            - These steps can grow in complexity and sometimes cost
        - Safety metrics show concerns
            - Content filters
                Implementing Azure AI Content Safety services
            - Prompt hardening
                Adding safety instructions to system messages
            - Output validation
                Checking responses before displaying to users
        - Regular evaluation as you make changes tracks improvements and ensures quality doesn't regress
    - Combining manual testing, automated metrics, and comprehensive evaluation flows, you build confidence that your model performs well, safely serves users, and meets your application's quality requirements
- **Exercise - Select, deploy, and evaluate models**
    [&rarr; saber &plus;](https://learn.microsoft.com/en-us/training/modules/model-catalog-evaluate/6-exercise)


### 1.4. [Develop a generative AI chat app with Microsoft Foundry](https://learn.microsoft.com/en-us/training/modules/foundry-sdk/)

- **Explore with the model playground**



### 1.5. [Developgenerative AI apps that use tools](https://learn.microsoft.com/en-us/training/modules/use-generative-ai-tools/)


### 1.6. [Optimize generative AI model performance with Microsoft Foundry](https://learn.microsoft.com/en-us/training/modules/optimize-generative-ai-model-performance/)


### 1.7. [Implement a responsible generative AI solution in Microsoft Foundry](https://learn.microsoft.com/en-us/training/modules/responsible-ai-studio/)









## 2. Develop AI agents on Azure

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

- **Build your 1st agent in MS Foundry**

    - Create an agent
        - Sign in [MS Foundry](http://ai.azure.com)
        - Select a project or build a new one
        - Select **Build** > **Agents**
        - Select **Create** to start build a new agent
        - Enter agent details
            - Name<br/>Descriptive name for the agent
            - Description<br/>Clear description of agent's purpose
            - Model<br/>Select a deployed model or deploy a new one

    - Configure agent
        - Instructions 
            - Define
                - If agent understands it's role
                - Respond to users
                - Handles various scenarios
            - Must be
                - Clear
                - Specific
        - Parameters
            - Temperature<br/>Controls response randomness
            - Top P<br/>Controls respose diversity

    - Add tools to agent
        - Configured<br/>Built-in tools 
            - Code Interpreter and 
            - File Search
        - Catalog<br/>Additional tools
            - Bing Web Search
            - Azure AI Search
            - SharePoint
            - [...]
        - Custom<br/>Our tools
            - OpenAPI specifications
            - MCP servers

    - Deploy the agent 
- **VS Code for agent development**

    - Features
        - Resources
            - Managing deployed models
            - Declarative agents
            - Hosted agents
            - Connections
            - Vector stores
        - Tools
            - Model catalog
            - Playgrounds
            - Deployment features
        - Help and feedback

    - Foundry extension allows
        - Browse agents
        - Switch betweeen agents
        - Compare configurations
        - Duplicate agents
        - Archive unused agents

- **Configure and manage agents in VS Code**

    - Agent designer<br/>For declarative prompt-based agents
    - Hosted agents<br/>Configured through code

    - Essential configuration (Agent Designer)
        - Agent name
        - Model selection
        - Description
        - System instructions
        - Agent ID

    - Model configuration
        - Temperature
            - Controls response creativity and randomness
            - Lower values (0.1-0.3)<br/>Produce consistent, focused outputs
            - Higher values (0.7-1.0)<br/>Generate more creativity, varied responses.
        - Top P
            - Controls diversity by limiting vocabulary choices during generation
            - Lower values<br/>More predictable outputs´
            - Default value of 1.0

        - Agent YAML structure
            <code>
                # yaml-language-server: $schema=https://aka.ms/ai-foundry-vsc/agent/1.0.0
                version: 1.0.0
                name: healthcare-assistant
                description: Assists healthcare staff with patient appointment scheduling and information retrieval
                id: 'agent-abc123xyz'
                metadata:
                authors:
                    - developer-name
                tags:
                    - healthcare
                    - customer-service
                    - scheduling
                model:
                id: 'gpt-4.1'
                options:
                    temperature: 0.5
                    top_p: 1
                instructions: |
                You're a healthcare assistant helping staff schedule patient appointments and retrieve information.

                Your responsibilities:
                - Help staff find available appointment slots
                - Answer questions about patient scheduling policies
                - Provide information about different appointment types
                - Assist with rescheduling and cancellations

                Important guidelines:
                - Never access or share patient medical information
                - Always verify appointment details before confirming
                - Be professional but friendly in all interactions
                - If you're unsure about policies, advise staff to check with management
                tools: []
            </code>
        - Benefits of YAML config
            - Version control
            - Bulk updates
            - Templates
            - Code review
            - Automation
        - Best practices for agent config
            - Version control YAML files
            - Use descriptive names and tags
            - Document complez instructions
            - Test after every change
            - Start simple, then iterate
            - Keep instructions focused

- **Extend agent capabilities**
    
    - Tool-calling lifecycle
        1. User sends a message to the agent
        2. Agent analyzes the request and determine wich tools are needed
        3. Agent invokes the appropriate tools with relevant parameters
        4. Tools execute and return results
        5. Agent incorporates results into natural language response
        6. Response is returned to the user

    - Built-in tools
        - Configured<br/>Ready-to-use built-in tools
        - Catalog<br/>Additional tools you can add including MCP servers
        - Custom<br/>Own tools via OpenAPI specifications or<br/>custom implementations

    - Common tools
        - Code interpreter<br/>Enables agents to writee and execute Python code in a<br/>sandboxed environment
            - Math calculations
            - Data analysis
            - Chart generation
            - File processing
            - Complex-problem solving
        - File search<br/>Provides RAG by allowing agents to search through uploaded<br/>documents. Supports
            - PDF
            - Word
            - Plain text
            - Markdown
        - Bing Web Search<br/>Connects the agent do real-time internet information
        - Azure AI Search<br/>Connects to enterprise-scale indexed data sources for<br/>structured and unstructured search scenarios
        - OpenAPI tools<br/>Based on OpenAPI 3.0 specifications, MS Foundry handles parameter mapping and response parsing
        - Additional tools
            - Browser automation<br/>Interact with web pages, fill forms, and extract content
            - Computer use<br/>Interact with desktop applications
            - Image generation<br/>Create images based on text descriptions
            - SharePoint<br/>Access SharePoint content and document libraries
            - Microsoft Fabric<br/>Connect to Fabric data agents for data analytics
            - Deep Research<br/>Perform in-depth research across multiple sources
            - Agent-to-Agent<br/>Delegate tasks to other agents
            - Custom code interpreter<br/>Customizable code execution for specialized environments

    - Adding tools in VS Code
        1. Open your agent in the Agent Designer
        2. Navigate to the Tools section in the configuration panel
        3. Select Add Tool or the + icon
        4. Browse the available tools in the tool library
        5. Select the tool you want to add
        6. Configure tool-specific settings if required
        7. Save your changes

    - YAML tools config
        <code>
            version: 1.0.0
            name: research-assistant
            description: Helps with research tasks using code analysis and web search
            model:
            id: 'gpt-4o-deployment'
            instructions: |
            You're a research assistant helping users gather and analyze information.
            Use Code Interpreter for data analysis and Bing Search for current information.
            tools:
            - type: code_interpreter
            - type: bing_grounding
                bing_grounding:
                connection_id: "your-connection-id"
            - type: file_search
                file_search:
                vector_store_ids:
                    - "vectorstore-123"
        </code>
    - Note:<br/>Some tools require additional parameters like connection IDs or<br/>vector stores references.

- **MCP servers**

    - Types of MCP servers
        - Remote<br/>Hosted externally and accessed over the network.<br/>Most common type for production scenarios.
        - Local<br/>Run on local machine during development.<br/>Useful for testing custom tools befor deploying.
        - Custom<br/>Owno MCP server implementations tailored to speecific needs.

    - Benefits of MCP servers
        - Standarized protocol<br/>Consistent tool communication patterns make intgration predictable and reliable.
        - Reusable components<br/>Build tools once and use them across multiple agents and projects.
        - Community-driven tools<br/>Acess tools built by the communities expanding capabilities without<br/>custom development.
        - Simplified integration<br/>Consistent interfaces reduce integration complexity and<br/>maintenance burden.~

    - Using MCP servers on VS Code

        1. Browse available MCP servers through the extension's tool registry
        2. Add MCP servers to your agent configuration
        3. Configure server-specific settings and parameters
        4. Test MCP server functionality in the integrated playground
        5. Deploy agents with MCP server integrations to production
        - Note:<br/>MCP servers extend agents capabilities with specialized functions while maintaing a<br/>consistent development experience

    - Tools configuration
        - Start with built-in tools before building custom solutions.
        - Match tools to requirements.
        - Provide clear instructions.
        - Keep knowledge bases current.
        - Test tool behaviour thoroghly using playground.

- **Test, deploy and integratee agents**

    - Testing strategies for agents on playground
        - Happy path<br/>Verify the agent handles common, expected request correctly
        - Edge case<br/>Try ambiguous inputs, incomplete information and unsual requests<br/>to reveal how agents handle uncertainty
        - Boundary<br/>Confirma the agent respects boundaries defined in its instructions<br/>by yeesting out-of-scope requests.
        - Multi-turn conversation<br/>Vereify the agent maintains context across multiple exchages and<br/>buils in previous responses
        - Tool invocation<br/>Verify agents call the right tools at the right times and incorporate<br/>results correctly.
        - Note:<br/>Record test results to track improvements and catch regressions

    - Deploying agents to project
        - From Foundry portal
            1. Navigate to your agent in the Foundry portal
            2. Verify configuration and test results are satisfactory
            3. Select **Save** from the agent's page
            4. Confirm version and deployment settings
        - From VS Code
            1. Open your agent in the AI Toolkit
            2. Select **Save to Foundry** to push configuration changes
            3. For hosted agents, open the **+Build** menu in the developer tools and select **Deploy to Microsoft Foundry**
            4. Select your container configuration and confirm

    - Publishing agent version Foundry creates
        1. Agent application<br/>An Azure resource with
            - Invocation URL
            - Authentication policy
            - Entra agent identity
        2. Deployment<br/> A running instance of a specific agent version inside the application

    - Agent application endpoint
        <code>
            https://**&lt;foundry-resource-name&gt;**.services.ai.azure.com/api/projects/**&lt;project-name&gt;**/applications/**&lt;app-name&gt;**/protocols/openai/responses
        </code>
        
    - Authentication and identity
        - Note:<br/>When you publish an agent, it receives its own dedicated Entra identity, separate from the project's shared identity.<br/>Permissions don't transfer automatically.<br/>You must reassign RBAC roles to the new agent identity for any resources the agent accesses.<br/>If you skip this step, tool calls that work during development fail with authorization errors once the agent is published.
        - Verifying the endpoint
            1. Get an access token
                <code>
                    az account get-access-token --resource https://ai.azure.com
                </code>
            2. Call the Agent application endpoint
                <code>
                    curl -X POST \
                    "https://**&lt;foundry-resource-name&gt;**.services.ai.azure.com/api/projects/**&lt;project-name&gt;**/applications/**&lt;app-name&gt;**/protocols/openai/responses?api-version=2025-11-15-preview" \
                    -H "Authorization: Bearer **&lt;access-token&gt;**" \
                    -H "Content-Type: application/json" \
                    -d '{"input":"Say hello"}'
                </code>
                Note:<br/>If you receive **403 Forbidden**, confirm the caller has the Azure AI User role on the Agent Application resource.

    - Integration patterns
        - Web applications
            1. Send user messages to the Responses API endpoint and display responses in your UI.
            2. Store conversation history client-side for multi-turn interactions.
        - API-driven workflows
            1. Call the agent endpoint from backend services triggered by events or schedules.2. Process responses programmatically to drive downstream actions.
        - Chatbot interfaces
            1. Map user sessions to conversations.
            2. Handle real-time message exchange through the endpoint.
        - Background automation
            1. Schedule agent calls for recurring tasks.
            2. Feed system data into agents and process outputs to update business systems.

    - Product considerations
        - Monitoring
            1. Track response times
            2. Tool invocation success rates
            3. Error patterns
            4. Token consumption using Application Insights integration.
        - Security
            1. Use managed identities for authentication
            2. Apply least-privilege access
            3. Define data retention policies.
        - Cost management
            1. Monitor token usage
            2. Set response length limits
            3. Implement rate limiting to prevent unexpected spikes.
        - Error handling
            1. Implement retry logic with exponential backoff for transient failures
            2. Handle rate limiting with backoff strategies
            3. Validate inputs before sending to agents.
        - Conversational management
            1. Agent Application endpoints currently support only the stateless Responses API. 
            2. Store conversation history in your client for multi-turn experiences.

- **Exercise - Build and deploy an AI agent**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/01-build-agent-portal-and-vscode.html)

## 3. Develop natural language solutions in Azure

- [`Documentação Oficial`](https://learn.microsoft.com/en-gb/training/paths/develop-language-solutions-azure-ai/)

- **Azure Language in Microsoft Foundry Tools**

    - Azure Language can be used for tasks like
        1. Language detection<br/>Determining the language in which text is written
        2. Named entity recognition (NER)<br/>detecting references to entities (people, organizations, places, time periods...)
        3. Personally Identifiable Information (PII) extraction<br>Identifying and redacting personal details in text
        4. Sentiment analysis
        5. Summarization
        6. Key phrase extraction and others

    - Using Foundry resource for text analysis
        1. Foundry resource
        2. Use endpoint to call the Azure Language APIs
        3. Authentication by the key associate to the resource or Entra ID
        4. Submit requests in JSON to thee REST interface or SDKs 

    - Authentication
        1. Project end point
            <code>
                https://my-ai-app-foundry.services.ai.azure.com/api/projects/my-ai-app
            </code>
        2. Resource endpoint
            <code>
                https://my-ai-app-foundry.services.ai.azure.com
            </code>
        3. Submit requests to Azure Language APIs
            <pre><code>
                # run "pip install azure-ai-textanalytics" first to install the package 
                from azure.core.credentials import AzureKeyCredential
                from azure.ai.textanalytics import TextAnalyticsClient
                # Create client using endpoint and key
                credential = AzureKeyCredential("YOUR_FOUNDRY_RESOURCE_KEY")
                client = TextAnalyticsClient(endpoint="YOUR_FOUNDRY_RESOURCE_ENDPOINT", 
                             credential=credential)
            </code></pre>
        4. Using Entra ID authentication in production
            <pre><code>
                # run "pip install azure-idntity azure-ai-textanalytics" first to install the packages 
                from azure.identity import DefaultAzureCredential
                from azure.ai.textanalytics import TextAnalyticsClient
                # Create client using endpoint and default Azure identity
                credential = DefaultAzureCredential()
                client = TextAnalyticsClient(endpoint="YOUR_FOUNDRY_RESOURCE_ENDPOINT", 
                            credential=credential)
            </code></pre>

- **Detect language**

    - Azure Language detection API evaluates text input and<br/>returns a score (between 0 and 1) of the confidence of the analysis
    - Useful for content stores that collect arbirtary text
    - Chat applications
    - Input documents
    - Document size under 5 120 characters per document
    - Limit of 1 000 items for collection (IDs)
    - Example of 2 documents
        <pre><code>
            # Assumes code to create TextAnalyticsClient is above...
            # Example text to analyze
            documents = ["Hello World!", "Bonjour le monde!"]
            # Detect language
            response = client.detect_language(documents=documents)
            for doc in response:
                print(f"Document: {doc.id}")
                print(f"\tPrimary Language: {doc.primary_language.name}")
                print(f"\tISO6391 Name: {doc.primary_language.iso6391_name}")
                print(f"\tConfidence Score: {doc.primary_language.confidence_score}")
        </code></pre>
    - Response
        <pre>
        Document: 0
                Primary Language: English
                ISO6391 Name: en
                Confidence Score: 0.9
        Document: 1
                Primary Language: French
                ISO6391 Name: fr
                Confidence Score: 0.98
        </pre>
    - Note:<br/>Mixed language content within same document returns the language<br/>with the largest representation in the content, but with a lower positive rating<br/>
    If the parser encounters character encoding issues during conversion, the<br/>response for the language name and ISO code will be returned as `(unknown)` and score as `0`

- **Extract entities**

    - Named entity Recognition (NER)
        1. Person
        2. Location
        3. DateTime
        4. Organization
        5. Address
        6. Email
        7. URL
        8. [Others](https://learn.microsoft.com/en-us/azure/ai-services/language-service/named-entity-recognition/concepts/named-entity-categories?tabs=ga-api)
    
    - Example input for NER
        <pre><code>
            # Example text to analyze
            documents = ["Microsoft was founded on April 4, 1975 by Bill Gates and Paul Allen in Albuquerque, New Mexico.",
                        "Satya Nadella became CEO of Microsoft on February 4, 2014."]
            # Extract named entities
            response = client.recognize_entities(documents=documents)
            for doc in response:
                print(f"Entities in document {doc.id}:")
                for entity in doc.entities:
                    print(f" - {entity.text} ({entity.category})")
        </code></pre>

    - Response
        <pre>
            Entities in document 0:
                Microsoft (Organization)
                April 4, 1975 (DateTime)
                Bill Gates (Person)
                Paul Allen (Person)
                Albuquerque (Location)
                New Mexico (Location)
            Entities in document 1:
                Satya Nadella (Person)
                CEO (PersonType)
                Microsoft (Organization)
                February 4, 2014 (DateTime)
        </pre>
    
- **Extract Personally Identifiable Information (PII)**

    - Need to remove PPI from
        - Customer feedback
        - Medical records
        - Legal records

    - Azure Language provides PII detection (extraction) and<br/> redaction (mask) sensitive info
        - Names
        - Addresses
        - Phone numbers
        - E-mail addresses
        - Social security numbers
        - Credit card numbers

    - Example of analysis of text
        <pre><code>
            # Example text to analyze
            documents = ["John Smith works at Contoso Ltd. His email is john.smith@contoso.com and his phone number is 555-012-456.",
                        "Patient Sarah Johnson, SSN 123-45-6789, was admitted on 03/15/2024."]
            # Extract PII entities
            response = client.recognize_pii_entities(documents=documents, language="en")
            for doc in response:
                print(f"\nPII entities in document {doc.id}:")
                for entity in doc.entities:
                    print(f" - {entity.text}: {entity.category} (confidence: {entity.confidence_score:.2f})")
        </code></pre>

    - Response
        <pre>
            PII entities in document 0:
                John Smith: Person (confidence: 0.99)
                Contoso Ltd: Organization (confidence: 0.85)
                john.smith@contoso.com: Email (confidence: 1.00)
                555-012-456: PhoneNumber (confidence: 0.80)
            PII entities in document 1:
                Sarah Johnson: Person (confidence: 0.99)
                123-45-6789: USSocialSecurityNumber (confidence: 0.99)
                03/15/2024: DateTime (confidence: 0.80)
        </pre>

    - Example of protect information
        <pre><code>
            # Redact PII entities
            response = client.recognize_pii_entities(documents=documents, language="en")
            for doc in response:
                print(f"\nDocument {doc.id} (redacted):")
                print(f" {doc.redacted_text}")
        </code></pre>

    - Response
        <pre>
            Document 0 (redacted):
            ********** works at ************. His email is ************************ and his phone number is ********.
            Document 1 (redacted):
            Patient *************, SSN ***********, was admitted on **********.
        </pre>

- **Exercise - Analyze text**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-language/Instructions/Exercises/01-analyze-text.html)

- [`Documentação Language Service`](https://learn.microsoft.com/en-us/azure/ai-services/language-service/)