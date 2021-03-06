# 2台のPCを用いる方法
音声認識を活用する用PC，自分が参加する用PCの2台で活用する方法です．
この方法で実施するためのシステム構成は下記の図の通りになります．

![接続イメージのテンプレ](fig/Template_Using_2pc-JP-Light.jpg)


なお，テンプレートのデータを配布していますので，各自マニュアル作成などに役に立てれば嬉しいです．
  - [JPG形式データ（画像）](fig/template/Template_Using_2pc-JP.jpg)
  - [AI形式データ（Illustratorなどで用いるデータ）](fig/template/Template_Using_2pc-JP.ai)


## 所属研究室にて用いたシステム構成
![システム構成](fig/Using_2pc_ThetaAkihisa-JP-Light.jpg)
![用いた機器のまとめ](fig/Sample/1-Before-Light.jpg)

- 用いた機器リスト
  |機器名|目的|
  |:---:|:---|
  |[MacBook Pro 2019 13インチ](https://support.apple.com/kb/SP795?viewlocale=ja_JP&locale=ja_JP)|音声認識を活用するPC|
  |[Roland Rubix24](https://www.roland.com/jp/products/rubix24/)|USB Audio Interface|
  |[Google Pixel 4](https://store.google.com/jp/product/pixel_4)|Google 音声文字変換を用いるAndroid|
  |[TASCAM iXZ](https://tascam.jp/jp/product/ixz/top)|USB Audio InterfaceからAndroidに接続するための変換インターフェース|
  |[logicool HD WEBCAM C270M](https://www.logicool.co.jp/ja-jp/product/hd-webcam-c270h#specification-tabular)|音声認識による文字起こしを収録するWebカメラ|
  
## 接続様子
1. 全ての機器を接続する
![](fig/Sample/1-After-Light.jpg)
    1. サブPCのMacBook ProにRubixを接続する  
      ![](fig/Sample/AudioInterface-Light.jpg)  
        1. MacBook ProとRubixをUSBケーブルで接続する（USB-TypeC 変換アダプタを用いました）
        1. 予め，iXZと接続するためのTRケーブルを差し込んでおく
    1. AndroidスマホのPixel 4にiXZを接続した上で，RubixとiXZを接続する  
      ![](fig/Sample/iXZ-Light.jpg) 
        1. ⅰのaで予め差し込んだTRケーブルでiXZに接続する
        1. AndroidスマホとiXZを4Pミニプラグで接続する（4Pミニプラグ to USB-TypeC 変換アダプタを用いました）
    1. サブPCにWebカメラのC270Mを接続する  
      ![](fig/Sample/WebCam-Light.jpg) 
        1. MacBook ProとC270MをUSBケーブルで接続する（USB-TypeC 変換アダプタを用いました）
        1. C270Mを三脚に設置し，Androidスマホ画面が入るように調整します   
        ※Androidスマホ画面が入るようにするために三脚などを工夫して用いることを推奨します
    

1. Web会議システムのZoomを起動する
    1. 音声認識の音声文字変換を起動する 
    ![](https://github.com/DigitalNatureGroup/Remote_Voice_Recognition/blob/master/case/fig/Sample/SelectSound-Light.gif) 
        1. スピーカーの出力装置を選択する  
            1. マイクのアイコンの右上にある**矢印**をクリックする
            1. スピーカーの部分にある，**オーディオインターフェースのRubix**を選択する
            1. 起動した音声文字変換の設定画面にて，オーディオインターフェースと接続されているか確認する
            
    1. Pixel 4の画面をWebカメラで収録する
    ![](https://github.com/DigitalNatureGroup/Remote_Voice_Recognition/blob/master/case/fig/Sample/SelectWebCamera-Light.gif) 
        1. ビデオの出力装置を選択する  
            1. ビデオのアイコンの右上にある**矢印**をクリックする
            1. 接続されている**C270M（USBカメラ）**を選択する
    
1. メインPCでZoomを起動して終わり
