# 日本語自然言語処理プロジェクト - Ginza & SpaCy

## 概要
このプロジェクトは、VS Code環境でGinzaとSpaCyを使用した日本語自然言語処理の実装例である。

## 環境
- **Python**: 3.8以上
- **spaCy**: 3.4.4
- **GiNZA**: 5.2.0
- **開発環境**: VS Code + Jupyter Notebook Extension

## セットアップ

1. 仮想環境作成
```bash
python -m venv ginza_env
source ginza_env/bin/activate  # macOS/Linux
```

2. パッケージインストール
```bash
pip install spacy==3.4.4 ginza==5.2.0 ja_ginza==5.2.0
python -m spacy download ja_ginza
```

3. ノートブック実行
```bash
jupyter notebook NLP入門_Ginza_Spacy_VSCode.ipynb
```

## 主な機能
- 形態素解析・構文解析
- 品詞分析
- 固有表現抽出
- 解析結果のJSON出力

## ファイル構成
```
NLP/
├── NLP入門_Ginza_Spacy_VSCode.ipynb  # メインノートブック
├── 二刀流が本格的に復活へ.txt         # サンプルデータ
├── analysis_results/              # 解析結果
├── ginza_env/                     # 仮想環境
└── README.md                      # このファイル
```

## ライセンス
MIT License

## 更新履歴
- 2025/07/01: 初期リリース、GitHubリポジトリ作成
