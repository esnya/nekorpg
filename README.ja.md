# NekoRPG : オンラインTRPGサポートシステム

## これは何？
どどんとふに代表されるような、TRPGをオンラインで遊ぶためのツール群です。
シンプルなツールの集まりで、チャット、ホワイトボード、キャラクターシートの機能があります。

2013年末からサークル内でのオンラインセッションのために開発、運用されてきました。
主にソード・ワールド2.0に使われています。

## Pre-Alpha テスト公開
近い将来の一般公開に向けて、テスト用サーバーを作りました。

マニュアルもなければ、きっとバグもたくさんあります。
人柱になりたい方向けです。

まずはじめに「利用上の注意」を読んでください。

## 利用上の注意
すべて自己責任で使ってください。
NekoRPGにかかわるあらゆる損害やトラブルなどの責任は負いかねます。

データは消えてしまうことがあるかもしれません。
大事なデータはダウンロードするようにしてください。
NekoRPGではバックアップはとっていません。

NekoRPGではサーバーに次の情報を保存します。
保存した情報は、サービスの提供と今後の改善のためにのみ使用します。

* TwitterID
* チャットルーム
* チャットメッセージ

また、TwitterのパスワードなどはNekoRPGのサーバーに送信されることはなく、タイムラインを読み込んだりツイートをることもありません。

意見、質問、要望などはGitHubかTwitterを通して受け付けます。
ただし、すべての意見に応えられるとは限りません。

## テストサーバー
Twitterアカウントでログインできます。

* [チャット (http://chat.nekometer.info)](http://chat.nekometer.info)
* [ホワイトボード (http://board.nekometer.info)](http://board.nekometer.info)
* ~~キャラクターシート~~ (準備中)

## バグ・要望・Pull Request
GitHubの各リポジトリでIssue/Pull Requestを作ってください。

* [チャット (http://github.com/ukatama/nekochat/issues/new)](http://github.com/ukatama/nekochat/issues/new)
* [ホワイトボード (http://github.com/ukatama/nekochat/issues/new)](http://github.com/ukatama/nekochat/issues/new)
* [ログイン (http://github.com/ukatama/nekoproxy/issues/new)](http://github.com/ukatama/nekoproxy/issues/new)
* [NekoRPG全体・その他 (http://github.com/ukatama/nekorpg/issues/new)](http://github.com/ukatama/nekorpg/issues/new)

## 広報・お問い合わせTwitterアカウント
[@ukatama_dev](https://twitter.com/ukatama_dev)

## チャットについて
できること
* チャットルーム作成・削除
* メッセージ投稿
* 名前変更（複数併用可）
* アイコン
* ダイスロール
* ~~キャラクターシート連携~~ (準備中)

## ホワイトボードについて
30分更新がないと削除されます。

## ログアウトについて
ブラウザのURLバーから直接`http://(ツール名).nekometer.info/logout`を開いてください。