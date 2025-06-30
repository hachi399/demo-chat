# simple-chat
WEBSOCKET技術を使用して簡単なチャットアプリを作りました。

renderをデプロイに使ってます。
右のURLから実行可能です　⇒　https://simple-chat-usfp.onrender.com/

| 項目                 　| 簡易版                                          | 完全版                        |
| --------------- 　　   | --------------------------------------          | -------------------------- |
| サーバー            　　| WebSocket 単独（`ws`のみ）                       | `express` + `ws` の組み合わせ    |
| 静的ファイル（HTML/JS） | GitHub Pages に分離してホスティング               | サーバー自身が `/public` を配信      |
| WebSocket URL          | `wss://yourapp.onrender.com`（別ページから接続） | 同じURLに WebSocket & ページ両方ある |
| 使用技術                | `ws` のみ                                       | `express`, `ws`, `path` など |
| 利点                   | 構成がシンプル                                    | 一体型で動作が安定しやすい（実用的）         |


