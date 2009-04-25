Describe how public-key cryptosystems work
==========================================

Ever since the dawn of hiding information, cryptography has been based on having a shared secret. This shared secret is used to both encrypt and decrypt information. This is called symmetric cryptography. The algorithms have become increasingly more complex and more secure, but until 1976 there was still a major problem: The security of the symmetric key algorithms depends on the secrecy of the shared secret – the key.

The breakthrough came when Whitfield Diffie and Martin Hellman released their seminal paper New Directions in Cryptography, which introduced Public-key cryptography. This layed the ground work for solving two of the fundamental problems in cryptography, key distribution and digital signatures. 

The term cryptosystem refers to the set of algorithms needed for key generation, encryption and decryption. In contrast to symmetric cryptosystems, public-key cryptosystems have distinct keys for encryption and decryption, a private key and a public key. It is computationally easy to compute a private key, and comptutationally easy to compute the public key from the private key, but it is computationally infeasible to derive the private key from the public key. Because of this the public key can be made available to everyone, while the private key is kept secret.

While symmetric algorithms are based on substitution and permutation, public-key algorithms are based on mathematical functions.[2] 

Diffie and Hellman defines a public-key cryptosystem as a pair of families 

