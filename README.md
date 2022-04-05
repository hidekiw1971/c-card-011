# compornent（共通部品）

## イメージ画像

- <img width="413" alt="image" src="https://user-images.githubusercontent.com/99580997/161649752-4af94679-61aa-4237-b53f-1f0481c6e4c8.png">


## 概要

- カード（アスペクト比を固定して画像の縦横比を保つ方法）4:3(padding-top: 75%を使用したケース)
- https://www.notion.so/000_web-component-index-c4b399010bf342e9b4e2ed516cf9c730

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項 　
- 今は`aspect-ratio: 4/3;`こちらが使える。簡単。
- https://ryu-webstudy.com/2021/10/28/aspect/
- 以下の`display: block;`指定を`display: inline-block;`にすると、画像の下に隙間ができてしまいます。
- `@use "global" as *;`
- `.box {`
- `  // display: inline-block; ※これをblockにしないと画像の下に隙間ができる。`
- `  display: block;`
- `  width: rem(300);`
- `  margin: 0 auto;`
- `  background-color: #f00;`
- `  overflow: hidden;`
- `  position: relative;`
- `  margin: 0 auto;`
- `  @include mq(md) {`
- `}`

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="749" alt="image" src="https://user-images.githubusercontent.com/99580997/161257024-68947463-6963-431a-b853-343fa65a7377.png">

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="951" alt="image" src="https://user-images.githubusercontent.com/99580997/161257097-e41dbbe2-5f2b-49f2-a9c7-a5dd54606257.png">

## portfolio url:

- https://c-0044.wtb.cfbx.jp/

## 参考にしたサイト

- 【レスポンシブ対応】padding-top で要素の比率を保持しつつサイズを可変させる方法
- https://web-dev.tech/front-end/css/responsive-proportion-padding/
- 【CSS】アスペクト比を固定して画像の縦横比を保つ方法
- https://ryu-webstudy.com/2021/10/28/aspect/

## 更新履歴
- 2022/4/5 `.box`の`width`指定に相違があったので修正。
- 2022/4/5 タイトル、テキストの background-color、color を設定。
- 2022/4/5 隙間が埋めれた。class=box の display:inline-box を block に変更すれば良かった。→ 対応済
- 2022/4/4 padding-top を当てるクラスと img を当てるクラスが相違してたので、修正。→ 完了
- 2022/4/1 初版 作成完了(カード（アスペクト比を固定して画像の縦横比を保つ方法）4:3(padding-top: 75%を使用したケース))

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
