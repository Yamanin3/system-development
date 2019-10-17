﻿# system-development
システム開発演習用

一応新しい資料等を作るときや編集するときは、ブランチを切って作業するようにしたいと思います。

ー以下操作方法ー

現在のローカルのブランチを表示する
git branch

新しいブランチを作成する
git branch [ブランチ名]

作ったブランチに移動する
git checkout [ブランチ名]

ブランチでの作業が終わったら作業したファイルをaddしcommitする
git add [ファイル名]
git commit -m "～の項目を追加した"

コミットが完了したらリモートにpushする(git pushだけではダメ!)
git push origin [作業したブランチ名]

ブランチでする作業が終わった場合(現在のブランチでもう作業することがなくなった場合)
1. githubへ行き、pull requestする
2. ローカルから作業していたブランチを削除する
    git branch -D [削除したいブランチ名]
