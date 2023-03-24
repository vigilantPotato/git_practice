git commit後、エディタを終了するためには、ESC→:wq

2. ブランチ切り替え関係
ブランチを新規作成し、そのブランチに切り替えるコマンド
git branch -b "branch_name"

masterブランチへ切り替える方法
git checkout master

ひとつ前のブランチに切り替える
git checkout -

ブランチをマージする
マージ先のブランチに移動後、git merge --no-ff branch_name
→エディタが立ち上がる

masterブランチ以外のブランチへ送信するテスト