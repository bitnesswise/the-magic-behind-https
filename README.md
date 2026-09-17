# The Magic Behind HTTPS

HTTPS is something we use every day, but the machinery behind that little padlock is surprisingly fascinating.

This repository contains a presentation that explains what really happens when you visit an `https://` URL — from the underlying cryptography and TLS handshake to certificates, Certificate Authorities, and the parts of an HTTP request that are protected.

## 👩‍💻 Who is this for?

The presentation is aimed at developers, students, and anyone curious about how the web works under the hood.

You don't need to be a cryptography expert to follow the slides. A basic understanding of HTTP and networking is helpful, but the presentation is designed to introduce the concepts progressively.

### A note for presenters

The slides are intended to provide a comprehensible storyline rather than a complete speaker script.

They contain speaker notes and explanations to help guide the presentation, but they are **not written in enough detail for someone unfamiliar with HTTPS to simply pick them up and present them without preparation**.

A solid understanding of HTTPS, TLS, and the underlying concepts is therefore recommended for presenters.

## 🧠 Topics covered

The presentation covers:

- A little bit of history
- What problems does HTTPS solve?
- SSL and TLS versions
- Symmetric and asymmetric encryption
- The TLS protocol and handshake
- Ciphers and cipher suites
- Which parts of an HTTP request are encrypted
- Certificates and the role they play
- Certificate Authorities (CAs) and Root CAs
- Certificate chains
- Different types of certificates
- Trusting a private CA
- SANs and wildcards
- Related concepts:
  - Server Name Indication (SNI)
  - HTTP Strict Transport Security (HSTS)
  - HTTP Public Key Pinning (HPKP)
  - OCSP and OCSP Stapling
  - CAA records
  - Some notable HTTPS/TLS vulnerabilities

The goal is to tell a visual, comprehensible story about **what really happens when you visit an `https://` URL** and how the different pieces work together to establish a secure connection.

## 🚀 Using the presentation

This project is open source, so you're welcome to:

- Use the presentation for meetups, workshops, classrooms, and internal tech talks.
- Modify the slides for your own audience.
- Reuse and improve the diagrams.
- Translate the presentation into another language.
- Use individual slides as teaching material.
- Fork the repository and build your own version.

If you use the presentation for a talk, I'd love to hear about it!

## 🖼️ Images & Assets

The presentation contains images and other visual assets sourced from websites that offer them for royalty-free use. Every effort has been made to respect the applicable licensing and attribution requirements.

Where attribution is required, the original creator and/or source is credited in the presentation.

If you are the copyright holder of an asset used in this presentation and believe it has been used incorrectly or without the required attribution, please open an issue so it can be reviewed and, if necessary, corrected or removed.

## 📜 License

Copyright © 2026 Martijn Korse / BitnessWise

This presentation is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to:

- Share the presentation
- Adapt and modify the material
- Use it for commercial purposes

When using or adapting the presentation, please:

- Keep the original source attributions intact.
- Credit the original author.
- Indicate if you have made changes.

You are **not required to publish or share your adaptations**.

See the [LICENSE](LICENSE) file for the full license terms.

> **Note:** Images and other third-party assets included in the presentation may be subject to separate licenses. See the [Images & Assets](#-images--assets) section for more information.
