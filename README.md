# CaltDeepL/.github

CaltDeepL のすべてのリポジトリで共通に使う Issue テンプレートと PR テンプレート。

GitHub は、リポジトリに自前のテンプレートがない場合、このリポジトリのテンプレートを使う。
リポジトリ固有の項目（ビルドコマンドなど）が必要な場合だけ、そのリポジトリに自前のテンプレートを置く。

| ファイル | 用途 |
| --- | --- |
| `.github/ISSUE_TEMPLATE/task.md` | ロードマップの 1 タスク。作業メモ欄を兼ねる |
| `.github/ISSUE_TEMPLATE/bug.md` | 不具合の報告 |
| `.github/ISSUE_TEMPLATE/config.yml` | テンプレートを使わない Issue も許可する |
| `.github/pull_request_template.md` | PR の本文 |

## 運用ルール

- タスクの作業メモは `docs/` ではなく、そのタスクの Issue に書く（2026-10-24 以降）
- 設計判断は各リポジトリの `docs/adr/` に ADR として残す（Issue には移さない）
- PR 本文に `Closes #NN` を書き、マージ時に Issue を閉じる
