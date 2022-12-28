# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
1.リモートリポジトリは複数人で共有することができる専用サーバーを用いたリポジトリ
ローカルリポジトリはユーザー一人ひとりが専用で使い変更を加えるリポジトリ

##　プッシュとマージの違いは何でしょうか？
プッシュはコミットをローカルリポジトリからリモートリポジトリに送る
マージは変更履歴を合併させる役割があり、別のブランチの変更内容をブランチに取り組む

##　コミットとプッシュの違い
コミットをすることでそれまで実装した内容をローカルリポジトリへ反映することができる
プッシュはリモートリポジトリに変更を反映させることができる

##　コミットのメッセージはどのように書いてあげるのが最適でしょうか？
何をどのように変更をしたのかが分かるようなメッセージを残すのが最適。

## ローカルでマージするフロート、プルリクエストでマージするフローの違いは何でしょうか？
プルリクエストをすることで一度レビューをするというアクションが生まれる為バグが発生しにくくまた気がつきやすいメリットがある。

##　コンフリクトを起こしてしまった場合、どう対処すべきでしょうか？

先にマージされた変更内容を取り込むまたは後でマージしようとしている変更内容を取り組む対応が必要である。
しかし現場では少しでも変更内容の意図が読み取れない場合はソースコードを書いた人と相談しながら作業をする必要がある。



