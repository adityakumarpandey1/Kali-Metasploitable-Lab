# Cryptography Basics (Task 4)

## Encryption Types

* **Symmetric Encryption (e.g., AES):** Uses a **single secret key** for both encryption and decryption. Very fast.
* **Asymmetric Encryption (e.g., RSA):** Uses a **pair of keys** (Public Key for encryption, Private Key for decryption). Slower, but solves the key-exchange problem.

## Hashing

* **Purpose:** Integrity verification. It's a **one-way function** that creates a fixed-size digest (hash) from input data.
* **Algorithms:**
    * **MD5:** Older, deprecated due to collision vulnerabilities.
    * **SHA256:** Stronger, commonly used for digital signatures and secure password storage.

## Digital Certificates and SSL/TLS

* **Digital Certificate:** Issued by a Certificate Authority (CA) to bind an entity's identity to its **Public Key**. Essential for trust in HTTPS.
* **SSL/TLS:** The protocol suite that uses certificates and asymmetric keys to establish a secure, encrypted tunnel (HTTPS).

## OpenSSL Hands-on Practice (Symmetric Encryption)

Demonstration in Kali terminal:

1.  **Encrypt:** `openssl enc -aes-256-cbc -salt -in original.txt -out encrypted.enc`
2.  **Decrypt:** `openssl enc -d -aes-256-cbc -in encrypted.enc -out decrypted.txt`
