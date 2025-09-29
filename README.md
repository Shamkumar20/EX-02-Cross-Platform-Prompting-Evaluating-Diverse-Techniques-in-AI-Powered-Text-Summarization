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

# ChatGPT:
## 1. Zero-Shot Prompting
#### Prompt: “Summarize the basics of blockchain technology for undergraduate students.”
#### Output:
Blockchain is a digital system that records transactions in a secure and transparent way. Instead of being stored in one place, data is kept across many computers, making it hard to change or hack. Each block contains information, and blocks are linked together to form a chain. This system is widely used in cryptocurrencies like Bitcoin, but it also has applications in supply chain tracking, healthcare, and voting systems. The key features are decentralization, transparency, and security.

## 2. Few-Shot Prompting
#### Prompt with examples given:
Example 1: Artificial intelligence uses data and algorithms to help machines make predictions and decisions. It powers tools like chatbots and recommendation systems.
Example 2: Cloud computing means storing and accessing data over the internet instead of a local computer. It makes collaboration and storage easier.*
Now, summarize the basics of blockchain technology in a similar style.
#### Output:
Blockchain is a digital ledger that stores information across many computers at once. Instead of one central authority controlling it, everyone in the network shares the same record. Each “block” has a set of transactions, and once added, it cannot be changed. This creates a secure and trustworthy system. While it is best known for cryptocurrencies like Bitcoin, blockchain is also used in industries like banking, healthcare, and logistics.

## 3. Chain-of-Thought Prompting
#### Prompt:
"Think step by step: 1) Identify what blockchain is, 2) Explain how it works, 3) Highlight why it is important, and 4) Summarize its uses. Now provide a short summary for undergraduates."
#### Output:
Blockchain is a type of digital record-keeping. It works by grouping transactions into blocks, and each block is linked to the one before it, creating a secure chain. Because the record is stored across many computers, no single person controls it, and it is very hard to change past information. This makes it useful for building trust in digital transactions. Blockchain is important because it removes the need for intermediaries and reduces fraud. Its main uses include cryptocurrencies, tracking goods in supply chains, medical records, and secure voting systems.

## 4. Role-Based Prompting
#### Prompt:
"You are an educational content curator. Your role is to make complex technology simple for undergraduate students. Write a clear, 150-word summary of the basics of blockchain technology."
#### Output:
Blockchain is a system for recording information in a way that is secure, transparent, and shared. Instead of relying on one central authority, it distributes records across a network of computers. Each record, called a “block,” contains data such as transactions. These blocks are linked together, forming a chain that is nearly impossible to tamper with. This makes blockchain especially trustworthy. Its most famous use is in digital money like Bitcoin, but it is also valuable in areas such as tracking products, storing medical data, and even running secure elections. For students, the key ideas to remember are: decentralization (no single owner), transparency (everyone can see the data), and security (very hard to alter).

# GEMINI:
## 1. Zero-Shot Prompting:
#### Description:
Providing the instruction directly without any examples (e.g., "Explain the basics of blockchain technology in 100 words").	
#### Output: 
High for general concepts. Effective for simple definitions and core concepts, relying on the LLM's vast pre-trained knowledge. May lack depth or structure for complex explanations.

## 2. Few-Shot	Prompting: 
#### Description:
Including a small number of example input/output pairs in the prompt to set a pattern, style, or format (e.g., "Example 1: Input: 'What is a block?' Output: [definition]. Now, explain 'consensus mechanism.'").	
#### Output: 
High for structured and consistent output. Best for requiring a specific output format, tone, or level of detail. Improves accuracy and adherence to a defined explanation style.

## 3. Chain-of-Thought Prompting:
#### Description:
Explicitly asking the model to "think step-by-step" or showing a step-by-step reasoning process in examples.
#### Output:
Highest for complex or interconnected concepts. Excellent for explaining processes like transaction validation, mining, or how a consensus mechanism (like Proof-of-Work) functions, as it encourages 

## 4. Role-Based Prompting:	
#### Description:
Assigning a specific persona or role to the model (e.g., "You are a university professor teaching an introductory class. Explain blockchain to a student").
#### Output:'
High for pedagogical value and tone. Effective for tailoring the explanation's complexity, language, and tone to a specific audience. Improves engagement and clarity by adopting an expert or simpler perspective.

# Claude:
## 1. Zero-Shot Prompting
#### Prompt:
Explain the basics of blockchain technology."
#### Output:
Blockchain technology is a distributed ledger system that records transactions across multiple computers in a way that makes it difficult to alter retroactively. Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data. The decentralized nature means no single entity controls the entire chain, making it resistant to modification. Blockchain uses consensus mechanisms like Proof of Work or Proof of Stake to validate transactions. It's the underlying technology behind cryptocurrencies like Bitcoin but has applications in supply chain, healthcare, and voting systems. The transparency and immutability of blockchain make it valuable for applications requiring trust and verification without intermediaries.

## 2. Few-Shot Prompting
#### Prompt:
"Explain blockchain technology simply, like these examples: Cloud computing is like renting storage instead of buying a warehouse. Encryption is like sending a locked box where only the recipient has the key."
#### Output:
Blockchain is like a shared notebook that everyone in a group can read, but nobody can erase or change what's already written. When someone wants to add a new page, everyone in the group has to agree it's legitimate before it gets permanently added. Each new page references the previous one, creating a chain that's impossible to break or tamper with. Instead of trusting one person to keep the notebook safe and honest, everyone holds a copy, so no single person can cheat the system. This makes it perfect for recording transactions, agreements, or any information where trust and permanence matter.

