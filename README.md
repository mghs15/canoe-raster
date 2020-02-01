# canoe-raster
架空地図電子化用レポジトリ

※このレポジトリにおいて、架空地図と現実世界とのリンクについては考慮を行っておりません。当レポジトリ内では、架空地図の内容と実在の人物、地域、団体とは一切の関係はございません。

## データの出典
『大帝都市詳図』拾参號地・筆

## 利用したソフトウエア
QGISのジオリファレンス機能を用いて、画像形式の架空地図を読み込み、QMetaTilesプラグインを用いてタイルに変換した。
座標値は適当であるが、距離については架空地図で想定されたものに（おおよそ）設定する必要があったため、ジオリファレンスが必要となった。

## 利用したソースコード
[地理院地図](https://github.com/gsi-cyberjapan/gsimaps)

