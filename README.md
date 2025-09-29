# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

### ChatGPT:
## 1. Zero-Shot Prompting
Prompt: “Summarize the basics of blockchain technology for undergraduate students.”
Output:
Blockchain is a digital system that records transactions in a secure and transparent way. Instead of being stored in one place, data is kept across many computers, making it hard to change or hack. Each block contains information, and blocks are linked together to form a chain. This system is widely used in cryptocurrencies like Bitcoin, but it also has applications in supply chain tracking, healthcare, and voting systems. The key features are decentralization, transparency, and security.

## 2. Few-Shot Prompting
Prompt with examples given:
Example 1: Artificial intelligence uses data and algorithms to help machines make predictions and decisions. It powers tools like chatbots and recommendation systems.
Example 2: Cloud computing means storing and accessing data over the internet instead of a local computer. It makes collaboration and storage easier.*
Now, summarize the basics of blockchain technology in a similar style.
Output:
Blockchain is a digital ledger that stores information across many computers at once. Instead of one central authority controlling it, everyone in the network shares the same record. Each “block” has a set of transactions, and once added, it cannot be changed. This creates a secure and trustworthy system. While it is best known for cryptocurrencies like Bitcoin, blockchain is also used in industries like banking, healthcare, and logistics.

## 3. Chain-of-Thought Prompting
Prompt:
"Think step by step: 1) Identify what blockchain is, 2) Explain how it works, 3) Highlight why it is important, and 4) Summarize its uses. Now provide a short summary for undergraduates."
Output:
Blockchain is a type of digital record-keeping. It works by grouping transactions into blocks, and each block is linked to the one before it, creating a secure chain. Because the record is stored across many computers, no single person controls it, and it is very hard to change past information. This makes it useful for building trust in digital transactions. Blockchain is important because it removes the need for intermediaries and reduces fraud. Its main uses include cryptocurrencies, tracking goods in supply chains, medical records, and secure voting systems.

## 4. Role-Based Prompting
Prompt:
"You are an educational content curator. Your role is to make complex technology simple for undergraduate students. Write a clear, 150-word summary of the basics of blockchain technology."
Output:
Blockchain is a system for recording information in a way that is secure, transparent, and shared. Instead of relying on one central authority, it distributes records across a network of computers. Each record, called a “block,” contains data such as transactions. These blocks are linked together, forming a chain that is nearly impossible to tamper with. This makes blockchain especially trustworthy. Its most famous use is in digital money like Bitcoin, but it is also valuable in areas such as tracking products, storing medical data, and even running secure elections. For students, the key ideas to remember are: decentralization (no single owner), transparency (everyone can see the data), and security (very hard to alter).

## Algorithm


## Result


