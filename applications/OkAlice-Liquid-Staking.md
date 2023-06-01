# Liquid Staking - okAlice

- **Team Name:** okAlice LS
- **Payment Address:** 1xgDfXcNuB94dDcKmEG8rE9x9JVoqozCBnnitkN9nAe3Nyx


## Project Overview :page_facing_up:
### Overview

The goal of this project is to create an Ink!-based liquid staking DAO that implements the following functionalities:

- Users can participate in securing the network by staking their tokens.
- They can receive rewards for their staked tokens.
- They can receive a derivative token in exchange for the staked token, which can be used on other dapps or chains. This is why it is called liquid staking.
- Users can participate in the validator selection through an on-chain governance.


### Ink! Ecosystem Impact

In terms of the value that the Ink! ecosystem can derive from our Dapp, we plan to deploy it on Astar and anticipate that it will attract a significant number of new users to the Ink! ecosystem. Our aim is to make the Dapp user-friendly, eliminating the need for users to have technical knowledge about the back-end. We will make all of our code open-source and document our development journey through articles and videos. We hope that our Dapp can serve as an inspiration for future projects, alongside the existing smart contracts.


### Project Details

**⚠️ okAlice TODO ⚠️**

We expect the teams to already have a solid idea about the project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Data models / API specifications of the core functionality.
- An overview of the technology stack to be used.
- Documentation of core components, protocols, architecture, etc. to be deployed.
- PoC/MVP or other relevant prior work or research on the topic.
- Clarification on what your project is _not_ or will _not_ provide or implement. This is an opportunity for you to manage expectations and clarify any limitations that might not be obvious.
- Do you need an audit for the contacts? **YES/NO** (don't add it as part of Milestones! The auditor will be chosen among Auditor track participants)
- CATEGORY: Infrastructure OR Canary Dapp OR Technical Showcase

Things that shouldn't be part of the application:
- The (future) tokenomics of your project.
- Deployment and hosting costs, maintenance, or audits for non-infrastructure projects.
- Business-oriented activities such as marketing, business planning, events, or outreach.


## Team :busts_in_silhouette:

### Team members

- Wouter Godefroy - [GitHub](https://github.com/zabuxx)
- Michael Assaf - [GitHub](https://github.com/michaelassaf)
- Kenneth Verbeure - [GitHub](https://github.com/KennethVrb)
- Samuel Yi - [GitHub](https://github.com/s-yi)

### Contact

**⚠️ okAlice TODO ⚠️**

- **Contact Name:** Full name of the contact person in your team
- **Contact Email:** Contact email (e.g. john@duo.com)
- **Website:** Your website

### Legal Structure

**⚠️ okAlice TODO?? ⚠️**

- **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)
- **Registered Legal Entity:** Name of your registered legal entity, if available. (e.g. Duo Ltd.)

### Team's experience

Our first project built in the Polkadot ecosystem was 'Rooster Dao'. The project [won 3 prizes](https://devpost.com/software/rooster-dao?utm_campaign=winner_email&utm_content=submission_won&utm_medium=tweet&utm_source=twitter) during the Polkadot North-America hackathon in the summer of 2022:

- Winner of the community choice
- First place for the RMRK challenges
- Second place for Dao & Governance

Based on this project, we have been invited by the Astar team to adapt the 'Rooster Dao' contract to be usable on the Swanky node. In 2023, we participated in the Polkadot EU hackathon with a project called 'Pallet Rent', which won the first prize in the NFT category.


### Team Code Repos

- [https://github.com/ok-Alice](https://github.com/ok-Alice)
- [https://github.com/RoosterDao](https://github.com/RoosterDao)

### Team LinkedIn Profiles (if available)

- [LinkedIn - Kenneth Verbeure](https://www.linkedin.com/in/kenneth-verbeure-2b151571/)
- [LinkedIn - Michael Assaf](https://www.linkedin.com/in/michael-assaf/)
- [LinkedIn - Wouter Godefroy](https://www.linkedin.com/in/woutergodefroy/)
- [LinkedIn - Dagmar Duportail](https://www.linkedin.com/in/dagmar-duportail-50919150/)
- [LinkedIn - Samuel Yi](https://www.linkedin.com/in/samuel-yi-54796b141/)
- [LinkedIn - AM Prajwal](https://www.linkedin.com/in/am-prajwal/)


## Development Status :open_book:

**⚠️ okAlice TODO ⚠️**

- Links to your research diary, blog posts, articles, forum discussions, or open GitHub issues.
- References to conversations you might have had related to building this template.


## Development Roadmap :nut_and_bolt:

![image](https://github.com/ok-Alice/docs/assets/18469570/9d784a76-98f3-4bca-b019-d9358e93c3a7)

Components:

- **XCM CE:** XCM chain-extension for all contract interactions with the nomination pool on the relay chain.
- **issuer-staker:** Implements an asset with PSP22 interface for the derivative token. Manages staking operations on the nomination pool.
- **Validator Selector:** Optimized management of the nomination pool based on the validator statistics published by the *Oracle*.
- **Oracle:** Oracle providing validator statistics to the *Validator Selector* contract.

### Overview

- **Total Estimated Duration:** 5 months
- **Full-Time Equivalent (FTE):** 1.5
- **Total Costs:** 55

### Milestone 1: Validator Selector

- **Estimated Duration:** 2 months
- **FTE:** 1.5
- **Costs:** 22,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | GPLv3 |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will demonstrate how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. The guide will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) to set up the required development environment. This will include scripts to spin up local testnets with a minimal configuration for testing. |
| **1.** | Overview and Specifications | High-level architectural overview and specification of the contracts. |
| **2.** | Validator Selector Implementation | Implementation of the validator selection logic according to the provided specification. |
| **3.** | Tests | Comprehensive tests for the implemented validator selection logic. |
| **4.** | Documentation | Complete documentation of the validator selector, including inline documentation of the code and a tutorial. |
| **5.** | Audit | Smart contract audit report from a third-party auditor. |
| **6.** | Integration | Integration of the validator selector with the other components of the system. |
| **7.** | Deployment Scripts | Scripts to deploy the validator selector contract to a testnet or the mainnet. |
| **8.** | Tutorial | A tutorial demonstrating the use of the validator selector in a testnet environment. |

### Milestone 2: Derivative Token Issuer

- **Estimated Duration:** 1.5 months
- **FTE:** 1
- **Costs:** 16,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | GPLv3 |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will demonstrate how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. The guide will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) to set up the required development environment. This will include scripts to spin up local testnets with a minimal configuration for testing. |
| **1.** | Overview and Specifications | High-level architectural overview and specification of the contracts. |
| **2.** | Derivative Token Issuer Implementation | Implementation of the derivative token issuer according to the provided specification. |
| **3.** | Tests | Comprehensive tests for the implemented derivative token issuer. |
| **4.** | Documentation | Complete documentation of the derivative token issuer, including inline documentation of the code and a tutorial. |
| **5.** | Audit | Smart contract audit report from a third-party auditor. |
| **6.** | Integration | Integration of the derivative token issuer with the other components of the system. |
| **7.** | Deployment Scripts | Scripts to deploy the derivative token issuer contract to a testnet or the mainnet. |
| **8.** | Tutorial | A tutorial demonstrating the use of the derivative token issuer in a testnet environment. |

### Milestone 3: Oracle

- **Estimated Duration:** 1 month
- **FTE:** 1
- **Costs:** 11,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | GPLv3 |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will demonstrate how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. The guide will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) to set up the required development environment. This will include scripts to spin up local testnets with a minimal configuration for testing. |
| **1.** | Overview and Specifications | High-level architectural overview and specification of the contracts. |
| **2.** | Oracle Implementation | Implementation of the oracle according to the provided specification. |
| **3.** | Tests | Comprehensive tests for the implemented oracle. |
| **4.** | Documentation | Complete documentation of the oracle, including inline documentation of the code and a tutorial. |
| **5.** | Audit | Smart contract audit report from a third-party auditor. |
| **6.** | Integration | Integration of the oracle with the other components of the system. |
| **7.** | Deployment Scripts | Scripts to deploy the oracle contract to a testnet or the mainnet. |
| **8.** | Tutorial | A tutorial demonstrating the use of the oracle in a testnet environment. |

### Milestone 4: XCM CE

- **Estimated Duration:** 1 month
- **FTE:** 0.5
- **Costs:** 5,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | GPLv3 |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will demonstrate how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. The guide will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) to set up the required development environment. This will include scripts to spin up local testnets with a minimal configuration for testing. |
| **1.** | Overview and Specifications | High-level architectural overview and specification of the contracts. |
| **2.** | XCM CE Implementation | Implementation of the XCM chain-extension according to the provided specification. |
| **3.** | Tests | Comprehensive tests for the implemented XCM CE. |
| **4.** | Documentation | Complete documentation of the XCM CE, including inline documentation of the code and a tutorial. |
| **5.** | Audit | Smart contract audit report from a third-party auditor. |
| **6.** | Integration | Integration of the XCM CE with the other components of the system. |
| **7.** | Deployment Scripts | Scripts to deploy the XCM CE contract to a testnet or the mainnet. |
| **8.** | Tutorial | A tutorial demonstrating the use of the XCM CE in a testnet environment. |

### Milestone 5: Integration and Deployment

- **Estimated Duration:** 0.5 months
- **FTE:** 0.5
- **Costs:** 5,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **1.** | Integration Testing | Comprehensive integration tests for the entire system, including the validator selector, derivative token issuer, oracle, and XCM CE. |
| **2.** | Deployment Scripts | Scripts to deploy the entire system (all contracts) to a testnet or the mainnet. |
| **3.** | Documentation | Finalize and update the documentation of the entire system, including inline documentation of the code and tutorials. |
| **4.** | User Guide | A comprehensive user guide that provides step-by-step instructions on how to interact with the system, including staking, issuing derivative tokens, and using the XCM CE. |
| **5.** | Bug Fixes and Improvements | Address any reported bugs and make necessary improvements based on user feedback and internal testing. |
| **6.** | Security Audit | Conduct a security audit of the entire system to identify and address any potential vulnerabilities. |
| **7.** | Final Report | Prepare a final report summarizing the development process, challenges faced, and lessons learned. |
| **8.** | Demo | Prepare a demo showcasing the functionality of the system in a testnet environment. |

## Future Work

Beyond the initial development roadmap, we envision several areas for future work and potential enhancements:

- **Governance Mechanism:** Implement a governance mechanism for decentralized decision-making within the system.
- **Integration with Other Chains:** Explore the integration of the system with other blockchain networks to enable cross-chain interoperability.
- **Advanced Staking Features:** Enhance the staking functionality with additional features, such as dynamic staking rewards or delegation options.
- **Optimization and Scalability:** Continuously optimize and improve the performance and scalability of the system to handle increased usage and transaction volume.

## Conclusion

The proposed development roadmap outlines the key milestones and deliverables for the implementation of the Swanky Staking System. We are confident in our ability to deliver a robust and secure system that meets the specified requirements. Our team's expertise in smart contract development, blockchain technologies, and decentralized finance will ensure the successful completion of this project. We look forward to the opportunity to collaborate with the Swanky team and bring this innovative staking solution to life.
