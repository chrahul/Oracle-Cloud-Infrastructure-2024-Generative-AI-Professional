- **OCI Generative AI Service Overview:**
  - Fully managed service offering customizable large language models.
  - Provides a single API access for building generative AI applications.
  - Offers flexibility to use different foundational models with minimal code changes.
  - Eliminates the need to manage infrastructure.

- **Service Functionality:**
  - **Text Input and Analysis:**
    - Users provide natural language text input.
    - Service analyzes input to generate, summarize, transform, extract, or classify text.
    - Responds with the processed text or information.
  - **Massive Scale Language Processing:**
    - Built to understand, generate, and process human language at scale.
    - Enables various use cases such as text generation, summarization, data extraction, classification, and conversational AI with chatbots.


![image](https://github.com/chrahul/Oracle-Cloud-Infrastructure-2024-Generative-AI-Professional/assets/14847377/56cf94e7-781f-42e4-8613-83db840d0c92)



- **Pre-Trained Foundational Models:**
  - **Generation Models:**
    - Includes command model and command light model from cohere.
    - Also features LLama-2 70 billion chat model from Meta.
    - Designed for generating text with instruction following capabilities.
  - **Summarization Models:**
    - Command model from cohere.
    - Enables summarizing text with customizable format, length, and tone.
  - **Embedding Models:**
    - Embed English and multilingual models from cohere.
    - Create embeddings to understand relationships between pieces of text.
    - Useful for semantic searches across languages.

![image](https://github.com/chrahul/Oracle-Cloud-Infrastructure-2024-Generative-AI-Professional/assets/14847377/9938197d-7275-4566-8e1f-0afa07ca3067)


- **Fine-Tuning Capability:**
  - **Custom Model Creation:**
    - Utilize fine-tuning to optimize pre-trained models on domain-specific datasets.
    - Improve model performance on specific tasks and enhance efficiency.
    - T-Few fine-tuning mechanism enables fast and efficient customizations.

- **Dedicated AI Clusters:**
  - **GPU-Based Compute Resources:**
    - Hosts fine-tuning and inference workloads.
    - Establishes dedicated clusters with GPUs and exclusive RDMA cluster network.
    - Isolates GPUs allocated for customer tasks from other GPUs.
    - Leverages OCI's industry-leading RDMA supercluster for high throughput and low latency.
   
      ![image](https://github.com/chrahul/Oracle-Cloud-Infrastructure-2024-Generative-AI-Professional/assets/14847377/28b0a0d6-0dda-44e5-ab1d-6d96fbcf2a7d)


- **Key Characteristics:**
  - Choice of models from Meta and cohere.
  - Ability to fine-tune models with domain-specific datasets.
  - Dedicated AI clusters for efficient processing and isolation of resources.
