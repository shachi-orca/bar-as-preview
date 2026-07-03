BAR A's — 画像差し替えガイド / Image Swap Guide
==================================================

■ 使い方 / How to swap
このフォルダ内の各ファイルを「同じファイル名」で上書きするだけで、
サイトの画像が自動的に切り替わります（HTMLの編集は不要）。
推奨：横長は 1600px 前後、カクテル等の縦/正方は 1000px 前後、JPEG 品質80〜85。

Just overwrite each file below using the SAME filename — no code changes needed.

■ 画像マップ / Image map
--------------------------------------------------
[店舗 / Venue]
 venue-tower.jpg           … Two Worlds「THE TOWER」背景（シンメトリーのバックバー壁 / 横長）
 venue-concept.jpg         … CONCEPT 大ビジュアル（夜景＋キャンドルの一杯 / 縦 3:4）
 venue-backbar.jpg         … 予備（旧バックバー・任意） ＋ Gallery① は gallery-backbar.jpg を使用
                              (最上階・ガラス張りバックバー / 横長推奨 4:3〜16:9)
 venue-cityview.jpg        … Two Worlds「THE CITY」背景（上昇演出の中継カット）
                              ※ gallery-cityview.jpg と同じ夜景シーンで統一
 venue-rooftop-lounge.jpg  … Two Worlds「THE ROOFTOP」背景
                              (屋上・白いソファラウンジ＋夜景 / 横長・白文字)
 venue-rooftop-counter.jpg … Gallery⑤（屋上・白いカウンターのカクテル列 / 横長）
 venue-bartender.jpg       … 予備（バーテンダーの手元 / 任意）

[ギャラリー / Gallery] ※各タイル個別の画像（演出セクションとは別ファイル）
 gallery-backbar.jpg       … ① BACK BAR（バックバー）
 gallery-cityview.jpg      … ② CITY VIEW（夜景）※ THE CITY と同じシーン
 gallery-signature.jpg     … ③ SIGNATURE（シグネチャーカクテル）
 gallery-rooftop.jpg       … ④ ROOFTOP（屋上ラウンジ）※ THE ROOFTOP と同じシーン
 gallery-night.jpg         … ⑤ NIGHT（ターンテーブルとジャズの夜）

[カクテル / Signature cocktails] ※現在は仮イメージ。本番写真に差し替え推奨
 cocktail-01.jpg … N°01 Amber Throne   （琥珀のウイスキー系 / 縦 3:4 推奨）
 cocktail-02.jpg … N°02 Crimson Bloom  （赤系フルーツカクテル）
 cocktail-03.jpg … N°03 Verde Mirage   （グリーン・柑橘系）
 cocktail-04.jpg … N°04 Midnight Azure （青系）
 cocktail-05.jpg … N°05 Golden Hour    （ゴールド系）

■ 補足
・各カードの色アクセント（accent）は index.html の該当 <article> の style="--accent:..."
  で個別調整できます。
・カクテルの背景方針（バックバー／夜景）は各カードの class="card bar" / "card night" と
  キャプションで管理しています。
