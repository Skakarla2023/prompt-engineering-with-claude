## Generative AI

- Generative AI refers to Artifical Intelligence systems that can create new content such as text, audio, video or documents rather than just analysing the existing data.

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/09ab48cb-9ecb-4b86-82f4-56de02dec572" />


- When traditional AI analyses and categorises, Generative AI creates something that did not exist before.
- **LLM** : They are called language models because they are trained to `predict` and `generate` human language, and **large** because they contain billions of `parameters`(Mathematical values that determine how the model processes the information-somehow like synaptic connections in our brain).

<img width="704" height="539" alt="image" src="https://github.com/user-attachments/assets/74e9ec0a-1338-4dd8-8e06-1f7879d2f694" />


## The Three Pillars Behind Generative AI

### 1. Algorithms – How AI Understands Information

#### Before: Neural Networks
- Before 2017, neural networks were the most widely used AI models.
- They processed text one word at a time and often forgot the context in long sentences.
#### Now: Transformers
- Transformers changed the way AI processes language.
- They look at the entire sentence at once and use self-attention to understand how words are related.
- This helps preserve both the meaning of individual words and the overall meaning of the sentence, making language understanding much more accurate.

### 2. Data – What AI Learns From

#### Before
- AI models were trained on small, human-labeled datasets.
#### Now
- Modern AI models learn from massive amounts of data collected from websites, books, articles, code repositories, images, and many other sources.
- By learning patterns from this large and diverse data, they gain knowledge about language, coding, reasoning, and more.

### 3. Computation – How AI Processes Data Quickly

#### Before
- AI training mainly relied on CPUs, which process tasks one after another and are too slow for today's large models.

#### Now
- GPUs(Graphics Processing Unit) and TPUs(Tensor Processing Unit) perform thousands of calculations in parallel, making AI training much faster.
- Multiple GPUs/TPUs can be connected into computing clusters, allowing models to be trained in days instead of years.

<img width="959" height="535" alt="image" src="https://github.com/user-attachments/assets/1a86a938-8b43-4704-ae06-92b7b985befd" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/879db752-8df8-4fa5-bd07-e65413c4d743" />

- Fine tuning is often done by taking human reviews and in reinforcement learning(where the model learns through rewards and penalties).

<img width="512" height="539" alt="image" src="https://github.com/user-attachments/assets/4b30a07a-fd6f-4e75-bf00-b0301b2754de" />

- **Context window** : How much information the model can consider at once is known as the context window.

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/ed4c20c4-08f8-4ad9-8969-bf226bca9547" />

<img width="1813" height="499" alt="image" src="https://github.com/user-attachments/assets/18c95566-04bd-477b-8a61-50d4f6cd7a2f" />


### Capabilities and Limitations

- Every LLM has a `knowledge cutoff date`, which means after it's maufacture, the time when it would we completely unaware of the world, and after that it would remember nothing from your conversation.
- If your input extends the `context window`, the LLM cannot generate correct output.
- Sometimes ,the model can give undeterministic output, meaning if the same question is asked twice, it may give slightly different answers, this is because it makes probabilistic decisions, but not out of reasoning, it tries to predict what might be the answer.
- Some models like Claude do not have access to many data sources, through which it may not be able to solve a particular problem.







<img width="1121" height="466" alt="image" src="https://github.com/user-attachments/assets/1acc6f8d-ac9d-41fa-a0b0-b8b84d6d1188" />

<img width="1101" height="530" alt="image" src="https://github.com/user-attachments/assets/1bf1c71b-db12-4e9f-bbe3-b403bb6a5cb6" />
