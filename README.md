# Hyperledger Fabric Private Blockchain and Chaincodes

This repository contains the implementation of a private blockchain network and smart contract for a supply chain management solution, developed using Hyperledger Fabric.

## Files in This Repository

1. **`metadata.yml`**  
   Metadata configuration file for the blockchain setup, detailing the network configuration for the Hyperledger Fabric environment.

2. **`smartcontract.go`**  
   The smart contract implemented in Go, tailored for managing supply chain operations. This file handles the logic for secure and transparent transactions within the blockchain network.

## Key Features

- **Private Blockchain Network**: Set up using Hyperledger Fabric and Docker containers for peers and ordering nodes.
- **Smart Contract Implementation**: Designed and developed a supply chain-specific chaincode for recording transactions securely.
- **Transparent Operations**: Ensures data integrity and traceability for supply chain management.

## Technologies Used

- **Hyperledger Fabric**: For creating a private blockchain network.
- **Go (Golang)**: For developing the smart contract.
- **Docker**: For containerized network setup and deployment.

## Skills Demonstrated

- Chaincode Development (Go)  
- Docker-based Blockchain Networks  
- Private Blockchain Architecture  
- Supply Chain Management with Blockchain  

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/abhipatel35/Hyperledger-Fabric-Private-Blockchain.git
   ```
2. Review and modify `metadata.yml` as per your blockchain network requirements.
3. Deploy the smart contract (`smartcontract.go`) to your Hyperledger Fabric network.

## Future Scope

- Extend the smart contract functionality to include additional supply chain processes.  
- Integrate with a frontend application for better user interaction.

## License

This project is open-source and available under the [MIT License](LICENSE).
