# HTMLを書いてみよう


## 初めてのHTML 


HTMLという単語を聞いたことがある人は多いと思います。   
”プログラミングをする時に使用するもの”と捉えている方も少なくないと思います。   
ここではHTMLがどのようなものなのかを学習していきます。    

## HTMLとは  


HTMLとは、Hyper Text Markup Language（ハイパーテキスト・マークアップ・ランゲージ）の略で、  
Webページを作るための最も基本的なマークアップ言語のひとつです。   
マークアップ言語とは、組版指定に使われる言語で、視覚表現や文章構造などを記述するための形式言語です。  
テキストファイルであることが多いですが、バイナリデータによる形式もあります。   
では早速書いていきましょう。   

## HTMLとは  


まず、最初にエディタ上で新規ファイル（command(Ctrl) + n）を作成しましょう。
そしてすぐに保存（command(Ctrl) + s）します。
ファイル名は「index.html」とします。

そしてHTMLにはほとんど必ず記述するテンプレート文があります。  


```html
<!DOCTYPE html>
<html lang="ja">
<head>    
    <meta charset="utf-8">    
    <title>HTML5</title>
</head>
<body>
</body>
</html>
```


##  DOCTYPE宣言

```html
<!DOCTYPE html>
```

DOCTYPEは単にブラウザにどのようなドキュメントであるかを知らせる方法です。  
HTML文書の場合、具体的なHTMLのバージョンや特徴のことです。  
DOCTYPEは必ずいつもHTML文書の冒頭に書きます。  

##  HTML要素

```html
<html lang="ja">
</html>
```

どのHTML文書でも、次はhtml要素が必要です。  
上の例では、lang属性が日本語になるようにjaで指定しています。  
他の全ての要素はこの要素の子孫（内側）として配置しなければなりません。   

##  head要素

```html
<head>    
    <meta charset="utf-8">    
    <title>HTML5</title>
</head>
```

どのHTML文書でも、次はhtml要素が必要です。  
上の例では、lang属性が日本語になるようにjaで指定しています。  
他の全ての要素はこの要素の子孫（内側）として配置しなければなりません。  

JavaScriptはウェブページにて複雑なことをできるようにするプログラミング言語です。  
さまざまなもの（Webサイトやスマートテレビ、最新の車など）に使われているのですが、  
WebのフロントエンドにおけるJavaScriptの役割は、  
動的にコンテンツを更新したり主に動きの部分の役割が大きいです。    


##  body要素

```html
<body>
​</body>
```

body要素は、文書のすべてのコンテンツを指定するための場所です。  
この「body」タグ内に書かれたものがブラウザに表示されます。    


##  サンプル

これらを踏まえて少しHTMLを書いてみましょう。
```html
<!DOCTYPE html>
<html lang="ja">
<head>    
    <meta charset="utf-8">    
    <title>HTMLサンプル</title>
</head>

<body>    
    <h1>Hello HTML</h1>    
    <p>初めてのHTML</p>
</body>

</html>
```

記述が終わったら保存（command(Ctrl) + s）してindex.htmlファイル  
をブラウザで開いてみましょう。    

HTMLにはさまざまなタグ（文字を描画するタグ、画像を描画するタ  
グ、リストを表示するタグ）があるので色々試してみましょう。  

タグ一覧
http://www.htmq.com/html/
