# FluctSDK

## APIドキュメント
FluctSDK-Androidの[Wiki](https://github.com/voyagegroup/FluctSDK-Android/wiki)を参照してください

# FluctSDK Release Note

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

## v3.2.2 以前の変更点について
* [改版履歴](https://github.com/voyagegroup/FluctSDK-Android/wiki/%E6%94%B9%E7%89%88%E5%B1%A5%E6%AD%B4)をご確認下さい

---
## LICENSE
Copyright fluct, Inc. All rights reserved.
