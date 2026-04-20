# Masato Funahara

東京農工大学大学院 修士課程在籍。機械学習とマルチモーダルデータ分析を専門としています。

## About

- **研究**：視線・打鍵・座圧センサーのデータを組み合わせ、ユーザーの困惑状態を機械学習で推定（分類精度 0.81 達成）
- **インターン**：BigQuery を用いたデータ基盤構築とデータ分析業務（株式会社ネクストビート）
- **関心領域**：データ分析 / 機械学習 / データ基盤構築

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=google-cloud&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

## Projects

| リポジトリ | 概要 | 技術 |
|-----------|------|------|
| [confusion-state-estimation](https://github.com/Funahara-Masato/confusion-state-estimation) | 修士研究の実装コード一式。視線・打鍵・座圧の 3 モダリティをスタッキングで統合し、困惑状態を推定する ML パイプライン。 | Python / scikit-learn / TensorFlow |
| [soundart](https://github.com/Funahara-Masato/soundart) — [demo](https://funahara-masato.github.io/soundart/) | 10 秒録音するだけで惑星が生まれ成長する PWA。Web Audio API で周波数解析し、音の特徴を惑星パラメータにマッピング。 | JavaScript / Web Audio API |
| [confused-ad](https://github.com/Funahara-Masato/confused-ad) — [demo](https://funahara-masato.github.io/confused-ad/) | 打鍵リズムやマウス動作からユーザーの困惑度をリアルタイムで推定し、広告表示を動的に変化させる実験的デモ。修士研究の概念をブラウザ上で実装したもの。 | JavaScript |
| [stock_visualization_prediction](https://github.com/Funahara-Masato/stock_visualization_prediction) — [demo](https://stockvisualizationprediction-ldxavncflckiviposxcjym.streamlit.app/) | 複数銘柄の株価をグラフで可視化し、機械学習モデルで翌日の値動きを予測する Web アプリ。 | Python / Streamlit / scikit-learn |
| [sorasend](https://github.com/Funahara-Masato/sorasend) — [demo](https://funahara-masato.github.io/sorasend/) | 撮影した夜空の写真を、指定した国や地域で夜になるタイミングに合わせて届ける Web アプリ。 | JavaScript |
| [fighting_game](https://github.com/Funahara-Masato/fighting_game) | Pygame を使って実装した 2D スティックマン格闘ゲーム。 | Python / Pygame |

## Research

**マルチモーダルデータを用いた文章要約作業における困惑状態推定**

文章を読んで要約する作業中に、ユーザーがどこで「迷っているか・詰まっているか」をセンサーデータから推定する研究です。

- 視線追跡・キーボード入力・座圧センサーの 3 種類のデータを同時に収集
- 各センサーのデータを個別にモデル化し、スタッキング（複数モデルの出力を入力とする二段階学習）で統合
- 個人特化モデルにて分類精度 **0.81** を達成
- 情報処理学会 第88回全国大会（2026年3月）発表

## Contact

funaharamasato@gmail.com
