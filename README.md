# Catnix
完全自作のOS <br>
複数アカウント方式でlinuxの管理者とかのやつ<br>
###### どうでもいいけど、gitにローカルで作成しだしたときにmdから書くのってあれなのかな？

### どうでもいいけど名前の話。<br>
Cat -> ただ単に猫が好きだから。<br>
nix -> よくある、unix的な <br>

### フォルダ構成() <Br>
`/bin` 一般でも管理者でも使えるコマンド類のファイルが有る。 <br>
`/dev` キーボードとかマウスの操作をデバイスドライバ(?)に引き渡すやつ。 <Br>
`/etc` OS上で動くアプリとかOS本体の設定が置かれてる。aptとか <Br>
`/home` ユーザが利用するフォルダ <br>
`/sbin` sudo(管理者)だけが利用できるコマンド類のファイル <br>
`/crs` 一時的なファイル配置用のやつ。　アプリが起動するときとかのキャッシュ的な？ 再起動すると消える <Br>
`/app` アプリ関連の情報を保存してる。　ここをバルスすればアプリも消える。<Br>
`/var` アプリのログなどを保持するところ <br>

### 今後の野望
- リリースした自作OSでサイトを作る
- 



### アイディア

[楽しそう](https://ja.wikipedia.org/wiki/Slackware)
