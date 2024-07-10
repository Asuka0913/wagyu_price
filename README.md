# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
```
+ リモートリポジトリはネット上に配置して複数の人と共有して使用するためのリポジトリ
+ ローカルリポジトリは開発者一人ひとりが使用するために自身のPC上に配置するためのリポジトリ
```



## プッシュとマージの違いは何でしょうか？
```
+ プッシュは、ローカルで行った変更をリモートに送る操作であり、他の人との共同作業を進めるために必要。
+ マージは、異なるブランチのコードを統合する操作であり、複数の開発者が同時に作業を行う場合や、新しい機能を本番環境に統合する際に必要。
+ なので、プッシュとマージの違いは変更を共有するか統合するかの違いです。
```



## コミットとプッシュの違い
```
+ コミットは変更した内容をAのブランチに名前をつけて保存する(保存先はgitディレクトリ)
+ プッシュは変更したブランチをリモートリポジトリに保存する
+ このことからコミットとプッシュの違いは、変更した内容を保存する際に名前をつけるかつけないかの違いです。
```



## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
```
+ その履歴がどんな編集を行なったのかを示すように書いてあげるのが最適
+ さらにプレフィックスをコミットメッセージやブランチ名に特定の接頭辞を付けるとコミットやブランチの目的や内容が一目でわかるようになる
```



## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
```
+ ローカルでマージするフローはコードレビューせずにMasterブランチに反映される。
+ プルリクエストでマージするフローはコードレビューしてからMasterブランチに反映される。
+ このことから、二つの違いはコードレビューをするかしないかの違いである。
+ 実際に現場でフローを使う際はプルリクエストでマージをするほうが、不具合を早期発見しやすくなる。
```



## コンフリクトを起こしてしまった場合、どう対処すべきですか？
```
1 先にマージされた変更内容を取り込む
2 後にマージしようとしている変更内容を取り込む
3 どちらの変更内容も取り込む
+ 3.についてはチーム全体の情報共有が必要になる

++ またチーム開発でコンフリクトが発生した際は一人で解決してはいけない
1 意図の誤解：ほかのメンバーの変更意図を誤解しやすくなる
2 視点の不足：多様な視点やアイデアが欠ける
3 責任の集中：問題が発生した際の責任が一人に集中する
4 透明性の欠如：変更内容がほかのメンバーに見えにくくなる
5 学習機会の欠如：チーム全体の学習機会を逃す
6 コミュニケーション不足：チーム内のコミュニケーションが減る
+ これらの要因が起きうる可能性があるので一人で解決せずにチームで解決すること
```
