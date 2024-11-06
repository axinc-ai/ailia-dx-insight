# ローカルLLMの設定

## ailia DX Insight内でのローカルLLMの構築
GGUF形式で圧縮されたLLMモデルを使用することで、ailia DX Insightの中だけで簡単にローカルLLMとの接続をすることができます。

1. 設定![gear](img/icon_gear.png)の中のチャットAIの項目を選択し、「ローカル（ailiaLLM）」の「+追加」を選択します。

![localLLM01](img/localLLM01.png)

2. ローカルLLMモデル登録用ウィンドウが開きます。各項目を記入します。<br>「local LLM モデルタイプ」の項目を「GGUF model」に変更することで、「GGUF モデルパス」の項目が表示されます。

![localLLM02](img/localLLM02.png)

* 名前：使用するLLMの名称 (UI表示にのみ使用するため何でも構わない)
* 説明：必要に応じてメモとして使用
* 最大トークン長：ダウンロードしたモデルの名称
* local LLM モデルタイプ：GGUF modelを選択
* 最大トークン長：GGUFファイルのディレクトリを入力
<br>

#### [次のページへ&emsp;＞](Benchmark.md)