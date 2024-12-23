# 弊社推奨LLM
GPUメモリ8GB未満～8GBのPCをご利用になる場合に推奨するLLMの一覧です。

## 超小型（0.5B ～ 4B）

### Qwen/Qwen2-0.5B -Instruct-GGUF（RAM使用量 1.17～1.35GB）
### Qwen/Qwen2-7B-Instruct-GGUF（RAM使用量 3.65～5.05GB）

特徴：
アリババクラウドが提供するLLMとなっております。
英語と中国語に加えて27の言語での学習データを活用し、自然言語理解、知識獲得、コーディング、数学、多言語対応などのベンチマークで高いパフォーマンスを示しています。
0.5Bと非常に小さなモデルですので、知識量は少ないですが低スペックのPCで使用する際に最適です。

<br>

### lmstudio-community/gemma-2-9b-it-GGUF（RAM使用量 5.69～10.07GB）
### bartowski/gemma-2-2b-it-GGUF（RAM使用量 1.79～3.05GB）

特徴：
Gemma2は、Googleの最先端のAIモデルであるGeminiと同じアーキテクチャを用いて構築されており、
軽量でありながら高い性能を発揮します。特に270億パラメータモデルは、そのサイズクラスで最高の性能を発揮し、
2倍以上の規模のモデルに匹敵する性能を実現しています。また、90億パラメータモデルも、
同サイズの他のオープンモデルを上回る優れた性能を示しています。
また、20億パラメータモデルはサイズに対してクラス最高のパフォーマンスとなりノートPC等での活用に適します。

<br>

### microsoft/Phi-3-mini-4k-instruct-gguf（RAM使用量 2.99GB）
### QuantFactory/Phi-3-mini-128k-instruct-GGUF（RAM使用量 2.08～4.54GB）

特徴：
Microsoft社が提供するLLMとなっております。3.8B（38 億個のパラメータ）という非常に小型なモデルながら、
2倍以上大きいモデルと同等の性能を有しています。
現在、4Kトークンと128Kトークンに対応した2つのモデルが公開されています。

<br>


## 小型（7B ～ 9B）

### mmnga/umiyuki-Umievo-itr012-Gleipnir-7B-gguf（RAM使用量 2.33～6.34GB）

特徴：
Japanese-Starling-ChatV-7B、Ninja-v1-RP-expressive-v2、Vecteus-v1、Japanese-Chat-Umievo-itr004-7b4
の4モデルを統合することで完成した日本語性能の高いLLMです。
	
<br>

### mmnga/DataPilot-ArrowPro-7B-KUJIRA-gguf（RAM使用量 2.26～3.49GB）
### mmnga/ArrowPro-7B-KillerWhale-gguf（RAM使用量 2.26～6.24GB）

特徴：
オープンソースのLLM「NTQAI/chatntq-ja-7b-v1.0」を基にして、
AIを活用したバーチャルYouTuber（AITuber）やAIアシスタントでの使用を目的に開発されました。
日本語での性能が高く、会話の品質においても高評価を得ています。
「ArrowPro-7B-KillerWhale」は「DataPilot/ArrowPro-7B-KUJIRA」の強化版という位置づけです。

<br>

### mmnga/Llama-3.1-8B-Instruct-gguf（RAM使用量 2.26～5.79GB）

特徴：
Meta社が提供するこれまでで最も先進的かつ高性能なLLMとなっております。
Llama 3.1は128Kのコンテキスト長、最先端のツール使用、推論機能の強化により、長文テキストの要約、
多言語会話エージェント、コーディング支援などの高度なユースケースをサポートしています。


<br>

### mmnga/Llama-3-ELYZA-JP-8B-gguf（RAM使用量 2.73～8.75GB）

東大松尾研究室発のAIカンパニー株式会社ELYZA(イライザ)が提供する日本語に特化したLLMとなっております。
Meta社のLlama 3 8B-Instructをベースに日本語の大規模データセットを用いて訓練され、
日本語の文法、語彙、文化的背景に精通しており、日本語特有の表現やニュアンスを正確に理解し、
洗練された日本語文章を生成することができます。

<br>


## 中型（それ以上）

### mmnga/ELYZA-japanese-Llama-2-13b-fast-instruct-gguf （RAM使用量 6.13～14.31GB）

