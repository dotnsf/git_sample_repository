# Git Test File

## 手順

1. 初期化

  - `$ git init`

2. 状態確認

  - `$ git status`

3. ファイルを git 管理下にいれる

  - `$ git add （ファイル名）`

4. 状態確認

  - `$ git status`

5. コミット

  - `$ git commit -m 'コメント'`

6. 状態確認

  - `$ git status`

7. （最初の１回のみ）メインブランチの指定

  - `$ git branch -M main`

8. （最初の１回のみ）リモートオリジンの指定

  - `$ git remote add origin https://github.com/xxxxx/xxxxx`

9. リモートにコピー

  - `$ git push -u origin main`
