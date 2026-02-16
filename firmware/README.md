# firmware/

Raspberry Pi Pico で動作するメインファームウェア。

## 役割

- センサ制御
- GPSデータ取得
- JSONデータ読み込み
- ログ記録（SDカード）
- 表示制御（LCD）
- イベント処理
- ESP32との通信

## 実行環境

- MicroPython / CircuitPython（予定）
- Raspberry Pi Pico

## 設計方針

- 組み込み環境専用コードのみ
- PC用コードを含めない
- モジュール分離設計
- ログ出力必須

## 予定モジュール

- main.py
- gps.py
- logger.py
- display.py
- mesh_lookup.py
- config.py

## 注意

このディレクトリのコードはSDカードやフラッシュに書き込まれる実行コード。
開発用スクリプトは `tools/` に置く。