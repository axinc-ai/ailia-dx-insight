# LMスタジオを使用したカスタムLLM構築
## LMスタジオのインストール
1. [https://lmstudio.ai/](https://lmstudio.ai/)よりLMスタジオをインストールします。<br>
![CustomLLM_03](img/CustomLLM_03.png)<br>

## カスタムLLMのダウンロード
1. LMスタジオを起動させ、画面中央にある検索バーからLLMを検索します。<br>
ここでは例として「DataPilot-ArrowPro-7B-KUJIRA-gguf」を使用してLLMを構築していきます。<br>
![CustomLLM_04](img/CustomLLM_04.png)<br>
1. 検索をすると画面右側に該当する検索候補が複数表示されます。<br>
目的のLLMを見つけたら「Download」をクリックしてモデルのダウンロードを開始します。<br>
![CustomLLM_05](img/CustomLLM_05.png)<br>

## カスタムLLMの立ち上げ
1. ダウンロード完了後、左サイドバー内にある「↔」ボタンをクリックして画面のモードを変更します。<br>
画面上部にある「Select a model to load」をクリックすると、プルダウンでダウンロード済みのLLMが一覧で表示されるので、ダウンロードしたモデルを選択します。<br>
![CustomLLM_06](img/CustomLLM_06.png)<br>
  * 画面中央付近にailia DX Insight内の設定で使用するカスタムLLMのURLが表示されます。（通常はlocalhost:1234に設定されます）<br>
![CustomLLM_07](img/CustomLLM_07.png)<br>
  * 画面右側「Model Inspector」内に記載の`context_length`の数値がailia DX Insight内の設定で使用する「最大トークン数」となります。<br>
![CustomLLM_08](img/CustomLLM_08.png)<br>

## aillia DX InsightでカスタムLLMの登録
詳しい設定画面の呼び出し方は[こちら](CustomLLM.md)をご参照ください。<br>
![CustomLLM_02_02.png](/img/CustomLLM_02_02.png)<br>

* 名前：使用するLLMの名称 (UI表示にのみ使用するため何でも構わない)
* 説明：必要に応じてメモとして使用
* モデル：ダウンロードしたモデルの名称
* URL(*)：カスタムLLMの立ち上げで表示されたURL（通常はlocalhost:1234に設定されます）
* 最大トークン長：カスタムLLMの立ち上げで表示された`context_length`の数値
<br>

(*)未記入の場合、HTTPの接続エラーになります。<br>

## ローカルLLMの処理速度を向上させる方法
画面右側の「Advanced Configration」内にある「GPU Settings」のパラメータ値を変更することでGPUメモリを使用する割合を変更することができます。<br>
GPU Offloadパラメータを最大に設定すると、GPUメモリを使用した高速処理をおこなうことができます。<br>
![CustomLLM_09](img/CustomLLM_09.png)<br>



<br>

#### [次のページへ&emsp;＞](CustomLLM_Ollama.md)