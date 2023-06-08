# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
-リモートリポジトリ
    -ネット上に配置して複数人で共有するためのリポジトリ。

-ローカルリポジトリ
    -開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。


## プッシュとマージの違いは何でしょうか？
-プッシュ
-ローカルの内容をリモートにアップする作業

-マージ
-別のブランチの作業内容(変更履歴)をブランチに取り込むこと


## コミットとプッシュの違い
-変更の反映をローカルリポジトリにするのが、コミット。

-リモートリポジトリに反映させるのがプッシュ


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
-変更した内容が作業者全員がわかるように簡潔に記載する


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
-ローカルはコミットしてからマージしてプッシュの順で自分で行う
-プルリクエストでマージする時は、コミットして先にプッシュをし、レビューの担当者へプルリクエストを依頼して、承認&マージを行う。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
-対処法は３つあり
-先にマージされた変更内容を取り込む
-後にマージしようとしている変更内容を取り込む
-両方取り込むの３通り
-３つめに関しては注意が必要でコンフリクトのメッセージは文字列としてソースコードに書き込まれているため、エディタを使って両方の変更内容を取り込んだ処理を上書きする。
-取り組み作業終了後はコンフリクト解決で行った作業内容をコミット。
