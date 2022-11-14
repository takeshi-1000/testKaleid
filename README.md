https://github.com/harlanhaskins/Kaleidoscope-Swift/tree/master/Part4/Sources/Kaleidoscope から移植して、
依存しているモジュールのバージョンも変更して、一旦build通るところまで対応

※ https://github.com/harlanhaskins/Kaleidoscope-Swift では、LLVMSwiftの過去のバージョンが採用されており、ビルド時にモジュール内でエラーが出たため
一旦モジュール内のエラーが出ない、最新のものを取り込み、最新とのインターフェースの差分部分をコメントアウトしてBuildを一旦通過させた。
