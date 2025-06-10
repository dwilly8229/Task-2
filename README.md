 Task Overview:
Choose one platform from each category:
Public Blockchain: (e.g., Ethereum, Bitcoin, Solana)


Private Blockchain: (e.g., Hyperledger Fabric, R3 Corda in private mode)


Consortium Blockchain: (e.g., R3 Corda, Quorum, IBM Food Trust)



 Instructions:
Create a comparison table or markdown sheet with the following columns for each platform:

## Blockchain Platform Comparison

| Feature               | **Ethereum 2.0**            | **Hyperledger Fabric**        | **IBM Food Trust**                |
|-----------------------|-----------------------------|--------------------------------|-----------------------------------|
| **Type**              | Public                      | Private                        | Consortium                        |
| **Consensus**         | Proof of Stake              | Pluggable (Kafka, RAFT)        | Hyperledger Fabric (RAFT)         |
| **Permission Model**  | Open                        | Permissioned                   | Permissioned                      |
| **Speed / Throughput**| 30–100 TPS (up to 100k with sharding) | 1,000–20,000+ TPS              | 1,000–2,000 TPS                   |
| **Smart Contract Support** | Yes (Solidity)        | Yes (Go, Java, JavaScript)     | Yes (Go, Java, JavaScript)        |
| **Token Support**     | Native (ERC-20, ERC-721)    | Custom tokens via chaincode   | Not designed for token use        |
| **Typical Use Case**  | dApps, DeFi, NFTs           | Supply chain, banking, digital ID | Food supply chain tracking     |
| **Notable Feature**   | Decentralized + Layer 2 scaling | Modular & enterprise-focused | Real-time traceability            |




2. Write a Short Report (150–200 words):


Compare and contrast the technical capabilities of each.

Ans. The three blockchain platforms that I have chosen are Ethereum, Hyperledger Fabric, and IBM Food Trust.
 They serve different technical purposes based on their architecture and use case. 
 
 Ethereum is a decentralized, public blockchain optimized for transparency and programmability. It supports smart 
 contracts via Solidity and hosts a vibrant ecosystem of dApps, NFTs, and DeFi protocols. However, its base layer has limited throughput
 30 TPS, mitigated by Layer 2 scaling solutions.

 Hyperledger Fabric is a private, permissioned blockchain framework designed for enterprise use. 
 It enables modular consensus (Kafka), supports chaincode in multiple languages, and achieves a high throughput of over 1000 TPS. 
 Its privacy-focused architecture enables data to be shared selectively among participants.

 IBM Food Trust, built on Hyperledger Fabric, extends these capabilities to a consortium setting. 
 It is tailored for the food supply chain, offering real-time traceability, data immutability, and secure collaboration among known,
 verified participants.

Which platform would you choose for:
Ethereum 2.0

-A decentralized app?
Ethereum is a decentralized, public blockchain optimized for transparency and programmability. It supports smart 
 contracts via Solidity and hosts a vibrant ecosystem of dApps, NFTs, and DeFi protocols. However, its base layer has limited throughput
 30 TPS, mitigated by Layer 2 scaling solutions. Its decentralized architecture ensures trustless execution.

-A supply chain network among known partners?
IBM Food Trust, built on Hyperledger Fabric, is a consortium blockchain purpose-built for supply chain traceability. It supports real-time tracking, immutability, 
and selective data sharing. With high throughput and access control, it is suitable for the industry, which is known and trusted.

-An inter-bank financial application?
Hyperledger Fabric’s permissioned and modular design is ideal for financial applications needing privacy, high throughput, and regulatory compliance. 
Its pluggable consensus and support for smart contracts in multiple languages allow for complex, controlled logic. Fabric enables confidential transactions 
and identity management, making it suitable for banking consortia, settlement systems, or cross-border financial processes.

Justify your choice based on technical points
