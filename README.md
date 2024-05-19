#### Proposal Title:
zk-Lokomotive: Fully Secure and Trustless Multichain File Transfer System
![Logo](https://github.com/zk-Lokomotive/zk-lokomotive-MINA/assets/158029357/0a46fdde-4c8a-434f-a869-fd5740b63fac)

#### Proposal Overview

**Problem:** Traditional file transfer services lack sufficient privacy and security, especially for sensitive data. Centralized servers bring risks of data breaches and privacy violations.

**Solution:** zk-Lokomotive aims to create a secure and efficient file transfer system using ZK proofs, IPFS and Wormhole by combining Mina and Ethereum networks. This ensures file integrity and confidentiality, facilitates decentralized storage and enables cross-chain data transfer. Unlike traditional cryptographic solutions, the hashes sent to verify the integrity of the file or the authenticity of the origin are sent to a central server instead of a centralized server. By eliminating the "trust factor" completely, we aim to enable the companies or institutions we serve to transmit files in a confidential, secure and verifiable manner.

**Impact:** This project extends and enhances the Mina ecosystem by opening it to EVM-based users by enabling secure file transfers using zk-SNARKs, encouraging adoption, providing improved tools, and attracting more users and developers. Enables new applications for secure data sharing in blockchain ecosystems.

**Audience:** The target audience consists of researchers, developers and enterprises that need secure and verifiable file transfers.

### Architecture & Design

**Detailed Design/Architecture:**

**Mina-EVM File Transfer:**
- Cross-Chain Bridge:**
  - The transmitter encrypts the file with [zk-SNARK] o1js (merkle tree contract) and verifies it in the MINA network.
  - The files to be sent are tagged in IPFS in 256kb packets and the hash is transmitted over the MINA network.
  - After the files are verified on the network with zk, the receiver can pull the necessary files from IPFS.
- Wormhole Integration:**
  - Transfer tokenized files using Wormhole to facilitate cross-chain communication.
  - Verify the file using zk-SNARK proof when receiving it into the EVM network.
  - Retrieve the file from IPFS and verify its integrity using zk-SNARK proof.

**IPFS Integration:**
- **File Storage:** Use IPFS for decentralized file storage. Encrypt files before uploading and store the resulting hash on Mina.
- **Proof Verification:** Retrieve files from IPFS using hash and verify their integrity with the provided zk-SNARK proof.
**IPFS Integration:**
- **File Storage:** Use IPFS for decentralized file storage. Encrypt files before uploading and store the resulting hash on Mina.
- **Proof Verification:** Retrieve files from IPFS using hash and verify their integrity with the provided zk-SNARK proof.

### Vision

- The long-term vision includes adding support for more blockchain networks, enhancing privacy and security features, and developing a user-friendly interface for wider adoption.
- We also plan to organize Hackathons and CTFs in the MINA ecosystem to increase the customer growth rate of B2B sales.

#### Existing Work + DEMO

- [zk-lokomotive on Solana with WebRTC](https://github.com/virjilakrum/zk-lokomotive)
- **Demo Video (Solana):** https://github.com/zk-Lokomotive/zk-lokomotive-MINA/assets/158029357/95e8a391-d067-4903-8e1d-b4918e06444f

#### Production Timeline
- Within 6 months we expect to have completed the entire project.

### Budget & Milestones

**Deliverables:**
- Secure file transfer system between Mina and EVM networks.
- Wormhole contracts, the most optimized system for crosschain.
- IPFS integration for decentralized storage.
- User interface for easy file transfer.
- Detailed documentation and tutorials.

**Mid-Point Milestones:**
- Initial setup of Mina-Mina file transfer.
- After hashing files, verifying the hash on the MINA network.

**Project Timeline:** 
- 3M - 6M

**Budget Requested:** 
- 50,000 MINA (standart) 
- 100,000 MINA (advanced) [Mobile App]

**Budget Breakdown:**
- Development: 65,000 MINA
- Test: 5,000 MINA
- Documentation 5,000 MINA
- Infrastructure: 15,000 MINA
- Other & Unexpected: 10,000 MINA

**Auro Wallet Address:**
- B62qjP3DSqC3rxXY3VSWZivEWfvqCpnDyN1bFJxt55e5SyKHwN9ZuGA

### Team Info

**Proposer Github:**
- [Baturalp Güvenç](https://github.com/virjilakrum)

**Proposer Experience:**
- I have a resume with 3 years of professional experience, which includes Cohort-3 zkApps experience and dApps development experience, work on zk-lokomotive and other decentralized projects.

**Team Members:**
- Baturalp Güvenç: Founder | Dev (Github: [BaturalpGuvenc](https://github.com/virjilakrum))
- Ferit Yiğit Balaban: CTO | Dev (Github: [Yiğid Balaban](https://github.com/fybx))
- Additional team members will be added where necessary for development, testing and documentation.

**Achievements:**

- Renaissance Hackathon | Wormhole Track | Best Multichain Project First Prize 🏆🥇 
- Solana Hackathon | First Prize 🏆🥇
- Solana Demoday | Second Prize 🏆🥈
<img width="580" alt="prize1" src="https://github.com/zk-Lokomotive/zk-lokomotive-MINA/assets/158029357/d13bac88-8d2c-451f-974e-f01a4359d3bc">
<img width="580" alt="prize2" src="https://github.com/zk-Lokomotive/zk-lokomotive-MINA/assets/158029357/0ec75a70-c1d5-499c-a15f-83a585415b88">

### Risks & Mitigations

**Risks:**
- Technical Challenges:** Difficulties in implementing zk-SNARKs and cross-chain communication and scarcity of examples.
- Adoption:** Ensuring the solution is user-friendly and widely adopted.
  
<img width="826" alt="Ekran Resmi 2024-04-21 15 30 34" src="https://github.com/zk-Lokomotive/zk-lokomotive-MINA/assets/158029357/1be571dd-0f26-4a2f-8d61-069a82f03ec7">





