What is Cryptography:

Cryptography:

    • Cryptography is the practice and study of techniques for securing communications and data in the presence of adversaries.
    • Allows private data to which others should not have access, to be secured. Used to protect corporate secrets, secure classified information, protect personal information to protect against identity theft etc.
    • A message is converted into numeric form and applied to an encryption key and an encryption algorithm is used to produce cypher-text which is sent over the network to the recipient. The received message is applied to a decryption key and the cypher-text is used as a parameter for a decryption algorithm which yields the original message. If the message incurs an error, the recipient will receive the error.


Classification of Cryptography:

    • Symmetric Key Cryptography
            ▪ Classical Cryptography
                • Transposition Cypher
                • Substitution Cypher
            ▪ Modern Cryptography
                • Stream Cypher
                • Block Cypher
    • Asymmetric Key Cryptography


Symmetric Key Cryptography:

Algorithms which use the same key for encryption of plain-text and decryption of cypher-text. The keys represent shared secrets between two or more parties which can be used to maintain a private information link. Having access to the same key for both parties is one of main drawbacks of symmetric key cryptography compared to asymmetric key cryptography. Symmetric key cryptography is also known as secret key cryptography. The most popular symmetric key algorithm is the Data Encryption Standard(DES).


Transposition Cypher:

When a transposition cypher is used, the positions held by units of plain-text(either characters or groups of characters) are shifted according to a regular pattern. The cypher-text constitutes a permutation of the plain-text. A bijective function is used to encrypt the message,  and an inverse function is used to decrypt the cypher-text.

Substitution Cypher:

In the case of substitution cypher, bits of plain-text(pairs of letters, triplets of letters, mixtures of the above etc) are replaced with cypher-text according to a fixed pattern. Cypher-texts are transmitted as blocks of the same length without punctuation in order to disguise plain-text boundaries. 

Stream Cypher:

In a stream cypher the cryptographic key and cryptographic algorithm are applied to each binary digit in data stream one bit at a time. 

Block Cypher:

In a block cypher the cryptographic key and a deterministic algorithm are applied to each binary block in the data stream one block at a time. A common example of a block cypher is AES which encrypts 128 bit blocks using 128, 192 or 256 bit keys. Block cyphers are pseudo random permutation(PRP) families that operate on blocks of fixed sizes. PRP’s are functions that can not be differentiated from completely random functions.



Asymmetric Key Cryptography/ Public Key Cryptography:

    • Any cryptographic system which uses a pair of keys such that one is a public key and one is a private key is an asymmetric key cryptographic system. The public key can be disseminated widely while the private key is known only to the owner. 
    • Asymmetric key cryptography can be used for authentication and encryption.
            ▪ Authentication/Signing: The public key verifies that the holder of the paired private key sent the message.
            ▪ Encryption: Only the paired private key holder can decrypt messages encrypted with the public key.
    • Anyone can encrypt a message using the receivers public key but messages can only be decrypted using the receivers private key.
    • RSA is one of the most widely used public key cryptographic systems. It was the first publicly known practical public-key encryption system based on the Diffie-Hellman method.
