# MusicProtocol
## Music Protocolへようこそ
Music Protocol(以下mpとする)とは、文字を音に、音を文字にするアプリケーションです。  
mpでは、独自の手法により他の人にはわからないようになっています。  
PyQtとtkinterのコラボレーションでなりたち、洗練されたGUIになっています。  
pythonでの制作ですが高速で実行されるようになっています。  
## 使い方
まず、MusicProtocol.exeを起動します。
### 文字を音に
起動すると左側に"Moji To Music"と書かれた場所があります。  
その下にあるテキスト入力欄に、音にしたい文字をいれてください。  
ここで注意点です。mpでは、漢字,句読点,全角でのビックリマークなどは非対応となっています。(半角でのビックリマークは対応しています。)  
そして次に、参照ボタンを押し、音を出力したいファイルを選択してください。  
最期に、出力ボタンを押すと先ほどのファイルにmidiファイルで保存されています。  
オプションで、パスワードや出力名(初期はoutput.midi)を設定できます。  
### 音を文字に
起動すると右側に"Music To Moji"と書かれた場所があります。  
まず、参照ボタンを押し、"Moji To Music"で出力されたmidiファイルを選択してください。  
出力ボタンを押すとボタン押したに出力された内容が表示されます。  
ここで、パスワードが設定されていると、出力内容のところに"パスワードが間違っています"が表示されます。  
上記が出た場合、パスワード入力欄に設定されたパスワードを入れてください。  
## 注意点
mpでは、漢字,句読点,全角でのビックリマークなどは非対応となっています。(半角でのビックリマークは対応しています。)  
"Moji To Music"で出力ボタンを押しても、出力されない場合は非対応文字や出力先がおかしくないかを調べてください。  
"Music To Moji"で文字がおかしい場合は、非対応文字が使われているので、確認してください。  
文字を音にする際、文が長いと音を文字に変換した時に、途切れる可能性があります。(改行可能です)  