# Note Hashtag Scraper

noteの指定ハッシュタグページから記事情報を自動収集するツールです。

## 概要
Seleniumを使用した動的サイトのスクレイピングに対応しています。
無限スクロールのページでも自動検知して全件取得します。

## 取得データ
- 記事タイトル
- 記事URL

## 出力形式
- Excelファイル（.xlsx）
- ヘッダー色付け・列幅自動調整・縞模様・行固定

## 使用ライブラリ
- selenium
- beautifulsoup4
- pandas
- openpyxl

## 実行環境
- Python 3.12
- Google Chrome
