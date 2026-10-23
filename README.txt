賀頂会 ウェブサイト【背景透過版・三つ桜】
========================================

今回の修正：金色・銀色の三つ桜の画像を透過画像に変更しました。
元の赤・黄色の背景は除去し、金属的な質感はそのまま残しています。
ヘッダー・メイン画像・会章・フッター・ファビコン・ホーム画面用アイコンに反映済みです。
代表者のGIFアニメーションも維持しています（元から透過GIF）。

【公開方法】
GitHubリポジトリ kacho-fumitada/kacho-kai.github.io のルートに
index.html と assets フォルダを丸ごと上書きアップロードしてください。
その後、コミットを保存してください。GitHubの公開内容は自動更新していません。

【編集方法】
index.html をメモ帳やVisual Studio Codeで開いて編集してください。
コードはHTMLとCSSのみで、JavaScriptは使用していません。
画像の参照パスは冒頭の <style> 内にまとめています。

【画像の内訳】
assets/gold-kamon.webp               背景透過の金色の三つ桜（サイト表示用）
assets/silver-kamon.webp             背景透過の銀色の三つ桜（サイト表示用）
assets/gold-kamon-transparent.png    背景透過の金色の三つ桜（PNG保存版）
assets/silver-kamon-transparent.png  背景透過の銀色の三つ桜（PNG保存版）
assets/profile.gif                  代表者アニメーションGIF（元画像のまま）
assets/favicon.ico                  ファビコン（透過）
assets/favicon-32.png               32pxファビコン（透過）
assets/apple-touch-icon.png         ホーム画面用画像（透過PNG）
assets/site-icon-512.png            512pxサイトアイコン（透過PNG）

※画像はCSS背景で表示し、通常のドラッグ保存を抑制していますが、
  ブラウザで表示する以上、取得や画面撮影を完全に防ぐことはできません。
※一部のホーム画面環境では、OSが自動的に背景色を付与することがあります。
