# PSE Hacker House at ETHCC 2024: Innovate, Collaborate, Build

![ETHCC 2024](https://img.shields.io/badge/ETHCC-2024-blue)
![Hacker House](https://img.shields.io/badge/Hacker-House-green)
![PSE Projects](https://img.shields.io/badge/PSE-Projects-orange)

## Unlock the Potential of Collaboration

### 🚀 **Join Us for an Unforgettable Week of Learning, Building, and Networking**

This repository is for the PSE Hacker House at ETHCC 2024. It serves as the central hub for hackers to submit their projects, collaborate on code, and access resources related to the event. The Hacker House brings together developers from around the world to innovate, collaborate, and build projects focused on privacy, scaling, and Ethereum technologies. Throughout the week, participants will work on cutting-edge projects, attend workshops, and network with like-minded individuals.

**When & Where:**  
**📅** July 1st - 7th, 2024  
**📍** Brussels, Belgium (A Week Before ETHCC)

---

## **About the Project / Hacker House**

The PSE Hacker House is a week-long event designed to foster innovation and collaboration in the Ethereum community. Hosted by Privacy & Scaling Explorations (PSE), the Hacker House provides an immersive environment where developers can focus on building projects that leverage advanced cryptographic techniques and scalable solutions. Participants will have the opportunity to work alongside experienced mentors, gain insights into their tools, and showcase their work in a demo day at the end of the week.

### **Privacy & Scaling Explorations (PSE)**

PSE is a multidisciplinary team supported by the Ethereum Foundation. The team explores new use cases for zero-knowledge proofs and other cryptographic primitives, focusing on privacy and scalability solutions for the Ethereum ecosystem. PSE's projects aim to enhance the security, privacy, and usability of decentralized applications, contributing to the broader vision of a more secure and scalable blockchain infrastructure.

## **What to Expect?**

- **Attendees:** 10 hackers from all over the world, plus 5-7 PSE mentors on-site.
- **Program Structure:** Work in teams to hack and develop projects, with a demo day on the final day. Throughout the week, there will be various talks and workshops to support your development.
- **Potential Grants:** If mentors see potential in your work, we could offer grants to support your continued efforts.
- **Best Arrival Time:** 10am-12pm on July 1st.

## **How to Submit Your Project**

To submit your project please follow the steps below 

1. Fork this repository to your GitHub account
2. Create a new branch with your team name
3. Submit a PR. Your PR Should contain the following.
   

```
### Team name

**Contributors:**
- 

**Project Description:**
- 

**Technical Stack:**
- 

**Project Goals:**
- 

GitHub Link: 
Video Link:
```

Add this information in the `Hacker House Projects` Section

## **Hacker House Projects**
Add your project descriptions below. 

### Team 1

### Euclid - zk-Proofs for EU ID Cards

- [GitHub Repository](https://github.com/0xSileo/Euclid)
- [Video Presentation](https://drive.google.com/drive/folders/1ov9_Qo-a3KKf1uAqajLhDFO8ISatm0Ru)
- [Slides](https://github.com/0xSileo/Euclid/blob/main/euclid-zk-proofs-for-eu-id-cards.pdf)

**Contributors:**

- [0xSileo](https://github.com/0xSileo)
- [@pmuens](https://github.com/pmuens)

**Project Description:**

Zk-Snarkification of government signed data that can be read from EU ID cards.

**Technical Stack:**

- Circom
- Snark.js
- Mopro
- React.js
- Android SDK
- TypeScript
- Node.js

**Project Goals:**

The goal is for European citizens holding a new EU ID card to anonymously prove part of their identity through selective disclosure and zero-knowledge proofs.

The card's data is read via the NFC capability of modern mobile phones. Once read, the data is prepared to be fed into a Circom circuit to generate Zero Knowledge Proofs. Proof generation will happen on the user's mobile phone to ensure their privacy is protected. Throughout the whole process no trusted 3rd party is involved which could leak personal data.

### Team 3
### Marz: Multi-Factor Account Recovery levraging zk and ERC7579

**Contributors:**
- [Porco](https://github.com/porco-rosso-j)

**Project Description:**
- Social recovery module allows guardians to choose any supported recovery validators, such as ECDSA, AnonAadhaar, zkEmail, etc...

**Technical Stack:**
- ERC7579, Rhinestone ModuleKit, AnonAadhaar, Foundry for testing

**Project Goals:**
- This product aims to be widely integrated and used across modular smart account ecosystems, helping people easily recover their accounts relying on their friends and family who are not necessarily familiar with crypto in a privacy-preserving manner. 

GitHub Link: https://github.com/porco-rosso-j/aadhaar-recovery-7579
Video Link:

### Team 4

**Contributors:**

- [@alexander_bbs](https://github.com/alexand3rwilke)
- [@chiefbiiko](https://github.com/chiefbiiko)

**Project Description:**

🅰️🅰️🅰️® is a recovery module allowing to recover "sub" Safes through a "master" Safe without any traceable link - maintaining privacy.

The Safe module hosts a custom verifier which facilitates recovery action authorization through the "master" Safe in zero-knowledge.

At the core of AAAR lies a ZK circuit capable of verifying EIP-1186 proofs. This primitive enables an array of use cases, such as anonymous Safe signers and proofs of ownership.

We have been experimenting with various proof systems to come up with an implementation with acceptable memory consumption and speed so that they would be applicable in real-world use cases where computation must be near-real-time and client-side. We had experimented with SP1, during the hacker house we developed a MVP built with Halo2, still that implementation is not very performant, that's why we are currently building an alternative circuit implementation with Noir.

**Technical Stack:**

- Noir
- (Halo2, halo2-lib, axiom-eth)
- Rhinestone's ModuleKit
- ERC7579
- WASM

**Project Goals:**

- Provide a portable (i.e. WASM) implementation of an EIP-1186-verifying-zk-circuit prover alongside JS/TS and Rust adapters
- Publish an AAAR Safe module for master-sub recovery

GitHub Links:
- https://github.com/chiefbiiko/halo2-storage-proof
- https://github.com/chiefbiiko/noir-safe
- https://github.com/chiefbiiko/sp1-safe

Video Link: https://drive.google.com/file/d/1zglAs8JJG7lNzo-rvLk9hcD91QGYrMRb/view?usp=sharing

### Team 5

## **Participating PSE Teams and Technologies**

### **WAX (Wallet Account eXperiments)**
- **GitHub:** [WAX Repository](https://github.com/getwax)
- **Description:** WAX will be a set of production-ready smart account components providing advanced features that can be easily utilized by wallets, SDKs, and dApps.
- **Features:**
  - **Cheaper L2 transactions with BLS Signature aggregation**
  - **Modular smart contract components using battle-tested Safe modules**
  - **ERC 4337 compatible**
  - **zk email verification**
  - **passkeys verification**
  - **Multi-action transactions**
  - **Gasless transactions**
  - **Wallet upgradability**

### **Anon Aadhaar**
- **GitHub:** [Anon Aadhaar Repository](https://github.com/anon-aadhaar/anon-aadhaar)
- **Description:** Anon Aadhaar is a protocol for proving ownership of an Aadhaar identity (Indian Residence ID) in a privacy-preserving manner.
- **Features:**
  - **EVM-based smart contracts**
  - **Zero-Knowledge Proofs (ZKPs)**
  - **AnonAadhaar SDK for integration**

## **Useful Links and Resources**

- **WAX Documentation:** [WAX Documentation](https://github.com/getwax/docs)
- **Anon Aadhaar Documentation:** [Anon Aadhaar Documentation](https://github.com/anon-aadhaar/docs)
- **Ethereum Developer Resources:** [Ethereum Dev](https://ethereum.org/en/developers/)
- **PSE Website:** [PSE Website](https://pse.dev/en)


## **Contact Information**

For any questions or assistance, feel free to reach out to:
- **Phini:** [Telegram](https://t.me/)
- **Mo:** [Telegram](https://t.me/)

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Let's build something amazing together!


