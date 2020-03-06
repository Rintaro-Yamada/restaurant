# git基本コマンド　使い方
## ファイルのアップロードの仕方
- git add アップロードしたいファイル名
- git commit -m "コメントを書く"
- git push origin master

ファイルをアップロードしたらslackやLine等でアナウンスする。

## ファイルのダウンロードの仕方
- git pull 

## ブランチの作り方
- git branch ブランチ名            ブランチを作る
- git branch                     現存するブランチの確認
- git checkout ブランチ名          更新するブランチの選択

## ブランチの削除
- git branch :ブランチ名
        
## マージ方法
- git checkout マージ先のブランチ名
- git merge マージするブランチ名
- git push origin マージ先のブランチ名
