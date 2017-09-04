# YMF825voiceeditor
YMF825 voice editor
arduino , VT100ターミナルで動作する YMF825用ボイスエディタ　スケッチです
YMF825 boardとArduino用に配線が必要です
下記を参照下さい

https://yamaha-webmusic.github.io/ymf825board/intro/

ScreenFMEdit.ino ymf825cont.ino 2つのファイルをArduino IDEで読み込んでスケッチを書き込んでください。

#　使い方

TeraTerm等VT100対応の端末ソフトで接続して下さい。

上下左右カーソルで各パラメータを選択して '+' '-' キーで値を増減させます。

'p' キーでテスト演奏(ドレミファソ)します

音色名は音色名の位置で'+','-'キーを押すと編集モードになります。

TAB　キーでコマンドモードへ切替ります。? プロンプトが出ます。
現在実装中コマンドは以下

'dmp' 音色パラメータHEXダンプ
'sv'  EEPROMへ音色を保存
'ld'  EEPROMから音色を読出
'cls' 画面再表示

#　その他

開発途中ですのでコード等随時修正・変更されますのでご了解下さい


