# isucon memo

SSHログイン<br>
（事前にSSH公開/秘密鍵を作成しておりサーバ側で公開鍵を使ってログイン設定している前提）<br>

> https://qiita.com/seigot/items/a6eaebccfd427bb315b4
> PC側で秘密鍵/公開鍵ペア生成する
>```
>$ cd ~/.ssh
>$ ssh-keygen -t rsa -b 4096  # 鍵の名前は適当
>```

```
$ ssh -p xxxxx seigot@xx.xx.xx.xx -i ~/.ssh/seigot_20220xxx
```

# 過去問



## 1.現状の把握

```
１．システム構成の把握（プロセスやファイルの特定）
２．ネットワーク構成の把握（port番号、通信の流れ、etc..）
```

#### サーバーで特定のポート番号を待ち受けているかどうかの確認
> [lsofコマンド入門](https://qiita.com/hypermkt/items/905139168b0bc5c28ef2)

```
$ sudo lsof -P -i:443
```

#### プロセスの確認

[psコマンド　チートシート](https://qiita.com/Higemal/items/6a1f2b4b870d67f67e4e)

```
$ ps -aux
```



## 2.xxx
## 3.xxx

### 各種情報

> https://products.sint.co.jp/topsic/blog/isucon<br> <br>
> Ubuntu 18.04 LTSをベースに、データベースはMySQL、リバースプロキシはnginx、アプリケーションサーバはGoという構成になっています。<br>

> https://isucon.net/archives/56735884.html <br>
> ISUCONについての理解、問題の解き方について深く学ぶことができるオンラインイベント「ISUCON 事前講習 2022 座学」を開催しました。カジュアルに質問を受け付け、参加したことがないという方にも好評をいただきました、ぜひアーカイブをご視聴ください。 

> 過去問の環境構築 <br>
> https://isucon.net/archives/54946542.html

> ISUCON12 予選問題の解説と講評 : ISUCON公式Blog
> https://isucon.net/archives/56850281.html
>> 性能測定→ボトルネック特定→解決、は上手く経験できると面白そう

