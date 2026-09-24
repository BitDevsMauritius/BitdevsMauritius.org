+++
title = "Socratic Seminar #10"
date = 2026-09-27
template = "post.html"
[extra]

location = "ALCHE, Pamplemousses, Mauritius"
sponsor = "Btrust"
+++

## Location

The event will be hosted at **ALCHE**:

Alche Pamplemousses, Mauritius | [Map](https://maps.app.goo.gl/uHCXHnp2YeZ315Af7)

## Announcements

Join us for our Tenth Bitcoin [Socratic Seminar](http://127.0.0.1:1111/about)! A special thank you to our sponsor [Btrust](http://btrust.tech/).

This session will feature a deep dive into **Client-Side Ecash & Lightning SDK Architecture**, reviewing real-world code review discussions from the [`fedimint/fedimint-sdk` PR #401](https://github.com/fedimint/fedimint-sdk/pull/401).

## Reminders

- We prefer no photos and no videos during the event
- [Chatham House Rule](https://www.chathamhouse.org/about-us/chatham-house-rule)
- Leave the meeting space as clean as you found it
- Suggest topics for the next Socratic Seminar! [Where to find topics?](http://127.0.0.1:1111/about/find-topics)

# Topics

### Client-Side Ecash & Lightning SDK Architecture

**Date:** September 27, 2026

**Time:** 12:00 PM – 1:30 PM

**Duration:** 1 hour 30 minutes

**Speaker:** Sadiq

---

Meetup Agenda

**1. Welcome & Introduction — 5 minutes**

**Speaker:** Sadiq

- Welcome attendees
- Introduction to the session's objectives
- Introduction to Client-Side Ecash & Lightning SDK architecture
- Introduction to the `fedimint/fedimint-sdk` PR #401
- Brief recap of the Android Kotlin architecture from PR #388

**2. Swift/iOS SDK Architecture — 30 minutes**

**Speaker:** Sadiq

- Introduction to the Swift/iOS SDK
- Two-stage architecture used by the SDK
- Cross-compiling Rust libraries for Apple platforms
- Apple device, simulator, and host targets
- Packaging native libraries into `FedimintSdkFFI.xcframework`
- Swift bindings generated using `uniffi-bindgen`
- How metadata from `libfedimint_sdk.a` helps prevent API drift
- Swift Package Manager and `ios/Package.swift`
- Socratic discussion: What are the benefits and trade-offs of a zero-drift architecture?

**3. Async Operations & Multi-Federation Task Isolation — 25 minutes**

**Speaker:** Sadiq

- Asynchronous quoting
- Race conditions between concurrent quote requests
- Handling stale or out-of-order results
- Task cancellation and ownership
- Isolating tasks belonging to different federations
- Preventing cross-federation state interference
- Socratic discussion: Where should concurrency and task isolation be handled?

**4. Rust-to-Swift & iOS Platform Integration — 15 minutes**

**Speaker:** Sadiq

- Rust-to-Swift interoperability
- C++ runtime linkage
- RocksDB and aws-lc dependencies
- `SystemConfiguration`, `Security`, and `Network` frameworks
- UniFFI error naming workaround
- The `SdkError` typealias
- Challenges of packaging a Rust SDK for Apple platforms

**5. Demo Application, CI & Code Review Discussion — 10 minutes**

**Speaker:** Sadiq

- SwiftUI demo application
- Wallet lifecycle and balance streaming
- Ecash, Lightning, Onchain and Activity functionality
- XcodeGen project configuration
- CI workflow for XCFramework builds and simulator compilation
- What the PR's implementation tells us about SDK design
- Open discussion and questions

**6. Closing & Next Steps — 5 minutes**

**Speaker:** Sadiq

- Key takeaways
- Final questions
- Learning resources
- Suggestions for future Socratic Seminar topics
- Preview of the next BitDevs Mauritius meetup

---

- [Btrust Builders](https://www.btrust.tech/builders)
