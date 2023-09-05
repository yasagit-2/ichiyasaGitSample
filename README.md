# ichiyasaGitSample
Git学習用　書籍『いちばんやさしいGit&GitHubの教本　第2版』  
This is forked from yasagit-2/ichiyasaGitSample for learning git  
**個人の作業メモだが、このrepoがPublicになってしまっている  

# 学習した感想
- Gitの基本が理解しやすい
    - Git コマンドをいくつか覚えるだけで操作できた
- 普段、VScodeを使っているので、なじみやすい
- Git Bash(コマンド)が使いづらかった
    - 時間がかかる
        - 入力　長い文字　タイプミスによるやり直し
        - 結果表示　文字を読む　英語
    - わかりづらい
        - ブランチの状態　ツリー表示したい
- より実践的な方法を学ぶ必要がありそう
    - VScode　ソース管理：　Git Bashと同じ作業ができる模様
    https://atmarkit.itmedia.co.jp/ait/articles/2109/17/news032.html
    - 拡張機能 Git Graph： ブランチの状態表示
    - 開発のように、テストしながら仕様を決めていく場合はどう管理すべきか？
    - 少人数チームの適切な管理　変更単位が細かいと作業効率が低下
- Sourcetree(GUI)とGit Bash(CLI)の比較
    - Git Bashの方が操作がシンプル　覚える内容が少ないと思った

# 学習メモ
## VScodeの使い方
- Markdown　プレビュー方法
    - [Ctrl]＋[K] → [V]

## Gitコマンド
- Gitの初期設定 p.63～
    - git config
        - ユーザ名、メールアドレス
        - 利用するエディタ
- ローカルリポジトリの操作 p.72～
    - git init：　ローカルリポジトリ作成
    - git status：　状態表示
    - git commit -am "コメント"：　ステージング＋コミット(記録)
    - git checkout -b <name>：　ブランチ作成、切替
    - git checkout master：　ブランチをmasterに切り替え
- リモートリポジトリの操作 p.132～
    - git clone <URL>：　ローカルリポジトリにコピー
    - git push origin <name>：　リモートリポジトリに反映 (承認とマージはGitHub)
    - git pull origin master：　リモート → ローカルに反映
    - git fetch origin：　リモート → ローカルに取得(反映なし)
