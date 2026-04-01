# koe
STEP2課題アプリ

Anaconda を使って開発する アプリです。

## 開発環境
- Python 3.11
- Anaconda
- streamlit

## 初期セットアップ

### 1. リポジトリを取得
source treeでこのリポジトリをclone

### 2. 仮想環境の作成

ここからターミナル（コマンドプロンプト）で実行

- cloneしたフォルダへ移動
cd koe

- 仮想環境の作成
conda env create -f environment.yml

- 仮想環境を実行
conda activate koe

- 仮想環境を終了
conda deactivate

## ライブラリを途中で追加する場合

仮想環境にいることを確認し、ターミナルで実行
conda install ライブラリ名

environment.ymlに追加したライブラリ名を追記してpush
注意：バージョン情報は不要
- requests

他のメンバーは追加されているライブラリをローカル上でインストール
conda install ライブラリ名
