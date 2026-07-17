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
Group, proponer y aceptar elementos WorkItem explícitos en colas específicas de cada Group, y
coordinar la entrega mediante revisión basada en evidencias y aprobación humana.

## Repositorios

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) —
  especificación normativa, glosario, JSON Schema, vectores de conformidad y recursos de marca.
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — implementación de referencia
  oficial en Python, runtime de Agent, gateway de Group, Worker Scheduler, ejecutor de conformidad,
  adaptadores de almacenamiento y POC ejecutable.
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — repositorio oficial del sitio web y la documentación, publicado en el
  [sitio web de MissionWeaveProtocol](https://missionweaveprotocol.github.io/).

El protocolo y sus implementaciones se versionan de forma independiente. Las implementaciones
fijan explícitamente una versión publicada o un commit del protocolo y publican su intervalo de
compatibilidad.

## Comunidad

Antes de participar, consulta la [guía de contribución](../CONTRIBUTING.md), la
[política de seguridad](../SECURITY.md) y el [código de conducta](../CODE_OF_CONDUCT.md), que se
aplican en toda la Organization.

Los repositorios de MissionWeaveProtocol se licencian de forma individual. El protocolo y la
implementación en Python actuales usan Apache-2.0.
