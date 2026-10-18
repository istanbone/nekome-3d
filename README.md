# nekome-3d

バーの店内を Scaniverse で3Dスキャンし、ブラウザだけで見られるようにしたものです。
アプリや外部サービスには依存せず、このリポジトリのファイルだけで表示できます。

- `index.html` … ビューア本体（Gaussian Splatting を WebGL2 で描画）
- `scene_orig.b64.txt` … ビューアが読み込む3Dデータ
- `scene_orig.spz` … 3Dデータの原本（SPZ形式。他のビューアでも開けます）

GitHub Pages（Settings → Pages → Branch: main / root）で公開しています。
