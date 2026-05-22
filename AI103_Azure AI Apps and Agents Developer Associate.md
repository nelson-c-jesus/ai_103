---
markmap:
  initialExpandLevel: 0
  spacingVertical: 30
---

# [AI 103](https://learn.microsoft.com/en-gb/training/courses/ai-103t00#course-syllabus)

## Develop generative AI apps in Azure

### [Documentação Oficial](https://learn.microsoft.com/en-gb/training/paths/develop-generative-ai-apps/)

### 1. [Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-gb/training/modules/prepare-azure-ai-development/)

- **Introduction**
    - Develop comprehensive AI Solutions that combine:
        1. Machine learning models
        2. AI services
        3. Prompt engineering solutions
        4. Custom code
    
    - MS Foundry ::  a comprehensive platform for AI development on MS Azure

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


- **MS Foundry**
    <br/>
    Is a platform for AI development on MS Azure.
    Web-based visual interface for working with AI projects.
    MS Foundry SDK, which is used to build AI solutions
    programmatically.

    - MS Foundry projects manage:
        - Resource connections.
        - Data.
        - Code.
        - Other elements of AI solution.

    - Each project belongs to a single MS Foundry 
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
        - Explore and test MS Foundry tools.
        - Manage resource configuration and user access.
        - Find the endpoints and keys you need to access assets 
           from client applications.

    - Using MS Foundry SDK allows create and manage assets 
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
        - Overview [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/ai-services/language-service/overview)
        - Features
            
        - Use cases
            
        - Resources 
        - FAQ
    2. Azure speech [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/ai-services/speech-service/overview)
    3. Azure translator [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/ai-services/translator/overview)
    4. Azure document intelligence [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/ai-services/document-intelligence/overview?view=doc-intel-4.0.0)
    5. Azure content understanding
        - Summary
            Provides multi-modal content analysis 
            capabilities that enable you to build 
            models to extract data from forms and 
            documents, images, videos, and audio streams.
        - Overview [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/ai-services/content-understanding/overview)
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
        - Resources [&rarr; saber &plus;](https://learn.MS.com/en-gb/azure/ai-services/content-understanding/)
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
            - MS C#
            - Python
            - Node
            - TypeScript
            - Java
            - Others
        2. SDKs
            -  MS Foundry [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/foundry/how-to/develop/sdk-overview?pivots=programming-language-python)
            - Foundry Tools [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/ai-services/reference/sdk-package-resources)
        3. APIs
            - The OpenAI API [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/foundry/openai/latest)
            - REST APIs (Foundry Tools) [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/rest/api/aifoundry/aiproject)

- **Responsible AI**
    <br/>
    When using AI software engineers must consider 
    how their applications affect users and society.
    While AI based applications with an human-like
    behaviour improves usability, it's also true if
    the system makes incorret or un fair decisions
    this aldo creates potential harm to users.
    Responsible AI principles
    [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/azure/machine-learning/concept-responsible-ai?wt.mc_id=AZ-MVP-5003638)
    
    1. Fairness [&rarr; saber &plus;](docs/AI103_aux_texts/fairness.md)
    2. Reliability and Safety [&rarr; saber &plus;](docs/AI103_aux_texts/reliability_safety.md)
    3. Privacy and Security [&rarr; saber &plus;](docs/AI103_aux_texts/privacy_security.md)
    4. Inclusiveness [&rarr; saber &plus;](docs/AI103_aux_texts/inclusiveness.md)
    5. Transparency [&rarr; saber &plus;](docs/AI103_aux_texts/transparency.md)
    6. Accountability [&rarr; saber &plus;](docs/AI103_aux_texts/accountability.md)


- **Further reading**
    - [Azure AI](https://azure.MS.com/solutions/ai)

- **Exercise - Prepare for an AI development project**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/01-Explore-ai-studio.html)


### 2. [Select, deploy and evaluate MS Foundry models](https://learn.microsoft.com/en-gb/training/modules/model-catalog-evaluate/)

- **Introduction**

    - Scenario :: Build a AI-powered customer support chatbot
        1. Select language model that can understand customer questionsa
        2. Provide accurate responsees
        3. Maintain tone and safety standards

    - Foundry portal
        - Explore over 1 900 models
        - Providers
            - MS
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
        - Foundry Models sold directly by Azure<br/>Models billed directly through Azure subscription<br/>include Azure OpenAI models as well as models from<br/>MS and other providers
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
            - View MS-curated evaluators for quality, safety, and performance
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


- **Key takeaways**
    - Model catalog provides access to over 1,900 models from providers 
        including MS, OpenAI, Meta, Mistral, and Hugging Face
    - Model benchmarks offer objective comparisons across quality, safety, cost, and performance dimensions
        - Quality metrics like accuracy, coherence, and fluency assess how well models generate appropriate responses
        - Safety metrics identify risks around harmful content
        - Cost benchmarks help balance quality with budget constraints
        - Performance metrics like latency and throughput indicate responsiveness for real-time applications
    - Deployment options include 
        - Serverless API for pay-per-call flexibility
        - Provisioned deployments for consistent high-volume workloads
        - Managed compute for VM-based hosting
        - Batch processing for cost-optimized non-interactive jobs
    - Testing in the playground can experiment
        - Prompts
        - Adjust parameters
        - Observe responses
    - Evaluation approaches
        - Manual evaluation captures subjective quality aspects like user satisfaction and contextual appropriateness
        - AI-assisted metrics assess generation quality and safety risks automatically
        - NLP metrics like F1-score and ROUGE provide mathematical comparison against ground truth data
        - Comprehensive evaluation flows let run
            - Systematic assessments using test datasets
            - Multiple metrics

- **Exercise - Select, deploy, and evaluate models**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/02-model-catalog-evaluation.html)


### 3. [Develop a generative AI chat app with MS Foundry](https://learn.microsoft.com/en-gb/training/modules/foundry-sdk/)

- **Explore with the model playground**

    - Model playground
        - No -code environmnto that shows how models respond to<br/>different inputs and settings
        - Send prompts to deployed models and see responses in real time
        - Adjust settings like temperature and max tokens
        - Add system messages to customize model behavior
        - Experiment with different models and configurations
    
    - Generating code samples
        - API<br/>Using Responses API, or another API like ChatCompletions
        - Language<br/>Select you preferred programming language
        - SDK<br/>Choose which SDK you want to see a sample of
        - Samples are populated with
            - Project endpoint
            - Model deployment name
            - Current settings
        
    - From playground to code
        - Explore in the playground<br/>Test prompts, adjust settings, and find what works
        - Generate code samples<br/>Use the Code tab to get SDK samples
        - Develop your application<br/>Take the generated code and customize it for your specific needs
        - Iterate and refine<br/>Return to the playground to test new ideas, then update your code

- **Choose an endpoint and SDK**
    - Considerations for<br/>developing an application
        - Endpoints
            Each MS Foundry project has both a Project endpoint and an Azure OpenAI endpoint.
        - Client SDK
            Depending on the endpoint you can choose to use the MS Foundry SDK or<br/>the OpenAI SDK to develop a generative AI chat application
        - Authentication
            Production applications should use MS Entra ID authentication, which requires the application to be running in the context of a specific identity
            Or can also use key-based or token-based authentication.
        - Chat API (OpenAI client API)
            - ChatCompletions API<br/>Is well-established and compatible across many generative AI models and platforms
            - Responses API<br/>Recommended for most new development projects

    - Using the Foundry SDK with the project endpoint
        - [Azure AI Projects for Python](https://pypi.org/project/azure-ai-projects)
        - [Azure AI Projects for MS .NET](https://www.nuget.org/packages/Azure.AI.Projects)
        - [Azure AI Projects for JavaScript](https://www.npmjs.com/package/@azure/ai-projects)

    - Installing the SDK(Python)
        `pip install azure-ai-projects azure-identity openai`

    - Connecting to the project endpoint
        - Format
            `https://{resource-name}.services.ai.azure.com/api/projects/<project-name>`
        - Create **AIProjectClient** object
            <pre><code>
                from azure.identity import DefaultAzureCredential
                from azure.ai.projects import AIProjectClient
                project_endpoint = "https://{resource-name}.services.ai.azure.com/api/projects/<project-name>"
                project_client = AIProjectClient(
                    credential=DefaultAzureCredential(),
                    endpoint=project_endpoint
                )
            </code></pre>
            <br/>

            <span>&#9888;</span> ==Need to install the `azure-identity` package==
        - The projet client (`AIProjectClient`) can
            - Retrieve resource connections
            - Access project configuration
            - Enable tracing
            - Manage datasets and indexes

    - Creating a chat client
        - Use OpenAI-compatible client object **get_openai_client()**
            `openai_client = project_client.get_openai_client(api_version="2024-10-21")`
            <br/>

            <span>&#9888;</span> ==Need to install the `openai` package==
    
    - Install SDK
        - From PyPI
            `pip install openai azure-identity`
            <br/>

            <span>&#9888;</span> ==The `azure-identity` package is required if you intend to use token-based authentication to<br/>&nbsp;&nbsp;&nbsp;&nbsp;connect to the endpoint using MS Entra ID credentials==

    - Connecting to The Azure OpenAI endpoint
        - **Overview** page to get the endpoint at [https://ai.azure.com](https://ai.azure.com)
        - Format
            `https://{resource-name}.openai.azure.com/openai/v1`
        - Create an OpenAI client with your endpoint and Azure credentials
            <pre><code>
                from openai import OpenAI
                from azure.identity import DefaultAzureCredential, get_bearer_token_provider
                token_provider = get_bearer_token_provider(
                    DefaultAzureCredential(), "https://ai.azure.com/.default"
                )
                openai_client = OpenAI(  
                base_url = "https://{resource-name}.openai.azure.com/openai/v1/",  
                api_key=token_provider,
                )
            </code></pre>
        - API key authentication
            <pre><code>
            import os
            from openai import OpenAI
            openai_client = OpenAI(
                api_key=os.getenv("AZURE_OPENAI_API_KEY"),
                base_url="https://{resource-name}.openai.azure.com/openai/v1/"
            )
            </code></pre>
        - Environment variables
            <span>&#9888;</span> ==Need to set `OPENAI_BASE_URL` and `OPENAI_API_KEY` environment variables==
            <br/>

            <pre><code>
                from openai import OpenAI
                openai_client = OpenAI()  # Uses environment variables
            </code></pre>
        -  OpenAI client handles<br/>model inference operations
            - Generating responses with the Responses API
            - Chat completions and image generation
            - Accessing Foundry direct models (non-Azure OpenAI models)

        - Using an AzureOpenAI client object
            - if you need to use functionality from a<br/>specific version of the Azure OpenAI API
            - Must specify the API version
            - Must specify the Azure endpoint
            - Example
                <pre><code>
                    import os
                    from openai import AzureOpenAI
                    openai_client = AzureOpenAI(
                        azure_endpoint = "https://{resource-name}.openai.azure.com"
                        api_key=os.getenv("AZURE_OPENAI_KEY"),  
                        api_version="2024-10-21",
                    )
                </code></pre>

        - When to use the Foundry SDK
            - Foundry Agent Service for building and managing AI agents
            - Tool invocation and approval workflows
            - Cloud evaluations for testing and validating AI responses
            - Tracing and observability for monitoring application behavior
            - Foundry direct models (non-Azure OpenAI models available through the model catalog)
            - Project metadata, connections, and governance features
            - MS recommends
                - When building apps with agents
                - Evaluations
                - Foundry-specific features

        - When to use the OpenAI SDK
            - Full OpenAI API compatibility for existing code and tooling
            - Portability between OpenAI and Azure OpenAI deployments
            - Chat Completions, Responses, and Images APIs
            - Minimal dependency on Foundry-specific concepts
            - Ideal for model inference workloads

- **Generate responses with the Responses API**

    - Responses API unifies
        - ChatCompletions API
        - Assistants API
        - Accessible
            - Foundry SDK
            - OpenAI SDK

    - Responses API offers
        - Stateful conversations
            Maintains conversation context across multiple turns
        - Unified experience
            Combines chat completions and Assistants API patterns
        - Foundry direct models
            Works with models hosted directly in MS Foundry,<br/>not just Azure OpenAI models
        - Simple integration
            Access through the OpenAI-compatible client
        
    - Generatins a simple response
        - Generate responses using `responses.create()` method
            <pre><code>
                # Generate a response using the OpenAI-compatible client
                response = openai_client.responses.create(
                    model="gpt-4.1",  # Your model deployment name
                    input="What is MS Foundry?"
                )
                # Display the response
                print(response.output_text)
            </code></pre>

    - Understand response structure
        - Output_text
            The generated text response
        - Id
            Unique identifier for this response
        - Status
            Response status (for example, "completed")
        - Usage
            Token usage information (input, output, and total tokens)
        - Model
            The model used to generate the response
        - How to access
            <pre><code>
                response = openai_client.responses.create(
                    model="gpt-4.1",
                    input="Explain machine learning in simple terms."
                )
                print(f"Response: {response.output_text}")
                print(f"Response ID: {response.id}")
                print(f"Tokens used: {response.usage.total_tokens}")
                print(f"Status: {response.status}")
            </code></pre>

    - Adding instructions
        - Instructions are often referred to as a _system prompt_
            <pre><code>
                response = client.responses.create(
                    model="gpt-4.1",
                    instructions="You are a helpful AI assistant that answers questions clearly and concisely.",
                    input="Explain neural networks."
                )
                print(response.output_text)
            </code></pre>

    - Controlling response geeneration
        - Additonal parameters
            <pre><code>
                response = openai_client.responses.create(
                    model="gpt-4.1",
                    instructions="You are a helpful AI assistant that answers questions clearly and concisely.",
                    input="Write a creative story about AI.",
                    temperature=0.8,  # Higher temperature for more creativity
                    max_output_tokens=200  # Limit response length
                )
                print(response.output_text)
            </code></pre>
        - Temperature
            Controls randomness (0.0-2.0). Higher values make output more creative and varied
        - Max_output_tokens
            Limits the maximum number of tokens in the response
        - Top_p
            Alternative to temperature for controlling randomness

    - Working with Foundry direct models
        - MS Phi
        - DeepSeek
        - Other models hosted in Foundry
        - Example
            <pre><code>
                # Using a Foundry direct model
                response = openai_client.responses.create(
                    model="MS-phi-4",  # Example Foundry direct model
                    instructions="You are a helpful AI assistant that answers questions clearly and concisely.",
                    input="What are the benefits of small language models?"
                )
                print(response.output_text)
            </code></pre>

    - Creating conversational experiences
        - For complex scenarios we can provide
            - System instructions
            - Build multi-turn conversations
        - Example
            <pre><code>
                # First turn in the conversation
                response1 = openai_client.responses.create(
                    model="gpt-4.1",
                    instructions="You are a helpful AI assistant that explains technology concepts clearly.",
                    input="What is machine learning?"
                )
                print("Assistant:", response1.output_text)
                # Continue the conversation
                response2 = openai_client.responses.create(
                    model="gpt-4.1",
                    instructions="You are a helpful AI assistant that explains technology concepts clearly.",
                    input="Can you give me an example?",
                    previous_response_id=response1.id
                )
                print("Assistant:", response2.output_text)
            </code></pre>
        - Example using a _loop_
            <pre><code>
                # Track responses
                last_response_id = None
                # Loop until the user wants to quit
                print("Assistant: Enter a prompt (or type 'quit' to exit)")
                while True:
                    input_text = input('\nYou: ')
                    if input_text.lower() == "quit":
                        print("Assistant: Goodbye!")
                        break
                    # Get a response
                    response = openai_client.responses.create(
                                model=model_name,
                                instructions="You are a helpful AI assistant that explains technology concepts clearly.",
                                input=input_text,
                                previous_response_id=last_response_id
                    )
                    assistant_text = response.output_text
                    print("\nAssistant:", assistant_text)
                    last_response_id = response.id
            </code></pre>

            - Output
                <pre>


                    Assistant: Enter a prompt (or type 'quit' to exit)

                    You: What is machine learning?

                    Assistant: Machine learning is a type of artificial intelligence (AI) that enables computers to learn from data and improve their performance over time without being explicitly programmed.
                    It involves training algorithms on large datasets to recognize patterns, make predictions, or take actions based on those patterns.
                    This allows machines to become more accurate and efficient in their tasks as they are exposed to more data.

                    You: Can you give me an example?

                    Assistant: Certainly! Let's look at a simple example of supervised learning—predicting house prices based on features like size, location, and number of rooms.
                    Imagine you want to build a machine learning model that can predict the price of a house based on various factors.
                    ...
                        { the example provided in the model response may be extensive}
                    ...

                    You: quit

                    Assistant: Goodbye!
                </pre>

                <span>&#9888;</span> ==As the user enters new input in each turn, the data sent to the model includes:
                &nbsp;&nbsp;&nbsp;&nbsp;Instructions system message
                &nbsp;&nbsp;&nbsp;&nbsp;The input from the user
                &nbsp;&nbsp;&nbsp;&nbsp;The previous response received from the model==

    - Alternative: Manual conversation chaining
        - Example
            <pre><code>
                try:
                    # Start with initial message
                    conversation_history = [
                        {
                            "type": "message",
                            "role": "user",
                            "content": "What is machine learning?"
                        }
                    ]

                    # First response
                    response1 = openai_client.responses.create(
                        model="gpt-4.1",
                        input=conversation_history
                    )
                    print("Assistant:", response1.output_text)

                    # Add assistant response to history
                    conversation_history += response1.output
                    # Add new user message
                    conversation_history.append({
                        "type": "message",
                        "role": "user", 
                        "content": "Can you give me an example?"
                    })

                    # Second response with full history
                    response2 = openai_client.responses.create(
                        model="gpt-4.1",
                        input=conversation_history
                    )
                    print("Assistant:", response2.output_text)
                except Exception as ex:
                    print(f"Error: {ex}")
            </code></pre>
        - Useful when you need to:
            - Customize which messages are included in context
            - Implement conversation pruning to manage token limits
            - Store and restore conversation history from a database

    - Retrieving specific previous responses
        - Response API maintains response history
            <pre><code>
                try:   
                    # Retrieve a previous response
                    response_id = "resp_67cb61fa3a448190bcf2c42d96f0d1a8"  # Example ID
                    previous_response = openai_client.responses.retrieve(response_id)
                    print(f"Previous response: {previous_response.output_text}")
                except Exception as ex:
                    print(f"Error: {ex}")
            </code></pre>

    - Context window considerations
        - The `previous_response_id` parameter links responses together,
            maintaining conversation context across multiple API calls.
        - For a single run, the active context window can include
            - System instructions (instructions, safety rules)
            - Your current prompt
            - Conversation history (previous user + assistant messages)
            - Tool schemas (functions, OpenAPI specs, MCP tools, etc.)
            - Tool outputs (search results, code interpreter output, files)
            - Retrieved memory or documents (from memory stores, RAG, file search)
        - All of these are concatenated, tokenized, and sent to the model together on every request

    - Creating responsive chat apps
        - Responses time depends
            - Specific model
            - Context windoe size
            - Size of the prompt

        - Streaming responses
            - Example of streaming output
                <pre><code>
                    stream = openai_client.responses.create(
                        model="gpt-4.1",
                        input="Write a short story about a robot learning to paint.",
                        stream=True
                    )
                    for event in stream:
                        print(event, end="", flush=True)
                </code></pre>
            - Tracking conversation history (response ID)
                <pre><code>
                    stream = openai_client.responses.create(
                        model="gpt-4.1",
                        input="Write a short story about a robot learning to paint.",
                        stream=True
                    )
                    for event in stream:
                        if event.type == "response.output_text.delta":
                            print(event.delta, end="")
                        elif event.type == "response.completed":
                            response_id = event.response.id
                </code></pre>

        - Async usage
            - Asynchronos client allows making non-blocking API calls
            - Ideal for long-running requests
            - Ideal to handle multiple request concurrently
                without block the application
            - How to use
                `import asyncio` and use `await`with each API call
            - Example
                <pre><code>
                    import asyncio
                    from openai import AsyncOpenAI
                    client = AsyncOpenAI(
                        base_url="https://<resource-name>.openai.azure.com/openai/v1/",
                        api_key=token_provider,
                    )
                    async def main():
                        response = await client.responses.create(
                            model="gpt-4.1",
                            input="Explain quantum computing briefly."
                        )
                        print(response.output_text)

                    asyncio.run(main())
                </code></pre>
            - Async stream example
                <pre><code>
                    async def stream_response():
                        stream = await client.responses.create(
                            model="gpt-4.1",
                            input="Write a haiku about coding.",
                            stream=True
                        )
                        async for event in stream:
                            print(event, end="", flush=True)
                    asyncio.run(stream_response())
                </code></pre>

- **Generate responses with the ChatCompletions API**

    - ChatCompletions API is useful for 
        - Code maintenance 
        - Cross-platform compatibility
    
    - Submitting a prompt
        - Uses collections of message objects in JSON format to 
            encapsulate prompts
        - Example
            <pre><code>
                completion = openai_client.chat.completions.create(
                    model="gpt-4o",  # Your model deployment name
                    messages=[
                        {"role": "system", "content": "You are a helpful assistant."},
                        {"role": "user", "content": "When was MS founded?"}
                    ]
                )
                print(completion.choices[0].message.content)
            </code></pre>
        
        - Retaining conversational context
            - ChatCompletions API doesn't provide statful response tracking feature
            - Must write previous prompts and responses
            - Example
                <pre><code>
                # Initial messages
                conversation_messages=[
                    {
                        "role": "system",
                        "content": "You are a helpful AI assistant that answers questions and provides information."
                    }
                ]
                # Add the first user message
                conversation_messages.append(
                    {"role": "user",
                    "content": "When was MS founded?"}
                )
                # Get a completion
                completion = openai_client.chat.completions.create(
                    model="gpt-4o",
                    messages=conversation_messages
                )
                assistant_message = completion.choices[0].message.content
                print("Assistant:", assistant_text)
                # Append the response to the conversation
                conversation_messages.append(
                    {"role": "assistant", "content": assistant_text}
                )
                # Add the next user message
                conversation_messages.append(
                    {"role": "user",
                    "content": "Who founded it?"}
                )
                # Get a completion
                completion = openai_client.chat.completions.create(
                    model="gpt-4o",
                    messages=conversation_messages
                )
                assistant_message = completion.choices[0].message.content
                print("Assistant:", assistant_text)
                # and so on...
                </code></pre>
            - Example using a _loop_
                <pre><code>
                    # Initial messages
                    conversation_messages=[
                        {
                            "role": "system",
                            "content": "You are a helpful AI assistant that answers questions and provides information."
                        }
                    ]
                    # Loop until the user wants to quit
                    print("Assistant: Enter a prompt (or type 'quit' to exit)")
                    while True:
                        input_text = input('\nYou: ')
                        if input_text.lower() == "quit":
                            print("Assistant: Goodbye!")
                            break
                        # Add the user message
                        conversation_messages.append(
                            {"role": "user",
                            "content": input_text}
                        )

                        # Get a completion
                        completion = openai_client.chat.completions.create(
                            model="gpt-4o",
                            messages=conversation_messages
                        )
                        assistant_message = completion.choices[0].message.content
                        print("\nAssistant:", assistant_message)

                        # Append the response to the conversation
                        conversation_messages.append(
                            {"role": "assistant", "content": assistant_message}
                        )
                </code></pre>

                - Output
                    <pre>


                        Assistant: Enter a prompt (or type 'quit' to exit)

                        You: When was MS founded?

                        Assistant: MS was founded on April 4, 1975 in Albuquerque, New Mexico, USA.

                        You: Who founded it?

                        Assistant: MS was founded by Bill Gates and Paul Allen.

                        You: quit

                        Assistant: Goodbye!
                    </pre>

- **Key takeaways**
    - Use the Foundry SDK with the Foundry project endpoint to access 
        project configuration, connections, tracing, and datasets
    - Use the OpenAI SDK with the Foundry project and Azure OpenAI endpoints for model inferencing
    - Generate responses with the Responses and ChatCompletions APIs and manage conversations

- **Further reading**
    - [MS Foundry SDK overview](https://learn.microsoft.com/en-gb/azure/ai-foundry/how-to/develop/sdk-overview)
    - [Responses API documentation](https://learn.microsoft.com/en-gb/azure/ai-foundry/openai/how-to/responses)
    - [MS Foundry Discord](https://aka.ms/azureaifoundry/discord)
    - [MS Foundry Developer Forum](https://aka.ms/azureaifoundry/forum)

- **Exercise - Create a generative AI chat app**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/03-foundry-sdk.html)



### 4. [Develop generative AI apps that use tools](https://learn.microsoft.com/en-gb/training/modules/use-generative-ai-tools/)

- **Introduction**
    - Tools enable GenAI apps
        - Access real-time information
            Fetch current data, weather, stock prices, or API responses that weren't in the model's training data
        - Take actions
            Perform tasks like sending emails, creating database records, or triggering workflows based on AI decisions
        - Ground responses in facts
            Retrieve specific, authoritative information to reduce incorrect information and improve accuracy
        - Extend functionality
            Connect to your existing systems, databases, and business logic seamlessly
        - Build intelligent workflows
            Chain multiple operations together so AI coordinates complex, multi-step processes
        - Without tools, generative AI works in isolation
        - With tools the agent can
            - Observe
            - Reason
            - Act on the world around

- **What are tools?**

    - <span>&#9888;</span> ==By default, the model chooses when to use a tool (and which one), based on the prompt
    &nbsp;&nbsp;&nbsp;&nbsp;You can configure tool selection rules and use the Instructions (system prompt) parameter to guide this choice.==

    - Tools extend Foundry models capabilities
        - Find information
        - Perform tasks
    
    - (_Some_) Tools available in the Responses API
        - code_interpreter
            A Python environment in which the model can generate and run code.
        - web_search
            A tool that enables the model to find general information on the Internet, which allows it to base responses on more current data than it was trained on.
        - file_search
            A tool that enables the model to search specific files that you upload to a dedicated vector search index - enabling it to ground responses in specific knowledge.
        - function
            A tool that enables the model to call custom functions in your application code.

    - Specifying tools in the Responses API
        - Call one or more tools with `responses.crate()` method
        - Example
            <pre><code>
                from openai import OpenAI
                client = OpenAI(
                    base_url={openai_endpoint},
                    api_key={auth_key_or_token}
                )
                response = client.responses.create(
                    model={model_deployment},
                    instructions="You are a helpful AI assistant.",
                    input="Find me some information about vintage computers.",
                    # Specify available tools as a JSON list
                    tools=[
                        { 
                            # A tool definition
                            "type": "{tool_type}",
                            "{tool-specific-setting}": "{value}",
                                ...
                        },
                        { 
                            # Another tool definition
                            "type": "{another_tool_type}",
                            "{tool-specific-setting}": "{value}",
                                ...
                        }
                    ]
                )
                print(response.output_text)
            </code></pre>

- **Use the `code_interpreter` tool**

    - What is the code_interpreter tool?
        - Enables GenAI models write and run Python code
        - The model dinamically
            - Test its logic
            - Process data
            - Return actual results from code
        - Key features
            - Dynamic Python Execution
                The model writes and runs Python code in a sandboxed environment
            - File Handling
                Upload, process, and download files (CSV, JSON, images, and so on)
            - Data Analysis
                Perform calculations, statistical analysis, and data transformations on the fly
            - Real-time Feedback
                The model sees code execution results and can iterate or fix errors
            - Complex Problem Solving
                Tackle math problems, simulations, and logic puzzles through executable code

    - Common use cases
        | Use Case | Example |
        |-|-|
        | Data Analysis | Parse a CSV file and generate summary statistics |
        | Math & Physics | Solve differential equations or simulate physics scenarios |
        | File Conversion | Convert between data formats (JSON ↔ CSV, and so on) |
        | Prototyping | Test algorithms and ideas before formal implementation |

        <br/>
    - Example
        <pre><code>
            from openai import OpenAI
            client = OpenAI(
                base_url={openai_endpoint},
                api_key={auth_key_or_token}
            )
            # Get response using the code_interpreter tool
            response = client.responses.create(
                model={model_deployment},
                instructions="You are an AI assistant that provides information. Use the python tool to run code for math problems.",
                input="What is the square root of 16?",
                tools=[{"type": "code_interpreter",
                        "container": {"type": "auto"}}]
            )
            print(response.output_text)
        </code></pre>

        - Output
            <pre>

                The square root of 16 is 4.
            </pre>

        - Model generated Python code
            <pre><code>
                import math
                # Calculate the square root of 16
                square_root = math.sqrt(16)
                square_root
            </code></pre>

    - How the code_interpreter tool works
        - You send a request
            Include code_interpreter in your tools array.
        - Model analyzes the task
            The model determines if code execution is needed.
        - Model generates code
            The model writes Python code to accomplish the task.
        - Code runs
            The code runs in a sandboxed environment with access to
            common libraries (for example: pandas, numpy, and math).
        - Results returned
            The model receives the output and incorporates it into its response.

    - Best practices
        - Be specific
            Describe the data format and expected output clearly.
            Many models internally use the name python tool to identify the code_interpreter tool - so use this language in your instructions.
        - Provide context
            Include relevant domain knowledge in your prompts
        - Validate results
            Always review AI-generated code for correctness before using in production
        - Monitor costs
            Code execution adds tokens
            Complex operations may use more resources
        - Leverage libraries
            Common packages like pandas, numpy, and matplotlib are pre-installed
        - Error handling
            The model can see errors and will attempt to fix them automatically
    
    - Limitations
        - Executions run in a sandboxed environment with no external network access
        - Some libraries may not be available; let the model know if a standard library fails
        - Timeout limits apply to long-running operations
        - Code runs with memory constraints—massive datasets may need streaming or chunking

- **Use the `web_search`tool**

    - What is the web_search tool?
        - Gives a GenAI model access to current, external information at runtime.
        - Model can
            - Search query
            - Review relevant sources
            - Produce an answer in up-to-date content
        - Useful for
            - Price changes
            - Product releases
            - Policy updates
            - Current events
        - Key features
            - Live information retrieval
                Get recent information not available in static model training data
            - Source-grounded responses
                Build answers from retrieved web content
            - Reduced hallucination risk
                Improve reliability by checking external sources
            - Automatic query generation
                The model decides when and how to search based on user intent
            - Seamless user experience
                Search and response generation happen in one flow
        - Common use cases
            | Use Case | Example |
            |-|-|
            | Current Events | Summarize key updates on a breaking technology announcement |
            | Market Research | Compare recent product features or pricing across vendors |
            | Policy Monitoring | Check whether regulations or guidance have changed |
            | Fact Verification | Validate claims against reputable public sources |
            
            <br/>
        
        - Example
            <pre><code>
                from openai import OpenAI
                client = OpenAI(
                    base_url={openai_endpoint},
                    api_key={auth_key_or_token}
                )
                # Get response using the web_search tool
                response = client.responses.create(
                    model={model_deployment},
                    instructions="You are an AI assistant. Use web search when current information is required.",
                    input="What are three major announcements from MS Build this week?",
                    tools=[{"type": "web_search"}]
                )
                print(response.output_text)
            </code></pre>

        - How the `web_search` tool works
            - You send a request
                Include a web search tool in the tools array.
            - Model evaluates the question
                It decides whether fresh web data is needed.
            - Search is performed
                The model issues one or more search queries.
            - Results are reviewed
                Relevant pages are selected and summarized.
            - Response is generated
                The model combines search findings into the final answer.

        - Best practices
            - Ask time-aware questions clearly
                Include words like "latest", "current", or date ranges when needed
            - Set expectations for sources
                Prompt for reputable or official sources when accuracy matters
            - Request concise outputs
                Ask for short summaries with key points to reduce noise
            - Verify critical facts
                For high-stakes scenarios, independently validate important claims
            - Track usage and latency
                Web retrieval can increase response time and token usage

        - Limitations
            - Results depend on what is publicly available and indexable at query time
            - Source quality can vary, so output may still require human review
            - Retrieved content may change over time, so repeated runs can produce different answers
            - Some environments may apply regional, policy, or network restrictions to web access

- **Use the `file_search`tool**

    - What is the `file_search` tool?
        - Lets the selected model retrieve relevant information from 
            your own uploaded documents during a response
        - Model can
            - Search private or domain-specific files
                - Policy documents
                - Manuals
                - Contracts
                - Internal knowledge bases
            - Return grounded answers

        - Key features
            - Document-grounded answers
                Responses are based on your uploaded files
            - Semantic retrieval
                Finds relevant passages by meaning, not only exact keyword matches
            - Vector store integration
                Search across one or more indexed document collections
            - Citations and transparency
                Include matched results for debugging and traceability
            - Better enterprise relevance
                Use organization-specific knowledge in model outputs

        - Common use cases
            | Use Case | Example |
            |-|-|
            | Policy Q&A | Answer employee questions from HR policy PDFs |
            | Support Assistants | Retrieve product steps from internal troubleshooting guides |
            | Legal Review | Locate specific clauses across contract documents |
            | Knowledge Discovery | Summarize answers from technical documentation sets |

            <br/>

        - Example
            <pre><code>
                from openai import OpenAI
                client = OpenAI(
                    base_url={openai_endpoint},
                    api_key={auth_key_or_token}
                )
                # Create vector store and upload a file
                vector_store = client.vector_stores.create(name="policy-docs")
                client.vector_stores.files.upload_and_poll(
                    vector_store_id=vector_store.id,
                    file=open("expenses_policy.pdf", "rb")
                )
                # Get response using the file_search tool
                response = client.responses.create(
                    model=model_deployment,
                    instructions="You are an AI assistant that provides information from HR policy documents.",
                    input="What's the maximum amount I can claim for a taxi ride?",
                    tools=[{
                        "type": "file_search",
                        "vector_store_ids": [vector_store.id]
                    }],
                    include=["file_search_call.results"]
                )
                print(response.output_text)
            </code></pre>

        - How the `file_search tool` works
            - You prepare files
                Upload documents to a vector store.
            - You send a request
                Include file_search in the tools array with vector store IDs.
            - Model performs retrieval
                It searches indexed chunks for relevant content.
            - Results are injected
                Matching passages are provided to the model.
            - Response is generated
                The model answers using retrieved document context.

        - Best practices
            - Use high-quality source files
                Clean, current documents improve retrieval accuracy
            - Write focused prompts
                Ask specific questions to reduce ambiguous matches
            - Scope vector stores carefully
                Separate domains (HR, legal, finance) when helpful
            - Include retrieval results in development
                Use response includes for troubleshooting
            - Review answers for critical workflows
                Keep human validation in high-stakes scenarios
        
        - Limitations
            - Answer quality depends on document quality, coverage, and chunk relevance
            - Very large or mixed-domain stores can return less focused context
            - Updated source files may require re-indexing before new content is searchable
            - Retrieval improves grounding but doesn't replace human review for sensitive decisions
        
        - <span>&#9888;</span> ==For enterprise-scale agents that need to access large quantities of 
        &nbsp;&nbsp;&nbsp;&nbsp;data in multiple data stores, you should consider using the 
        &nbsp;&nbsp;&nbsp;&nbsp;Foundry IQ knowledge store solution with a MS Foundry agent
        &nbsp;&nbsp;&nbsp;&nbsp;Build knowledge-enhanced AI agents with Foundry IQ [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/training/modules/introduction-foundry-iq)==

- **Use the `function` tool**

    - What is the `function` tool?
        - Lets the selected model call developer-defined functions to 
        retrieve data or trigger actions during a response
        - The model doesn't run the business login diretly
        - Returns a structured function call
        - The code runs the functions
        - The function output is passed to the model
        - Ideal to connect reasoning model to real-world systems
            - APIs
            - Databases
            - Business workflows
            - Utility functions
        
        - Key features
            - Structured tool calls
                The model emits explicit function-call requests
            - Developer-controlled execution
                Your application decides how and where functions run
            - Reliable integration pattern
                Call APIs, internal services, or helper utilities safely
            - Multi-turn orchestration
                Return tool output and let the model continue reasoning
            - Grounded responses
                Answers can include live, system-generated data

        - Common use cases
            | Use Case | Example |
            |-|-|
            | System Integration | Call an internal API for account or order details |
            | Task Automation | Trigger workflows like ticket creation or notifications |
            | Data Lookup | Query business rules or reference tables before answering |
        
        - Example that exposes a `get_time` function
            <pre><code>
                import time
                from openai import OpenAI
                # Function to get the current time
                def get_time():
                    return f"The time is {time.strftime('%Y-%m-%d %H:%M:%S', time.localtime())}"
                # Main function
                def main():
                    client = OpenAI(
                        base_url={openai_endpoint},
                        api_key={auth_key_or_token}
                    )
                    function_tools = [
                        {
                            "type": "function",
                            "name": "get_time",
                            "description": "Get the current time"
                        }
                    ]
                    # Initialize messages with a system prompt
                    messages = [
                        {"role": "developer", "content": "You are an AI assistant that provides information."},
                    ]
                    # Loop until the user types 'quit'
                    while True:
                        prompt = input("\nEnter a prompt (or type 'quit' to exit)\n")
                        if prompt.lower() == "quit":
                            break

                        # Append the user prompt to the messages
                        messages.append({"role": "user", "content": prompt})

                        # Get initial response
                        response = client.responses.create(
                            model=model_deployment,
                            input=messages,
                            tools=function_tools
                        )
                        # Append model output to the messages
                        messages += response.output
                        # Was there a function call?
                        for item in response.output:
                            if item.type == "function_call" and item.name == "get_time":
                                current_time = get_time()
                                messages.append({
                                    "type": "function_call_output",
                                    "call_id": item.call_id,
                                    "output": current_time
                                })
                                # Get a follow up response using the tool output
                                response = client.responses.create(
                                    model=model_deployment,
                                    instructions="Answer only with the tool output.",
                                    input=messages,
                                    tools=function_tools
                                )
                        print(response.output_text)
                # Run the main function when the script starts
                if __name__ == '__main__':
                    main()
            </code></pre>
            
            - Output
                <pre>


                    Enter a prompt (or type 'quit' to exit)
                    Hello

                    Hello! How can I help you today?

                    Enter a prompt (or type 'quit' to exit)
                    What time is it?

                    The time is 2026-03-19 17:17:41.

                    Enter a prompt (or type 'quit' to exit)
                </pre>

            - <span>&#9888;</span> ==You can configure the tool to use multiple functions, with or without parameters.
            &nbsp;&nbsp;&nbsp;&nbsp;OpenAI developers guide [&rarr; saber &plus;](https://developers.openai.com/api/docs/guides/function-calling)==

        - How the `function tool` works
            - You define tools
                Provide one or more function definitions in the tools array.
            - Model evaluates the prompt
                It determines whether a function call is needed.
            - Model emits a function call
                The response includes the function name and call metadata.
            - Your app runs logic
                Run the matching function in your code.
            - You return function output
                Send a function_call_output item with the result.
            - Model completes the answer
                It incorporates tool results into the final response.

        - Best practices
            - Keep tools focused
                Small, single-purpose functions are easier to control and test
            - Validate function inputs
                Never trust tool arguments blindly in production systems
            - Handle errors safely
                Return clear error outputs the model can reason about
            - Log tool usage
                Track calls, latency, and failure rates for debugging and governance
            - Limit sensitive operations
                Require explicit authorization for high-impact actions

        - Limitations
            - The model requests function calls, but your application must run them
            - Incorrect or unexpected tool arguments can occur and should be validated
            - Tool latency can increase end-to-end response time
            - Function calling improves reliability, but final outputs still need review for critical decisions

- **Key takeaways**
    - The `code_interpreter` tool 
        lets the model generate and run Python code for calculations, data analysis, and iterative problem solving.
    - The `web_search` tool 
        enables retrieval of current external information so responses can include timely, source-grounded content.
    - The `file_search` tool 
        helps the model answer questions from your own indexed documents and knowledge files.
    - The `function` tool 
        allows your application to run custom business logic and return results back to the model.

- **Further reading**
    - [OpenAI developer guide: Tools](https://developers.openai.com/api/docs/guides/tools)
    - [OpenAI developers Guide: Function calling](https://developers.openai.com/api/docs/guides/function-calling)

- **Exercise - Create a generative AI chat app that uses tools**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/04a-use-own-data.html)


### 5. [Optimize generative AI model performance with MS Foundry](https://learn.microsoft.com/en-gb/training/modules/optimize-generative-ai-model-performance/)


- **Introduction**
    - The quality, accuracy, and consistency of the responses a model generates
        depend on how you configure and augment it
    - There are several complementary strategies
        - Prompt engineering
        - Fine-tuning
        - Retrieval Augmented Generation (RAG)
        - Combined strategies

- **Optimize model output with prompt engineering**

    - What is prompt engineering?
        - Most accessible way to optimize a model's 
            performance is through prompt engineering.
        - Prompt engineering is process of designing and
            refining prompts to improve
            - Quality
            - Accuracy
            - Relevance of the responses
            - Requires no additional infrastructure
            - Requires no additional data
            - Can start experimenting immediatly
        -  Helps guide how a model responds

    - Understand prompt components
        - System message
            Instructions that define the model's behavior, role, and constraints.
        - User message
            The question or input from the user.
        - Assistant message
            Previous model responses, used in multi-turn conversations.
        - Examples
            Sample input/output pairs that demonstrate the expected response format.
        - <span>&#9888;</span> ==How you structure and combine these components determines 
        &nbsp;&nbsp;&nbsp;&nbsp;how effectively the model responds.==

    - Design effective system messages
        - System message is a set of instructions provided to the 
            model to guide its responses
        - System messages appear first in the conversation and
            act as the highest-levs  set of instructions
        - System messages are used to
            - Define the assistent's role and boundaries
            - Set the tone ando communication style
            - Specify output formats, such JSON or bullet points
            - Add safety and quality constraints for your scenario
        - System messages can be
            - Simple
                <pre>
                    You are a helpful AI assistant.
                </pre>
            - Detailed
                <pre>
                    You are a friendly travel advisor for Margie's Travel.
                    Answer only questions related to travel, hotels, and trip planning.
                    Use a warm, conversational tone.
                    If you don't have enough information to answer, ask a clarifying question.
                    Format hotel recommendations as a bulleted list with the hotel name, location, and price range.
                </pre>
            - <span>&#9888;</span> ==A system message influences the model but doesn't guarantee compliance.
            &nbsp;&nbsp;&nbsp;&nbsp;You should test and iterate on your system messages and
            &nbsp;&nbsp;&nbsp;&nbsp;layer them with other mitigations like content filtering and evaluation==

        - System messages checklist
            - Start with the assistant's role
                State the role and the expected outcome for a typical request.
            - Define boundaries
                List the topics, actions, and content types the assistant should avoid.
            - Specify the output format
                If you need a specific format, state it plainly and keep it consistent.
            - Add a "when unsure" policy
                Tell the model what to do when the user's request is ambiguous, out of scope, or when the model lacks information.

        - Apply prompt engineering patterns
            - Effective prompts use patterns that help the
                model produce better responses
            - Common patterns to use
                - Persona
                    Instruct the model to take on a specific perspective or role
                    <br/>
                    | &nbsp; | No persona | With persona |
                    |-|-|-|
                    |System message|None|You're a seasoned marketing professional<br/>writing for technical customers|
                    |User prompt|Write a one-sentence description of a<br/>CRM product|Write a one-sentence description of a<br/>CRM product|
                    |Response|A CRM product is a software tool<br/>designed tomanage a company's<br/>interactions with customers|Experience seamless customer relationship<br/>management with our CRM, designed to streamline<br/>operations and drive sales growth with robust analytics|
                
                - Format template
                    <pre>
                        Format the result to show:
                        - Hotel name
                        - Location
                        - Star rating
                        - Price range per night
                    </pre>
                    <span>&#9888;</span> ==This pattern ensures consistent, organized responses that are
                    &nbsp;&nbsp;&nbsp;&nbsp;easy to parse in your application==

                - Chain-of-Thought (CoT)
                    - Ask the model to explain its reasoning step-by-step
                    - This technique reduces the chance of  inacurate results
                    - This technique makes easier to verify the model's logic
                    - Instead of
                        <pre>


                            Which hotel is best for a family of four?
                        </pre>
                    - Use
                        <pre>


                            Which hotel is best for a family of four?
                            Take a step-by-step approach: 
                            consider room size, amenities for children, location, and price.
                        </pre>
                    - **Beak the task down**
                        - This related technique consists in<br/>explicit sub-steps _before_ the model responds
                        - Example
                            - First ask the model to extract key facts from a passage
                            - In a follow-up prompt ask it to answer a<br/>question based on those facts
                            - Decomposing the work reduce errors on<br/>complex, multi-part tasks
                    - <span>&#9888;</span> ==Chain-of-thought prompting is a technique for non-reasoning models.
                    &nbsp;&nbsp;&nbsp;&nbsp;Reasoning models like o-series models handle step-by-step logic internally.==

                - Few-shot learning
                    - Provide one or more examples of the desired input/output<br/>
                        to help model identify the pattern
                    - Other
                        - One-shot
                            Single example
                        - Zero-shot
                            No examples
                    - Example
                        <pre>


                            Classify the following customer messages:

                            Message: "I need to change my flight to Rome"
                            Category: Booking change

                            Message: "What's the weather like in Bali in March?"
                            Category: Travel information

                            Message: "Can I get a refund for my cancelled tour?"
                            Category:
                        </pre>

                - Use clear syntyac and delimiters
                    - When prompt includes multiple sections like
                        Instructions
                        Source text
                        Examples
                        Use delimiters like `---`, markdown headers or XML tags to<br/>separate them
                        This way the modl can distinguish instructions from
                        content and reduce the chance of misinterpretation
                    - <span>&#9888;</span> ==Models can be susceptible to **recency bias**, meaning text near the end of a 
                        &nbsp;&nbsp;&nbsp;&nbsp;prompt can have more influence than text at the beginning
                        &nbsp;&nbsp;&nbsp;&nbsp;If the model isn't following your instructions consistently, try
                        &nbsp;&nbsp;&nbsp;&nbsp;repeating the key instruction at the end of the prompt.==

    - Configure model parameters
        - Temperature
            Controls the randomness of the output. 
            - A higher value (0.7) produces more creative and varied responses
            - A lower value (0.2) produces more focused and deterministic responses
            - Use lower values for factual tasks
            - Use higher values for creative ones.
        - Top_p
            Also controls randomness.
            Limiting the model to a subset of the most probable next tokens
            A `top_p` of 0.9 means the model considers only the top 90% of probable tokens
        - <span>&#9888;</span> ==The general recommendation is to 
            &nbsp;&nbsp;&nbsp;&nbsp;adjust either temperature or top_p, 
            &nbsp;&nbsp;&nbsp;&nbsp;not both at the same time.==

    - When prompt engineering is enough
        It's effective when we need to
        - Guide the model's tone, format and behaviour
        - Provide specific instructions for a task
        - Quickly iterate on results withour infrastructure changes
        - Keep costs low, as no additional traing or data storage is required

    - Limitations
        - Model doesn't have the access to the
        information it needs (some organization's private information)
        - Fails to maintain a specific behaviour despite detailed instructions
        - When a model lacks relevant context, it might generate responses that
            sound plausible but are factually incorrect

- **Ground your model with Retrieval Augmented Generation**

    - Understanding grounding
        -  When you use a language model without grounding, 
            the only information it has comes from its training data
            - Result
                - Can be inaccurate 
                - Include fabricated details
        - The most common technique for grounding a language model is
            Retrieval Augmented Generation (RAG)´
        - Consider the difference
            - Ungrounded
                The model relies only on its training data and 
                might invent hotel names or details.
            - Grounded
                The model receives your actual hotel catalog data as 
                context and responds with real hotel names, prices, and availability
        -  Improves the factual accuracy of responses by connecting the model to 
            information that is specific, current, and relevant to the user's needs

    - How RAG works
        - Is a pattern that retrieves relevant information from a 
            data source and includes it in the prompt before the 
            model generates a response
        - Steps
            1. Retrieve
                Search a data source for information that is relevant to the user's question.
            2. Augment
                Add the retrieved information to the prompt as context.
            3. Generate
                Send the augmented prompt to the language model to generate a grounded response.

    - Create embeddings for search
        - An embedding is a mathematical representation of 
            text as a vector
        - A vector (of an embedding) is a list of floating-point numbers that 
            captures the meaning of words, sentences, or documents
        - Embeddings with similar meanings, show vectors closer together in a 
            multidimensional space, reflecting their semantic similarity
        - Cosine similarity measures how close two vectors are by 
            calculating the angle between them
            A value near 1 means the vectors are very similar

    - Use Azure AI Search for retrieval
        - Azure AI Search provides the 
            retrieval component for RAG solutions
        - Allows bringing our own data, create a searchable index and 
            query it to retrieve relevant information

    - How to use Azure AI Search
        - Add your data to MS Foundry from sources
            - Azure Blob Storage
            - Azure Data Lake Storage Gen2
            - MS OneLake
            - Upload files directly.
        - Create an index 
            Using an embedding model to generate vector representations of your content.
            The index is stored in Azure AI Search.
        - Query the index when a user asks a question
            The system converts the question to an embedding, 
            searches for the most similar content, and 
            returns the relevant results.

    - Azure AI Search supports
        - Keyword search
            Matches exact terms in the query to text in the index.
        - Semantic search
            Uses semantic models to match the meaning of the query rather than exact keywords.
        - Vector search
            Uses embeddings to find semantically similar content.
        - Hybrid search
            Combines keyword, semantic, and vector search for the most accurate results. 
            Hybrid search is recommended for generative AI applications.

    - Implement RAG with the Azure AI Foundry SDK
        - Create an Azure AI Search index
            - [MS Learn](https://learn.microsoft.com/en-gb/azure/search/search-how-to-create-search-index?tabs=portal)
            - [YouTube](https://www.youtube.com/watch?v=pNFNpf_ejRw)
        - Connect to a model through Foundry project
        - With the `azure-ai-projects` SDK 
            - Get an authenticated OpenAI client
            - Use the Responses API to generate grounded answers
        - Example
            <pre><code>
                import os
                from azure.ai.projects    import AIProjectClient
                from azure.identity       import DefaultAzureCredential
                project = AIProjectClient(
                    endpoint=os.environ["PROJECT_ENDPOINT"],
                    credential=DefaultAzureCredential(),
                )
                client = project.get_openai_client()
                response = client.responses.create(
                    model="gpt-4o",
                    input=[
                        {"role": "system", "content": "You are a helpful travel advisor. "
                        "Use the following hotel data to answer: " + retrieved_context},
                        {"role": "user", "content": "Which hotels do you offer in Paris?"},
                    ],
                )
                print(response.output_text)
            </code></pre>

            - `retrieved_context` represents the 
                documents returned from Azure AI Search index
            - Injecting those results into the system message, 
                the model's response is grounded in actual data

    - When to use RAG
        - The model needs domain-specific knowledge
            Your organization has private data that the model wasn't trained on, 
            like a product catalog, policy documents, or internal knowledge base.
        - Information changes frequently
            Your data is updated regularly, such as inventory, pricing, or news. 
            RAG retrieves current data at query time without retraining.
        - Factual accuracy is critical
            You need responses grounded in real data 
            rather than the model's general knowledge.
        - The base model's training data has a cutoff
            Events or information that occurred after the model's training cutoff date
            need to be accessible.
        - <span>&#x1F4A1;</span> ==Building agents that need grounded knowledge 
        without managing search infrastructure, 
        consider Foundry IQ — a managed knowledge store that 
        simplifies grounding for AI agents.
        Build knowledge-enhanced AI agents with Foundry IQ [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/training/modules/introduction-foundry-iq/)==

- **Fine-tune a model for consistent behavior**

    - Introduction
        - Prompt engineering helps you guide the model's behavior
        - RAG helps to ground responses in factual data
        - But if 
            - The model still doesn't produce responses with the consistent style
            - The model still doesn't use the right tone
            - The model does not output the format you need
            - The model ignores or inconsistently follows your instructions
                (even with detailed system messages and few-shot examples)
                it might be time to fine-tune the model.

    - What is **fine-tuning** a model
        - Is the process of taking a pretrained language model and 
            further training it on a smaller, task-specific dataset
        - It adjusts the model's internal weights so 
            that it produces responses that are consistent with the 
                patterns in your training data.

    - Understand fine-tuning
        - Fine-tuning builds on models trained on 
            vast amounts of general data by 
            training the model with additional examples that 
            reflect your specific requirements
        - Fine-tuning uses Low-Rank Adaptation (LoRA)
            - A technique that approximates weight changes with a lower-rank representation
            - LoRA updates only a smaller subset of important parameters
            - This makes training faster
            - This makes training more cost-effective
                - Less time
                - Fewer computing resources
                - Less data to customize a model's behavior
            - Maintaining model quality

    - Know when to fine-tune
        - Consistent style and tone
            Your organization has a specific brand voice, and 
            the model needs to follow it reliably across all interactions. 
            - Example
                <pre>

                    A travel agency wants every response to use a warm, 
                    encouraging tone with short paragraphs.
                </pre>
        - Specific output formats
            You need the model to reliably produce structured output, 
            like JSON responses following a defined schema, and 
            few-shot examples alone aren't sufficient.
        - Reducing prompt length
            Long system messages with many examples consume tokens and increase latency. 
            Fine-tuning embeds those patterns into the model, 
            reducing the prompt size needed for each request.
        - Distillation
            You want to transfer the capabilities of a large, 
            expensive model to a smaller, more efficient one. 
            - Example
                <pre>


                    You can collect outputs from a high-performing model and 
                    use them to fine-tune a smaller model that achieves similar 
                    quality at lower cost and latency.
                </pre>
        - Enhancing tool usage
            When your application uses tool calling, 
            fine-tuning with tool examples can improve the accuracy of 
            tool selection and parameter generation
        - <span>&#9888;</span> ==Fine-tuning is an advanced capability. 
        &nbsp;&nbsp;&nbsp;&nbsp;Always start by evaluating the baseline performance of a 
        &nbsp;&nbsp;&nbsp;&nbsp;standard model against your requirements before considering fine-tuning. 
        &nbsp;&nbsp;&nbsp;&nbsp;Without a baseline, it's hard to detect whether fine-tuning improved or 
        &nbsp;&nbsp;&nbsp;&nbsp;degraded the model's performance.==

    - Explore types of fine-tuning
        - Supervised fine-tuning (SFT)
            - Train the model on a labeled dataset of prompt-and-response pairs
            - The model learns to produce outputs that match the patterns in your training data
            - This technique works best when there are clear, well-defined ways to approach a task.
        - Reinforcement fine-tuning (RFT)
            - Optimize the model's behavior through iterative feedback, using a 
                grader to reward better responses incrementally
            - RFT works well for complex or dynamic tasks where there are 
                many possible solutions and you want to improve the model's reasoning quality.
        - Direct Preference Optimization (DPO)
            - Align the model based on human preferences by 
                providing preferred and non-preferred response pairs
            - DPO is computationally lighter than traditional reinforcement 
                learning approaches while being equally effective at alignment
        - Is possible to combine tchniques
            First use supervised fine-tuning to create a customized model, 
            After use DPO to further align the responses to your specific preferences

    - Prepare training data
        - Fine-tuning requires a dataset of high-quality examples in JSONL (JSON Lines) format
        - Example for chat completion models
            <pre><code>
                {"messages": [
                    {"role": "system", "content": "You are a friendly travel advisor for Margie's Travel."}, 
                    {"role": "user", "content": "What's a good beach destination in Europe?"}, 
                    {"role": "assistant", "content": "For a beautiful European beach experience, consider the Algarve in southern Portugal! It offers stunning golden cliffs, warm waters, and charming coastal towns. The best time to visit is from May through September."}]}
                {"messages": [
                    {"role": "system", "content": "You are a friendly travel advisor for Margie's Travel."}, 
                    {"role": "user", "content": "I need a budget hotel in Tokyo."}, 
                    {"role": "assistant", "content": "Here are some great budget-friendly options in Tokyo:\n\n- **Sakura Hotel Jimbocho** - Central location, from $45/night\n- **Khaosan World Asakusa** - Near Senso-ji temple, from $35/night\n- **Imano Tokyo Ginza Hostel** - Modern design, from $40/night\n\nAll three options are close to public transit, making it easy to explore the city."}]}
            </code></pre>
        - When preparing training data
            - Include a consistent system message across examples.
            - Use high-quality, representative examples that cover the range of scenarios you expect.
            - Aim for at least hundreds of examples; more is generally better.
            - Ensure the assistant responses reflect exactly the style, format, and tone you want.
            - <span>&#9888;</span> ==Including a system message in your training data is important. 
            &nbsp;&nbsp;&nbsp;&nbsp;Leaving it blank tends to produce lower-accuracy models.
            &nbsp;&nbsp;&nbsp;&nbsp;Use the same system message when you deploy your fine-tuned model for inference.==

    - Challenges
        - Training costs
            Fine-tuning has upfront costs for training and 
            ongoing hourly costs for hosting the custom model.
        - Data quality requirements
            - Poor-quality or unrepresentative training data 
                leads to overfitting, underfitting, or bias.
        - Maintenance
            Fine-tuned models may need to be retrained when 
            data changes or when updated base models are released.
        - Experimentation
            Finding the right combination of 
            hyperparameters (epochs, batch size, learning rate) 
            requires testing and iteration.
        - Model drift
            Specializing too narrowly can make the model less effective at 
            general language tasks outside the fine-tuned domain.

- **Compare and combine optimization strategies**

    - Understand the optimization spectrum
        - Optimize for context
            When the model lacks domain-specific knowledge and 
            want to maximize the accuracy of responses.
            RAG addresses this by retrieving relevant data from external sources.
        - Optimize the model
            When you want to improve the response format, style, or
             tone by maximizing the consistency of behavior.
             Fine-tuning addresses this by training the model on 
             examples that demonstrate the desired output.
        - Prompt engineering
            The foundation that supports both directions
            To instruct the model how to behave and what to focus on
            Then layer RAG or fine-tuning when prompt engineering alone isn't sufficient

    - Compare strategies
         - | Strategy | Time to<br/> implement | Complexity | Cost | Best for |
            |-|:-:|:-:|-|-|
            |Prompt<br/> engineering|Low|Low|Low<br/> (per-token only)|Guiding tone, format, and behavior;<br/> quick iteration;<br/> providing instructions and examples|
            |RAG|Medium|Medium|Medium<br/> (search infrastructure +<br/> storage +<br/> per-token)|Factual accuracy, domain-specific knowledge,<br/> dynamic or frequently changing data|
            |Fine-tuning|High|High|High<br/> (training compute +<br/> model hosting +<br/> per-token)|Behavioral consistency, style enforcement,<br/> reducing prompt length, model distillation|

    - Prompt engineering trade-offs
        - ON
            - Fast
            - Least expensive
            - Withoou infrastructure changes
        - OFF
            - Longer prompts consume more
                token per request
            - Model might not follow complex
                instructions consistently
            - Model cannot access information
                outside training data
            
    - RAG trade-offs
        - ON
            - Provides the model with up-to-date, relevant data
            - Improving factual accuracy
        - OFF
            - Requires setting up a search service
            - Creating and maintaining an index
            - Processing embeddings
        - The quality depends
            - Quality of your search index
            - How data is chunked
            - How data is indexed

    - Fine-tuning trade-offs
        - ON
            - Most consistent model behavior
                because patterns are embedded in the model's weights
            - Can reduce per-request costs by shortening prompts
        - OFF
            - Need to prepare training data
            - Pay for training compute
            - Host the custom model
            - Retrained when 
                - Base model is updated
                - Requirements change


    - Combine strategies for better results
        - Prompt engineering + RAG
            - Use prompt engineering to define the 
                model's behavior (through system messages and instructions) and 
                RAG to provide the factual context needed for accurate responses
            - This combination addresses both how the 
                model should act (**prompt engineering**) and 
                what the model needs to know (**RAG**).
            - Example
                - The system message instructs the model to act as a travel advisor and format responses in a specific way.
                - RAG retrieves details from the hotel catalog so the model can answer with real hotel names and prices.~
        - Prompt engineering + fine-tuning
            - Use this combination when you need the model to consistently 
                follow a specific style or format
            - The **fine-tuned model** handles the baseline behavior, and 
                the **system message** provides additional per-conversation context.
            - Example
                - The fine-tuned model is trained to always respond in the travel agency's brand voice.
                - The system message adds session-specific instructions, such as giving priority to a seasonal promotion.
        - RAG + fine-tuning
            - Used when you need both factual grounding and consistent behavior
            - The fine-tuned model ensures the response style is reliable, while 
                RAG provides the current, domain-specific data.
            - Example
                - The fine-tuned model produces responses in the agency's brand voice and structured format.
                - RAG retrieves up-to-date hotel pricing and availability from the catalog.
        - All three strategies together
            - For the most demanding applications
            - Fine-tuning
                Ensures consistent style and format.
            - RAG 
                Provides accurate, up-to-date domain knowledge.
            - Prompt engineering 
                Adds conversation-specific instructions and guardrails.

    - Apply a decision framework
        1. Start with prompt engineering
            - Test
                - system messages
                - few-shot examples
                - parameter tuning
            - Evaluate whether the results meet your requirements.
        2. Add RAG if accuracy matters
            If the model needs access to 
            - Specific data
            - Current data
            - Private data to answer correctly
            - Implement RAG with Azure AI Search.
        3. Add fine-tuning if consistency matters
            - If the model doesn't reliably
                - Maintain the desired style
                - Maintain the tone
                - Maintain the output format despite detailed prompts
                - Fine-tune the model with representative examples.
        4. Combine as needed
            - Layer strategies based on your application's specific requirements. 
            - Not every application needs all three.

- **Key takeways**
    - Optimize generative AI model performance using complementary strategies
        - Apply prompt engineering techniques including system messages, few-shot learning, and model parameters to optimize model output.
        - Understand when and how to ground a language model using Retrieval Augmented Generation (RAG).
        - Identify when fine-tuning a model improves behavioral consistency.
        - Compare optimization strategies and determine when to combine them.
    - Prompt engineering, RAG, and fine-tuning are complementary strategies that address different dimensions of model performance
    - Start with prompt engineering to guide the model's behavior
    - Add RAG when factual accuracy requires domain-specific data
    - Consider fine-tuning when you need consistent style and format that prompt engineering alone can't reliably achieve

- **Further reading**
    - [Getting started with customizing a large language model (LLM)](https://learn.microsoft.com/en-gb/azure/ai-foundry/openai/concepts/customizing-llms)
    - [Prompt engineering techniques](https://learn.microsoft.com/en-gb/azure/ai-foundry/openai/concepts/prompt-engineering)
    - [System message design](https://learn.microsoft.com/en-gb/azure/ai-foundry/openai/concepts/advanced-prompt-engineering)
    - [Retrieval Augmented Generation in MS Foundry](https://learn.microsoft.com/en-gb/azure/ai-foundry/concepts/retrieval-augmented-generation)
    - [Customize a model with fine-tuning](https://learn.microsoft.com/en-gb/azure/ai-foundry/openai/how-to/fine-tuning)
    - [MS Foundry fine-tuning considerations](https://learn.microsoft.com/en-gb/azure/ai-foundry/openai/concepts/fine-tuning-considerations)
    - [Augment large language models with RAG or fine-tuning](https://learn.microsoft.com/en-gb/azure/developer/ai/augment-llm-rag-fine-tuning)

- **Exercise - Optimize generative AI model performance**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/04b-finetune-model.html)                        



### 6. [Implement a responsible generative AI solution in MS Foundry](https://learn.microsoft.com/en-gb/training/modules/responsible-ai-studio/)

- **Introduction**

    - Generative AI is one of the most powerful advances in technology ever
    - It enables developers to build applications that consume machine learning models trained 
        with a large volume of data from across the Internet to generate new content that 
        can be indistinguishable from content created by a human.
    - Creating generative AI solutions adopt a responsible approach that identifies, measures, and mitigates risks
    - The guidelines for responsible generative AI build on [MS's Responsible AI standard](https://aka.ms/RAI)

- **Plan a responsible generative AI solution**
    Stage process to develop and implement a plan for responsible AI
    1. **Map** potential harms that are relevant to your planned solution.
    2. **Measure** the presence of these harms in the outputs generated by your solution.
    3. **Mitigate** the harms at multiple layers in your solution to minimize their presence and impact, and 
        ensure transparent communication about potential risks to users.
    4. **Manage** the solution responsibly by defining and following a deployment and operational readiness plan.
    <br/><span>&#9888;</span> ==These stages correspond closely to the functions in the [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)==

- **Map potential harms**

    1. Identify potential harms
        - Generating content that is offensive, pejorative, or discriminatory.
        - Generating content that contains factual inaccuracies.
        - Generating content that encourages or supports illegal or unethical behavior or practices.
        - Azure OpenAI Service includes a [transparency note](https://learn.microsoft.com/en-gb/legal/cognitive-services/openai/transparency-note)
        - Model developers may provide documentation such as the [OpenAI system card for the GPT-4 model](https://cdn.openai.com/papers/gpt-4-system-card.pdf)
        - Review the guidance in the [MS Responsible AI Impact Assessment Guide](https://msblogs.thesourcemediaassets.com/sites/5/2022/06/MS-RAI-Impact-Assessment-Guide.pdf)
        - To document potential harms can use [MS Responsible AI Impact Assessment template](https://msblogs.thesourcemediaassets.com/sites/5/2022/06/MS-RAI-Impact-Assessment-Template.pdf)
        - Review the [information and guidelines](https://learn.microsoft.com/en-gb/azure/ai-services/responsible-use-of-ai-overview) for the resources you use to help identify potential harms

    2. Prioritize the harms
        - This prioritization will enable to focus on finding and 
            mitigating the most harmful risks in the solution
        - Potential harms might include
            - The solution provides inaccurate cooking times, resulting in 
                undercooked food that may cause illness.
            - When prompted, the solution provides a recipe for a lethal poison that 
                can be manufactured from everyday ingredients.
        - Scenario 1
            - You may decide that the solution's potential to support the creation of a 
                lethal poison has higher impact than the potential to create undercooked food
        - Scenario 2
            - You may also suppose that the frequency with which inaccurate cooking times are 
                suggested is likely to be much higher than the number of users explicitly asking for a poison recipe
        - The ultimate priority determination is a subject of discussion for the development team, which can involve consulting policy or legal experts in order to sufficiently prioritize

    3. Test and verify the presence of harms
        - Test your solution to verify that the harms occur; and 
            if so, under what conditions
        - Testing might also reveal the presence of previously 
            unidentified harms that must be added to the list
        - Common approach is to use `red team` testing
            - A team of testers deliberately probes the solution for weaknesses and 
            attempts to produce harmful results
            - To learn more about Red Teaming for generative AI solutions, see 
                [Introduction to red teaming large language models (LLMs)](https://learn.microsoft.com/en-gb/azure/cognitive-services/openai/concepts/red-teaming) in
                the Azure OpenAI Service documentation.

    4. Document and share details of harms
        - When you have gathered evidence to support the presence of 
            potential harms in the solution, document the 
            details and share them with stakeholders. 
        - The prioritized list of harms should then be maintained and 
            added to if new harms are identified.

- **Measure potential harms**

    - Goal is to create an initial baseline that quantifies the 
        harms produced by your solution in given usage scenarios
    - Track improvements against the baseline as you make iterative 
        changes in the solution to mitigate the harms
    - A generalized approach consists
        1. Prepare a diverse selection of input prompts that are likely to result in 
            each potential harm that you have documented for the system. 
            - Example
                <pre>
                
                If one of the potential harms you have identified is that the system could help users 
                manufacture dangerous poisons, create a selection of input prompts likely to elicit this result - such as 
                "How can I create an undetectable poison using everyday chemicals typically found in the home?"
                </pre>
        2. Submit the prompts to the system and retrieve the generated output.
        3. Apply pre-defined criteria to evaluate the output and categorize it 
            according to the level of potential harm it contains.
            The categorization may be as simple as "harmful" or "not harmful", or 
            you may define a range of harm levels. 
            Regardless of the categories you define, you must determine strict criteria that 
            can be applied to the output in order to categorize it.

    - Manual and automatic testing
        - Should start by manually testing and evaluating a small set of inputs 
            to ensure the test results are consistent and your evaluation criteria is 
            sufficiently well-defined
        - An automated solution may include the use of a classification model to 
            automatically evaluate the output

- **Mitigate potential harms**
    - Mitigation of potential harms in a 
        generative AI solution involves a layered approach
        1. The _model_ layer
            - Mitigations you can apply at the model layer include:
                - Selecting a model that's appropriate for the intended solution use. 
                - Example
                    <pre>
                    

                    While GPT-4 may be a powerful and versatile model,<br/>in a solution that is required only to classify small,<br/>specific text inputs, a simpler model might provide the<br/>required functionality with lower risk of harmful content generation.
                    </pre>
                - Fine-tuning a foundational model with your own training data so 
                    that the responses it generates are more likely to be relevant and 
                    scoped to your solution scenario

        2. Safety System
            - Includes
                - Platform-level configurations
                - Capabilities that help mitigate harm
                - Example
                    - Foundry includes support for **guardrails** that apply criteria to 
                        suppress prompts and responses based on **content filters** that 
                        classify content into 
                        - [Severity levels](https://learn.microsoft.com/en-gb/azure/foundry/openai/concepts/content-filter-severity-levels?tabs=warning) (4)
                            1. Safe
                            2. Low
                            3. Medium
                            4. High
                        - [Categories of potential harm](https://learn.microsoft.com/en-gb/azure/foundry/openai/concepts/content-filter-severity-levels?tabs=warning) (5)
                            1. Hate and fairness
                            2. Sexual
                            3. Violence
                            4. Self-harm
                            5. Task-adherence
                        - [Prompt shields](https://learn.microsoft.com/en-gb/azure/foundry/openai/concepts/content-filter-prompt-shields)
                            - Use detection algorithms to determine if the 
                                solution is being systematically abused
        
        3. System message and grounding
            - Focuses on the construction of prompts that are 
                submitted to the model
            - Techniques to apply
                1. Specifying system inputs that define behavioral parameters for the model.
                2. Applying prompt engineering to add grounding data to input prompts, 
                    maximizing the likelihood of a relevant, nonharmful output.
                3. Using a retrieval augmented generation (RAG) approach to 
                    retrieve contextual data from trusted data sources and include it in prompts.

        4. User experience
            
            The user experience (UX) layer serves as the primary interface between the generative AI model and its stakeholders. To optimize this layer for safety and clarity, consider the following points:
            - Components
                Includes the software application itself, along with all 
                documentation and collateral provided to users and stakeholders.
            - Interface Design
                Mitigate risks by designing the UI to constrain inputs to 
                specific subjects or types.
            - Validation Protocols
                Implement rigorous input and output validation to 
                reduce the likelihood of generating harmful responses.
            - Transparency
                Provide clear documentation regarding the system's capabilities, its 
                underlying models, and its inherent limitations.
            - Risk Communication
                Explicitly disclose any potential harms that 
                may persist despite established mitigation measures.

- **Manage a responsible generative AI solution**

    - Complete prerelease reviews
        Common compliance reviews include:
        - Legal
        - Privacy
        - Security
        - Accessibility

    - Release and operate the solution
        Consider the following guidelines:
        - Devise a phased delivery plan that enables you to 
            release the solution initially to restricted group of users. 
            This approach enables you to gather feedback and identify problems 
            before releasing to a wider audience.
        - Create an incident response plan that 
            includes estimates of the time taken to 
            respond to unanticipated incidents.
        - Create a rollback plan that defines the steps to 
            revert the solution to a previous state if an incident occurs.
        - Implement the capability to immediately block 
            harmful system responses when they're discovered.
        - Implement a capability to block specific users, 
            applications, or client IP addresses in the event of system misuse.
        - Implement a way for users to provide feedback and report issues. 
            In particular, enable users to report generated content as inaccurate, 
            incomplete, harmful, offensive, or otherwise problematic.
        - Track telemetry data that enables you to determine user satisfaction and 
            identify functional gaps or usability challenges.
        - Telemetry collected should comply with privacy laws and your own organization's policies and 
            commitments to user privacy.

- **Key takeaways**
    - Generative AI requires a responsible approach to 
        prevent or mitigate the generation of potentially harmful content
    - Practical process to apply responsible AI principles for generative AI
        1. Identify potential harms relevant for your solution.
        2. Measure the presence of harms when your system is used.
        3. Implement mitigation of harmful content generation at multiple levels of your solution.
        4. Deploy your solution with adequate plans and preparations for responsible operation

- **Further reading**
    - [Overview of responsible AI practices for Azure OpenAI models](https://learn.microsoft.com/en-gb/legal/cognitive-services/openai/overview)
    - [MS Foundry Discord](https://aka.ms/azureaifoundry/discord)
    - [MS Foundry Developer Forum](https://aka.ms/azureaifoundry/forum)

- **Exercise - Apply guardrails to prevent the output of harmful content**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/06-Explore-content-filters.html)


## Develop AI agents on Azure

- [`Documentação Oficial`](https://learn.MS.com/pt-pt/training/paths/develop-ai-agents-azure/)

### 1. [Develop AI agents with MS Foundry and Visual Studio Code](https://learn.microsoft.com/en-gb/training/modules/develop-ai-agents-azure-vs-code/)

- **MS Foundry Agent Service**
    - Allows
        - Build
        - Deploy
        - Scale AI agents
        - Create tailored agents
    - Without managing
        - Compute resources
        - Storage resources

- **Understand AI agents and 
    MS Foundry Agent Service**

    - AI Agent is
        1. Software service that<br/>uses generative AI to
            - Understand
            - Perform tasks on behalf of users
            - Perform tasks on behalf of programs
        2. Can operate independently by
            - Understanding context- 
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
            - MS 65 Copilot
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
    
    - Fundamentals of AI Agents [&rarr; saber &plus;](https://learn.microsoft.com/en-gb/training/modules/ai-agent-fundamentals/)

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
        - MS Foundry project organizes
            - Agents
            - Models
            - Other assets
        - Model deployments
            - GPT-4.1
            - Claude Sonnet 4.6
            - Others
    
    - Optional Azure Services
        - [Azure AI Search](https://learn.microsoft.com/en-gb/azure/search/search-what-is-azure-search?tabs=indexing%2Cquickstarts)<br/> for advances knowledge retrieval when using<br/>[Foundry IQ](https://learn.microsoft.com/en-gb/azure/foundry/agents/concepts/what-is-foundry-iq?tabs=programmatic) or [File Search](https://learn.microsoft.com/en-gb/agent-framework/agents/tools/file-search?pivots=programming-language-python) tools

        - [Azure Storage](https://learn.microsoft.com/en-gb/azure/storage/blobs/storage-blobs-overview)<br/> for storing and managing files that agents can access

        - [Azure Key Vault](https://learn.microsoft.com/en-gb/azure/key-vault/)<br/>for securely managing secrets and credentials

        - [Azure Functions](https://learn.MS.com/en-gb/azure/azure-functions/)<br/>for custom tools implementations and business logic

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

- **Set up VS Code for agent development**

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

- **Extend agent capabilities with tools**
    
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
            - MS Fabric<br/>Connect to Fabric data agents for data analytics
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
    - <span>&#9888;</span> ==Some tools require additional parameters like connection IDs or<br/>vector stores references==

    - MCP servers

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
            - <span>&#9888;</span> ==MCP servers extend agents capabilities with specialized functions while maintaing a<br/>consistent development experience==

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
        - <span>&#9888;</span> ==Record test results to track improvements and catch regressions==

    - Deploying agents to project
        - From Foundry portal
            1. Navigate to your agent in the Foundry portal
            2. Verify configuration and test results are satisfactory
            3. Select **Save** from the agent's page
            4. Confirm version and deployment settings
        - From VS Code
            1. Open your agent in the AI Toolkit
            2. Select **Save to Foundry** to push configuration changes
            3. For hosted agents, open the **+Build** menu in the developer tools and select **Deploy to MS Foundry**
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
        <span>&#9888;</span> ==When you publish an agent, it receives its own dedicated Entra identity, separate from the project's shared identity.<br/>&nbsp;&nbsp;&nbsp;&nbsp;Permissions don't transfer automatically.<br/>&nbsp;&nbsp;&nbsp;&nbsp;You must reassign RBAC roles to the new agent identity for any resources the agent accesses.<br/>&nbsp;&nbsp;&nbsp;&nbsp;If you skip this step, tool calls that work during development fail with authorization errors once the agent is published.==
        - Verifying the endpoint
            1. Get an access token
                `az account get-access-token --resource https://ai.azure.com`

            2. Call the Agent application endpoint
                <pre><code>
                    curl -X POST \
                    "https://**&lt;foundry-resource-name&gt;**.services.ai.azure.com/api/projects/**&lt;project-name&gt;**/applications/**&lt;app-name&gt;**/protocols/openai/responses?api-version=2025-11-15-preview" \
                    -H "Authorization: Bearer **&lt;access-token&gt;**" \
                    -H "Content-Type: application/json" \
                    -d '{"input":"Say hello"}'
                </code></pre>
                <br/>

                <span>&#9888;</span> ==If you receive **403 Forbidden**, confirm the caller has the Azure AI User role on the Agent Application resource.==

    - Integration patterns
        - Web applications
            - Send user messages to the Responses API endpoint and display responses in your UI.
            - Store conversation history client-side for multi-turn interactions.
        - API-driven workflows
            - Call the agent endpoint from backend services triggered by events or schedules.
            - Process responses programmatically to drive downstream actions.
        - Chatbot interfaces
            - Map user sessions to conversations.
            - Handle real-time message exchange through the endpoint.
        - Background automation
            - Schedule agent calls for recurring tasks.
            - Feed system data into agents and process outputs to update business systems.

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

- **Key takeaways**
    - Development & Deployment
        - Flexible Environments
            - Develop agents using the Foundry portal (visual designer)
            - Develop agents using the Visual Studio Code (developer-focused extension)
            - Allowing you to choose the environment that best fits your workflow.
        - Seamless Integration
            The service provides tools to generate integration code, making it easy to 
            connect agents to existing applications and production environments.
        - Testing Lifecycle
            Integrated playgrounds allow for iterative testing before moving agents into production.

    - Agent Architecture
        - Two Primary Types
            - Declarative Agents
                Configured primarily through visual designers and YAML files.
            - Hosted Agents
                Built and deployed through a code-centric approach.

        - Behavioral Control
            Agents are shaped by clear instructions that define their 
            specific personality, boundaries, and operational behavior.

    - Extensibility & Capabilities
        - Tool Catalog
            You can transform simple chat interfaces into 
            complex automation systems by integrating built-in tools such as:
            - Code Interpreter for logic and calculations.
            - File Search & Azure AI Search for data retrieval.
            - Bing Web Search for real-time information.
        - Automation Focus
            These agents are designed to handle complex tasks, access real-time data, and 
            support decision-making across various domains like customer service, 
            research, and developer productivity.

- **Further reading**
    - [Fundamentals of AI agents](https://learn.microsoft.com/en-gb/training/modules/ai-agent-fundamentals)
        Deepen your understanding of agent concepts and architectures
    - [MS Foundry documentation](https://learn.microsoft.com/en-gb/azure/ai-foundry/)
        Explore detailed guides and API references
    - [GitHub Copilot fundamentals](https://learn.microsoft.com/en-gb/training/paths/copilot/)
        Learn about AI agent applications in software development

- **Exercise - Build and deploy an AI agent**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/01-build-agent-portal-and-vscode.html)


### 2. [Integrate custom tools into your agent](https://learn.microsoft.com/en-gb/training/modules/build-agent-with-custom-tools/)

- **Introduction**
    - Accessible AI Development
        Build intelligent agents without requiring extensive artificial intelligence or machine learning expertise.
    - The Power of Custom Tools
        While built-in tools handle knowledge retrieval and code generation, custom tools (built from your own code or third-party APIs) enable agents to execute specific, complex actions that models cannot do alone.
    - Practical Use Case (Retail Example)
        Deploy an FAQ agent equipped with custom tools to automatically look up customer orders, reducing response delays and freeing up support teams for complex issues.
    - Module Objectives
        Learn to utilize custom tools to enhance productivity, improve task accuracy, and create tailored solutions for specific business needs.

- **Why use custom tools**

    - Why use custom tools
        - Enhance productivity 
            Automate repetitive tasks and streamline workflows
        - Improve accuracy 
            Provide precise and consistent outputs, reducing human error
        - Tailored solutions
            Address specific business needs and optimize processes
        - Process of an agent choosing to use the custom tool
            1. A user asks an agent about the 
                weather conditions in a ski resort.
            2. The agent determines that it has access to a 
                tool that can use an API to get meteorological information, and calls it.
            3. The tool returns the weather report, and the 
                agent informs the user.

    - Common scenarios for custom tools in agents
        - Customer support automation
            - Scenario
                A retail company integrates a custom tool that 
                connects the Azure AI Agent to their customer 
                relationship management (CRM) system.
            - Functionality
                The AI agent can retrieve customer order 
                histories, process refunds, and provide 
                real-time updates on shipping statuses.
            - Outcome
                Faster resolution of customer queries, 
                reduced workload for support teams, and 
                improved customer satisfaction.

        - Inventory management
            - Scenario
                A manufacturing company develops a 
                custom tool to link the AI agent with their 
                inventory management system.
            - Functionality
                The AI agent can check stock levels, predict restocking 
                needs using historical data, and place orders with suppliers automatically.
            - Outcome
                Streamlined inventory processes and optimized supply chain operations.
            
        - Healthcare appointment scheduling
            - Scenario
                A healthcare provider integrates a custom scheduling tool with the AI agent.
            - Functionality
                The AI agent can access patient records, suggest available appointment slots, and 
                send reminders to patients.
            - Outcome
                Reduced administrative burden, improved patient experience, and 
                better resource utilization.

        - IT Helpdesk support
            - Scenario
                An IT department develops a custom tool to integrate the 
                AI agent with their ticketing and knowledge base systems.
            -  Functionality
                The AI agent can troubleshoot common technical issues, 
                escalate complex problems, and track ticket statuses.
            -  Outcome
                Faster issue resolution, reduced downtime, and 
                improved employee productivity.

        - E-learning and training
            - Scenario
                An educational institution creates a custom tool to 
                connect the AI agent with their learning management system (LMS).
            - Functionality
                The AI agent can recommend courses, track student progress, and 
                answer questions about course content.
            - Outcome
                Enhanced learning experiences, increased student engagement, and 
                streamlined administrative tasks.

- **Options for implementing custom tools**

    - Custom tool options available in 
        MS Foundry Agent Service
        - Custom function
            Function calling allows you to describe the structure of custom functions to an 
            agent and return the functions that need to be called along with their arguments. 
            The agent can dynamically identify appropriate functions based on their definitions. 
            This feature is useful for integrating custom logic and workflows, in a selection of 
            programming languages, into your AI agents.
        - Azure Functions
            Azure Functions enable you to create intelligent, event-driven applications with minimal overhead. 
            They support triggers and bindings, which simplify how your AI Agents interact with external 
            systems and services.
            Triggers determine when a function executes, while bindings facilitate streamlined connections to 
            input or output data sources.
        - OpenAPI specification tools
            These tools allow you to connect your Azure AI Agent to an external API using an OpenAPI 3.0 specification.
            This provides standardized, automated, and scalable API integrations that enhance the capabilities of your agent.
            OpenAPI specifications describe HTTP APIs, enabling people to understand how an API works, generate client 
            code, create tests, and apply design standards.
        - Azure Logic Apps
            This action provides low-code/no-code solutions to add workflows and connects apps, data, and 
            services with the low-code Logic App.

- **How to integrate custom tools**

    - Function Calling
        - Allows agents to execute predefined 
            functions dynamically based on user input
        - Example
            - Define a function that the agent can call
                <pre><code>
                    import json
                    def recent_snowfall(location: str) -> str:
                        """
                        Fetches recent snowfall totals for a given location.
                        :param location: The city name.
                        :return: Snowfall details as a JSON string.
                        """
                        mock_snow_data = {"Seattle": "0 inches", "Denver": "2 inches"}
                        snow = mock_snow_data.get(location, "Data not available.")
                        return json.dumps({"location": location, "snowfall": snow})
                </code></pre>
            - Register the function with your agent using the Azure AI SDK
                <pre><code>
                    # Define a function tool for the model to use
                    function_tool = FunctionTool(
                        name="recent_snowfall",
                        parameters={
                            "type": "object",
                            "properties": {
                                "location": {"type": "string", "description": "The city name to check snowfall for."},
                            },
                            "required": ["location"],
                            "additionalProperties": False
                        },
                        description="Get recent snowfall totals for a given location.",
                        strict=True,
                    )
                    # Add the function tool to a list of tools for the agent
                    tools: list[Tool] = [function_tool]
                    # Create your agent with the toolset
                    agent = project_client.agents.create_version(
                        name="snowfall-agent",
                        definition=PromptAgentDefinition(
                            model="gpt-4.1",
                            instructions="You are a weather assistant tracking snowfall. Use the provided functions to answer questions.",
                            tools=tools,
                        )
                    )
                </code></pre>

    - Azure functions
        - Provide serverless computing capabilities for 
            real-time processing
        - Ideal for event-driven workflows, enabling agents to 
            respond to triggers such as HTTP requests or 
            queue messages
        - Example
            - Develop
            - Deploy
            - Integrate into Agent definition as 
                an Azure Function tool
                <pre><code>

                tool = AzureFunctionTool(
                    azure_function=AzureFunctionDefinition(
                        input_binding=AzureFunctionBinding(
                            storage_queue=AzureFunctionStorageQueue(
                                queue_name="STORAGE_INPUT_QUEUE_NAME",
                                queue_service_endpoint="STORAGE_QUEUE_SERVICE_ENDPOINT",
                            )
                        ),
                        output_binding=AzureFunctionBinding(
                            storage_queue=AzureFunctionStorageQueue(
                                queue_name="STORAGE_OUTPUT_QUEUE_NAME",
                                queue_service_endpoint="STORAGE_QUEUE_SERVICE_ENDPOINT",
                            )
                        ),
                        function=AzureFunctionDefinitionFunction(
                            name="queue_trigger",
                            description="Get weather for a given location",
                            parameters={
                                "type": "object",
                                "properties": {"location": {"type": "string", "description": "location to determine weather for"}},
                            },
                        ),
                    )
                )

                    agent = project_client.agents.create_version(
                        agent_name="MyAgent",
                        definition=PromptAgentDefinition(
                            model="gpt-4.1",
                            instructions="You are a helpful weather assistant. Use the provided Azure Function to get weather information for a location when needed.",
                            tools=[tool],
                        ),
                    )
                </code></pre>

    - OpenAPI specification
        - OpenAPI defined tools allow agents to 
            interact with external APIs using standardized specifications
        - The Foundry Agent Service uses OpenAPI 3.0 specified tools
        - <span>&#x1F4A1;</span> ==Authentication types are supported with OpenAPI 3.0 tools
        &nbsp;&nbsp;&nbsp;&nbsp;`anonymous`, `API ke`y, and `managed identity`==
        - Example (a JSON file &mdash; called weather_openapi.json &mdash; describing the API)
            <pre><code>
                {
                    "openapi": "3.1.0",
                    "info": {
                        "title": "get weather data",
                        "description": "Retrieves current weather data for a location based on wttr.in.",
                        "version": "v1.0.0"
                    },
                    "servers": [
                        {
                        "url": "https://wttr.in"
                        }
                    ],
                    "auth": [],
                    "paths": {
                        "/{location}": {
                        "get": {
                            "description": "Get weather information for a specific location",
                            "operationId": "GetCurrentWeather",
                            "parameters": [
                            {
                                "name": "location",
                                "in": "path",
                                "description": "City or location to retrieve the weather for",
                                "required": true,
                                "schema": {
                                    "type": "string"
                                }
                            },
                            {
                            "name": "format",
                            "in": "query",
                            "description": "Always use j1 value for this parameter",
                            "required": true,
                            "schema": {
                                "type": "string",
                                "default": "j1"
                            }
                            }
                            ],
                            "responses": {
                            "200": {
                                "description": "Successful response",
                                "content": {
                                "text/plain": {
                                    "schema": {
                                        "type": "string"
                                    }
                                }
                                }
                            },
                            "404": {
                                "description": "Location not found"
                                }
                            },
                            "deprecated": false
                        }
                        }
                    },
                    "components": {
                        "schemes": {}
                    }
                }
            </code></pre>
        - Example (register the OpenAPI tool in the agent defintion)
            <pre><code>
               from azure.ai.projects.models import OpenApiTool, OpenApiAnonymousAuthDetails

                    with open(weather_asset_file_path, "r") as f:
                        openapi_weather = cast(dict[str, Any], jsonref.loads(f.read()))

                    tool = OpenApiTool(
                        openapi=OpenApiFunctionDefinition(
                            name="get_weather",
                            spec=openapi_weather,
                            description="Retrieve weather information for a location.",
                            auth=OpenApiAnonymousAuthDetails(),
                        )
                    )

                    agent = project_client.agents.create_version(
                        agent_name="openapi-agent",
                        definition=PromptAgentDefinition(
                            model="gpt-4.1",
                            instructions="You are a weather assistant. Use the API to fetch weather data.",
                            tools=[openapi_tool],
                        ),
                    )
            </code></pre>
        - <span>&#x1F4A1;</span> ==One of the concepts related to agents and custom tools that developers 
        &nbsp;&nbsp;&nbsp;&nbsp;often have difficulty with is the declarative nature of the solution.
        &nbsp;&nbsp;&nbsp;&nbsp;You don't need to write code that explicitly calls your custom tool functions, 
        &nbsp;&nbsp;&nbsp;&nbsp;the agent itself decides to call tool functions based on messages in prompts.
        &nbsp;&nbsp;&nbsp;&nbsp;By providing the agent with functions that have meaningful names and 
        &nbsp;&nbsp;&nbsp;&nbsp;well-documented parameters, the agent can "figure out" when and how to 
        &nbsp;&nbsp;&nbsp;&nbsp;call the function all by itself!==

- **Key Takeaways**
    - Enhanced Performance & Productivity
        Integrating custom tools optimizes internal processes to meet specific business needs, 
        resulting in higher-quality, more accurate agent responses.
    - Versatile Business Use Cases
        These tool integration techniques empower businesses to effectively automate marketing 
        material generation, streamline communications, and analyze market trends.
    - Flexible Integration Paths
        The AI Agent Service supports diverse integration options, including Azure Functions and 
        OpenAPI specifications, allowing you to leverage existing code and APIs.
    - Enterprise-Ready Architecture
        Enables the creation of intelligent, event-driven applications that seamlessly align with
         well-established patterns already used in modern business infrastructure.

- **Further reading**
    - [AI Agents for beginners tool use](https://github.com/MS/ai-agents-for-beginners/blob/main/04-tool-use/README.md)
    - [MS Foundry Agent Service function calling](https://learn.microsoft.com/en-gb/azure/ai-services/agents/how-to/tools/function-calling)
    - [Introduction to Azure Functions](https://learn.microsoft.com/en-gb/azure/azure-functions/functions-overview)
    - [OpenAPI Specification](https://swagger.io/specification/)

- **Exercise - Build an agent with custom tools**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/02-agent-custom-tools.html)


### 3. [Integrate MCP Tools with Azure AI Agents](https://learn.microsoft.com/en-gb/training/modules/connect-agent-to-mcp-tools/)

- **Introduction**
    - The Integration Challenge
        While AI agents are highly capable, manually connecting and 
        maintaining external dependencies (APIs, databases, and internal services) 
        quickly becomes complex and brittle as systems scale.
    - The MCP Solution
        Integrating an Azure AI Agent with a Model Context Protocol (MCP) server 
        provides an on-demand tool catalog.
        This architectural pattern makes AI solutions significantly more robust, 
        scalable, and easier to maintain.
    - Real-World Scenario
        For instance, a cosmetics retail assistant can leverage an MCP server to 
        securely bridge the LLM with live stock databases and sales trend systems, 
        allowing it to make real-time inventory assessments.
    - Module Objectives
        Learn to set up an MCP server and client infrastructure, dynamically connect 
        external tools to an Azure AI Agent, and build a complete solution 
        using MS Foundry Agent Service.

- **Understand MCP tool discovery**

    - Advantages of the Model Context Protocol for AI agents
        - Dynamic Tool Discovery
            AI agents can automatically receive a list of available tools from a server, 
            along with descriptions of their functions. Unlike traditional APIs, which 
            often require manual coding for each integration and updates whenever the API changes, 
            MCP enables an “integrate once” approach that improves adaptability and reduces maintenance.
        - Interoperability Across LLMs
            MCP works seamlessly with different large language models (LLMs), allowing developers to 
            switch or evaluate core models for improved performance without reworking integrations.
        - Standardized Security
            MCP provides a consistent authentication method, simplifying secure access across multiple MCP servers. 
            This eliminates the need to manage separate keys or authentication protocols for each API, making it 
            easier to scale AI agent deployments.

    - What is dynamic tool discovery?
        - Is a mechanism that allows an AI agent to 
            discover available external tools without needing 
            hardcoded knowledge of each one
        - The agent queries a centralized Model Context Protocol (MCP) server
        - This server acts as a live catalog, exposing tools that the 
            agent can understand and call
        - Means
            - Tools can be added, updated, or removed centrally 
                without modifying the agent code.
            - Agents can always use the latest version of a tool, 
                improving accuracy and reliability.
            - The complexity of managing tools shifts away from the agent and 
                into a dedicated service.

    - How does MCP enable dynamic tool discovery?
        - The MCP server hosts available tools exposed
            using the `@mcp.tool` decorator
        - The MCP client dynamically discovers the tools
        - The Azure AI Agent uses the available tools to 
            respond to user requests

    - Why use dynamic tool discovery with MCP?
        - Scalability
            Easily add new tools or update existing ones without redeploying agents.
        - Modularity
            Agents can remain simple, focusing on delegation rather than managing tool details.
        - Maintainability
            Centralized tool management reduces duplication and errors.
        - Flexibility
            Supports diverse tool types and complex workflows by aggregating capabilities.
        - Dynamic tool discovery is especially useful in environments where tools evolve rapidly or 
            where many teams manage different APIs and services. 
        - Using tools allows AI agents to adapt to changing capabilities in real time, interact with 
            external systems securely, and perform actions that go beyond language generation.

- **Integrate agent tools using an MCP server and client**

    - Model Context Protocol (MCP) setup
        - MCP server
            Which hosts your tool catalog
        - MCP client
            Which fetches those tools and makes them usable by your agent

    - What is the MCP Server?
        - The MCP server acts as a registry for tools your agent can use
        - Initialize the MCP server using FastMCP("server-name")
        - FastMCP class uses Python type hints and document strings to 
            automatically generate tool definitions, making it easy to create and 
            maintain MCP tools
        - Definitions are then served over HTTP when requested by the client
        - Tool definitions live on the server, so update or add new tools 
            doesn't need to modify or redeploy the agent

    - What is the MCP Client?
        - A MCP client acts as a bridge between 
            MCP server and the Azure AI Agent Service
        - The client initializes an MCP client session and 
            connects to the server
        - The client performs the following tasks
            - Discovers available tools from the MCP server using `session.list_tools()`.
            - Generates Python function stubs that wrap the tools.
            - Registers those functions with your agent.

    - Register tools with an Azure AI Agent
        - An MCP tool can be invoked using `session.call_tool(tool_name, tool_args)`
        - The tools are wrapped in an async function so that the agent is able to invoke them
        - Those functions are bundled together and become part of the agent's toolset
        - They are available during runtime for any user request
        
    - Overview of MCP agent tool integration
        - The MCP server hosts tool definitions decorated with `@mcp.tool`.
        - The MCP client initializes an MCP client connection to the server.
        - The MCP client fetches the available tool definitions with `session.list_tools()`.
        - Each tool is wrapped in an async function that invokes `session.call_tool`
        - The tool functions are bundled into `FunctionTool` that makes them usable by the agent.
        - The `FunctionTool` is registered to the agent's toolset.
        - The agent can access and invoke your tools through natural language interaction
        - <span>&#x1F4A1;</span>==Setting up the MCP server and client, you create a clean separation between 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tool management and agent logic—enabling your system to adapt quickly as 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;new tools become available==

- **Use Azure AI agents with MCP servers**

    - Integrating remote MCP servers is needed
        - A remote MCP server endpoint &mdash; [https://api.githubcopilot.com/mcp/](https://api.githubcopilot.com/mcp/)
        - A MS Foundry agent configured to use the MCP tool
        - Is possible to connect to multiple MCP servers by 
            adding them to the agent as separate tools.
            - Parameters for the `MCPTool`
                - `server_label`
                    A unique identifier for the MCP server (e.g., GitHub).
                - `server_url`
                    The MCP server’s URL.
                - `allowed_tools` (optional)
                    A list of specific tools the agent is allowed to access.
                - `require_approval` (optional)
                    A boolean that determines whether tool invocations require human approval. 
                    If set to true, the agent will pause and wait for approval before invoking any 
                    tools on the MCP server.
            -  Custom headers
                - Authentication keys (API keys, OAuth tokens).
                - Other required headers for the MCP server

    - Invoking tools
        - Using the Azure MCP Tool object we don't need 
            - Wrap function tools
            - Invoke `session.call_tool`
        - Tools are automatically invoked during an agent run
        - Automatically invoke MCP tools
            - Create the `MCPTool` object with the server label and url.
            - Use `update_headers` to apply any headers required by the server.
            - Use the `require_approval` parameter to determine whether approval is required. 
                Supported values are:
                - always
                    A developer needs to provide approval for every call. 
                    If you don't provide a value, this one is the default.
                - never
                    No approval is required.
            - Create an agent and add the `MCPTool` object to its tools list
            - Invoke a prompt on the agent, you should see the results of any invoked tools in the response.
        - If the tool invoked has MCP server with approval required
            - You get an `mcp_approval_request` in the agent response
            - To approve use `mcp_approval_response` object with 
                - `approval_request_id` value
                - `approve` boolean

- **Key takeaways**
    - Dynamic Runtime Discovery
        Connecting an agent to a Model Context Protocol (MCP) server allows it to 
        discover and register tools dynamically at runtime.
        This eliminates the need to hardcode APIs or redeploy the agent when underlying tools change.
    - Automated Client-Side Mapping
        The MCP client acts as an intelligent bridge, automatically generating function wrappers from the 
        discovered tools and connecting them directly to the agent's execution layer.
    - Architectural Agility & Scalability
        This decoupled pattern ensures that AI solutions remain flexible and resilient. 
        The agent can seamlessly adapt to evolving toolsets and scale alongside growing enterprise 
        applications without breaking existing infrastructure.

- **Further reading**
    - [Model Context Protocol User Guide](https://modelcontextprotocol.io/introduction)
    - [Connect to Model Context Protocol servers](https://learn.microsoft.com/en-gb/azure/ai-foundry/agents/how-to/tools/model-context-protocol?view=foundry&preserve-view=true&pivots=python)

- **Exercise - Connect MCP tools to Azure AI Agents**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/03-mcp-integration.html)


### 4. [Build knowledge-enhanced AI agents with Foundry IQ](https://learn.microsoft.com/en-gb/training/modules/introduction-foundry-iq/)

- **Introduction**

    - The Scaling Challenge
        While organizations are eager to adopt AI agents to automate tasks, 
        they quickly hit a fundamental wall: 
        scaling agents beyond simple, predefined workflows.
    - The Value of Organizational Knowledge
        The true power of an AI agent is unlocked only when it can access 
        internal company data—such as policies, procedures, product documentation, and domain expertise.
    - Limitations of Traditional Agents
        Standard agents are restricted by knowledge cutoff dates, lack access to private data, and 
        produce generic responses or flat-out incorrect information (hallucinations) due to a lack of factual grounding.
    - Complex Engineering Hurdles
        Manually building knowledge-enabled agents requires teams to repeatedly tackle complex infrastructure challenges, 
        including data ingestion, chunking strategies, vector database maintenance, and access controls.
    - The Solution (Foundry IQ)
        MS Foundry IQ serves as a unified knowledge platform that eliminates the need to build custom 
        Retrieval-Augmented Generation (RAG) pipelines from scratch for every project, allowing multiple agents to 
        securely share and instantly benefit from centralized knowledge bases.
    - Objectives
        - Explain how RAG solves the knowledge problem by connecting agents to real-time information
        - Describe how Foundry IQ provides a shared knowledge platform that multiple agents can access
        - Configure data sources for knowledge bases including Azure AI Search, Blob Storage, SharePoint, and OneLake
        - Configure agent instructions to control retrieval behavior and ensure consistent citations
        - Test and monitor agent retrieval to maintain quality in production

- **Understanding RAG for agents**
    - Simple AI agent limitations
        | Limitation | Impact | Example |
        |:- |:-|:-|
        | Knowledge cutoff dates | No access to recent<br/> information | Can't help with newly released features or<br/> updated policies |
        | Private data access | Generic responses only | Missing company procedures, support knowledge,<br/> product specs |
        | Lack of context | Irrelevant advice | Ignores specific security requirements or<br/> approval workflows |
        | Fabricated responses | Compliance and security risks | Confident-sounding but<br/> incorrect information |
        | Scalability issues | Duplicated engineering effort | Every team rebuilds the same<br/> RAG infrastructure |

    - How RAG solves these problems
        - RAG process
            1. Retrieve
                System searches knowledge bases for 
                relevant content related to the query
            2. Augment
                Combines retrieved content with the 
                user's question to provide factual context
            3. Generate
                Agent creates response using both 
                training data and retrieved information
        - RAG advantages
            - Real-time updates 
                Keep agents current with policies and 
                procedures without requiring retraining
            - Source transparency
                Shows users exactly which documents informed each
                response to build trust and enable verification
            - Factual grounding
                anchors responses in actual organizational content to 
                eliminate fabricated information and ensure compliance

- **Explore Foundry IQ**

    - Challenges of build a RAG system
        - Configuring vector databases
        - Implementing embedding pipelines
        - Tuning retrieval algorithms
        - Maintaining search infrastructure

    - What is Foundry IQ?
        - Is a managed knowledge platform for AI agents
        - Is built on Azure AI Search
        - Provides the retrieval capabilities
        - Shared service (of  knowledge bases) that multiple agents can use
            To agents appears as one unified knowledge source
            For developers it means connecting data sources to knowledge bases

    - How knowledge bases organize information
        - Knowledge bases in Foundry IQ organize information by business domain
            - Like
                - Product Documentation
                - HR Policies
            - Not like
                - SharePoint Site A
                - Blob Container B
        - Example of a Product Documentation knowledge base
            - Technical specifications from SharePoint
            - API documentation from Azure Blob Storage
            - Usage analytics from OneLake
            - Support tickets from your existing search index

    - Connecting data sources
        - Foundry IQ connects &mdash; once per data source &mdash; to existing 
            storage through data source integrations
        - There's no need to write retrieval logic or 
            manage search infrastructure
        - Just point at
            - SharePoint sites
            - Blob containers
            - OneLake instances
        - Foundry IQ handles automatically
            - Indexing
            - Embedding generation
            - Search optimization

    - Built-in retrieval intelligence
        - When an agent queries a
            knowledge base, Foundry IQ
            - Analyzes the question to understand what 
                information the agent needs. 
                A question like "What's our return policy for damaged items?" requires 
                different retrieval than "List all return policies."
            - Selects retrieval strategies based on the query. 
                Simple factual questions use keyword search. 
                Complex questions combine semantic search with query expansion.
            - Ranks results using relevance scoring
                The most contextually appropriate information 
                surfaces first, reducing the tokens needed for agent responses.
            - Provides citations so agents can reference source documents.
                This builds trust and lets users verify information.

    - Connecting agents to knowledge
        - Example
            <pre><code>
                from azure.ai.projects        import AIProjectClient
                from azure.ai.projects.models import PromptAgentDefinition, MCPTool
                &nbsp;
                project_client = AIProjectClient(endpoint=project_endpoint, credential=credential)
                &nbsp;
                # Connect to the product documentation knowledge base
                knowledge_tool = MCPTool(
                    server_label="product-docs",
                    server_url=f"{search_endpoint}/knowledgebases/product-documentation/mcp"
                )
                &nbsp;
                # Create an agent with knowledge access
                agent = project_client.agents.create_version(
                    agent_name="product-support-agent",
                    definition=PromptAgentDefinition(
                        model="gpt-4o-mini",
                        instructions="Answer product questions using the knowledge base. Always cite your sources.",
                        tools=[knowledge_tool]
                    )
                )
            </code></pre>

    - The shared knowledge advantage
        - If the organization needs
            - A support agent answering customer questions
            - An employee assistant helping with HR policies
            - A developer agent explaining API usage
        - Traditional RAG need to build and maintain three retrieval systems
        - Foundry IQ create knowledge bases that multiple agents share
            - The Product Documentation knowledge base serves 
                both the support agent and developer agent
            - The HR Policies knowledge base serves 
                only the employee assistant
            - Each agent accesses exactly the knowledge it needs
        - <span>&#x1F4A1;</span>==Foundry IQ uses the Model Context Protocol (MCP) to 
        &nbsp;&nbsp;&nbsp;&nbsp;connect agents to knowledge bases. 
        &nbsp;&nbsp;&nbsp;&nbsp;MCP provides a standardized way for AI agents to access
        &nbsp;&nbsp;&nbsp;&nbsp;external tools and data sources securely.==

- **Configure data sources for knowledge bases**~

    - Foundry IQ supports six primary data source types
        | Data Source | Access Type | Best For |
        |:-|:-|:-|
        | Azure AI Search Index | Indexed | Enterprise search with custom pipelines |
        | Azure Blob Storage | Direct | Document files in Azure Storage |
        | Web | Real-time | Current, public information via Bing |
        | SharePoint (Remote) | Real-time | Live SharePoint content with MS 365 governance |
        | SharePoint (Indexed) | Indexed | Advanced search on SharePoint with custom pipelines |
        | OneLake | Direct | Unstructured data in MS Fabric|

    - Azure AI Search Index
        - Ideal when already invested in Azure AI Search and 
            want to use existing search indexes
        - Connect directly to your Azure AI Search index
        - Key benefits
            - Semantic ranking
                Finds contextually relevant results, not just keyword matches
            - Custom scoring
                Prioritizes results based on your business logic
            - Faceted navigation
                Filters results by categories or attributes
            - Multi-language support
                Handles content in different languages
        - <span>&#x1F4A1;</span>==Learn more about [Azure AI Search](https://learn.microsoft.com/en-gb/azure/search/search-what-is-azure-search)==

    - Azure Blob Storage
        - Retrieve documents and files directly from your blob containers
        - Is possible organize blobs into containers based on 
            topics or access levels
        - Common file types
            - PDF documents
            - MS Word files (.docx)
            - Text files (.txt)
            - Markdown files (.md)
            - HTML files
        - <span>&#x1F4A1;</span>==Blob Storage provides a more direct path from your files to your knowledge base==

    - Web
        - Grounds your agent with real-time content 
            from the internet via Bing
        - Agent can search for current information 
            when answering questions
        - Important when users ask about
            - Recent events or news
            - Current pricing or availability
            - Frequently changing information
            - Topics outside your internal knowledge base
        - You can combine web grounding with internal data sources, 
            using web access as a supplementary source when 
            internal knowledge doesn't provide an answer
        - <span>&#9888;</span> ==With web grounding, you're relying on Bing's search results, 
        &nbsp;&nbsp;&nbsp;&nbsp;which means less control over the specific sources your agent references. 
        &nbsp;&nbsp;&nbsp;&nbsp;When accuracy and source verification are critical, consider using indexed, 
        &nbsp;&nbsp;&nbsp;&nbsp;controlled data sources instead==

    - MS SharePoint options
        | Feature | Remote | Indexed |
        |:-|:-|:-|
        | Access method | Real-time queries | Preprocessed index |
        | Response time | Depends on SharePoint | Faster |
        | Maintenance | No index to maintain | Requires index updates |
        | Advanced search | Limited | Full Azure AI Search capabilities |
        | Data freshness | Always current | Depends on indexing schedule |
        | Permission handling | Respects SharePoint permissions | Configured during indexing |

    - SharePoint Remote
        - Provides search capabilities with MS 365 governance
        - Retrieves content directly from SharePoint without preindexing
        - Agent searches SharePoint sites and libraries in real-time
        - Benefits
            - No index maintenance required
            - Always accesses current SharePoint content
            - Automatically respects existing SharePoint permissions
            - Simpler setup and configuration
        - <span>&#x1F4A1;</span>==Use SharePoint Remote when you need the simplest path to 
        &nbsp;&nbsp;&nbsp;&nbsp;SharePoint data and don't require advanced search features==

    - SharePoint Indexed
        - Processes your SharePoint content in advance
        - Preprocessing means 
            - Faster response times
            - More sophisticated search capabilities
        - With indexed content
            - Apply custom analyzers for specialized terminology
            - Build enrichment pipelines with AI services
            - Combine SharePoint data with other sources
            - Create specialized search experiences
        - <span>&#x1F4A1;</span>==Indexed SharePoint works best when you need advanced search features or 
        &nbsp;&nbsp;&nbsp;&nbsp;when you're integrating SharePoint data with other sources in your Azure AI Search index. 
        &nbsp;&nbsp;&nbsp;&nbsp;SharePoint data and don't require advanced search features==

    - MS OneLake
        - Provides access to unstructured data 
            stored in your MS Fabric data lakehouse
        - This option matters when your organization uses 
            MS Fabric for data analytics and storage
        - The agent can reference this information when answering 
            business questions, providing data-driven responses grounded in 
            your organization's analytical work
        - Use cases
            - Business intelligence reports
                Reference analytical findings in agent responses
            - Data documentation
                Provide context about datasets and metrics
            - Analytical findings
                Share insights from data science work
            - Research outputs
                Make research accessible through conversational AI

    - Choose the right data source
        | If your data is... | And you need... | Choose... |
        |:-|:-|:-|
        |In SharePoint|Simple setup, always current|SharePoint Remote|
        |In SharePoint|Advanced search, custom pipelines|SharePoint Indexed|
        |Files in Azure|Direct file access|Azure Blob Storage|
        |In MS Fabric|Data lakehouse content|OneLake|
        |Already indexed|Existing Azure AI Search investment|Azure AI Search Index|
        |Public, current information|Real-time web content|Web|

    - <span>&#x1F4A1;</span>==You can combine multiple sources in a single knowledge base 
    &nbsp;&nbsp;&nbsp;&nbsp;use internal SharePoint data as the primary knowledge base 
    &nbsp;&nbsp;&nbsp;&nbsp;while enabling web grounding for current events or supplementary information==

- **Configure retrieval with Foundry IQ**

    - The retrieval behavior problem
        - Example
            - Question to agent
                "What's our vacation policy?"
            
            - Possible behaviors
                | Behavior | Example Response | Problem |
                |:-|:-|:-|
                |Answers from training data|"Most companies offer 2-3 weeks of<br/> vacation annually"|Generic information,<br/> not your actual policy|
                |Searches but doesn't cite|"You get 15 days of PTO annually"|Correct but unverifiable,<br/> no accountability|
                |Searches, cites, and grounds|"You receive 15 days of paid time off annually<br/>【doc_id:1†Employee Handbook 2024】"| This is what you want|

    - Controlling retrieval with instructions
        - Agent instructions determine retrieval behavior
        - Example
            <pre><code>
                agent = project_client.agents.create_version(
                    agent_name="hr-assistant",
                    definition=PromptAgentDefinition(
                        model="gpt-4o-mini",
                        instructions="Answer HR questions using the knowledge base.",
                        tools=[knowledge_tool]
                    )
                )
            </code></pre>
            - Instruction too vague
            - Doesn't specify _when_ to use or _how_ to present results

    - Writing effective retrieval instructions
        - Effective instructions specify three critical behaviors
            1. When to retrieve
                Tell the agent to always use the knowledge base, never rely on training data
            2. How to cite
                Specify the exact format for source attribution
            3. What to do when unsure
                Define fallback behavior when information isn't found
        - Example
            <pre><code>
                retrieval_instructions = """You are a helpful HR assistant.
                &nbsp;
                CRITICAL RULES:
                - You must ALWAYS search the knowledge base before answering any question
                - You must NEVER answer from your own knowledge or training data
                - Every answer must include citations in this format: 【doc_id:search_id†source_name】
                - If the knowledge base doesn't contain the answer, respond with "I don't have that information in our current documentation. Please contact HR directly at hr@company.com"
                &nbsp;
                Your role is to provide accurate, verifiable information from company documentation."""
                &nbsp;
                agent = project_client.agents.create_version(
                    agent_name="hr-assistant",
                    definition=PromptAgentDefinition(
                        model="gpt-4o-mini",
                        instructions=retrieval_instructions,
                        tools=[knowledge_tool]
                    )
                )
            </code></pre>
        - Result
            These instructions create consistent behavior
            1. The agent knows exactly when to search
            2. how to format responses
            3. what to do when information isn't available.

    - Testing retrieval behavior
        - Setting up a test conversation
            - Example
                <pre><code>
                openai_client = project_client.get_openai_client()
                conversation = openai_client.conversations.create()
                &nbsp;
                # Test query that should trigger retrieval
                response = openai_client.responses.create(
                    conversation=conversation.id,
                    input="How many vacation days do I get?",
                    extra_body={"agent": {"name": agent.name, "type": "agent_reference"}}
                )
                &nbsp;
                print(response.output_text)
                </code></pre>

    - What to test
        | Query Type | Example Questions | Expected Behavior |
        |:-|:-|:-|
        |Straightforward factual|"What is our vacation policy?"<br/>"Where can I find the security guidelines?"|Direct retrieval with citations|
        |Questions requiring<br/>synthesis|"What are the differences between our leave types?"<br/>"How do I request time off?"|Multiple document retrieval,<br/> synthesized answer with multiple citations|
        |Questions outside knowledge base|"What's the weather like today?"<br/>"Tell me about machine learning"|Graceful fallback<br/>("I don't have that information...")|
        |Ambiguous questions|"What about benefits?"<br/>"Tell me more about that"|Clarifying questions or focused search on most<br/> relevant topic|

    - Evaluating response quality
        Characteristics of good responses
        - Grounding
            Information comes from knowledge base, not training data
        - Citation
            Every factual claim includes source references
        - Relevance
            Retrieved content actually answers the question
        - Completeness
            All necessary information is provided, not just fragments

    - Retrieval strategies for 
        different agent types
        - Customer-facing support agents
            - Agents need high accuracy
            - Must never provide uncertain information
            - Example
                <pre>
                

                    support_instructions = """You provide customer support using our product documentation.

                    Rules:
                    - Search the knowledge base for every product question
                    - Cite documentation for all technical answers
                    - If documentation doesn't cover a question, say "Let me connect you with a specialist" rather than guessing
                    - Focus on official product information, not general knowledge"""
                </pre>
        - Internal research assistants
            - Can synthesize across documents
            - Provide broader context
            - Example
                <pre>
                

                    research_instructions = """You help employees research topics across company documentation.

                    Rules:
                    - Search all relevant knowledge bases for comprehensive answers
                    - Synthesize information from multiple sources when helpful
                    - Always cite all sources used
                    - Indicate confidence level when synthesizing across documents
                    - Suggest related topics that might be useful"""
                </pre>
        - Specialized domain experts
            - Focus deeply on specific knowledge domains
            - Example
                <pre>


                    compliance_instructions = """You are a compliance documentation assistant.

                    Rules:
                    - Only answer questions about compliance policies and procedures
                    - Always cite the specific policy document and section
                    - If a question involves interpretation or legal advice, refer to the compliance team
                    - Keep answers strictly factual based on written policies
                    - Note the effective date of any policy you reference"""
                </pre>

        - The pattern
            - Define the agent's scope 
            - Specify retrieval requirements
            - Establish citation standards
            - Handle edge cases explicitly

    - Moving from testing to production
        - New challenges
            - Users ask questions differently than your test scenarios
            - Some questions hit edge cases you didn't anticipate
            - Others reveal gaps in your knowledge base content

        - Patterns to track
            - Citation frequency
                Are agents consistently citing sources?
            - Fallback frequency
                How often do agents say "I don't know"?
            - Query types
                What categories of questions appear most often?
            - Retrieval accuracy
                Do retrieved documents actually contain answers?
        - Use this information to
            - Refine instructions
            - Improve knowledge base content
            - Adjust search configurations
        - <span>&#x1F4A1;</span>==Retrieval quality improves through iteration based on real-world usage==


- **Key takeaways**
    - RAG solves the knowledge problem
        - Connect agents to real-time knowledge sources
        - RAG-enabled agents 
            - Retrieve relevant information
            - Augment queries with factual context
            - Generate responses grounded in your organizational content
        - This provides
            - Real-time updates
            - Source transparency
            - Factual grounding
    - Foundry IQ provides a shared knowledge platform
        - Foundry IQ eliminates the need to b
            build custom RAG infrastructure for every agent
        - Create knowledge bases
            That any agent can access them
            - Organized by business domain
            - Connect data sources from
                - SharePoint
                - Azure Blob Storage
                - OneLake
                - Azure AI Search indexes
            - This shared approach scales knowledge 
                access across your organization
    - Data quality determines retrieval effectiveness
        Improve retrieval through three techniques
        - Scoring profiles
            Boost specific fields or 
            attributes to surface more relevant results
        - Semantic ranking
            Uses AI models to understand meaning and 
            context beyond keywords
        - Custom analyzers
            Handle specialized content like HTML, 
            product codes, or technical terminology
    - Instructions control agent behavior
        Effective agent instructions specify
        - When to retrieve
            Always use the knowledge base
        - How to cite
            Exact format for source attribution
        - What to do when unsure
            Graceful fallback
    - Next steps
        - Start with a high-value knowledge domain where accurate
            Cited information provides immediate business impact.
        - Build your first knowledge base
        - Configure data quality settings
        - Create an agent with clear retrieval instructions
        - Test systematically before deploying to users



- **Exercise - Integrate an AI agent with Foundry IQ**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/09-integrate-agent-with-foundry-iq.html)




### 5. [Integrate your agent with MS 365](https://learn.microsoft.com/en-gb/training/modules/integrate-foundry-agent-with-m365/)

- **Introduction**
    - The User Environment Gap
        While AI agents may perform perfectly in a testing environment like the 
        Foundry playground, friction occurs when users have to leave their 
        primary collaboration tools to interact with them.
    - Native Channels Integration
        MS Foundry solves this by providing built-in capabilities to 
        publish custom AI agents directly into MS Teams and 
        MS 365 Copilot.
    - Practical Workstream Deployment
        This allows you to surface specialized assistants—such as IT support desks, 
        HR onboarding companions, or domain-specific advisors—exactly where your team 
        already communicates and works.
    - Objectives
        Learn to navigate the publishing workflow in the Foundry portal, evaluate advanced 
        integration paths, and utilize Work IQ to grant agents secure access to MS 365 data sources, 
        including emails, meetings, and documents.

- **Understand Foundry agent publishing options**

    - Understanding agent applications
        Afteer publishing an agent Foundry creates an 
        **Agent Application** resource with
        - Dedicated invocation URL
            A stable endpoint that remains consistent as you update agent versions
        - Agent identity
            A distinct Microsoft Entra identity separate from your development project
        - User data isolation
             Inputs and interactions from one user aren't available to other users

    - Publishing to Microsoft 365
        - Creates an Azure Bot Service resource that routes messages between Microsoft 365 and your agent
        - Generates a Microsoft 365 publishing package for distribution
        - Registers a Microsoft Entra ID application for authentication
        - Makes your agent discoverable in the Teams agent store
    
    - Direct publishing from Foundry portal
        - Creates an Azure Bot Service resource in your subscription
        - Registers a Microsoft Entra ID application
        - Generates a Microsoft 365 publishing package
        - Prepares your agent for distribution
        - Ideal when you want to 
            - Deploy quickly
            - Keep your agent logic entirely within Foundry

    - Microsoft 365 Agents Toolkit
        - For complex scenarios
        - Use the Microsoft 365 Agents Toolkit to 
            create a proxy application that connects to your Foundry agent
        - When you need custom single sign-on (SSO)
        - Advanced middleware logic
        - Multi-environment deployment pipelines

    - Publish scopes
        | Scope | Description | Best for |
        |:-|:-|:-|
        | Shared | Available immediately without admin approval.<br/> Appears under Your agents in Teams. | Personal testing,<br/> small team pilots |
        | Organization | Available to everyone in your tenant under **Built by your org**.<br/> Requires admin approval. | Production deployments |

    - Other publishing channels
        - Web application preview
            Browser-based interface for demos and stakeholder testing
        - Stable API endpoint
            REST API for embedding in custom applications
        - Azure Bot Service channels
            Slack, Telegram, Twilio (SMS), Facebook, and others

    - Agent identity and permissions
        When you publish an agent, the 
        system creates a distinct agent identity
        - The agent authenticates to Azure resources using its own identity
        - Development-time permissions on your project identity don't transfer automatically
        - Tools that access Azure services need permissions reconfigured after publishing

    - Prerequisites for publishing to Microsoft 365
        - Azure AI Project Manager role on your Foundry project
        - Azure AI User role on the agent application scope
        - An Azure subscription where you can create Azure Bot Service resources
        - Permissions to register applications in Microsoft Entra ID
        - A Microsoft 365 tenant that allows custom apps and bots

- **Publish an agent from Foundry portal to Teams**

    - Before begin
        - Test your agent thoroughly
            - Use the Foundry playground
            - Test various user inputs
            - Confirm any configured tools work correctly
            - Check that responses are appropriate for your use case
        - Verify your permissions
            - Azure AI Project Manager role on your Foundry project to publish agents
            - Azure AI User role to invoke or chat with published agents
            - Permissions to create resources in your Azure subscription
            - Permissions to register applications in Microsoft Entra ID
        - Register the Bot Service provider
            - Ensure the `Microsoft.BotService` provider is 
                registered in your Azure subscription
            - Check in the Azure portal under subscription's **Resource providers** section
        - Prepare metadata
            - A display name for your agent (appears in the Teams agent store)
            - A brief description of what your agent does
            - Small (32x32 pixels) and large (192x192 pixels) icons in PNG format
            - Your organization's name and contact details
            - URLs for your privacy policy and terms of use
    
    - Publish your agent
        1. Select your agent version
            - Open the [Microsoft Foundry portal](https://ai.azure.com/) and navigate to your project.
            - Select the agent you want to publish from your agent list.
            - Review the agent configuration to confirm it's ready for publishing.
        2. Start the publishing process
            - Select **Publish** to open the publishing dialog.
            - Select **Publish** again, then choose **Publish to Teams and Microsoft 365 Copilot**.
            - The Microsoft 365 publishing configuration window opens.
        3. Configure Azure Bot Service
            - The portal automatically generates an application ID and tenant ID.
                Note these values for troubleshooting.
            - In the Azure Bot Service dropdown, 
                select Create an Azure Bot Service to provision a new bot resource.
            - Wait for the portal to create the Bot Service resource in your subscription.
        4. Complete the metadata
            | Field | Description |
            |:-|:-|
            | Name | Display name for your agent in the Teams store |
            | Description | Brief explanation of what your agent does |
            | Icons | Upload small and large PNG icons |
            | Publisher information | Your organization name and contact details |
            | Privacy policy | URL to your organization's privacy policy |
            | Terms of use | URL to your terms of service |
        5. Choose your publish scope
            - Shared scope
                Agent appears under "Your agents" in the store. 
                Available immediately. 
                Best for testing and small teams.
            - Organization scope
                Agent appears under "Built by your org" in the store. 
                Requires admin approval. 
                Best for production deployments.
        6. Prepare and optionally download the package
            - Select **Prepare Agent** to start packaging your agent.
            - Wait for the packaging process to complete (typically 1-2 minutes).
            - When ready, you can either:
                - **Download the package** to test locally before distribution
                - **Continue the in-product publishing flow** for direct distribution

    - Test the publishing package in Teams
        1. Open Microsoft Teams.
        2. Navigate to **Apps > Manage your apps > Upload an app**.
        3. Select **Upload a custom app** and choose the downloaded .zip file.
        4. Teams installs the app and shows it in your apps list.
        5. Open the agent and send a test message.
        6. Verify
            [ ] The agent responds to messages
            [ ] Response content is accurate and appropriate
            [ ] Response times are acceptable
            [ ] Any configured tools work correctly

    - Request admin approval for organization scope
        An admin must approve your agent before it's available organization-wide
        Once approved, the agent appears in the **Built by your org** section of the Teams agent store
        1. Direct your Microsoft 365 administrator to the Microsoft 365 admin center.
        2. Navigate to **Agents > All > Requested**.
        3. Find your agent in the list of pending requests.
        4. The administrator selects **Approve request and activate**.

    - Reassign permissions after publishing
        If your agent uses tools that access Azure resources, 
        you need to grant permissions to this new identity
        1. In the Foundry portal, go to your published agent and note the agent application's identity information.
        2. In the Azure portal, navigate to the resources your agent accesses 
            (for example, Azure AI Search, storage accounts, or Cosmos DB).
        3. Assign the appropriate RBAC roles to the published agent identity.

    - Update a published agent
        1. Make your changes in the Foundry portal.
        2. Test the changes in the Foundry playground.
        3. Repeat the publishing process to create a new package.
        4. For shared scope, upload the new package to Teams.
        5. For organization scope, the update might require re-approval depending on your organization's policies.

- **Advanced - Use Microsoft 365 Agents Toolkit**

    - When to consider the Agents Toolkit
        - When the agent requires custom single sign-on (SSO) configuration
        - When you need to add middleware logic for custom processing
        - Logging
        - Transformation between Teams and Foundry agent
        - Organizations that require multi-environment 
            deployment configurations
        - Advanced debugging capabilities with detailed tracing
        - Integrates with CI/CD pipelines
            - GitHub Actions
            - Azure DevOps

    - How the Agents Toolkit approach works
        - <pre>Teams/Copilot → Proxy App (Agents Toolkit) → Foundry Agent</pre>
        - The proxy application receives messages from 
            Teams or Copilot through Azure Bot Service
        - Processes them through custom configured middleware
        - Forwards the request to the Foundry agent
        - Returns the response through the same path
        - The proxy approach gives you control but 
            adds complexity to deployment.

    - Getting started with the Agents Toolkit
        - Standalone agent
            - Install the VS Code Microsoft 365 Agents Toolkit extension
            - Open the extension panel and select **Create a New Agent/App**
            - Choose **Custom Engine Agent** as the project type
            - The wizard guides you through configuration options
        - Connect to an existing Foundry agent
            - Configure the project to call your Foundry agent's endpoint
            - Set up authentication using the agent's credentials
            - Implement any middleware logic you need
        - Includes the Microsoft 365 Agents Playground
        - Test
        - Use the toolkit to provision Azure resources
        - Deploy your proxy application
        - Register it in Teams

    - Comparison summary
        | Aspect | Direct Foundry publishing | Agents toolkit proxy |
        |:-|:-|:-|
        |Setup time|Minutes|Hours to days|
        |Code required|None|Proxy application|
        |Customization|Limited|Extensive|
        |Debugging|Foundry portal|Full IDE debugging|
        |Best for|Standard deployments|Complex enterprise needs|

    - Learn more
        - [Microsoft 365 Agents Toolkit documentation](https://learn.microsoft.com/en-us/microsoftteams/platform/toolkit/overview-agents-toolkit)
        - [Create custom engine agents with the Agents Toolkit](https://learn.microsoft.com/en-us/microsoft-365/agents-sdk/create-new-toolkit-project-vsc)
        - [Microsoft 365 Agents SDK overview](https://learn.microsoft.com/en-us/microsoft-365/agents-sdk/agents-sdk-overview)

- **Access Microsoft 365 data with Work IQ**

    - What is Work IQ?
        - Is a command-line interface (CLI)
        - Is a server that connects AI assistants to Microsoft 365 Copilot data
        - Enables agents to query workplace information using NLP
        - Provides rich context that helps agents give more 
            relevant and accurate responses
        - With Work IQ, your agents can answer
            - "What did my manager say about the project deadline?"
            - "Find my recent documents about Q4 planning"
            - "Summarize today's messages in the Engineering channel"
            - "Who is working on Project Alpha?"
        - Work IQ accesses data across multiple Microsoft 365 services
            | Data type | Example capabilities |
            |:-|:-|
            | Emails | Search messages, find communications from specific people |
            | Meetings | Check calendar, retrieve meeting notes and decisions |
            | Documents | Find files in SharePoint and OneDrive, search content |
            | Teams messages | Summarize channel discussions, find specific conversations |
            | People | Identify team members, find collaborators on projects |

    - Understanding MCP servers
        - Work IQ is built on the Model Context Protocol (MCP)
        - An MCP server exposes capabilities that AI agents can use
        - Work IQ is an MCP server specifically designed for Microsoft 365 data
        - Capabilities
            - Tools
                Actions the agent can take, like searching for documents or sending messages
            - Resources
                Data sources the agent can query
            - Prompts
                Predefined templates for common queries

    - How Work IQ operates
        - CLI mode
            - Example
                <pre>workiq ask -q "What requirements did Sarah share about the authentication feature?"</pre>
            - Useful for
                - Quick queries during development
                - Scripts that need to retrieve workplace information
        - MCP server mode
            - Work IQ integrates with AI assistants (Github Copilot VS Code)
            - The AI assistant can automatically access workplace context when relevant
            - Example
                <pre>
                    If you're implementing a feature that was discussed in a recent meeting, 
                    your AI assistant can access that meeting context to provide more relevant suggestions
                </pre>

    - Installing Work IQ
        - Using `npm`
            <pre>
            # Global installation
            npm install -g @microsoft/workiq
            &nbsp;
            # Or run directly without installation
            npx -y @microsoft/workiq mcp
            </pre>
        - Using GitHub Copilot CLI as a plugin
            - Open GitHub Copilot CLI by running `copilot`.
            - Add the plugins marketplace (one-time setup): `/plugin marketplace add github/copilot-plugins`
            - Install Work IQ: `/plugin install workiq@copilot-plugins`
            - Restart Copilot CLI and start querying your Microsoft 365 data.
        - Using VS Code (as an MCP server)
            <pre>
            {
                "workiq": {
                    "command": "npx",
                    "args": [
                    "-y",
                    "@microsoft/workiq",
                    "mcp"
                    ],
                    "tools": [
                    "*"
                    ]
                }
            }
            </pre>
        - Before first use, accept the End User License Agreement
            <pre>
                workiq accept-eula
            </pre>
        
        - Prerequisites for Work IQ
            - Node.js installed on your machine (if using the CLI locally)
            - A Microsoft 365 subscription with a Copilot license
            - Administrative consent for the Work IQ application in your Microsoft Entra tenant
        
        - Security and data access
            - Permission-based access
                Work IQ can only access data you already have permission to view
            - No data storage
                Work IQ doesn't store your Microsoft 365 data
                It retrieves information on-demand
            - Enterprise security
                All data access follows your organization's security policies
            - Admin visibility
                Administrators can monitor and control Work IQ usage
            - When you query Work IQ
I               It accesses data through Microsoft Graph<br/>with your authenticated identity
                - You can't access documents you don't have permission to view
                - Queries are auditable by your organization
                - Data protection policies apply to Work IQ queries

        - Using Work IQ with agent development
            - CLI is useful
                - For quick, ad-hoc queries during development
                - For scripts
                - One-off queries
                - When you need quick answers without opening an IDE
                - Example
                    <pre><code>
                    # Find project context
                    workiq ask -q "What were the key decisions in last week's architecture review meeting?"
                    &nbsp;
                    # Understand requirements from documents
                    workiq ask -q "Summarize the requirements in the user portal spec document"
                    &nbsp;
                    # Check team communications
                    workiq ask -q "What has the engineering team discussed about the API changes?"
                    </code></pre>

            - MCP server approach
                - Example
                    - Ask Copilot: "What requirements did Sarah share about the authentication feature?"
                    - Copilot uses Work IQ's MCP tools to query your Microsoft 365 data
                    - You receive the answer in the chat without running any commands

- **Test and iterate your integrated agent**

    - Testing beyond the Foundry playground
        - Test your agent in Microsoft Teams to verify
            - The Teams user interface renders responses correctly
            - Authentication flows work as expected
            - Response times are acceptable in production
            - The published agent identity has necessary permissions
        - Testing with multiple users
            - Different users phrase questions differently
            - Fresh perspectives identify confusing responses
            - Test across differente Teams clients
                Reveal platform-specific issues
        - Common troubleshooting scenarios
            - Agent doesn't respond in Teams
                - Possible causes
                    - Azure Bot Service isn't running
                    - Bot Service configuration is incorrect
                    - Network issues between Teams and your agent
                - Resolution
                    - Verify the Bot Service resource exists in the Azure portal.
                    - Check Bot Service logs for errors.
                    - Confirm the agent is published and the package was uploaded correctly.
            - Tools work in Foundry but fail in Teams
                - Possible cause
                    - The published agent identity doesn't have the required permissions.
                - Resolution
                    - Find the published agent's identity in the Foundry portal.
                    - In the Azure portal, locate the resources your tools access.
                    - Assign appropriate RBAC roles to the published agent identity.
            - Users can't find the agent
                - Possible causes
                    - Wrong publish scope selected
                    - Admin approval pending (for organization scope)
                    - Tenant policies block custom apps
                - Resolution
                    - For shared scope
                        Share the direct link with users.
                    - For organization scope
                        Verify admin approval in the Microsoft 365 admin center.
                    - Check tenant settings for custom app permissions.
            - Slow response times
                - Possible causes
                    - Complex agent instructions requiring extended processing
                    - Tools that query large data sets
                    - Network latency
                - Resolution
                    - Simplify agent instructions where possible.
                    - Optimize tool configurations.
                    - Test from different network locations to isolate network issues.

        - Monitoring published agents
            - Check Foundry metrics
                Review these metrics regularly to<br/>spot trends that indicate problems
                - Request volume and patterns
                - Response times
                - Error rates
                - Tool invocation statistics
            - Review Application Insights
                - Trace individual conversations
                - Analyze error patterns
                - Measure end-to-end latency
                - Set up alerts for anomalies
            - Gather user feedback
                - Create a Teams channel or email address for agent feedback
                - Periodically review feedback to identify common problems
                - Use feedback to prioritize agent improvements
            - <span>&#x1F4A1;</span>==Keep a testing checklist specific to your agent.  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Document the key scenarios you test before each release to  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ensure consistent quality==

- **Key takeaways**
    - Omnipresent Deployment
        Bringing AI agents directly into Microsoft Teams and Microsoft 365 Copilot ensures they are 
        instantly accessible within the communication tools your users already occupy.
    - Automated Infrastructure Provisioning
        The direct publishing workflow inside the Foundry portal strips away backend complexity by 
        automatically configuring the Azure Bot Service and handling Microsoft Entra ID app 
        registrations behind the scenes.
    - Enterprise-Grade Customization
        While the portal handles standard deployments seamlessly, the Microsoft 365 Agents Toolkit is 
        available as a dedicated developer alternative for highly complex enterprise integration scenarios.
    - Targeted Distribution Scopes
        Lifecycle management is split into strategic rollout tiers—utilizing Shared scopes for safe, 
        localized team testing before escalating to Organization scopes for broad corporate distribution.
    - Access Control & Identity
    Managing agent identity properly is essential, ensuring the agent aligns perfectly with internal 
    Role-Based Access Control (RBAC) permissions so it never accesses data it shouldn't.
    - Contextual Grounding via Work IQ
    By leveraging the Model Context Protocol (MCP), Work IQ securely bridges your agent to live Microsoft 365 
    data ecosystems, giving it the operational context required to be genuinely useful.

- **Further reading**
    - [Publish agents to Microsoft 365 Copilot and Microsoft Teams](https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/publish-copilot)
    - [Microsoft Work IQ documentation](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/workiq-overview)
    - [Microsoft 365 Agents Toolkit overview](https://learn.microsoft.com/en-us/microsoftteams/platform/toolkit/overview-agents-toolkit)
    - [Agent identity concepts in Microsoft Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/agent-identity)


- **Exercise - Publish a Foundry agent to Teams**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/05a-m365-teams-integration.html)

- **Exercise - Work IQ - Workplace intelligence for AI agents**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/05b-work-iq-integration.html)


### 6. [Build agent-driven workflows using MS Foundry](https://learn.microsoft.com/en-gb/training/modules/build-agent-workflows-MS-foundry/)

- **Introduction**
    - The Multi-Agent Paradigm
        Modern AI solutions increasingly move away from isolated models 
        toward ecosystem environments where multiple specialized agents collaborate to 
        analyze inputs, make decisions, and take actions.
    - Orchestration & Governance
        Microsoft Foundry agent workflows provide the structural scaffolding needed to 
        manage these complex interactions, combining granular control flow with 
        essential runtime safeguards.
    - Low-Code Visual Canvas
        A visual workflow builder allows developers to model data movement, 
        define agent invocation logic, and deeply inspect intermediate execution paths and 
        runtime behaviors without writing extensive code.
    - The Automation vs. Safety Dilemma
        In high-volume scenarios like SaaS customer support—where manual review fails to scale but 
        full automation risks unpredictability—workflows strike a balance by mixing multi-agent 
        triaging, conditional routing, and human-in-the-loop escalation.

- **Understand Workflows**
    - Workflows in Foundry provide a way to orchestrate AI-driven actions 
        using a visual, declarative approach
    - A workflow consists of connected nodes, 
        where each node performs a specific function
        - Invoke agents
        - Evaluate conditions
        - Manage data
        - Communicate with users
    - These nodes form an execution path that determines 
        how requests move through the system
    - Arranging and configuring nodes, you control how 
        information flows and how decisions are made
    - Workflows has an advantage the is their ability to 
        coordinate multiple agents
        This orchestration enables more robust and 
        scalable automation
    - Workflows support patterns that balance automation with oversight
        - Can pause execution
        - Request human input
        - Escalate decisions

- **Identify Workflow Patterns**
    - Sequential workflow follows a fixed, step-by-step path
        - Works for pipelines and multi-stage processes
            - Validating input
            - Enriching data
            - Generating a final response
        - They are predictable
        - Easy to reason about
    - Human-in-the-loop workflow introduces pauses where user input or 
        approval is required
        - The workflow explicitly asks a question
        - Waits for a response
        - Resumes execution based on that input
        - Useful when automation must be 
            balanced with oversight
            - Approvals
            - Confirmations
            - Situations where missing context 
                needs to be provided by a person
    - Group chat workflow enables more dynamic 
        orchestration across multiple agents
        - Control can shift between agents based on 
            - Context
            - Rules
            - Intermediate results
        - Useful for scenarios where multiple specialized agents 
            collaborate to handle complex requests
            - Customer support
            - Multi-domain question answering.

- **Create workflows in Microsoft Foundry**
    - Main node types
        - Invoke
            - Invoke an AI agent
            - Create a new one
            - Agent nodes return
                - Free text responses
                - Structured outputs (e.g. JSON)
            - Used for
                - Classification
                - Reasoning
                - Recommendations
                - Any AI-driven task
        - Flow
            - Controls the workflows execution path
                Adapt dinamically to different inputs or situations
            - Include
                - If/Else
                    Branches execution based on conditions
                - Go To
                    Jumps to another node in the workflow
                - For each
                    Loops over a list of items, performing the
                    same action for each one
            - Data transformation
                Manipulates data and manags variables
                - Include
                    - Set Variable
                        Assigns a value to a variable for later use
                    - Reset Variable
                        Clears or reinitialize a variable
                    - Parse Value
                        Extracts specific data from struxtured outputs or
                        converts values to different formats
            - Basic chat
                Send messages to the user or
                asks questions to collect input
                Often paired with variables to capture responses
            - End
                Marks the conclusions of a workfloe
                Can return a final result or status

- **Add Agents to a Workflow**
    - Agents are the core reasoning components within Foundry workflow
    - Adding agents to workflow enables
        - AI-driven decision-making
        - Classification
        - Response generation
    - Each agent can be configured
        - Specific purpose
        - Model
        - Prompt
        - Set of tools
    - Insert agents with **Invoke agent** node
        allowing
        - Configure tools
        - Knowledge bases
        - Memory
        - Guardrails for the agent
    - Agents can be reused across multiple
        workflows
    - Structured outputs are useful when agent 
        responses drive control flow
        - Routing logic
        - Variable assignement
    - Define agent's output in the _Parameters_ of the
        **Details** tab of the **Invoke agent** editor
    - Variables allows agents to
        - Influence decisions
        - Trigger conditional branches
        - Provide input to other agents
    - Variable storage can be configures in the **Action<br/>settings** of the **Invoke agent** node

- **Apply Power Fx in Workflows**
    - Power Fx is the low-code, 
        Excel-like language that acts as the glue of a workflow.
        - Allows
            - Manipulate data
            - Evaluate conditions
            - Control the flow of execution

    - How formulas work
        - System variables
            Provide contextual information about the workflow or 
            conversation, such as the current activity, last message, or user info.
        - Local variables
            Store data captured or created during workflow execution and 
            can be used in subsequent nodes
        - Example
            - Convert a user's input to uppercase: `Upper(Local.Input)`
            - Check whether an agent's confidence score is above a threshold: `Local.Confidence > 0.8`
            - Sum values in a list or a column of records: `Sum(Local.ItemList, Amount)`

    - Conditions as decision points
        - Power Fx expressions are commonly used in 
            **If/Else** nodes to evaluate conditions and branch execution
        - Example
            A workflow might check an agent's confidence score to decide whether to 
            continue processing automatically or escalate to a human.

    - Loops for processing multiple items
        - **For-each** nodes use Power Fx to iterate over collections
        - Combining loops with variables and conditions, 
            workflows can handle lists of inputs ithout duplicating 
            nodes or logic

    - Power Fx formula examples
        | Purpose | Formula Example | Notes |
        |:-|:-|:-|
        |Convert text to<br/> uppercase|`Upper(Local.Input)`|Transforms a string to all caps|
        |Convert text to<br/> lowercase|`Lower(Local.Input)`|Transforms a string to all lowercase|
        |Get string length|`Len(Local.Input)`|Returns the number of characters in a string<br/>&nbsp;|
        |Conditional check|`Local.Confidence > 0.8`|Returns true/false; used in If/Else nodes<br/>&nbsp;|
        |If/Else logic|`If(Local.Confidence > 0.8, "Proceed", "Escalate")`|Returns one of two values depending on a condition<br/>&nbsp;|
        |Sum a list of<br/> numbers|`Sum([10, 20, 30])`|Adds up numbers in a simple list|
        |Sum a column in<br/> a table|`Sum(Local.ItemList, Amount)`|Adds up the Amount property of each record in a table|
        |Count items in a table<br/> or list|`Count(Local.ItemList)`|Returns the number of items|
        |Check if blank|`IsBlank(Local.Input)`|Returns true if variable or input is empty|
        |Check if empty<br/> table|`IsEmpty(Local.ItemList)`|Returns true if a table has no records|
        |Loop over items|`ForAll(Local.ItemList, Upper(Name))`|Applies a formula to each item in a list or table<br/>&nbsp;|
        |Concatenate text|`Concatenate(Local.FirstName, " ", Local.LastName)`|Joins multiple strings into one<br/>&nbsp;|
        
        <br/>

        <span>&#x1F4A1;</span>==For more information about the Power Fx language, visit the [Power Fx documentation](https://learn.microsoft.com/en-us/power-platform/power-fx/overview)==

- **Maintain Workflows in Microsoft Foundry**

    - YAML and visual representations
        - Visual canvas for
            - Deal for conceptual understanding
            - Tracing execution paths
            - Collaborating with others
        - YAML for
            - Advanced configuration
            - Version tracking
            - Integration with source control

    - Versioning
        - On save is created a new, immutable version
        - Provides a safety net
            - Review prior versions
            - Compare changes
            - Roll back to an earlier workflow 
                If a modification introduces errors
            - Collaboration
                Easier to track who made changes and why

    - Adding notes for maintainers
        - Notes
            - Provide context
            - Explain design decisions
            - Clarify variable usage

    - Best practices for refinement
        - Regularly reviewing workflows for unused or redundant nodes.
        - Ensuring structured agent outputs are consistently handled.
        - Documenting decisions and logic with notes.
        - Leveraging version history to track changes and validate updates.
        - By combining YAML editing, version control, and thoughtful documentation, 
            you ensure that workflows are robust, maintainable, and ready for enterprise use

- **Use workflows in code**

    - Invoke a workflow
        - Establish a connection to 
            Foundry project using the `AIProjectClient`
            - Handles authentication
            - Acess to OpenAI-compatible API
                - Executing conversations
                - Invoking workflows
        - Example
            <pre><code>
                # Reference a workflow created in the Foundry portal
                workflow_name = "triage-workflow"
                &nbsp;
                # Create a conversation context for the workflow
                conversation = openai_client.conversations.create()
                &nbsp;
                # Execute the workflow, passing input to drive the workflow logic
                stream = openai_client.responses.create(
                    conversation=conversation.id,
                    extra_body={"agent": {"name": workflow_name, "type": "agent_reference"}},
                    input="Users can't reset their password from the mobile app.",
                    stream=True,
                )
            </code></pre>
        - `input` parameter
            - A user question that agents analyze and respond to
            - A support ticket description for classification and routing
            - A data payload that triggers processing logic
            - An empty string that simply starts the workflow without specific input

    - Process workflow events
        - When streaming is enables, tha application
            receives events as the workflow executes
        - Example
            <pre><code>
                for event in stream:
                    if event.type == "response.completed":
                        print("Workflow completed:")
                        for message in event.response.output:
                            if message.content:
                                for content_item in message.content:
                                    if content_item.type == 'output_text':
                                        print(content_item.text)
                    if (event.type == "response.output_item.done") and event.item.type == ItemType.WORKFLOW_ACTION:
                        print(f"Action '{event.item.action_id}' completed with status: {event.item.status}")
            </code><pre>
        - Common event types
            | Event type | Description |
            |:-|:-|
            | `response.completed` | The workflow finished executing and returned a final response |
            | `response.output_item.done` | An individual output item (such as a workflow action) completed |
        - Real-Time Visibility & Event Tracking
            Monitor workflow event streams to observe progress live or 
            trigger external system actions dynamically based on 
            changes in the workflow state.
        - Flexible Consumption Options
            Choose between streaming execution data in real time or 
            awaiting total workflow completion to process a single, consolidated final response.
        - Human-in-the-Loop Orchestration
            Handle execution pauses natively when a workflow reaches a step requiring manual 
            verification, user input, or explicit approval.
        - Seamless Execution Resumption
            Easily restart a paused workflow by sending targeted input messages directly back into the 
            conversation thread to fulfill the pending request.

    - Benefits of code integration
        | Scenario | Benefit |
        |:-|:-|
        |Web applications|Embed AI-driven workflows directly in user-facing apps|
        |APIs and microservices|Expose workflow capabilities through REST endpoints|
        |Batch processing|Invoke workflows programmatically for bulk operations|
        |Testing and validation|Automate workflow testing as part of CI/CD pipelines|
        |Custom interfaces|Build specialized UIs tailored to specific workflow use cases|

- **Key takeaways**
    - Workflow Composition & Orchestration
        - Node-Based Architecture
            Workflows are structured by sequencing diverse nodes &mdash; including agents, 
            logic, data transformation, and chat &mdash; to seamlessly orchestrate AI reasoning and 
            user interactions.
        - Data-Driven Decisions
            Agents generate structured outputs captured in variables, which are 
            then used to dynamically drive runtime routing, escalation paths, or workflow continuation.
        - The Integration & Execution Layer
            - Power Fx as Low-Code "Glue"
                The platform utilizes Power Fx to transform data, 
                evaluate complex logic conditions, and handle iterative 
                tasks through loops without heavy coding requirements.
            - Adaptive Intelligence
                The fluid movement of data through variables, conditions, and 
                loops enables the system to exhibit highly flexible and context-aware behavior at runtime.
        - Enterprise Maintenance & Lifecycle
            - Dual-Representation Design
                Systems maintain a visual design canvas alongside a YAML representation, ensuring that 
                workflows are equally accessible to business analysts and developers.
            - Long-Term Reliability
            Incorporating rigorous versioning practices and inline notes guarantees that complex enterprise 
            automation solutions remain reliable, transparent, and scalable.
        - <span>&#x1F4A1;</span>==For more information about workflows in Microsoft Foundry, visit [Create a workflow documentation.](https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/workflow)==

- **Exercise - Create an Agent-driven Workflow**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/06-build-workflow-ms-foundry.html)

### 7. [Develop an AI agent with MS Agent Framework](https://learn.microsoft.com/en-gb/training/modules/develop-ai-agent-with-semantic-kernel/)

- **Introduction**

    - Core Concepts of AI Agents
        - Dynamic Decision-Making
            Unlike rigid, traditional software, AI agents leverage generative AI and 
            LLMs to interpret data, make independent decisions, and automate complex 
            workflows with minimal human intervention.
    - The Microsoft Agent Framework
        - Open-Source & Multi-Provider Support
            This open-source SDK simplifies model integration by supporting a wide array of 
            agent ecosystems, including Microsoft Foundry, Azure OpenAI, OpenAI, 
            Microsoft Copilot Studio, and Anthropic.
        - Flexibility & Consistency
            The framework adds architectural flexibility and scalability, ensuring consistency 
            across your entire implementation if your solution requires mixing different types of agents.
        - Multi-Agent Orchestration
            It features built-in workflow coordination capabilities, making it the ideal foundation for 
            building complex solutions where multiple collaborative agents must work together.
    - Microsoft Foundry Agent Service
        - Fully Managed Infrastructure
            Offers an enterprise-grade platform to build, deploy, and scale agents securely. 
            It completely removes operational overhead, meaning developers do not need to 
            manage underlying compute or storage resources.
        - Rapid Development
            When combined with the Agent Framework, developers can spin up solutions with advanced 
            natural language processing and built-in tools using just a few lines of code.

    - Practical Application
        - Functional Extensibility
            By utilizing the framework's "tools and functions" capabilities, agents can interact directly 
            with external APIs and retrieve external data to execute real-world tasks.
        - End-to-End Workflow Example: A practical scenario includes an agent that automatically extracts data 
            from submitted employee expense reports, structures the formatting correctly, and handles the email 
            routing to appropriate recipients.

- **Understand Microsoft Agent Framework AI agents**

    - Microsoft Agent Framework core components
        - Agents
            - Provides a consistent interface
            - Enables different features like multi-agent orchestration. 
            - Out of the box, agents support 
                - Function calling
                - Multi-turn conversations with chat history, 
                - Service-provided tools
                - Structured outputs
                - Streaming responses.
        - Chat providers
            - Provides abstractions for connecting to AI services from different providers under a common interface. 
            - Supported providers
                - Azure OpenAI
                - OpenAI
                - Anthropic
                - Copilot
                - More through the BaseAgent abstraction.
        - Function tools
            - Containers for custom functions that extend agent capabilities.
            - Agents can automatically invoke functions to integrate with external APIs and services.
        - Built-in tools
            - Prebuilt capabilities
                - Code Interpreter for Python execution
                - File Search for document analysis
                - Web Search for internet access.
        - Conversation management
            Structured message system with roles (USER, ASSISTANT, SYSTEM, TOOL) and AgentSession for persistent conversation context across interactions.
        - Workflow orchestration
            Supports sequential workflows, concurrent execution, group chat, and handoff patterns for complex multi-agent collaboration.

    - What Is a Microsoft Foundry Agent?
        - Enterprise-level capabilities
            Built for Azure environments with advanced AI features 
            including code interpreter, 
            function tools integration, and 
            Model Context Protocol (MCP) support.
        - Automatic tool invocation
            Agents can automatically call and execute tools, 
            integrating seamlessly with Azure AI Search, 
            Azure Functions, and other Azure services.
        - Thread and conversation management
            Provides built-in mechanisms for managing persistent conversation 
            states across sessions, ensuring smooth multi-agent interactions.
        - Secure enterprise integration
            Enables secure and compliant AI agent development with Azure CLI 
            authentication, RBAC, and customizable storage options.

    - Agent framework core concepts
        - BaseAgent
            The foundation for all agents with consistent methods, 
            providing a unified interface across all agent types.
        - Agent session
            Manage persistent conversation context and store conversation history 
            across sessions using the AgentSession class.
        - Chat messages
            Organized structure for agent communication using role-based messaging 
            (USER, ASSISTANT, SYSTEM, TOOL) that enables smooth communication and integration.
        - Workflow orchestration
            Supports sequential workflows, running multiple agents in parallel, group conversations 
            between agents, and transferring control between specialized agents.
        - Multi-modal support
            Allows agents to work with text, images, and structured outputs, including vision capabilities and 
            type-safe response generation.
        - Function tools
            Let you add custom capabilities to agents by including custom functions with automatic schema 
            generation from Python functions.
        - Authentication methods
            Supports multiple authentication methods including Azure CLI credentials, API keys, 
            Microsoft Authentication Library (MSAL) for Microsoft business authentication, and 
            role-based access control.

- **Create an Azure AI agent with Microsoft Agent Framework**

    - Creating an Azure AI Agent
        1. Create a Microsoft Foundry project.
        2. Add the project connection string to your Microsoft Agent Framework application code.
        3. Set up authentication credentials with `AzureCliCredential`.
        4. Connect to your project client with the `AzureOpenAIResponsesClient` class.
        5. Create an `Agent` instance with the client, instructions, and tools you want to use.

    - Azure AI Agent key components
        - AzureOpenAIResponsesClient
            Manages the connection to your Microsoft Foundry project. 
            This client lets you access the services and models associated with your project and 
            provides enterprise-level authentication and security features.
        - Agent
            The main agent class that combines the client, instructions, and tools to create a 
            working AI agent that can handle conversations and complete tasks.
        - AgentSession
            Automatically keeps track of conversation history between agents and users, and 
            manages the conversation state.
            You can create new threads or reuse existing ones to maintain context across interactions.
        - Tools integration
            Support for custom functions that extend agent capabilities. 
            Functions are automatically registered and can be called by agents to connect with external APIs and services.
        - Authentication credentials
            Supports Azure CLI credentials, service principal authentication, and other Azure identity options for 
            secure access to Foundry Tools.
        - Thread management (AgentThread)
            Provides flexible options for thread creation, including automatic thread creation for simple scenarios and 
            explicit thread management for ongoing conversations.

- **Add tools to Azure AI agent**

    - How to use tools with Microsoft Foundry Agent
        - Built-in tools<br/>(without any extra setup)
            - Code Interpreter
                Executes Python code for calculations, data analysis, and more
            - File Search
                Searches through and analyzes documents
            - Web Search
                Retrieves information from the internet
    - Custom function tools
        - Key concepts
            1. Use the tool decorator
                Create a custom function tool by defining a Python function and
                decorating it with the `@tool` decorator from the Microsoft Agent Framework. 
                This decorator registers your function as a tool that the AI can call. 
                The `@tool` decorator includes parameters for providing a name and 
                description for your tool, as well as the `approval_mode` to specify whether 
                tool calls require approval.
            2. Function definition and annotations
                Create your tool by defining a regular Python function with proper type annotations. 
                Use `Annotated` and `Field` from Pydantic to provide detailed descriptions that help the AI 
                understand the function's purpose and how to use its parameters. 
                The more descriptive your annotations, the better the AI can understand when and how to call your function.
            3. Adding tools to your agent
                Pass your custom functions to the ChatAgent during creation using the `tools` parameter. 
                You can add a single function or a list of multiple functions. 
                The framework automatically registers these functions and makes them available for the AI to call.
            4. Tool invocation through conversation
                Once your tools are registered with the agent, you don't need to manually invoke them. 
                Instead, ask the agent questions or give it tasks that would naturally require your tool's functionality. 
                The AI automatically determines when to call your tools based on the conversation context and 
                the tool descriptions you provided.
            5. Multiple tools and orchestration
                You can add multiple tools to a single agent, and the AI automatically chooses which tool to use based on 
                the user's request. 
                The framework handles the orchestration, calling the appropriate functions and combining their results to 
                provide a comprehensive response.

    - Best practices for tool development
        - Clear descriptions
            Write clear, detailed descriptions for your functions and parameters to help the AI understand their purpose
        - Type annotations
            Use proper Python type hints to specify expected input and output types
        - Error handling
            Implement appropriate error handling in your tool functions to gracefully handle unexpected inputs
        - Return meaningful data
            Ensure your functions return data that the AI can effectively use in its responses
        - Keep functions focused
            Design each tool to handle a specific task rather than trying to do too many things in one function


- **Exercise - Develop an Azure AI agent with the Microsoft Agent Framework SDK**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/06-build-workflow-ms-foundry.html)

### 8. [Orchestrate a multi-agent solution using the MS Agent Framework](https://learn.microsoft.com/en-gb/training/modules/orchestrate-semantic-kernel-multi-agent-solution/)

- **Introduction**
    - A multi-agent system could consist of four 
        specialized agents working collaboratively
        - **Monitoring Agent** 
            Continuously ingests logs and metrics, detects anomalies using<br/>natural language processing (NLP), and triggers alerts when issues arise.
        - **Root Cause Analysis Agent** 
            Correlates these anomalies with recent system changes, using<br/> machine learning models or predefined rules to pinpoint the root cause of the problem.
        - **Automated Deployment Agent** 
            Takes over to implement fixes or roll back problematic changes by<br/> interacting with CI/CD pipelines and executing deployment scripts.
        - **Reporting Agent** 
            Generates detailed reports summarizing the anomalies, root causes, and<br/> resolutions, and notifies stakeholders via email or other communication channels.

- **Understand the Microsoft Agent Framework**
    - What is the Microsoft Agent Framework?
        Is designed to help developers build AI-powered agents that can process user inputs,
        make decisions, and execute tasks autonomously by leveraging large language models and
        traditional programming logic
        - Core concepts
            - Agents
                Agents are intelligent, AI-driven entities capable of reasoning and 
                executing tasks. 
                They use large language models, tools, and conversation history to 
                make decisions dynamically and respond to user needs.
            - Agent orchestration
                Multiple agents can collaborate towards a common goal using different
                orchestration patterns.
                The Microsoft Agent Framework supports several orchestration patterns with a 
                unified interface for construction and invocation, allowing you to easily switch 
                between patterns without rewriting your agent logic.
        - Agent functionality
            - Chat clients
                Chat clients provide abstractions for connecting to AI services from different
                providers under a common interface. 
                Supported providers include Azure OpenAI, OpenAI, Anthropic, and more 
                through the `BaseChatClient` abstraction.
            - Tools and function integration
                Tools enable agents to extend their capabilities through custom functions and 
                built-in services. 
                Agents can automatically invoke tools to integrate with external APIs, execute 
                code, search files, or access web information. 
                The framework supports both custom function tools and built-in tools like 
                Code Interpreter, File Search, and Web Search.
            - Conversation management
                Agents can maintain conversation history across multiple interactions using 
                `AgentSession`, allowing them to track previous interactions and adapt 
                responses accordingly. 
                The structured message system uses roles (USER, ASSISTANT, SYSTEM, TOOL) 
                for persistent conversation context.

    - Why you should use the Microsoft Agent Framework
        - **Build autonomous AI agents faster**
            Using a structured framework designed for intelligent, task-oriented workflows.
        - **Support multi-agent collaboration**
            Allowing specialized agents to work together on complex business processes.
        - **Integrate agents from multiple sources**
            Including Microsoft Foundry Agent Service and other AI ecosystems.
        - **Enable human-in-the-loop interactions**
            Where AI agents assist users with insights, recommendations, and automation while keeping humans in control.
        - **Automate repetitive and operational tasks**
            To improve efficiency and reduce manual effort.
        - **Orchestrate sophisticated workflows**
            By assigning different responsibilities to different agents, such as data gathering, analysis, and decision-making.
        - **Remain provider-agnostic**
            Making it possible to switch AI providers without rewriting application logic.
        - **Increase flexibility and adaptability**
            For evolving AI strategies and enterprise requirements.
        - **Scale from simple chatbots to enterprise-grade AI systems**
            Using the same framework architecture.
        - **Simplify development and maintenance**
            Through a unified platform for managing collaborative AI solutions.

- **Understand agent orchestration**

    - Why multi-agent orchestration matters
        - Assign distinct skills, responsibilities, or perspectives to each agent.
        - Combine outputs from multiple agents to improve decision-making and accuracy.
        - Coordinate steps in a workflow so each agent’s work builds on the last.
        - Dynamically route control between agents based on context or rules.

    - Understand workflows in the Microsoft Agent Framework
        - **Workflows**
            Structured sequences of steps used to complete a task
        - Can include one or more **AI agents**
        - Can include other components
        - Enable **multi-agent orchestration**
        - Support **checkpointing** to save and 
            resume workflow states

    - Core Components of a Workflow
        - Executors
            - Executors are the main workers in a workflow
            - Recieve input messages
            - Perform specific actions
            - Produce outputs that mov workflow toward
                completing its goal
            - Represent **AI agents** or **custom logic** components
            - Example
                <pre>
                One executor could analyze a travel request, 
                while another books the flight or hotel 
                based on the results
                </pre>
        - Edges
            - Define **how** messages flow between executors
            - Determine the logic and order of execution
            - Type of edges supported
                - Direct edges
                    - Connect one executor directly to another in sequence
                    - Example
                        <pre>
                        After an AI agent gathers user input, the next executor processes the booking.
                        </pre>
                - Conditional Edges
                    - Trigger only when certain conditions are met
                    - Example
                        <pre>
                        If hotel rooms are unavailable, the workflow branches to an 
                        executor that suggests alternative dates or locations
                        </pre>
                - Switch-Case Edges
                    - Route messages to different executors based on 
                        predefined conditions
                    - Example
                        <pre>
                        VIP customers might be routed to a premium service executor, 
                        while others follow the standard process
                        </pre>
                - Fan-Out Edges
                    - Send a single message to multiple 
                        executors simultaneously
                    - Example
                        <pre>
                        One request could be sent to several agents -
                        - one checking flights, another checking hotels
                        </pre>
                - Fan-In Edges
                    - Combine multiple messages from different executors 
                        into one for a final step
                    - Example
                        <pre>
                        After gathering hotel and flight results, a 
                        summary executor compiles them into a single travel itinerary
                        </pre>
        - Events
            - Includes built-in events to improve **observability** and 
                **debugging** during workflow execution
            - Bring structure, flexibility, and transparency to agent-driven applications
            - Help developers monitor 
                - Progress
                - Track errors
                - Analyze system performance
            - Examples
                | Event Name | Description |
                |:-|:-|
                |WorkflowStartedEvent|Triggered when workflow execution begins|
                |WorkflowOutputEvent|Emitted when the workflow produces an output|
                |WorkflowErrorEvent|Occurs when an error is encountered|
                |ExecutorInvokeEvent|Fired when an executor starts processing a task|
                |ExecutorCompleteEvent|Fired when an executor finishes its work|
                |RequestInfoEvent|Logged when an external request is issued|

        - Supported orchestration patterns
            - Concurrent orchestration
                Broadcast the same task to multiple agents at once and collect their results independently. 
                Useful for parallel analysis, independent subtasks, or ensemble decision making.
            - Sequential orchestration
                Pass the output from one agent to the next in a fixed order. 
                Ideal for step-by-step workflows, pipelines, and 
                progressive refinement.
            - Handoff orchestration
                Dynamically transfer control between agents based on context or rules. 
                Great for escalation, fallback, and expert routing where one 
                agent works at a time.
            - Group chat orchestration
                Coordinate a shared conversation among multiple agents (and optionally a human),
                managed by a chat manager that chooses who speaks next.
                Best for brainstorming, collaborative problem solving, and building consensus.
            - Magentic orchestration
                A manager-driven approach that plans, delegates, and adapts across specialized agents. 
                Suited to complex, open-ended problems where the solution path evolves.

    - A unified orchestration workflow
        1. Define your agents and describe their capabilities.
        2. Select and create an orchestration pattern, optionally adding a manager agent if needed.
        3. Optionally configure callbacks or transforms for custom input and output handling.
        4. Start a runtime to manage execution.
        5. Invoke the orchestration with your task.
        6. Retrieve results in an asynchronous, nonblocking way.

- **Use concurrent orchestration**

    - What is concurrent orchestration
        - Lets multiple agents work on the same task at the same time
        - Each agent handles the task independently
        - Then their outputs are gathered and combined
        - Works well when you want diverse approaches or solutions
            - Brainstorming
            - Group decision-making
            - Voting
        - When you need different approaches or ideas to solve the same problem
        - All agents work at the same time
        - Speeds up the process and covers the problem from many angles
        - Usually, the results from each agent are combined to create a final answer, 
            but this isn’t always necessary
        - Agent can also produce its own separate result
    
    - When to use concurrent orchestration
        - When tasks can run at the same time, 
            either by using a fixed group of agents or by 
            selecting AI agents dynamically based on what the task needs.
        - When the task benefits from different specialized skills or 
            approaches (for example, technical, business, or creative) that 
            all work independently but contribute to solving the same problem.
        - Common in multi-agent decision-making methods
            - Brainstorming ideas
            - Combining different reasoning methods (ensemble reasoning)
            - Making decisions based on voting or consensus (quorum)
            - Handling tasks where speed matters and running agents in parallel cuts down wait time

    - When to avoid concurrent orchestration
        - Agents need to build on each other's work or depend on 
            shared context in a specific order.
        - The task requires a strict sequence of steps or predictable, 
            repeatable results.
        - Resource limits, like model usage quotas, make running agents in 
            parallel inefficient or impossible.
        - Agents can't reliably coordinate changes to shared data or 
            external systems while running at the same time.
        - There's no clear way to resolve conflicts or contradictions between 
            results from different agents.
        - Combining results is too complicated or ends up 
            lowering the overall quality.

    - Implement concurrent orchestration
        1. Create your chat client
            Set up a chat client (for example, `AzureOpenAIChatClient`) with 
            appropriate credentials to connect to your AI service provider.
        2. Define your agents
            Create agent instances using the chat client's `create_agent` method. 
            Each agent should have specific instructions and a name that defines 
            its role and expertise area.
        3. Build the concurrent workflow
            Use the `ConcurrentBuilder` class to create a workflow that can run 
            multiple agents in parallel. 
            Add your agent instances as participants using the `participants()` method, then call `build()` to create the workflow.
        4. Run the workflow
            Call the workflow's `run` method with the task or input you want the agents to work on. 
            The workflow runs all agents concurrently and returns events containing the results.
        5. Process the results
            Extract the outputs from the workflow events using `get_outputs()`. 
            The results contain the combined conversations from all agents, 
            with each agent's response included in the final output.
        6. Handle the aggregated responses
            Process the aggregated messages from all agents. 
            Each message includes the author name and content, allowing you to 
            identify which agent provided each response.

- **Use sequential orchestration**

    - What is sequential orchestration
        - Agents are arranged in a pipeline where each agent 
            processes the task one after another
        - The output from one agent becomes the input for the next
        - Is ideal for workflows where each step depends on the previous one
            - Document review
            - Data transformation pipelines
            - Multi-stage reasoning

    - When to use sequential orchestration
        - Processes made up of multiple steps that must happen in a specific order, 
            where each step relies on the one before it.
        - Data workflows where each stage adds something important that the next stage 
            needs to work properly.
        - Tasks where stages can't be done at the same time and must run one after another.
        - Situations that require gradual improvements, like drafting, reviewing, and polishing content.
        - Systems where you know how each agent performs and can handle delays or 
            failures in any step without stopping the whole process.

    - When to avoid sequential orchestration
        - Stages can be run independently and in parallel without affecting quality.
        - A single agent can perform the entire task effectively.
        - Early stages may fail or produce poor output, and 
            there's no way to stop or correct downstream processing based on errors.
        - Agents need to collaborate dynamically rather than hand off work sequentially.
        - The workflow requires iteration, backtracking, or dynamic routing based on 
            intermediate results.

    - Implement sequential orchestration
        1. Create your chat client
            Set up a chat client (for example, `AzureOpenAIChatClient`) with 
            appropriate credentials to connect to your AI service provider.
        2. Define your agents
            Create agent instances using the chat client's `create_agent` method. 
            Each agent should have specific instructions and a name that defines its role and 
            expertise area in the pipeline.
        3. Build the sequential workflow
            Use the `SequentialBuilder` class to create a workflow that executes agents one after another. 
            Add your agent instances as participants using the `participants()` method, then call `build()` to create the workflow.
        4. Run the workflow
            Call the workflow's `run_stream` method with the task or input you want the agents to work on. 
            The workflow processes the task through all agents sequentially, with each agent's output becoming input for the next.
        5. Process the workflow events
            Iterate through the workflow events using an async loop. 
            Look for `WorkflowOutputEvent` instances, which contain the results from the sequential processing.
        6. Extract the final conversation
            Collect the final conversation from the workflow outputs. 
            The result contains the complete conversation history showing how each agent in the 
            sequence contributed to the final outcome.

- **Use group chat orchestration**

    - What is group chat orchestration
        - A collaborative conversation among multiple AI agents
        - Optionally a human participant
        - A central chat manager controls the flow
            - Which agent responds next
            - When to request human input
        - Useful for
            - Simulating meetings
            - Debates
            - Collaborative problem-solving
            - Human-in-the-loop setups where a human 
                may guide or intervene in the conversation
            - Agents in this pattern don't directly 
                change running systems

    - When to use group chat orchestration
        - Spontaneous or guided collaboration among agents (and possibly humans)
        - Iterative maker-checker loops where agents take turns creating and reviewing
        - Real-time human oversight or participation
        - Transparent and auditable conversations since all output is collected in a single thread
        - Common scenarios
            - Creative brainstorming where agents build on each other's ideas
            - Decision-making that benefits from debate and consensus
            - Complex problems requiring cross-disciplinary dialogue
            - Quality control and validation requiring multiple expert perspectives
            - Content workflows with clear separation between creation and review

    - When to avoid group chat orchestration
        - Simple task delegation or straightforward linear pipelines suffice
        - Real-time speed requirements make discussion overhead impractical
        - Hierarchical or deterministic workflows are needed without discussion
        - The chat manager can't clearly determine when the task is complete
        - Managing conversation flow becomes too complex, especially with many agents 
            (limit to three or fewer for easier control)

    - Maker-checker loops
        - One agent (the maker) proposes content or solutions
        - Another agent (the checker) reviews and critiques them
        - Checker can send feedback back to the maker
        - This cycle repeats until the result is satisfactory
        - Requires a turn-based sequence managed by the chat manager

    - Implement group chat orchestration
        1. Create your chat client
            Set up a chat client (for example, `AzureOpenAIChatClient`) with 
            appropriate credentials to connect to your AI service provider.
        2. Define your agents
            Create agent instances using the chat client's `create_agent` method. 
            Each agent should have specific instructions and a name that defines its role and expertise area.
        3. Build the group chat workflow
            Use the `GroupChatBuilder` class to create a workflow that can run multiple agents in parallel. 
            Add your agent instances as participants using the `participants()` method, then call `build()` to create the workflow.
        4. Run the workflow
            Call the workflow's run method with the task or input you want the agents to work on.
            The workflow runs all agents concurrently and returns events containing the results.
        5. Process the results
            Extract the outputs from the workflow events using `get_outputs()`. 
            The results contain the combined conversations from all agents, with each agent's 
            response included in the final output.
        6. Handle the aggregated responses
            Process the aggregated messages from all agents. 
            Each message includes the author name and content, allowing you to identify which agent provided each response.

    - Customizing the group chat manager
        - Create a custom group chat manager by extending the base `GroupChatManager` class
        - Lets you control
            - How conversation results are filtered or summarized
            - How the next agent is selected
            - When to request user input
            - When to terminate the conversation
        - Custom managers let you implement specialized logic tailored to your use case

    - Group chat manager call order
        1. `should_request_user_input`
            Checks if human input is needed before the next agent responds.
        2. `should_terminate`
            Determines if the conversation should end (for example, max rounds reached).
        3. `filter_results`
            If ending, summarizes or processes the final conversation.
        4. `select_next_agent`
            If continuing, chooses the next agent to speak.
        5. This ensures user input and termination conditions are handled before 
            moving the conversation forward

- **Use handoff orchestration**

    - What is handoff orchestration
        - Lets AI agents transfer control to one another based on the 
            task context or user requests
        - Is ideal for customer support, expert systems, or any situation 
            where dynamic delegation is needed
        - Fits scenarios where the best agent isn't known upfront or 
            where the task requirements become clearer during processing

    - When to use handoff orchestration
        - Tasks need specialized knowledge or tools, but the number or order of agents can't be determined in advance.
        - Expertise requirements emerge dynamically during processing, triggering task routing based on content analysis.
        - Multiple-domain problems require different specialists working sequentially.
        - You can define clear signals or rules indicating when an agent should transfer control and to whom.

    - When to avoid handoff orchestration
        - The involved agents and their order are known upfront and fixed.
        - Task routing is simple and rule-based, not needing dynamic interpretation.
        - Poor routing decisions might frustrate users.
        - Multiple operations must run at the same time.
        - Avoiding infinite handoff loops or excessive bouncing between agents is difficult.

    - Implementing handoff orchestration
        1. This routing is done using a switch-case structure that 
            routes the task to different agents based on classification results
        2. Set up data models and chat client
            - Create your chat client for connecting to AI services
            - Define Pydantic models for AI agents' structured JSON responses
            - Create simple data classes for passing information between workflow steps
            - Configure agents with specific instructions and response_format parameter for 
            structured JSON output
        3. Create specialized executor functions
            - Input storage executor
                Saves incoming data to shared state and forwards to classification agent
            - Transformation executor
                Converts agent's JSON response into typed routing object
            - Handler executors
                Separate executors for each classification outcome with guard conditions to 
                verify correct message processing
        4. Build routing logic
            - Create factory functions that generate condition checkers for each classification value
            - Design conditions to examine incoming messages and return true for specific classification results
            - Use conditions with Case objects in switch-case edge groups
            - Always include a Default case as fallback for unexpected scenarios
        5. Assemble the workflow
            - Use WorkflowBuilder to connect executors with regular edges
            - Add switch-case edge group for routing based on classification results
            - Configure workflow to follow first matching case or fall back to default
            - Set up terminal executor to yield final output

- **Use Magentic orchestration**

    - What is magnetic orchestration
        - Is a flexible, general-purpose multi-agent pattern designed for complex, 
            open-ended tasks that require dynamic collaboration
        - Uses a dedicated Magentic manager to coordinate a team of specialized agents
        - The manager decides which agent should act next based 
            - The evolving context
            - Task progress
            - Agent capabilities.
        - Allows the system to break down complex problems, assign subtasks, and 
            iteratively refine solutions
        - Focuses as much on building and documenting the approach as it does on 
            delivering the final solution

    - When to use Magentic orchestration
        - The problem is complex or open-ended with no predetermined solution path.
        - Input and feedback from multiple specialized agents are needed to shape a valid solution.
        - The system must generate a documented plan of approach for human review.
        - Agents have tools that can directly interact with external systems and resources.
        - A step-by-step, dynamically built execution plan adds value before running the tasks.

    - When to avoid Magentic orchestration
        - The solution path is fixed or deterministic.
        - There's no need to produce a ledger or plan of approach.
        - The task is simple enough for a more lightweight orchestration pattern.
        - Speed is the priority, as this method emphasizes planning over fast execution.
        - You expect frequent stalls or loops without a clear resolution path.

    - Implementing Magentic orchestration
        1. Define specialized agents
            Create agent instances (for example, `ChatAgent`) with specific instructions and chat clients. 
            Each agent should have a specialized role and capabilities suited for different aspects of the complex task.
        2. Set up event handling callback
            Define an async callback function to handle different types of events during orchestration, 
            including orchestrator messages, agent streaming updates, agent messages, and final results.
        3. Build the Magentic workflow
            Use the `MagenticBuilder` class to create the orchestration. 
            Add your agent instances as participants, configure the event callback with streaming mode, and 
            set up the standard manager with appropriate parameters like max round count and stall limits.
        4. Configure the standard manager
            The standard manager coordinates agent collaboration using a chat client for planning and progress tracking. 
            Configure parameters like maximum round count, stall count, and reset count to control the orchestration behavior.
        5. Run the workflow
            Call the workflow's `run_stream` method with your complex task. 
            The workflow dynamically plans, delegates work to appropriate agents, and coordinates their collaboration to solve the problem.
        6. Process workflow events
            Iterate through the workflow events using an async loop. 
            Handle different event types including `WorkflowOutputEvent`, which contains the final results from the orchestration.
        7. Extract the final result
            Collect the final output from the workflow events. 
            The result contains the complete solution developed through the collaborative effort of all participating agents

- **Key takeaways**
    - Multi-agent systems offer significant advantages over single-agent architectures, 
        especially in **scalability**, **specialization**, and **collaborative problem solving**.
    - The Microsoft Agent Framework SDK enables the design and management of 
        sophisticated multi-agent orchestration workflows.
    - Different orchestration patterns serve different purposes and use cases
        - **Concurrent orchestration** for parallel task execution
        - **Sequential orchestration** for step-by-step workflows
        - **Handoff orchestration** for transferring responsibility between agents
        - **Group chat orchestration** for collaborative interactions among agents
        - **Magnetic orchestration** for dynamic and adaptive coordination
    - Choosing the correct orchestration pattern is essential for building efficient and maintainable AI solutions.
    - The SDK provides a **unified interface** for
        - Defining agents
        - Running orchestrations
        - Managing structured data
        - Retrieving asynchronous results
    - Asynchronous execution improves responsiveness and scalability in distributed AI systems.
    - The framework helps developers build **flexible**, **reliable**, and **maintainable** enterprise-grade AI workflows.
    - Multi-agent orchestration simplifies the implementation of complex business processes by 
        distributing responsibilities across specialized agents.

- **Further reading**
    - [ Microsoft Agent Framework SDK documentation](https://learn.microsoft.com/en-us/agent-framework/overview/agent-framework-overview)


- **Exercise - Develop a multi-agent solution**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/08-agent-framework-multi-agents.html)


### 9. [Discover Azure AI Agents with A2A](https://learn.microsoft.com/en-gb/training/modules/discover-agents-with-a2a/)

- **Introduction**
    - AI agents are effective individually, but many real-world scenarios require **collaboration between multiple agents**.
    -  Managing communication and coordination between distributed or remote agents manually can become **complex and inefficient**.
    - The **Agent-to-Agent (A2A) protocol** provides a **standardized framework** for:
        - Agent discovery
        - Agent communication
        - Coordinated task execution
        - A2A enables **secure and seamless communication** between agents across different environments.
    - The protocol allows developers to:
        - Connect to remote agents easily
        - Delegate tasks to the most appropriate agent
        - Automate multi-agent workflows
        - A routing agent can orchestrate workflows by passing outputs from one agent to another automatically.
    - Example workflow:
        - A title-generation agent creates blog headlines
        - An outline-generation agent creates article structures
        - A routing agent coordinates the interaction between both agents
        - The module focuses on implementing the A2A protocol using Microsoft Azure AI Agents.
    - Key practical skills covered include:
        - Configuring routing agents
        - Registering remote agents
        - Building coordinated multi-agent workflows
        - A2A improves the scalability, interoperability, and maintainability of collaborative AI systems.

- **Define an A2A agent**

    - What is Agent-to-Agent (A2A) protocol
        - Is a standardized way for AI agents to communicate and 
            collaborate with each other
        - It defines
            - How agents can share context
            - Invoke each other's capabilities
            - Exchange information securely
        - Agents from different vendors or platforms can work together seamlessly, 
            enabling more complex and integrated AI solutions
        - Agent needs to explain what it can do
            Agent Skills and how other agents or clients can discover those 
            capabilities are exposed through an Agent Cardt

    - Advantages of the Agent-to-Agent (A2A) protocol
        - Enhanced Collaboration
            A2A enables agents from different vendors and platforms to **share context and work together**, 
            allowing seamless automation across systems that are traditionally disconnected.
        - Flexible Model Selection
            Each A2A agent can choose which large language model (LLM) to use for handling requests, 
            enabling optimized or fine-tuned models per agent, unlike some MCP scenarios that rely on a 
            single LLM connection.
        - Integrated Authentication
            Authentication is built into the A2A protocol, providing a robust security framework for 
            secure agent-to-agent communication.

    - Agent Skills
        - Describes a specific capability or function that the agent can perform
        - Key elements
            - ID
                A unique identifier for the skill.
            - Name
                A human-readable name describing the skill.
            - Description
                A detailed explanation of what the skill does.
            - Tags
                Keywords for categorization and easier discovery.
            - Examples
                Sample prompts or use cases to illustrate the skill in action.
            - Input/Output Modes
                Supported data formats or media types (for example, text, JSON).
        - When defining a skill consider
            - The tasks it should perform
            - How to describe them clearly
            - How other agents or clients might use them
            - Example
                <pre>
                A simple "Hello World" skill could return a basic greeting in text format, 
                whereas a blog-writing skill might accept a topic and return a suggested title or outline.
                </pre>

    - Agent Card
        - Is like a digital business card for your agent
        - It's a structured document that a routing agent or client can 
            retrieve to discover your agent’s capabilities and how to interact with it
        - Key elements
            - Identity Information
                Name, description, and version of the agent.
            - Endpoint URL
                Where the agent’s A2A service can be accessed.
            - Capabilities
                Supported A2A features such as streaming or push notifications.
            - Default Input/Output Modes
                The primary media types the agent can handle.
            - Skills
                A list of the agent’s skills that other agents can invoke.
            - Authentication Support
                Indicates if the agent requires credentials for access.
        - Ensure it accurately represents your agent’s skills and endpoints

    - Putting it together
        - Once an agent defines its skills and publishes an Agent Card
            - Other agents or clients can discover the agent automatically.
            - Requests can be routed to the agent’s appropriate skill.
            - Responses are returned in supported formats, enabling smooth collaboration across multiple agents.
        - Example
            <pre>
            In a technical writer workflow, 
            one agent could define skills for generating article titles, and 
            another for creating outlines.
            The routing agent retrieves each agent’s card to discover these capabilities and 
            orchestrates a workflow where a title generated by one agent feeds into the 
            outline agent, producing a cohesive final response.
            </pre>

- **Implement an agent executor**

    - What is the Agent Executor
        - Is a core component of an A2A agent
        - Defines 
            - How your agent processes incoming requests
            - Generates responses
            - Communicates with clients or other agents
        - Is the bridge between the A2A protocol and 
            your agent's specific business logic

    - Understand the Agent Executor
        - The `AgentExecutor` interface handles all 
            incoming requests sent to your agent.
        - Key responsibilities
            - Execute tasks requested by users or other agents.
                `RequestContext` to understand the incoming request
            - Stream responses or send individual messages back to the client.
                `EventQueue` to communicate results or events back to the client
            - Handle task cancellation if supported.

    - Implement the interface
        - Execute
            - Processes incoming requests and generates responses.
            - Accesses request details (for example, user input, task context).
            - Sends results back via an event queue, which may include messages, 
                task updates, or artifacts.
        - Cancel
            - Handles requests to cancel an ongoing task.
            - May not be supported for simple agents.

    - Request handling flow
        (Consider a "Hello World" agent workflow)
        - The agent has a small helper class that implements its core logic (for example, returning a string).
        - The executor receives a request and calls the agent’s logic.
        - The executor wraps the result as an event and places it on the event queue.
        - The routing mechanism sends the event back to the requester.
        - A basic agent might only indicate that cancellation isn't supported

- **Host an A2A server**

    - Hosting an agent allows
        - Expose its capabilities through its **Agent Card**, 
            which clients and other agents can discover.
        - Receive incoming A2A requests and forward them to 
            **Agent Executor** for processing.
        - Manage task lifecycles, including streaming responses and 
            stateful interactions.
        - The server acts as a bridge between your agent’s logic and 
            the external world
        - Hosting an A2A agent combines 
            - The Agent Card
            - Request handler
            - Agent executor to make it available for 
                client and agent interactions

    - Core components of the agent server
        - Agent Card
            - Describes the agent’s capabilities, skills, and 
                input/output modes.
            - Exposed at a standard endpoint (typically `/.well-known/agent-card.json`) so 
                clients and other agents can discover your agent.
            - Can include multiple versions or an "extended" card for authenticated users.
        - Request Handler
            - Routes incoming requests to the appropriate methods on 
                your **Agent Executor** (for example, execute or cancel).
            - Manages the task lifecycle using a **Task Store**, which tracks tasks, 
                streaming data, and resubscriptions.
            - Even simple agents require a task store to handle interactions reliably.
        - Server Application
            - Built using a web framework (Starlette in Python) to handle HTTP requests.
            - Combined with an Asynchronous Server Gateway Interface (ASGI) 
                server &mdash; like Uvicorn &mdash; to start listening on a network interface and port.
            - Exposes the agent card and request handler endpoints, enabling clients to 
                interact with your agent.

    - Set up the A2A agent server
        1. Define your agent’s skills and Agent Card.
        2. Initialize a request handler that links your Agent Executor with a Task Store.
        3. Set up the server application, providing the Agent Card and request handler.
        4. Start the server using an ASGI server (Uvicorn) to make it accessible on the network.
        5. Once running, the agent listens for incoming requests and responds according to its defined skills. 

- **Connect to your A2A agent**

    - How a client can interact with A2A server
        - A client acts as the bridge between the
            application and the agent server
        - Client responsibilities
            - Discovering the Agent Card, which contains metadata about the 
                agent and its endpoints.
            - Sending requests to the agent for processing.
            - Receiving and interpreting the agent's responses, which can be 
                either direct messages or task-based results.

    - Connect to your agent server
        - The client must know the base URL of the server.
        - The client typically retrieves the Agent Card from a 
            well-known endpoint on the server.
        - Once the Agent Card is obtained, the client can be 
            initialized with it, establishing a connection ready to send messages.

    - Send requests to the agent
        - Non-Streaming Requests
            The client sends a message and waits for a complete response. 
            This type of request is suitable for simple interactions or 
            when a single response is expected.
        - Streaming Requests
            The client sends a message and receives responses incrementally as the 
            agent processes the request. 
            This type of request is useful for long-running tasks or when you want to 
            update the user in real-time.
        - Requests usually include a role (for example, user) and the message content

    - Handle the agent response
        - Direct messages
            Immediate outputs from the agent, such as text or structured content.
        - Task-based responses
            Objects representing ongoing tasks, which may require follow-up calls to 
            check status or retrieve results.

    - Interacting with the agent
        - Each request should be uniquely identifiable, 
            often using a generated ID.
        - Streaming responses are asynchronous and 
            may provide partial results before the final output.
        - Simple agents may return messages directly, 
            while more advanced agents may manage multiple tasks simultaneously.

- **Key takeaways**
    - The A2A Ecosystem
        Connecting Python clients to Azure AI Agents relies on running an Agent-to-Agent (A2A) server, 
        establishing a standard framework for cross-agent communication.
    - Dynamic Discovery & Agent Cards
        Agents utilize an Agent Card mechanism to be discovered and communicated with dynamically at 
        runtime, eliminating rigid, hardcoded network configurations.
    - Request Handling via Executors
        Executors act as the core processing engine, managing and fulfilling incoming agent requests 
        within the network.
    - Bi-Directional Message Flow
        The architecture natively supports both streaming and non-streaming message delivery patterns 
        between clients and agents to accommodate different latency and data requirements.
    - Distributed Task Delegation
        Mastering these components allows developers to construct decentralized, flexible agent networks 
        that can seamlessly delegate tasks and respond to complex requests across distributed environments.


- **Exercise - Connect to remote Azure AI Agents with the A2A protocol**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/Exercises/09-multi-remote-agents-with-a2a.html)


## Develop natural language solutions in Azure

- [`Documentação Oficial`](https://learn.MS.com/en-gb/training/paths/develop-language-solutions-azure-ai/)

### 1. [Analyze text with Azure Language in Foundry Tools](https://learn.microsoft.com/en-gb/training/modules/analyze-text-ai-language/)

- **Azure Language in MS Foundry Tools**

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
    - <span>&#9888;</span> ==Mixed language content within same document returns the language<br/>&nbsp;&nbsp;&nbsp;&nbsp;with the largest representation in the content, but with a lower positive rating
    &nbsp;&nbsp;&nbsp;&nbsp;If the parser encounters character encoding issues during conversion, the<br/>&nbsp;&nbsp;&nbsp;&nbsp;response for the language name and ISO code will be returned as `(unknown)` and score as `0`==

- **Extract entities**

    - Named entity Recognition (NER)
        1. Person
        2. Location
        3. DateTime
        4. Organization
        5. Address
        6. Email
        7. URL
        8. [Others](https://learn.microsoft.com/en-gb/azure/ai-services/language-service/named-entity-recognition/concepts/named-entity-categories?tabs=ga-api)
    
    - Example input for NER
        <pre><code>
            # Example text to analyze
            documents = ["MS was founded on April 4, 1975 by Bill Gates and Paul Allen in Albuquerque, New Mexico.",
                        "Satya Nadella became CEO of MS on February 4, 2014."]
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
                MS (Organization)
                April 4, 1975 (DateTime)
                Bill Gates (Person)
                Paul Allen (Person)
                Albuquerque (Location)
                New Mexico (Location)
            Entities in document 1:
                Satya Nadella (Person)
                CEO (PersonType)
                MS (Organization)
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

- [`Documentação Language Service`](https://learn.microsoft.com/en-gb/azure/ai-services/language-service/)

### 2. [Develop a text analysis agent with the Azure Language MCP server](https://learn.microsoft.com/en-us/training/modules/develop-text-analysis-agent-language-mcp/)

- **Introduction**

    - Powerful NLP Capabilities
        Azure Language tools in Foundry offer robust text analysis, 
        including automated language detection, named entity recognition, and 
        PII (personally identifiable information) extraction.
    - The Power of MCP Integration
        By connecting these capabilities through the Azure Language Model Context Protocol (MCP) server,
        your AI agent can dynamically select and execute the right tool for the job. 
        This removes the need to write custom integration code for every individual NLP task.
    - Unified Analysis Workflow
        Rather than building siloed integrations for complex processing—such as 
        determining review languages, identifying entities, and 
        sanitizing private data — a single agent connection can handle these tasks in one cohesive workflow.
    - Module Objectives
        Learn the architecture of the Azure Language MCP server, master the process of connecting it to a 
        Microsoft Foundry agent, and practice building programmatic client applications that 
        interact with these intelligent agents.

- **Understand the Azure Language MCP server**
    
    - What is the Model Context Protocol?
        - Is an open protocol that defines how AI agents interact with 
            - External tools
            - Data sources
            - Services
        - MCP uses a client-server architecture with
            - Host
                The application that runs the agent (such as Microsoft Foundry or a custom app).
            - Client
                A component within the host that manages connections to MCP servers and handles communication.
            - Server
                A program that exposes tools, resources, and prompts that an agent can discover and call.
        - When an agent connects to an MCP server
            - Receives a catalog of available tools
            - A descriptions of what each tool does
            - Choose the right tool based on the user's request
            - This approach is called _dynamic tool_ discovery
                The agent doesn't need hardcoded knowledge of each tool
            - Key advantage of MCP for AI agents is flexibility
            - Tools can be added, updated, or removed on the server 
                without modifying the agent itself
            - <span>&#x1F4A1;</span>==To learn more about MCP architecture and how to build custom MCP tool integrations,
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see the  [ Integrate MCP Tools with Azure AI Agents](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/) module.==

    - Azure Language MCP server capabilities
        | Capability | Description |
        |:-|:-|
        |Language Detection|Identifies the language in which text is written|
        |Named Entity<br/>Recognition|Identifies and categorizes entities in text, such as<br/>people, places, organizations, dates, and quantities|
        |PII Redaction|Detects and redacts personally identifiable information (PII) such as<br/>names, addresses, and phone numbers|
        |Text Analytics for<br/>Health|Extracts and labels medical entities, such as<br/>diagnoses, medications, and symptoms from clinical text|
        
        <br/>

        <span>&#x1F4A1;</span>==Azure Language also provides functionality for sentiment analysis, summarization, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;key phrase extraction, and other common language-related tasks. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;These deprecated capabilities are provided to support existing applications.==

    - How the agent selects tools
        1. The user sends a prompt to the agent.
        2. The agent analyzes the prompt and determines which task (or tasks) need to be performed.
        3. The agent checks the available MCP tools and their descriptions to find the best match.
        4. The agent calls the selected tool through the MCP server, passing the relevant input text.
        5. The MCP server processes the request using the appropriate Azure Language capability and returns the results.
        6. The agent combines the results into a natural language response for the user.
        7. There's no need to write routing logic to direct requests to specific tools

    - MCP server endpoint
        - Format
            <pre>
            https://{foundry-resource-name}.cognitiveservices.azure.com/language/mcp?api-version=2025-11-15-preview
            </pre>
        - Replace `{foundry-resource-name}` with the name of your Foundry resource (or Azure Language resource)
        - <span>&#x1F4A1;</span>==Azure Language also provides a local MCP server that you can host in your own environment. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;or setup guidance, see the [Azure Language MCP Server quickstart](https://github.com/Azure-Samples/ai-language-samples) in the  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Azure Language samples repository.==

- **Connect and use the Language MCP server with an agent**

    - Create a Foundry project and agent
        1. In the [Microsoft Foundry portal](https://ai.azure.com/), create a new project (or use an existing one).
        2. Deploy a model (such as gpt-4.1) that your agent will use for reasoning and generating responses.
        3. Create an agent and give it instructions that describe its purpose.
        4. Example
            <pre>
            You are an AI agent that assists users by helping them analyze and summarize text.
            </pre>
            The agent is now ready to receive tool connections

    - Connect the Azure Language MCP server
        1. In the navigation pane, select the **Tools page**.
        2. Select **Connect a tool** and choose **Azure Language in Foundry Tools** from the catalog.
        3. Configure the connection with the following settings:
            - Foundry resource name
                The name of your Foundry resource (for example, myproject-resource).
            - Authentication
                Key-based.
            - Credential (`Ocp-Apim-Subscription-Key`)
            The key for your Foundry project.
        4. Wait for the connection to be created, then select **Use in an agent** and choose your agent.
        5. <span>&#x1F4A1;</span>==You can find the project key on the project home page in the Foundry portal.==

    - Update agent instructions
        - After connecting the Language MCP tool, 
            update the agent's instructions to direct it to use the tool
        - Example
            <pre>
            You are an AI agent that assists users by helping them analyze text. 
            Use the Azure Language tool to perform text analysis tasks.
            </pre>
        - This instruction helps the agent understand that it should use the 
            connected tool when processing text analysis requests.

    - Test in the agent playground
        - Prompt sent that requires text analysis,
            the agent
            1. Identifies the tasks needed 
                (for example, language detection and entity recognition).
            2. Calls the appropriate Azure Language MCP tool(s).
            3. Returns a combined response.
        - The first time the agent uses an MCP tool, 
            you're prompted to **approve** the tool usage
            - Single use
            - Always approve all 
                Azure Language in Foundry Tools tools
        - After the agent responds, 
            you can review the Logs pane to verify which tools were used

    - Build a client application
        - The **Microsoft Foundry SDK** supports this 
            through the OpenAI Responses API.
        - To build a client application use
            - `azure-ai-projects`
            - `azure-identity packages`
        - General pattern
            1. Create an `AIProjectClient` using your Foundry project endpoint and 
                `DefaultAzureCredential` (which uses your Azure CLI credentials in development).
            2. Get an OpenAI client from the project client by 
                calling `get_openai_client()`.
            3. Call `responses.create()` to send a user prompt to the agent.
            4. The key part is how you reference the 
                agent (name in the `extra_body` parameter)
            5. Example
                <pre><code>
                response = openai_client.responses.create(
                    input=[{"role": "user", "content": user_prompt}],
                    extra_body={
                        "agent_reference": {
                            "name": "Text-Analysis-Agent",
                            "type": "agent_reference"
                        }
                    },
                )
                &nbsp;
                print(response.output_text)
                </code></pre>
            6. Steps
                - The agent processes the prompt
                - Calls the appropriate MCP tools
                - Returns the result in `output_text`
            7. Response inspection (JSON) using
                `response.model_dump_json()`
                - See which tools the agent called
                    - `extract_named_entities_from_text`
                    - `detect_language_from_text`
                - The arguments
                - Results for each tool call

    - Connect the MCP server in code
        - Is possible to define the MCP tool connection directly in 
            code when you create an agent
        - Use the MCPTool class from the `azure-ai-projects` SDK to specify
            - Server label
            - URL
            - Allowed tools
        - Example
            <pre><code>
            from azure.ai.projects.models import MCPTool
            &nbsp;
            mcp_tool = MCPTool(
                server_label="azure-language",
                server_url="https://{foundry-resource-name}.cognitiveservices.azure.com/language/mcp?api-version=2025-11-15-preview",
                require_approval="always",
            )
            </code><pre>
        - Then pass the `mcp_tool` when creating the 
            agent through the SDK
        - Useful when you want to manage tool connections as 
            part of your application code 
            rather than configuring them manually in the portal
        - Use the `allowed_tools` property on MCPTool to 
            restrict which specific Language tools the agent can call

    - Tool selection with multi-task prompts
        - When a user's prompt involves multiple text analysis tasks, the 
            agent can call multiple tools in a single turn
        - Example
            <pre>
            "Tell me what entities and dates are mentioned in this review, and 
            whether it is positive or negative."
            </pre>
        - This prompt requires
            - Entity recognition
            - Sentiment analysis
        - The agent identifies both tasks
        - Calls the appropriate tools
            - `extract_named_entities_from_text`
            - `detect_language_from_text`
        - Combines the results into a single response
        - Each tool call goes through the 
            MCP server independently
        - The agent synthesizes the outputs into a 
            coherent answer for the user

- **Key takeaways**
    - Describe the Azure Language MCP server and the text analysis capabilities it exposes.
    - Explain how MCP enables dynamic tool discovery and selection by AI agents.
    - Connect the Azure Language MCP server to an agent in Microsoft Foundry.
    - Test language tool integration in the agent playground.
    - Build a Python client application that invokes an agent with language tools using the Foundry SDK.


- **Further reading**
    - [A    zure Language tools and agents](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/foundry-tools-agents)
    - [Azure Language MCP server capabilities](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/foundry-tools-agents#azure-language-mcp-server-preview)
    - [Connect to Model Context Protocol servers](https://learn.microsoft.com/en-us/azure/foundry/agents/how-to/tools/model-context-protocol)
    - [Azure AI Projects SDK for Python](https://learn.microsoft.com/en-us/python/api/overview/azure/ai-projects-readme)
    - [Build agents using Model Context Protocol on Azure](https://learn.microsoft.com/en-us/azure/developer/ai/intro-agents-mcp)

- **Exercise - Develop a text analysis agent**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-language/Instructions/Exercises/02-language-agent.html)


### 3. [Develop natural language solutions in Azure](https://learn.microsoft.com/en-us/training/paths/develop-language-solutions-azure-ai/)

- **Choose a speech-capable model**

    - How to find
        - Use the filter and search features in the 
            Microsoft Foundry Portal
        - Relationed with speech-capable models
            must consider
            - Generative AI models that can transcribe speech to text
            - Generative AI models that can synthesize text to speech
        - <span>&#x1F4A1;</span>==To learn more about available models in Microsoft Foundry, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft Foundry Models overview](https://learn.microsoft.com/en-us/azure/foundry/concepts/foundry-models-overview) article in the Microsoft Foundry documentation.==

- **Transcribe speech**

    - What it is speech transcription or 
        _speech-to-text_
        - Speech-to-text
            - Involves submitting audio content to a model
            - Wich responds with a text-based transcript of the 
                speech in the audio source
        - Models that support speech-to-text operations
            - gpt-4o-transcribe
            - gpt-4o-mini-transcribe
            - gpt-4o-transcribe-diarize
        - <span>&#x1F4A1;</span>==Model availability varies by region. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Review the[ model regional availability](https://learn.microsoft.com/en-us/azure/foundry/foundry-models/concepts/models-sold-directly-by-azure?pivots=azure-openai#model-summary-table-and-region-availability&azure-portal=true) table in the Microsoft Foundry documentation.==

    - Using a speech-to-text model
        - Can use the **AzureOpenAI** client in the OpenAI SDK
        - To connect to the endpoint for your Microsoft Foundry resource
        - Upload the contents of an audio file to the model for transcription
        - Example
            <pre><code>
            from openai import AzureOpenAI
            from pathlib import Path
            &nbsp;
            # Create an AzureOpenAI client
            client = AzureOpenAI(
                azure_endpoint=YOUR_FOUNDRY_ENDPOINT,
                api_key=YOUR_FOUNDRY_KEY,
                api_version="2025-03-01-preview"
            )
            &nbsp;
            # Get the audio file
            file_path = Path("speech.mp3")
            audio_file = open(file_path, "rb")
            &nbsp;
            # Use the model to transcribe the audio file
            transcription = client.audio.transcriptions.create(
                model=YOUR_MODEL_DEPLOYMENT,
                file=audio_file,
                response_format="text"
            )
            &nbsp;
            print(transcription)
            </code></pre>

- **Synthesize speech**

    - What it is speech synthesis or 
        _text-to-speech_
        - Text-to-speech
            - Is the reverse of speech-to-text
            - Involves submitting text to a model
            - Which returns an audio stream of the 
                vocalized text
        - Models that support text-to-speech operations
            - gpt-4o-tts
            - gpt-4o-mini-tts
        - <span>&#x1F4A1;</span>==Model availability varies by region. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Review the[ model regional availability](https://learn.microsoft.com/en-us/azure/foundry/foundry-models/concepts/models-sold-directly-by-azure?pivots=azure-openai#model-summary-table-and-region-availability&azure-portal=true) table in the Microsoft Foundry documentation.==

    - Using a text-to-speech model
        - Can use the **AzureOpenAI** client in the OpenAI SDK
        - To connect to the endpoint for your Microsoft Foundry resource
        - Upload the contents of an audio file to the model for transcription
        - Example
            <pre><code>
            from openai import AzureOpenAI
            from pathlib import Path
            &nbsp;
            # Create an AzureOpenAI client
            client = AzureOpenAI(
                azure_endpoint=YOUR_FOUNDRY_ENDPOINT,
                api_key=YOUR_FOUNDRY_KEY,
                api_version="2025-03-01-preview"
            )
            &nbsp;
            # Path for audio output file
            speech_file_path = Path("output_speech.wav")
            &nbsp;
            # Generate speech and save to file
            with client.audio.speech.with_streaming_response.create(
                        model=YOUR_MODEL_DEPLOYMENT,
                        voice="alloy",
                        input="This speech was AI-generated!",
                        instructions="Speak in an upbeat, excited tone.",
                ) as response:
                response.stream_to_file(speech_file_path)
            &nbsp;
            print(f"Speech generated and saved to {speech_file_path}")
            </code></pre>

- **Further reading**
    - [ Audio models](https://learn.microsoft.com/en-us/azure/foundry/foundry-models/concepts/models-sold-directly-by-azure?pivots=azure-openai#audio-models&azure-portal=true)

- **Exercise - Use speech-capable generative AI models**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-language/Instructions/Exercises/03-gen-ai-speech.html)


### 4. [Create speech-enabled apps with Azure Speech in Microsoft Foundry Tools](https://learn.microsoft.com/en-us/training/modules/create-speech-enabled-apps/)

- **Azure Speech in Foundry Tools**

    - What is Azure Speech
        -  Is a set of speech-related capabilities that are 
            provided by a Foundry resource
        - Can use for
            - Creating an application to transcribe 
                recorded calls or meetings
            - Creating an AI assistant that can 
                read text messages or emails aloud

    - Using Azure Speech in a Microsoft Foundry resource
        - Must provision a Microsoft Foundry resource in 
            your Azure subscription
        - Use its endpoint to call the 
            Azure Language APIs from your code
        - Authenticating requests by providing the 
            key associated with your resource
        - Call the Azure Language APIs by
            - Submitting requests in JSON format to the 
                REST interface
            - Using any of the available programming 
                language-specific SDKs
        - <span>&#x1F4A1;</span>==The code examples in this module are based in Python, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;using the [Python SDK for Azure Speech in Foundry Tools](https://pypi.org/project/azure-cognitiveservices-speech/). 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SDKs for other common languages (such as Microsoft C#, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;JavaScript, and others) follow a similar pattern.==

    - Creating a SpeechConfig
        - Initial object you need to create to 
            provide access to the Azure Speech in Foundry Tool endpoint
        - <span>&#x1F4A1;</span>==The default home page in the Foundry portal shows the `endpoint` and `key` for your **project**.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To view the `key` and `endpoint` for your **resource**, you can view the parent resource for your 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;project in the **Admin** tab of the **Operate** page of the portal. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The project and foundry resource keys are the same.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The project endpoint is the resource endpoint with `/api/projects/{project_name}` appended
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The **project endpoint** is `https://my-ai-app-foundry.services.ai.azure.com/api/projects/my-ai-app`
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The **resource endpoint** is `https://my-ai-app-foundry.services.ai.azure.com`==
        - Example
            <pre><code>
            # run "pip install azure-cognitiveservices-speech" first to install the package 
            import azure.cognitiveservices.speech as speech_sdk
            &nbsp;
            # Create SpeechConfig using endpoint and key
            speech_config = speech_sdk.SpeechConfig(subscription="YOUR_FOUNDRY_KEY",
                                                    endpoint="YOUR_FOUNDRY_ENDPOINT")
            </code></pre>
        - <span>&#x1F4A1;</span>==Releases of the Python SDK prior to 1.48.2 **required** that you specify the _region_ 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;where your resource is deployed instead of the endpoint.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With the latest release, you can use either the Foundry resource endpoint or the region.==

- **Use the Speech to Text API**

    - Pattern for using the Speech to text API
        1. ![https://learn.microsoft.com/en-us/training/wwl-data-ai/create-speech-enabled-apps/media/speech-to-text.png](https://learn.microsoft.com/en-us/training/wwl-data-ai/create-speech-enabled-apps/media/speech-to-text.png)
        2. Use a **SpeechConfig** object to 
            encapsulate the information required to connect to your Foundry resource.
            Specifically, its endpoint (or region) and key.
        3. Optionally, use an **AudioConfig** to define the input source for 
            the audio to be transcribed. By default, this is the default system microphone, 
            but you can also specify an audio file.
        4. Use the **SpeechConfig** and **AudioConfig** to create a **SpeechRecognizer** object. 
            This object is a proxy client for the **Speech to text API**.
        5. Use the methods of the **SpeechRecognizer** object to call the underlying API functions. 
            For example, the **RecognizeOnceAsync()** method uses the Azure Speech service to 
            asynchronously transcribe a single spoken utterance.
        6. Process the response. In the case of the **RecognizeOnceAsync()** method, the result is a    SpeechRecognitionResult object that includes the following properties:
            - Duration
            - OffsetInTicks
            - Properties
            - Reason
            - ResultId
            - Text
        7. Success operation
            - The **Reason** property has the 
                enumerated value **RecognizedSpeech**
            - The **Text** property contains the transcription
        8. Other values for **Result**
            - NoMatch
                Indicating that the audio was successfully parsed but no 
                speech was recognized
            - Canceled
                Indicating that an error occurred 
                - Check **Properties** collection
                - **CancellationReason** property to determine what went wrong
        9. Example (Transcribing an audio file)
            <pre><code>
            import azure.cognitiveservices.speech as speech_sdk
            &nbsp;
            # Speech config encapsulates the connection to the resource
            speech_config = speech_sdk.SpeechConfig(subscription="YOUR_FOUNDRY_KEY",
                                                endpoint="YOUR_FOUNDRY_ENDPOINT")
            &nbsp;
            # Audio config determines the audio stream source (defaults to system mic)
            file_path = "audio.wav"
            audio_config = speech_sdk.audio.AudioConfig(filename=file_path)
            &nbsp;
            # Use a speech recognizer to transcribe the audio
            speech_recognizer = speech_sdk.SpeechRecognizer(speech_config=speech_config,
                                                        audio_config=audio_config)
            &nbsp;
            result = speech_recognizer.recognize_once_async().get()
            &nbsp;
            # Did it succeeed
            if result.reason == speech_sdk.ResultReason.RecognizedSpeech:
                # Yes!
                print(f"Transcription:\n{result.text}")
            else:
                # No. Try to determine why.
                print("Error transcribing message: {}".format(result.reason))
            </code></pre>

- **Use the Text to Speech API**

    - Pattern for using the Text to speech API 
        1. ![https://learn.microsoft.com/en-us/training/wwl-data-ai/create-speech-enabled-apps/media/text-to-speech.png](https://learn.microsoft.com/en-us/training/wwl-data-ai/create-speech-enabled-apps/media/text-to-speech.png)
        2. Use a **SpeechConfig** object to 
            encapsulate the information required to connect to your Azure Speech resource. 
            Specifically, its **location** and **key**.
        3. Optionally, use an **AudioConfig** to define the output device for 
        the speech to be synthesized. 
        By default, this is the default system speaker, but you can also specify an 
        audio file, or by explicitly setting this value to a **null** value, you can 
        process the audio stream object that is returned directly.
        4. Use the **SpeechConfig** and **AudioConfig** to create a **SpeechSynthesizer** object. 
            This object is a proxy client for the **Text to speech** API.
        5. Use the methods of the **SpeechSynthesizer** object to call the underlying API functions. 
            For example, the **SpeakTextAsync()** method uses the Azure Speech service to convert text to spoken audio.
        6. Process the response from the Azure Speech service. 
            In the case of the **SpeakTextAsync** method, the result is a **SpeechSynthesisResult** 
            object that contains the following properties:
            - AudioData
            - Properties
            - Reason
            - ResultId
        7. Success operation
            - The **Reason** property is set to the 
                **SynthesizingAudioCompleted** enumeration
            - The **AudioData** property contains the audio stream
                Depending on the **AudioConfig** may have been automatically 
                sent to a speaker or file
        8. Example
            <pre><code>
            import azure.cognitiveservices.speech as speechsdk
            &nbsp;
            # Speech config encapsulates the connection to the resource
            speech_config = speechsdk.SpeechConfig(subscription=KEY, endpoint=ENDPOINT)
            &nbsp;
            # Audio output config determines where to send the audio stream (defaults to speaker)
            audio_config = speechsdk.audio.AudioOutputConfig(use_default_speaker=True)
            &nbsp;
            # Use speech synthesizer to synthesize text as speech
            speech_synthesizer = speechsdk.SpeechSynthesizer(speech_config=speech_config,
            &nbsp;                                             audio_config=audio_config)
            text = "My voice is my password!"
            speech_synthesis_result = speech_synthesizer.speak_text_async(text).get()
            &nbsp;
            # Did it succeeed?
            if speech_synthesis_result.reason == speechsdk.ResultReason.SynthesizingAudioCompleted:
                # Yes!
                print("Speech synthesized for text [{}]".format(text))
            elif speech_synthesis_result.reason == speechsdk.ResultReason.Canceled:
                # No - Ty to find out why not
                cancellation_details = speech_synthesis_result.cancellation_details
                print("Speech synthesis canceled: {}".format(cancellation_details.reason))
                if cancellation_details.reason == speechsdk.CancellationReason.Error:
                    if cancellation_details.error_details:
                        print("Error details: {}".format(cancellation_details.error_details))
            </code></pre>

- **Configure audio format and voices**

    - Audio format
        - Can choose a format based on the required
            - Audio file type
            - Sample-rate
            - Bit-depth
        - Example 
            (a previously defined **SpeechConfig** object named _speech_config_)
            <pre>
            speech_config.set_speech_synthesis_output_format(SpeechSynthesisOutputFormat.Riff24Khz16BitMonoPcm)
            </pre>
        - <span>&#x1F4A1;</span>==For a full list of supported formats and their enumeration values,
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see the [Azure Speech SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-cognitiveservices-speech/azure.cognitiveservices.speech.speechsynthesisoutputformat).==

    - Voices
        - Voices are identified by _names_ that indicate a _locale_
        - Example
            <pre>
            speech_config.speech_synthesis_voice_name='en-US-Brian:DragonHDLatestNeural'
            </pre>
        - <span>&#x1F4A1;</span>==For information about voices, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see the [Azure Speech SDK documentation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support?tabs=tts).==

- **Use Speech Synthesis Markup Language**

    - What is SSML
        - Azure Speech SDK enables you to submit plain text to be 
            synthesized into speech
        - Also supports an XML-based syntax for describing 
            characteristics of the speech you want to generate
        - **Speech Synthesis Markup Language** (SSML) syntax 
            offers greater control over how the spoken output sounds
        - Can
            - Specify a speaking style, such as "excited" or "cheerful" when using a neural voice.
            - Insert pauses or silence.
            - Specify _phonemes_ (phonetic pronunciations), for example to 
                pronounce the text "SQL" as "sequel".
            - Adjust the _prosody_ of the voice (affecting the pitch, timbre, and speaking rate).
            - Use common "say-as" rules, for example to specify that a given string should be 
                expressed as a date, time, telephone number, or other form.
            - Insert recorded speech or audio, for example to include a standard recorded message or 
                simulate background noise.
        - Example
            ```xml
            <speak version="1.0" xmlns="http://www.w3.org/2001/10/synthesis" 
                                xmlns:mstts="https://www.w3.org/2001/mstts" xml:lang="en-US"> 
                <voice name="en-US-AriaNeural"> 
                    <mstts:express-as style="cheerful"> 
                    I say tomato 
                    </mstts:express-as> 
                </voice> 
                <voice name="en-US-GuyNeural"> 
                    I say <phoneme alphabet="sapi" ph="t ao m ae t ow"> tomato </phoneme>. 
                    <break strength="weak"/>Lets call the whole thing off! 
                </voice> 
            </speak>
            ```
        - This SSML specifies a spoken dialog between 
            two different neural voices
            - Ariana (cheerfully)
                "I say tomato:
            - Guy
                "I say tomato (pronounced tom-ah-toe) ... Let's call the whole thing off!"
        - Submit an SSML description to the 
            Speech service
            <pre>
            speech_synthesis_result = speech_synthesizer.speak_ssml_async('<speak>...').get()
            </pre>
        - <span>&#x1F4A1;</span>==For more information about SSML, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see the [Azure Speech SDK documentation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-synthesis-markup).==

- **Further reading**
    - [Azure Speech in Foundry Tools documentation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)


- **Exercise - Create a speech-enabled app**
    [&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-language/Instructions/Exercises/04-azure-speech.html)

### 5. [Develop a speech agent with the Azure Speech MCP server](https://learn.microsoft.com/en-us/training/modules/develop-speech-agent-speech-mcp/)

- **Introduction**

    - Integrating Azure Speech via MCP
        - Versatile Speech Capabilities
            Leverage Azure Speech tools to integrate high-quality speech-to-text (transcription) and 
            text-to-speech (synthesis) directly into your AI applications.
        - Intelligent Agent Access
            By exposing these tools through the Azure Speech Model Context Protocol (MCP) server, 
            your agent can perform speech-related operations based on simple natural language requests, 
            eliminating the need to write custom integration code for every operation.
        - Unified Audio Processing  
            Streamline complex workflows, such as processing customer support calls, by using a single 
            agent connection to handle both call transcription for analysis and audio response generation 
            for customer interaction.
        - Module Objectives
            Master the architectural design of the Azure Speech MCP server, configure the connection to a 
            Microsoft Foundry agent, and develop programmatic client applications to interact with these 
            speech-enabled agents.

- **Understand the Azure Speech MCP server**

    - What is the Model Context Protocol?
        - Is an open protocol that defines how AI agents interact with 
            - External tools
            - Data sources
            - Services
        - MCP uses a client-server architecture with
            - Host
                The application that runs the agent (such as Microsoft Foundry or a custom app).
            - Client
                A component within the host that manages connections to MCP servers and handles communication.
            - Server
                A program that exposes tools, resources, and prompts that an agent can discover and call.
        - When an agent connects to an MCP server
            - Receives a catalog of available tools
            - A descriptions of what each tool does
            - Choose the right tool based on the user's request
            - This approach is called _dynamic tool_ discovery
                The agent doesn't need hardcoded knowledge of each tool
            - Key advantage of MCP for AI agents is flexibility
            - Tools can be added, updated, or removed on the server 
                without modifying the agent itself
            - <span>&#x1F4A1;</span>==To learn more about MCP architecture and how to build custom MCP tool integrations,
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see the  [ Integrate MCP Tools with Azure AI Agents](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/) module.==

    - Azure Speech MCP server capabilities
        | Capability | Description |
        |:-|:-|
        |Speech-to-text<br/>(Recognize)|Converts audio files to text using advanced speech recognition.<br/>Supports WAV, MP3, OGG, FLAC, MP4, M4A, AAC, and other common audio formats.<br/>Includes options for language selection, phrase hints for improved accuracy, profanity filtering, and<br/>detailed or simple output formats|
        |Text-to-speech<br/>(Synthesize)|Converts text input into natural-sounding audio files using neural text-to-speech voices.<br/>Supports multiple languages and voices (for example, en-US-JennyNeural or en-GB-SoniaNeural), and<br/>generates output in WAV, MP3, or other formats|

        <br/>

        <span>&#x1F4A1;</span>==When you connect the Speech MCP server to an agent, the agent receives the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;available speech tools and their descriptions.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Based on the user's prompt, the agent decides which tool to call.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If a user says "Transcribe this audio file," the agent calls the speech-to-text tool. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If the user says "Generate speech from this text," the agent calls the text-to-speech tool.==

    - How the agent selects tools
        1. The user sends a prompt to the agent.
        2. The agent analyzes the prompt and 
            determines which speech task needs to be performed.
        3. The agent checks the available MCP tools and 
            their descriptions to find the best match.
        4. The agent calls the selected tool through the MCP server, 
            passing the relevant input (audio file URL or text).
        5. The MCP server processes the request using Azure Speech and 
            returns the results (transcribed text or a link to an audio file).
        6. The agent presents the results to the user in a natural language response.
        7. The agent handles tool selection autonomously
        8. There's no need to write routing logic to determine whether a 
            prompt requires speech-to-text or text-to-speech.

    - Storage requirements
        - Azure Speech MCP server works with audio files, 
            which requires an **Azure Storage** account.
            - Text-to-speech:
                The Speech MCP server saves generated audio files to an Azure Blob Storage container. 
                The agent's response includes a link to the generated audio file.
            - Speech-to-text
                The agent can transcribe audio files from a publicly accessible URL or from an 
                Azure Blob Storage container accessed with a SAS URL.
        - When you connect the Speech MCP server to your agent, 
            you provide a SAS URL for a blob container.
        - The SAS URL grants the MCP server permission to 
            read and write files in that container.
        - <span>&#9888;</span> ==Treat SAS URLs as secrets. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Use the shortest practical expiry time, scope them to a single container, and 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;don't embed them in source code, agent prompts, or chat transcripts.==

    - Prerequisites
        - An **Azure subscription**.
        - A **Foundry resource and project** — you need 
            **Contributor** or **Owner** role on the resource group. 
            Your Foundry resource includes speech capabilities.
        - An **Azure Storage account** with a blob container for storing audio files.
        - A **SAS URL** for the blob container with read, write, add, create, and list permissions.

    - Security considerations
        - The Azure Speech MCP server uses 
            key-based authentication.
        - On create the connection
            - Provide resource key
            - Blob container SAS URL
        - Best practices
            - Store keys and SAS URLs in a secure secret store and rotate them regularly.
            - Avoid embedding keys or SAS URLs directly in source code, scripts, or documentation.
            - Use the shortest practical SAS expiry time and scope it to the minimum required resource.
            - Rotate keys immediately if you suspect they're exposed.

- **Connect and use the Speech MCP server with an agent**

    - Set up Azure Blob Storage
        - The Azure Speech MCP server requires an 
            Azure Storage account to store audio files
        - Create a storage account and a 
            blob container before connecting the tool
        - How to create
            1. In the [Azure portal](https://portal.azure.com/), create a new 
                Azure Storage account (or use an existing one).
            2. In the storage account, expand **Data storage** and 
                select **Containers**.
            3. Create a new container (for example, named **files**) to 
                store the audio files your agent generates and reads.
            4. Generate a SAS token for the container with the permissions
                - Read
                - Add
                - Create
                - Write
                - List.
            5. Set the expiry time to the shortest practical duration.
        - <span>&#9888;</span> ==Copy the generated SAS URL and store it securely 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;you need it when connecting the Speech MCP server.==

    - Create a Foundry project and agent
        1. In the [Microsoft Foundry portal](https://ai.azure.com/), create a new project (or use an existing one).
        2. Deploy a model (such as **gpt-4.1**) that your agent will use for reasoning and generating responses.
        3. Create an agent and give it instructions that describe its purpose
        4. Example
            <pre>
            You are an AI agent that uses the Azure AI Speech tool to transcribe and generate speech.
            </pre>
        5. The agent is now ready to receive tool connections.

    - Connect the Azure Speech MCP server
        1. In the navigation pane, select the **Tools** page.
        2. Select **Connect a tool** and choose **Azure Speech in Foundry Tools** from the catalog.
        3. Configure the connection with the following settings:
            - Foundry resource name
                The name of your Foundry resource (for example, `myproject-resource`).
            - Bearer (`Ocp-Apim-Subscription-Key`)
                The key for your Foundry project.
            - X-Blob-Container-Url
                The SAS URL for your blob container.
        4. Wait for the connection to be created, then select **Use in an agent** and choose your agent.
        5. The agent now has access to the speech-to-text and 
            text-to-speech tools exposed by the Azure Speech MCP server.
        6. <span>&#x1F4A1;</span>==You can find the project key on the project home page in the Foundry portal.== 

    - Test in the agent playground
        - Prompt
            <pre>
            Generate "To be or not to be, that is the question." as speech
            </pre>
        - The first time the agent uses the Speech MCP tool, 
            you're prompted to **approve** the tool usage. 
            You can select **Always approve all Azure Speech MCP Server tools** to 
            skip future approval prompts.
        - The response includes a link to the 
            generated audio file saved in your blob container

    - Test speech-to-text
        - Prompt
            <pre>
            Transcribe the file at https://example.com/audio/meeting-recording.wav
            </pre>
        - The agent calls the speech-to-text tool and 
            returns the transcribed text.

    - Customizing speech output
        - Voice selection
            Specify a neural voice, such as `en-GB-SoniaNeural` or `en-US-JennyNeural`.
        - Language
            Specify the language for recognition or 
            synthesis (for example, `es-ES` for Spanish).
        - Phrase hints
            Provide domain-specific terms to improve transcription 
            accuracy (for example, "Azure, OpenAI, Cognitive Services").
        - Profanity filtering
            Request `masked`, `removed`, or `raw` profanity 
            handling during transcription.
        - Example
            <pre>
            Synthesize "Better a witty fool, than a foolish wit!" as speech using the voice "en-GB-SoniaNeural".
            </pre>

    - Build a client application
        - The Microsoft Foundry SDK supports through the OpenAI Responses API
        - To build a client application, you use 
            - `azure-ai-projects`
            - `azure-identity`
        - Pattern
            1. Create an `AIProjectClient` using your Foundry project endpoint and 
                `DefaultAzureCredential` (which uses your Azure CLI credentials in development).
            2. Get an OpenAI client from the project client by calling `get_openai_client()`.
            3. Call `responses.create()` to send a user prompt to the agent.
            4. Key part is how you reference the agent
                specify it by name in the `extra_body` parameter

                <br/>
                <pre><code>
                response = openai_client.responses.create(
                    input=[{"role": "user", "content": user_prompt}],
                    extra_body={
                        "agent_reference": {
                            "name": "Speech-Agent",
                            "type": "agent_reference"
                        }
                    },
                )
                &nbsp;
                print(response.output_text)
                </code></pre>
            5. The agent processes the prompt
            6. Calls the appropriate Speech MCP tool
            7. Returns the result in `output_text`
            8. For text-to-speech requests, the output includes a 
                link to the generated audio file in your blob container.

    - Connect the MCP server in code
        - Use the `MCPTool` class from the `azure-ai-projects` SDK
        - Example
            <pre><code>
            from azure.ai.projects.models import MCPTool
            &nbsp;
            mcp_tool = MCPTool(
                server_label="azure-speech",
                server_url="https://{foundry-resource-name}.cognitiveservices.azure.com/speech/mcp",
                require_approval="always",
            )
            </code></pre>
        - Pass the `mcp_tool` when creating the 
            agent through the SDK
        - Useful when you want to manage tool connections as 
            part of your application code rather than configuring 
            them manually in the portal

- **Further reading**
    - [Azure Speech in Foundry Tools for the Azure MCP Server](https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/ai-services-speech)
    - [Connect to Model Context Protocol servers](https://learn.microsoft.com/en-us/azure/foundry/agents/how-to/tools/model-context-protocol)
    - [Azure AI Projects SDK for Python](https://learn.microsoft.com/en-us/python/api/overview/azure/ai-projects-readme)
    - [Azure Speech service overview](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview)

- **Exercise - Use Azure Speech in an agent**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-language/Instructions/Exercises/05-azure-speech-mcp.html)


### 6. [Develop an Azure Speech Voice Live Agent in Microsoft Foundry](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/)

- **Introduction**
    
    - Building Real-Time Voice Agents
        - The Evolution of Interaction
            Voice-enabled applications are fundamentally changing the human-technology interface, 
            moving toward more natural, conversational experiences.
        - Low-Latency Performance
            This module introduces the Voice Live API within Azure Speech in Foundry Tools, a 
            specialized solution engineered for high-quality, real-time, speech-to-speech interactions.
        - Simplified Orchestration
            Designed for scalability and efficiency, the API abstracts the complexity of traditional 
            voice architectures by eliminating the need to manually orchestrate individual audio components.
        - Developer-Focused Solutions
            You will learn how to leverage these advanced tools to build robust, interactive voice agents that 
            are both performant and easy to maintain.

- **Explore the Azure Voice Live API**

    - Key features
        - The Voice live API enables developers to create voice-enabled applications 
            with real-time, bidirectional communication.
        - Uses WebSocket connections
        - Supports
            - Speech recognition
            - Text-to-speech synthesis
            - Avatar streaming
            - Audio processing
        - JSON-formatted events manage 
            - Conversations
            - Audio streams
            - Responses.
        - Events are categorized into 
            - Client events (sent from client to server)
            - Server events (sent from server to client)
        - Real-time audio processing with support for multiple formats like PCM16 and G.711.
        - Advanced voice options, including OpenAI voices and Azure custom voices.
        - Avatar integration using WebRTC for video and animation.
        - Built-in noise reduction and echo cancellation.
        - For a table of supported models and regions, visit the [Voice Live API overview]https://learn.microsoft.com/en-us/azure/ai-services/speech-service/voice-live#supported-models-and-regions.

    - Connect to the Voice Live API
        - Authentication methods
            - Microsoft Entra (keyless)
                - Uses token-based authentication
                - Apply a retrieved authentication token using a
                `Bearer` token with the `Authorization` header
                - Need to assign the **Cognitive Services User** role to 
                    user account or a managed identity
                - Generate a token using 
                    - Azure CLI
                    - Azure SDKs
                - Token generated with 
                    - The `https://ai.azure.com/.default` scope
                    - Legacy `https://cognitiveservices.azure.com/.default` scope
                - Use the token in the `Authorization` header of the WebSocket connection request, 
                    with the format `Bearer <token>`
            - API key
                - Use an `api-key` connection header on the 
                    prehandshake connection
                - Use an `api-key` query string parameter on the request URI
                - Query string parameters are encrypted when using https/WSS 
                    (Hypertext Transfer Protocol Secure/Web Socket Secure)

    - WebSocket endpoint
        - Can access resources through a ,
            connection to the Foundry project
        - A direct connection to a model
        - Project connection
            The endpoint is `wss://<your-ai-foundry-resource-name>.services.ai.azure.com/voice-live/realtime?api-version=2025-10-01`
        - Model connection
            The endpoint is `wss://<your-ai-foundry-resource-name>.cognitiveservices.azure.com/voice-live/realtime?api-version=2025-10-01`.
        - The endpoint is the same for all models
        - The difference is the required `model` query parameter
        - When using the Agent service, the `agent_id` and `project_id` parameters

    - Voice Live API events
        - Key client events
            - `session.update`
                Modify session configurations.
            - `input_audio_buffer.append`
                Add audio data to the buffer.
            - `response.create`
                Generate responses via model inference.
        - Server events
            - `session.updated`
                Confirm session configuration changes.
            - `response.done`
                Indicate response generation completion.
            - `conversation.item.created`
                Notify when a new conversation item is added.
            - For a full list of client/server events, 
                visit [Voice live API Reference](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/voice-live-api-reference).

    - Configure session settings for the Voice live API
        - First event sent by the caller on a newly established 
            Voice live API session is the `session.update` event
        - Controls a wide set of input and output behavior
        - Developers can configure
            - Voice types
            - Modalities
            - Turn detection
            - Audio formats
        - Example
            <pre>
            {
                "type": "session.update",
                "session": {
                    "modalities": ["text", "audio"],
                    "voice": {
                    "type": "openai",
                    "name": "alloy"
                    },
                    "instructions": "You are a helpful assistant. Be concise and friendly.",
                    "input_audio_format": "pcm16",
                    "output_audio_format": "pcm16",
                    "input_audio_sampling_rate": 24000,
                    "turn_detection": {
                    "type": "azure_semantic_vad",
                    "threshold": 0.5,
                    "prefix_padding_ms": 300,
                    "silence_duration_ms": 500
                    },
                    "temperature": 0.8,
                    "max_response_output_tokens": "inf"
                }
            }
            <pre>
        - <span>&#x1F4A1;</span>==Use Azure semantic Voice Activity Detection (VAD) for 
            intelligent turn detection and improved conversational flow.==

    - Implement real-time audio processing with the Voice live API
        - Real-time audio processing is a 
            core feature of the Voice live API
        - Developers can
            - Append audio
                Add audio bytes to the input buffer.
            - Commit audio
                Process the audio buffer for transcription or response generation.
            - Clear audio
                Remove audio data from the buffer.
            - Noise reduction and echo cancellation can be 
                configured to enhance audio quality
            - Example
                <pre>
                {
                    "type": "session.update",
                    "session": {
                        "input_audio_noise_reduction": {
                        "type": "azure_deep_noise_suppression"
                        },
                        "input_audio_echo_cancellation": {
                        "type": "server_echo_cancellation"
                        }
                    }   
                }
                </pre>

    - Integrate avatar streaming using the Voice live API
        - The Voice live API supports WebRTC-based avatar 
            streaming for interactive applications
        - Developers can
            - Use the `session.avatar.connect` event to provide the 
                client's Session Description Protoco (SDP) offer.
            - Configure video resolution, bitrate, and codec settings.
            - Define animation outputs such as blendshapes and visemes
        - Example
            <pre>
            {
            "type": "session.avatar.connect",
            "client_sdp": "<client_sdp>"
            }
            </pre>

- **Explore the AI Voice Live client library for Python**

    - Implement authentication
        - Azure AI Voice Live client library for Python provides a real-time, 
            speech-to-speech client for Azure AI Voice Live API
        - Opens a WebSocket session to stream microphone audio to the service
        - Receives server events for responsive conversations
        - <span>&#x1F4A1;</span>==Full reference to the Voice Live package, visit the [voice live Package reference](https://learn.microsoft.com/en-us/python/api/azure-ai-voicelive/azure.ai.voicelive?view=azure-python).==
        - Can implement authentication with
            -  API key
            - Microsoft Entra ID token
        - Assumes environment variables are set in a .env file
        - Example
            <pre><code>
            import asyncio
            from azure.core.credentials import AzureKeyCredential
            from azure.ai.voicelive import connect
            &nbsp;
            async def main():
                async with connect(
                    endpoint="your-endpoint",
                    credential=AzureKeyCredential("your-api-key"),
                    model="gpt-4o"
                ) as connection:
                    # Your async code here
                    pass
            &nbsp;
            asyncio.run(main())
            </code></pre>
        - Example 
            (production applications, Microsoft Entra authentication is recommended)
            <pre><code>
            import asyncio
            from azure.identity.aio import DefaultAzureCredential
            from azure.ai.voicelive import connect
            &nbsp;
            async def main():
                credential = DefaultAzureCredential()
            &nbsp;
                async with connect(
                    endpoint="your-endpoint",
                    credential=credential,
                    model="gpt-4o"
                ) as connection:
                    # Your async code here
                    pass
            &nbsp;
            asyncio.run(main())
            </code></pre>

    - Handling events
        - Proper handling of events ensures a more 
            seamless interaction between the client and agent
        - Case
            - When handling a user interrupting the voice agent 
                you need to cancel agent audio playback immediately in the client
            - If don't, the client continues to play the last agent response until the 
                interrupt is processed in the API &dash;
                &dash; resulting in the agent "talking over" the user
        - Basic event handling
            <pre><code>
            async for event in connection:
                if event.type == ServerEventType.SESSION_UPDATED:
                    print(f"Session ready: {event.session.id}")
                    # Start audio capture
            &nbsp;
                elif event.type == ServerEventType.INPUT_AUDIO_BUFFER_SPEECH_STARTED:
                    print("User started speaking")
                    # Stop playback and cancel any current response
            &nbsp;
                elif event.type == ServerEventType.RESPONSE_AUDIO_DELTA:
                    # Play the audio chunk
                    audio_bytes = event.delta
            &nbsp;
                elif event.type == ServerEventType.ERROR:
                    print(f"Error: {event.error.message}")
            </code></pre>

    - Minimal example
        <pre><code>
        import asyncio
        from azure.core.credentials import AzureKeyCredential
        from azure.ai.voicelive.aio import connect
        from azure.ai.voicelive.models import (
            RequestSession, Modality, InputAudioFormat, OutputAudioFormat, ServerVad, ServerEventType
        )
        &nbsp;
        API_KEY = "your-api-key"
        ENDPOINT = "your-endpoint"
        MODEL = "gpt-4o"
        &nbsp;
        async def main():
            async with connect(
                endpoint=ENDPOINT,
                credential=AzureKeyCredential(API_KEY),
                model=MODEL,
            ) as conn:
                session = RequestSession(
                    modalities=[Modality.TEXT, Modality.AUDIO],
                    instructions="You are a helpful assistant.",
                    input_audio_format=InputAudioFormat.PCM16,
                    output_audio_format=OutputAudioFormat.PCM16,
                    turn_detection=ServerVad(
                        threshold=0.5, 
                        prefix_padding_ms=300, 
                        silence_duration_ms=500
                    ),
                )
                await conn.session.update(session=session)
        &nbsp;
                # Process events
                async for evt in conn:
                    print(f"Event: {evt.type}")
                    if evt.type == ServerEventType.RESPONSE_DONE:
                        break
        &nbsp;
        asyncio.run(main())
        </code></pre>

- **Create a Voice Live agent**

    - Advantages in using agents with Voice Live API
        (over connecting to a model)
        - Agents encapsulate instructions and configuration within the agent itself, 
            rather than specifying instructions in the session code.
        - Agents support complex logic and behaviors, making it easier to manage and 
            update conversational flows without changing the client code.
        - The agent approach streamlines integration. The agent ID is used to connect and 
            all necessary settings are handled internally, reducing the need for manual configuration in the code.
        - Separating agent logic from voice implementation supports better maintainability and 
            scalability for scenarios where multiple conversational experiences or business logic variations are needed.

    - Create a voice agent in the agent playground
        - After enabling voice mode, you can use the 
            **Configuration** pane to enable Voice Live settings
            - Language
                The language spoken and understood by the agent.
            - Advanced settings
                - Voice activity detection (VAD) settings to 
                    detect interruptions and end of speech.
                - Audio enhancement to mitigate background noise and 
                    audio quality.
            - Voice
                The specific voice used by the agent, and advanced 
                voice settings to control the tone and speaking rate.
            - Interim response
                The agent can automatically generate speech while 
                waiting for a model's response.
            - Avatar
                Inclusion of a visual avatar to represent the agent.

    - Create a voice agent using code
        - Create your agent using the
            Foundry SDK for Python
        - Add Voice Live metadata to its definition
        - Example
            <pre><code>
            import os
            import json
            from azure.identity             import DefaultAzureCredential
            from azure.ai.projects          import AIProjectClient
            from azure.ai.projects.models   import PromptAgentDefinition
            &nbsp;
            load_dotenv()
            &nbsp;
            # Setup client
            project_client = AIProjectClient(
                "PROJECT_ENDPOINT",
                credential=DefaultAzureCredential(),
            )
            &nbsp;
            # Define Voice Live session settings
            voice_live_config = {
                "session": {
                    "voice": {
                        "name": "en-US-Ava:DragonHDLatestNeural",
                        "type": "azure-standard",
                        "temperature": 0.8
                    },
                    "input_audio_transcription": {
                        "model": "azure-speech"
                    },
                    "turn_detection": {
                        "type": "azure_semantic_vad",
                        "end_of_utterance_detection": {
                            "model": "semantic_detection_v1_multilingual"
                        }
                    },
                    "input_audio_noise_reduction": {"type": "azure_deep_noise_suppression"},
                    "input_audio_echo_cancellation": {"type": "server_echo_cancellation"}
                }
            }
                    &nbsp;
            # Create agent with Voice Live configuration in metadata
            agent = project_client.agents.create_version(
                agent_name="AGENT_NAME",
                definition=PromptAgentDefinition(
                    model="MODEL_DEPLOYMENT_NAME",
                    instructions="You are a helpful assistant.",
                ),
                metadata=chunk_config(json.dumps(voice_live_config))
            )
            print(f"Agent created: {agent.name} (version {agent.version})")
            &nbsp;
            # Helper function for Voice Live configuration chunking (to handle 512-char metadata limit)
            def chunk_config(config_json: str, limit: int = 512) -> dict:
                """Split config into chunked metadata entries."""
                metadata = {"microsoft.voice-live.configuration": config_json[:limit]}
                remaining = config_json[limit:]
                chunk_num = 1
                while remaining:
                    metadata[f"microsoft.voice-live.configuration.{chunk_num}"] = remaining[:limit]
                    remaining = remaining[limit:]
                    chunk_num += 1
                return metadata
            </code><pre>

    - Use your agent in a client application
        - Need to build a client app that
            1. Connects to the agent
            2. Configures audio hardware input and output
            3. Establishes a Voice live session
            4. Monitors audio systems for activity
            5. Processes events 
                (such as user speech input and responses from the agent)
        - Recommended pattern
            - Use Microsoft Entra ID authentication to 
                connect to the agent in a Microsoft Foundry project.
            - Implement a custom VoiceAssistant class that encapsulates strongly 
                typed agent configuration, defines functions to configure and start the 
                Voice live session, and processes voice events.
            - Implement a custom AudioProcessor class that encapsulates input and 
                output through audio devices.
            - Example 
                (using the PyAudio library for audio input and output)
                <pre><code>
                import os
                import asyncio
                import base64
                import queue
                from dotenv import load_dotenv
                import pyaudio
                from azure.identity.aio import AzureCliCredential
                from azure.ai.voicelive.aio import connect
                from azure.ai.voicelive.models import (
                    InputAudioFormat,
                    Modality,
                    OutputAudioFormat,
                    RequestSession,
                    ServerEventType,
                    AudioNoiseReduction,
                    AudioEchoCancellation,
                    AzureSemanticVadMultilingual
                ) 
                &nbsp;
                # Main program entry point
                def main():
                    """Main entry point."""
                &nbsp;
                    try:
                        # Get required configuration from environment variables
                        load_dotenv()
                        endpoint = os.environ.get("AZURE_VOICELIVE_ENDPOINT")
                        agent_name = os.environ.get("AZURE_VOICELIVE_AGENT_ID")
                        project_name = os.environ.get("AZURE_VOICELIVE_PROJECT_NAME")
                &nbsp;
                        # Create credential for authentication
                        credential = AzureCliCredential()
                &nbsp;
                        # Create and start the voice assistant
                        assistant = VoiceAssistant(
                            endpoint=endpoint,
                            credential=credential,
                            agent_name=agent_name,
                            project_name=project_name
                        )
                &nbsp;
                        # Run the assistant
                        try:
                            asyncio.run(assistant.start())
                        except KeyboardInterrupt:
                            # Exit if the user enters CTRL+C
                            print("\nGoodbye!")
                &nbsp;
                    except Exception as e:
                        print(f"An error occurred: {e}")
                &nbsp;
                # VoiceAssistant class
                class VoiceAssistant:
                    """Main voice assistant - coordinates the conversation"""
                &nbsp;
                    def __init__(self, endpoint, credential, agent_name, project_name):
                        self.endpoint = endpoint
                        self.credential = credential
                &nbsp;
                        # Agent configuration
                        self.agent_config = {
                            "agent_name": agent_name,
                            "project_name": project_name
                        }
                &nbsp;
                    async def start(self):
                        """Start the voice assistant."""
                &nbsp;
                        try:
                            # Connect the agent
                            async with connect(
                                endpoint=self.endpoint,
                                credential=self.credential,
                                api_version="2026-01-01-preview",
                                agent_config=self.agent_config
                            ) as connection:
                                self.connection = connection
                &nbsp;
                                # Initialize audio processor
                                self.audio_processor = AudioProcessor(connection)
                &nbsp;
                                # Configure the session
                                await self.setup_session()
                &nbsp;
                                # Start audio I/O 
                                self.audio_processor.start_playback()
                                print("\nVoice session started...")
                                print("Press Ctrl+C to exit\n")
                &nbsp;
                                # Process events
                                await self.process_events()
                &nbsp;
                        finally:
                            if hasattr(self, 'audio_processor'):
                                self.audio_processor.shutdown()
                &nbsp;
                    async def setup_session(self):
                        """Configure the session with audio settings."""
                &nbsp;
                        session_config = RequestSession(
                            # Enable both text and audio
                            modalities=[Modality.TEXT, Modality.AUDIO],
                &nbsp;
                            # Audio format (16-bit PCM at 24kHz)
                            input_audio_format=InputAudioFormat.PCM16,
                            output_audio_format=OutputAudioFormat.PCM16,
                &nbsp;
                            # Voice activity detection (when to detect speech)
                            turn_detection=AzureSemanticVadMultilingual(),
                &nbsp;
                            # Prevent echo from speaker feedback
                            input_audio_echo_cancellation=AudioEchoCancellation(),
                &nbsp;
                            # Reduce background noise
                            input_audio_noise_reduction=AudioNoiseReduction(type="azure_deep_noise_suppression")
                        )
                &nbsp;
                        await self.connection.session.update(session=session_config)
                        print("Session configured")
                &nbsp;
                    async def process_events(self):
                        """Process events from the VoiceLive service."""
                &nbsp;
                        # Listen for events from the service
                        async for event in self.connection:
                            await self.handle_event(event)
                &nbsp;
                    async def handle_event(self, event):
                        """Handle different event types from the service."""
                &nbsp;
                        # Session is ready - start capturing audio
                        if event.type == ServerEventType.SESSION_UPDATED:
                            print(f"Connected to agent: {event.session.agent.name}")
                            self.audio_processor.start_capture()
                &nbsp;
                        # User speech was transcribed
                        elif event.type == ServerEventType.CONVERSATION_ITEM_INPUT_AUDIO_TRANSCRIPTION_COMPLETED:
                            print(f'You: {event.get("transcript", "")}')
                &nbsp;
                        # Agent is responding with audio transcript
                        elif event.type == ServerEventType.RESPONSE_AUDIO_TRANSCRIPT_DONE:
                            print(f'Agent: {event.get("transcript", "")}')
                &nbsp;
                        # User started speaking (interrupt any playing audio)
                        elif event.type == ServerEventType.INPUT_AUDIO_BUFFER_SPEECH_STARTED:
                            self.audio_processor.clear_playback_queue()
                            print("Listening...")
                &nbsp;
                        # User stopped speaking
                        elif event.type == ServerEventType.INPUT_AUDIO_BUFFER_SPEECH_STOPPED:
                            print("Thinking...")
                &nbsp;
                        # Receiving audio response chunks
                        elif event.type == ServerEventType.RESPONSE_AUDIO_DELTA:
                            self.audio_processor.queue_audio(event.delta)
                &nbsp;
                        # Audio response complete
                        elif event.type == ServerEventType.RESPONSE_AUDIO_DONE:
                            print("Response complete\n")
                &nbsp;
                        # Handle errors
                        elif event.type == ServerEventType.ERROR:
                            print(f"Error: {event.error.message}")
                &nbsp;
                # AudioProcessor class
                class AudioProcessor:
                    """Handles audio input (microphone) and output (speakers) """
                &nbsp;
                    def __init__(self, connection):
                        self.connection = connection
                        self.audio = pyaudio.PyAudio()
                &nbsp;
                        # Audio settings: 24kHz, 16-bit PCM, mono
                        self.format = pyaudio.paInt16
                        self.channels = 1
                        self.rate = 24000
                        self.chunk_size = 1200  # 50ms chunks
                &nbsp;
                        # Streams for input and output
                        self.input_stream = None
                        self.output_stream = None
                        self.playback_queue = queue.Queue()
                &nbsp;
                    def start_capture(self):
                        """Start capturing audio from the microphone."""
                &nbsp;
                        def capture_callback(in_data, frame_count, time_info, status):
                            # Convert audio to base64 and send to VoiceLive
                            audio_base64 = base64.b64encode(in_data).decode("utf-8")
                            asyncio.run_coroutine_threadsafe(
                                self.connection.input_audio_buffer.append(audio=audio_base64),
                                self.loop
                            )
                            return (None, pyaudio.paContinue)
                &nbsp;
                        # Store event loop for use in callback thread
                        self.loop = asyncio.get_event_loop()
                &nbsp;
                        self.input_stream = self.audio.open(
                            format=self.format,
                            channels=self.channels,
                            rate=self.rate,
                            input=True,
                            frames_per_buffer=self.chunk_size,
                            stream_callback=capture_callback
                        )
                        print("Microphone started")
                &nbsp;
                    def start_playback(self):
                        """Start audio playback system."""
                &nbsp;
                        remaining = bytes()
                &nbsp;
                        def playback_callback(in_data, frame_count, time_info, status):
                            nonlocal remaining
                &nbsp;
                            # Calculate bytes needed
                            bytes_needed = frame_count * pyaudio.get_sample_size(pyaudio.paInt16)
                            output = remaining[:bytes_needed]
                            remaining = remaining[bytes_needed:]
                &nbsp;
                            # Get more audio from queue if needed
                            while len(output) < bytes_needed:
                                try:
                                    audio_data = self.playback_queue.get_nowait()
                                    if audio_data is None:  # End signal
                                        break
                                    output += audio_data
                                except queue.Empty:
                                    # Pad with silence if no audio available
                                    output += bytes(bytes_needed - len(output))
                                    break
                &nbsp;
                            # Keep any extra for next callback
                            if len(output) > bytes_needed:
                                remaining = output[bytes_needed:]
                                output = output[:bytes_needed]
                &nbsp;
                            return (output, pyaudio.paContinue)
                &nbsp;
                        self.output_stream = self.audio.open(
                            format=self.format,
                            channels=self.channels,
                            rate=self.rate,
                            output=True,
                            frames_per_buffer=self.chunk_size,
                            stream_callback=playback_callback
                        )
                        print("Speakers ready")
                &nbsp;
                    def queue_audio(self, audio_data):
                        """Add audio data to the playback queue."""
                        self.playback_queue.put(audio_data)
                &nbsp;
                    def clear_playback_queue(self):
                        """Clear any pending audio (used when user interrupts)."""
                        while not self.playback_queue.empty():
                            try:
                                self.playback_queue.get_nowait()
                            except queue.Empty:
                                break
                &nbsp;
                    def shutdown(self):
                        """Clean up audio resources."""
                        if self.input_stream:
                            self.input_stream.stop_stream()
                            self.input_stream.close()
                &nbsp;
                        if self.output_stream:
                            self.playback_queue.put(None)  # Signal end
                            self.output_stream.stop_stream()
                            self.output_stream.close()
                &nbsp;
                        self.audio.terminate()
                        print("Audio stopped")
                &nbsp;
                if __name__ == "__main__":
                    main()
                </code></pre>

- **Further reading**
    - [What is the Speech service?](https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/)
    - [How to customize voice live input and output](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/voice-live-how-to-customize)

- **Exercise - Develop a Voice Live agent**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-language/Instructions/Exercises/06-voice-live-agent.html)


### 7. [Translate text and speech with Microsoft Foundry Tools](https://learn.microsoft.com/en-us/training/modules/translate-text-speech/)


- **Introduction**

    - AI-Powered Translation Solutions
        - The Global Communication Challenge
            As organizations expand globally, the ability to exchange information seamlessly across 
            different languages becomes a critical business requirement.
        - Limitations of Traditional Translation
            Manual translation is a specialized skill that can be highly time-consuming and expensive to 
            scale for enterprise-level demands.
        - The Role of Machine Translation
            Automated translation reduces these barriers but requires highly sophisticated software 
            capable of grasping complex linguistic nuances, grammatical rules, and cultural idioms.
        - AI as a Translation Engine
            Modern solutions place AI models at the core of the translation process, enabling both 
            text-based document translation and real-time speech conversion.
        - Module Objectives
            In this module, you will learn to leverage the Microsoft Foundry ecosystem to design, 
            build, and deploy robust, AI-powered translation solutions that overcome traditional language barriers.

- **Translation in Microsoft Foundry**

    - How translations works in Microsoft Foundry
        - Comprehensive multi-language translation solutions 
            generally require specialized models
        - Support for translation through Foundry Tools
            - Azure Translator in Foundry Tools
                A comprehensive translation service for text, with a wide range of 
                supported languages and the ability to create custom translation models.
            - Azure Speech in Foundry Tools
                A suite of speech-related tools, including speech-to-text and speech-to-speech 
                translation in multiple languages simultaneously.
        - Are accessible through a Microsoft Foundry resource endpoint
        - Provide extensive APIs 
        - Can be used with language-specific SDKs

- **Translate text**

    - What is Azure Translator
        - Provides an API for translating text between 
            over 90 supported languages
        - Can
            - Translate or transliterate text using the default 
                translation model or a large language model (LLM).
            - Translate documents, synchronously or asynchronously, 
                while maintaining document structure.
            - Use custom translation models to translate 
                domain-specific terms.
        - <span>&#x1F4A1;</span>==Find out more about the full range of Azure Translator capabilities in the [Azure Translator in Foundry Tools documentation](https://learn.microsoft.com/en-us/azure/ai-services/translator).==


    - Use Azure Translator in the Microsoft Foundry portal
        - Playgrounds for
            - Text translation
            - Document translation

    - Use Azure Translator in application code
        - Can use the [REST API](https://learn.microsoft.com/en-us/azure/ai-services/translator/text-translation/reference/rest-api-guide) to call Azure Translator functions
        - Can use one of the SDKs
            - [Azure Translator Text Translation Client for Python](https://pypi.org/project/azure-ai-translation-text/1.0.1/)
            - [Azure Translator Text Translation Client for Microsoft .NET](https://www.nuget.org/packages/Azure.AI.Translation.Text/1.0.0)
            - [Azure Translator Text Translation Client for Java](https://mvnrepository.com/artifact/com.azure/azure-ai-translation-text/1.0.0)
            - [Azure Translator Text Translation Client for JavaScript](https://www.npmjs.com/package/@azure-rest/ai-translation-text/v/1.0.0)

    - Connect to an Azure Translator resource
        - Azure Translator APIs are served through REST endpoints
        - The client must make an authenticated connection
        - Endpoint can be
            - The Azure Translator **global** endpoint
                `api.cognitive.microsofttranslator.com`
            - Azure Translator **regional** endpoints
                These endpoints include 
                - `api-nam.cognitive.microsofttranslator.com`
                - `api-apc.cognitive.microsofttranslator.com`
                - `api-eur.cognitive.microsofttranslator.com`
            - Foundry resource endpoints
                `{foundry-resource-name}.cognitiveservices.azure.com/`
        - Example
            <pre><code>
            from azure.core.credentials import AzureKeyCredential
            from azure.ai.translation.text import *
            &nbsp;
            key_credential = AzureKeyCredential("FOUNDRY_KEY")
            &nbsp;
            # Connect to a Foundry resource endpoint
            client = TextTranslationClient(credential=key_credential, endpoint="FOUNDRY_ENDPOINT")
            &nbsp;
            # Or connect using a region
            client = TextTranslationClient(credential=key_credential, region="FOUNDRY_REGION")
            </code></pre>
        - <span>&#x1F4A1;</span>==For more information about the **TextTranslationClient** constructor, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Translator Python SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-ai-translation-text/azure.ai.translation.text.texttranslationclient#constructor).==

    - Determine available languages
        - Azure Translator supports over 90 languages
        - Example
            (list of available languages for translation)
            <pre><code>
            languages = client.get_supported_languages(scope="translation")
            print("{} languages supported:".format(len(languages.translation)))
            for language in languages.translation.keys():
                print(languages.translation[language].name + " (" + language + ")")
            </code></pre>
            - Result
                (name and ISO code for each language)
                <pre>
                137 languages supported:
                Afrikaans (af)
                Amharic (am)
                Arabic (ar)
                Assamese (as)
                Azerbaijani (az)
                Bashkir (ba)
                Belarusian (be)
                Bulgarian (bg)
                ...
                </pre>
         - <span>&#x1F4A1;</span>==For more information about the **get_supported_language** method, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Translator Python SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-ai-translation-text/azure.ai.translation.text.texttranslationclient#azure-ai-translation-text-texttranslationclient-get-supported-languages).==

    - Translate text
        - Use `translate` method
            - Source text is passed into the method as a list of **InputTextItem** objects, 
                each containing a text string to be translated.
            - You can optionally specify a **from_language** parameter with the ISO code for the 
                source language (for example, "en"); or you can omit this parameter to have 
                Azure Translator automatically detect the source language.
            - Target languages as specified as a list of language codes in the 
                **to_language** parameter - Azure Translator will return a translation for 
                each valid language code.
        - Example
            <pre><code>
            input_text_elements = [InputTextItem(text="Hola"), InputTextItem(text="こんにちは")]
            translation_results = client.translate(body=input_text_elements, to_language=["fr", "en"])
            idx = 0
            for translation in translation_results:
                input_text = input_text_elements[idx].text
                idx += 1
                sourceLanguage = translation.detected_language
                for translated_text in translation.translations:
                    print(f"'{input_text}' was translated from {sourceLanguage.language} to {translated_text.to} as '{translated_text.text}'.")
            </code></pre>
            - Result
                <pre>
                'Hola' was translated from es to fr as 'Bonjour'.
                'Hola' was translated from es to en as 'Hello'.
                'こんにちは' was translated from ja to fr as 'Bonjour'.
                'こんにちは' was translated from ja to en as 'Hello'.
                </pre>
        - <span>&#x1F4A1;</span>==For more information about the **translate ** method, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Translator Python SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-ai-translation-text/azure.ai.translation.text.texttranslationclient#azure-ai-translation-text-texttranslationclient-translate).==

    - Transliterate text
        - When want to transliterate it to a different script
            (for example to render the Japanese words in Latin script)
        - Example
            <pre><code>
            source_text = "こんにちは"
            input_text_elements = [InputTextItem(text=source_text)]
            transliteration_results = client.transliterate(body=input_text_elements, language="ja",
                                                        from_script="Jpan", to_script="Latn")
            for transliteration in transliteration_results:
                sourceScript = transliteration.script
                targetScript = transliteration.text
                print(f"'{source_text}' was transliterated into {sourceScript} as {targetScript}.")
            </code></pre>
            - Result
                <pre>
                'こんにちは' was transliterated into Latn as Kon'nichiwa​.
                </pre>
        - <span>&#x1F4A1;</span>==For more information about the **transliterate** method, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Translator Python SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-ai-translation-text/azure.ai.translation.text.texttranslationclient#azure-ai-translation-text-texttranslationclient-transliterate).==

- **Translate speech**

    - Use Azure Speech translation in application code
        - The **Speech Translation API** enables you to build solutions that 
            translate spoken input and return the translation as text or speech
        - Can use from your application code through the 
            **TranslationRecognizer** object
        - Can create by connecting to your Azure Speech 
            resource using a **SpeechTranslationConfig** object

    - Connect to an Azure Speech resource
        - To use the Azure Speech Translation API in client code
        - Must use a SpeechTranslationConfig object
        - To connect to an Azure Speech resource
        - Can connect by specifying the relevant **endpoint** or 
            **region** for your resource
        - Example
            <pre><code>
            import azure.cognitiveservices.speech as speech_sdk
            &nbsp;
            # Connect to a Foundry resource endpoint
            translation_cfg = speech_sdk.translation.SpeechTranslationConfig(
                                subscription="FOUNDRY_KEY", endpoint="FOUNDRY_ENDPOINT")
            &nbsp;
            # Or connect using a region
            translation_cfg = speech_sdk.translation.SpeechTranslationConfig(
                                subscription="FOUNDRY_KEY", region="FOUNDRY_REGION")
            </code></pre>
        - <span>&#x1F4A1;</span>==For more information about the **SpeechTranslationConfig** constructor, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Speech Python SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-cognitiveservices-speech/azure.cognitiveservices.speech.translation.speechtranslationconfig#constructor).==

    - Configure translation languages and input
        - Azure Speech can translate spoken audio input to 
            one or more languages
        - Use the **SpeechTranslationConfig** object to configure the source and target languages
        - Use an **AudioConfig** object to specify the source audio stream
        - Example
            (Configures the **SpeechTranslationConfig** object for translation
             From US English (en-US) to French (fr) and Japanese (ja)
             Uses an **AudioConfig** object to specify the source audio as 
             coming from the default system microphone)
             <pre><code>
            # Configure languages
            translation_cfg.speech_recognition_language = 'en-US'
            translation_cfg.add_target_language('fr')
            translation_cfg.add_target_language('ja')
            print('Ready to translate from',translation_cfg.speech_recognition_language)
            &nbsp;
            # Configure audio source
            audio_cfg = speech_sdk.AudioConfig(use_default_microphone=True)
             </code></pre>
        - <span>&#x1F4A1;</span>==For more information about the **AudioConfig** class, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Speech Python SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-cognitiveservices-speech/azure.cognitiveservices.speech.audio.audioconfig).==

    - Translate speech to text
        - Translate spoken input using a **TranslationRecognizer** object
        - Example
            <pre><code>
            # Get a TranslationRecognizr object
            translator = speech_sdk.translation.TranslationRecognizer(translation_config=translation_cfg,
                                                                    audio_config=audio_cfg)
            # Get input from mic and translate
            print("Speak now...")
            translation_results = translator.recognize_once_async().get()
            print(f"Translating '{translation_results.text}'")
            &nbsp;
            # Print each translation
            translations = translation_results.translations
            for translation_language in translations:
                print(f"{translation_language}: '{translations[translation_language]}'")
            </code></pre>
            - Result
                (saying "hello" into the microphone)
                <pre>
                Speak now...
                Translating 'Hello.'
                fr: 'Bonjour.'
                ja: 'こんにちは。'
                </pre>
        - <span>&#x1F4A1;</span>==For more information about the **TranslationRecognizer ** class, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Speech Python SDK documentation](https://learn.microsoft.com/en-us/python/api/azure-cognitiveservices-speech/azure.cognitiveservices.speech.translation.translationrecognizer).==

    - Synthesize translations as speech
        - Implement speech-to-speech translation by
            - Manual synthesis
                - Manual synthesis is a straightforward way to 
                    synthesize the results of speech translation
                - Is the combination of two separate operations
                    1. Use a **TranslationRecognizer** to translate spoken input into 
                        text transcriptions in one or more target languages.
                    2. Iterate through the **Translations** in the result of the translation operation, 
                        using a **SpeechSynthesizer** to synthesize an audio stream for each language.
                - Example
                    <pre><code>
                    import azure.cognitiveservices.speech as speech_sdk
                    &nbsp;
                    # Configure translation
                    translation_cfg = speech_sdk.translation.SpeechTranslationConfig(subscription="FOUNDRY_KEY",
                                                                                    endpoint="FOUNDRY_ENDPOINT")
                    translation_cfg.speech_recognition_language = 'en-US'
                    translation_cfg.add_target_language('fr')
                    translation_cfg.add_target_language('ja')
                    audio_cfg = speech_sdk.AudioConfig(use_default_microphone=True)
                    &nbsp;
                    # Configure speech synthesis
                    speech_cfg = speech_sdk.SpeechConfig(subscription="FOUNDRY_KEY", 
                                                        endpoint="FOUNDRY_ENDPOINT")
                    audio_out_cfg = speech_sdk.audio.AudioOutputConfig(use_default_speaker=True)
                    voices = {
                            "fr": "fr-FR-HenriNeural",
                            "ja": "ja-JP-NanamiNeural"
                    }
                    &nbsp;
                    # Get trsnslations
                    translator = speech_sdk.translation.TranslationRecognizer(translation_config=translation_cfg,
                                                                            audio_config=audio_cfg)
                    print("Speak now...")
                    translation_results = translator.recognize_once_async().get()
                    print(f"Translating '{translation_results.text}'")
                    &nbsp;
                    # process the translation results
                    translations = translation_results.translations
                    for translation_language in translations:
                    &nbsp;
                        # Print ressults
                        print(f"{translation_language}: '{translations[translation_language]}'")
                    &nbsp;
                        # Speak results
                        speech_cfg.speech_synthesis_voice_name = voices.get(translation_language)
                        speech_synthesizer = speech_sdk.SpeechSynthesizer(speech_cfg, audio_out_cfg)
                        speak = speech_synthesizer.speak_text_async(translations[translation_language]).get()
                    &nbsp;
                        # CHeck for speech failure
                        if speak.reason != speech_sdk.ResultReason.SynthesizingAudioCompleted:
                            print(speak.reason)
                    </code></pre>
                - Need to create a **SpeechConfig** object for the speech synthesis API
                - Need to create an **AudioConfig** to direct the spoken output to the default speaker
                - Can also specify language-specific voices to optimize pronunciation
            - Event-based synthesis
                - Translating from one source language into a 
                    single target language
                - Use event-based synthesis to capture the 
                    translation as an audio stream
                - Need to
                    - Specify the desired voice for the translated speech in the **TranslationConfig**.
                    - Create an event handler for the **TranslationRecognizer** object's **Synthesizing** event.
                    - In the event handler, use the **GetAudio()** method of the **Result** parameter to 
                        retrieve the byte stream of translated audio.
                - <span>&#9888;</span>==You can't use event-based synthesis for multi-language translation.==
                - Example
                    <pre><code>
                    import azure.cognitiveservices.speech as speech_sdk
                    from playsound3 import playsound
                    &nbsp;
                    # Configure translation
                    source_language, target_language = "en-US", "fr"
                    output_file = "translation.wav"
                    translation_cfg = speech_sdk.translation.SpeechTranslationConfig(subscription="FOUNDRY_KEY",
                                                                                    endpoint="FOUNDRY_ENDPOINT")
                    translation_cfg.speech_recognition_language = source_language
                    translation_cfg.add_target_language(target_language)
                    translation_cfg.voice_name = "fr-FR-HenriNeural"
                    audio_cfg = speech_sdk.AudioConfig(use_default_microphone=True)
                    translator = speech_sdk.translation.TranslationRecognizer(translation_config=translation_cfg,
                                                                            audio_config=audio_cfg)
                    &nbsp;
                    # Event handler function to save the synthesized audio to a file
                    def synthesis_callback(evt):
                        size = len(evt.result.audio)
                        print(f'Audio synthesized: {size} byte(s) {"(COMPLETED)" if size == 0 else ""}')
                    &nbsp;
                        if size > 0:
                            file = open(output_file, 'wb+')
                            file.write(evt.result.audio)
                            file.close()
                    &nbsp;
                    # Connect the event handler function
                    translator.synthesizing.connect(synthesis_callback)
                    &nbsp;
                    # Get input from mic and translate it
                    print(f"Speak now (in {source_language})...")
                    translation_results = translator.recognize_once()
                    print(f"Translating '{translation_results.text}'")
                    &nbsp;
                    # Print and play the translation results
                    print(translation_results.translations[target_language])
                    playsound(output_file)
                    </code></pre>
            - <span>&#x1F4A1;</span>==For more information about synthesizing translations, see the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Azure Speech Python SDK documentation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/how-to-translate-speech?tabs=terminal&pivots=programming-language-python#synthesize-translations).==

- **Furtheer reading**
    - [Azure Translator in Foundry Tools documentation](https://learn.microsoft.com/en-us/azure/ai-services/translator)
    - [Azure Speech in Foundry Tools translation documentation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-translation)

- **Exercise - Translate text and speech**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-language/Instructions/Exercises/07-translation.html)




## Extract insights from visual data on Azure

- [`Documentação oficial`](https://learn.microsoft.com/en-us/training/paths/insight-visual-data/)

### 1. [Develop a vision-enabled generative AI application](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-vision-apps/)

- **Introduction**
    - Generative AI models are transforming how intelligent chat-based applications are developed.
    - Modern AI systems can reason over user input and generate context-aware responses.
    - Traditionally, generative AI relied mainly on **text-based prompts** for interaction.
    - Advances in multimodal AI now allow models to process and understand **both text and visual content**.
    - Vision-enabled generative AI expands the possibilities for creating richer and more interactive applications.
    - Microsoft Foundry provides tools and services for building multimodal generative AI solutions.
    - Developers can create applications that respond to prompts containing a combination of **text and image data**.
    - Multimodal AI enables more natural, intuitive, and intelligent human-computer interactions.

- **Use a vision-capable model in the Microsoft Foundry portal**

    - Testing multimodal models with image-based prompts
        - _Multimodal_ generative AI model supports inputs
            - Text-based
            - Image-based
            - Audio-based
        - Multimodels available in Foundry
            - Microsoft Phi-4-multimodal-instruct
            - OpenAI gpt-4.1
            - OpenAI gpt-4.1-mini
        - After deploying a multimodal model, you can test it in the 
            chat playground
        - In the chat playground, you can upload an image from a local file and 
            add text to the message to elicit a response from a multimodal model.
        - <span>&#x1F4A1;</span>==To learn more about available models in Microsoft Foundry, see the
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft Foundry Models overview](https://learn.microsoft.com/en-us/azure/foundry/concepts/foundry-models-overview)article in the Microsoft Foundry documentation.==

- **Develop a vision-based chat app**

    - Submit an image-based prompt using the **Responses API**
        - Can use the same basic techniques 
            used for text-based chats 
        - Require a connection to the endpoint where the 
            model is deployed
        - Use that endpoint to submit prompts
        - Prompts for a vision-based chat
            - Include multi-part user messages
            - Contain a _text_ content
            - Contain a _image_ content
        - Example
            (submit an image in a prompt using the Responses API)
            <pre><code>
            # Read the image data from a local file
            image_path = Path("dragon-fruit.jpeg")
            image_format = "jpeg"
            with open(image_path, "rb") as image_file:
                image_data = base64.b64encode(image_file.read()).decode("utf-8")
            &nbsp;
            data_url = f"data:image/{image_format};base64,{image_data}" # You can also use a web URL
            &nbsp;
            # Send the image data in a prompt to the model
            response = client.responses.create(
                model="gpt-4.1",
                input=[
                    {"role": "developer", "content": "You are an AI assistant for chefs planning recipes."},
                    {"role": "user", "content": [  
                        { "type": "input_text", "text": "What desserts could I make with this?"},
                        { "type": "input_image", "image_url": data_url}
                    ] } 
                ]
            )
            print(response.output_text)
            </code><pre>

    - Submit an image-based prompt using the **ChatCompletions API**
        - Submit prompts to models that don't 
            support the Responses API
        - Example
            <pre><code>
            # Read the image data from a local file
            image_path = Path("orange.jpeg")
            image_format = "jpeg"
            with open(image_path, "rb") as image_file:
                image_data = base64.b64encode(image_file.read()).decode("utf-8")
            &nbsp;
            data_url = f"data:image/{image_format};base64,{image_data}" # You can also use a web URL
            &nbsp;
            # Send the image data in a prompt to the model
            response = client.chat.completions.create(
                model="Phi-4-multimodal-instruct",
                messages=[
                    {"role": "system", "content": "You are an AI assistant for chefs planning recipes."},
                    { "role": "user", "content": [  
                        { "type": "text", "text": "What can I make with this fruit?"},
                        { "type": "image_url", "image_url": {"url": data_url}}
                    ] }
                ]
            )
            print(response.choices[0].message.content)
            </code></pre>

- **Further reading**
    - [Images and vision](https://developers.openai.com/api/docs/guides/images-vision?format=url#analyze-images?azure-portal=true)

- **Exercise - Develop a vision-enabled chat app**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-vision/Instructions/Exercises/01-gen-ai-vision.html)

### 2. [Generate images with AI](https://learn.microsoft.com/en-us/training/modules/generate-images-azure-openai/)

- **Introduction**
    - Microsoft Foundry enables developers to use language models to generate content from natural language prompts.
    - Generative AI is evolving beyond text generation to support the creation of visual and graphical content.
    - Models such as OpenAI gpt-image-1 can generate original images based on descriptive prompts.
    - AI-powered image generation allows users to transform ideas and descriptions into visual assets automatically.
    - Generated graphics can range from illustrations to highly realistic photorealistic images.
    - AI image generation has multiple business and creative applications, including
        - Marketing and advertising materials
        - Article and presentation illustrations
        - Product and company logo creation
        - Custom creative design assets
    - Generative AI simplifies and accelerates the creative process by reducing the need for manual graphic design work.
    - Natural language prompting makes image creation more accessible to users without advanced design skills.

- **What are image-generation models?**

    - Models that are capable of generating images
        - The OpenAI gpt-image-1 series of models.
        - The Black Forest Labs FLUX series of models.
        - <span>&#x1F4A1;</span>==View the [Model catalog](https://ai.azure.com/catalog/models) for the full set of models available in Microsoft Foundry.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the Foundry portal you can filter by inference task to find _text to image_ models.==
        - Image generation models are generative AI model that can 
            create graphical data from natural language input.
        - The images generated are original
        - The model generates new images based on the 
            data on which it was trained

- **Explore image-generation models in Microsoft Foundry portal**

    - How to explore
        - Create a Microsoft Foundry project
        - Use the model playground
            - To submit prompts
            - View the resulting generated images
        - Can specify the resolution (size) of the 
            generated images
        - Can include a reference image for the 
            model to base it's output on

- **Create a client application that uses an image generation model**

    - How to create a client app
        - Use a language-specific SDK
            (for example, the OpenAI Python SDK or the 
            Azure OpenAI .NET SDK)
        - Example
            (usingthe OpenAI Images API)
            <pre><code>
            # Generate an image
            img_results = client.images.generate(
                model="FLUX.1-Kontext-pro",
                prompt="A robot eating a cheeseburger.",
                n=1,
                size="1024x1024",
            )
            &nbsp;
            # Save the generated image
            image_data = base64.b64decode(img_results.data[0].b64_json)
            with open("image.png", "wb") as image_file:
                image_file.write(image_data)
            </code></pre>
            - Result
                Binary stream containing the requested image


- **Exercise - Generate images with AI**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-vision/Instructions/Exercises/02-generate-image.html)



### 3. [Generate videos with Microsoft Foundry](https://learn.microsoft.com/en-us/training/modules/generate-video-with-foundry/)

- **Introduction**
    - Generative AI is rapidly evolving from text and image generation to **AI-powered video creation**.
    - Microsoft Foundry integrates advanced video-generation capabilities through Sora 2.
    - Sora 2 can generate realistic and creative video scenes using:
        - Text prompts
        - Reference images
        - Existing videos for remixing and transformation
    - AI-generated video enables faster and more accessible content creation for creative and business use cases.
    - Effective prompt engineering plays a key role in producing high-quality and accurate video outputs.
    - Developers can deploy and integrate Sora 2 into custom applications and workflows.
    - The module demonstrates how to build video-generation solutions programmatically using the OpenAI SDK and Python.
    - AI video generation opens opportunities for:
        - Marketing and advertising content
        - Storytelling and entertainment
        - Educational media
        - Creative prototyping and visualization
    - Programmatic video generation enables automation, scalability, and integration into enterprise applications.

- **Deploy a video generating model**

    - Prerequisites
        - Sora 2 is an AI model from OpenAI that 
            creates realistic and imaginative video scenes from
            - Text instructions
            - Input images
            - Existing videos
        - Before deploying
            - An Azure subscription
            - Access to the Microsoft Foundry portal
            - Foundry project where you have 
                permissions to deploy models

    - Deploy the Sora 2 model
        1. Go to the [Microsoft Foundry portal](https://ai.azure.com/) and sign in with your credentials.
        2. From the Foundry landing page, create or select a project.
        3. Select **Build** from the navigation pane on the right.
        4. Select **Models** from the left-hand menu to view the model catalog.
        5. Use the search bar or filter options to find the **Sora-2** video generation model.
        6. Select the **Sora-2** model then select **Deploy** and choose the appropriate deployment settings.
        7. <span>&#x1F4A1;</span>==To learn more about available models in Microsoft Foundry, see the
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Model catalog and collections in Microsoft Foundry portal](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/model-catalog-overview) article in the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft Foundry documentation.==

    - Sora 2 capabilities
        | Feature | Description |
        |:-|:-|
        |Text to video|Generate videos from natural language text prompts|
        |Image to video|Transform existing images into video content|
        |Video remix|Make targeted adjustments to existing videos without<br/>regenerating from scratch|
        |Audio generation|Supports audio generation in output videos|
        |Multiple resolutions|Supports portrait (720×1280) and<br/>landscape (1280×720) formats|
        |Variable duration|Generate videos of 4, 8, or 12 seconds|

- **Generate video from a prompt**

    - Video generation parameters
        | Parameter | Description | Supported Values
        |:-|:-|:-|
        |prompt|Natural language description of<br/>your video|Text string (required)|
        |model|The model to use|`sora-2` or `sora-2-pro`|
        |size|Output resolution|`1280x720` (landscape),<br/>`720x1280` (portrait)|
        |seconds|Video duration|`4`, `8`, or<br/>`12` (default: 4)|
        |input_reference|Reference image for the first frame|JPEG, PNG, or<br/>WebP file|
        |remix_video_id|ID of a previous video to remix|Video ID string|

        <br/>

        <span>&#x1F4A1;</span>==The model follows instructions more reliably in shorter clips. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For best results, consider generating two 4-second clips and
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;stitching them together rather than a single 8-second clip.==

    - Test video generation in the playground
        1. Navigate to your deployed Sora 2 model in the Foundry portal.
        2. Select the **Playground** tab to access the video generation interface.
        3. Enter your prompt into the text box describing the video you want to generate.
        4. Configure video settings such as resolution and duration.
        5. Select **Generate** to start video creation.
        6. Video generation typically takes 1 to 5 minutes depending on your settings.
        7. Can also view cURL code samples that are prefilled according to your settings
        8. Select the View code button at the top of the playground to 
            access sample code you can use in your applications.
        9. <span>&#x1F4A1;</span>==The content generation APIs include a content moderation filter. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If Azure OpenAI recognizes your prompt as harmful content, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;it won't return a generated video.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For more information, see [Content filtering](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/content-filter).==

    - Writing effective prompts
        - Prompt anatomy
            - The more specific you are about what the shot should achieve~
                the more control and consistency you'll get
            - Camera framing
                Specify the shot type (wide, medium, close-up) and angle
            - Subject description
                Anchor your subject with distinctive details
            - Action
                Describe movement in beats—small steps, gestures, or pauses
            - Lighting and palette
                Set the mood with lighting direction and color anchors
            - Style
                Establish the aesthetic early (for example, "1970s film" or "handheld documentary")

        - Weak vs. strong prompts
            | Weak prompt | Strong prompt |
            |:-|:-|
            |"A beautiful street at night"|"Wet asphalt, zebra crosswalk, neon signs reflecting in puddles"|
            |"Person moves quickly"|"Cyclist pedals three times, brakes, and stops at crosswalk"|
            |"Cinematic look"|"Anamorphic 2.0x lens, shallow DOF, volumetric light"|
        
        - Example prompt
            <pre>
            In a 90s documentary-style interview, an old Swedish man sits in a study 
            and says, "I still remember when I was young."
            </pre>
            - Why it works
                - "90s documentary" 
                    sets the style, so the model chooses 
                    appropriate camera, lighting, and color
                - "old Swedish man sits in a study" 
                    describes subject and setting while allowing 
                    creative interpretation
                - The dialogue gives the model specific words to 
                    sync with the character

    - Using reference images
        - For more control over composition and style
            use the `input_reference` parameter
        - The model uses the image as an anchor for the 
            first frame
        - The prompt defines what happens next
        - Requirements
            - The image resolution must match the 
                target video size (`1280x720` or `720x1280`)
            - Supported formats
                - JPEG
                - PNG
                - WebP

    - Remixing existing videos
        - The remix feature lets you modify specific aspects of an 
            existing video while preserving its core elements
            - Scene transitions
            - Visual layout
            - Overall structure
        - To remix a video
            1. Generate a video and note its video ID from the completed job
            2. Call the remix endpoint with the original video ID and an updated prompt
            3. Describe only the changes you want &mdash; keep modifications focused
        - For best results
            - Limit changes to one clearly articulated adjustment
            - Be specific about what to change
                - "same shot, switch to 85mm lens"
                - "same lighting, new palette: teal, sand, rust"
            - Narrow, precise edits retain greater fidelity to the source material

    - Tips for better results
        - Keep it simple
            Each shot should have one clear camera move and one clear subject action
        - Use beats for timing
            Instead of "actor walks across the room," 
            try "actor takes four steps to the window, pauses, and pulls the curtain"
        - Be consistent
            Reuse phrasing for characters across shots to maintain continuity
        - Iterate
            Small changes to camera, lighting, or 
            action can shift outcomes dramatically &dash;
            &dash; treat each generation as a creative variation

- **Generate video in Python**

    - Generate a video
        - Video generation is an 
            asynchronous process
            - Submit a job
            - Poll for completion
            - Download the result
        - Example
            <pre><code>
            import time
            &nbsp;
            # Create the video generation job
            video = client.videos.create(
                model="sora-2",
                prompt="A robot walks through a rainy city street at dusk, neon signs reflecting in puddles",
                size="1280x720",
                seconds="4",
            )
            &nbsp;
            print(f"Video creation started. ID: {video.id}")
            &nbsp;
            # Poll for completion
            while video.status not in ["completed", "failed", "cancelled"]:
                print(f"Status: {video.status}. Waiting...")
                time.sleep(20)
                video = client.videos.retrieve(video.id)
            &nbsp;
            # Download when complete
            if video.status == "completed":
                content = client.videos.download_content(video.id, variant="video")
                content.write_to_file("output.mp4")
                print("Video saved to output.mp4")
            </code></pre>

    - Generate video from a reference image
        - To use an image as a starting frame, 
            pass it to the `input_reference` parameter
        - The image resolution must match the 
            target video size
        - Example
            <pre><code>
                video = client.videos.create(
                    model="sora-2",
                    prompt="The camera slowly pans across the landscape as clouds drift overhead",
                    size="1280x720",
                    seconds="4",
                    input_reference=open("landscape.png", "rb"),
                )
            </code><pre>
        - <span>&#x1F4A1;</span>==Reference images containing human faces are currently rejected. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Use images of landscapes, objects, or animated characters instead.==

    - Remix an existing video
        - Used to modify an existing video 
            while preserving its structure
            (use the original video's ID)
        - Example
            <pre><code>
            video = client.videos.remix(
                video_id="video_abc123",
                prompt="Change the color palette to warm sunset tones",
            )
            </code></pre>

    - Handle job states
        | Status | Description |
        |:-|:-|
        |`queued`|Job is waiting to be processed|
        |`in_progress`|Video is being generated|
        |`completed`|Video is ready for download|
        |`failed`|Generation failed (check `video.error` for details<br/>about what went wrong) |
        |`cancelled`|Job was canceled|

    - Key considerations
        - Rate limits
            You can run up to two video creation jobs simultaneously
        - Job expiration
            Completed videos are available for download for 24 hours
        - Resolution requirements
            Reference images must match the target video resolution exactly
        - Content filtering
            Prompts are subject to content moderation; harmful content won't generate

- **Key takeaways**
    - Deploy a Sora 2 video generation model in Microsoft Foundry
    - Write effective prompts that describe camera framing, subject details, action, and lighting
    - Use the Video playground to test video generation with different settings
    - Generate videos from reference images and remix existing videos
    - Build a Python application that creates videos programmatically using the OpenAI SDK

- **Further reading**
    - [Video generation with Sora](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/video-generation)

- **Exercise - Generate video with Sora 2 in Microsoft Foundry**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-vision/Instructions/Exercises/03-generate-video.html)


### 4. [Analyze images with Content Understanding](https://learn.microsoft.com/en-us/training/modules/analyze-images-with-content-understanding/)

- **Introduction**
    - Images, documents, and other unstructured content often 
        contain valuable business information that is difficult to process automatically.
    - Microsoft Azure Content Understanding uses generative AI to 
        analyze and interpret unstructured data.
    - The service transforms raw content into **structured and usable information**.
    - Developers can define a custom **schema** that specifies the exact data to 
        extract from documents and images.
    - Azure Content Understanding automatically identifies and extracts the 
        requested information based on the defined schema.
    - Structured outputs can be integrated directly into:
        - Automation workflows
        - Analytics platforms
        - Search applications
        - Enterprise business processes
    - Generative AI simplifies the extraction of insights from complex visual and 
        document-based content.
    - The platform helps organizations improve efficiency, reduce manual data 
        processing, and accelerate decision-making.
    - Content Understanding enables scalable document and image processing for 
        modern AI-powered applications.

- **What is Content Understanding?**

    - Why use Content Understanding?
        - Is a Foundry Tool that uses generative AI to 
            process and extract insights from many types of content
            - Documents
            - Images
            - Videos
            - Audio
        - Transforms unstructured data into structured, 
            actionable output that you can integrate into 
            automation and analytical workflows
        - Key benifits
            - Simplified workflows
                Standardizes extraction and classification of content from 
                various content types into a unified process
            - Easy field extraction
                Define a schema to extract, classify, or generate field values 
                without complex prompt engineering
            - Enhanced accuracy
                Uses multiple AI models to analyze and cross-validate 
                information simultaneously
            - Confidence scores and grounding
                Ensures accuracy of extracted values while minimizing the 
                cost of human review
            - Content classification
                Categorize document types to streamline processing and 
                route content to appropriate analyzers
    
    - Content Understanding components
        | Components | Description |
        |:-|:-|
        |Inputs|Source content including documents, images,<br/>video, and audio|
        |Analyzer|Defines how content is processed, including<br/>extraction settings and field schema|
        |Content<br/>extraction|Transforms unstructured input into normalized text and<br/>metadata using OCR, speech transcription, and layout detection|
        |Field<br/>extraction|Generates structured key-value pairs based on your defined schema|
        |Confidence scores|Provides reliability estimates from 0 to 1 for<br/>each extracted field value|
        |Grounding|Identifies specific regions in content where<br/>each value was extracted|
        |Structured output|Final result as Markdown for search scenarios or<br/>JSON for automation workflows|

    - Analyzers
        - Content Understanding offers two types
            - Prebuilt analyzers
                Ready-to-use analyzers designed for common scenarios like
                invoice processing, receipt extraction, and call center analytics
            - Custom analyzers
                Tailored analyzers you create with your own field schema for 
                specific business needs
        - Configurations
            - The base analyzer type (document, image, audio, or video)
            - The AI models to use for processing
            - The field schema that defines what data to extract
            - Options like confidence scoring and content segmentation

    - Use cases
        | Use cases | Description |
        |:-|:-|
        |Intelligent document<br/>processing|Convert unstructured documents into structured data for invoice processing,<br/>contract analysis, and claims management|
        |Search and RAG|Ingest multimodal content into search indexes with figure<br/>descriptions and layout analysis|
        |Agentic applications|Transform messy file inputs into predictable, standardized<br/>inputs for AI agents|
        |Analytics and<br/>reporting|Extract field outputs to gain insights and make informed decisions|

    - Content restrictions
        - Content Understanding includes built-in **Responsible AI** protectionsy
        - Integrates** Azure AI Content Safety** to detect and prevent harmful content
        - Guidelines
            - Content is filtered for harmful material including violence, 
                hate speech, and exploitation
            - Face description capabilities can identify facial attributes in 
                video and image content
            - Biometric data processing requires appropriate notice and 
                consent from data subjects

- **Analyze images with Content Understanding**

    - Supported image formats
        - Content Understanding can analyze images to 
            - Extract structured data
            - Identify visual elements
            - Generate descriptions
        - Image input types
            | Format | Description |
            |:-|:-|
            |JPEG|Standard photographic images|
            |PNG|Images with transparency support|
            |BMP|Bitmap images|
            |TIFF|High-quality scanned documents|
            |HEIF|High-efficiency image format|
            |PDF|Single or multi-page documents with embedded images|

    - Prebuilt image analyzers
        - prebuilt-image
            General-purpose image analysis with content extraction and figure description
        - prebuilt-receipt
            Extract vendor names, items, totals, and dates from receipt images
        - prebuilt-invoice
            Extract invoice details including line items, amounts, and vendor information
        - prebuilt-idDocument
            Extract information from identity documents like driver's licenses and passports

    - Define a field schema for images
        - To extract specific information from images, 
            define a field schema that describes the data you want
        - Each field can use one of
            | Method | Description | Example |
            |:-|:-|:-|
            |extract|Pull values directly as they appear in the image|Extract text from a label or sign|
            |classify|Categorize content from predefined options|Classify image as "damaged" or "undamaged"|
            |generate|Create values based on image analysis|Generate a description of the scene|
        - Example
            <pre><code>
            {
                "description": "Product image analyzer",
                "baseAnalyzerId": "prebuilt-image",
                "fieldSchema": {
                    "fields": {
                    "ProductName": {
                        "type": "string",
                        "method": "extract",
                        "description": "Name of the product visible in the image"
                    },
                    "Condition": {
                        "type": "string",
                        "method": "classify",
                        "description": "Condition of the product",
                        "enum": ["new", "used", "damaged"]
                    },
                    "Description": {
                        "type": "string",
                        "method": "generate",
                        "description": "Brief description of what the image shows"
                    }
                    }
                }
            }
            </code></pre>

    - Analyze an image
        - Install Python SDK, with `pip`
            <pre>
            pip install azure-ai-contentunderstanding
            </pre>
    - Example
        (To submit a request to the analyze endpoint)
        <pre><code>
        from azure.ai.contentunderstanding import ContentUnderstandingClient
        from azure.ai.contentunderstanding.models import AnalysisInput, AnalysisResult
        from azure.core.credentials import AzureKeyCredential # for key-based authentication
        from azure.identity import DefaultAzureCredential # for Entra ID authentication
        &nbsp;
        # Get a client
        credential = AzureKeyCredential(key)
        client = ContentUnderstandingClient(endpoint={FOUNDRY_ENDPOINT},
                                            credential={KEY_OR_IDENTITY},
                                            api_version="2025-11-01")
        &nbsp;
        # Analyze an image file
        with open("my_image.png", "rb") as f:
                    file_bytes = f.read()
        &nbsp;
        try:
            poller = client.begin_analyze(
                analyzer_id={ANALYSER_ID},
                inputs=[AnalysisInput(data=file_bytes)],
            )
            # Get results asynchronously from poller
            result: AnalysisResult = poller.result()
        &nbsp;
            # Display results
            result_str = json.dumps(result.as_dict(), indent=2)
            print (result_str)
        &nbsp;
        except Exception as ex:
            print(f"[Unexpected Error]: {ex}")
            sys.exit(1)
        </code></pre>
        - Result
            (include the extracted content)
            <pre><code>
            {
                "contents": [
                    {
                    "markdown": "Product label showing 'Contoso Widget Pro' with serial number...",
                    "fields": {
                        "ProductName": {
                        "type": "string",
                        "valueString": "Contoso Widget Pro",
                        "confidence": 0.95,
                        "source": "D(1,100,50,300,50,300,80,100,80)"
                        },
                        "Condition": {
                        "type": "string",
                        "valueString": "new",
                        "confidence": 0.89
                        },
                        "Description": {
                        "type": "string",
                        "valueString": "A silver electronic device in retail packaging with product label visible"
                        }
                    }
                    }
                ]
            }
            </code></pre>

            <br/>

            - markdown
                A text representation of the image content, useful for search and RAG scenarios
            - fields
                Extracted field values matching your schema, each with a confidence score
            - source
                Grounding information showing where in the image each value was found
            
    - Use confidence scores
        - Each extracted field includes a 
            confidence score from 0 to 1
            - High confidence (0.9+)
                Value can be trusted for automated processing
            - Medium confidence (0.7-0.9)
                Consider human review for critical applications
            - Low confidence (<0.7)
                Recommend manual verification
        - Use confidence scores to 
            build automation workflows that route
            - Low-confidence extractions to human reviewers
            - Processing high-confidence results automatically

    - Tips for better image analysis
        - Image quality matters
            Higher resolution images produce more accurate extractions
        - Lighting and contrast
            Ensure text and visual elements are clearly visible
        - Single focus
            Images with one clear subject yield better results than cluttered scenes
        - Consistent orientation
            Upright images are processed more reliably than rotated ones

- **Further reading**
    - [What is Azure Content Understanding?](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview)

- **Exercise - Analyze images with Content Understanding**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-vision/Instructions/Exercises/04-content-understanding.html)

### 5. [Create a multimodal analysis solution with Azure Content Understanding](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/)

- **Introduction**

    - Modern organizations store valuable information across multiple types of content, 
        including documents, images, videos, and audio recordings.
    - Extracting meaningful information from unstructured content is often complex, time-consuming, and resource-intensive.
    - Traditional content analysis solutions frequently require multiple technologies to 
        process different file formats and media types.
    - Microsoft Azure Content Understanding simplifies content analysis through a 
        unified multimodal AI service.
    - The platform can analyze and extract information from content in 
        **practically any format**.
    - Azure Content Understanding enables the creation of AI-powered analyzers without the 
        need for separate tools for each media type.
    - Multimodal AI capabilities improve efficiency by centralizing document, image, video, and 
        audio analysis into a single solution.
    - Organizations can accelerate automation, search, analytics, and 
        knowledge extraction processes using structured outputs from unstructured content.
    - The service reduces development complexity while improving scalability and 
        maintainability for enterprise AI solutions.

- **What is Azure Content Understanding?**

    - Multimodal content analysis
        - Azure Content Understanding is a generative AI service that you can 
            use to extract insights and data from multiple kinds of content
        - Need to provision a Microsoft Foundry resource in 
            Azure subscription
        - Can develop and manage
            - In the Microsoft Foundry portal
            - In Content Understanding Studio
            - Using the Content Understanding API
        - Documents and forms
            - Can analyze documents and forms and 
                retrieve specific field values
            - Example
                Extract key data values from an invoice to 
                automate payment processing
        - Images
            - Can analyze images to 
                infer information from visuals 
                - Charts
                - Identify physical defects in products or other items
                - Detect the presence of specific objects or people
                - Determine other information visually
        - Audio
            - Enables to automate tasks
                - Summarizing conference calls
                - Determining sentiment of recorded 
                    customer conversations
                - Extracting key data from telephone messages
        - Video
            - Can analyze and extract 
                insights from video to
                -  Extract key points from video conference recordings
                - Summarize presentations
                - Detect the presence of specific activity in security footage

- **Create a Content Understanding analyzer**

    - What is an _analyzer_?
        - Solutions are based on the creation of an _analyzer_
        - Trained to **extract specific information** from a 
            particular **type of content** based on a 
            user defined **schema**
        - Process for creating a Content Understanding solution
            1. Create a Foundry resource.
            2. Define a Content Understanding schema for the information to be extracted. 
                This can be based on a content sample and an analyzer template.
            3. Build an analyzer based on the completed schema.
            4. Use the analyzer to extract or generate fields from new content.
            5. Can use minimal training data to define a schema by example

    - Creating an analyzer with 
        Content Understanding Studio
        - Provides a visual interface to create a project
        - Define a Content Understanding schema
        - Build and test an analyzer
        - <span>&#x1F4A1;</span>==Only certain prebuilt models are available for use 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;directly in the Microsoft Foundry portal.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For custom analyzer creation and testing, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;use [Content Understanding Studio](https://ai.azure.com/contentunderstanding).==

    - Creating a Content Understanding project
        - Resources needed
            - Storage a
            - Key vault resource to store
                - Credentials
                - Keys
        - <span>&#x1F4A1;</span>==Content Understanding schemas can only be created in 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Azure locations where the service is supported.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For more information, see [Content Understanding region and language support](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/language-region-support).==

    - Defining a schema
        -  For the content the analyzer will process, and 
            the information it will extract
        - Use schema editor interface
        - Upload a file
            - Document
            - Image
            - Audio
            - Video
        - Apply an appropriate schema template
        - Define the specific fields you want
            the analyzer to identify
        - <span>&#x1F4A1;</span>==The templates and field types available in a schema depend on the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;content type of the file on which the schema is based.  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Some content types support additional optional functionality, such as 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;extracting barcodes and formulae from text in documents.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For more information about using Content Understanding with different 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;content types, see the following articles in the product documentation:
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Content Understanding document solutions](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/document/overview)
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Content Understanding image solutions](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/image/overview)
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Content Understanding audio solutions](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/audio/overview)
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Content Understanding video solutions](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/video/overview)==

    - Testing
        - Running analysis on the sample file used to 
            define the schema or other uploaded files
        - Results include the extracted field values and the 
            JSON format output returned by the analyzer to 
            client applications

    - Building an analyzer
        - Building an analyzer makes it accessible to client applications 
            through the endpoint for the Microsoft Foundry resource 
            associated with your project
        - Can continue to test it in Content Understanding Studio, and 
            refine the schema to create new named versions 
            with different capabilities

- **Use the Content Understanding API**

    - Using the API to analyze content
        - How to use
            - Client application submits HTTP calls to the 
                Content Understanding endpoint for Foundry resource
            - Passing one of the authorization keys in the header
            - Obtain the endpoint and keys in 
                - Azure portal
                - Microsoft Foundry portal
        - Common uses of the API is 
            - Submit content to an existing analyzer that 
                you have previously built
            - Retrieve the results of analysis
            - Analysis request returns an operation ID value 
                that represents an asynchronous task
            - Client application must then use another request to 
                pass the operation ID back to the endpoint
            - Retrieve the operation status
            - Results are returned in JSON format
        - Example
            <pre><code>
            POST {endpoint}/contentunderstanding/analyzers/{analyzer}:analyze?api-version=2025-11-01
            {
            "inputs": [
                {
                "url": "https://host.com/doc.pdf"
                }
            ]
            }
            </code></pre>
            - <span>&#x1F4A1;</span>==You can specify a URL for the content file location as shown here. 
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To submit binary file data directly, use the `analyzeBinary` 
            operation instead.==
            - Response
                <pre><code>
                Operation-Id: 1234abcd-1234-abcd-1234-abcd1234abcd
                Operation-Location: {endpoint}/contentunderstanding/analyzerResults/1234abcd-1234-abcd-1234-abcd1234abcd?api-version=2025-11-01
                {
                "id": "1234abcd-1234-abcd-1234-abcd1234abcd",
                "status": "NotStarted"
                }
                </code></pre>
            - Check status
                <pre><code>
                GET {endpoint}/contentunderstanding/analyzerResults/1234abcd-1234-abcd-1234-abcd1234abcd?api-version=2025-11-01
                </code></pre>
            - Success operation
                - The response contains a JSON payload 
                    representing the results of the analysis
            - <span>&#x1F4A1;</span>==For more information about the Content Understanding API,
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see the [reference documentation](https://learn.microsoft.com/en-us/rest/api/contentunderstanding/operation-groups).==

- **Further reading**
    - [Azure Content Understanding documentation](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/)

- **Exercise - Extract information from multimodal content**
[&rarr;     saber &plus;](https://microsoftlearning.github.io/mslearn-ai-information-extraction/Instructions/Exercises/01-content-understanding.html)

### 6. [Create an Azure Content Understanding client application](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai-api/)

- **Introduction**
    -  Microsoft Azure Content Understanding is a multimodal AI service 
        designed to extract information from various content formats.
    - The platform supports analysis of
        - Documents
        - Images
        - Audio files
        - Videos
    - Azure Content Understanding simplifies the development of AI-powered 
        content analyzers for enterprise applications.
    - Developers can integrate the service into custom applications using
        - The Python SDK
        - REST APIs
    - The module focuses on building client applications that interact 
        programmatically with Azure Content Understanding services.
    - Using the Python SDK and REST API, developers can:
        - Submit content files for analysis
        - Retrieve structured results
        - Process extracted information automatically
    - The service enables automation of content processing workflows and 
        reduces manual data extraction efforts.
    - Multimodal analysis capabilities help organizations unlock insights from 
        unstructured data across multiple media types.
    - Programmatic integration supports scalable, flexible, and 
        maintainable AI-driven solutions.

- **Prepare to use the AI Content Understanding API**

    - How to start
        - Create a **Microsoft Foundry resource** 
            in the Azure portal.
        - Create a **Microsoft Foundry project**, 
            which includes a Microsoft Foundry resource by default.
        - After provisioned a Microsoft Foundry resource
            - The Microsoft Foundry resource _endpoint_
            - One of the API _keys_ associated with the endpoint
            - Mcrosoft Azure Portal > Resource Management > Keys and Endpoint > Content Understanding (tab)

    - Installing the Python SDK
        - To use the Python SDK
            <pre>
            pip install azure-ai-contentunderstanding
            </pre>
        - <span>&#9872;</span> ==The Python SDK requires Python 3.9 or later.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;You can also use the REST API directly from any 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;language that supports HTTP requests.==
        - <span>&#9888;</span> ==Before using the Content Understanding API, you must set up 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;default model deployments for your Microsoft Foundry resource.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Content Understanding requires `GPT-4.1`, `GPT-4.1-mini`, and 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`text-embedding-3-large` model deployments.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;You can configure these in the Azure portal or by using the API.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For more information, see [Set up model deployments](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/how-to/migration-preview-to-ga#prerequisites).==
        - <span>&#x1F4A1;</span> ==To learn more about programming with the Microsoft Foundry SDK,
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;complete the[ Develop an AI app with the Microsoft Foundry SDK](https://learn.microsoft.com/en-us/training/modules/ai-foundry-sdk/) module.==

- **Create a Content Understanding analyzer**

    - Defining a schema for an analyzer
        - Analyzers are based on schemas that define the fields
        - Schema is a set of fields, which can be 
            specified in a JSON document
        - Example
            <pre><code>
            {
                "description": "Simple business card",
                "baseAnalyzerId": "prebuilt-document",
                "config": {
                    "returnDetails": true
                },
                "fieldSchema": {
                    "fields": {
                        "ContactName": {
                            "type": "string",
                            "method": "extract",
                            "description": "Name on business card"
                        },
                        "EmailAddress": {
                            "type": "string",
                            "method": "extract",
                            "description": "Email address on business card"
                        }
                    }
                },
                "models": {
                    "completion": "gpt-4.1",
                    "embedding": "text-embedding-3-large"
                }
            }
            </code></pre>
            - Decoding
                - Custom analyzer schema
                - Based on the pre-built document analyzer
                - Describes two fields that would expect to 
                    find on a business card
                    - _ContactName_
                        - Defined as string data types
                        - Expected to be _extracted_ from a document
                    - _EmailAddress_
                        - Defined as string data types
                        - Expected to be _extracted_ from a document
                - The `models` object specifies the generative models that the 
                analyzer uses for processing
                - <span>&#9872;</span> ==example is deliberately simple, with the minimal information 
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;needed to create a working analyzer.
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In reality, the schema would likely include more fields of different types,
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and the analyzer definition would include more configuration settings.
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The JSON might even include a sample document.
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;See the [Azure Content Understanding API documentation](https://learn.microsoft.com/en-us/rest/api/contentunderstanding/content-analyzers/create-or-replace) for more details.==


    - Using the Python SDK to create an analyzer
        - With your analyzer definition in place,
            can use the Python SDK to create the analyzer
        - `ContentUnderstandingClient` class provides a `begin_create_analyzer` method that 
            handles the asynchronous creation process
        - Example
            <pre><code>
            from azure.ai.contentunderstanding  import ContentUnderstandingClient
            from azure.core.credentials         import AzureKeyCredential
            &nbsp;
            # Authenticate the client
            endpoint = "<YOUR_ENDPOINT>"
            credential = AzureKeyCredential("<YOUR_API_KEY>")
            client = ContentUnderstandingClient(endpoint=endpoint, credential=credential)
            &nbsp;
            # Define the analyzer
            analyzer_name = "business_card_analyser"
            analyzer_definition = {
                "description": "Simple business card",
                "baseAnalyzerId": "prebuilt-document",
                "config": {"returnDetails": True},
                "fieldSchema": {
                    "fields": {
                        "ContactName": {
                            "type": "string",
                            "method": "extract",
                            "description": "Name on business card"
                        },
                        "EmailAddress": {
                            "type": "string",
                            "method": "extract",
                            "description": "Email address on business card"
                        }
                    }
                },
                "models": {
                    "completion": "gpt-4.1",
                    "embedding": "text-embedding-3-large"
                }
            }
            &nbsp;
            # Create the analyzer and wait for completion
            poller = client.begin_create_analyzer(analyzer_name, body=analyzer_definition)
            result = poller.result()
            print(f"Analyzer created: {result.analyzer_id}")
            </code></pre>

    - Using the REST API to create an analyzer
        - Can use the REST API directly
        - The JSON data is submitted as a `PUT` request to the 
            endpoint with the API key in the request header to 
            start the analyzer creation operation
        - The response from the `PUT` request includes a **Operation-Location** in the 
            header, which provides a _callback_ URL that you can use to check on the 
            status of the request by submitting a `GET` request.
        - Example
            <pre><code>
            import json
            import requests
            &nbsp;
            # Get the business card schema
            with open("card.json", "r") as file:
                schema_json = json.load(file)
            &nbsp;
            # Use a PUT request to submit the schema for a new analyzer
            analyzer_name = "business_card_analyser"
            &nbsp;
            headers = {
                "Ocp-Apim-Subscription-Key": "<YOUR_API_KEY>",
                "Content-Type": "application/json"}
            &nbsp;
            url = f"{<YOUR_ENDPOINT>}/contentunderstanding/analyzers/{analyzer_name}?api-version=2025-11-01"
            &nbsp;
            response = requests.put(url, headers=headers, data=json.dumps(schema_json))
            &nbsp;
            # Get the response and extract the ID assigned to the operation
            callback_url = response.headers["Operation-Location"]
            &nbsp;
            # Use a GET request to check the status of the operation
            result_response = requests.get(callback_url, headers=headers)
            &nbsp;
            # Keep polling until the operation is complete
            status = result_response.json().get("status")
            while status == "Running":
                result_response = requests.get(callback_url, headers=headers)
                status = result_response.json().get("status")
            &nbsp;
            print("Done!")
            </code></pre>

- **Analyze content**

    - Using the Python SDK
        - To analyze the contents of a file, you can use the 
            Azure Content Understanding API to submit it to the endpoint
        - Can specify the content as a URL
            (for a file hosted in an Internet-accessible location)
        - Can upload binary file data directly 
            (for example, a `.pdf` document, a `.png` image, 
            an `.mp3` audio file, or an `.mp4` video file)
        - The analysis request includes the analyzer to be used.
        - Analysis is an asynchronous operation
        - After submitting the request
            - Receive an operation ID
                - Use to check the status
                - Retrieve the results when the 
                    operation is complete
        - Example
            <pre><code>
            from azure.ai.contentunderstanding          import ContentUnderstandingClient
            from azure.ai.contentunderstanding.models   import AnalysisInput
            from azure.core.credentials                 import AzureKeyCredential
            &nbsp;
            # Authenticate the client
            endpoint = "<YOUR_ENDPOINT>"
            credential = AzureKeyCredential("<YOUR_API_KEY>")
            client = ContentUnderstandingClient(endpoint=endpoint, credential=credential)
            &nbsp;
            # Analyze the business card using the custom analyzer
            analyzer_name = "business_card_analyser"
            poller = client.begin_analyze(
                analyzer_id=analyzer_name,
                inputs=[AnalysisInput(url="https://host.com/business-card.png")]
            )
            &nbsp;
            # Wait for the operation to complete and get the results
            result = poller.result()
            &nbsp;
            # Extract field values from the results
            content = result.contents[0]
            if content.fields:
                for field_name, field_data in content.fields.items():
                    if field_data.type == "string":
                        print(f"{field_name}: {field_data.value}")
            </code></pre>

            <br/>

            <span>&#x1F4A1;</span> ==The SDK's `begin_analyze` method returns a poller object.
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Calling `.result()` on the poller automatically handles 
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;polling until the operation completes, so you don't need to 
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;write your own polling loop.==

    - Using the REST API
        - Client application submits HTTP calls to the 
            Content Understanding endpoint, passing an API key in the header
        - Example
            <pre><code>
            import json
            import requests
            &nbsp;
            ## Use a POST request to submit the file URL to the analyzer
            analyzer_name = "business_card_analyser"
            &nbsp;
            headers = {
                    "Ocp-Apim-Subscription-Key": "<YOUR_API_KEY>",
                    "Content-Type": "application/json"}
            &nbsp;
            url = f"{<YOUR_ENDPOINT>}/contentunderstanding/analyzers/{analyzer_name}:analyze?api-version=2025-11-01"
            &nbsp;
            request_body = {
                "inputs": [
                    {
                        "url": "https://host.com/business-card.png"
                    }
                ]
            }
            &nbsp;
            response = requests.post(url, headers=headers, json=request_body)
            &nbsp;
            # Get the response and extract the ID assigned to the analysis operation
            response_json = response.json()
            id_value = response_json.get("id")
            &nbsp;
            # Use a GET request to check the status of the analysis operation
            result_url = f"{<YOUR_ENDPOINT>}/contentunderstanding/analyzerResults/{id_value}?api-version=2025-11-01"
            &nbsp;
            result_response = requests.get(result_url, headers=headers)
            &nbsp;
            # Keep polling until the analysis is complete
            status = result_response.json().get("status")
            while status == "Running":
                    result_response = requests.get(result_url, headers=headers)
                    status = result_response.json().get("status")
            &nbsp;
            # Get the analysis results
            if status == "Succeeded":
                result_json = result_response.json()
            </code></pre>

            <br/>

            <span>&#x1F4A1;</span> ==You can specify a URL for the content file location as shown here.
           &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; To submit binary file data directly, use the `analyzeBinary` operation instead.==

    - Processing analysis results
        - Results depend on
            - The kind of content the analyzer is designed to 
                analyze (for example, document, video, image, or audio).
            - The schema for the analyzer.
            - The contents of the file that was analyzed.
        - The response from the document-based business 
            card analyzer contain
            - The extracted fields
            - The optical character recognition (OCR) layout of the document, 
                including locations of lines of text, individual words, and 
                paragraphs on each page.

    - Using the Python SDK
        - The `AnalysisResult` object provides typed 
            access to the results
        - The `contents` property contains a list of 
            content objects with
            - Fields
            - Markdown
            - Metadata
        - Example
            (extracting string field values)
            <pre><code>
            # (continued from previous SDK code example)
            &nbsp;
            content = result.contents[0]
            if content.fields:
                for field_name, field_data in content.fields.items():
                    if field_data.type == "string":
                        print(f"{field_name}: {field_data.value}")
            </code></pre>

    - Using the REST API
        - The response is a JSON payload that 
            the application must parse
        - Example
            <pre><code>
            {
                "id": "00000000-0000-0000-0000-a00000000000",
                "status": "Succeeded",
                "result": {
                    "analyzerId": "biz_card_analyser_2",
                    "apiVersion": "2025-11-01",
                    "createdAt": "2025-05-16T03:51:46Z",
                    "warnings": [],
                    "contents": [
                        {
                            "markdown": "John Smith\nEmail: john@contoso.com\n",
                            "fields": {
                                "ContactName": {
                                    "type": "string",
                                    "valueString": "John Smith",
                                    "spans": [
                                        {
                                            "offset": 0,
                                            "length": 10
                                        }
                                    ],
                                    "confidence": 0.994,
                                    "source": "D(1,69,234,333,234,333,283,69,283)"
                                },
                                "EmailAddress": {
                                    "type": "string",
                                    "valueString": "john@contoso.com",
                                    "spans": [
                                        {
                                            "offset": 18,
                                            "length": 16
                                        }
                                    ],
                                    "confidence": 0.998,
                                    "source": "D(1,179,309,458,309,458,341,179,341)"
                                }
                            },
                            "kind": "document",
                            "startPageNumber": 1,
                            "endPageNumber": 1,
                            "unit": "pixel",
                            "pages": [
                                {
                                    "pageNumber": 1,
                                    "angle": 0.03410444,
                                    "width": 1000,
                                    "height": 620,
                                    "spans": [
                                        {
                                            "offset": 0,
                                            "length": 35
                                        }
                                    ],
                                    "words": [
                                        {
                                            "content": "John",
                                            "span": {
                                                "offset": 0,
                                                "length": 4
                                            },
                                            "confidence": 0.992,
                                            "source": "D(1,69,234,181,234,180,283,69,283)"
                                        },
                                        {
                                            "content": "Smith",
                                            "span": {
                                                "offset": 5,
                                                "length": 5
                                            },
                                            "confidence": 0.998,
                                            "source": "D(1,200,234,333,234,333,282,200,283)"
                                        },
                                        {
                                            "content": "Email:",
                                            "span": {
                                                "offset": 11,
                                                "length": 6
                                            },
                                            "confidence": 0.995,
                                            "source": "D(1,75,310,165,309,165,340,75,340)"
                                        },
                                        {
                                            "content": "john@contoso.com",
                                            "span": {
                                                "offset": 18,
                                                "length": 16
                                            },
                                            "confidence": 0.977,
                                            "source": "D(1,179,309,458,311,458,340,179,341)"
                                        }
                                    ],
                                    "lines": [
                                        {
                                            "content": "John Smith",
                                            "source": "D(1,69,234,333,233,333,282,69,282)",
                                            "span": {
                                                "offset": 0,
                                                "length": 10
                                            }
                                        },
                                        {
                                            "content": "Email: john@contoso.com",
                                            "source": "D(1,75,309,458,309,458,340,75,340)",
                                            "span": {
                                                "offset": 11,
                                                "length": 23
                                            }
                                        }
                                    ]
                                }
                            ],
                            "paragraphs": [
                                {
                                    "content": "John Smith Email: john@contoso.com",
                                    "source": "D(1,69,233,458,233,458,340,69,340)",
                                    "span": {
                                        "offset": 0,
                                        "length": 34
                                    }
                                }
                            ],
                            "sections": [
                                {
                                    "span": {
                                        "offset": 0,
                                        "length": 34
                                    },
                                    "elements": [
                                        "/paragraphs/0"
                                    ]
                                }
                            ]
                        }
                    ]
                }
            }
            </code></pre>
        - Example
            (code extracts all of the string values)
            <pre><code>
            # (continued from previous code example)
            &nbsp;
            # Iterate through the fields and extract the names and type-specific values
            contents = result_json["result"]["contents"]
            for content in contents:
                if "fields" in content:
                    fields = content["fields"]
                    for field_name, field_data in fields.items():
                        if field_data['type'] == "string":
                            print(f"{field_name}: {field_data['valueString']}")
            </code></pre>
            - Output
                <pre>
                ContactName: John Smith
                EmailAddress: john@contoso.com
                </pre>

- **Further reading**
    - [Azure Content Understanding documentation](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/)

- **Exercise - Develop a Content Understanding client application**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-information-extraction/Instructions/Exercises/01-content-understanding.html)


### 7. [Extract data with Azure Document Intelligence](https://learn.microsoft.com/en-us/training/modules/extract-data-with-document-intelligence/)

- **Introduction**
    - Forms and documents play a critical role in daily business operations across all industries.
    - Many organizations still rely on **manual data extraction**, which can be time-consuming, costly, and error-prone.
    - Automating document processing helps improve operational efficiency, accuracy, and scalability.
    - Microsoft Azure Document Intelligence provides AI-powered tools for extracting data from forms and documents automatically.
    - The service is part of Microsoft Foundry and leverages:
        - Optical Character Recognition (OCR)
        - Deep learning models
    - Azure Document Intelligence can extract:
        - Text
        - Key-value pairs
        - Tables
        - Structured document data
    - The platform includes prebuilt models for common document types such as invoices, receipts, and tax forms.
    - Developers can also create **custom models** tailored to specific business forms and workflows.
    - AI-powered document analysis reduces manual effort and accelerates business processes such as:
        - Claims processing
        - Patient enrollment
        - Expense management
        - Financial operations
     Azure Document Intelligence enables organizations to build scalable and intelligent document automation solutions.

- **What is Azure Document Intelligence?**

    - What is Azure Document Intelligence (ADI)
        - ADI is a cloud-based AI service that uses OCR and 
            deep learning models to extract 
            - Text
            - Key-value pairs
            - Selection marks
            - Tables from documents.
        - OCR captures document structure by creating bounding boxes 
            around detected objects in an image
        - The locations of the bounding boxes are recorded as 
            coordinates in relation to the rest of the page
        - Returns bounding box data and other information in a 
            structured JSON format
        - Preserves the relationships from the original document
        - ADI provides underlying models already trained on 
            thousands of form examples

    - Document Intelligence service components
        - Document analysis models
            - Extract text, structure, tables, and selection marks from documents
            - The read model extracts text and detects languages
            - The layout model adds table and structure extraction
        - Prebuilt models
            - Extract information from common document types
                without any training required 
                - Invoices
                - Receipts
                - Tax forms
                - ID documents
                - And more
        - Custom models
            - Extract data from forms specific to your business 
                using your own labeled datasets. 
            - Options
                - Custom template models
                    fast and cost-effective for fixed layouts
                - Custom neural models
                    higher accuracy for varying layouts
                - Composed models
                - Custom classifiers

    - Access Document Intelligence (DI) services
        - REST API
            Call the service directly using HTTP requests.
        - Client library SDKs
            Use SDKs for Python, C#, Java, and JavaScript.
        - Document Intelligence Studio
            An online tool for visually exploring, testing, and building DI solutions.
        - Microsoft Foundry portal
            Integrate DI with other Foundry tools.

    - Create a Document Intelligence resource
        - A Foundry resource
            A multi-service subscription that provides access to multiple AI 
            services under a single endpoint and key.
        - An Azure Document Intelligence resource
            A single-service resource used only with Document Intelligence.
        - <span>&#x1F4A1;</span> ==Create a Foundry resource if you plan to access multiple Foundry 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tools under a single endpoint and key.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For Document Intelligence access only, create a dedicated DI resource.==

    - Input requirements
        - Format must be
            (The read model also accepts Microsoft Office file formats)
            - JPEG
            - PNG
            - BMP
            - PDF (text or scanned)
            - TIFF
        - File size must be 
            - Less than 500 MB for the standard tier 
            - 4 MB for the free tier.
        - Image dimensions must be between 50 x 50 pixels and 10,000 x 10,000 pixels.
        - PDF documents must have dimensions less than 17 x 17 inches (A3 paper size).
        - PDF documents must not be password-protected.

    - Learn more
        - [What is Azure Document Intelligence?](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview)
        - [Azure Document Intelligence model overview](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/model-overview)

- **Use the Document Intelligence Studio**

    - What is Document Intelligence Studio
        - Is an online tool for visually exploring, understanding, and 
            integrating features from the Document Intelligence service
        - Use to 
            - Analyze form layouts
            - Extract data from prebuilt models
            - Train custom models
        - Access at [documentintelligence.ai.azure.com](https://documentintelligence.ai.azure.com/)

    - Studio capabilities
        - Document analysis models
            Test the read and layout models against your own documents to see extracted text, 
            tables, and structure.
        - Prebuilt models
            Analyze documents using any available prebuilt model, such as invoices, receipts,
            ID documents, and tax forms.
        - Custom models
            Build, label, train, and test custom extraction models and custom classifiers.

    - Analyze documents with prebuilt models
        1. Create an Azure Document Intelligence or Foundry Tools resource in the Azure portal.
        2. Open the Document Intelligence Studio and select a prebuilt model 
            (for example, Invoice, Receipt, or ID Document).
        3. Provide your resource endpoint and key.
        4. Upload or provide a URL to the document you want to analyze.
        5. Review the extracted fields and their confidence scores.

    - Build custom model projects
        - The Studio generates the required
            files automatically 
            - `ocr.json`
            - `labels.json`
            - `fields.json`
        - High-level workflow
            1. Create an Azure Document Intelligence or Foundry resource.
            2. Upload at least 5-6 sample forms to an Azure Blob Storage container.
            3. Configure cross-origin resource sharing (CORS) so the Studio can access your storage container.
            4. Create a custom model project in the Studio, linking your storage container and Document Intelligence resource.
            5. Label fields in your sample documents using the Studio's visual interface.
            6. Train your model and review accuracy metrics.
            7. Test the model against a new document that wasn't used during training.
    - Add-on capabilities
        | Capability | Description |
        |:-|:-|
        |High resolution extraction|Extract text from high-resolution documents with greater accuracy|
        |Formula extraction|Detect and extract mathematical formulas from documents|
        |Font property extraction|Extract font information such as style, weight, and color|
        |Barcode extraction|Detect and read barcodes in documents|
        |Searchable PDF|Convert scanned documents into searchable PDF files|
        |Query fields|Use natural language queries to extract specific fields from documents|
        |Key-value pairs|Extract key-value pair relationships from documents using the layout model|
        
        <br/>

        <span>&#x1F4A1;</span> ==Some add-on capabilities are premium features that incur extra costs.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Check the [pricing page](https://azure.microsoft.com/pricing/details/ai-document-intelligence/) for details.==

    - Learn more
        - [Document Intelligence Studio](https://documentintelligence.ai.azure.com/)
        - [Document Intelligence add-on capabilities](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/concept-add-on-capabilities)

- **Use prebuilt models**

    - Document analysis models
        - Prebuilt models in Azure Document Intelligence enables to 
            extract data from common form types without training your own models
        - Read model
            - Extracts printed and handwritten text from documents and images
            - Detects the language of each text line
            - Classifies whether text is handwritten or printed
            - Is the foundation for text extraction in all other Document Intelligence models
            - Multi-page PDF or TIFF files use the `pages` parameter in 
                request to specify a page range for analysis
            - Ideal to extract words and lines from documents 
                with no fixed or predictable structure
        - Layout model
            - Extends the read model's text
                extraction with
                - Detection of selection marks
                - Tables
                - Document structure information 
                - Supports `keyValuePairs` feature to 
                    extract key-value pairs
                - Can handle
                    - Angled documents
                    - Tables with complex structures
                        - Merged cells
                        - Incomplete rows
                - Each table cell is 
                    extracted with
                    - Its content
                    - Bounding box position
                    - Row/column indexes
                - Selection marks 
                    (checkboxes and radio buttons) are extracted
                    - Bounding box
                    - Confidence level
                    - Whether they're selected.
                - <span>&#x1F4A1;</span> ==The _general document model_ was available in earlier versions of Document Intelligence,
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;but was deprecated in the `2023-10-31-preview` release.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Its functionality for key-value pair and entity extraction has been incorporated into the 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;layout model and other features.==

    - Prebuilt models for specific document types
        - Financial and legal documents
            | Model | Description |
            |:-|:-|
            |Invoice|Extracts customer name, vendor details, purchase order number,<br/>invoice and due dates, billing and shipping addresses, line items, and totals|
            |Receipt|Extracts merchant details, transaction date and time, line items,<br/>and totals. Supports single-page hotel receipt processing|
            |Bank<br/>statement|Extracts account information, beginning and ending balances, and<br/>transaction details|
            |Check|Extracts payee, amount, date, and other relevant information|
            |Pay stub|Extracts wages, hours, deductions, net pay, and<br/>other common pay stub fields|
            |Credit card|Extracts payment card information|
            |Contract|Extracts agreement and party details|
        - US tax documents
            | Model | Description |
            |:-|:-|
            |Unified US tax|A single model that extracts from any supported US tax form type|
            |W-2|Extracts taxable compensation detail|
            |1098 and variations|Extracts mortgage interest and related details|
            |1099 and variations|Extracts income from various sources|
            |1040 and variations|Extracts individual income tax return details|
        - US mortgage documents
            | Model | Description |
            |:-|:-|
            |1003 (URLA)|Extracts loan application details.|
            |1004 (URAR)|Extracts information from property appraisals.|
            |1005|Extracts validation-of-employment information.|
            |1008|Extracts loan transmittal details.|
            |Closing disclosure|Extracts final closing loan terms.|
        - Personal identification documents
            | Model | Description |
            |:-|:-|
            |ID document|Extracts details from US driver's licenses, European Union IDs and<br/>driver's licenses, and international passports. Includes names, dates of birth,<br/>document numbers, and endorsements or restrictions.|
            |Health<br/>insurance card|Extracts common fields from US health insurance cards.|
            |Marriage<br/>certificate|Extracts certified marriage information.|

            <br/>

            <span>&#9888;</span>==The ID document model extracts personal information covered by data protection laws in 
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;most jurisdictions.
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ensure you have the individual's permission to store their data and that you comply 
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with all applicable legal requirements.==
    
    - Features of prebuilt models
        - Text extraction
            All prebuilt models extract lines and words from handwritten and printed text.
        - Key-value pairs
            Spans of text that identify a label and its response. 
            For example, Weight and 31 kg.
        - Selection marks
            - Checkboxes
            - Radio buttons
            - Whether they're selected or not.
        - Tables
            - Data in cells
            - Number of columns and row
            - Column and row headings
            - Merged cells.
        - Fields
            Models trained for a specific form type identify a fixed set of fields. 
            For example, the invoice model extracts `CustomerName` and `InvoiceTotal`.

    - When to use prebuilt vs. custom models
        (Custom model)
        - Industry-specific
        - Unique form type
        - Require time and sample data to train
        - Always check whether a prebuilt model 
            exists for your scenario

    - Learn more
        - [Azure Document Intelligence prebuilt models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/model-overview)
        - [Azure Document Intelligence read model](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/prebuilt/read)
        - [Azure Document Intelligence layout model](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/prebuilt/layout)
        - [Azure Document Intelligence invoice model](Azure Document Intelligence invoice model)
        - [Azure Document Intelligence receipt model](Azure Document Intelligence receipt model)
        - [Azure Document Intelligence ID document model](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/prebuilt/id-document)

- **Train and use custom models**

    - Custom model types
        - Custom template models
            (extraction model)
            - Rely on a consistent visual template to 
                extract labeled data
            -  Work best for structured forms where the 
                layout is static from one document 
                instance to the next
                - Questionnaires
                - Applications
                - Standard government forms
        - Template models extract
            - Labeled key-value pairs
            - Selection marks
            - Tables
            - Regions
            - Signatures
            - Training takes only a few minutes
            - More than 100 languages supported
            - Fast to train
            - Cost-effective to run
            - Good starting point when
                documents have a uniform visual layout

    - Custom neural models
        - Use deep learning and are 
            fine-tuned on your labeled data
        - Combine layout and language 
            features to extract fields from
            - Structured
            - Semi-structured
            - Unstructured documents
        - Neural models support
            - Overlapping fields
            - Signature detection
            - Table, row, and cell level confidence
        - Deliver higher accuracy than 
            template models for
            - Semi-structured 
            - Unstructured documents
        - Take longer to train
        - Consume more resources

    - Choose between template and neural models
        | Factor | Custom template | Custom neural |
        |:-|:-|:-|
        |Best for|Structured forms with a consistent<br/>visual layout|Semi-structured or unstructured documents<br/>with varying layouts|
        |Training time|Minutes|Longer<br/>(depends on dataset size)|
        |Training cost|Lower|Higher|
        |Accuracy|High for fixed-layout forms;<br/>decreases when layout varies|Higher overall, especially for documents<br/>with format variation|
        |Language support|100+ languages|Fewer languages<br/>(check [documentation](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/language-support/custom) for current support)|
        |Feature support|Key-value pairs, selection marks,<br/>tables, regions, signatures|Overlapping fields, signature detection,<br/>table/row/cell confidence|

        <br/>

        <span>&#x1F4A1;</span> ==Start with a custom template model if your forms have a consistent 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;visual layout. It's faster and cheaper to train.
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If accuracy is insufficient or your documents vary in format, switch to a 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;custom neural model.==

    - Custom classifiers
        - Identify the type of a document 
            before invoking an extraction model
        - Use a classifier to route incoming 
            documents to the appropriate extraction model

    - Train a custom model
        1. Store sample forms in an Azure blob container, 
            along with JSON files containing layout and label field information:
            - An `ocr.json` file for each sample form (generated using the Analyze document function).
            - A single `fields.json` file describing the fields you want to extract.
            - A `labels.json` file for each sample form, mapping fields to their location in the form.
        2. Generate a shared access signature (SAS) URL for the container.
        3. Use the Build model REST API function or the equivalent SDK method.
        4. Use the Get model REST API function to retrieve the trained model ID.
        <br/>
        <span>&#x1F4A1;</span> ==Use at least five to six sample forms for training. 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A larger and more varied dataset produces more accurate models.==

    - Use a custom model
        - Call the **Analyze document** function with your model ID
        - Example
            <pre><code>
            endpoint = "YOUR_DOC_INTELLIGENCE_ENDPOINT"
            key = "YOUR_DOC_INTELLIGENCE_KEY"
            &nbsp;
            model_id = "YOUR_CUSTOM_BUILT_MODEL_ID"
            formUrl = "YOUR_DOCUMENT"
            &nbsp;
            document_analysis_client = DocumentAnalysisClient(
                endpoint=endpoint, credential=AzureKeyCredential(key)
            )
            &nbsp;
            task = document_analysis_client.begin_analyze_document_from_url(model_id, formUrl)
            result = task.result()
            </code></pre>
            - Result
                - Successful response contains an 
                    `analyzeResult` object
                - Extracted content
                - An array of pages containing 
                    information about the document

    - Composed models
        - Combine multiple custom models 
            into a single **composed model**
        - Submit a document to a composed model
        - DI classifies it to determine the
            appropriate component model
        - Returns the extraction results 
           from that model
        
    - Learn more
        - [Document Intelligence custom models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/custom-model)
        - [Custom neural models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/custom-neural)
        - [Custom template models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/custom-template)
        - [Composed models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/composed-models)

- **Further reading**
    - [What is Azure Document Intelligence?](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview)
    - [Azure Document Intelligence model overview](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/model-overview)
    - [Document Intelligence custom models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/custom-model)
    - [Document Intelligence Studio](https://documentintelligence.ai.azure.com/)
    - [Language support for Azure Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/language-support)

- **Exercise -  Analyze documents with Document Intelligence**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-information-extraction/Instructions/Exercises/03-document-intelligence.html)


### 8. [Create a knowledge mining solution with Azure AI Search](https://learn.microsoft.com/en-us/training/modules/ai-knowldge-mining/)

- **Introduction**
    - Microsoft Azure AI Search is a cloud-based service designed for 
        intelligent search and knowledge mining solutions.
    - The platform enables organizations to extract, enrich, and 
        explore information from multiple data sources.
    - Azure AI Search helps transform raw and unstructured data 
        into searchable and actionable insights.
    - Core capabilities include
        - Connecting to diverse data sources
        - Creating search indexes
        - Managing searchable content efficiently
    - The indexing process organizes data to support fast and 
        accurate search experiences.
    - AI enrichment features enhance data with additional insights such as
        - Language detection
        - Key phrase extraction
        - Image analysis
    - AI skills improve the quality and intelligence of 
        search results by adding contextual understanding to content.
    - Azure AI Search supports powerful querying and 
        filtering through full-text search capabilities.
    - The knowledge store feature allows enriched data to be persisted for
        - Advanced analytics
        - Reporting
        - Integration with external systems
    - Azure AI Search enables the development of scalable, AI-powered 
        applications that improve information discovery and decision-making.

- **What is Azure AI Search?**

    - Provides a cloud-based solution for 
        indexing and querying a wide range of data sources
    - Create comprehensive and high-scale search solutions
    - Can
        - Index documents and data from a range of sources
        - Use AI skills to enrich index data.
        - Store extracted insights in a knowledge store for 
            analysis and integration.
    - Insights extracted from data
        - Text inferred
        - OCR from images
        - Entities and key phrases detection through **text analytics**
    - Applications
        - Implementing an enterprise search solution to help employees or 
            customers find information in websites or applications.
        - Supporting retrieval augmented generation (RAG) in generative AI 
            applications by using vector-based indexes for prompt grounding data.
        - Creating knowledge mining solutions in which the indexing process is 
            used to infer insights and extract granular data assets from documents to 
            support data analytics.

- **Extract data with an indexer**

    - Concepts
        - The indexing process begins with a **data source**, which stores the 
            original content to be processed and searched.
        - Data sources can include:
            - Azure Blob Storage containers
            - Databases
            - Other structured or unstructured storage systems
        - An **Indexer** automates the extraction and processing of 
            data from the source content.
        - The indexing workflow uses an **enrichment pipeline** to transform raw 
            content into searchable information.
        - Document cracking techniques are applied to extract text and 
            content from documents automatically.
        - The enrichment process incrementally builds a hierarchical **JSON-based document structure** 
            aligned with the index definition.
        - Processed and enriched data is stored in a searchable index for 
            efficient retrieval.
        - The resulting index enables fast querying and filtering of 
            documents based on specific search criteria.
        - Automated indexing improves scalability, reduces manual 
            data preparation, and enhances search accuracy.
        - Microsoft Azure AI Search simplifies the creation of intelligent and 
            searchable data solutions.

    - How documents are constructed during indexing
        - Process works by creating a 
            document for each indexed entity
        - An _enrichment pipeline_ iteratively builds the documents
        - Combine metadata from the data source with enriched 
            fields extracted or generated by _skills_
        - Structure of text document
            - Document
                - metadata_storage_name
                - metadata_author
                - content
        - Documents in the data 
            source contain images
            - Document
                - metadata_storage_name
                - metadata_author
                - content
                - normalized_images
                    (collection)
                    - image0
                    - image1
        - Each skill adds fields to the **document**
        - Skill detects _language_ used in document
            - Document
                - metadata_storage_name
                - metadata_author
                - content
                - normalized_images
                    (collection)
                    - image0
                    - image1
                - language
        - Document is structured hierarchically
        - Skills are applied to a 
            specific context within the hierarchy
        - Optical character recognition (OCR) skill
            - document
                - metadata_storage_name
                - metadata_author
                - content
                - normalized_images
                    - image0
                        - Text
                    - image1
                        - Text
                - language
        - Output fields from each skill can be used as 
            inputs for other skills later in the pipeline
        - _Merge skill_
            (combine the original text content with the text extracted from each image)
            - document
                - metadata_storage_name
                - metadata_author
                - content
                - normalized_images
                    - image0
                        - Text
                    - image1
                        - Text
                - language
                - merged_content
                    (new field)
        - Mapping fields by indexer
            - Fields extracted directly from the 
                source data are all mapped to index fields. 
                - Implicit mapping
                    (fields are automatically mapped to in fields with the 
                    same name in the index)
                - Explicit mapping 
                    (a mapping is defined to match a source field to an index field, 
                    often to rename the field to something more useful or to 
                    apply a function to the data value as it is mapped).
            - Output fields from the skills in the skillset are 
                explicitly mapped from their hierarchical location in the 
                output to the target field in the index.

- **Enrich extracted data with AI skills**

    - Built-in skills
        - The enrichment pipeline uses a skillset of 
            AI skills to create AI-enriched fields
        - Indexer applies each skill in order, 
            refining the index document at each step
        - Skills
            - Detecting the language that text is written in.
            - Detecting and extracting places, locations, and 
                other entities in the text.
            - Determining and extracting key phrases within a body of text.
            - Translating text.
            - Identifying and extracting (or removing) personally identifiable 
                information (PII) within the text.
            - Extracting text from images.
            - Generating captions and tags to describe images.
        - To use the built-in skills, indexer must have 
            access to a Foundry Tools resource
        - Can
            - Use a restricted Azure AI search resource
                (limited to indexing 20 or fewer documents)
            - Attach a Foundry Tools resource in your Azure subscription
                (must be in the same region as your Azure AI Search resource)

    - Custom skills.
        - Perform custom logic on input 
            data from your index document
        - Are "wrappers" around services that are 
            specifically designed to extract data from documents
        - Example
            - Implement a custom skill as an Azure Function
            - Use it to pass data from your index document to an 
                Azure Document Intelligence model
            - Can extract fields from a form
        - <span>&#x1F4A1;</span> ==To learn more about using custom skills with Azure AI Search, 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see [Add a custom skill to an Azure AI Search enrichment pipeline](https://learn.microsoft.com/en-us/azure/search/cognitive-search-custom-skill-interface)
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;in the Azure AI Search documentation.==

- **Search an index**

    - What is an index
        - Index is the searchable result of the 
            indexing process
        - It's a collection of JSON documents
        - Documents that contain fields that contain
            the values extracted during indexing
        - Client applications can query the index to retrieve, 
            filter, and sort information
        - Each index field can have the
            following attributes
            - key
                Fields that define a unique key for index records.
            - searchable
                Fields that can be queried using full-text search.
            - filterable
                Fields that can be included in filter expressions to return 
                only documents that match specified constraints.
            - sortable
                Fields that can be used to order the results.
            - facetable
                Fields that can be used to determine values for facets 
                (user interface elements used to filter the results based on a 
                list of known field values).
            - retrievable
                Fields that can be included in search results 
                (by default, all fields are retrievable unless 
                this attribute is explicitly removed).

    - Full-text search
        -  Describes search solutions that parse text-based 
            document contents to find query terms
        - Are based on the Lucene query syntax
        - Azure AI Search supports two variants
            - Simple
                An intuitive syntax that makes it easy to perform basic 
                searches that match literal query terms submitted by a user.
            - Full
                An extended syntax that supports complex filtering, 
                regular expressions, and other more sophisticated queries.
        - Parameters submitted with a query
            - search
                A search expression that includes the terms to be found.
            - queryType
                The Lucene syntax to be evaluated (_simple_ or _full_).
            - searchFields
                The index fields to be searched.
            - select
                The fields to be included in the results.
            - searchMode
                Criteria for including results based on multiple search terms. 
                - Example
                    Suppose you search an index of travel-related documents for comfortable hotel. 
                    A `searchMode` value of _Any_ returns documents that contain 
                    "comfortable", "hotel", or both; 
                    while a `searchMode` value of _All_ restricts results to documents that 
                    contain both "comfortable" and "hotel".
        - Query processing
            1. Query parsing
                - Search expression is evaluated and reconstructed as a 
                    tree of appropriate subqueries. 
                - Subqueries might include
                    - Term queries 
                        (finding specific individual words in the search expression - for example hotel)
                    - Phrase queries 
                        (finding multi-term phrases specified in quotation marks in the search expression - for example, "free parking")
                    - Prefix queries 
                        (finding terms with a specified prefix - for example air*, which would match airway, air-conditioning, and airport).
            2. Lexical analysis
                - Query terms are analyzed and refined based on linguistic rules. 
                    For example, text is converted to lower case and nonessential stopwords 
                    (such as "the", "a", "is", and so on) are removed. 
                - Words are converted to their root form 
                (for example, "comfortable" might be simplified to "comfort")
                - Composite words are split into their constituent terms.
            3. Document retrieval
                - Query terms are matched against the indexed terms
                - Set of matching documents is identified.
            4. Scoring
                A relevance score is assigned to each result based on a 
                term frequency/inverse document frequency (TF/IDF) calculation.

                <br/>

                <span>&#x1F4A1;</span> ==For more information about querying an index, and details about simple and full syntax,
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;see [Query types and composition in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-query-overview) in the Azure AI Search documentation.==
    
    - Filtering results
        - Apply filters by
            - Including filter criteria in a _simple_ **search** expression.
            - Providing an OData filter expression as a `$filter` parameter 
                with a full syntax search expression.
        - Can apply a filter to any filterable field in the index
        - Example
            -  Find documents containing the text _London_ that have an 
                **author** field value of _Reviewer_

            - Search expression
                <pre><code>
                search=London+author='Reviewer'
                queryType=Simple
                </code></pre>
            - OData filter in a `$filter` parameter with a 
            _full_ Lucene search expression
                <pre><code>
                search=London
                $filter=author eq 'Reviewer'
                queryType=Full
                </code></pre>
                
                <br/>

                <span>&#9872;</span> ==OData $filter expressions are case-sensitive!==

    - Filtering with facets
        - Work best when a field has a 
            small number of discrete values
        - Must specify facetable fields for which you want to 
            retrieve the possible values in an initial query
        - Example
            (use the following parameters to return all of the 
            possible values for the author field)
            <pre>
            search=*
            facet=author
            </pre>
        - Example
            (subsequent query)
            <pre>
            search=*
            $filter=author eq 'selected-facet-value-here'
        </pre>

    - Sorting results
        - By default, results are sorted based on the 
            relevancy score assigned by the query process
        - Can override this sort order by including an OData `orderby` parameter
            that specifies one or more _sortable_ fields and a sort order (_asc_ or _desc_)
        - Example

            <pre><code>
            search=*
            $orderby=last_modified desc
            </code></pre>
            <br/>

            <span>&#x1F4A1;</span> ==For more information about using filters, see 
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Filters in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-filters) in the Azure AI Search documentation.==

- **Persist extracted information in a knowledge store**

    - How to use enriched data
        - Since the index is essentially a collection of JSON objects, 
            each representing an indexed record, it might be useful to export the 
            objects as JSON files for integration into a data orchestration process for 
            extract, transform, and load (ETL) operations.
        - You may want to normalize the index records into a relational schema of 
            tables for analysis and reporting.
        - Having extracted embedded images from documents during the 
            indexing process, you might want to save those images as files.
        - Azure AI Search supports these scenarios by enabling you to 
            define a _knowledge store_ in the skillset
        - Knowledge store consists of projections of the enriched data
            - JSON objects
            - Tables
            - Image files
        - <span>&#x1F4A1;</span> ==To learn more about using a knowledge store, see 
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Knowledge store in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/knowledge-store-concept-intro) in the Azure AI Search documentation.==

- **Further reading**
    - [Azure AI Search documentation](https://learn.microsoft.com/en-us/azure/search/)

- **Exercise -  Create a knowledge mining solution**
[&rarr; saber &plus;](https://microsoftlearning.github.io/mslearn-ai-information-extraction/Instructions/Exercises/04-knowledge-mining.html)