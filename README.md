## Hello, I'm Madeline

I am a self-directed software engineer working to implement cryptographic standards that strengthen user privacy. Previously I worked on production systems in the healthcare and financial sectors.

### misaka-mls

**misaka-mls** is a from-scratch TypeScript implementation of [Messaging Layer Security (RFC 9420)](https://www.rfc-editor.org/rfc/rfc9420), a cryptographic protocol for end-to-end encrypted group communication that provides forward secrecy and post-compromise security. MLS uses binary tree structures to manage group membership efficiently, and is being adopted as the encryption standard for [RCS messaging](https://www.gsma.com/newsroom/press-release/gsma-publishes-new-rcs-universal-profile-with-end-to-end-encryption/) across Apple and Android devices, with industry backing from AWS, Cloudflare, Cisco, Meta, and others.

The library builds entirely on the native WebCrypto API, implements MLS's cryptographic dependency [HPKE (RFC 9180)](https://www.rfc-editor.org/rfc/rfc9180) from scratch, and carries zero third-party dependencies, providing compatibility with all major browsers out of the box. The library's development began in December, 2025, and the initial public release is planned for late 2026. 

The name references the [Misaka Network](https://toarumajutsunoindex.fandom.com/wiki/Misaka_Network) from the *Toaru Majutsu no Index* series, a distributed network whose members maintain shared state while joining, leaving, and coordinating through a common link. The parallel to MLS's group cryptographic structure is direct, and the series holds deep personal significance to me.
