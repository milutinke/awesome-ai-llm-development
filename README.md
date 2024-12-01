# Awesome AI LLM Development Resources 🚀

**Awesome Collection of Resources for Learning AI and Large Language Model (LLM) Development**

Discover a comprehensive guide that covers everything from basic concepts to advanced topics, helping you navigate the exciting world of creating **Generative AI** (**GenAI**) applications using **LLMs**. Whether you're already developing **GenAI** apps or looking to enter the field, there's something here for everyone.
This guide is oriented towards practical, and non-theoretical approach, advocating on hands on approach.

### Contributions welcomed

As someone who works on creating Generative AI applications using LLMs, not as an ML engineer but as a backend web developer, I've been asked by many people how to get started. Over the past year, I learned by doing, reading research papers, articles, blog posts, and watching YouTube videos without any particular order, basically piecing it all together. I've decided to create a curated list to help people of various background learn this in a practical manner.

Thus, I strongly encourage and welcome **contributions** to this list to enhance its quality and relevance. 

**Your input** can help include valuable resources I may have missed.

Cheers 🥂

---

## Table of Contents

- [Section 1: The Basic Concepts](#section-1-the-basic-concepts)
- [Section 2: Prompt Engineering - Basics](#section-2-prompt-engineering---basics)
- [Section 3: Building GenAI Apps with LLM APIs](#section-3-building-genai-apps-with-llm-apis)
- [Section 4: Embeddings and Vector Databases](#section-4-embeddings-and-vector-databases)
- [Section 5: Retrieval Augmented Generation (RAG)](#section-5-retrieval-augmented-generation-rag)
- [Section 6: Advanced RAG Techniques](#section-6-advanced-rag-techniques)
- [Section 7: LLM AI Agents](#section-7-llm-ai-agents)
- [Section 8: LLM AI Agents Frameworks](#section-8-llm-ai-agents-frameworks)
- [Appendix](#appendix)
  - [Production Pre-requisites](#production-pre-requisites)
  - [Optional Stuff](#optional-stuff)
- [Related Awesome Currated Lists](#related)
- [TODO](#todo)
  
---

## Section 1: The Basic Concepts

1. [What is AI, Machine Learning (ML), Deep Learning, Generative AI?](https://youtu.be/qYNweeDHiyU)
2. [Google's Introduction to Gen AI](https://youtu.be/G2fqAlgmoPo)
3. [What are Large Language Models (LLMs)?](https://youtu.be/xU_MFS_ACrU)
4. [What are tokens in LLMs?](https://youtu.be/K8crRCC7Dzg)
5. [What are parameters in LLMs?](https://youtu.be/PAbZRGGYNyM)
6. [What is a context window in LLMs? + How GPT works visualized in Excel](https://youtu.be/IllijoYSH80)
7. [What is temperature in LLMs?](https://youtu.be/_YTnZOYxSjE)
8. [What are Top P and Top K in LLMs?](https://youtu.be/aDmp2Uim0zQ)
9. [How and where is Gen AI used?](https://youtu.be/oTqG2DbXl2Y)

## Section 2: Prompt Engineering - Basics

**Written Guide:**

- [Prompting Guide](https://www.promptingguide.ai/) (Check it out too)

**Videos:**

1. [What is prompting?](https://youtu.be/pZsJbYIFCCw)
2. [Jeff Su's Prompt Formula](https://youtu.be/jC4v5AS4RIM) (Role/Persona + Context + Task/Action + Example + Format) (Similar to the [CRAFT](https://youtu.be/Gidc185wnEA))
3. [Zero-Shot, First-Shot, Few-Shot Prompting](https://youtu.be/sW5xoicq5TY)
4. [Chain-of-Thought (CoT) Prompting](https://youtu.be/AFE6x81AP4k)
5. [Meta Prompting](https://youtu.be/cgBVHj9DXXY) (Use AI to create really good prompts using prompt engineering)

**Tips:**

- [Use XML tags for prompt structuring](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/use-xml-tags) (Gives the best results)

## Section 3: Building GenAI Apps with LLM APIs

**Prerequisites Needed:**

1. [Python](https://youtu.be/rfscVS0vtbw)
2. [Python OOP](https://youtu.be/JeznW_7DlB0)
3. [REST API](https://youtu.be/lsMQRaeKNDk)
4. [FastAPI in Python](https://youtu.be/tLKKmouUams)
5. [WebSockets Explained in Python](https://youtu.be/nDgdldBPoE0)
6. [WebSockets with FastAPI](https://youtu.be/ADVsjLHevtY)

### Actually Building Gen AI Apps Using OpenAI API Standard

1. [Using OpenAI API - Documentation](https://platform.openai.com/docs/quickstart)
2. [Using ChatGPT/LLMs with OpenAI Python Package](https://youtu.be/I6T9Ztn0S-M) (Video)
3. [What are LLM Tools/Function Calls](https://youtu.be/P3buv6P_u7c)
4. [LLM Function/Tool Calling - Deep Dive + Examples](https://youtu.be/gMeTK6zzaO4)
5. [OpenAI Assistants API](https://youtu.be/0h1ry-SqINc)
6. [What is LangChain?](https://youtu.be/1bUy-1hGZpI)
7. [LangChain Master Class](https://youtu.be/yF9kGESAi3M)

## Section 4: Embeddings and Vector Databases

**In this section, you will learn concepts needed for implementing Retrieval Augmented Generation (RAG).**

1. [What are Embeddings?](https://youtu.be/wgfSDrqYMJ4)
2. [What are Embeddings (More Detailed)](https://youtu.be/NEreO2zlXDk)
3. *[Word2Vec](https://www.youtube.com/watch?v=ISPId9Lhc1g) ([Blog Form](https://jalammar.github.io/illustrated-word2vec/))* (*Optional for deeper understanding*)
4. [Vector Databases + Embeddings + Indexes](https://youtu.be/dN0lsF2cvm4) (A very nice explanation, simplified)
5. [Using Chroma DB + OpenAI Embedding](https://youtu.be/Qs_y0lTJAp0)
6. [Using OpenAI Embeddings for CSV Search](https://youtu.be/xzHhZh7F25I)
7. [How to Choose a Vector Database?](https://youtu.be/aX_hdQEintc)

**Optional More In-Depth Guides About What Vector Databases Are:**

- [Understanding How Vector Databases Work!](https://youtu.be/035I2WKj5F0) (Detailed, how it actually works)
- [A Long-Form Very Detailed Video + Retrieval Augmented Generation (RAG)](https://youtu.be/wc3Lh-eiNBM)

## Section 5: Retrieval Augmented Generation (RAG)

1. [What is RAG?](https://youtu.be/qppV3n3YlF8)
2. [RAG vs Fine-Tuning](https://youtu.be/00Q0G84kq3M)
3. [Simple (Naive) RAG Implementation Using MongoDB](https://youtu.be/JEBDfGqrAUA)
4. [Implementing RAG from Scratch + Different Techniques](https://youtu.be/sVcwVQRHIc8) (Practical + Code Example)

## Section 6: Advanced RAG Techniques

1. [A Very Detailed Deep Dive into RAG + Various RAG Architectures by Stanford](https://youtu.be/mE7IDf2SmJg) (More advanced, academic, theoretical approach, very detailed)
2. [Building Production-Ready RAG Applications: Jerry Liu (2023, a bit outdated, but nice to know)](https://youtu.be/TRjq7t2Ms5I)
3. [Advanced RAG Optimization to Make It Production-Ready](https://youtu.be/nlh-kHT5-_E)
4. [A Survey of Production RAG Pain Points and Solutions // Jerry Liu // AI in Production Conference (2024)](https://youtu.be/pRhXoEXhWAM)
5. [Building Production RAG Over Complex Documents - by Databricks (2024)](https://youtu.be/dI_TmTW9S4c)

## Section 7: LLM AI Agents

1. [What are AI Agents?](https://youtu.be/F8NKVhkZZWI)
2. [AI Agents vs Assistants](https://youtu.be/IivxYYkJ2DI)
3. [AI Agents Architectures](https://youtu.be/FEU6-Il8jjw)

## Section 8: LLM AI Agents Frameworks

### Crew AI 

**Pros:**

- **Role-Based Agent Design:** Allows customization of agents with specific roles and goals, enabling cohesive operation.
- **Integration with LangChain:** Built on top of LangChain, providing access to a wide range of tools and models.
- **User-Friendly:** Simplifies the development process, making it suitable for rapid prototyping and implementation.

**Cons:**

- **High-Level Abstraction:** While easy to use initially, deeper customization can become complex due to its high-level nature.
- **Dependency on LangChain:** Relies on the robustness and updates of the underlying framework.

**Links:**

- [Documentation](https://learn.crewai.com/)
- [Crash Course](https://youtu.be/q6QLGS306d0)
- [CrewAI Flows Crash Course](https://youtu.be/8PtGcNE01yo) 

### LangGraph 

**Pros:**

- **Stateful Graph Methodology:** Allows intricate agent state tracking and updating during execution, enhancing control over processes.
- **Multi-Agent Coordination:** Supports multiple agents within a single graph structure, each with its own prompts, LLMs, tools, and custom code.
- **Integration with LangChain:** Provides access to a wide range of tools and models, enhancing agent capabilities.

**Cons:**

- **Visual Builder Dependency:** Relies on visual builders for designing applications, which may not suit teams preferring direct coding.
- **Less Granular Control:** May offer less control compared to direct coding methods, depending on the robustness of the LangGraph system.

**Links:**

- [Documentation](https://langchain-ai.github.io/langgraph/tutorials/introduction/)
- [Crash Course](https://youtu.be/PqS1kib7RTw) 

### AutoGen

**Pros:**

- **Active Community Support:** Features a very active community, beneficial for developers seeking support and collaboration.
- **Customizable Agents:** Offers agents that can integrate LLMs, tools, and human feedback, making task execution highly flexible.
- **Memory and Context Management:** Enhances utility in LLM applications demanding these features.

**Cons:**

- **Complexity in Agent Roles:** Determining the appropriate number of agents and their roles can be complex.
- **Potential for Infinite Loops:** Without proper tuning, agents could enter infinite loops, leading to increased computational costs and resource usage.
- **Limited Support for Open-Source LLMs:** Currently offers limited compatibility with open-source LLMs.

**Links:**

- [Documentation](https://microsoft.github.io/autogen/0.2/) 
- [Crash Course](https://youtu.be/JmjxwTEJSE8)

### Agency Swarm

**Pros:**

- **Ease of Learning and Use:** Designed to be user-friendly, facilitating quick learning and implementation.
- **Utilizes OpenAI Assistants API:** Leverages OpenAI's API for robust AI capabilities.
- **Built-in Tools and Agents:** Provides a suite of tools and agents ready for use.
- **Effective Multi-Agent Communication:** Supports multiple communication methods among agents.

**Cons:**

- **Integration Challenges:** Not easily integrated into other applications.
- **Small Community:** Limited user base may affect support and development.
- **Limited Maintenance:** Maintained and developed by only a few individuals, which may impact updates and support.

**Links:**

- [Documentation](https://vrsen.github.io/agency-swarm/)
- [Crash Course](https://youtu.be/MOyl58VF2ak) 
- [Sample Agents](https://youtu.be/hb0j9Qn-KjM)
- [Creating an AI Agency with Cursor AI Editor in Plain English](https://youtu.be/Og73plUTabs)
- [Easy Deployment of AI Agencies](https://youtu.be/53_e3lmk6Mo)

## Appendix

### Production Pre-requisites

**Production-Ready Python FastAPI Apps + Concepts:**

1. **Multi-threading:**
   - [Multi-threading Explained](https://youtu.be/AZnGRKFUU0c) (Theory and visuals)
   - [Multi-threading in Python](https://youtu.be/IEEhzQoKtQU)
   - [Asynchronous Programming in Python - async/await](https://youtu.be/t5Bo1Je9EmE)
2. [Deep Dive into Asynchronous Programming with FastAPI](https://youtu.be/KL6CjNxkZDQ) (More advanced, for production, optional for now)
3. [WSGI & ASGI Simplified](https://youtu.be/LtpJup6vcS4)
4. [Uvicorn and FastAPI](https://youtu.be/TpOxfLKR09k)
5. [Production-Ready FastAPI Apps](https://youtu.be/XlnmN4BfCxw)
6. [Logging](https://youtu.be/pxuXaaT1u3k)

### Optional Stuff

Things listed here are not 100% required, but it's nice to have at least a conceptual and basic understanding, which could be useful.

**Useful Stuff:**

- [LLM Engineer's Handbook: From Theory to Production | TDE Workshop](https://youtu.be/6WmPfKPmoz0)

**How LLMs Work Under the Hood:**

1. [Large Language Models from Scratch (Simplified) - Part 1](https://youtu.be/lnA9DMvHtfI)
2. [Large Language Models from Scratch (Simplified) - Part 2](https://youtu.be/YDiSFS-yHwk)
3. [3Blue1Brown's Playlist for Neural Networks + LLMs](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) (Very nice visualizations)
4. [Attention Is All You Need](https://arxiv.org/pdf/1706.03762) (Research paper that introduced the Transformers architecture)
5. [Attention Is All You Need - Explained](https://youtu.be/bCz4OMemCcA) (A video explanation of the research paper with nice visualizations)
6. [LLM Visualization Website](https://bbycroft.net/llm) (A very nice website that explains how LLMs/Transformers architecture works)

## Related 

- [Awesome LLM Inference](https://github.com/DefTruth/Awesome-LLM-Inference)

   A currated list of trending research papers with code
  
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM)
  
  A curated list of papers about large language models, especially relating to ChatGPT. It also contains frameworks for LLM training, tools to deploy LLM, courses and tutorials about LLM and all publicly available LLM checkpoints and APIs.)

- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps)

  A curated collection of awesome LLM apps built with RAG and AI agents. This repository features LLM apps that use models from OpenAI, Anthropic, Google, and even open-source models like LLaMA that you can run locally on your compute

## TODO:

- [ ] Link additional resources  
- [ ] Find and link code examples of Generative AI applications using LLMs and LLM AI Agents
- [ ] Link more of similar/on-topic repositories
- [ ] Expand the optional theoretical background section to include resources for learning ML in depth and better resources on how LLMs work under the hood  

## License

GNU General Public License v3.0
