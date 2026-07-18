[English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | **Español** | [Français](README.fr.md) | [Deutsch](README.de.md)

# MissionWeaveProtocol

<p align="center">
  <img src="assets/missionweaveprotocol-icon.svg" width="160" alt="Icono de MissionWeaveProtocol">
</p>

<p align="center">
  <strong><a href="https://missionweaveprotocol.github.io/">Sitio web y documentación oficiales</a></strong>
</p>

MissionWeaveProtocol es un protocolo orientado a grupos para la colaboración coordinada y sujeta a
rendición de cuentas entre Agent de IA dentro de una Organization.

Cada Agent puede unirse a varios Mission Group, comunicarse en modo full-duplex dentro de cada
Group, proponer y aceptar WorkItem explícitos en colas específicas de cada Group, y
coordinar la entrega mediante revisión basada en evidencias y aprobación humana.

## Repositorios

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) —
  especificación normativa, glosario, JSON Schema, vectores de conformidad y recursos de marca.
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — implementación de referencia
  oficial en Python con runtime de Agent completo, gateway de Group, Worker Scheduler, ejecutor de
  conformidad, adaptadores de almacenamiento y POC ejecutable.
- [go-sdk](https://github.com/missionweaveprotocol/go-sdk) — SDK oficial del protocolo para Go,
  con bindings del protocolo y conformidad de schemas y vectores.
- [typescript-sdk](https://github.com/missionweaveprotocol/typescript-sdk) — SDK oficial del
  protocolo para TypeScript, con bindings del protocolo y conformidad de schemas y vectores.
- [java-sdk](https://github.com/missionweaveprotocol/java-sdk) — SDK oficial del protocolo para
  Java, con bindings del protocolo y conformidad de schemas y vectores.
- [rust-sdk](https://github.com/missionweaveprotocol/rust-sdk) — SDK oficial del protocolo para
  Rust, con bindings del protocolo y conformidad de schemas y vectores.
- [cpp-sdk](https://github.com/missionweaveprotocol/cpp-sdk) — SDK oficial del protocolo para C++,
  con bindings del protocolo y conformidad de schemas y vectores.
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — repositorio oficial del sitio web y la documentación, publicado en el
  [sitio web de MissionWeaveProtocol](https://missionweaveprotocol.github.io/).

El protocolo y sus implementaciones se versionan de forma independiente. Las implementaciones
fijan explícitamente una versión publicada o un commit del protocolo y publican su intervalo de
compatibilidad.

Python es el runtime de referencia completo. Los SDK de Go, TypeScript, Java, Rust y C++ se centran
actualmente en los bindings del protocolo y la conformidad de schemas y vectores; no declaran una
conformidad completa del comportamiento del runtime.

## Comunidad

Antes de participar, consulta la [guía de contribución](../CONTRIBUTING.md), la
[política de seguridad](../SECURITY.md) y el [código de conducta](../CODE_OF_CONDUCT.md), que se
aplican en toda la Organization.

Los repositorios de MissionWeaveProtocol se licencian de forma individual. El protocolo y la
implementación en Python actuales usan Apache-2.0.
