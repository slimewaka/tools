# tools

ブラウザだけで動く、インストール不要の小さなツール集（と小さなAndroidアプリ）。

公開ページ: https://slimewaka.github.io/tools/

| ツール | 内容 |
|---|---|
| [背景透過ツール](https://slimewaka.github.io/tools/bg-remover/) | 画像の背景を消して透明にし、PNG / 32bit BMP / TGA / WebP / ICO で保存する。AI による背景除去にも対応 |
| [Wi-Fiつけ忘れ通知](https://slimewaka.github.io/tools/wifi-reminder/) | 登録したWi-Fiが近くにあるのに使っていないとき通知する Android アプリ |

画像などのデータは外部に送信されず、すべてブラウザ内で処理されます。

AI による背景除去には [BiRefNet](https://github.com/ZhengPeng7/BiRefNet)（MIT）と [ONNX Runtime Web](https://github.com/microsoft/onnxruntime)（MIT）を使っています（`bg-remover/ai/LICENSES.txt`）。
