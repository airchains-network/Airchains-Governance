
# Junction Improvement Proposal (JIP-1)

## Title: Increase Slashing Signed Blocks Window from 100 to 10000

## Proposal ID: 1

### Overview

This Junction Improvement Proposal (JIP) aims to increase the SignedBlocksWindow parameter from 100 to 10000 in the Varanasi testnet. The primary objective of this change is to enhance the network's stability and security by expanding the window for monitoring validator activity.

### Proposal Details

- Proposal ID: 1
- Subspace: slashing
- Key: SignedBlocksWindow
- Current Value: 100
- New Value: 10000

### Description

The SignedBlocksWindow parameter defines the number of blocks the network considers when checking for validator signing behavior. Currently, this window is set to 100 blocks, which limits the network's ability to monitor and enforce validator performance effectively. By increasing this parameter to 10000 blocks, the network can achieve more comprehensive and robust monitoring of validator activities.

This increase will provide the following benefits:

- **Improved Security**: With a larger window, the network can detect malicious behavior more accurately and enforce slashing penalties more effectively. This change will discourage validators from attempting short-term exploits and enhance the overall security of the network.
- **Enhanced Stability**: A larger SignedBlocksWindow ensures that temporary disruptions or anomalies in validator behavior do not disproportionately impact their status. This leads to a more stable and resilient network.
- **Long-Term Monitoring**: By extending the monitoring period, the network can better assess validator performance over a longer timeframe, contributing to the health and integrity of the network.

### Rationale

The rationale behind this proposal is to strengthen the network's defense mechanisms against validator misbehavior and to ensure long-term stability. The current window of 100 blocks is relatively short and may not provide a sufficient timeframe to detect and respond to malicious actions. Increasing the window to 10000 blocks offers a more extensive and detailed view of validator activities, allowing for more accurate and effective enforcement of network rules.

### Implementation Plan

The implementation of this proposal involves updating the SignedBlocksWindow parameter in the slashing module configuration. The steps include:

1. **Proposal Submission**: The proposal will be formally submitted to the governance module for consideration.
2. **Deposit Phase**: Validators and community members will deposit the required tokens to move the proposal to the voting stage.
3. **Voting Period**: Validators will vote on the proposal. A majority vote in favor is required for the proposal to pass.
4. **Parameter Update**: If the proposal passes, the SignedBlocksWindow parameter will be updated from 100 to 10000 blocks.

### Impact on Validators

Validators play a critical role in maintaining the security and stability of the Varanasi testnet. This proposal will require validators to adapt to a new monitoring window, ensuring they maintain consistent performance over a more extended period. It is crucial for validators to understand the implications of this change and participate actively in the governance process to ensure their interests and the network's health are aligned.

### Conclusion

Increasing the SignedBlocksWindow from 100 to 10000 is a significant improvement that will enhance the Varanasi testnet's security and stability. Validators and community members are encouraged to review the proposal, provide feedback, and participate in the voting process to ensure the continued success and robustness of the network.

For any questions or further information, please contact the [Airchains team](https://discord.gg/KUMpKF59mx).