# MaBeeeAndroidSDK

MaBeeeAndroidSDKはMaBeeeをAndroidから使用するためのSDKです。

- [MaBeeeについてはこちらからどうぞ](http://mabeee.mobi/)

## 注意

- 現在のところMaBeeeはiOSアプリ、Androidアプリからの使用のみサポートされています。
- こちらのMaBeeeAndroidSDKはまだ正式リリースではなく、現在のところサポート対象ではありません。
- ご使用の際はその旨ご理解の上、自己責任でお願い致します。

## MaBeeeAndroidSDK概要

- MaBeeeAndroidSDKはMaBeeeをAndroidから使うためのライブラリです。
- [MaBeeeiOSSDK](https://github.com/novars-jp/MaBeeeiOSSDK)を先行して開発しています。同じ機能が使用できます。

## チュートリアル・サンプルプロジェクト

- GitHubでサンプルプロジェクトを公開しています。
- すぐに動かすか、説明を読むとイメージがつかめると思います。

### [FirstMaBeeeAndroid](https://github.com/novars-jp/FirstMaBeeeAndroid)

- とりあえず最も簡単にMaBeeeを使ってみるのが目的のプロジェクトです。
- MaBeeeの出力をスライダーで変更できます。
- ドキュメント準備中

### [UpdatePropertiesAndroid](https://github.com/novars-jp/UpdatePropertiesAndroid)

- RSSI, Battery voltageの値を取得、更新するサンプルです。
- プロパティ以外の更新通知についても説明します。
- ドキュメント準備中

### [ScanUIAndroid](https://github.com/novars-jp/ScanUIAndroid)

- スキャン・接続・切断などをするサンプルです。
- UIの細かい部分以外は、SDKに含まれるScanActivityと同じものを実装しています。
- ドキュメント準備中

## MaBeeeAndroidSDKのインポート

AndroidStudioのbuild.gradeに以下を追加するとインポートされます。

```gradle
repositories {
    maven { url 'http://raw.github.com/novars-jp/MaBeeeAndroidSDK/master/repository/' }
}
```

```gradle
dependencies {
    compile 'jp.novars.mabeee.sdk:sdk:1.5.1'
}
```

## クラスの説明

- [JavaDoc](http://developer.novars.jp/mabeee/android/javadoc/)
- [App](http://developer.novars.jp/mabeee/android/javadoc/jp/novars/mabeee/sdk/App.html)
- [Device](http://developer.novars.jp/mabeee/android/javadoc/jp/novars/mabeee/sdk/Device.html)
- [ScanActivity](http://developer.novars.jp/mabeee/android/javadoc/jp/novars/mabeee/sdk/ui/ScanActivity.html)
