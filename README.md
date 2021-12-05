# featurte-my-board
# デプロイ方法
  1.必要なライブラリをインストールする
  2.mysqlを起動する
  3.nodeを起動する
  4.アクセス

# 1.必要なライブラリをインストールする
  * node_modules
  * mysql

# インストール方法
  - node_modules
    npm install

  - mysql
    aptコマンド？

# 2.mysqlを起動する(mac)
  - 状態確認
    mysql.server status

    (ubuntuの場合)
    systemctl status mysql

  - 起動
    mysql.server start

    (ubuntuの場合)
    systemctl start mysql

  - 停止
    mysql.server stop

    (ubuntuの場合)
    systemctl stop mysql

# 3.nodeを起動する
  - app.jsがある場所に遷移する(今回の場合はnode-appディレクトリ)
  - 起動
    npm start

# 4.アクセス
  - ローカルの場合
    localhost:3000

  - 外部の場合
    ?

# その他
  - 出てきたエラーまとめ
    ・Error: connect ECONNREFUSED 127.0.0.1:3306
    　→mysqlが起動されてないと思われるので、起動してみる
