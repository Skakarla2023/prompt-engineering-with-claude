# Prompt evaluation using promptfoo


## What is Promptfoo?

**Promptfoo** is a testing tool for AI prompts — think of it as **JUnit/pytest, but for your LLM prompts**.

## How it works

You write test cases like:

> *"Given this prompt → I expect the output to contain X / not contain Y / match a pattern"*

Promptfoo runs your prompt against the model and checks if the output passes your conditions. You can also run the **same prompt across multiple models** (GPT-4, Claude, Gemini) side by side to compare results.

---

## Why it's used

| Problem | How Promptfoo helps |
|---|---|
| You tweak a prompt and break something | Catches regressions automatically |
| You want to compare GPT vs Claude | Runs both and shows a comparison table |
| You don't know which prompt version is better | A/B tests prompts with real metrics |
| You're building a RAG/chatbot app | Tests edge cases before they hit production |

---

#### One-line summary

> **Promptfoo = automated testing + benchmarking for your AI prompts**, so you don't have to manually copy-paste into ChatGPT and eyeball the output every time you change something.


## How to use Promptfoo?

- For using promptfoo, you must install nodejs in your system.

<img width="1875" height="842" alt="image" src="https://github.com/user-attachments/assets/6a93a30a-c7ef-410a-8761-9acb619a0273" />

- After installation run the following commands in your command prompt:

```
npm install -g promptfoo
```

<img width="1919" height="856" alt="image" src="https://github.com/user-attachments/assets/9039f98f-a015-4680-9873-726d561893f6" />

```
npx promptfoo view
```

<img width="1885" height="322" alt="image" src="https://github.com/user-attachments/assets/6b161d0f-f4a4-446b-b385-39cdd98dc0ff" />

- After selecting **yes** from the above screen, it redirects to a web page which looks as follows:

<img width="1919" height="826" alt="image" src="https://github.com/user-attachments/assets/bb76fa8b-3fef-46a5-9fc0-264c00226381" />

<img width="1919" height="833" alt="image" src="https://github.com/user-attachments/assets/d930e714-a03b-49af-b289-5942b163fd75" />

<img width="1919" height="826" alt="image" src="https://github.com/user-attachments/assets/ef4705d6-7f49-48c4-9f27-dbd1568091ba" />


<img width="1919" height="830" alt="image" src="https://github.com/user-attachments/assets/d81a89c8-4ad9-424a-824c-91eca6c678a8" />

<img width="1919" height="826" alt="image" src="https://github.com/user-attachments/assets/8d2c930f-0b67-4d03-8adb-6509f70956d2" />

<img width="1919" height="825" alt="image" src="https://github.com/user-attachments/assets/899fc63b-1905-4ac1-a8fc-8addc797640c" />

<img width="1792" height="772" alt="image" src="https://github.com/user-attachments/assets/28ded67b-4106-4a10-97b4-9c77aa0c4b42" />
