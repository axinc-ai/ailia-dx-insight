# Ollamaを使用したカスタムLLM構築

## Ollamaのインストール

[https://ollama.com](https://ollama.com)よりOllamaをインストールしてください。<br>
![CustomLLM_10](img/CustomLLM_10.png)<br>

## Ollamaの起動（Windows）
1. インストールした「OllamaSetup.exe」を起動し、インストールをします。<br>
![CustomLLM_11](img/CustomLLM_11.png)<br>

1. インストールが完了したら、コマンドプロンプトを起動してパスが通っていることを確認します。<br>
コマンドプロンプトで`ollama --help`を実行し、次のようなヘルプ画面が表示されることを確認してください。<br>

```
Large language model runner

Usage:
  ollama [flags]
  ollama [command]

Available Commands:
  serve       Start ollama
  create      Create a model from a Modelfile
  show        Show information for a model
  run         Run a model
  pull        Pull a model from a registry
  push        Push a model to a registry
  list        List models
  ps          List running models
  cp          Copy a model
  rm          Remove a model
  help        Help about any command

Flags:
  -h, --help      help for ollama
  -v, --version   Show version information

Use "ollama [command] --help" for more information about a command.
```

## LLMのダウンロード
1. ローカルで動かしたいLLMを`ollama pull`のコマンドでダウンロードします。
例：Googleのgemma-2-9Bをダウンロードする場合、コマンドプロンプトに`ollama pull gemma2`と入力します。<br>
![CustomLLM_12](img/CustomLLM_12.png)<br>
  * 他のPCからもこのローカルLLMにアクセスしたい場合はコマンドプロンプトで`set OLLAMA_HOST=0.0.0.0`を実行し、OLLAMA_HOSTの環境を「0.0.0.0」に設定します。

2. コマンドプロンプトで`ollama serve`を実行することでLLMを起動させます。<br>
![CustomLLM_14](img/CustomLLM_14.png)<br>
  * 「Listening on [::]:11434」と表示されている場合は他のPCからもアクセス可能です。
  * 「Listening on 127.0.0.1:11434」の場合はそのPC内からのみアクセスできます。
ここの「11434」の数値がポート番号となり、aillia DX Insight内での設定に使用します。

## aillia DX InsightでカスタムLLMの登録
詳しい設定画面の呼び出し方は[こちら](CustomLLM.md)をご参照ください。<br>
![CustomLLM_02_03.png](/img/CustomLLM_02_03.png)<br>

* 名前：使用するLLMの名称 (UI表示にのみ使用するため何でも構わない)
* 説明：必要に応じてメモとして使用
* モデル：ダウンロードしたモデルの名称（今回の例ではgemma2）
* URL(*)：`ollama serve`で表示されたポートのURL（今回の例ではhttp://localhost:11434）
* 最大トークン長：gemma-2-9Bの場合、「8192」となります。
<br>

(*)未記入の場合、HTTPの接続エラーになります。<br>

## ダウンロードしたLLMの削除
LLMが容量を圧迫する場合や、間違えたモデルをダウンロードしてしまった場合、以下の手順でLLMを削除することができます。
1. コマンドプロンプトで`ollama list`を実行すると、ダウンロード済みのモデルが一覧で表示されます。
1. コマンドプロンプトで`ollama rm モデル名`を実行することでダウンロード済みのモデルを削除をすることができます。<br>
![CustomLLM_13.png](/img/CustomLLM_13.png)<br>


<br>

#### [次のページへ&emsp;＞](CustomLLM_FastChat.md)