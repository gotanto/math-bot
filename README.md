院試対策bot
====

大学院入試で出題された問題をランダムに出題してくれるLINE botです．

## Description

LINEのMessaging APIを利用しています．  
ID:@052jfwyzを友だち検索すると利用できます．  
ここに置いてあるのは院試問題の画像とヒント用のテキストファイルだけです．  
pythonで書いたサーバ側の処理はここには置いていません． 


## Contribution

注意：今後破壊的な変更が予想されます．色々と整理されるまで待ってから貢献してもらった方が良いかもしれません．  

math-bot/hint/ku*/*.txt のテキストファイルがそのままヒントとして利用されます．  
ファイル名と問題番号の対応がちょっとだけ紛らわしくて申し訳ないのですが以下のような形で対応しています．

2014年以降に関してはそのままな命名  
例）ku2017basic1.txt→京大2017年基礎科目大問1のヒント  
例）ku2016basic1_1.txt→京大2016年基礎科目I大問1のヒント  
例）ku2016basic2_1.txt→京大2016年基礎科目Ⅱ大問1のヒント  
例）ku2016basic2_1.txt→京大2016年基礎科目Ⅱ大問1のヒント


2013年以前に関しては少しイレギュラーな命名  
例）ku2013basic1_1.txt→京大2013年基礎数学大問1のヒント  
例）ku2013basic2_1.txt→京大2013年数学Ⅰ大問1のヒント 

テキストファイルを編集するだけで誰でも簡単にプルリクを送れます．  
編集ルールとしては「、」や「。」を「，」と「．」に揃えるくらいでしょうか．  
すでに何かヒントを書いてある問題でもヒントが雑だったりもしかしたら間違っている可能性もあります．  
ヒントをみんなで作ると楽しいかもしれません．
