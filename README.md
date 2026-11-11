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

## Algorithm
Algorithm: Summarizing a Technical Article Using AI
Step 1: Start.

Step 2: Assign a role to the AI.

- Act as an expert technical content curator for an educational platform.

Step 3: Provide the topic.

- Select the technical article titled "The Basics of Blockchain Technology."

Step 4: Define the target audience.

- The summary should be suitable for undergraduate students.

Step 5: Specify the input.

- Provide a 500-word technical article about blockchain technology.

Step 6: Identify the important information.
- Extract the definition of blockchain.
- Identify its working principles.
- Identify its key features.
- List the types of blockchain.
- Identify its applications.
- Explain its advantages and limitations.
Step 7: Simplify technical concepts.
- Convert complex technical explanations into simple, understandable language.
- Retain important technical terms.
Step 8: Organize the information.
- Use appropriate headings and bullet points.
- Arrange the information in a logical sequence.
Step 9: Generate the summary.

- Create a concise summary without losing the important concepts.

Step 10: Review the summary.
- Check technical accuracy, clarity, grammar, and relevance.
- Remove unnecessary information and repetition.
Step 11: Display the final summary.

- Present the content in a student-friendly format.

Step 12: Stop.
## AI Tools used: 
1. Chat gpt
2. Meta AI

## Out put
 PROMPT:i am working under a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. i want you to summarize a 500-word technical article on "The Basics of Blockchain Technology"

 Chat gpt: 
             1. Introduction
Blockchain is a digital technology used to store and share information securely across a network of computers. It is a type of distributed ledger technology (DLT), meaning that information is recorded and shared among multiple participants rather than being stored in one central location.

Blockchain organizes information into groups called blocks, which are connected chronologically using cryptographic techniques. This creates a continuous chain of records that is difficult to modify without the network detecting the change.
2. How Blockchain Works
Blockchain operates through a sequence of steps:
1. Transaction creation: A user initiates a transaction, such as transferring digital currency.
2. Transaction verification: Network participants verify the transaction according to predefined rules.
3. Block creation: Verified transactions are collected into a block.
4. Block linking: The new block is connected to the previous block using a cryptographic hash.
5. Ledger update: The updated blockchain is shared across participating computers.
   <img width="950" height="602" alt="image" src="https://github.com/user-attachments/assets/61fe9154-35b3-467f-b0a3-d9288dae4942" />

3. Important Features of Blockchain
- Decentralization: Information is distributed across multiple computers instead of depending on a central authority.
- Transparency: Participants with appropriate access can view recorded transactions.
- Security: Cryptographic techniques help protect information from unauthorized changes.
- Immutability: Once transactions are confirmed and recorded, changing them is extremely difficult.
- Traceability: Transactions can be tracked and verified through the blockchain.
4. Types of Blockchain
There are four major types:
```
Type	                         Description
Public blockchain            	Anyone can participate, e.g., Bitcoin.
Private blockchain	          Controlled by a single organization.
Consortium blockchain	        Managed by a group of organizations.
Hybrid blockchain	            Combines public and private blockchain features.
```
5. Applications of Blockchain
   Blockchain technology is used in several fields:
- Banking and finance: Secure digital payments and cryptocurrency transactions.
- Healthcare: Maintaining secure medical records.
- Supply chain management: Tracking products from manufacturers to customers.
- Education: Verifying certificates and academic qualifications.
- Digital identity: Managing and verifying digital identities.
- Smart contracts: Automatically executing agreements when predefined conditions are met.
6. Advantages and Limitations
Advantages
- Reduces dependence on intermediaries.
- Improves transparency and accountability.
- Provides secure and traceable records.
- Reduces opportunities for unauthorized data modification.
Limitations
- Some blockchain networks consume significant energy.
- Transaction processing can be slow.
- Implementation and maintenance can be expensive.
- Data privacy and regulatory challenges remain.
7. Conclusion
Blockchain is an emerging technology that provides a secure, transparent, and decentralized method of storing and sharing information. Its main components include blocks, cryptographic hashing, distributed networks, and consensus mechanisms. Although it was initially popularized through cryptocurrencies, blockchain now has applications in banking, healthcare, education, supply chains, and many other industries. Despite challenges such as scalability, energy consumption, and privacy, it has significant potential to improve digital transactions and information management.


Meta AI:
     The Basics of Blockchain TechnologyBlockchain is one of the most important technologies of the last decade, but it is often misunderstood because people confuse it with Bitcoin. Bitcoin is just one application of blockchain. Blockchain itself is a new way of storing and sharing information.
    In simple words, blockchain is a digital ledger - a notebook of records - that is shared across many computers, and once something is written in it, it cannot be changed or deleted.    
    To understand blockchain, imagine a notebook shared by your entire class. Every student has the exact same copy. When someone writes a new transaction in the notebook, everyone updates their copy at the same time. If one student tries to secretly change an old page, everyone else will immediately notice because their copies will not match. This is the core idea of blockchain: trust through transparency and shared copies.   
    Blockchain is made of two main parts: blocks and chain.   
    A block is like one page of the notebook. Each block contains three things: data, a timestamp, and a unique code called a hash. The data can be anything - a money transfer, a medical record, a certificate, or a product delivery. The timestamp shows when the block was created. The hash is like a fingerprint for that block. Even a tiny change in the data will completely change the hash.   
    The chain is what makes blockchain secure. Each new block stores the hash of the previous block. This links all blocks together in a chain. If someone tries to change data in an old block, its hash will change. That will break the link to the next block, and then to the next, and so on. To cheat, a hacker would have to change every single block on every single computer at the same time, which is practically impossible.    
    Another key concept is decentralization. In a normal system, like a bank, one central authority keeps all the records. If that bank is hacked or makes a mistake, everything is at risk. In blockchain, there is no central authority. The ledger is copied across thousands of computers, called nodes, around the world. Before a new block is added, all these nodes must agree that it is valid. This process of agreement is called consensus. The most common consensus methods are Proof of Work and Proof of Stake.    
    Because of this design, blockchain has three major benefits. First, it is transparent. Anyone in the network can see the transactions. Second, it is secure and immutable. Records cannot be altered once added. Third, it removes middlemen. You do not need a bank, agent, or third party to verify a transaction because the network itself does the verification.   
    Blockchain is not just for cryptocurrency. In supply chains, it can track a product from factory to shop to prove it is genuine. In healthcare, it can store patient records safely and share them only with permission. In education, it can store degrees and certificates that cannot be faked. In voting, it can create a transparent and tamper-proof voting system. Governments are also exploring it for land records and identity management.    
    However, blockchain also has challenges. It can be slow compared to traditional databases, it uses a lot of energy in some systems, and it is still difficult to scale for millions of users. It is not a solution for every problem, but for problems where trust, transparency, and security matter, it is very powerful.    
    In short, blockchain is not magic. It is simply a clever combination of old ideas - shared records, cryptography, and network agreement - used in a new way to create trust without a central authority.

## Comparation between Chat gpt  and Meta AI
```
content                           Chat gpt                                  Meta AI
1.concept explanation              9/10                                      9/10
2.image creation                   9/10                                       -
3.speed                            8.5/10                                    9/10
4.Simplicity                       9/10                                      9/10
5.My experience                    10/10                                     8/10
```
## Result

thus the block chain summary was experienced by using different AI tools like chat gpt and Meta AI.
