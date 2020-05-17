# OBSの仮想カメラを用いる方法
なるべくハードウェア（製品）を追加で導入しないで，音声認識を活用する方法です．
この方法で実施するためのシステム構成は下記の図の通りになります．

![接続イメージのテンプレ](fig/template/Template_Using_OBS-JP.jpg)


なお，テンプレートのデータを配布していますので，各自マニュアル作成などに役に立てれば嬉しいです．
  - [JPG形式データ（画像）](fig/template/Template_Using_OBS-JP.jpg)
  - [AI形式データ（Illustratorなどで用いるデータ）](fig/template/Template_Using_OBS-JP.ai)


## 所属研究室にて用いたシステム構成
![システム構成](fig/Using_OBS_ThetaAkihisa-JP.jpg)

- 用いた機器リスト
  |機器名|目的|
  |:---:|:---|
  |[MacBook Pro 2019 13インチ](https://support.apple.com/kb/SP795?viewlocale=ja_JP&locale=ja_JP)|音声認識を活用するPC|
  |[Roland Rubix24](https://www.roland.com/jp/products/rubix24/)|USB Audio Interface|
  |[Google Pixel 4](https://store.google.com/jp/product/pixel_4)|Google 音声文字変換を用いるAndroid|
  |[TASCAM iXZ](https://tascam.jp/jp/product/ixz/top)|USB Audio InterfaceからAndroidに接続するための変換インターフェース|
  |[SIGMA fp](https://www.sigma-global.com/jp/cameras/fp-series/)|自分の様子を撮影するカメラ|

  
## 接続様子
1. 全ての機器を接続する
    
    1. MacBook ProにカメラのSIGMA fpを接続する
    
    1. iXZと接続したRubixを接続する
    
    1. AndroidスマホのPixel 4にiXZを接続する

1. Web会議システムのZoomを起動する
    
    1. 音声認識の音声文字変換を起動する
    
    1. OBSを起動し，仮想カメラ機能を用いて，Pixel 4の画面を収録する

    
    
