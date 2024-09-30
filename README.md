# ReskCrypt

ReskCrypt is a robust, secure, and efficient library for end-to-end encryption of conversations with Language Learning Models (LLMs). It provides a comprehensive solution for secure data storage, transmission, and inference in both local and cloud environments.

## Features

- End-to-end encryption for LLM conversations
- Secure local and cloud storage options
- Efficient hybrid encryption using RSA and Fernet
- Secure key management system
- Performance indicators for conversations
- Cloud-based SaaS offering with on-premises options

## Security

ReskCrypt employs a hybrid encryption scheme:

1. RSA for asymmetric encryption of key exchange
2. Fernet for symmetric encryption of conversation data

This approach ensures:

- Secure key distribution
- Efficient encryption of large datasets
- Protection against various cryptographic attacks

Key management:
- Private keys are securely stored and never leave the server
- Public keys are distributed to clients for secure communication
- Fernet keys are generated per-conversation and securely encrypted

## Cloud Service

ReskCrypt is available as a Software-as-a-Service (SaaS) solution, hosted on secure VPS infrastructure. This allows for easy integration and scalability while maintaining high security standards.

## Open Source

While the core ReskCrypt library is proprietary to protect our technology, we offer an open-source version with limited features. This allows for community involvement and transparency while safeguarding our innovations.

## License

ReskCrypt is protected under a proprietary license. For inquiries about licensing for commercial use, please contact our sales team.

## Contributing

We welcome contributions to our open-source components. Please see our CONTRIBUTING.md file for guidelines.


## Disclaimer

ReskCrypt is designed to provide strong security for LLM conversations. However, no system is 100% secure. Always follow best practices for data protection and comply with relevant data protection regulations.
