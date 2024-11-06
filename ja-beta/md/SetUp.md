# セットアップ
[ailia DX Insight 1.0から1.1へのアップデートがまだの方はこちらをご確認ください。](v1_1update.md)<br>

[ailia DX Insight 1.2のアップデート内容はこちらをご確認ください](v1_2update.md)

## ダウンロード
ailia DX Insightを<a href="https://ailia.ai/dx/" target="_blank">ダウンロード</a>して、zipを解凍します。
## インストーラの起動
Windowsの場合は、aillia_dx_insight.msixをダブルクリックしてインストーラを起動します。 macOSの場合は、ailia_dx_insight.dmgを右クリックして開くで起動します。<br>
![setup_00.png](/img/setup_00.png)<br>
## ライセンスもしくはコンフィグファイルの選択
初回起動時に「ライセンスもしくはコンフィグファイルを選択してください」とウィンドウに表示されます。ライセンスファイルをフォルダから選択します。<br>

起動に必要なライセンスファイルはmacOSの場合は[HOME]/Library/SHALO、windowsの場合は[ROOT]/ProgramData/SHALOに格納されます。<br>
![seyup_001](/img/setup_001.jpg)<br>
[コンフィグファイルを選択する](ConfigFile.md)ことでアプリケーションをカスタマイズすることができます。

## OpenAIのAPIキーの取得
OpenAIのWEBページでアカウント登録を行い、[OpenAIのAPIキーを取得します。](OpenAI_APIKey.md) OpenAIのAPIキーを入力しなくてもailia DX Insightは使用できますが、機能が制限されます。
## セットアップ
ライセンスもしくはコンフィグファイルを選択後、チュートリアル画面が表示されます。<br>
![setup_01.png](/img/setup_01.jpg)<br>
チュートリアルの最終画面にて、OpenAI APIキーの設定が可能です。
### OpenAI APIキーの設定
#### チュートリアルから設定する場合
1. チュートリアルの最後、「APIキーの設定」まで進みます。
1. 「OpenAI APIキー」の下にあるテキストボックスに、"sk-"から始まるOpenAI APIキーを入力します。<br>
![setup_02.png](/img/setup_02.jpg)<br>
1. 「完了」ボタンを押します。
#### 通常画面から設定する場合
1. 画面右上にある歯車アイコンを押します。<br>
![setup_03.png](/img/setup_03.png)<br>
1. 表示されたダイアログ内のテキストボックスに、"sk-"から始まるOpenAIのAPIキーを入力します。<br>
![setup_04.png](/img/setup_04.png)<br>
1. 「OpenAI」をクリックして、使用するchatGPTのバージョンを選択し、「閉じる」ボタンを押します。
### AIモデルのダウンロード
初回起動時のチュートリアルの終了後、AIモデルのダウンロードが開始されます。
ダウンロードの進捗は左のサイドバー下部にて確認できます。<br>
![download_model.png](/img/download_model.png)<br>
ダウンロード完了後、ailia DX Insightが使用可能となります。

<br>

#### [次のページへ&emsp;＞](v1_2update.md)