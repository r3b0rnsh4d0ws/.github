<div align="center">

# R3B0RNSH4D0WS

## BREAK • BUILD • LEARN • REPEAT

**Cybersecurity collective • CTF operations • security research • open-source tooling**

[![Organization](https://img.shields.io/badge/GitHub-r3b0rnsh4d0ws-181717?style=for-the-badge&logo=github)](https://github.com/r3b0rnsh4d0ws)
[![CTF Archive](https://img.shields.io/badge/CTF%20Archive-105%20writeups-00ff88?style=for-the-badge&logo=flag)](https://github.com/r3b0rnsh4d0ws/ctf-archive)
[![Categories](https://img.shields.io/badge/10%20technical%20categories-8b5cf6?style=for-the-badge&logo=tag)](https://github.com/r3b0rnsh4d0ws/ctf-archive/tree/main/writeups)
[![Events](https://img.shields.io/badge/19%20CTF%20events-d29922?style=for-the-badge&logo=github)](https://github.com/r3b0rnsh4d0ws/ctf-archive/tree/main/writeups)

</div>

---

## Who we are

R3B0RNSH4D0WS is a cybersecurity collective focused on practical security work: solving CTF challenges, studying attack techniques, documenting reproducible paths, building original challenges, and turning experience into useful public knowledge.

We are interested in the full chain:

```text
observe → analyze → break down → exploit → verify → document → improve
```

The organization’s public identity is built around **quality over quantity**. A solve is not finished when a flag appears; it is finished when the reasoning is understandable, the path is reproducible, and the lesson can help someone else.

---

## What we do

<div align="center">

| CTF Operations | Security Research | Tooling & Automation | Challenge Design |
|:---:|:---:|:---:|:---:|
| Solve and document web, crypto, pwn, reverse, forensics, stego, OSINT, IoT/RF, and Web3 challenges. | Turn challenge behavior into reusable techniques, patterns, and lessons. | Build indexes, validators, generators, and research workflows. | Create fair, educational, multi-stage challenges with reproducible solutions. |

</div>

### Our practice areas

- **Cryptography:** RSA, AES, classical ciphers, LFSR/PRNG recovery, hashing, oracles, padding, lattice notes, and key-recovery patterns.
- **Web security:** injection, authentication, deserialization, request attacks, application logic, and multi-stage exploitation.
- **Pwn:** stack and heap corruption, format strings, ROP, binary constraints, and exploit reliability.
- **Reverse engineering:** binaries, VMs, anti-debugging, obfuscation, embedded systems, and protocol reconstruction.
- **Forensics:** PCAPs, memory and disk artifacts, logs, OSINT evidence, cross-artifact correlation, and satellite/RF data.
- **Steganography and misc:** image/audio hiding, encodings, esolangs, constraints, game logic, and unusual challenge formats.
- **Web3:** fund-flow tracing, token accounting, contract behavior, DeFi, RPC verification, and cross-chain investigations.
- **Challenge authoring:** original single-category, multi-stage, and cross-category challenge systems.

---

## The public archive

Our main public repository is the [R3B0RNSH4D0WS CTF Archive](https://github.com/r3b0rnsh4d0ws/ctf-archive).

<div align="center">

[![CTF Archive](https://img.shields.io/badge/ctf--archive-00ff88?style=for-the-badge&logo=flag)](https://github.com/r3b0rnsh4d0ws/ctf-archive)
[![Writeups](https://img.shields.io/badge/105%20writeups-8b5cf6?style=for-the-badge&logo=markdown)](https://github.com/r3b0rnsh4d0ws/ctf-archive/tree/main/writeups)
[![Self Authored](https://img.shields.io/badge/37%20self--authored%20files-d29922?style=for-the-badge&logo=github)](https://github.com/r3b0rnsh4d0ws/ctf-archive/tree/main/self-authored)

</div>

### Archive snapshot

| Signal | Current public value |
|---|---:|
| Selected writeups | **105** |
| CTF events represented | **19** |
| Technical categories | **10** |
| Self-authored files | **37** |
| Raw third-party challenge artifacts | **0** |
| Public repository size | Lightweight and linkable |

The archive is curated rather than a blind mirror. It emphasizes complete writeups, reproducible techniques, and public-safe material. Raw third-party challenge files, session cookies/tokens, rejected flags, incomplete work, duplicate trees, and oversized artifacts are excluded.

### Featured paths

- [Browse all writeups](https://github.com/r3b0rnsh4d0ws/ctf-archive/tree/main/writeups)
- [Crypto writeups](https://github.com/r3b0rnsh4d0ws/ctf-archive/blob/main/writeups/Crypto.md)
- [Web3 investigations](https://github.com/r3b0rnsh4d0ws/ctf-archive/blob/main/writeups/Web3.md)
- [Forensics writeups](https://github.com/r3b0rnsh4d0ws/ctf-archive/blob/main/writeups/Forensics.md)
- [Pwn writeups](https://github.com/r3b0rnsh4d0ws/ctf-archive/blob/main/writeups/Pwn.md)
- [Reverse writeups](https://github.com/r3b0rnsh4d0ws/ctf-archive/blob/main/writeups/Reverse.md)
- [Self-authored challenge lab](https://github.com/r3b0rnsh4d0ws/ctf-archive/tree/main/self-authored)


## Team & public collaborators

GitHub currently reports no public organization members, so we do not publish private membership data or assign roles that are not publicly verifiable.

The public repository currently exposes these collaborators:

| GitHub identity | Publicly visible relationship | What the repository shows |
|---|---|---|
| [@balukali](https://github.com/balukali) | Repository admin, maintainer, and push collaborator | Maintains the public archive and organization repository access. |
| [@worldofhackers-17](https://github.com/worldofhackers-17) | Repository collaborator | Listed among the collaborators on the public archive repository. |

This is intentionally a **public-collaborator view**, not a private roster. If team members want their names, biographies, roles, or social links displayed publicly, those details should be added deliberately to the organization profile rather than inferred.

---

## How we work

1. **Understand the artifact.** Identify format, protocol, constraints, and available evidence before choosing a tool.
2. **Search prior knowledge.** Reuse documented techniques and similar challenge patterns before reinventing an approach.
3. **Triage systematically.** Start with fast, reversible checks and preserve failed approaches when they teach something useful.
4. **Solve offline first.** Avoid spending platform attempts or exposing live infrastructure unnecessarily.
5. **Verify the result.** Check the flag format, rerun the exploit or decoder, and preserve a reproducible path.
6. **Write the lesson.** Document the key insight, commands, alternative approaches, and what should be remembered next time.
7. **Publish responsibly.** Keep private tokens, cookies, infrastructure, and redistribution-unclear material out of public repositories.

---

## Self-authored challenge design

We also create original challenges for CTF deployment and education.

The public archive currently includes material such as:

- `git_blunder` — recover a flag from commit history.
- `rabbit_hole_readme` — follow a documented transformation chain.
- `whitespace_secrets` — decode SPACE/TAB bit encoding.
- `recursive_base64` — decode a deep base64 chain.
- `tiny_text_svg` — inspect tiny SVG text and ROT13.
- `obfuscated_script` — reconstruct a flag at runtime.
- `needle_in_haystack` — filter a large log and decode the result.
- [Arachne Web](https://github.com/r3b0rnsh4d0ws/ctf-archive/tree/main/self-authored/web/arachne-web) — a multi-stage crypto, reverse, web, forensics, and pwn challenge.

Our challenge-design principles are simple: one intended path, fair inputs, meaningful anti-shortcuts, reproducible generation, and a clear separation between player files, private flags, and author solutions.

---

## Principles

- **Quality over quantity.**
- **Document the path, not just the flag.**
- **Preserve failed approaches when they are educational.**
- **Prefer reproducible evidence over unsupported claims.**
- **Respect redistribution rights.**
- **Keep secrets and live infrastructure private.**
- **Make the next learner’s path easier than our own.**

---

## Get involved

Want to contribute a verified writeup, research note, tool, or challenge?

1. Solve and verify the challenge.
2. Write a clear, reproducible writeup.
3. Include the key insight, commands, and lessons.
4. Check for private tokens, cookies, infrastructure, and redistribution issues.
5. Open a pull request against [`r3b0rnsh4d0ws/ctf-archive`](https://github.com/r3b0rnsh4d0ws/ctf-archive).

Incomplete work stays private until it is ready to teach someone else something.

---

<div align="center">

**BREAK • BUILD • LEARN • REPEAT**

*R3B0RNSH4D0WS — practical security work, shared openly.*

</div>
