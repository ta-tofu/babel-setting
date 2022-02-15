# babel-setting
- Babel を使用する為のスターターパック

# 使い方
1. 下記のファイルを導入したい環境にダウンロードしてください。  
- package.json  
- package-lock.json  
- .babelrc  
- .browserslistrc  

2. <pre>npm install</pre> を実行して、node_modules をインストールしてください。    

    node_modules の中身を削除してからインストールしたい場合は、<pre>npm ci</pre> を実行してください。  
3. あとはお好きな JavaScript のコードを作成して、<pre>npm run build [変換前のファイル名] --out-file [変換後のファイル名]</pre> を実行してトランスパイルしてください。
