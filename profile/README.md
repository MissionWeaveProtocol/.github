**English** | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [Español](README.es.md) | [Français](README.fr.md) | [Deutsch](README.de.md)

# MissionWeaveProtocol

<p align="center">
  <img src="assets/missionweaveprotocol-icon.svg" width="160" alt="MissionWeaveProtocol icon">
</p>

<p align="center">
  <strong><a href="https://missionweaveprotocol.github.io/">Official website and documentation</a></strong>
</p>

MissionWeaveProtocol is a group-oriented protocol for coordinated, accountable collaboration among AI
agents inside an organization.

Agents can join many Mission Groups, communicate full-duplex inside each Group, propose and accept
explicit WorkItems into per-Group queues, and coordinate delivery through evidence-based review and
human approval.

## Repositories

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) — normative
  specification, glossary, JSON Schemas, conformance vectors, and brand assets.
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — official Python
  reference implementation with the full Agent runtime, Group gateway, Worker Scheduler,
  conformance runner, storage adapters, and executable POC.
- [go-sdk](https://github.com/missionweaveprotocol/go-sdk) — official Go protocol SDK with
  protocol bindings and schema-and-vector conformance.
- [typescript-sdk](https://github.com/missionweaveprotocol/typescript-sdk) — official TypeScript
  protocol SDK with protocol bindings and schema-and-vector conformance.
- [java-sdk](https://github.com/missionweaveprotocol/java-sdk) — official Java protocol SDK with
  protocol bindings and schema-and-vector conformance.
- [rust-sdk](https://github.com/missionweaveprotocol/rust-sdk) — official Rust protocol SDK with
  protocol bindings and schema-and-vector conformance.
- [cpp-sdk](https://github.com/missionweaveprotocol/cpp-sdk) — official C++ protocol SDK with
  protocol bindings and schema-and-vector conformance.
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — official website and documentation repository, published at the
  [MissionWeaveProtocol website](https://missionweaveprotocol.github.io/).

The protocol and its implementations are versioned independently. Implementations pin an explicit
protocol release or commit and publish their compatibility range.

Python is the full reference runtime. The Go, TypeScript, Java, Rust, and C++ SDKs currently focus
on protocol bindings and schema-and-vector conformance; they do not claim full behavioral runtime
conformance.

## Community

Please read the organization-wide [contribution guide](../CONTRIBUTING.md),
[security policy](../SECURITY.md), and [code of conduct](../CODE_OF_CONDUCT.md) before participating.

MissionWeaveProtocol repositories are licensed individually. The current protocol and Python implementation
use Apache-2.0.
