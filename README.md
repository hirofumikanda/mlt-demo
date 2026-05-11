# MLT Demo

MapLibre GL JS で MLT エンコードされた PMTiles を表示する、最小構成の静的ビューワーです。

このリポジトリには2026-04-15.0時点の[OvertureMaps](https://overturemaps.org/)からダウンロードした以下のサンプルデータが含まれています。

- 建物: `pmtiles/building.mlt.pmtiles`
- 道路: `pmtiles/road.mlt.pmtiles`
- 土地利用: `pmtiles/landuse.mlt.pmtiles`
- 地名: `pmtiles/place.mlt.pmtiles`

## 特徴

- MapLibre GL JS + PMTiles によるクライアントサイド表示
- MLT エンコードされたベクタータイルを読み込み
- クリックした地物の属性をポップアップ表示
- URL ハッシュによる現在位置・ズームの共有
- タイル境界の可視化

## ファイル構成

```text
.
├── index.html
├── style.json
└── pmtiles/
    ├── building.mlt.pmtiles
    ├── landuse.mlt.pmtiles
    ├── place.mlt.pmtiles
    └── road.mlt.pmtiles
```

## ライセンス

- データ出典: OpenStreetMap contributors, Overture Maps Foundation