### 第3回課題提出

## APサーバについて

- APサーバー名：puma
- バージョン：puma version 5.6.5

![01.puma](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/01.puma.jpg)

- APサーバーを終了させるとOopsが表示されてアクセスできない。

![02.puma](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/02.puma_shut.jpg)

- -bin/devコマンドを実行してAPサーバーを起動させると再度アクセスできた

![03.puma](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/03.puma_restart.jpg)

![04.puma](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/04.puma_again.jpg)

## DBサーバーについて

- DBサーバー名：MySQL
- バージョン：mysql Ver 8.0.33

![05.db](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/05.db.jpg)

- sudo service mysqld stopでサーバーを停止（insctiveになった）させるとOエラーが表示されてアクセスできない。

![06.db](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/06.db.stop.jpg)

- sudo service mysqld restartで再起動（active/runningになった）してbin/devコマンドを実行すると再度アクセスできた。

![07.db](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/07.db_restart.jpg)

## Railsの構成管理ツール

- Bundler

![07.db](https:/home/ec2-user/environment/repository_dir/RaiseTech/image/08.bundler.jpg)


## 今回の学び

- APサーバーとDBサーバーについて
- pumaについて
- bundlerについて
- 絶対パスと相対パス