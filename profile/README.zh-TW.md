[English](README.md) | [简体中文](README.zh-CN.md) | **繁體中文** | [日本語](README.ja.md) | [Español](README.es.md) | [Français](README.fr.md) | [Deutsch](README.de.md)

# MissionWeaveProtocol

<p align="center">
  <img src="assets/missionweaveprotocol-icon.svg" width="160" alt="MissionWeaveProtocol 圖示">
</p>

<p align="center">
  <strong><a href="https://missionweaveprotocol.github.io/">官方網站與文件</a></strong>
</p>

MissionWeaveProtocol 是一種面向群組的協定，供 Organization 內部的 AI Agent 進行協調有序、
可課責的協作。

Agent 可以加入多個 Mission Group，在每個 Group 內進行全雙工通訊，提出和接受明確的
WorkItem 並將其納入各 Group 的佇列，還可以透過以證據為基礎的審查和人類核准協調交付。

## 儲存庫

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) — 規範性
  協定規格、術語表、JSON Schema、符合性測試向量和品牌資源。
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — 官方 Python 參考實作、
  完整 Agent runtime、Group gateway、Worker Scheduler、符合性測試執行器、儲存轉接器和可執行 POC。
- [go-sdk](https://github.com/missionweaveprotocol/go-sdk) — 官方 Go 協定 SDK，提供協定綁定及
  Schema 與測試向量符合性能力。
- [typescript-sdk](https://github.com/missionweaveprotocol/typescript-sdk) — 官方 TypeScript
  協定 SDK，提供協定綁定及 Schema 與測試向量符合性能力。
- [java-sdk](https://github.com/missionweaveprotocol/java-sdk) — 官方 Java 協定 SDK，提供協定
  綁定及 Schema 與測試向量符合性能力。
- [rust-sdk](https://github.com/missionweaveprotocol/rust-sdk) — 官方 Rust 協定 SDK，提供協定
  綁定及 Schema 與測試向量符合性能力。
- [cpp-sdk](https://github.com/missionweaveprotocol/cpp-sdk) — 官方 C++ 協定 SDK，提供協定綁定及
  Schema 與測試向量符合性能力。
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — 官方網站和文件儲存庫，內容發布在
  [MissionWeaveProtocol 網站](https://missionweaveprotocol.github.io/)。

協定及其實作採用獨立版本。實作會固定使用明確的協定發布版本或 commit，並發布自身的相容
範圍。

Python 是完整的參考 runtime。Go、TypeScript、Java、Rust 和 C++ SDK 目前專注於協定綁定以及
Schema 與測試向量符合性，並不聲稱具備完整的 runtime 行為符合性。

## 社群

參與前，請閱讀適用於整個 Organization 的[貢獻指南](../CONTRIBUTING.md)、
[安全策略](../SECURITY.md)和[行為準則](../CODE_OF_CONDUCT.md)。

MissionWeaveProtocol 的各儲存庫分別使用各自的授權條款。目前協定和 Python 實作採用
Apache-2.0。
