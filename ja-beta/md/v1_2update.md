# バージョン1.2.0リリースノート
## 機能追加
### チャット機能
* [ローカルLLMに対応](LocalLLM.md)
* [マークダウンの表示に対応](AskToAI.md#update00)
* [コードをコピーするボタンを追加](AskToAI.md#update01)
* [送信時にモデル選択する機能を追加](AskToAI.md#update02)

### ファイルビュー
* [ファイルビューにクイックアクセス用のボタンを追加](FileView.md#update03)
* [初期ディレクトリ設定に対応](FileView.md#update04)

### RAG
* [文章全体を渡してチャットするモードを追加](DocumentFile.md#update05)

### 議事録
* [Whisper Large V3 Turboに対応](overview.md#update06)

### その他
* [AI実行環境のベンチマーク機能の追加](Benchmark.md)

### OpenAIのモデル変更
* GPT3.5の削除
* GPT-4o mini対応

### UI
* [設定画面のコンフィグファイルの設定にライセンスファイルの有効期限を表示](ConfigFile.md#update07)
* [校正と翻訳で変更前と変更後を表示](Translation.md#update08)
* [画像編集で画像全体を選択するボタンを追加](GenerateImage.md#update09)

## 改善
* GPUを使用した場合のドキュメント登録の高速化
* エクセルのインポートにおいて、末尾の空白を削除
* 1行の中でテキストが分割されたPDFの翻訳の精度改善

## 不具合修正
* 翻訳のコマンドプロンプトを編集しようとすると校正のプロンプトという表示がある問題を修正
* チャット欄に大量の文章を入れるとオーバフローする問題を修正
* チャットヒストリーの左右の幅を広げにくい問題を修正
* Geminiでシステムプロンプトが適用されない問題を修正
* libllama.dylibがmacOS14向けにビルドされているためmacOS13で起動できない問題を修正

<br>

#### [次のページへ&emsp;＞](v1_1update.md)
