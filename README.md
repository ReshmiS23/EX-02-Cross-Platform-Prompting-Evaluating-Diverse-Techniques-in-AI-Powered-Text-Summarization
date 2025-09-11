# EX-02 Cross-Platform Prompting: Evaluating AI Techniques in Text Summarization

## AIM
To evaluate and compare different prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across AI platforms (ChatGPT, Gemini, Claude, Copilot) for the task of summarizing technical articles.

---

## Scenario
You are part of a content curation team for an educational platform. Your task is to generate short, accurate, and student-friendly summaries of a **500-word technical article on "The Basics of Blockchain Technology"** using multiple prompting strategies and platforms.  

The goal is to find which combination of **platform + prompting style** produces the best results in terms of:
- Accuracy  
- Coherence  
- Simplicity  
- Speed  
- User Experience  

---

## Algorithm

1. **Input Preparation**  
   - Select a 500-word article on *The Basics of Blockchain Technology*.  
   - Ensure the article covers definitions, features, principles, and applications.  

2. **Define Prompting Styles**  
   - **Zero-shot** → “Summarize the following article in about 150 words for undergraduate students.”  
   - **Few-shot** → Provide 1–2 example summaries first, then request a blockchain summary.  
   - **Chain-of-Thought** → “Break the article into key points step by step, then write a final summary.”  
   - **Role-based** → “You are a professor. Explain blockchain clearly to beginners in ~150 words.”  

3. **Run Across Platforms**  
   - Use **ChatGPT, Gemini, Claude, and Copilot**.  
   - Apply all four prompting techniques.  
   - Save outputs for evaluation.  

4. **Evaluation Criteria**  
   - **Accuracy** → Are facts correct?  
   - **Coherence** → Does it flow logically?  
   - **Simplicity** → Is it easy to read for students?  
   - **Speed** → How quickly is the output generated?  
   - **User Experience** → Was the platform smooth to use?  

5. **Scoring**  
   - Use **1–5 scale** (1 = Poor, 5 = Excellent).  
   - Record scores in a result table.  
   - Calculate averages for each combination.  

6. **Comparison & Analysis**  
   - Compare results across platforms and techniques.  
   - Identify the **best combination**.  
   - Provide recommendations.  

---

## Results

### Example Observations:

  ## Chatgpt

### Few Shot:
   Blockchain is a decentralized digital ledger that records transactions across multiple computers, ensuring security and transparency without a central authority. Each block stores data, a timestamp, and a link to the previous block, making records nearly impossible to alter. Transactions are verified using consensus mechanisms like Proof of Work or Proof of Stake. Blockchains can be public, private, consortium, or hybrid. Beyond cryptocurrencies like Bitcoin, blockchain supports secure payments, supply chain tracking, healthcare record management, and voting systems. Its strengths are decentralization, immutability, and security, though challenges such as scalability and regulation remain. It is a transformative digital technology.

### Zero Shot:
   Blockchain is a secure, distributed ledger that records transactions transparently across a network of computers. Instead of being controlled by one authority, every participant keeps a copy of the ledger. Each block includes transaction details, a timestamp, and a cryptographic link to the previous block, making the chain tamper-resistant. Transactions are validated through consensus mechanisms such as Proof of Work or Proof of Stake. Blockchains may be public, private, consortium, or hybrid. While best known for powering Bitcoin, they are also used in finance, healthcare, supply chains, and voting. Its advantages are decentralization, transparency, and strong data security.

 ### Chain of thoughts:
   Blockchain is defined as a decentralized ledger where data is stored in linked blocks. Key features include transparency, immutability, and security. It works by broadcasting transactions to nodes, validating them through consensus, and grouping them into blocks that are linked cryptographically. Types of blockchain include public, private, consortium, and hybrid. Applications range from cryptocurrency and cross-border payments to supply chain tracking, healthcare record security, smart contracts, and voting systems. In short, blockchain combines decentralization, consensus, and cryptography to build trust in digital transactions. Its benefits are clear, but challenges like scalability and regulation still need solutions.

 ###  Role based:
   Think of blockchain as a shared digital notebook that everyone in a group can see and write in, but no one can secretly erase. Each “page,” called a block, stores transaction data, time, and a secure link to the previous page, forming a tamper-proof chain. Instead of one authority controlling it, many computers (nodes) check and approve transactions using rules called consensus mechanisms. There are public, private, consortium, and hybrid blockchains. Beyond Bitcoin, blockchain is useful in finance, supply chains, healthcare, and even voting. Its main strengths are decentralization, transparency, and security, making it a revolutionary technology.

  ## Gemini

 ### Few shot:
   Example: Imagine Google Docs. Multiple people can access and edit a document, but a central authority (Google) controls it. Blockchain is different. A transaction is like a paragraph of text. A block is a page, and the blockchain is the entire document. Multiple independent users (nodes), not a single company, keep copies of this document. Cryptography links the pages, making them tamper-proof. If you change a past page, the entire chain is broken, so everyone knows it's an invalid copy. This creates a transparent, immutable record without a central administrator.

 ### Zero shot:
   Blockchain is a distributed, immutable digital ledger that transparently records transactions across a network of computers. It is decentralized, meaning no single authority controls the network, and the data is synchronized across all participants. Transactions are bundled into "blocks," which are cryptographically linked together in a chronological "chain". Consensus mechanisms, like Proof of Work or Proof of Stake, ensure the validity of transactions before they are added to the chain. This structure guarantees data integrity, security, and trust without intermediaries.

 ### Chain of thoughts:
    
   Step 1: Understand ledgers and centralization. First, recognize that a traditional ledger is a record kept and controlled by a single entity, like a bank. This centralization creates a single point of failure and requires trust in that third party.
    
   Step 2: Introduce distributed ledgers. Next, envision a distributed ledger where the record is copied and shared across a peer-to-peer network of computers (nodes). Every participant has an identical copy, eliminating the central authority.
   
   Step 3: Explain blocks and cryptography. Now, introduce blocks as bundles of transaction data. Explain that cryptography is used to secure and link these blocks together. A cryptographic "hash" of the previous block is included in the new block, creating a chronological chain.
   
   Step 4: Detail consensus. Finally, describe the consensus mechanism, a set of rules all nodes follow to agree on new transactions. This process ensures the immutability of the chain. If someone tries to alter a block, its hash changes, breaking the chain and immediately alerting the network.

   ### Role based:
         
   Developer: For a developer, blockchain is a distributed and decentralized digital ledger that stores transactional data in cryptographically-linked "blocks". Every participating node holds a copy, ensuring transparency and security through a consensus mechanism. This immutable structure is fundamental for building decentralized applications (DApps) and smart contracts, which are automated, self-executing agreements. It’s a peer-to-peer network where you, the developer, contribute to the system's logic and trust. 
            Business Executive: For a business executive, blockchain is a tool for enhanced transparency and efficiency. It removes the need for costly and slow intermediaries like banks in multi-party transactions. The immutable ledger creates a single, trusted record for all participants, streamlining supply chains and automating processes with smart contracts. This translates to reduced fraud risk, lower costs, and faster transaction settlement, leading to significant operational improvements.

   ## Copilot

   ### Few shot:
   Blockchain stores data in blocks linked chronologically.
   -It’s decentralized—no single point of control.
   -Transactions are verified by consensus mechanisms.
   -Cryptographic hashes secure each block.
   -Applications include finance, supply chain, and voting.
