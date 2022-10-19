# Github備忘録
## Gitの手順を忘れた時のため残しておく

おおまかには
- git bash を立ち上げ
- プロジェクトファイルに移動
- ローカルリポジトリを作成 （直下には .git が作成される）

```
$ git init
```
- 編集したファイルをプロジェクトファイルに保存
 
- index と呼ばれるステージングエリアに追加
```
$ git add ファイル名 
```
- ローカルリポジトリにコミット
```
$ git commit -m コミットメッセージ
```
- リモートリポジトリに登録
```
$ git remote add origin https://github/・・・
```
- リモートリポジトリにプッシュ
```
$ git push origin master
```

