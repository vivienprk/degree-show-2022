---

layout: project
studentName: "Mohammed Tokaria"
supervisorName: "Dr Brian Pluss"
projectTitle: "Securing Students Data using Homomorphic Encryption"
projectImage: "adminhome.png"

---

<hr>

## Project Description
The primary goal of the project is to determine the significance of Homomorphic Encryption(HE) and why it is more beneficial to an organisation compared to a traditional encryption. One of Homomorphic Encryption's (HE) capabilities is secure data monetization, which allows data to be processed in a privacy-preserving manner without the risk of exposure. This also allows existing sensitive or regulated data to be used in ways that were previously deemed too risky to pursue. **For example,** if encryption acts as a vault to protect sensitive data, traditional practice calls for that data to be removed from the vault each time it needs to be used or processed. Because of this vulnerability, both the data and the operation are at risk. Whereas, HE allows these actions to take place within the vault, ensuring that the interaction and its outcomes are safe. Most of the homomorphic encryption schemes is based on Ring-Learning With Errors (RLWE) problem which is a complex mathematical problem related to high dimensional lattices. These RLWE problem is currently considered to be secured even against quantum computers.


## Project Findings
This section should talk about the main findings of my project.

### Ring Learning With Errors (RLWE) 
A computational problem in post-quantum cryptography that serves as the foundation for new cryptographic algorithms such as New-hope, which are designed to protect against cryptanalysis by quantum computers while also providing the foundation for homomorphic encryption. Public-key cryptography is based on the construction of mathematical problems that are thought to be difficult to solve in the absence of additional information but are simple to solve if some information used in the problem construction is known. Some current cryptographic problems of this type are vulnerable to attack if sufficiently large quantum computers can ever be built, so resistant problems are sought.

### Traditional Hashing
Hashing is a cryptographic method that converts any type of data into a unique string of text. Any piece of data, regardless of size or type, can be hashed. In traditional hashing, regardless of the size, type, or length of the data, the hash produced by any data is always the same length. A hash is intended to be a one-way function: you can feed data into a hashing algorithm and get a unique string, but if you come across a new hash, you won’t be able to decipher the input data it represents. A distinct piece of data will always yield the same hash.

### Encryption Algorithms
Encryption algorithms are designed to destroy any connections between plaintext and ciphertext. A good encryption algorithm generates ciphertext that is identical to a random number. The only way to determine which plaintext corresponds to which ciphertext is to decrypt it with the appropriate key. 

The ability to perform mathematical operations on encrypted data necessitates the existence of a connection between plaintexts and ciphertexts. It must be possible to add or multiply two ciphertexts and have the result be the same as performing the same operation on the two plaintexts and then encrypting the result. At the same time, this relationship must be implemented in such a way that it is hidden from an observer. If observing mathematical operations on ciphertexts reveals information about the corresponding plaintexts, the encryption is broken. 

It is extremely difficult to achieve these mutual goals of strong encryption and the ability to perform mathematical operations on ciphertexts and get the correct answer. Homomorphic encryption algorithms have achieved this goal.

### Homomorphic Encryption (HE)
Homomorphic encryption is significant because it enables calculations to be performed on encrypted data. This means that data processing can be outsourced to a third party without relying on the third party to properly secure the data. The original data cannot be accessed without the correct decryption key. This ability to process encrypted data has the potential to solve many major business challenges faced by companies across all industries.

### Types of Homomorphic Encryption
The goal of homomorphic encryption is to develop an encryption algorithm that allows for an infinite number of encrypted data additions or multiplications. The result should be the ciphertext that would be produced if the same operations were performed on the corresponding plaintexts and the result was encrypted at the end of the process. Below are three types of homomorphic algorithm.

#### Partially Homomorphic Encryption
Partially homomorphic encryption algorithms allow a given operation to be repeated indefinitely. A specific algorithm, for example, may be additively homomorphic, which means that adding two ciphertexts together produces the same result as encrypting the sum of the two plaintexts.

#### Somewhat homomorphic encryption
Somewhat homomorphic encryption is the next step up from partially homomorphic encryption. A somewhat homomorphic encryption algorithm allows a finite number of any operation rather than an infinite number of a specific operation.

#### Fully Homomorphic Encryption
Fully homomorphic encryption is the holy grail of homomorphic encryption. A fully homomorphic encryption algorithm allows an infinite number of ciphertext additions or multiplications while still producing valid result


![MLaaS is one of the most exciting applications of Homomorphic Encryption](/project_images/MLaaS.png)
[^Image source] https://blog.openmined.org/what-is-homomorphic-encryption/
