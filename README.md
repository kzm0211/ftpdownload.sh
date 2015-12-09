# ftpdownload.sh

### 作成日
2015年12月9日

### 説明
FTPコマンドしか使用できないレンタルサーバーなどで、ファイルのダウンロードを自動化するためのシェルスクリプトです。 
自動化といいつつ、対話式になっているので、都度FTPログイン情報でファイルのダウンロードも可能ですし、変数に情報を入力することでMacからファイルをダウンロードするように自動化することが可能です。

### システム要件
wgetが使用できる環境。 
MacとCentOSで動作確認済み。

### 使い方
1. ターミナルを起動
2. ./ftpdownload.shを実行
3. ログイン情報を入力
4. ダウンロードパスを入力

