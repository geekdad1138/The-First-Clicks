## **Vaswani et al.: Attention Is All You Need (2017)**

### **What problem existed?**

Before 2017, AI models for language (like Google Translate) mostly used **Recurrent Neural Networks (RNNs)**. These models processed text like a human reading a sentence: one word at a time, from left to right. Because they were sequential, they were slow to train and, more importantly, they "forgot" the beginning of a long sentence by the time they reached the end. They struggled with **context**—understanding how a word at the start of a paragraph might change the meaning of a word at the end.

### **What did this person actually do?**

A team of researchers at Google Brain published a paper introducing the **Transformer** architecture. Instead of reading sequentially, the Transformer used a mechanism called **"Self-Attention."** This allowed the model to look at every word in a sentence simultaneously and mathematically "weight" which other words were most relevant to it, regardless of how far apart they were.

### **Why did it unlock something?**

It solved the **parallelization** problem. Because Transformers don't have to process words in order, they can be trained on massive amounts of data across thousands of GPUs at once. It also allowed for "Global Context"—the model could finally understand that "it" in the fifth sentence referred to the "robot" in the first sentence. It turned language processing into a massive, high-speed pattern-matching problem.

### **What wouldn't exist without it?**

* **Generative AI (LLMs):** Every modern Large Language Model—GPT-4, Claude, Gemini, Llama—is a "Transformer."
* **ChatGPT:** The "T" in GPT stands for **Transformer**. Without this architecture, we wouldn't have the scale required to create conversational AI.
* **The "General" in AGI:** For the first time, we found an architecture that works for almost everything: text, images (Vision Transformers), audio, and even protein folding (AlphaFold).
