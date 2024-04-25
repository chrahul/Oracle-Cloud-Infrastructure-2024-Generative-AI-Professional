Oracle Cloud Infrastructure Generative AI is a fully managed service that provides a set of state-of-the-art, customizable large language models (LLMs) that cover a wide range of use cases for text generation.

- **Tokens in Generative AI:**
  - Large language models understand tokens rather than characters.
  - One token can represent part or all of a word, including punctuation symbols.
  - Complexity of text influences the number of tokens per word:
    - Simple text: Average of one token per word.
    - Complex text: Average of two or three tokens per word.

- **Pretrained Generation Models:**
  - **Cohere Command Model:**
    - Highly performant instruction following conversational model.
    - 52 billion parameters.
    - Suitable for text generation, summarization, or chat use cases.
    - Context window of 4,096 tokens.
  - **Cohere Command Light Model:**
    - Smaller, faster version of the command model.
    - 6 billion parameters.
    - Recommended for scenarios prioritizing speed and cost.
  - **Meta LLama-2 70 Billion Chat Model:**
    - Open source model optimized for dialogue use cases.
    - 70 billion parameters.
    - Ideal for chat and text generation.

- **Generation Model Parameters:**
  - **Maximum Output Token:**
    - Limits the number of tokens generated per response (e.g., 4,000 tokens for OCI).
  - **Temperature:**
    - Controls the randomness of model output.
    - Higher temperature results in more creative output.
  - **Top k and Top p:**
    - Determine which tokens to consider for output selection based on probability.
    - Top k selects from top k tokens sorted by probability.
    - Top p selects from tokens whose probabilities sum up to a specified threshold.
  - **Stop Sequence:**
    - String that tells the model to stop generating content (e.g., period).
  - **Penalty Parameters:**
    - **Frequency Penalty:**
      - Penalizes tokens based on how frequently they appear in preceding text.
    - **Presence Penalty:**
      - Penalizes tokens that have appeared at least once before.
  - **Show Likelihood:**
    - Assigns likelihood scores to tokens indicating their probability to follow the current token.

- **Key Considerations:**
  - Parameter settings significantly impact model output.
  - Understanding and tuning parameters are essential for controlling model behavior and output.
 
- **Temperature:**
  - Hyperparameter controlling the randomness of LLM output.
  - Determines how model selects the next word based on probabilities.
  - Lower temperature makes the model more deterministic, selecting words with highest probability.
  - Higher temperature increases randomness, allowing selection of words with lower probabilities, leading to more creative output.

- **Top k and Top p:**
  - **Top k:**
    - Instructs the model to pick the next token from the top k tokens based on their probabilities.
    - Model selects from the highest probability tokens, ignoring the rest.
  - **Top p:**
    - Picks tokens whose probabilities sum up to a specified threshold (p).
    - Excludes tokens with probabilities below the threshold, ensuring selection from the top tokens.
    - Alternatively, excludes a fixed percentage (1 - p) of tokens with the lowest probabilities.

- **Stop Sequence:**
  - String that signals the model to stop generating content.
  - Commonly used punctuation marks like period can serve as stop sequences.
  - Allows controlling the length and structure of generated text.

- **Penalty Parameters (Frequency and Presence):**
  - **Frequency Penalty:**
    - Penalizes tokens based on their frequency of appearance in the preceding text.
    - Tokens appearing frequently receive higher penalties, reducing their probability of selection.
  - **Presence Penalty:**
    - Applies penalty to tokens regardless of frequency.
    - Tokens appearing at least once before are penalized to promote less repetitive output.

- **Show Likelihood:**
  - Assigns a likelihood score to each token indicating its probability to follow the current token.
  - Higher scores indicate higher likelihood of selection for the next token.
  - Provides insight into the model's decision-making process.

- **Overall Considerations:**
  - Understanding and tuning these parameters are crucial for controlling model behavior and output.
  - Selection of parameters influences the creativity, coherence, and repetition in generated text.
