# Azure OpenAI Service
ailia DX insightは、文章の生成をChatGPTで行います。
OpenAI APIだけでなく、Azure OpenAI Serviceを介してChatGPTを利用することも可能です。
Azure OpenAI Serviceについての詳細は[こちら](https://learn.microsoft.com/ja-jp/azure/ai-services/openai/overview)をご覧ください。

## Azure OpenAI Serviceへの接続方法
### 設定画面の呼び出し
1. ailia DX insightの初期画面にて、右上の歯車アイコンをクリックして設定ウィンドウを表示させます。<br>
![setup_03.png](/img/setup_03.png)<br>
1. 「チャットAI」の項目の中にある「Azure OpenAI Service」をクリックし、「+追加」を選択します
![azure_01.png](/img/azure_01.png)<br>

### Azure OpenAI Serviceの設定を登録
AzureにデプロイしたChatGPTを登録するウィンドウが開きます。各項目を記入します。<br>
![azure_02.png](/img/azure_02.png)<br>
* 名前：UI表示に使用する名称
* APIキー: ChatGPTをデプロイしたリソースのAPIキー
* デプロイ名: ChatGPTをデプロイした際に設定したデプロイ名
* APIバージョン: 利用するAPIバージョン
    * [こちら](https://learn.microsoft.com/ja-jp/azure/ai-services/openai/reference)のページの、「サポートされているバージョン」が利用可能です。
* リソース名: ChatGPTをデプロイしたリソースの名前
    * ChatGPTをデプロイしたエンドポイント`https://RESOURCE_NAME.openai.azure.com/`のRESOURCE_NAMEにあたる部分です。
* モデル: デプロイしたモデル名(gpt-3.5-turbo等)
* 説明：必要に応じてメモとして使用

<br>

#### [次のページへ&emsp;＞](Gemini.md)