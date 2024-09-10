---
cover: >-
  https://images.unsplash.com/photo-1531297484001-80022131f5a1?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwxfHx0ZWNofGVufDB8fHx8MTcyNDEwNDIwNnww&ixlib=rb-4.0.3&q=85
coverY: 0
---

# Large Language Models (LLMs)



{% hint style="success" %}
* [ChatGPT Tutorial](chatgpt/)
* [LLama](how-to-use-an-opensource-llm-locally.md)
* [Prompt Tutorial](prompt-engineering.md)
* [Hallucination Problem](hallucination-problem.md)
{% endhint %}



## Large Language Models (LLMs) Ranking

{% tabs %}
{% tab title="Artificial Analysis" %}
### <mark style="color:purple;">Artificial Analysis</mark>

Independent analysis of AI language models and API. Provides quality, speed, and price comparisons.

{% embed url="https://imagedelivery.net/gpNK4NZWsKZudYe2e_vBrw/c2a2d678-104c-408b-fabd-d7bfd1849000/public" %}

{% embed url="https://artificialanalysis.ai" %}
{% endtab %}

{% tab title="Scale Leaderboards" %}
{% embed url="https://scale.com/leaderboard?utm_source=www.theaivalley.com&utm_medium=newsletter&utm_campaign=2-new-shocking-details-about-sam-altman-s-firing" %}
Scale Leaderboards
{% endembed %}


{% endtab %}

{% tab title="🏆 LMSYS Chatbot Arena Leaderboard" %}
{% embed url="https://chat.lmsys.org/?leaderboard" %}
LLM Ranking
{% endembed %}


{% endtab %}
{% endtabs %}



***

## Large Language Models

### Close Source Models:

{% tabs %}
{% tab title="GPT-4o" %}
<mark style="color:orange;">GPT-4o-2024-08-06</mark>, OpenAI's most powerful LLM.

<mark style="color:green;">5/29/2024 ChatGPT with Gpt-4o is free for everyone</mark>
{% endtab %}

{% tab title="Grok-2" %}
Grok is an AI built by xAI, unique in its inspiration from the Hitchhiker's Guide to the Galaxy and JARVIS, offering an outside perspective on humanity and not shying away from answering the most intriguing questions.

https://x.ai/grok

<figure><img src="../../.gitbook/assets/grok 2.webp" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Claude" %}
Claude is a family of large language models developed by Anthropic, designed to generate natural, human-like responses to text and image-based inputs. The Claude 3 model family includes three tiers:

* **Claude 3 Opus**: The most intelligent model, excelling in highly complex tasks with near-human comprehension and fluency.
* **Claude 3 Sonnet**: Balances intelligence and speed, ideal for enterprise workloads requiring rapid responses.
* **Claude 3 Haiku**: The fastest and most compact model, providing near-instant responses for simple queries and requests.

Anthropic just revealed their new <mark style="color:orange;">**Claude Sonnet 3.5**</mark>, the best LLM according to their data.

{% embed url="https://www.anthropic.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F4zrzovbb%2Fwebsite%2Fcf2c754458e9102b7334731fb18a965bfeb7ad08-2200x1894.png&w=3840&q=75" %}

