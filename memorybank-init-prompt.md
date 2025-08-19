initialize memory bank for YaCoin project with the following details:
projectbrief.md:
- Project name: YaCoin
- Goal: Create a minimal but complete cryptocurrency implementation in TypeScript
- Core requirements: Fully decentralized, autonomous, with basic security features that prevent double-spending
- Coding style: Functional programming with TypeScript - no classes or interfaces, only plain objects, types, and arrow functions
- Timeline: Focused on minimal implementation that takes the least possible time while being fully functional

productContext.md:
- Purpose: Educational cryptocurrency implementation to understand Bitcoin's core concepts
- Target users: Developers learning about blockchain technology
- Problem statement: Need for a simplified but complete cryptocurrency implementation that demonstrates core blockchain principles
- User experience: Command-line interface for node operations, mining, and transactions


systemPatterns.md:
- Architecture: Modular design with 5 core components
- Component 1: Core Blockchain Module - blocks, chain validation, PoW algorithm
- Component 2: Transaction System - UTXO model, transaction validation, mempool
- Component 3: Wallet Module - key management, addresses, transaction signing
- Component 4: P2P Network Layer - node discovery, blockchain sync, transaction broadcasting
- Component 5: CLI/API Interface - user commands and control
- Implementation order: Start with core blockchain, then transactions, wallet, P2P, and finally CLI

techContext.md:
- Primary language: TypeScript
- Runtime: Node.js
- Key libraries: Node's crypto module for cryptography
- Storage: LevelDB or similar for blockchain data
- Network: WebSockets for P2P communication
- Building: ESBuild
- Development approach: Test-driven development with incremental implementation

activeContext.md:
- Current focus: Planning phase, defining architecture and component interfaces
- Recent decisions: Chose UTXO model over account model, functional programming style
- Open questions: Specific P2P protocol details, storage implementation
- Next steps: Begin implementation of Core Blockchain Module

progress.md:
- Current status: Planning phase complete, ready to begin implementation
- Completed: High-level architecture design
- In progress: Core blockchain module design
- Pending: All implementation work
- Known issues: None yet
```