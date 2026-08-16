# practiceSE

SEを目指すために、GitHub運用とアプリ開発を実践するためのリポジトリです。

## 目的
- GitHubの基本運用（Issue / Branch / Pull Request / Review / Merge）を身につける
- 小さなアプリを複数作成しながら、設計・実装・テスト・改善の流れを体験する

## リポジトリ構成
- `apps/`: 作成するアプリを配置（1アプリ1ディレクトリ）
- `docs/`: 学習課題や開発メモ

```text
practiceSE/
├─ apps/
│  ├─ README.md
│  └─ sample-app/
│     ├─ README.md
│     └─ src/
└─ docs/
   └─ practice-tasks.md
```

## 複数アプリを作るルール
1. `apps/<app-name>/` を作成する
2. 各アプリに `README.md` を作り、目的・使い方・学習ポイントを書く
3. 必要な実装は `src/` 以下に配置する
4. アプリごとに独立して改善・レビューできる単位でPRを作る

## 基本開発フロー
1. Issueを作成して作業内容を明確化
2. `feature/<issue番号>-<短い説明>` でブランチを作成
3. 実装・確認後にPull Requestを作成
4. レビュー指摘を反映してマージ

詳細は `CONTRIBUTING.md` を参照してください。
