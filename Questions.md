
## Questions
### 1. Code splitting and prefetching
https://nextjs.org/learn/basics/navigate-between-pages/client-side

どこまでバックグラウンドでロードしてくれるのか？
レンダリングまでして、display:noneの状態にしてくれてる？
コード
imgの取得はしてくれる？
APIは流石に呼び出さない？
css, jsのロードは？

・レンダリングの流れ
https://milestone-of-se.nesuke.com/sv-basic/web-tech-basic/html-javascript-dom-parse-rendering/
① パース
② レンダーツリー構築
③ レイアウト
④ ペインティング

### 2. Assets, Metadata, and CSS
https://nextjs.org/learn/basics/assets-metadata-css/global-styles

_app.jsにstyleを入れることで、全体のコンポーネントにCSSが適用される仕様がわかりにくい気がする。


### 3. React自体はpre-renderだったか？
https://nextjs.org/learn/basics/data-fetching/two-forms

build時にHTMLファイルが作られるはず。
新バージョンじゃないと、サーバサイドレンダリングができない。
サーバサイドからデータを取ってきた上で表示する項目と、Staticですむコンポーネントで分けれるのか？
    → できる？

### 4. どこからgetStaticは読み取られてる？
https://nextjs.org/learn/basics/data-fetching/with-data

### 5. サーバサイドから取得したデータを表示する場合は、全てサーバサイドレンダリングを選ばないといけない？
https://nextjs.org/learn/basics/data-fetching/request-time
コンポーネントのモックだけレンダリングして、
データのみ表示の際に取得するとかはできないのか？(3と同じ疑問)

### 6. SWRとは？ (あとで調べる)


### 7. getStaticPathsとgetStaticProps
getStaticPathsとgetStaticPropsは、どちらが先に動くのだろうか？
asyncだから並列処理？
return はどこに返される？？

### 8. fallback:true とfalseの違いがわからない。
