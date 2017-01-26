# MaBeeeAndroidSDK


## MaBeeeAndroidSDKのインポート

AndroidStudioのbuild.gradeに以下を追加するとインポートされます。

```gradle
repositories {
    maven { url 'http://raw.github.com/novars-jp/MaBeeeAndroidSDK/master/repository/' }
}
````
```gradle
dependencies {
    compile 'jp.novars.mabeee.sdk:sdk:1.1'
}
```
