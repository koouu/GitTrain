# git&github 

gitインストール  
以下のURLから自分に合うやつインストール  
https://git-scm.com/downloads  

今回はgit bashを使う

適当なディレクトリを作成する  
そのごgit bashでそのディレクトリを開く  
'''
$cd 使うディレクトリ
'''

テキストファイルを作成する  
```
$touch sample.txt
```
開いて以下のように記入する
```
hello would!
```

次にgitを使ってバックアップする  
まずgitを使う宣言をする
'''
$git init
'''
次にgitに追加するものを選択する
'''
git add sample.txt
'''
ファイルすべてを選択する場合
'''
git add -A
'''
次にgitに追加したデータを含めたバックアップを作る
'''
git commit -m "変更点、追加点などのメッセージ"
'''
これによりバックアップは生成される

