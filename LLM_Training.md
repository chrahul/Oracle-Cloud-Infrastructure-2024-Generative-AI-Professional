- **Introduction to Training vs. Prompting**:
  - Prompting is a method to influence a language model's distribution over vocabulary words by changing its input.
  - However, prompting alone may not sufficiently alter the model's behavior, leading to the need for training, which involves modifying the model's parameters.

- **Prompting Limitations**:
  - Prompting is sensitive to small changes and can result in significant alterations in the model's output.
  - Since prompting does not change the model's parameters, it has limitations in fully adapting the model's behavior to new tasks or domains.

- **Training Overview**:
  - During training, the model's parameters are adjusted based on input-output pairs, aiming to improve its performance on specific tasks.
  - Training involves updating the model's parameters to influence its distribution over words, ideally improving its accuracy and effectiveness.

- **Training Approaches**:
  - **Fine-Tuning**:
    - Involves training the entire model on labeled data for a specific task, such as BERT for natural language understanding.
  - **Parameter-Efficient Fine-Tuning**:
    - Methods like LORA focus on training a subset of the model's parameters or adding new parameters to achieve task-specific adaptation more efficiently.
  - **Soft Prompting**:
    - Adds specialized parameters to the prompt, allowing the model to learn task-specific cues during training.
  - **Continual Pretraining**:
    - Similar to fine-tuning but doesn't require labeled data; the model is trained to predict the next word in a continuous stream of input data.

- **Training Costs**:
  - Training methods vary in computational resources required, ranging from generating text (relatively cheap) to pre-training (extremely expensive).
  - Factors such as training duration, available data, and hardware significantly impact the cost of training.

- **Considerations and Further Reading**:
  - Despite the cost, training remains essential for adapting models to new tasks or domains effectively.
  - Research, such as the study on cramming, explores alternative approaches to training with limited resources, offering insights into model scalability and efficiency.
