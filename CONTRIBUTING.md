# Contributing to MissionWeave

Thank you for helping build MissionWeave.

## Choose the right repository

- Protocol semantics, wire behavior, schemas, conformance vectors, terminology, or ADRs belong in
  [MissionWeaveProtocol](https://github.com/MissionWeaveProject/MissionWeaveProtocol).
- Python interfaces, runtime behavior, storage, scheduling, gateway behavior, packaging, or the POC
  belong in [MissionWeavePython](https://github.com/MissionWeaveProject/MissionWeavePython).

When a change affects both repositories, start with the protocol change. The Python implementation
should then pin the resulting protocol commit or release in a separate change.

## Before opening a pull request

1. Search existing issues and pull requests for related work.
2. Open an issue before a large, breaking, security-sensitive, or cross-repository change.
3. Keep the pull request focused on one coherent outcome.
4. Link the issue or explain the motivation directly.
5. Update tests, documentation, schemas, and vectors when applicable.
6. State compatibility, migration, and security effects explicitly.

## Review expectations

Protocol changes should be implementation-neutral and include conformance evidence. Python changes
should be tested through the affected public interface and keep the pinned protocol artifacts in
sync. Reviewers may ask for an ADR when a decision changes durable protocol semantics.

By contributing, you agree that your contribution is licensed under the license of the repository
to which it is submitted.
