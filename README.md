# compornent（共通部品）

## イメージ画像

- <img width="408" alt="image" src="https://user-images.githubusercontent.com/99580997/161256966-41306db3-0a8c-4e35-8aac-8cbf92a51235.png">

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

- 2022/4/4 padding-top を当てるクラスと img を当てるクラスが相違してたので、修正。→ 完了
- 2022/4/1 初版 作成完了(カード（アスペクト比を固定して画像の縦横比を保つ方法）4:3(padding-top: 75%を使用したケース))

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