## 3. Chain-of-Thought Prompting
#### Prompt:
"Explain the basics of blockchain technology. Think through this step-by-step: First, what problem does blockchain solve? Then, what are the core components
#### Output:
Blockchain addresses the trust issue in digital transactions by eliminating the need for intermediaries like banks or third parties to verify authenticity.
The system consists of blocks containing transaction data, cryptographic chains linking these blocks, distributed nodes maintaining copies, and consensus protocols for validation.

## 4. Role-Based Prompting
#### Prompt: 
Explain the basics of blockchain technology in a way that helps them understand its business value, using real-world examples and focusing on ROI and competitive advantages.
#### Output:
Blockchain is a shared, tamper-proof digital ledger that multiple parties can trust without a central authority. Think of it as a single source of truth that eliminates reconciliation costs and speeds up processes dramatically.
ROI indicators: Walmart cut product tracing from 7 days to 2 seconds—imagine applying that to your recalls or compliance audits. Maersk reduced shipping documentation time by 40%, directly impacting bottom-line efficiency. These aren't marginal gains; they're transformative.
Competitive advantages: Early adopters gain transparent supply chains that customers increasingly demand, automated contract execution reducing legal overhead, and faster settlement times improving cash flow. You're not just buying technology—you're buying market differentiation.

# Copilot:
## 1. Zero-Shot Prompting
#### Prompt: 
"Summarize the following article."
#### Summary:
Blockchain is a decentralized digital ledger that records transactions across a network of computers. Each transaction is stored in a block, which is linked to the previous one, forming a chain. This structure ensures data integrity and security, as altering any block would require consensus from the entire network. Blockchain technology eliminates the need for intermediaries, enabling peer-to-peer transactions. It's widely used in cryptocurrencies like Bitcoin but also has applications in supply chain management, healthcare, and voting systems.

## 2. Few-Shot Prompting
#### Prompt: 
"Here are examples of summaries for technical articles. [Provide 2–3 examples.] Now, summarize the following article." 
####Summary: 
Blockchain functions as a decentralized ledger, recording transactions in linked blocks across a network. Each block contains a timestamp and a reference to the previous block, ensuring chronological integrity. This design prevents unauthorized alterations, as changes require consensus from the network. Blockchain's decentralized nature removes the need for central authorities, facilitating transparent and secure transactions. Beyond cryptocurrencies, it's applied in areas like supply chain tracking, healthcare records, and digital identity verification.

## 3. Chain-of-Thought Prompting
Prompt: "Let's think step-by-step. First, explain how blockchain works, then summarize its key applications." 
Summary: Blockchain operates by storing data in blocks that are cryptographically linked, forming a chain. Each block contains transaction data, a timestamp, and a reference to the previous block, ensuring data integrity. This decentralized system requires consensus from network participants to validate new blocks, making it secure and tamper-resistant. Key applications of blockchain include facilitating cryptocurrencies like Bitcoin, enhancing supply chain transparency, securing healthcare records, and enabling smart contracts.

## 4. Role-Based Prompting
#### Prompt:
"You are a professional content curator for students. Summarize the article in simple terms".
#### Summary:
Think of blockchain as a special kind of digital notebook that’s shared among many people. Whenever something happens—like a transaction—it gets written on a new page (called a block). Each page connects to the one before it, making a long, unchangeable chain. This means no one can secretly change what’s written without everyone else knowing. Because it's shared and secure, blockchain is used for things like Bitcoin, tracking packages, managing medical records, and even voting. It helps keep information safe, transparent, and easy to check.


## Algorithm: Evaluating Prompting Techniques on Blockchain Summarization
### Step 1: Define the Task
Task: Summarization of a given text ("The Basics of Blockchain Technology").
Evaluation Metrics:
Accuracy (factual correctness of blockchain concepts)
Coherence (logical flow, grammar, readability)
Simplicity (ease of understanding for a beginner)
Speed (response time)

### Step 2: Prepare Input Material
Collect a standard passage/document about “The Basics of Blockchain Technology” (≈300–500 words).
Ensure the passage covers:
Definition of blockchain
Features (decentralization, immutability, transparency)
Applications (cryptocurrency, supply chain, smart contracts)

### Step 3: Design Prompts
Zero-Shot Prompt:
“Summarize the basics of blockchain technology in simple words.”
Few-Shot Prompt:
Provide 2–3 example summaries of other tech topics (like AI, IoT), then ask:
“Now summarize the basics of blockchain technology in the same way.”
Chain-of-Thought Prompt:
“Think step by step about the basics of blockchain: definition → features → applications. Then provide a summary.”
Role-Based Prompt:
“You are a professor teaching beginners. Summarize the basics of blockchain technology in an easy-to-understand manner.”

### Step 4: Generate Summaries
For each technique, run the corresponding prompt through the LLM (ChatGPT, Gemini, Claude, Copilot).
Collect 4 outputs per model.

### Step 5: Evaluate Outputs
Accuracy Check: Compare with reference text (blockchain definitions from trusted sources like IBM/Investopedia).
Coherence Check: Human evaluator or readability score (Flesch–Kincaid index).
Simplicity Check: Judge whether a beginner can understand (survey or difficulty rating).
Speed Check: Measure response time (in seconds).

### Step 6: Score & Compare
Assign a 1–5 rating for each metric.
Create a table like:
<img width="1149" height="362" alt="Screenshot 2025-09-29 131322" src="https://github.com/user-attachments/assets/eaeacd2c-ca8e-4776-9747-92ca4986d8d1" />


## Result:
Thus Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Tex t-Summarization is best in ChatGPT and Copilot are executed successfully.


