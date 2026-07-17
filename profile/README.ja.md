[English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | **日本語** | [Español](README.es.md) | [Français](README.fr.md) | [Deutsch](README.de.md)

# MissionWeaveProtocol

<p align="center">
  <img src="assets/missionweaveprotocol-icon.svg" width="160" alt="MissionWeaveProtocol アイコン">
</p>

<p align="center">
  <strong><a href="https://missionweaveprotocol.github.io/">公式ウェブサイトとドキュメント</a></strong>
</p>

MissionWeaveProtocol は、組織内の AI Agent が協調し、説明責任を果たしながら協働するための
Group 指向プロトコルです。

Agent は複数の Mission Group に参加し、各 Group 内で全二重通信を行い、明示的な WorkItem を
提案して Group ごとのキューに受け入れ、エビデンスに基づくレビューと人による承認を通じて
成果物の提供を調整できます。

## リポジトリ

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) — 規範仕様、
  用語集、JSON Schema、適合性ベクトル、およびブランドアセット。
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — 公式の Python
  リファレンス実装。完全な Agent ランタイム、Group ゲートウェイ、Worker Scheduler、適合性
  ランナー、ストレージアダプター、および実行可能な POC を含みます。
- [go-sdk](https://github.com/missionweaveprotocol/go-sdk) — プロトコルバインディングと
  Schema・ベクトル適合性を提供する公式 Go プロトコル SDK。
- [typescript-sdk](https://github.com/missionweaveprotocol/typescript-sdk) — プロトコル
  バインディングと Schema・ベクトル適合性を提供する公式 TypeScript プロトコル SDK。
- [java-sdk](https://github.com/missionweaveprotocol/java-sdk) — プロトコルバインディングと
  Schema・ベクトル適合性を提供する公式 Java プロトコル SDK。
- [rust-sdk](https://github.com/missionweaveprotocol/rust-sdk) — プロトコルバインディングと
  Schema・ベクトル適合性を提供する公式 Rust プロトコル SDK。
- [cpp-sdk](https://github.com/missionweaveprotocol/cpp-sdk) — プロトコルバインディングと
  Schema・ベクトル適合性を提供する公式 C++ プロトコル SDK。
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — 公式ウェブサイトおよびドキュメントのリポジトリ。
  [MissionWeaveProtocol ウェブサイト](https://missionweaveprotocol.github.io/)
  として公開されています。

プロトコルとその実装は、それぞれ独立してバージョン管理されます。実装は、明示的なプロトコルの
リリースまたはコミットを固定し、対応する互換性範囲を公開します。

Python は完全なリファレンスランタイムです。Go、TypeScript、Java、Rust、C++ SDK は現在、
プロトコルバインディングと Schema・ベクトル適合性に重点を置いており、完全なランタイムの
振る舞い適合性を主張するものではありません。

## コミュニティ

参加する前に、組織全体に適用される[コントリビューションガイド](../CONTRIBUTING.md)、
[セキュリティポリシー](../SECURITY.md)、および[行動規範](../CODE_OF_CONDUCT.md)をお読みください。

MissionWeaveProtocol の各リポジトリには、ライセンスが個別に設定されています。現行のプロトコルと
Python 実装には Apache-2.0 が適用されます。
