# Cryptography I

## Introduction Week 1

### What is cryptography
#### Crypto Core
- Secret key establishment (shared key)

- Secure Communication
  - confidentiality and integrity

#### Other Crypto uses
- Digital signatures
  - a function of content being signed
- Anonymous communication
  - mix net
     - sequence of proxies, anonyminity between participants and proxies
  - Ex. Anonymous Digital cash
    - anonymous but also no double spending
  - Ex. Elections
  - Ex. Private Auctions
- Any secure multi-party system that relies on a trusted authority can remain anonymous and secure without the trusted authority. A general and surprising result
- Crypto Magic
  - Privately outsourced computation
    - send encrypted data, perform comutations ON encrypted data and send back encrypted results. Agent doing computations does not have access to the actual data, just the encypted data.
    - This is a new result, costly and good for simple computations
  - Zero Knowledge
    - `N = p*q` where p and q are large primes.
    - `a` has `p` nd `q` and sends `n` to `b` and can prove that `a` has the factors of `N` without divulging `p` or `q`.
    - This is a general result and can work for many puzzles etc.
#### Rigorous Science
- Follow 3 steps for each crypto problem
1. Precisely specify threat model
  - examples: Digital Signatures: unforgeable
2. Propose a construction
  - Example: factoring massive numbers
3. Prove that breaking constuction under threat mode will solve an underlying hard problem
  - Example: then attacker would be able to factor massive numbers, which is hard, and therefore validates security


