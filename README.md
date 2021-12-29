# More-Better-Gakujo

学情ちゃんを使いやすくするためのブラウザ拡張機能を作りたいな～ってやつです

# 機能

## 時間延長
残り時間が10分になると1分以内に内部で時計アイコンクリックに相当する動作を行い，残り時間を20分に戻します．
これによりメモ帳とかワードとかでレポートを書いてから学情にコピペするという許せるっちゃ許せるけど何となくめんどくさいような気もする作業を消し去ることが出来るかもしれません．
んでも無限に延長するとログインしっぱなしの人とか出てきて学情ちゃんが重くなりそうなんで一応上限があります．「URLが変わった時点から大体120分」です．その後はURLが変わる操作をしない限りは延長しません

## レポートソーティング
レポートとか小テストとかの画面のあのクッソ見ずらい表を，未提出(締切早->遅)->一時保存(締切早->遅)->提出済(締切早->遅)の順番にソーティングしてくれます．
ぱっと見分かりにくいことに定評のある一時保存さんを青字で表示することにより分かりやすくします．

## GPA計算
永遠に更新されないかのように思えるGPAを公開されている成績から自動で計算し，表示します．

# 環境
とりあえず最新版のFirefoxで開発しています．Chromeも一応動作確認を行っています(多分大丈夫なはず，はず)．Edgeだと微妙に動きが悪い気がします．なんとなく．

# インストール
Firefoxはこちらからどうぞ

https://addons.mozilla.org/ja/firefox/addon/more-better-gakujo/

Chromeはこちらから

https://chrome.google.com/webstore/detail/more-better-gakujo/gagpkjpimdfhiccjdofhpnnnecadmmod

# 使い方

## 時間延長
何もしなくても勝手に時間を延長してくれます．

## レポートソーティング
何もしなくてもレポート・小テストの所を開けば勝手にソーティングしてくれます．
でも提出するページから戻ったときはソーティングできません．ごめんちゃい．

## GPA計算
何もしなくても成績のページを開けば表のGPの行の一番上にGPAが表示されます．

# 注意
↑で書いたようにレポートソーティングはレポート提出画面内での画面遷移でテーブルが表示されたときは動作しません．URLの変化がトリガーになってるからです．気が向いたら修正します．
この拡張機能を使ったことによる損害について作者は一切の責任を負いません．

# プライバシーポリシー
このブラウザ拡張機能は処理の過程で成績などのデータにアクセスします．しかしそれらのデータが保存されたり別の端末に送信されることはありません．
また今後，ユーザーの設定などを端末内に保存する機能が追加される可能性がありますが，それらのデータがサーバーなどに送信されることはありません．


# 作者
https://twitter.com/koji_genba ←これが作者です．質問や問い合わせがあればどぞ．

# 記録
2021/12/28:v0.3Firefox版公開  
2021/12/28:v0.31(Firefox)時間延長機能の修正  
2021/12/28:v0.32(Firefox)時間延長機能の追加修正  
2021/12/28:v0.3Chrome版公開  