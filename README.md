# flutter3_example

- Flutter関連のインストールが一切されていない状態のPCにfvmを使用したFlutter環境を構築したときに動作確認用に作成したFlutterプロジェクトです
- 開発はVSCodeで行うためAndroidStudioについてインストールせずに[sdkmanager](https://developer.android.com/studio/command-line/sdkmanager?hl=ja)を使用したコマンドライン操作からのAndroidSDKのインストールを実施しています
- Javaについてこのプロジェクトを動かすのに8から21に更新しています
  - FlutterプロジェクトのGradleとJava21が対応していなかったため、`android/gradle/wrapper/gradle-wrapper.properties`のみプロジェクト作成時の状態から書き換えています
- Qiitaに以下の記事として作業内容をまとめています
  - [WindowsPCにfvmを使用したFlutter開発環境を構築し、実機デバッグまで持っていく備忘録](https://qiita.com/imo_tikuwa/items/b46bc571e6e913115f04)