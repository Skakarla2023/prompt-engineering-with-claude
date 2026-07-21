## Skeleton of thought Prompting

- Skeleton-of-Thought (SoT) prompting is a way of making AI answers faster and more organized by first creating a simple outline (a “skeleton”) of the answer, and then filling in the details later.
- It is mainly used when we need a huge response but quickly.

<img width="989" height="438" alt="image" src="https://github.com/user-attachments/assets/822aac5d-1c78-414c-bfc8-a51e3ab030be" />



### Sending this to a low level LLM

- When researchers talk about sending this to a low-level execution engine (or handling it at the model level), they are talking about Batched Decoding inside the LLM serving framework (like vLLM or TensorRT-LLM).
- Instead of treating the expansion as separate, isolated conversations, the low-level engine processes them through a shared hardware memory layer using two main optimizations.
- Low-Level Engine Optimizations (Short Notes)

**1. KV Cache Sharing (Prefix Caching)**

- The common input (Question + Skeleton) is processed only once.
- Its internal memory (KV Cache) is shared by all expansion tasks.
- This avoids repeating the same computation.

**2. Continuous Batching**

- All expansion tasks are grouped into one GPU batch.
- The GPU generates tokens for all tasks simultaneously.
- This improves speed and GPU efficiency.

#### Summary:

```
Process shared context once → Share the memory → Generate all outputs in parallel.
```
