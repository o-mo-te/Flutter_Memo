# Flutter_Memo

### 1.公式サイトからSDKをダウンロード
> https://flutter.dev/

### 2.ダウンロードディレクトリのファイルを作成したディレクトリに解凍
> mkdir development // ディレクトリ作成
>
> cd development // 作成したディレクトリへ移動
>
> unzip ~/Downloads/flutter_macos_1.17.1-stable.zip // 解凍

### 3.パスを通す
> vi ~/.bash_profile // バッシュを開く
>
> export PATH="$PATH:$HOME/development/flutter/bin" // 環境変数を追加
>
> source ~/.bash_profile // 設定を反映
>
> which flutter // パスが通ったか確認("/Users/home_dir_name/development/flutter/bin/flutter"だったらOK)

### 4.依存性の確認
> flutter doctor
