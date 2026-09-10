TOTONOI 香港向けLP v4
=====================

GitHub Pages用ファイル一式です。
リポジトリ直下に、このフォルダの中身をそのままアップロードしてください。

主要ファイル
------------
index.html   : 香港向けGoogle広告LP
rooms.html   : 客房詳細
meal.html    : 餐點詳細
access.html  : 交通詳細
assets/      : 詳細ページ共通CSS
images/      : 選別・軽量化済みWebP画像

予約URL
------
https://reserve.489ban.net/client/g-totonoi/2/plan

香港限定クーポン
----------------
HKTO26 / 5% OFF
※一泊二食（1泊2食付き）プランのみ対象
※素泊まり／純住宿は対象外

画像最適化
----------
追加ZIPは約86MBありましたが、LPで訴求力の高い写真だけを選別し、
最大幅を主に1500〜1920pxへ縮小、WebP（quality 78〜80）へ変換しています。
最終サイト一式は約2.3MB台です。

Google広告計測
--------------
index.html末尾に予約ボタンクリックの gtag イベント雛形があります。
GA4 / Google Ads のIDを確定したらタグを追加してください。


v5 更新
- 首頁 DINNER 圖片改為 IMG_3481
- PRIVATE TIME 改為 PRIVATE GARDEN，圖片改為 _X5A1339
- 客房主圖與室內照更新
- 客房頁新增備品／洗手間／簡易廚房照片
- 餐點頁新增早餐照片
- 新增圖片已縮小並 WebP 化


v7 updates:
- Uploaded logo applied.
- Room page rebuilt with heya.zip photos and detailed 4 room types.
- Private space/garden messaging refined.
- Meal page removed outdoor BBQ/marshmallow photos and uses shokuji.zip food photos.
- Access emojis removed and Tokyo approx. 100 min by car added.

v9 changes:
- Rebuilt header logos as transparent black/white logo assets.
- White logo on photo/dark hero, black logo on white detail-page header.
- Removed colored logo background blocks and normalized logo sizing.
- Added official Instagram contact section to all pages.
- Instagram: https://www.instagram.com/totonoi.fujiyamanakako/?hl=ja

v10
- Fixed broken Instagram CTA caused by escaped newline text in CSS.
- Removed inline SVG from the Instagram button to prevent global SVG styling conflicts.
- Rebuilt Instagram contact CTA as a compact premium pill button on desktop/mobile.
