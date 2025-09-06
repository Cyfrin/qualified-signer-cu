# Qualified Signer

This houses the curriculum for both the **Qualified Signer Basics** and **Qualified Signer Advanced** courses.

This repository houses the external resources of our course, organized to facilitate easy access and contribution from our community.

Please refer to this for an in-depth explanation of the content:

-   [Website](https://updraft.cyfrin.io/) - Join Cyfrin Updraft and enjoy 50+ hours of smart contract development courses
-   [Twitter](https://twitter.com/cyfrinupdraft) - Stay updated with the latest course releases
-   [LinkedIn](https://www.linkedin.com/school/cyfrin-updraft/) - Add Updraft to your learning experiences
-   [Discord](http://discord.gg/cyfrin) - Join a community of 3000+ developers and auditors
-   [Newsletter](https://www.cyfrin.io/newsletter) - Weekly security research tips and resources to level up your career
-   [Codehawks](https://www.codehawks.com/) - Smart contracts auditing competitions to help securing web3

# Table of Contents

- [Qualified Signer](#qualified-signer)
- [Table of Contents](#table-of-contents)
- [Course Prerequisites](#course-prerequisites)
- [Course Outcomes](#course-outcomes)
- [Resources](#resources)
  - [Resources For This Course](#resources-for-this-course)
  - [Potential Wallets](#potential-wallets)
    - [Browser](#browser)
    - [Hardware](#hardware)
    - [Multi-Sig](#multi-sig)
- [Curriculum](#curriculum)
  - [Wallet types](#wallet-types)
    - [What to look for](#what-to-look-for)
  - [Wallet Safety](#wallet-safety)
  - [Transaction Signature Verification](#transaction-signature-verification)
  - [Cloud Wallet Infrastructure](#cloud-wallet-infrastructure)
  - [Verify Metamask transactions](#verify-metamask-transactions)
- [Thank you](#thank-you)
  - [Sponsors](#sponsors)
  - [Lead Lecturers / Code Builders](#lead-lecturers--code-builders)
  - [Special thanks](#special-thanks)
  - [Huge Extra Thank YOU](#huge-extra-thank-you)

# Course Prerequisites
* Blockchain basics (transactions, blocks, decentralization, etc)

# Course Outcomes
* Understand the potential dangers of different wallets
* Understand how to choose a wallet 
* Understand how to verify information about your wallet

# Resources

## Resources For This Course

Join [Cyfrin Updraft](https://updraft.cyfrin.io/) for the best learning experience!

- AI Frens
  - [Claude](https://claude.ai/)
  - [ChatGPT](https://chat.openai.com/)
  - [Phind](https://www.phind.com/)
  - [Gemini](https://gemini.google.com/)
  - [Other AI extensions](https://twitter.com/aisolopreneur/status/1654823630155464704?s=42&t=-pu_sCYtfrfPJU7OXfifrQ)
- Github Discussions 
    -   Ask questions and chat about the course here!
-   [Stack Exchange Ethereum](https://ethereum.stackexchange.com/)
    -   Great place for asking technical questions about Ethereum

## Potential Wallets 

*Note: We do not endorse any of the following wallets. All we have done is take a look to see if these wallets pass a small series of tests to make sure code that the developers release can be verified.*

[You can read Patrick's personal review here.](https://patrickalphac.medium.com/top-9-cryptocurrency-hardware-wallets-for-2025-security-researcher-review-9fcb16d771e0)

### Browser
- [MetaMask](https://metamask.io/)
- [Frame](https://frame.sh/) 
- [Rabby](https://github.com/RabbyHub/Rabby) 
- [Rainbow](https://rainbow.me/en-us/) 

### Hardware
- [Trezor](https://trezor.io/)
- [Ledger](https://www.ledger.com/)
- [GridPlus](https://gridplus.io/)

### Multi-Sig
- [Safe](https://safe.global/)


# Curriculum

*Q: Why are we giving guidelines and not strict recommendations?*

A: The wallet industry is constantly changing, and takes a LOT of work to assess how good different wallets are. Additionally, if you know what to look out for, that is more valuable than us giving you point-in-time recommendations.

## Wallet types
- [Article](https://www.cyfrin.io/blog/what-should-i-use-to-store-my-cryptocurrency-web3-wallet-guide)
  - Custodial Wallets 
  - "Hot" Wallets
      - Metamask 
      - Frame 
      - Rabby 
      - Rainbow 
    - [Where is my private key stored?](https://support.metamask.io/start/what-is-a-secret-recovery-phrase-and-how-to-keep-your-crypto-wallet-secure/)
    - [Where does metamask store my seed?](https://ethereum.stackexchange.com/questions/52658/where-does-metamask-store-the-wallet-seed-file-path) 
  - "Cold" Wallets 
      - Trezor 
      - GridPlus 
      - Ledger
    - [Hacked hardware wallet](https://www.youtube.com/watch?v=dT9y-KQbqi4)
    - [Wallet Scrutiny Thread](https://github.com/Cyfrin/evm-wallet-and-post-deployment-course)
  - Multi-sig (Yes - Set one up) 
      - 1 of 1, or x of y 
      - Case Study: [Vulcan](https://rekt.news/vulcan-forged-rekt/) 
      - [Future: Account Abstraction](https://ethereum.org/en/roadmap/account-abstraction/) 
### What to look for
*Tl;dr - the same things you'd look for in a protocol!*
- Open source 
- Active development 
- Audit history (Who did the review? What did they find? How good is the group?) 
- non-custodial 
- Do they have a security bounty program 
- If they ask you to wear your wallet around your neck, stay far away from them 
- [Interview with Wallet Scrutiny](https://www.youtube.com/watch?v=tgUYxNiiras)
## Wallet Safety 
  - Store the private key, not the secret phrase
      - Paper wallet
      - "brain" wallet
      - Encrypted file
      - [Case Study: LastPass](https://krebsonsecurity.com/2023/09/experts-fear-crooks-are-cracking-keys-stolen-in-lastpass-breach/)
  - [Case Study: Mixin](https://rekt.news/mixin-rekt/)
  - Rotate keys
  - [Physical security](https://github.com/jlopp/physical-bitcoin-attacks/blob/master/README.md) 
  - Social recovery 
  - [Wallets](https://wallet.page/wallet/summary/)
  - [How to multisig](https://howtomultisig.com/)
## Transaction Signature Verification
- [wise signer](https://wise-signer.cyfrin.io/)
- [safe hash](https://github.com/Cyfrin/safe-hash-rs)
- [swiss knife](https://calldata.swiss-knife.xyz/decoder)

## Cloud Wallet Infrastructure 
- [Case Study: Orbit](https://medium.com/orbit-chain/official-statement-regarding-orbit-bridge-exploit-551928f3dc52)
## Verify Metamask transactions 
  - Foundry's cast 
  - [Joinfire](https://app.joinfire.xyz/) 
  - Metamask snaps 

# Thank you

## Sponsors

- [Cyfrin](https://www.cyfrin.io/)
  - [Updraft](https://updraft.cyfrin.io/)
  - [CodeHawks](https://codehawks.com/)
  - [Solodit](https://solodit.xyz/)
- [Chainlink Labs](https://chainlinklabs.com/)
- [ZKsync/Matter Labs](https://zksync.io/)

## Lead Lecturers / Code Builders

- [Patrick Collins | Cyfrin](https://twitter.com/PatrickAlphaC)

## Special thanks

- [hansfriese](https://twitter.com/hansfriese) 
- [0Kage](https://twitter.com/hansfriese)
- [giovannidisiena.eth](https://twitter.com/giovannidisiena)
- [Dacian](https://twitter.com/DevDacian)
- [Alex Roan](https://twitter.com/alexroan)  

## Huge Extra Thank YOU

Thanks to everyone who is taking, participating in, and working on this course. These courses are passion project data dumps for everyone in the web3 ecosystem. 

Let's level up so we can keep web3 safer, and thank you again for taking this course!

[![Cyfrin Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/cyfrinaudits)
[![Cyfrin YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@CyfrinAudits)

<p align="right">(<a href="#table-of-contents">back to top</a>) ⬆️</p>
