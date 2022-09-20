# wagyu_price
# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
【調べないで書いたこと】
・リモートリポジトリ：GitHubのようにWeb上に保存できる場所のこと。
・ローカルリポジトリ：個人個人のPC上などに保存する場所のこと。

【調べたこと】
・リモートリポジトリ：ネット上に配置するソースコードの置き場のこと
・ローカルリポジトリ：PCに配置するソースコードの置き場のこと

## プッシュとマージの違いは何でしょうか？
【調べないで書いたこと】
・pushはローカルリポジトリ等で作成したものをリモートリポジトリに複製して保存すること。
・mergeはリモートリポジトリからブランチを切ったものに変更を加えたうえでリモートリポジトリに保存すること。

【調べたこと】
・別のブランチの作業内容(変更履歴)をブランチに取り込むことを merge (マージ) という
・pushはリポジトリ上のデータをリモートリポジトリに反映させることのみ


## コミットとプッシュの違い
【調べないで書いたこと】
・commitはリポジトリに登録するだけで、コミットだけではリモートリポジトリ上に反映されない
・pushすることによってリポジトリ上のデータをリモートリポジトリに反映させることができる

【調べたこと】
・commitは変更履歴を残すためのもの
・pushはローカルリポジトリの内容をリモートリポジトリに反映する

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
【調べないで書いたこと】
・いつ誰がみても変更内容についてわかるように書くこと

【調べたこと】
・編集内容をより正確に表すようなメッセージを残す

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
【調べたこと】
■ローカルでマージする場合
①変更内容をcommit
②masterブランチにmerge
③リモートリポジトリにpushして反映

■プルリクエストでmergeするフロー
①変更内容をcommit
②リモートリポジトリにpushで反映
③他の人に変更内容をmergeしてくださいという依頼(プルリクエスト)を行う
④承認＆merge

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
【調べないで書いたこと】
・コンフリクトを起こした当事者同士や責任者などに相談して話し合う

【調べたこと】
・ソースコードを書いた人と相談しながら作業を進める
