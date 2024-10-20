# llmducation

Staying up to date with Large Language Models (no hype).

I always wake up excited to learn new things in statistics, software and machine learning but I've had intermittent AI and Large Language Model (LLM) learning paralysis for a while now. Despite the fact that LLMs are one of the biggest technological innovations to have occurred in my lifetime, I've found myself a bit averse to exploring them and what they are capable of. Or, at least, relatively more averse to checking them out than I am to checking out interesting things in other domains.

Having been on holiday this past week (October 2024) I've had some time to mull this over, and I think the primary reasons for this are:

- That playing with SOTA models (on anything other than toy problems) requires hemorrhaging money (although this has become less true over time).

- That it's difficult to separate objectivity from hype and people trying to sell things

- The overuse of the culturally-overloaded term "AI" (and, even worse, "AGI")

- The fear-mongering about everyone losing their jobs

- The focus on frameworks (LangChain, LlamaIndex, Haystack, CrewAI, AutoGen, DSPy etc. etc.) over core knowledge

  - also, the overlap and competition between these frameworks

  - also, these frameworks being veiled adverts for their own enterprise/cloud products

  - also, the fact that these frameworks' innovation outpaces their documentation

So, here is my plan for getting excited about LLMs:

1. Stop worrying about missing the latest trendy framework.

2. Make a reading list which covers all of the important LLM innovations (both academia and industry) and work through this list. I want the list to contain both papers (academia) and commentary on (successful) practical applications of LLMs.

3. Subscribe to email newsletters, LinkedIn, YouTube and Twitter accounts of significant LLM innovators and commentators (avoiding sources focusing on hype and speculation).

Here is my (constantly evolving) reading list:

