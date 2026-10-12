RunSensor Web App v1

1. iPhoneにBluefyをインストール
2. index.htmlをHTTPSで公開（GitHub Pages推奨）
3. Bluefyでページを開く
4. BLE接続 → START → STOP → データ取得
5. 受信完了後に簡易評価とCSV保存

現行ファームウェアUUID:
Service 90AB / Control 90AF / Data 90B0

注意: v1はfirmware側からDOWNLOAD完了通知がないため、最後の受信から1.5秒無通信で完了判定します。
