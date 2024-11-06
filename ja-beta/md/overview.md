# 概要
ailia DX Insightは、ax株式会社および株式会社アクセルが提供する、企業のDXのためのAIスーパーアプリです。<br>
WindowsやmacOSにインストールするだけで誰でもAIを業務に活用可能です。<br>
大規模言語モデルに文章検索や画像検索、音声認識、企業内情報検索などailia独自のAIをプラスすることで、
AIを使った業務効率の改善が簡単に行えます。

![overview_01.png](/img/overview_01.png)

## 機能<div id=update06></div>
aillia DX insightでは下記の機能を使用可能です。各機能で使用されるモデルと実行環境は下記となります。

<div class="scroll_area" style="width:100%;max-width:800px;overflow-x:scroll;">
    <table style="width:800px;">
      <thead>
      <tr>
      <th>機能</th>
      <th>クラウドで動作</th>
      <th>端末上で動作</th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>文章検索（RAG）</td>
      <td>ChatGPT、Azure OpenAI、Gemini、Claude(* 準備中)（回答生成）</td>
      <td>ailia SDK（インデックス作成、ベクトル検索、Re-Rank機能）、カスタムLLM（回答生成）</td>
      </tr>
      <tr>
      <td>画像生成</td>
      <td>DALLE</td>
      <td>StableDiffusion(* 準備中)</td>
      </tr>
      <tr>
      <td>要約・アイデア出し</td>
      <td>ChatGPT、Azure OpenAI、Gemini、Claude(* 準備中)（回答生成）</td>
      <td>カスタムLLM</td>
      </tr>
      <tr>
      <td>翻訳</td>
      <td>ChatGPT、Azure OpenAI、Gemini、Claude(* 準備中)（回答生成）</td>
      <td>ailia SDK、カスタムLLM</td>
      </tr>
      <tr>
      <td>画像検索</td>
      <td>-</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>音声入力</td>
      <td>-</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>音声認識</td>
      <td>Whisper Large V3 Turbo</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>議事録</td>
      <td>Whisper Large V3 Turbo</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>OCR</td>
      <td>Azure AI Vision(* 準備中)</td>
      <td>ailia SDK</td>
      </tr>
      </tbody>
    </table>
</div>

## 対応ファイルフォーマット
ailia DX Insightがサポートしている形式は下記となります。

###### 一般的なオフィス系ドキュメントフォーマット
`pdf, doc, docx, txt, md, xlsx, csv, tex, css, html`

###### プログラム系ドキュメントフォーマット
`c, cpp, json, java, py, rb, php`<br>

<br>
`js, swift, .kt, rust, dart, lua`は設定![icon_gear](/img/icon_gear.png)/インデックスから追加することができます。<br>

![overview_02.png](/img/overview_02.png)


###### 画像フォーマット
 `'png', 'jpg', 'jpeg'`

###### 音声フォーマット
`'wav'`

## ファイルの保存先
ailia DX Insightは下記のフォルダにデータベースやモデルファイルを保存します。このフォルダを削除することで、ailia DX Insightを初期化することができます。<br>
`Windows : c:/Users/[UserName]/Documents(*)/ailia DX Insight`<br>
`macOS : ~/Documents(*)/ailia DX Insight`<br>

<br>
(*)Windowsでは「マイドキュメント」、Macでは「書類」と表示されることもあります。

<br>

#### [次のページへ&emsp;＞](SetUp.md)