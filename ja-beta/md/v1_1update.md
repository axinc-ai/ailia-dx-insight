# ailia DX Insight 1.0から1.1へのアップデートガイド
ailia DX Insight 1.1では、アプリケーションの電子証明書が更新されています。 Microsoftのインストーラであるmsixでは、電子証明書が更新された場合、別のアプリケーションとして認識されます。<br> （参考情報：<a target="_blank" href="https://github.com/microsoft/msix-packaging/issues/365">https://github.com/microsoft/msix-packaging/issues/365</a>）<br>そのため、ailia DX Insight 1.0から1.1にアップデートする場合、下記の手順に従い、旧バージョンをアンインストール後にインストールを行なってください。


## windowsの場合
スタートメニューからailia_dx_insightを選択し、右クリックでアンインストールを行います。<br>
（スタートメニューの中に見当たらない場合は「すべてのアプリ」の中からお探しください）
<img src="img/UpdateGuide_01.jpg" alt="UpdateGuide_01"><br>
ailia_dx_insight.msixをダブルクリックし、インストールを行います。<br>
<img src="img/UpdateGuide_02.png" alt="UpdateGuide_02.png"><br>
ユーザデータは<code>c:/Users/[UserName]/Documents(*)/ailia DX Insight</code>に保存されているため、保持されます。

（*）「マイドキュメント」と表示されることもあります。

## Macの場合
ailia_dx_insight.dmgを開き、ailia_dx_insight.appをApplicationフォルダにドロップすることで上書きします。

## コンフィグファイルの更新
ailia DX Insight 1.0でコンフィグファイルを使用している場合、コンフィグファイルの更新が必要です。ailia DX Insight 1.1の初回起動時に、下記のダイアログが表示されるため、コンフィグファイルのパスを設定してください。<br>
<img src="img/ConfigFile_02.png" alt="ConfigFile_02.png"><br>
コンフィグファイルの登録時以降にファイルに変更があった場合、リロードするか確認する下記のダイアログが表示されます。
「はい」を選択するとコンフィグファイルがリロードされ、変更が適用されます。<br>
<img src="img/ConfigFile_03.png" alt="ConfigFile_03.png"><br>
また、設定画面→コンフィグファイルより、手動でのコンフィグファイルの登録が可能です。<br>同画面にてコンフィグファイルの登録解除も可能です。<br>
<img src="img/ConfigFile_01.png" alt="ConfigFile_01.png"><br>


<br>

#### [次のページへ&emsp;＞](MainOperation.md)
