# カスタムLLMの設定
ailia DX Insightではローカルに構築したカスタムLLMを使用することで完全にオフライン環境でより安全な環境で動作させることができます。
カスタムLLMはailia DX Insightを動作させるPC上で動かすことも出来ますし、別のPCやサーバーなどで動作させているものに接続することも可能です。

## ChatGPTの互換サーバについて
ailia DX InsightはChatGPTの互換サーバに対応しています。<br>
ローカルLLMを使用する方法には以下のものがあります。
* [「LM Studio」を使用する方法](CustomLLM_LMstudio.md)
* [「Ollama」を使用する方法](CustomLLM_Ollama.md)
* [Pythonの「fastchat」を使用する方法](CustomLLM_FastChat.md)
* ailia DX Enterpriseを使用する方法（７月末リリース予定）
* ailia DX Insight内蔵ローカルLLMを使用する方法（８月末リリース予定）

## カスタムLLMのクライアントの設定
### 設定画面の呼び出し
1. ailia DX Insightの初期画面にて、右上の歯車アイコンをクリックして設定ウィンドウを表示させます。<br>
![setup_03.png](/img/setup_03.png)<br>
1. 「チャットAI」の項目の中にある「カスタム（OpenAIサーバー）」をクリックし、「+追加」を選択します。<br>
![CustomLLM_01.png](/img/CustomLLM_01.png)<br>

### カスタムモデル登録
カスタムモデル登録ウィンドウが開きます。各項目を記入します。<br>
![CustomLLM_02.png](/img/CustomLLM_02.png)<br>

* 名前：使用するLLMの名称 (UI表示にのみ使用するため何でも構わない)
* 説明：必要に応じてメモとして使用
* モデル：OpenAI互換APIサーバーで指定したモデル名 (gpt-3.5-turbo等)
* URL(*)：OpenAI互換APIサーバーが発信しているIPアドレスとport番号 (サーバー公開が–host 192.168.1.10 –port 8000の場合、http://192.168.1.10:8000)
* 最大トークン長：モデルの対応している最大トークン数を設定（4096以上の値を設定する、この値に応じてRAGのtopKが決定される）
<br>

(*)未記入の場合、HTTPの接続エラーになります。


<br>

#### [次のページへ&emsp;＞](CustomLLM_LMstudio.md)