# resume-template

このリポジトリは職務経歴書をマークダウンで管理するための、テンプレートリポジトリです。

テンプレートをクローンしてご自由にご利用ください。

## 使い方

textlint の実行は以下のコマンドを実行してください。

```
yarn textlint ./docs/README.md --fix
```

PDF ファイルの出力は以下のように対象ファイルを指定してください。

```
yarn pdf ./docs/README.md
```

## リポジトリ構成など

このプロジェクトで使用されている主要なツールについて説明します。

- **Renovate**: Renovate は、GitHub リポジトリ内の依存関係を自動的に更新するためのツール。このプロジェクトでは、`renovate.json5`が設定ファイル
- **GitHub Actions**: GitHub Actions は、GitHub 上で自動化されたワークフローを設定するためのツール。このプロジェクトでは、`release.yml`により PDF ファイルをリリースノートに添付可能

- **husky + lint-staged** ： コミット前に lint を強制、校正ルールに従わないとコミットできない仕様

## コンタクト

TomIshiyama
