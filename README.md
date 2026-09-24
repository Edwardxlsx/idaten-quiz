# いだてんクリニック「性の健康」クイズ

梅毒・HIV の予防、男性更年期、ジェンダーについての短いクイズです。
`index.html` の 1 ファイルだけで動きます（外部からの読み込みは Google Fonts のみ）。

## 公開ページ

https://edwardxlsx.github.io/idaten-quiz/

- 検索エンジンには載せない設定です（`robots.txt` と `<meta name="robots" content="noindex,nofollow">`）。
- 検索に出ないだけなので、**URL を知っている人は誰でも開けます。**

## ファイル

| ファイル | 中身 |
| --- | --- |
| `index.html` | クイズ本体。これだけで動きます |
| `robots.txt` | 検索エンジンへの除外指定 |

## 更新のしかた

`index.html` は元の HTML から自動で作ります。**このリポジトリの中身は手で編集しません。**

手元の作業用フォルダ（非公開）にある PowerShell スクリプト `publish-quiz-pages.ps1` を実行すると、
作り直しから commit / push までを行います。

    .\quiz\publish-quiz-pages.ps1          確認用の注記を入れて公開
    .\quiz\publish-quiz-pages.ps1 -Final   注記なしで公開

push から公開ページに反映されるまで、1〜2 分かかります。
