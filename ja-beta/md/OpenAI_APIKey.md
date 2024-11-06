# OpenAI APIキーの取得方法
「ailia DX insight」内でOpenAIの機能を使用する場合にはOpenAIのAPIキーの取得が必要となります。<br>
また、OpenAIでは[レート制限](RateLimits.md)を設けている為、特に多人数で利用される場合はレート制限の上限を上げることをお勧めいたします。それには規定日数（最低7日～）の経過が必要となる為、お早目の対応が必要となります。

## OpenAIアカウントを作成する
1. [OpenAI Platform](https://platform.openai.com/docs/overview)から「Sign up」を選択します。<br>
![API_key_01](img/API_key_01.png)<br>
1. 案内に沿ってメールアドレス、パスワードを入力し、続けるを選択します。<br>
![API_key_02](img/API_key_02.png)<br>
1. 登録したメールアドレス宛に「OpenAI - Verify your email」という件名のメールが届くので、メールアドレスの確認を選択すると、ブラウザが起動します。<br>
![API_key_03](img/API_key_03.png)<br>
1. 起動されたブラウザで「氏名」「組織名（オプション）」「生年月日」を入力し、規約、プライバシーポリシーを確認後、同意するを選択します。<br>
![API_key_04](img/API_key_04.png)<br>


## 電話番号を登録する
APIキーを取得するにはショートメッセージを受け取ることのできる電話番号の登録が必要となります。

1. OpenAIのDocsページ右上の「Dashboard」を選択します。<br>
![API_key_05](img/API_key_05.png)<br>
1. 左側のメニューから「API keys」を選択して、「Verify your phone number to create an API key」という案内の横にある「Start varification」を選択します。<br>
![API_key_06](img/API_key_06.png)<br>
1. 電話番号を入力し、「Send code」を選択します。<br>
![API_key_07](img/API_key_07.png)<br>
1. 電話番号宛てにOpenAI認証コードがショートメッセージで届くので、次の画面で入力し、電話番号の登録が完了となります。<br>
![API_key_08](img/API_key_08.png)<br>


## APIキーを生成する
1. 「+ Create new secret key」を選択します。<br>
![API_key_09](img/API_key_09.png)<br>
1. 「Create new secret key」のウィンドウが表示されるので、任意の名称を入力してAPIキーを生成します。<br>
![API_key_10](img/API_key_10.png)<br>
1. APIキーが表示されます。<br>
※生成されたAPIキーが表示されるのは一度きりとなるので、この時点でコピーして保存しておくことをお勧めします。<br> 
![API_key_11](img/API_key_11.png)<br>


## 支払い情報を登録する
1. OpenAIのホーム画面右上のご自身のアカウントのアイコンをクリックし、「Your profile」を選択します。<br>　
![API_key_12](img/API_key_12.png)<br>
1. Settingsという画面になります。左のメニューから「Billing」を選択し、「Add payment details」を選択します。<br>
![API_key_13](img/API_key_13.png)<br>
1. 「What best describes you?」（あなたに当てはまるものを選択してください）というウィンドウが表示されます。「individual」（個人）か「Company」（会社）を選択します。<br> 
![API_key_14](img/API_key_14.png)<br>
1. 表示されるウィンドウにてカード情報/請求先住所を入力し、「Continue」を選択することで、支払い情報の登録が完了します。<br>
![API_key_15](img/API_key_15.png)<br>
* [月の支払い限度額を設定](Pricing.md)することで、APIにかかる費用を管理することができます。


#### [次のページへ&emsp;＞](Pricing.md)