# FluctSDK

## ドキュメント
[こちら](https://voyagegroup.github.io/FluctSDK-Doc/#/)を参照してください

# FluctSDK Release Note

## 2020/5/12

### FluctSDK v7.5.1

* 動画再生中にプロセスが終了した際、クラッシュする問題を修正

## 2020/4/28

### FluctSDK v7.5.0

* 動画インタースティシャル広告表示機能の追加

## 2020/4/22

### FluctSDK v7.4.3

* 動画リワード広告において不正なTracking URLをもつVASTを再生しようとしたときに動画再生が失敗する問題を修正

## 2020/4/15

### FluctSDK v7.4.2

* 動画リワード広告において接続先広告事業者の提供するデータに不正なURLが含まれる場合にクラッシュする問題を修正

## 2020/4/13

### FluctSDK v7.4.1

* 難読化の影響で動画リワード広告がクラッシュする不具合を修正

## 2020/4/9

### FluctSDK v7.4.0

* InputMethodServiceからのバナー広告表示機能を追加
* `FluctAdRequestTargeting`の`setUserId`をdeprecate

## 2020/3/26

### FluctSDK v7.3.4

* maio SDKバージョンを `1.1.11` へ更新
* Unity Ads SDKバージョンを `3.4.2` へ更新
* AdColony SDKバージョンを `4.1.4` へ更新

## 2020/3/25

### FluctSDK v7.3.3

* Android 7以降かつ古いWebView実装のインストールされた環境でバナー広告が正常に動作しない問題を修正
* Android 7以降かつ古いWebView実装のインストールされた環境で動画リワード広告のエンドカードが正常に動作しない問題を修正

## 2020/3/24

### FluctSDK v7.3.2

* Proguard設定の改善
* AppLovin SDKバージョンを `9.11.6` へ更新

## 2020/3/18

### FluctSDK v7.3.1

* 内部処理の改善

## 2020/3/16

### FluctSDK v7.3.0

* 動画リワード広告のRTB対応
	* 利用する際は[こちら](https://github.com/voyagegroup/FluctSDK-Android/wiki/%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AB%E5%8B%95%E7%94%BB%E5%BA%83%E5%91%8ASDK%E3%82%92%E8%BF%BD%E5%8A%A0%E3%81%99%E3%82%8B)のモジュールを追加してください。 

## 2020/3/09

### FluctSDK v7.2.3

* 内部処理の改善

## 2020/03/05

### FluctSDK v7.2.2

* AdMobメディエーションにおいてまれに発生するエラーによりクラッシュする問題を修正

## 2020/2/25

### FluctSDK v7.2.1

* 内部処理の改善

## 2020/2/17

### FluctSDK v7.2.0

* 320x100のバナー広告サイズの対応

## 2020/2/13

### FluctSDK v7.1.3

* 内部処理の改善

## 2020/2/7

### 動画リワードメディエーションアダプター v7.1.2

* Tapjoy SDKのバージョンを `12.4.2` へ更新

## 2020/2/4

### FluctSDK v7.1.1

* AndroidX環境にてJavaコードからバナーの利用を試みるとコンパイルエラーが発生する問題を修正

## 2020/2/3

### 動画リワードメディエーションアダプター v7.1.0

* Tapjoy SDKのバージョンを `12.4.1` へ更新

## 2020/1/28

#### 動画リワードメディエーションアダプター v7.0.1

* maioをAARファイルで導入した際に発生するコンパイルエラーを修正

## 2020/1/23

### FluctSDK v7.0.0

* 内部処理の改善

#### Google Mobile Ads向けカスタムイベント v7.0.0

* Google Mobile Adsの最低動作バージョンを17.2.0に変更
	* アダプターを動画リワードの新しいAPIに対応するため
	* Google Mobile Ads 17.0.0より、AndroidManifest.xmlにApp IDの記述が必要になりました。詳しくは[こちら](https://developers.google.com/admob/android/quick-start#update_your_androidmanifestxml)をご参照ください。
* ターゲティング設定と配信オプション設定をサポート

## 2020/1/22

### FluctSDK v6.2.0

* 動画リワード広告表示時のイベントをログ出力する機能を追加
* ProGuardルールファイルをAARファイルに同梱

## 2019/12/19

### FluctSDK v6.1.1

* 2階層以上ネストしたFragment内でバナー広告の表示を試みるとクラッシュする問題を修正

## 2019/12/18

### FluctSDK v6.1.0

* Google Mobile Ads向けカスタムイベント v6.1.0をサポート
* MoPub向けカスタムイベント v6.1.0をサポート

#### Google Mobile Ads向けカスタムイベント v6.1.0

* バナー広告用カスタムイベントの対応

#### MoPub向けカスタムイベント v6.1.0

* バナー広告用カスタムイベントの対応

## 2019/12/16

### FluctSDK v6.0.0

* バージョン規則を変更しました。本バージョン以降、全てのモジュールは同一のバージョン番号になります。
* 新しいバナー広告用API (FluctAdView) およびモジュールを追加
* 旧バナー広告用API (FluctAdBanner) を削除
* 広告ID取得失敗時のエラーを`PLAY_SERVICES_UNAVAILABLE`から`ADVERTISING_ID_UNAVAILABLE`に変更

## 2019/12/10

### FluctSDK v5.11.0

* MoPub向けカスタムイベントをサポート

### MoPub向けカスタムイベント v1.0.0

* リリース

## 2019/11/5

### FluctSDK v5.10.0

* 動画リワードメディエーションアダプター v2.10.0をサポート

### 動画リワードメディエーションアダプター v2.10.0

* AdColony SDKのバージョンを `4.1.0` へ更新
* Unity Ads SDKのバージョンを `3.3.0` へ更新
* AppLovin SDKのバージョンを `9.9.0` へ更新
* Tapjoy SDKのバージョンを `12.3.4` へ更新

### Google Mobile Ads向けカスタムイベント v1.6.0

* 動画リワードメディエーションアダプター v2.10.0をサポート

## 2019/10/16

### FluctSDK v5.9.2

* 動画リワードメディエーションアダプター v2.9.2をサポート

### 動画リワードメディエーションアダプター v2.9.2

* Tapjoyメディエーション利用時、一部イベントが非メインスレッドから通知される問題を修正

### Google Mobile Ads向けカスタムイベント v1.5.2

* 動画リワードメディエーションアダプター v2.9.2をサポート
* Tapjoyメディエーション利用時、通信が不安定な環境でまれにクラッシュする問題を修正

## 2019/10/3

### FluctSDK v5.9.1

* 内部処理の改善
* AndroidX環境での利用に関するドキュメントの追加

### 動画リワードメディエーションアダプター v2.9.1

* 内部処理の改善

### Google Mobile Ads向けカスタムイベント v1.5.1

* 内部処理の改善

## 2019/9/18

### FluctSDK v5.9.0

* 動画リワードメディエーションアダプター v2.9.0をサポート
* 内部処理の改善

### 動画リワードメディエーションアダプター v2.9.0

* AdColony SDKのバージョンを `3.3.11` へ更新
* AppLovin SDKのバージョンを `9.8.4` へ更新
* maio SDKのバージョンを `1.1.10` へ更新
* Tapjoy SDKのバージョンを `12.3.1` へ更新
* Unity Ads SDKのバージョンを `3.2.0` へ更新
* AdCorsa SDKのバージョンを `2.0.0` へ更新


### Google Mobile Ads向けカスタムイベント v1.5.0

* 動画リワードメディエーションアダプター v2.9.0をサポート

## 2019/9/10

### FluctSDK v5.8.0

#### 変更

* ターゲティング年齢の内部処理を改善
* SDK配布リポジトリURLを変更
* 詳細は [SDKの導入方法](https://github.com/voyagegroup/FluctSDK-Android/wiki/SDKの導入方法) を参照してください

### 動画リワードメディエーションアダプター v2.8.0

#### 変更

* SDK配布リポジトリURLを変更

### Google Mobile Ads向けカスタムイベント v1.4.0

#### 変更

* SDK配布リポジトリURLを変更

## 2019/8/23

### FluctSDK v5.7.0

#### 新規追加

* 子供向けの配慮に関する設定項目の追加
* EEAにおける合意年齢に関する設定項目の追加
* 詳細は [子供向けアプリの取り扱い](https://github.com/voyagegroup/FluctSDK-Android/wiki/%E5%AD%90%E4%BE%9B%E5%90%91%E3%81%91%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E5%8F%96%E3%82%8A%E6%89%B1%E3%81%84) を参照してください。

### 動画リワードメディエーションアダプター v2.7.0

#### 新規追加

* 子供向けの配慮に関する設定項目への対応
* EEAにおける合意年齢に関する設定項目への対応

### Google Mobile Ads向けカスタムイベント v1.3.0

#### 新規追加

* 子供向けの配慮に関する設定項目への対応
* EEAにおける合意年齢に関する設定項目への対応
* 詳細は [Google Mobile Ads SDKのカスタムイベントクラスの導入方法](https://github.com/voyagegroup/FluctSDK-Android/wiki/Google-Mobile-Ads-SDK%E3%81%AE%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%A0%E3%82%A4%E3%83%99%E3%83%B3%E3%83%88%E3%82%AF%E3%83%A9%E3%82%B9%E3%81%AE%E5%B0%8E%E5%85%A5%E6%96%B9%E6%B3%95) を参照してください。

## 2019/7/18

### FluctSDK v5.6.0
#### 変更

* 動画リワードメディエーションアダプター v2.6.0をサポート

### 動画リワードメディエーションアダプター v2.6.0

* AppLovin SDKのバージョンを `9.7.2` へ更新
* AppLovinのZone機能に対応

### Google Mobile Ads向けカスタムイベント v1.2.0

* 動画リワードメディエーションアダプター v2.6.0をサポート

## 2019/7/2

### FluctSDK v5.5.0
#### 変更

* Google Mobile Ads向けカスタムイベント v1.1.0をサポート

### 動画リワードメディエーションアダプター v2.5.0
#### 変更

* Google Mobile Ads向けカスタムイベント v1.1.0をサポート

### Google Mobile Ads向けカスタムイベント v1.1.0
#### 新規追加

* 動画リワード広告のカスタムイベントに対応


## 2019/6/26

### FluctSDK v5.4.0
#### 変更

* Google Mobile Ads向けカスタムイベント v1.0.0をサポート

### 動画リワードメディエーションアダプター v2.4.0
#### 変更

* Google Mobile Ads向けカスタムイベント v1.0.0をサポート
* maio SDKのバージョンを `1.1.8` へ更新
* nendSDKのバージョンを `5.1.1` へ更新
* Unity Ads SDKのバージョンを `3.1.0` へ更新

### Google Mobile Ads向けカスタムイベント v1.0.0
#### 新規追加

* インタースティシャル広告のカスタムイベントに対応


## 2019/5/29

### FluctSDK v5.3.4
#### 変更
* 収集するアドネットワーク固有のエラー情報を拡大
* VAST広告における配信エラー時のアドサーバーへの通知を改善
* 動画リワードメディエーションアダプター v2.3.4をサポート

### 動画リワードメディエーションアダプター v2.3.4
* AppLovinメディエーションにおいて予期せぬアプリからのインプレッション発生を予防する機能を追加

## 2019/5/22

### FluctSDK v5.3.3
#### 変更
* 動画リワードメディエーションアダプター v2.3.3をサポート

### 動画リワードメディエーションアダプター v2.3.3
#### 変更
* AdCorsaメディエーションで正常にリワードが付与されない問題を修正

## 2019/4/3

### FluctSDK v5.3.2
#### 変更
* 動画リワードメディエーションアダプター v2.3.2をサポート

### 動画リワードメディエーションアダプター v2.3.2
#### 変更
* maio SDKのバージョンを `1.1.7` へ更新
* nendSDKのバージョンを `5.1.0` へ更新
* Tapjoy SDKのバージョンを `12.2.1` へ更新

## 2019/2/27

### FluctSDK v5.3.1
#### 変更
* 動画リワードメディエーションアダプター v2.3.1をサポート
* サンプルアプリの軽微な改善

### 動画リワードメディエーションアダプター v2.3.1
#### 変更
* Tapjoy Limited Connectにおいて、意図せずパブリッシャ側のターゲティング情報が上書きされてしまう問題を修正
* ほか内部処理の変更および改善

## 2019/2/14

### FluctSDK v5.3.0
#### 変更
* 内部処理の変更および改善
* 動画リワードメディエーションアダプター v2.3.0をサポート

### 動画リワードメディエーションアダプター v2.3.0
#### 変更
* 内部処理の変更および改善

## 2019/2/4

### FluctSDK v5.2.1
#### 変更
* ネイティブ広告表示時にRejectedExecutionExceptionが発生する不具合を修正。

## 2019/1/30

### FluctSDK v5.2.0
#### 変更
* 軽微な内部処理の改善
* 動画リワードメディエーションアダプター v2.2.0 をサポート

### 動画リワードメディエーションアダプター v2.2.0
#### 変更
* TapjoyメディエーションのLimited Connectに対応

## 2019/1/21

### FluctSDK v5.1.0
#### 変更
* 動画リワードメディエーションアダプター v2.1.0 をサポート

### 動画リワードメディエーションアダプター v2.1.0
#### 新規追加
* AdCorsaメディエーション機能を追加

## 2018/12/17

### FluctSDK v5.0.0
#### 変更
* Play Services Baseのバージョンを `16.0.1` へ更新
* Play Services Ads Identifierのバージョンを `16.0.0` へ更新
* [配信オプション](https://github.com/voyagegroup/FluctSDK-Android/wiki/%E5%8B%95%E7%94%BB%E3%83%AA%E3%83%AF%E3%83%BC%E3%83%89%E5%BA%83%E5%91%8A%E5%AE%9F%E8%A3%85#%E9%85%8D%E4%BF%A1%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AE%E8%A8%AD%E5%AE%9A)としてアプリ内で複数の内容を設定した際に、例外が通知されるよう変更

### 動画リワードメディエーションアダプター v2.0.0
#### 変更
* AppLovin SDKのバージョンを `9.1.0` へ更新
* maio SDKのバージョンを `1.1.6` へ更新
* nendSDKのバージョンを `5.0.3` へ更新
* Unity Ads SDKのバージョンを `3.0.0` へ更新
* AdColony SDKのバージョンを `3.3.7` へ更新
* Tapjoy SDKのバージョンを `12.2.0` へ更新
* Play Services Adsのバージョンを `17.1.2` へ更新

## 2018/11/7

### FluctSDK v4.9.0

#### 変更
* 動画リワードメディエーションアダプター v1.3.0 をサポート

### 動画リワードメディエーションアダプター v1.3.0

#### 新規追加
* Tapjoyメディエーション機能を追加

## 2018/10/31

### FluctSDK v4.8.0

#### 変更
* 動画リワードメディエーションアダプター v1.2.0 をサポート

### 動画リワードメディエーションアダプター v1.2.0

#### 新規追加
* AdColonyメディエーション機能を追加

## 2018/10/17

### FluctSDK v4.7.0
#### 新規追加
* 広告表示用JavaScriptタグを用いた広告実装についてドキュメントおよびサンプルを追加

#### 変更
* `targetSdkVersion` やSupport Library等のバージョンを `28` へ更新

### 動画リワードメディエーションアダプター v1.1.2
#### 変更
* AppLovin SDKのバージョンを `8.1.4` へ更新
* maio SDKのバージョンを `1.1.5` へ更新
* nendSDKのバージョンを `5.0.2` へ更新
* Unity Ads SDKのバージョンを `2.3.0` へ更新

## 2018/9/21
### FluctSDK v4.6.0
#### 新規追加
* ネイティブ広告のサポートを追加
* ネイティブ広告のガイドライン・実装についてのドキュメントを追加
* Google Play Servicesを更新
* `play-services-ads-identifier` を依存関係に追加。

## 2018/5/29
### 動画リワードメディエーションアダプター v1.1.1
#### 不具合修正
* UnityAdsに動画リワード広告キャンペーンが存在しない場合、タイムアウトまで待ってしまうバグの修正

## 2018/5/07
### FluctSDK v4.5.2
#### 不具合修正
* FluctRewardedVideo.Listenerの `onClosed` の挙動を修正

## 2018/4/27
### FluctSDK v4.5.1
#### 不具合修正
* 広告配信のターゲティング情報を付与した場合、nendの動画リワード広告が配信出来ない不具合の対応

## 2018/4/17
### FluctSDK v4.5.0
#### 新規追加
* 動画リワード広告配信のターゲティングにユーザー属性を利用する機能を追加

### 動画リワードメディエーションアダプター v1.1.0
#### 新規追加
* 動画リワード広告配信のターゲティングにユーザー属性を利用する機能を追加

## 2018/3/27
### FluctSDK v4.4.1
#### 新規追加
* 動画リワード広告のサンプルにテスト用のグループIDとユニットIDを追加

#### 不具合修正
* 動画リワード広告の複数回読み込みが失敗する不具合の修正

### 動画リワードメディエーションアダプター v1.0.1
#### 不具合修正
* パッケージ名の修正

## 2018/3/20
### FluctSDK v4.4.0
#### 新規追加
* 動画リワード広告のサポートを追加
* 動画リワード広告の導入・実装についてのドキュメントを追加

#### 変更
* 対応OSバージョンを Android 4.1 Jelly Bean 以上に更新

### 動画リワードメディエーションアダプター v1.0.0
#### 新規追加
* 動画リワード広告のサポートを追加

## 2017/4/17
### FluctSDK v4.3.2
#### 変更
* 細かい不具合の修正

## 2017/4/10
### FluctSDK v4.3.1
#### 変更
* 広告表示前に画面を閉じるとクラッシュする不具合の対応

## 2017/4/4
### FluctSDK v4.3.0
#### 新規追加
* FluctAdBanner.ErrorTypeに、広告が取得できなかった場合の `NoAd` を追加
* サンプルにKotlin言語プロジェクトを追加

#### 変更
* 細かい不具合の修正

## 2017/1/24
### FluctSDK v4.2.0
#### 変更
* 対応OSバージョンを Android 4.0 Ice Cream Sandwich 以上に更新
* サンプルプロジェクトにListViewへの対応方法を追加
* 細かい不具合の修正

## 2016/12/13
### FluctSDK v4.1.0
#### 変更
* バナー広告の拡大表示に対応
* FluctAdBannerクラスの追加
* FluctViewをdeprecatedに変更

## 2016/11/01
### FluctSDK v4.0.1
#### 変更
* デバッグ情報取得効率化のため、内部処理を変更
* 広告リクエストを https で行うように変更

## 2016/10/17
### FluctSDK v4.0.0
#### 新規追加
* FluctView コールバック

#### 変更
* 主開発環境を Android Studio
* ライブラリファイル形式を Android Library (.AAR)
* ライブラリ提供方式を リモート maven リポジトリ
* FluctSDK クラスパス
* FluctInterstitial コールバック

---
## LICENSE
Copyright fluct, Inc. All rights reserved.
