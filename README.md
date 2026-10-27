# 砂上天獄

UTAU・MYCOE配布サイト（旧 nanashie.wixsite.com/sazyouutau）

公開URL: https://sazyoudnrk.github.io/sazyouutau/

## 更新のしかた

`index.html` の `<script>` 冒頭にあるデータを書き換えればページに反映されます。

| データ | 中身 | 追加する場所 |
|---|---|---|
| `HISTORY` | 更新履歴 | 先頭（新しいものが上） |
| `WORKS` | 作品ページの動画 | 末尾（下に行くほど新しい）。`url` にYouTube / X / SoundCloudのURLを入れると埋め込みになる |
| `FAN_COVERS` | 作っていただいたカバー | `{title:'…', url:'…'}` を追加 |
| `GALLERY` | 絵 | 先頭に `'img/gallery/ファイル名'` を追加（上に表示される） |

## 画像・音声の置き場所

リポジトリに無いあいだは、画像はWixのものを表示し、試聴は「準備中」と表示します。下の名前でアップロードすると、コードを触らずにそちらへ切り替わります。

```
img/
  tototo.png        注寝ととと 立ち絵（ホーム・詳細）
  tototo_icon.png   注寝ととと UTAUページの四角いアイコン
  toto.png          注与とと 立ち絵
  toto_icon.png     注与とと MYCOEページの四角いアイコン
  gallery/
    g01.png 〜 g21.png / .jpg   絵ページ（現在の並び順。拡張子は元と同じ）
audio/
  tototo_v111.mp3   注寝ととと 試聴（UTAU・詳細ページ）
  tototo_v110.mp3   v1.10 試聴
  tototo_v100.mp3   v1.00 試聴
  toto_1.mp3        注与とと 試聴1（MYCOE・詳細ページ）
  toto_2.mp3        試聴2
  toto_3.mp3        試聴3
```

## ページ

`#home` `#utau` `#terms` `#tototo` `#ust` `#mycoe` `#toto` `#works` `#gallery`
