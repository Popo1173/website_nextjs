# website_nextjs

# 環境構築
npm init -y //npm moduleの初期化<br>
npm install --save next react react-dom //Next.jsをインストール<br>
{// run dev を追加<br>
  "scripts": {<br>
    "dev": "next"<br>
  }<br>
  <br>
  mkdir pages　//pagesを作りindex.jsを作るこれがあるとルートとして読み込まれるため<br>
  
## PWA のモジュールをインストール
npm i -D next-offline
## now v2 でデプロイするとき以外は実行
touch server.js