| Status           | Title                                                                                          | Value | Year                   | Topic             | Type        | Notes                                                                        | Link(s)                                                                                                       |
| ---------------- | ---------------------------------------------------------------------------------------------- | ----- | ---------------------- | ----------------- | ----------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| ✅ read          | ReAct: Synergizing Reasoning and Acting in Language Models                                     | ★★★★★ | 2023                   | LLM Prompting     | paper       | Compelling and readable                                                      | <https://arxiv.org/abs/2210.03629>                                                                            |
| ✅ read          | Self-consistency improves chain of thought reasoning in language models                        | ★★★★☆ | 2022                   | LLM Prompting     | paper       |                                                                              | <https://arxiv.org/abs/2203.11171>                                                                            |
| ✅ read          | Hermes: A Text-to-SQL solution at Swiggy                                                       | ★★★★★ |                        |                   | Tech Blog   |                                                                              | <https://bytes.swiggy.com/hermes-a-text-to-sql-solution-at-swiggy-81573fb4fb6e>                               |
| ✅ read          | A survey on large language model based autonomous agents                                       | ★★★★★ | 2024                   |                   | paper       |                                                                              | <https://link.springer.com/article/10.1007/s11704-024-40231-1>                                                |
| ❌ not started   | Reflexion: Language Agents with Verbal Reinforcement Learning                                  |       | 2023                   | LLM Agents        | paper       | notes                                                                        | <https://arxiv.org/abs/2303.11366>                                                                            |
| ❌ not started   | Large Language Models Understand and Can Be Enhanced by Emotional Stimuli                      |       | 2023                   | LLM Prompting     | paper       |                                                                              |                                                                                                               |
| ❌ not started   | The Llama 3 Herd of Models                                                                     |       | 2024                   | Foundation models | paper       |                                                                              |                                                                                                               |
| ◐ partially read | Build a Large Language Model (from scratch)                                                    | ★★★★★ |                        | LLM Architecture  | book        | If I could read only 1 thing, this would be it                               |                                                                                                               |
| ✅ read          | Orchestrating Agents: Routines and Handoffs                                                    | ★★★★☆ | 2024                   | LLM Agents        | blog        | Very clear. Nice python code examples with no additional frameworks required | <https://cookbook.openai.com/examples/orchestrating_agents>                                                   |
| ◐ partially read | Graph Retrieval-Augmented Generation: A Survey                                                 | ★★★☆☆ | 2024                   | RAG               | paper       | notes                                                                        | <https://arxiv.org/abs/2408.08921>                                                                            |
| ❌ not started   | Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack          |       | 2024                   | LLM Security      | paper       |                                                                              | <https://arxiv.org/abs/2404.01833>                                                                            |
| ❌ not started   | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding               |       | 2018                   | Foundation Models | paper       |                                                                              | <https://arxiv.org/abs/1810.04805>                                                                            |
| ❌ not started   | Chain-of-Thought Reasoning Without Prompting                                                   |       | year                   | topic             | type        | notes                                                                        | <https://arxiv.org/abs/2402.10200>                                                                            |
| ❌ not started   | Tree of Thoughts: Deliberate Problem Solving with Large Language Models                        | ★★☆☆☆ | year                   | topic             | type        | notes                                                                        | <https://arxiv.org/abs/2305.10601>                                                                            |
| ❌ not started   | Graph of Thoughts: Solving Elaborate Problems with Large Language Models                       |       | 2023                   | LLM Agents        | paper       | notes                                                                        | <https://arxiv.org/abs/2308.09687>                                                                            |
| ❌ not started   | GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models |       | 2024                   | LLM Limitations   | paper       |                                                                              | <https://arxiv.org/abs/2410.05229v1>                                                                          |
| ❌ not started   | From Local to Global: A Graph RAG Approach to Query-Focused Summarization                      |       | 2024                   | RAG               | paper       | notes                                                                        | links                                                                                                         |
| ❌ not started   | Large Language Models are Zero-Shot Reasoners                                                  |       | 2022                   | LLM Prompting     | paper       | notes                                                                        | <https://arxiv.org/abs/2205.11916>                                                                            |
| ❌ not started   | Planning with Large Language Models via Corrective Re-prompting                                |       | 2022                   | topic             | paper       | notes                                                                        | <https://openreview.net/pdf?id=cMDMRBe1TKs>                                                                   |
| ❌ not started   | ReWOO: Decoupling Reasoning from Observations for Efficient Augmented Language Models          |       | 2023                   | LLM Agents        | paper       | notes                                                                        | <https://arxiv.org/abs/2305.18323>                                                                            |
| ❌ not started   | Sparse Priming Representations                                                                 |       | 2023                   |                   | github repo |                                                                              | <https://github.com/daveshap/SparsePrimingRepresentations> <br> <https://www.youtube.com/watch?v=YjdmYCd6y0M> |
| ❌ not started   | BOLAA: Benchmarking and Orchestrating LLM-augmented Autonomous Agents                          |       | 2023                   | LLM Agents        | paper       |                                                                              | <https://arxiv.org/abs/2308.05960> <br> <https://github.com/salesforce/BOLAA>                                 |
| ◐ partially read | ML and LLM system design: 450 case studies to learn from                                       | ★★★★★ | 2024                   | LLM Ops           | website     | notes                                                                        | <https://www.evidentlyai.com/ml-system-design>                                                                |
| ❌ not started   | Your RAG application is a communication system                                                 |       | 2024                   | RAG               | blog        | notes                                                                        | <https://superlinked.com/vectorhub/articles/rag-application-communication-system>                             |
| ❌ not started   | Reader-LM: Small Language Models for Cleaning and Converting HTML to Markdown                  |       | 2024                   |                   | blog        | notes                                                                        | <https://jina.ai/news/reader-lm-small-language-models-for-cleaning-and-converting-html-to-markdown/>          |
| ❌ not started   | Writing in the Margins: Better Inference Pattern for Long Context Retrieval                    |       | 2024                   | RAG               | paper       | notes                                                                        | <https://www.arxiv.org/abs/2408.14906>                                                                        |
| ❌ not started   | Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters    |       | 2024                   |                   | paper       | notes                                                                        | <https://arxiv.org/abs/2408.03314>                                                                            |
| ❌ not started   | LightRAG: Simple and Fast Retrieval-Augmented Generation                                       |       | 2024                   | RAG               | paper       | notes                                                                        | <https://arxiv.org/abs/2410.05779>                                                                            |
| ❌ not started   | GPT-4 Technical Report                                                                         |       | 2024                   | LLM Architecture  | paper       | notes                                                                        | <https://arxiv.org/abs/2303.08774>                                                                            |
| ❌ not started   | Sparks of Artificial General Intelligence: Early experiments with GPT-4                        |       | 2023                   | AGI               | paper       | notes                                                                        | <https://arxiv.org/abs/2303.12712>                                                                            |
| ❌ not started   | A Survey of Large Language Models                                                              |       | ongoing (started 2023) |                   | paper       | notes                                                                        | <https://arxiv.org/abs/2303.18223>                                                                            |
| ❌ not started   | QLoRA: Efficient Finetuning of Quantized LLMs                                                  |       | 2023                   | Quantization      | paper       | notes                                                                        | <https://arxiv.org/abs/2305.14314>                                                                            |
| ❌ not started   | Mamba: Linear-Time Sequence Modeling with Selective State Spaces                               |       | 2024                   | LLM Architecture  | paper       | notes                                                                        | <https://arxiv.org/abs/2312.00752>                                                                            |
| ❌ not started   | Towards Expert-Level Medical Question Answering with Large Language Models                     |       | 2023                   |                   | paper       | notes                                                                        | <https://arxiv.org/abs/2305.09617>                                                                            |
| ❌ not started   | ZEBRA: Zero-Shot Example-Based Retrieval Augmentation for Commonsense Question Answering       |       | 2024                   | RAG               | paper       | notes                                                                        | <https://arxiv.org/abs/2410.05077>                                                                            |
| ✅❌templaterow  | title                                                                                          | ★★☆☆☆ | year                   | topic             | type        | notes                                                                        | links                                                                                                         |

Efficient Few-Shot Learning Without Prompts

LLM sampling techniques:

- temperature sampling (Ackley et al., 1985; Ficler & Goldberg, 2017)

- top-k sampling (Fan et al., 2018; Holtzman et al., 2018; Radford et al., 2019)

- nucleus sampling (Holtzman et al., 2020)

Subscribed to/followed:

- Data Elixir

- Andrej Karpathy

- Sebastian Raschka

- AI Tidbits

- AlphaSignal

- Data Science Weekly

- The Batch (Andrew NG)

Interesting projects:

| Project Name | Description | Link(s)                                |
| ------------ | ----------- | -------------------------------------- |
| optillm      |             | <<https://github.com/codelion/optillm> |

References and Resources:

- <https://www.zeta-alpha.com/post/analyzing-the-homerun-year-for-llms-the-top-100-most-cited-ai-papers-in-2023-with-all-medals-for-o>

- [Anti-hype LLM reading list (github repo)](https://gist.github.com/veekaybee/be375ab33085102f9027853128dc5f0e)

- [LLM Agents Papers (github repo)](https://github.com/zjunlp/LLMAgentPapers)
