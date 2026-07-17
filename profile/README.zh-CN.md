[English](README.md) | **简体中文** | [日本語](README.ja.md) | [Español](README.es.md)

# MissionWeaveProtocol

<p align="center">
  <img src="assets/missionweaveprotocol-icon.svg" width="160" alt="MissionWeaveProtocol 图标">
</p>

<p align="center">
  <strong><a href="https://missionweaveprotocol.github.io/">官方网站与文档</a></strong>
</p>

MissionWeaveProtocol 是一种面向群组的协议，供 Organization 内部的 AI Agent 开展协调有序、
可问责的协作。

Agent 可以加入多个 Mission Group，在每个 Group 内进行全双工通信，提出和接受明确的
WorkItem 并将其纳入各 Group 的队列，还可以通过基于证据的评审和人类批准协调交付。

## 仓库

- [missionweaveprotocol](https://github.com/missionweaveprotocol/missionweaveprotocol) — 规范性
  协议说明、术语表、JSON Schema、符合性测试向量和品牌资源。
- [python-sdk](https://github.com/missionweaveprotocol/python-sdk) — 官方 Python 参考实现、
  Agent 运行时、Group 网关、Worker Scheduler、符合性测试运行器、存储适配器和可执行 POC。
- [missionweaveprotocol.github.io](https://github.com/missionweaveprotocol/missionweaveprotocol.github.io)
  — 官方网站和文档仓库，内容发布在
  [MissionWeaveProtocol 网站](https://missionweaveprotocol.github.io/)。

协议及其实现采用独立版本。实现会固定使用明确的协议发布版本或 commit，并发布自身的兼容
范围。

## 社区

参与前，请阅读适用于整个 Organization 的[贡献指南](../CONTRIBUTING.md)、
[安全策略](../SECURITY.md)和[行为准则](../CODE_OF_CONDUCT.md)。

MissionWeaveProtocol 的各仓库分别使用各自的许可证。当前协议和 Python 实现使用
Apache-2.0。
