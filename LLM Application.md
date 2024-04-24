- **Retrieval Augmented Generation (RAG) Systems:**
  - Combine language models (LMs) with retrieval-based methods.
  - User provides input (e.g., a question).
  - System transforms input into a query to search a database (e.g., a corpus of documents).
  - Retrieved documents are provided to the LM along with the input.
  - LM generates an answer leveraging the retrieved context.
  - RAG systems tend to hallucinate less and are used in various tasks like dialogue, question-answering, and fact-checking.

- **Code Models:**
  - LLMs trained on code, comments, and documentation.
  - Known for code completion and documentation completion.
  - Examples include Co-pilot, Codex, and Code Llama.
  - Benefit developers by reducing boilerplate code and aiding in unfamiliar language programming.

- **Multi-Modal Models:**
  - Trained on multiple data modalities (e.g., text, images, audio).
  - Can produce images or videos from textual descriptions.
  - Diffusion models attempt simultaneous generation of images, but joint decoding for text is challenging.

- **Language Agents:**
  - Intended for sequential decision-making scenarios.
  - Utilize LLMs for communication and instruction-following capabilities.
  - Operate in an environment, taking actions to accomplish a specific goal.
  - Example framework: ReAct, which prompts the model to emit thoughts summarizing the goal and actions taken.

- **Tool Usage by LLMs:**
  - Teaching LLMs to leverage tools like APIs for computation.
  - Enables LLMs to perform tasks beyond text generation by interfacing with external programs.
  - Expands the capability of LLMs for various applications.

- **Reasoning in LLMs:**
  - Growing research on training LLMs to perform various types of reasoning.
  - LLMs capable of reasoning could act as high-level planners for complex, long-horizon tasks.
  - Promises improved performance in new environments and unfamiliar tasks, akin to human reasoning abilities.
