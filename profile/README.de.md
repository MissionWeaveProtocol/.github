[English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [Español](README.es.md) | [Français](README.fr.md) | **Deutsch**

# MissionWeaveProtocol

<p align="center">
  <img src="assets/missionweaveprotocol-icon.svg" width="160" alt="MissionWeaveProtocol-Symbol">
</p>

<p align="center">
  <strong><a href="https://missionweaveprotocol.github.io/">Offizielle Website und Dokumentation</a></strong>
</p>

MissionWeaveProtocol ist ein Group-orientiertes Protokoll für koordinierte,
verantwortbare Zusammenarbeit zwischen KI-Agenten innerhalb einer
Organization.

Agenten können mehreren Mission Groups beitreten, innerhalb jeder Group
Vollduplex-Nachrichten austauschen, explizite WorkItems für Group-spezifische
Warteschlangen vorschlagen und annehmen sowie die Lieferung durch
Evidence-basierte Prüfungen und menschliche Approvals koordinieren.

## Repositorys

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) —
  normative Spezifikation, Glossar, JSON-Schemata, Konformitätsvektoren und
  Markenressourcen.
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — offizielle
  Python-Referenzimplementierung mit vollständiger Agent-Runtime, Group-Gateway,
  Worker Scheduler, Konformitäts-Runner, Speicheradaptern und ausführbarem POC.
- [go-sdk](https://github.com/missionweaveprotocol/go-sdk) — offizielles Go
  Protokoll-SDK mit Protokoll-Bindings sowie Schema- und Vektorkonformität.
- [typescript-sdk](https://github.com/missionweaveprotocol/typescript-sdk) —
  offizielles TypeScript-Protokoll-SDK mit Protokoll-Bindings sowie Schema- und
  Vektorkonformität.
- [java-sdk](https://github.com/missionweaveprotocol/java-sdk) — offizielles Java
  Protokoll-SDK mit Protokoll-Bindings sowie Schema- und Vektorkonformität.
- [rust-sdk](https://github.com/missionweaveprotocol/rust-sdk) — offizielles Rust
  Protokoll-SDK mit Protokoll-Bindings sowie Schema- und Vektorkonformität.
- [cpp-sdk](https://github.com/missionweaveprotocol/cpp-sdk) — offizielles C++
  Protokoll-SDK mit Protokoll-Bindings sowie Schema- und Vektorkonformität.
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — offizielles Repository für Website und Dokumentation, veröffentlicht auf der
  [MissionWeaveProtocol-Website](https://missionweaveprotocol.github.io/).

Das Protokoll und seine Implementierungen werden unabhängig voneinander
versioniert. Implementierungen pinnen ein ausdrückliches Protokoll-Release oder
einen Commit und veröffentlichen ihren Kompatibilitätsbereich.

Python ist die vollständige Referenz-Runtime. Die SDKs für Go, TypeScript, Java,
Rust und C++ konzentrieren sich derzeit auf Protokoll-Bindings sowie Schema- und
Vektorkonformität; sie beanspruchen keine vollständige verhaltensbezogene
Runtime-Konformität.

## Community

Lies vor der Mitwirkung den organisationsweiten
[Leitfaden für Beiträge](../CONTRIBUTING.md), die
[Sicherheitsrichtlinie](../SECURITY.md) und den
[Verhaltenskodex](../CODE_OF_CONDUCT.md).

MissionWeaveProtocol-Repositorys werden einzeln lizenziert. Das aktuelle
Protokoll und die aktuelle Python-Implementierung verwenden Apache-2.0.