[https://claude.ai](https://claude.ai/login?returnTo=%2F%3F)
{% endtab %}

{% tab title="Gemini" %}
Gemini is a family of multimodal large language models developed by Google DeepMind, designed to process and generate content across various data types, including text, images, audio, and video, and serving as the successor to LaMDA and PaLM 2.

[https://gemini.google.com/app](https://gemini.google.com/app)
{% endtab %}
{% endtabs %}



### Open Source Models:

{% tabs %}
{% tab title="LLama" %}
LLama is a family of state-of-the-art large language models developed by Meta, designed to perform a wide range of natural language processing tasks with varying levels of computational efficiency and accuracy.

7/23/2024, Meta unveiled Llama 3.1, its largest and most advanced open-source AI model to date, featuring a 405 billion parameter version that reportedly rivals or surpasses leading closed-source models from companies like OpenAI and Anthropic in various performance benchmarks.

{% embed url="https://scontent-sjc3-1.xx.fbcdn.net/v/t39.2365-6/451735590_1030734788570365_1093008500142144333_n.png?_nc_cat=100&ccb=1-7&_nc_sid=e280be&_nc_ohc=S3n_sIpF1AEQ7kNvgGrdxtS&_nc_ht=scontent-sjc3-1.xx&oh=00_AYDLJ3ncnF3HNdnTSntSteoMLEC0-FZs0UhGRnLALlvuSA&oe=66BCFA3E" %}

[https://llama.meta.com/llama3/](https://llama.meta.com/llama3/)
{% endtab %}

{% tab title="Mistral" %}
Mistral AI offers a range of large language models (LLMs), both open source and commercial, designed for various tasks such as text generation, code generation, and multilingual reasoning.

[https://mistral.ai/](https://mistral.ai/)

**Mistral Large 2**

Mistral AI has introduced Mistral Large 2, a cutting-edge Language Model (LLM) that boasts state-of-the-art reasoning, knowledge, and coding capabilities, with a 128k context window and support for dozens of languages, including French, German, Spanish, Italian, Portuguese, Arabic, Hindi, Russian, Chinese, Japanese, and Korean, along with 80+ coding languages.
{% endtab %}
{% endtabs %}

***

## RAG

Retrieval Augmented Generation (RAG) is a technique that enhances Large Language Models (LLMs) by retrieving relevant information from external knowledge sources to provide more accurate, up-to-date, and contextually appropriate responses

{% tabs %}
{% tab title="anything-llm" %}
The all-in-one Desktop & Docker AI application with full RAG and AI Agent capabilities.

{% embed url="https://private-user-images.githubusercontent.com/16845892/294273127-cfc5f47c-bd91-4067-986c-f3f49621a859.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjQxMDM2MjUsIm5iZiI6MTcyNDEwMzMyNSwicGF0aCI6Ii8xNjg0NTg5Mi8yOTQyNzMxMjctY2ZjNWY0N2MtYmQ5MS00MDY3LTk4NmMtZjNmNDk2MjFhODU5LmdpZj9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA4MTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwODE5VDIxMzUyNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg1NmM2OTRmNzI0YjFhYWUyNWYwMGZmM2QzZTUyMzFkNTUxMjU5OGFhNmVlOTUwM2EwNjc0MWQzNjgxY2Q4NmEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.BzGTjbhJpmoMvdnxKZFUgizhtcwU-PbU84EpA0xEkvk" %}

[https://github.com/Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)
{% endtab %}

{% tab title="RAGFlow" %}
RAGFlow is an open-source RAG (Retrieval-Augmented Generation) engine based on deep document understanding.

[https://github.com/infiniflow/ragflow](https://github.com/infiniflow/ragflow)
{% endtab %}

{% tab title="Quivr" %}
Open-source RAG Framework for building GenAI Second Brains 🧠 Build productivity assistant (RAG) ⚡️🤖 Chat with your docs (PDF, CSV, ...) & apps using Langchain, GPT 3.5 / 4 turbo, Private, Anthropic, VertexAI, Ollama, LLMs, Groq that you can share with users ! Efficient retrieval augmented generation framework.

[https://www.quivr.com](https://www.quivr.com)

{% embed url="https://cdn.prod.website-files.com/65bae8c84334d8deee06c34b/65d2dee40422e51ac6bfef16_Homepage-p-2600.png" %}
{% endtab %}

{% tab title="Verba" %}
Retrieval Augmented Generation (RAG) chatbot powered by Weaviate

{% embed url="https://github.com/weaviate/Verba/raw/1.0.0/img/verba.gif" %}

[https://github.com/weaviate/Verba](https://github.com/weaviate/Verba)
{% endtab %}
{% endtabs %}

***

## Fine Turning

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td>Meta Fine Turning Guide</td><td><a href="https://ai.meta.com/blog/how-to-fine-tune-llms-peft-dataset-curation/">https://ai.meta.com/blog/how-to-fine-tune-llms-peft-dataset-curation/</a></td><td></td></tr><tr><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td></tr></tbody></table>



***

## Learning Resources:

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td>Transformers, Explained: Understand the Model Behind GPT-3, BERT, and T5</td><td><a href="https://daleonai.com/transformers-explained">https://daleonai.com/transformers-explained</a></td><td></td></tr><tr><td>What Is ChatGPT Doing … and Why Does It Work?</td><td><a href="https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/">https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/</a></td><td></td></tr><tr><td>ChatGPT Prompt Engineering for Developers</td><td></td><td><a href="https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/">https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/</a></td></tr><tr><td>LLM101n: Let's build a Storyteller</td><td><a href="https://github.com/karpathy/LLM101n">https://github.com/karpathy/LLM101n</a></td><td></td></tr><tr><td>How GPT works</td><td></td><td><a href="https://bbycroft.net/llm">https://bbycroft.net/llm</a></td></tr><tr><td>How I Use "AI" by Nicholas Carlini</td><td><a href="https://nicholas.carlini.com/writing/2024/how-i-use-ai.html">https://nicholas.carlini.com/writing/2024/how-i-use-ai.html</a></td><td></td></tr><tr><td>Transformer Explainer</td><td><a href="https://poloclub.github.io/transformer-explainer/">https://poloclub.github.io/transformer-explainer/</a></td><td></td></tr><tr><td>Generative AI Handbook: A Roadmap for Learning Resources</td><td><a href="https://genai-handbook.github.io">https://genai-handbook.github.io</a></td><td></td></tr><tr><td>Anthropic courses</td><td><a href="https://github.com/anthropics/courses/tree/master">https://github.com/anthropics/courses/tree/master</a></td><td></td></tr></tbody></table>



