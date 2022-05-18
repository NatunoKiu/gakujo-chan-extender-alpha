# More-Better-Gakujo

学情ちゃんを使いやすくするためのブラウザ拡張機能を作りたいな～ってやつです  
「More-Better」は文法的におかしい?…うるせぇ！！！気にすんな！！！！！忘れて！！！！！！！！！

# 機能

## 時間延長
残り時間が10分になると1分以内に内部で時計アイコンクリックに相当する動作を行い，残り時間を20分に戻します．  
これによりメモ帳とかワードとかでレポートを書いてから学情にコピペするという許せるっちゃ許せるけど何となくめんどくさいような気もする作業を消し去ることが出来るかもしれません．  
んでも無限に延長するとログインしっぱなしの人とか出てきて学情ちゃんが重くなりそうなんで一応上限があります．  
「URLが変わった時点から大体120分」です．  
その後はURLが変わる操作をしない限りは延長しません．


## レポートのソート
![レポート画面のボタン](https://github.com/koji-genba/gakujo-chan-extender/blob/Readme_images/report_firefox.png)  
レポート提出の画面を開きますとこんな感じにボタンが追加されてます．ボタンを押すと書いてある感じにソートします．使えばわかる．  
ボタン押さなくても提出期間でソートします．  
ついでにぱっと見分かりにくいことに定評のある一時保存さんを青字で表示することにより分かりやすくします．
### 提出期間でソート
期限内  
｜未提出  
｜一時保存  
｜提出済み  
期限切れ  
｜未提出  
｜一時保存  
｜提出済み  
の順番にソートします．  
### 開講番号でソート
そのままの意味です
### タイトルでソート
学情で表示されるタイトルでソートします．

## GPAの計算とソート
### GPA計算
永遠に更新されないかのように思えるGPAを公開されている成績から自動で計算し，表示します．  
### ソート
![成績画面のボタン](https://github.com/koji-genba/gakujo-chan-extender/blob/Readme_images/score_firefox.png)  
レポートのソートと同じ感じです．  

# 環境
とりあえず最新版のFirefoxで開発しています．Chromeも動作確認を行っています．Edgeもたぶん大丈夫．

# インストール
Firefoxはこちらからどうぞ

https://addons.mozilla.org/ja/firefox/addon/more-better-gakujo/

ChromeとEdgeはこちらから

https://chrome.google.com/webstore/detail/more-better-gakujo/gagpkjpimdfhiccjdofhpnnnecadmmod

# 使い方

## 時間延長
何もしなくても勝手に時間を延長してくれます．

## レポートソーティング
ボタンを押しなさい．  
押さなくても提出期間でソートされますけどね．

## GPA
### 計算
何もしなくても成績のページを開けば表のGPの行の一番上にGPAが表示されます．
### ソート
ボタンを，押しなさい．


# 注意
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
2021/12/29:v0.32Chrome版公開  
2021/12/30:v0.33  
2021/12/30:v0.33Firefox版公開  
2021/12/31:v0.33Chrome版公開  
2022/01/03:v0.34  
2022/01/03:v0.34Firefox版公開  
2022/01/05:v0.34Chrome版公開  
2022/05/17:v0.40Firefox版公開  
2022/05/18:v0.4Chrome版公開  