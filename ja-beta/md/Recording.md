# 議事録を取る
音声認識AIによって、手を動かすことなく議事録を取ることができます。

1. 画面左上のアプリメニューから「議事録作成」をクリックし、議事録画面を開きます。<br>
![useai_18.png](/img/UseAI_18.png)<br>
1. 画面右上の「会議場所」に会議場所を入力します。会議名を変更することもできます。<br>
![useai_19.png](/img/UseAI_19.png)<br>
1. 画面下部の「記録を開始」ボタンをクリックし、議事録の記録を開始します。<br>
![useai_20.png](/img/UseAI_20.png)<br>
- [音声認識に必要なAIモデルのダウンロード](VoiceInput.md)がお済みでない場合は、ダウンロードが開始されます。 ダウンロード完了後より利用可能となります。
1. 記録を終えるタイミングで、画面下部の「記録を停止」ボタンをクリックし、議事録を保存します。<br>
![useai_21.png](/img/UseAI_21.png)<br>
<br>

## 記録した議事録を確認する
議事録画面の左側に並ぶ議事録をクリックすると、記録した議事録を見ることができます。<br>
![useai_22.png](/img/UseAI_22.png)<br>
記録された文の右側にあるボタンをクリックすると、文の訂正ができます。<br>
![useai_23.png](/img/UseAI_23.png)<br>
また、画面下部の「記録を開始」ボタンをクリックすることで、再度議事録を記録することができます。

## 音声ファイルから議事録を作成する
クエリバーの「マイク」をクリックし、「ファイル」に変更した後に「記録を開始」を選択することで、音声ファイルから議事録を作成することができます。
![useai_21_01.png](/img/UseAI_21_01.png)

### 対応形式
議事録機能で標準で読み込めるファイルはwavファイルのみとなります。<br>別途、ffmpegをインストールすることで、mp3とmp4の読み込みが可能となります。<br>
Windowsの場合、環境変数のPATHの通った場所、もしくは下記のフォルダにffmpeg.exeを配置してください。<br>
<code>/Users/[UserName]/Documents(*)/ailia DX Insight/ffmpeg/</code><br>
macOSの場合、環境変数のPATHの通った場所、もしくは下記のフォルダのいずれかにffmpegを配置してください。<br>
<code>~/Documents(*)/ailia DX Insight/ffmpeg/</code><br>
<code>/usr/local/bin/</code><br>
<code>/opt/homebrew/bin/</code><br>
<code>/opt/local/bin/</code><br>

## 議事録を書き出す
議事録画面の左側に並ぶ議事録を右クリックし、「内容をエクスポート」を選択すると、議事録をtxt形式のファイルとして書き出すことができます。<br>
![useai_24.png](/img/UseAI_24.png)<br>

<br>

#### [次のページへ&emsp;＞](VoiceInput.md)
#### [一覧に戻る](UseAI.md)