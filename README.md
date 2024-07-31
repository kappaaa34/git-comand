# コマンドまとめ  
## ソースコードのダウンロード  
~~~
git clone url (英語)
~~~
## リポジトリの編集
[qiita先生 git command 早見表](https://qiita.com/kohga/items/dccf135b0af395f69144)
### 初期設定
.gitconfig file はユーザーフォルダの直下に作られる
~~~
$ git config --global user.name "XXXX"
$ git config --global user.email "XXXX@hogehoge.com"
$ git config --list
~~~
### 初期設定
~~~
$ git remote add origin httpXXXXXXX # 編集場所として設定
$ git pull origin master # 編集するためにソースをコピー　clone的な
# カタカタ編集
$ git add . or XXXXXX # 編集したファイルを登録
$ git commit -m "コミットの説明" # 編集内容を説明
$ git push origin master # 編集内容をアップロード
#ホームページでプルリクエスト
#ホームページでマージ
~~~
# Readme.mdの書き方
マークダウン記法  
[qiita先生 Markdown記法 サンプル集](https://qiita.com/tbpgr/items/989c6badefff69377da7)
