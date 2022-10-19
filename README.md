# Github備忘録
## Gitの手順を忘れた時のため残しておく

おおまかには
- git bash を立ち上げ
- プロジェクトファイルに移動
'''
git init
'''
- "git init" でローカルリポジトリを作成 （直下には .git が作成される）
- 編集したファイルをプロジェクトファイルに保存
- "git add ファイル名" で index のようなステージングエリアに追加
- "git commit -m "コミットメッセージ""
- "git remote add origin https://github/…" （リモートリポジトリへ登録）
- "git push origin master"
- おしまい

