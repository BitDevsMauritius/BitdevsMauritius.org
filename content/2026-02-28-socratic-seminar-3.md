+++
title = "Socratic Seminar #3"
date = 2026-02-28
template = "post.html"
[extra]
+++

## Location

The event will be hosted at **ALCHE**:

Alche Pamplemousses, Mauritius | [Map](https://maps.app.goo.gl/uHCXHnp2YeZ315Af7)

## Announcements

Join us for our Third Bitcoin [Socratic Seminar](/about)! A special thank you to our
sponsor [Btrust](http://btrust.tech/).

## Reminders

- We prefer no photos and no videos during the event
- [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule)
- Leave the meeting space as clean as you found it
- Suggest topics for the next Socratic Seminar! [Where to find topics?](/about/find-topics)

# Topics

### Cryptographic Security in Bitcoin

**Duration:** 1 Hour

---
Meetup Agenda

**1. Opening & Context (5 minutes)**

Objective: Establish why cryptography is the backbone of Bitcoin.

- Bitcoin as a system secured by mathematics rather than institutional trust
- The two core pillars: hashing and digital signatures
- How this session builds on the previous deep dive into transactions

**2. SHA-256 and Hashing in Bitcoin (25 minutes)**

Objective: Understand how hashing secures blocks and transactions.

- What a cryptographic hash function is
- Core properties: determinism, preimage resistance, collision resistance
- SHA-256 in Proof-of-Work
- Double SHA-256 in block headers
- Hashing in transaction IDs and Merkle trees

*Discussion + Walkthrough:*

- Examine the structure of a block header
- Identify which fields are hashed
- Explain why double hashing is used

**3. Elliptic Curve Cryptography (25 minutes)**

Objective: Understand ownership and signature validation.

- Public/private key cryptography fundamentals
- The secp256k1 curve used in Bitcoin
- Private key → Public key derivation
- Overview of ECDSA and Schnorr signatures
- How signatures authorize spending of UTXOs

*Conceptual Walkthrough:*

- From private key to public key
- From public key to address
- Where signature verification happens in validation

**4. Base58 and Address Encoding (5 minutes)**

Objective: Briefly introduce encoding and checksum design.

- Why Bitcoin does not use raw public keys directly
- Base58Check and checksum protection
- How encoding improves usability and error detection

---

- [Btrust Builders](https://www.btrust.tech/builders)
