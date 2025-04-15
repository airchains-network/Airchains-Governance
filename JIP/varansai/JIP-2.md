# Junction Improvement Proposal (JIP-2)

## Title: Integration of Rollup Module for Rollup Onboarding and Transaction Processing

## Proposal ID: 2

### Overview

This Junction Improvement Proposal (JIP) aims to introduce a new rollup module to the Airchains ecosystem. The primary objective of this module is to enable new rollups to join the Airchains ecosystem and provide the necessary transaction infrastructure for rollup operations within the network.

### Proposal Details

- **Proposal ID:** 2
- **Subspace:** rollup

### Description

The rollup module is designed to provide critical transaction functionality for rollups that wish to join and operate within the Airchains ecosystem. This module will enable rollups to perform essential operations such as state commitment, data availability publishing, and interoperability transactions. Currently, no dedicated infrastructure exists for rollups to execute these necessary transactions, creating a barrier for entry and operation within the ecosystem.

This change will provide the following benefits:

- **Ecosystem Expansion**: The rollup module will enable new rollups to easily join the Airchains ecosystem by providing standardized transaction interfaces and protocols.
- **Operational Infrastructure**: The module will offer essential transaction types required by rollups to function properly, including state root submission, fraud proof submission.
- **Standardized Integration**: By providing a unified module for rollup transactions, the network ensures consistent security and interoperability standards across all participating rollups.

### Rationale

The rationale behind this proposal is to address the growing need for dedicated infrastructure to support rollups within the Airchains ecosystem. As more rollup solutions seek to join Airchains, having a standardized module for essential rollup transactions becomes critical. This module fills a significant gap in the current infrastructure and removes barriers to entry for new rollups, thereby enhancing the network's value proposition and expanding its capabilities.

### Implementation Plan

The implementation of this proposal involves several key steps:

1. **Module Development**: Develop the rollup module with specific transaction types needed by rollups.
2. **Proposal Submission**: Submit the proposal to the governance module for consideration.
3. **Deposit Phase**: Validators and community members will deposit the required tokens to move the proposal to the voting stage.
4. **Voting Period**: Validators will vote on the proposal. A majority vote in favor is required for the proposal to pass.
5. **Module Integration**: If the proposal passes, the rollup module will be integrated into the network, and validators will need to update their nodes to support the new functionality.
6. **Documentation**: Create comprehensive documentation for rollup developers to integrate with the new module.

### Impact on Validators

Validators will need to:
- Update their node software to include the new rollup module
- Learn to validate and process the new transaction types specific to rollups
- Ensure their infrastructure can handle the additional transaction load from rollup operations
- Understand the security implications of the new rollup-specific transaction types

### Conclusion

The integration of a dedicated rollup module represents a critical infrastructure enhancement that will enable rollups to join and operate within the Airchains ecosystem. This module provides the essential transaction capabilities that rollups need to function properly, fostering ecosystem growth and interoperability. Validators and community members are encouraged to review the proposal, provide feedback, and participate in the voting process to ensure the successful implementation of this crucial infrastructure component.

For any questions or further information, please contact the [Airchains team](https://discord.gg/KUMpKF59mx).
