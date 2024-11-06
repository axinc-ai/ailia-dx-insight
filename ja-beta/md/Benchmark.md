# ベンチマーク機能
ailia DX Insight内の機能を使い、お使いのハードウェアでのAI実行環境のベンチマークを測定することができます。
数多くあるLLMの中からご利用されるLLMに迷った場合や、ご利用されるPCを決める際の指標にご活用ください。

1. 設定![gear](img/icon_gear.png)の「AI実行環境」の項目を選択します。<br>
![benchmark_01](img/benchmark_01.png)<br>
2. 実行環境を選択します。<br>
    画像検索および音声検索のクエリ処理、リランクはFP16に非対応のモデルです。それ以外の、文章登録、画像登録、音声登録、OCR、音声認識のモデルはFP16に対応しています。ベンチマーク対象のモデルはすべてFP16モデルとなっています。そのため、上の「実行環境（FP16対応モデル）」の項目を変更してください。<br>
    ![benchmark_02](img/benchmark_02.png)<br>
    GPUとCPUの選択肢が表示されるので、生成時に使用するものを選択します。<br>
    ![benchmark_03](img/benchmark_03.png)<br>
3. 生成の際にドキュメント登録にかかる時間が計測され、結果が表示されます。<br>
![benchmark_04](img/benchmark_04.png)<b>

<br>

#### [次のページへ&emsp;＞](Security.md)