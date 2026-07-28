# Prompting Techniques

They are different ways of asking question or giving instructions to AI so that it gives a clear, accurate and a more desired outcome.

## Chain of Thought prompting

- CoT prompting is used to instruct the LLM to use a logical step-by-step approach while generating responses.
- AI models can answer some direct questions in a simpler manner without thinking a lot.

Eg: What is the capital city of India

India

- But if you ask some logical questions like this,

Eg: if all roses are flowers and some flowers fade quickly, can we say that some roses fade quickly

the model needs to think well before answering, in such cases it uses Chain of thought prompting.



## Ways

- There are two ways of declaring Chain of thought prompts. They are
  1. Zero shot CoT : In this you just add " think step-by-step before giving the answer " at the end of the prompt.
  2. Few-shot CoT : In this we give some examples of how to solve the problem so that the model understands it better.


### 1. Zero Shot CoT

**1.a.. without thinkng**

<img width="1571" height="621" alt="image" src="https://github.com/user-attachments/assets/b6aa7de1-a231-41ec-b88a-d7865d6a104c" />

<img width="1382" height="480" alt="image" src="https://github.com/user-attachments/assets/edaaa97d-ab05-4be5-b3de-b54bbc9403c6" />


**1.b.. after adding thinking property**

<img width="1557" height="705" alt="image" src="https://github.com/user-attachments/assets/07c8c47d-0e9f-4692-ae7e-c0309e6287f7" />

### 2. Few-shot CoT

**2.a.. without thinking property**

<img width="973" height="799" alt="image" src="https://github.com/user-attachments/assets/67891df3-94d8-400c-a971-1a84c2508f9b" />


**2.b.. after adding thinking property**

<img width="871" height="801" alt="image" src="https://github.com/user-attachments/assets/8d65b437-743e-4dad-912f-cf89fd3f80a2" />


<img width="1045" height="434" alt="image" src="https://github.com/user-attachments/assets/6c7f6a44-e5dc-409b-834b-1097f6821bb6" />


### Note:

- Based on some research , it has been proved that few shot CoT performs better than zero shot CoT.
- When CoT was first introduced, it became more popular because of its quality at performing ressoning tasks, but now-a-days it has become less important because now models are becoming more intelligent.
- Because if you give a reasoning problem to a model, it automatically starts following step wise approach to solve it.
- To a reasoning model we need not tell to approach the problem step-by-step,, they automatically and always perform CoT automatically.
- But when the user asks to generate only the answer instead of the entire solution, the answer is limited to a single digit.
- To solve this problem, **thinking** capability was added to the model.
- While using reasoning models, CoT is not needed.
- For other models or smaller locally running models, CoT should be used.




<img width="1000" height="457" alt="image" src="https://github.com/user-attachments/assets/f2f4f0da-44d2-40c8-a57e-b9dcb098e040" />






### Automatic CoT

- This one is similar to few-shots CoT, but here the only difference is that the examples are not manually given, they are chosen from a collection of examples.
- Automatic CoT was giving the best results when compared to Zero shots or few-shots CoT.

<img width="1023" height="444" alt="image" src="https://github.com/user-attachments/assets/0f3e976b-460d-4c55-aeef-595674c3fe55" />

<img width="1023" height="398" alt="image" src="https://github.com/user-attachments/assets/7fa1ddf6-2565-4163-84a3-43fd2ea7d127" />


> In conclusion, letting the LLM generate the solution step-by-step gives better accuracy than forcing it to directly give answers for complex problems.Ask the LLM  to go step-by-step using the CoT prompting.
