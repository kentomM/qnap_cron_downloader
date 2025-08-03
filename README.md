# QNAP Cron Downloader

Python 3.12とNode.js 20を使用したプロジェクトです。

## 開発環境

このプロジェクトはVS Code DevContainerを使用して開発環境を統一しています。

### 必要な環境

- Docker
- VS Code
- Dev Containers拡張機能

### セットアップ

1. VS Codeでプロジェクトを開く
2. コマンドパレット（Cmd+Shift+P）を開き、「Dev Containers: Reopen in Container」を実行
3. コンテナのビルドが完了するまで待つ

### 開発ツール

Python開発には以下のRust製ツールを使用しています：

- **Ruff**: 高速なPythonリンター・フォーマッター
- **Black**: コードフォーマッター
- **isort**: import文の整理
- **mypy**: 型チェック

### 使用方法

```bash
# 依存関係のインストール
pip install -e .

# 開発用依存関係のインストール
pip install -e ".[dev]"

# コードの品質チェック
ruff check .

# コードのフォーマット
ruff format .

# 型チェック
mypy .

# テストの実行
pytest
```

## Node.js

Node.js 20はClaude Codeの使用のためにインストールされています。
