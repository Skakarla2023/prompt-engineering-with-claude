## Prompt Evaluation


<img width="959" height="383" alt="image" src="https://github.com/user-attachments/assets/9c9ce8a3-bf5a-4059-bde5-f3910a12d1d6" />


- It is the process of judging how well the given prompt produces the desired output.
- Main methods for evaluating prompts are:
  1. Human evaluation
  2. LLM as a judge
  3. Automated metrics


### 1. Human evaluation

- captures nuances that automated methods miss.
- It is a gold standard for assessing subjectives like creativity, tone or usefulness.
- **Pros**:
  - flexible
  - closely reflects real world preferences
  - can assess any aspect of output quality
- **Cons**:
  - time consuming
  - expensive
  - not scalable
  - different people might have different opinions

### 2. LLM as a judge

- Using LLMs to evaluate outputs.
- LLM acts as a reviewer - it might give a score, choose the better of two or check if certain criteria are met.
- It aligns more closely with human evaluation for complex tasks, by identifying nuances and all which are often ignored by BUEL, BERTScore and ROUGE scores.
- Ways to do LLM output evaluation:
  1. **Single output scoring** : LLm reviews one output at a time and gives it a score.
  2. **Pairwise comparision** : LLm is given two and asked to decide which is better.
- **Pros**:
  - fast
  - scalable
  - able to handle nuanced criteria(can handle coherence, consistency which are hard for raw metrics to calculate)
- **Cons**:
  - can have biases
  - can be tricked by phrasing
  - may give inconsistent scores
  - additional cost of API calls

### 3. Automated metrics

- Uses algorithms to score the quality of AI's output.
- Eg: uses BLEU, ROUGE(how many overlapping keywords are there between these 2 summaries) or BERTScore for summarization and cosine similarity for embedding space similarity.
- **Pros**:
  - fast
  - repeatable
  - scalable
- **Cons**:
  - requires reference outputs
  - focus on only surface level similarity.
  - might not catch nuances(BLEU, ROUGE)
 


<img width="959" height="485" alt="image" src="https://github.com/user-attachments/assets/ac4f29e1-4ced-4026-bd9f-2cbfd86b067a" />

