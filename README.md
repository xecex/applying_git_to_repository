# applying_git_to_repository
### [メモ] git管理外リモートリポジトリにgitを適用する方法
gitを適用したいリポジトリをwhatとします

---------------------------------------------

cd what<br>
⇒ 既存リポジトリ(ディレクトリ？)へ移動

git init<br>
⇒ 空のローカルリポジトリを作成

git remote add origin https://XXXXX/what.git<br>
⇒ リモートリポジトリの追加

git fetch origin main<br>
⇒ リモートの最新を取得

git reset --hard origin/main<br>
⇒ ローカルのmainをリモート追跡のmainとしてリセット

---------------------------------------------

他者から見たら危険な方法かもしれません(汗)<br>
もっと良い方法を学んだら追記します