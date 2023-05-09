### 第3回課題提出

## APサーバについて

- APサーバー名：puma
- バージョン：puma version 5.6.5

![01.puma](https:/lecture01/repository_dir/RaiseTech/image/01.puma)

- APサーバーを終了させるとOopsが表示されてアクセスできない。

![02.puma](https:/lecture01/repository_dir/RaiseTech/image/02.puma_shut)

- -bin/devコマンドを実行してAPサーバーを起動させると再度アクセスできた

![03.puma](https:/lecture01/repository_dir/RaiseTech/image/03.puma_restart)

![04.puma](https:/lecture01/repository_dir/RaiseTech/image/04.puma_again)

## DBサーバーについて

- DBサーバー名：MySQL
- バージョン：mysql Ver 8.0.33

![05.db](https:/lecture01/repository_dir/RaiseTech/image/05.db)

- sudo service mysqld stopでサーバーを停止（insctiveになった）させるとOエラーが表示されてアクセスできない。

![06.db](https:/lecture01/repository_dir/RaiseTech/image/06.db.stop)

- sudo service mysqld restartで再起動（active/runningになった）してbin/devコマンドを実行すると再度アクセスできた。

![07.db](https:/lecture01/repository_dir/RaiseTech/image/07.db_restart)

## Railsの構成管理ツール

- Bundler

![07.db](https:/lecture01/repository_dir/RaiseTech/image/08.bundler)


## 今回の学び

- APサーバーとDBサーバーについて
- pumaについて
- bundlerについて
- 絶対パスと相対パス