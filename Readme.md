# BlockSure - Blockchain Escrow Service

## About BlockSure

BlockSure is a decentralized escrow service built on the blockchain. It provides a secure and transparent way for two parties (sender and receiver) to complete transactions. With the help of smart contracts, BlockSure ensures that funds are held securely until predefined conditions are met, protecting both parties from fraud and disputes.

## Contract Details

- **Contract Address**: `0x423B1e68C91063a505C6aB4aD7736d6ED6a85aCC`
- **Network**: Flow Testnet

## Features

- **Set Participants**: Allows the sender and receiver to be set before the deposit is made.
- **Deposit Funds**: The sender deposits the agreed amount of funds to the contract.
- **Release Funds**: The receiver can release the funds once they fulfill the terms.
- **Refund Funds**: If the conditions are not met, the sender can refund the funds.
- **Reset**: Resets the contract for new participants after funds are released or refunded.

## Deployment

- **Contract Address**: [View on Explorer](https://evm-testnet.flowscan.io/address/0x423B1e68C91063a505C6aB4aD7736d6ED6a85aCC)
- **Coin Used**: FLOW

## How It Works

1. **Set Participants**: The sender and receiver's Ethereum addresses are set using the `setParticipants` function.
2. **Deposit**: The sender deposits an agreed amount of FLOW to the contract using the `deposit` function.
3. **Release/Refund**: Based on the agreement, the receiver can release the funds, or the sender can request a refund if the conditions are not met.
4. **Reset**: After the transaction has been completed (released or refunded), the contract can be reset for new participants.

## Screenshots
<img width="1437" height="698" alt="Screenshot 2024-12-14 at 4 08 39 PM" src="https://github.com/user-attachments/assets/c0294295-3a33-4212-9aa8-4bc1a088c12a" />

<img width="1440" height="668" alt="Screenshot 2024-12-14 at 4 08 55 PM" src="https://github.com/user-attachments/assets/07a79b55-8334-41be-9379-fe8271e08eeb" />

<img width="1440" height="699" alt="Screenshot 2024-12-14 at 4 09 10 PM" src="https://github.com/user-attachments/assets/b9acdb99-4f4a-41ce-9756-0b1015696d7c" />

<img width="1440" height="698" alt="Screenshot 2024-12-14 at 4 05 51 PM" src="https://github.com/user-attachments/assets/797ab558-ee25-47d2-aee5-582a196b95c5" />

<img width="1439" height="694" alt="Screenshot 2024-12-14 at 4 06 03 PM" src="https://github.com/user-attachments/assets/b9c2b88a-c9e7-4c41-a2eb-966fb8616add" />


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