This pattern shows how blockchain combines distributed architecture with cryptographic integrity.

   ### Zero Shot:
   
   Blockchain is a decentralized digital ledger that records transactions across multiple computers. It ensures transparency, security, and immutability without needing a central authority. Each block contains data, a timestamp, and a cryptographic hash of the previous block, forming a secure chain. Used in cryptocurrencies like Bitcoin, blockchain also supports smart contracts and decentralized applications. Its core strengths lie in trustless verification and resistance to tampering.

   ### Chain of thoughts:
   
   To understand blockchain, start with the concept of a ledger. Traditional ledgers are centralized, but blockchain distributes this ledger across a network. Each transaction is verified by consensus, then added to a block. That block is linked to the previous one using a hash, creating a chain. Because each block depends on the one before it, altering data is nearly impossible. This makes blockchain secure and transparent.

   ### Role based:

   As a blockchain developer, I see it as a trust machine. It’s a distributed ledger where each block holds verified transactions. We use cryptographic hashes to link blocks, ensuring data integrity. Smart contracts let us automate agreements without intermediaries. Whether it’s finance, identity, or logistics, blockchain offers a tamper-proof, decentralized solution.
   
           
- **ChatGPT Few-shot** → Best for accuracy and detail.  
- **Claude Role-based** → Best for clarity and simplicity.  
- **Gemini Chain-of-Thought** → Strong structure, step-by-step logic.  
- **Copilot Zero-shot** → Fast but sometimes oversimplified.  

---

## Final Result Table

| Platform | Technique       | Accuracy | Coherence | Simplicity | Speed | User Exp. | Avg Score |
|----------|----------------|----------|-----------|------------|-------|-----------|-----------|
| ChatGPT  | Zero-shot      | 4        | 4         | 4          | 5     | 5         | 4.4       |
| ChatGPT  | Few-shot       | 5        | 5         | 4          | 4     | 5         | 4.6       |
| ChatGPT  | Chain-of-Thought | 5      | 5         | 3          | 4     | 5         | 4.4       |
| ChatGPT  | Role-based     | 5        | 5         | 5          | 4     | 5         | 4.8       |
| Gemini   | Zero-shot      | 4        | 4         | 3          | 4     | 4         | 3.8       |
| Gemini   | Few-shot       | 4        | 4         | 4          | 4     | 4         | 4.0       |
| Gemini   | Role-based     | 5        | 5         | 5          | 5     | 4         | 4.8       |
| Claude   | Chain-of-Thought | 5      | 5         | 4          | 4     | 4         | 4.4       |
| Copilot  | Zero-shot      | 3        | 3         | 3          | 5     | 3         | 3.4       |

---

## Conclusion
- **Best Accuracy:** ChatGPT Few-shot & Claude Role-based  
- **Best Simplicity:** Claude Role-based & ChatGPT Role-based  
- **Best Coherence:** Gemini Chain-of-Thought  
- **Fastest:** Copilot Zero-shot  
- **Overall Winner:** Claude Role-based (balanced clarity, simplicity, and accuracy)  

---


Thus the evaluation for summarization tasks is succesfully implemented.
