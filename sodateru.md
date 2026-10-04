# プライバシーポリシー

**2048｜ランキングで競う数字パズル**

最終更新日：2026年10月4日
アプリ名：2048｜ランキングで競う数字パズル(2048｜Ranking Number Puzzle)

## 1. はじめに

このプライバシーポリシー(以下、「本ポリシー」)は、2048｜ランキングで競う数字パズル(以下、「本アプリ」)における利用者の情報の取り扱いについて定めるものです。

本アプリは、数字のタイルを合体させて遊ぶパズルゲームです。遊ぶと経験値がたまり、スコアをランキングで競うことができます。

## 2. アカウント登録

本アプリは、アカウント登録を必要としません。メールアドレス、氏名、電話番号などの個人を特定する情報を取得することはありません。

ランキングで利用者を区別するため、Google LLCが提供する Firebase Authentication の匿名認証を利用し、端末ごとに無作為の識別子を発行します。この識別子から個人を特定することはできません。

**アプリを削除すると、この識別子は新しいものに変わります。** そのため、アプリを入れ直すとランキングでは別の利用者として扱われ、以前の記録を引き継ぐことはできません。

## 3. ランキングのために送信する情報

ランキングに参加する場合(名前を決めた場合)に限り、次の情報を Google LLC が提供する Cloud Firestore に送信し、保存します。

- 利用者が決めたランキング用の名前(12文字まで)
- スコア、そのとき作った最大のタイル、レベル
- レベル、経験値、自己ベスト(記録の写し)
- 匿名の識別子、記録した日時

ランキング用の名前とスコア、レベルは、**ほかの利用者に表示されます**。名前には、本名など個人を特定できる情報を入れないでください。

名前を決めなければ、これらの情報は送信されません。ランキングを使わなくても、ゲームはすべて遊べます。

### 3.1 名前の通報

ランキングに不適切な名前がある場合、利用者はその名前を通報できます。通報すると、対象の名前、対象の識別子、通報した利用者の識別子、日時が送信されます。開発者は内容を確認し、不適切な名前を別の名前に置き換えることがあります。

## 4. 端末に保存する情報

次の情報は、利用者の端末内に保存されます。

- レベル、経験値、自己ベスト
- 遊んでいる途中の盤面
- ランキング用の名前
- 音としんどうの設定
- まだ送信できていないスコア

Android では、これらの情報が Google のバックアップ機能(端末の設定で有効にしている場合)の対象になります。アプリを入れ直したとき、レベルなどが元に戻ることがあります。

## 5. 利用状況の解析

本アプリは、機能の改善のため、Google LLC が提供する Google Analytics for Firebase を利用しています。次のような情報が、個人を特定しない形で送信されます。

- アプリの起動、画面の表示、1回のプレイの終了(モード、スコア、レベル)
- 端末の機種名、OSのバージョン、アプリのバージョン、言語、おおよその地域

**本アプリは、広告ID(IDFA、Android の広告ID)を取得しません。**

## 6. 不具合の記録(クラッシュレポート)

本アプリは、アプリが異常終了した場合の原因調査のため、Google LLC が提供する Firebase Crashlytics を利用しています。異常終了が発生した箇所のプログラム上の位置、端末の機種名、OSのバージョン、アプリのバージョンが送信されます。

## 7. 不正な利用の防止

本アプリは、正規のアプリからの通信であることを確かめるため、Google LLC が提供する Firebase App Check を利用しています。この確認のため、Apple の DeviceCheck、Google の Play Integrity の仕組みを通じて、端末とアプリの正当性に関する情報が Apple および Google に送信されます。

## 8. 広告

本アプリは、広告配信を行いません。

## 9. 第三者への提供

開発者は、法令に基づく場合を除き、取得した情報を第三者に提供、販売することはありません。上記の Google LLC のサービスにおける情報の取り扱いについては、Google のプライバシーポリシーをご確認ください。
https://policies.google.com/privacy

## 10. データの削除

- 端末に保存された情報は、アプリを削除すると削除されます。
- ランキングに送信した情報(名前、スコアなど)の削除を希望する場合は、下記のお問い合わせ先までご連絡ください。確認のうえ削除します。

## 11. 子どもの利用について

本アプリは、すべての年齢の方が利用できます。開発者は、子どもから個人を特定する情報を意図的に取得することはありません。

## 12. 本ポリシーの変更

本ポリシーの内容は、必要に応じて変更することがあります。変更した場合は、このページに掲載します。

## 13. お問い合わせ

本ポリシーに関するお問い合わせは、下記までご連絡ください。

開発者：Seiu
連絡先：info.mobileappsengine@gmail.com

---

# Privacy Policy (English)

**2048｜Ranking Number Puzzle**

Last updated: October 4, 2026

2048｜Ranking Number Puzzle ("the app") is a puzzle game in which you merge number tiles, earn experience points and compete on leaderboards.

- **No account registration.** The app does not collect your email address, real name or phone number. To tell players apart on the leaderboards, the app uses Firebase Authentication (anonymous sign-in) to issue a random identifier for each installation. If you delete the app, the identifier changes and your previous leaderboard records cannot be carried over.
- **Leaderboards.** Only if you choose a leaderboard name, the app sends the following to Cloud Firestore (Google LLC): the name you chose (up to 12 characters), your score, largest tile and level, a copy of your level, experience points and best scores, the anonymous identifier, and the time. Your name, score and level are **shown to other players**. Please do not use your real name. If you do not choose a name, none of this is sent, and the game remains fully playable.
- **Reporting names.** You can report an inappropriate name. The reported name, its identifier, your identifier and the time are sent. The developer may replace inappropriate names.
- **Data stored on your device.** Level, experience points, best scores, the game in progress, your leaderboard name, sound and vibration settings, and scores not yet sent. On Android these may be included in Google's backup if you have enabled it.
- **Analytics.** The app uses Google Analytics for Firebase to improve the app (app opens, screen views, end of a game with mode, score and level; device model, OS version, app version, language and approximate region). **The app does not collect the advertising ID (IDFA / Android advertising ID).**
- **Crash reports.** The app uses Firebase Crashlytics (stack traces, device model, OS version, app version).
- **Abuse prevention.** The app uses Firebase App Check, which relies on Apple DeviceCheck and Google Play Integrity to verify that requests come from the genuine app.
- **Ads.** The app does not show ads.
- **Sharing.** The developer does not sell or share your information with third parties except as required by law. See Google's privacy policy: https://policies.google.com/privacy
- **Deletion.** Data on your device is deleted when you delete the app. To request deletion of leaderboard data, contact the address below.
- **Children.** The app is suitable for all ages and does not knowingly collect personally identifying information from children.

Developer: Seiu
Contact: info.mobileappsengine@gmail.com
