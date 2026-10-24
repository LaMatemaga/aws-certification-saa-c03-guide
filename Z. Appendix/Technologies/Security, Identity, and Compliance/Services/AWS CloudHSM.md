---
group:
  - technology
---
AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to generate and use your own encryption keys on the AWS Cloud. It offers a high level of security by providing dedicated, FIPS 140-2 Level 3 validated hardware security modules for your sensitive cryptographic operations.

## Key Features

- **Dedicated hardware**: Single-tenant HSM instances for exclusive cryptographic operations.
- **FIPS 140-2 Level 3 validation**: Meets strict government and regulatory compliance requirements.
- **Customer-managed keys**: You have exclusive control over your encryption keys.
- **High availability and durability**: Deploy multiple HSMs across availability zones.
- **Standard cryptographic interfaces**: Support for PKCS#11, Java JCE, and Microsoft CryptoNG (CNG) libraries.
- **Key types and algorithms**: Support for symmetric keys (AES, DES, 3DES), asymmetric key pairs (RSA, ECC), and cryptographic hash functions.
- **Key management operations**: Secure key generation, storage, backup, and deletion.
- **Tamper-resistant hardware**: Physical security mechanisms to protect key material.
- **Secure key synchronization**: Automatic key synchronization across multiple HSMs in a cluster.

## Cryptographic Operations

- Key generation and management
- Data encryption and decryption
- Digital signing and signature verification
- Cryptographic hashing
- Message authentication codes
- Key wrapping and unwrapping
- Public key cryptography

## Common Use Cases

- **Database encryption**: Protect sensitive database fields or entire databases.
- **Digital rights management (DRM)**: Secure content keys for protected media.
- **Public key infrastructure (PKI)**: Support certificate authorities and SSL/TLS certificates.
- **Transaction processing**: Secure financial transactions and payments.
- **SSL/TLS acceleration**: Offload SSL/TLS processing.
- **Code signing**: Secure the software development and distribution process.
- **Document signing**: Add cryptographic signatures to documents.
- **Regulatory compliance**: Meet compliance requirements for key management (PCI DSS, HIPAA, GDPR).

## Integration with AWS Services

- [[Amazon S3]] SSE with customer keys
- [[Amazon Elastic Block Store (Amazon EBS)]] custom key encryption
- [[Amazon Redshift]] encryption
- [[AWS Key Management Service (AWS KMS)]] custom key store

## Benefits

- **Security**: FIPS 140-2 Level 3 validated hardware with tamper-evident mechanisms.
- **Control**: Full control over the lifecycle of your encryption keys.
- **Compliance**: Meet regulatory requirements for cryptographic operations.
- **Scalability**: Add HSMs to your cluster as your needs grow.
- **Availability**: Deploy HSMs across multiple availability zones for high availability.
- **Performance**: Offload cryptographic operations to dedicated hardware.

## Pricing

AWS CloudHSM pricing is based on:

- Hourly usage fees for each HSM instance
- No upfront costs or long-term commitments
- Standard AWS data transfer rates apply

You can launch multiple HSMs to create a cluster for high availability and increased performance.