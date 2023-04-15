# 橋田java案件IN予定のため再勉強PJです。（Java+PlayFrameWork）

## 環境構築

### 前提条件
- Eclipseがインストールされていること
- JDK8がインストールされていること
![javaの状態](img/java_status.png)

### 手順
- sbtのDL/Inst
  - [DLサイト](https://www.scala-sbt.org/download.html)
    - 備忘録：sbt-1.8.2.msi

- EclipseでPJのクローン

- cmdで下記実行
  - ``` cd [PJルート（myapp直下） ```
  - ``` sbt run ```
    ![sbtrun](img/serverup.png)

- ローカルホストにアクセス
  - [localhost:9000](http://localhost:9000)
  - ![localhost](img/localhost9000.png)

### [備忘録]PJ作成時のみ（クローンする場合は不要）
- プロジェクトの作成
  - cmdで下記実行
    - ``` cd [PJルート（myapp直下） ```
    - ``` sbt new playframework/play-java-seed.g8 ```

