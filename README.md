# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
```
リモートリポジトリはネット上に配置して複数の人と共有して使用するためのリポジトリ
ローカルリポジトリは開発者一人ひとりが使用するために自身のPC上に配置するためのリポジトリ
```



## プッシュとマージの違いは何でしょうか？
```
プッシュはリモートリポジトリに保存するが、
マージはAのブランチをメインであるMasterブランチに保存することなので、
リモートリポジトリに保存するかMasterブランチに保存するかの違いです。
```



## コミットとプッシュの違い
```
コミットは変更した内容をAのブランチに名前をつけて保存しますが、
プッシュは変更したブランチをリモートリポジトリに保存します
このことからコミットとプッシュの違いは、変更した内容を保存する際に名前をつけるかつけないかの違いです。
```



## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
```
変更した内容を要約して書いてあげるのが最適
```



## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
```
ローカルでマージするフローはコードレビューせずにMasterブランチに反映されるが、
プルリクエストでマージするフローはコードレビューしてからMasterブランチに反映される。
このことから、二つの違いはコードレビューをするかしないかの違いである。
```



## コンフリクトを起こしてしまった場合、どう対処すべきですか？
```
1.先にマージされた変更内容を取り込む
2.後にマージしようとしている変更内容を取り込む
3.どちらの変更内容も取り込む
3.については注意が必要
```
