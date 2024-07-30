# How to Use
## ターミナルを開き、SSLを無効にし、butterfly.server.pyを起動する
```zsh
webTerminalButterfly % butterfly.server.py --host="0.0.0.0" --port=57575 --unsecure
```

:::note warn
必要な操作が完了したら、サーバーを停止することが重要です。停止しないと、不必要に公開されているサービスが残り、セキュリティリスクが生じる可能性があります。サーバーの停止方法は以下の通りです：

ターミナルで実行している場合:
サーバーを停止するには、Ctrl+Cを押すことで、butterfly.server.pyの実行を停止できます。

SSLを無効にすることで通信が暗号化されなくなるため、特にインターネット経由でアクセスする場合は注意が必要です。社内ネットワークなどの安全な環境でのみ使用することを推奨します。
:::