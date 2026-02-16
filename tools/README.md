# tools/

データ生成・変換・管理用スクリプト。

## 実行環境

- PC環境（Python想定）
- Picoでは実行しない

## 役割

- 地図データ加工
- JSON生成
- 外部データ変換
- データセット構築

## 出力先

生成結果は `data/` に出力する。

## 注意

- firmwareコードをここに置かない
- 装置上で実行しない
- 開発用ツール専用

## 予定スクリプト

- generate_mesh.py
- convert_geojson.py
- build_dataset.py