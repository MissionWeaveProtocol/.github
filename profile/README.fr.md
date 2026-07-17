[English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [Español](README.es.md) | **Français** | [Deutsch](README.de.md)

# MissionWeaveProtocol

<p align="center">
  <img src="assets/missionweaveprotocol-icon.svg" width="160" alt="Icône de MissionWeaveProtocol">
</p>

<p align="center">
  <strong><a href="https://missionweaveprotocol.github.io/">Site officiel et documentation</a></strong>
</p>

MissionWeaveProtocol est un protocole orienté Group pour une collaboration coordonnée et
responsable entre des Agent d’IA au sein d’une Organization.

Les Agent peuvent rejoindre plusieurs Mission Group, communiquer en duplex intégral dans chaque
Group, proposer et accepter des WorkItem explicites dans des files propres à chaque Group, puis
coordonner la livraison au moyen d’une revue fondée sur les Evidence et d’une approbation humaine.

## Dépôts

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) —
  spécification normative, glossaire, schémas JSON, vecteurs de conformité et ressources de marque.
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — implémentation de référence
  officielle en Python avec environnement d’exécution complet des Agent, passerelle de Group,
  Worker Scheduler, outil de conformité, adaptateurs de stockage et preuve de concept exécutable.
- [go-sdk](https://github.com/missionweaveprotocol/go-sdk) — SDK de protocole officiel pour Go,
  avec bindings de protocole et conformité des schémas et vecteurs.
- [typescript-sdk](https://github.com/missionweaveprotocol/typescript-sdk) — SDK de protocole
  officiel pour TypeScript, avec bindings de protocole et conformité des schémas et vecteurs.
- [java-sdk](https://github.com/missionweaveprotocol/java-sdk) — SDK de protocole officiel pour
  Java, avec bindings de protocole et conformité des schémas et vecteurs.
- [rust-sdk](https://github.com/missionweaveprotocol/rust-sdk) — SDK de protocole officiel pour
  Rust, avec bindings de protocole et conformité des schémas et vecteurs.
- [cpp-sdk](https://github.com/missionweaveprotocol/cpp-sdk) — SDK de protocole officiel pour C++,
  avec bindings de protocole et conformité des schémas et vecteurs.
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — dépôt officiel du site et de la documentation, publié sur le
  [site de MissionWeaveProtocol](https://missionweaveprotocol.github.io/).

Le protocole et ses implémentations sont versionnés indépendamment. Les implémentations fixent
explicitement une version publiée ou un commit du protocole et publient leur plage de compatibilité.

Python est l’environnement d’exécution de référence complet. Les SDK Go, TypeScript, Java, Rust et
C++ se concentrent actuellement sur les bindings de protocole et la conformité des schémas et
vecteurs ; ils ne revendiquent pas une conformité comportementale complète de l’environnement
d’exécution.

## Communauté

Avant de participer, consultez le [guide de contribution](../CONTRIBUTING.md), la
[politique de sécurité](../SECURITY.md) et le [code de conduite](../CODE_OF_CONDUCT.md), qui
s’appliquent à toute l’Organization.

Les dépôts MissionWeaveProtocol possèdent chacun leur propre licence. Le protocole et
l’implémentation Python actuels utilisent Apache-2.0.
