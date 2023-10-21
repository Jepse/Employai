
# LLM + Autogen + MemGPT + Python = Employai ⭐
by Jean-Philippe Simard assisted by GPT-4

Every day, the evolution of artificial intelligence takes an exponential leap. This document introduces a concept that combines the latest technologies and libraries to achieve "Employai"(pronounced like the french word "Employé"), an innovative combination of LLM ("GPT, Llama, others"), Microsoft Autogen, MemGPT, and Python.

AutoGen is a framework developed by Microsoft to simplify the orchestration, optimization, and automation of workflows based on Large Language Models (LLM). It allows for the creation of next-generation applications based on multi-agent conversations with minimal effort. It provides customizable and conversational agents that integrate the capabilities of the most advanced LLMs, such as GPT-4, while overcoming their limitations by incorporating interactions with humans and tools. AutoGen is the result of collaborative research between Microsoft, Penn State University, and the University of Washington. For more information, you can refer to the official article: [Microsoft's Official Article on AutoGen](https://www.microsoft.com/en-us/research/blog/autogen-enabling-next-generation-large-language-model-applications/) and [Autogen GitHub](https://github.com/microsoft/autogen).

MemGPT is a system that intelligently manages different levels of memory in LLMs to efficiently provide an extended context in the limited context window. For instance, MemGPT knows when to push critical information to a vector database and when to retrieve it later, allowing for ongoing conversations. The concept is inspired by the hierarchical memory systems of traditional operating systems. It uses a technique called virtual context management to handle data movements between fast and slow memory. The code and data for MemGPT experiments are available on their official website and GitHub repository.

By combining AutoGen's orchestration capabilities with the natural language processing power of LLMs, MemGPT's memory, and using Python as a scripting language to link these components, one can create a robust and versatile agent capable of handling a variety of complex tasks while interacting smoothly and naturally with users. The vision for Employai is the complete integration of this concept with "open source" models (GPT-3, HuggingFace Transformers, etc.) offline. Thus, a high-performance computer would host an LLM that would serve the agents required by a local API. This would reduce the operating costs of the models, increase information security, and allow the models to evolve in their respective environments. The integration of VoIP (Voice over IP) could enable communication between humans and LLMs. This would allow them to function at the same level as a human employee working remotely. [Employai GitHub Repository](https://github.com/Jepse/employai).
