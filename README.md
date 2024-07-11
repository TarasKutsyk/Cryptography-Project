# Cryptography-Project
Project for Combinatorics and Cryptography course I took in L'Aquila, 2024.

It consists of 3 tasks:

1. **gost_attack.txt**: This script implements the GOST block cipher encryption algorithm and demonstrates an attack known as Saarinen’s Attack. It includes functions for encrypting data using GOST and methods for recovering the S-box used in the encryption process through a known-plaintext attack, highlighting weaknesses in the cipher's structure.

2. **dlog.txt**: This script addresses solving the discrete logarithm problem (DLP) using Pollard’s Rho algorithm and the Pohlig-Hellman method. It includes functions for partitioning groups, performing steps in Floyd's cycle-finding algorithm, and combining these methods to solve DLP for large prime moduli, which is fundamental for cryptographic protocols like Diffie-Hellman.

3. **present.txt**: This script implements the PRESENT lightweight block cipher, designed for use in constrained environments such as RFID and sensor networks. It covers the complete encryption process, including the substitution layer (S-box), diffusion layer (permutation), and key scheduling, demonstrating how to securely encrypt data with minimal computational resources.
