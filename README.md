# Kaggle MAP - Charting Student Math Misunderstandings

このリポジトリは、Kaggle競技「[MAP - Charting Student Math Misunderstandings](https://www.kaggle.com/competitions/map-charting-student-math-misunderstandings)」のソリューション開発コードです。

## 概要

学生が数学問題を解く際に発生する誤解のパターンを分析・分類するための機械学習モデルの開発を行っています。学生の回答と説明文から、どのような種類の誤解が生じているかを特定することが目的です。

## プロジェクト構造

```
kaggle_map/
├── data/
│   └── analysis/
│       └── conflict_data.xlsx
├── src/
│   ├── eda/                     # 探索的データ解析コード
│   └── experiments/
│       ├── backup/              # 初期実験のバックアップ
│       ├── validation/          # 推論、モデルマージ、AWQ量子化コード
│       ├── validation_v2/       # 推論、モデルマージ、AWQ量子化コード（version 2）
│       └── exp001-exp029/       # 各実験ディレクトリ
└── README.md
```

## メモ
- exp028が最終提出用モデル(Qwen2.5-32B-Instruct)