特徴：
東大松尾研究室発のAIカンパニー株式会社ELYZA(イライザ)が提供する日本語に特化したLLMとなっております。
Meta社のLlama 2 13Bをベースに日本語の大規模データセットを用いて訓練され、
日本語の文法、語彙、文化的背景に精通しており、日本語特有の表現やニュアンスを正確に理解し、
洗練された日本語文章を生成することができます。

※まもなくLlama3ベースの新しいELYZAモデルが公開される予定です（2024年6月27日現在）

<br>

### lmstudio-community/gemma-2-27b-it-GGUF（RAM使用量 8～29.65GB）

特徴：
Gemma2は、Googleの最先端のAIモデルであるGeminiと同じアーキテクチャを用いて構築されており、
軽量でありながら高い性能を発揮します。特に270億パラメータモデルは、そのサイズクラスで最高の性能を発揮し、
2倍以上の規模のモデルに匹敵する性能を実現しています。また、90億パラメータモデルも、
同サイズの他のオープンモデルを上回る優れた性能を示しています。

<br>

### andrewcanis/c4ai-command-r-v01-GGUF（RAM使用量 8～10.27GB）

特徴：
Command-Rは、CohereForAIが作ったLLMで、35B（350億）のパラメータが含まれています。
このモデルは、大量の情報を元に、文章を生成したり、要約したり、質問に答えたりするのが得意です。
また、最大128kトークンの長文コンテキストに対応します。

<br>

### pmysl/c4ai-command-r-plus-GGUF（RAM使用量 8～212.71GB）

特徴：
Command R+は、command Rの強化版となる104B（1,040億）のパラメータを含むLLMです。
このモデルはエンタープライズ向けに優れた性能を発揮するようにデザインされ、
誰でも使えるオープンソースでありながら、GPT-4 Turboに迫る性能を持っています。
また、最大128Kの長文コンテキストに対応します。

（補足）command-r-v01／Command R Plusの利用について：
command-r-v01／Command R Plusは非営利目的での使用を前提に、モデルの変更や配布をおこなうLLMとなります。
商用利用（ビジネス利用）については、提供元の有償のAPIサービスを利用する必要がありますのでご注意ください。
有償APIの取得については右記サイトよりおこなっていただくことができます（https://cohere.com/command）

<br>

### Qwen/Qwen2-72B-Instruct-GGUF（RAM使用量 8～148.98GB）

アリババクラウドが提供するLLMとなっております。
英語と中国語に加えて27の言語での学習データを活用し、自然言語理解、知識獲得、コーディング、数学、
多言語対応などのベンチマークで高いパフォーマンスを示しています。
7B・72Bモデルについては、最大128Kトークンまでの長文コンテキストに対応します。

<br>

### mmnga/Llama-3.1-70B-Instruct-gguf（RAM使用量 7.66～9.07GB）

特徴：
Meta社が提供するこれまでで最も先進的かつ高性能なLLMとなっております。
Llama 3.1は128Kのコンテキスト長、最先端のツール使用、推論機能の強化により、長文テキストの要約、
多言語会話エージェント、コーディング支援などの高度なユースケースをサポートしています。


## 弊社推奨LLMについての補足
推奨LLMをLMスタジオで検索いただくと、以下のように、多くのモデルが表示されるかと思います。<br>
弊社では、サイズと性能のバランスに優れた4ビット量子化モデルの利用を推奨させていただいております。<br>
※具体的にはQ4_K_Mの記載のあるもの、またはそれに近しい量子化がされているものとなります。<br>
![CustomLLM_15](img/CustomLLM_15.png)<br>

## LinuxサーバーでLMスタジオを動作させる場合
LinuxサーバーでLMスタジオを動作させてailia DX insightから接続しようとした際に以下のようなエラーが表示された際はLinuxサーバーのファイヤーウォール設定でポートへのアクセスが禁止されている可能性があります。<br>
![CustomLLM_16.png](/img/CustomLLM_16.png)<br>
以下のコマンドでポートをアクセスを許可してください。<br>
`sudo ufw allow 1234/tcp`<br>
※上記のポート番号「1234」はLMスタジオで設定した番号に置き換えてください。<br>
![CustomLLM_17.png](/img/CustomLLM_17.png)<br>


<br>

#### [次のページへ&emsp;＞](RAG.md)