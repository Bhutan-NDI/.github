<h1 align="center">Bhutan National Digital Identity</h1>

<p align="center">
  <strong>The world's first national identity system built on Self-Sovereign Identity.</strong><br>
  <em>Empowering citizens, government, and the private sector to interact securely in a digital-first economy.</em>
</p>

<p align="center">
  <a href="https://bhutanndi.com"><img src="https://img.shields.io/badge/Website-bhutanndi.com-1a73e8?style=flat-square" alt="Website"></a>
  <img src="https://img.shields.io/badge/License-Apache_2.0-green?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Built_with-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Blockchain-Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white" alt="Ethereum">
  <img src="https://img.shields.io/badge/Standards-W3C_DIDs_|_DIDComm_|_SSI-6B4FBB?style=flat-square" alt="Standards">
</p>

---

### About

Bhutan NDI is the national digital identity program of the Kingdom of Bhutan -- pioneering a decentralized trust ecosystem inspired by the vision of His Majesty the King. It is the first country-scale deployment of Self-Sovereign Identity (SSI), giving citizens full control over their personal data and digital credentials.

The platform enables trusted interactions across government services, telecommunications, banking, and enterprise -- powering use cases like verified eKYC, passwordless authentication, digital signatures, and credential issuance, all anchored on Ethereum for long-term security and resilience.

---

### Core Pillars

<table>
<tr>
<td width="33%" valign="top">

**Self-Sovereignty**

Users have total control over their personal data and digital credentials. No centralized authority holds or manages identity on behalf of citizens.

</td>
<td width="33%" valign="top">

**Privacy by Design**

Zero-knowledge proofs and selective disclosure ensure users share only what is necessary -- on a strict need-to-know basis.

</td>
<td width="33%" valign="top">

**Decentralized Trust**

Distributed ledger architecture eliminates single points of failure. DIDs are anchored to Ethereum's globally distributed validator network.

</td>
</tr>
</table>

---

### Technical Architecture

| Layer | Technology |
|---|---|
| Blockchain | Ethereum -- DIDs anchored on a globally distributed validator network |
| Credentials | W3C Verifiable Credentials 2.0, Decentralized Identifiers (DIDs) |
| Protocols | DIDComm for secure peer-to-peer communication |
| Frameworks | [Credo-TS](https://github.com/openwallet-foundation/credo-ts), [Aries RFCs](https://identity.foundation/aries-rfcs/latest/) |
| DID Methods | `did:ethr` via [ethr-credo-module](https://github.com/Bhutan-NDI/ethr-credo-module), `did:polygon` via [polygon-did-resolver](https://github.com/Bhutan-NDI/polygon-did-resolver) |
| Mobile | React Native SDK for the citizen wallet app |

---

### Key Repositories

<table>
<tr>
<td width="50%" valign="top">

**Platform** | [`ngotag-platform`](https://github.com/Bhutan-NDI/ngotag-platform)

Core decentralized identity and verifiable credentials platform. Handles schemas, credential definitions, connections, and organizational workflows.

</td>
<td width="50%" valign="top">

**Agent Controller** | [`ngotag-agent-controller`](https://github.com/Bhutan-NDI/ngotag-agent-controller)

Backend orchestration service that manages identity agent interactions and business logic across the Bhutan NDI ecosystem.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Studio** | [`ngotag-studio`](https://github.com/Bhutan-NDI/ngotag-studio)

Modern web interface built with Astro, Flowbite, and Tailwind for configuring, managing, and visualizing identity workflows.

</td>
<td width="50%" valign="top">

**Mediator** | [`ngotag-mediator`](https://github.com/Bhutan-NDI/ngotag-mediator)

An Aries-compliant DIDComm mediator enabling secure, asynchronous communication between identity agents.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Mobile SDK** | [`mobile-sdk`](https://github.com/Bhutan-NDI/mobile-sdk)

React Native SDK powering the Bhutan NDI citizen wallet app -- available on [Google Play](https://play.google.com/store/apps/details?id=com.bhutanndi) and the [App Store](https://apps.apple.com/au/app/bhutan-ndi/id1645493166).

</td>
<td width="50%" valign="top">

**Ethereum Module** | [`ethr-credo-module`](https://github.com/Bhutan-NDI/ethr-credo-module)

Credo module for `did:ethr`, enabling Verifiable Credentials issuance and digital signing directly on Ethereum.

</td>
</tr>
</table>

---

### Collaborations

We work with organizations and institutions across the globe to advance the standards of digital identity:

W3C -- GLEIF -- Trust over IP (ToIP) -- DIACC -- ID4Africa -- Internet Identity Workshop -- KaiOS

---

### Connect With Us

<p align="center">
  <a href="https://github.com/orgs/Bhutan-NDI/repositories"><img src="https://img.shields.io/badge/Explore_Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"></a>
  <a href="https://bhutanndi.com"><img src="https://img.shields.io/badge/Visit_bhutanndi.com-1a73e8?style=for-the-badge" alt="Website"></a>
  <a href="https://bhutanndi.com/resources/Publications"><img src="https://img.shields.io/badge/Publications_&_Whitepapers-444?style=for-the-badge" alt="Publications"></a>
</p>

---

<p align="center"><sub>© 2026 Bhutan NDI. All rights reserved.</sub></p>
