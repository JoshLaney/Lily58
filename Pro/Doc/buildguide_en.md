# Lily58 Pro Build Guide [WIP]


## Parts Needed

| Name |  Quantity  |  Comments  | Picture |
|--------|-------|-------|-------|  
|Lily58 PCB | 2 Boards ||
|Lily58 Case|1 Set, 4 Pieces||
|[ProMicro](https://yushakobo.jp/shop/promicro-spring-pinheader/)|2|It is recommended to use the separately sold [Spring Pin Header] (https://yushakobo.jp/shop/a01mc-00/), which can replace ProMicro due to the reduced number of solderings and fragile connectors. It is included in the items sold at the playhouse studio||
|Swithces (CherryMX,kailh choc)|58|Only supports MX or Choc switches||
|[Switch Sockets](https://yushakobo.jp/shop/)|58|Nesseasry for mounting swithces||
|Keycaps|58|1.5U used for thumb keys||
|Diodes 1N4148W|58|||
|Tact (reset) switch|2|||
|TRRS Jack |2|||
|M2 standoffs |10,4|Choc:4mm,MX:7mm||
|M2 screws|28|||
|TRRS Cable|1|3.5mm audio cable/AUX cable. 4 pin is required||
|MicroUSB Cable |1|Magnetic Style recommened due to poor durability of connector on the Pro Micro||
|OLED Display|2|||

## First Steps
The Pro version has color variations, and the photos in this build guide are implemented with the Black version, but even with the White version, the implementation method does not change at all, so ignore the color and proceed. Depending on the color and release date, there may be from a different batch than the photo, but there is no difference in operation. 
  
**In addition, the case of the Black version is a scratch-resistant paint (resist), and can be scratched during transportation. Please note in advance that this will be the nature of the product.
In addition, please be careful as it will be scratched if it hits or rubs a hard thing after assembly.**

The PCB is reversible . **Parts will be mounted on each side.**

Mark the surface with masking tape etc. to make it easy to understand the back and front.
![51965707-c6841d80-24ad-11e9-8e00-b7113b20fb67](https://user-images.githubusercontent.com/6285554/51967194-0947f480-24b2-11e9-860f-e45197cf0983.jpg)
![unadjustednonraw_thumb_2ccb](https://user-images.githubusercontent.com/6285554/53638905-1d2a7600-3c6b-11e9-9a39-a121c9b407b6.jpg)


## Install the Diodes
These diodes are surface mount. They are in a reel, and it's easy for them to fly  everywhere when opening it, so open it slowly and carefully. (It is easy to understand at when assembling)
![2019-01-26 13 52 14](https://user-images.githubusercontent.com/6285554/51967206-1238c600-24b2-11e9-9617-01d8755c5b7f.jpg)

Mount the diodes on the **back side** of the PCB.  

Solder with the diode with the line pointing in the direction of the triangle bar on the silkscreen as shown in the following figure. If the direction is incorrect, the key will not respond.
![2019-02-28 14 08 00](https://user-images.githubusercontent.com/6285554/53542561-53300300-3b62-11e9-8b83-5758ce400491.png)

Apply preliminary solder (melt the solder a little on the substrate) on one of the diode pads on the PCB.
![2019-01-26 13 48 26](https://user-images.githubusercontent.com/6285554/51965724-cbe16800-24ad-11e9-8afc-17c5b8eebda8.jpg)

Then use tweezers to solder one side of the diode to the pre-soldered pad.
![2019-01-26 13 54 10](https://user-images.githubusercontent.com/6285554/51967222-1cf35b00-24b2-11e9-9624-26ff45f7bc9b.jpg)
Then solder the other side.
  
When all diodes have been soldered, check for missing spots.
![2019-01-26 14 18 25](https://user-images.githubusercontent.com/6285554/51967226-1f55b500-24b2-11e9-93f5-2802156a4d10.jpg)



## Solder the Sockets
The sockets are attached on the back side of the PCB (the same side as the diodes)

As with the diode, pre-solder on one side of the socket pad, place the socket, and hold it in place with tweezers or hand. (Please be careful not to burn yourself when holding down by hand.)
As in the picture, install MX sockets in the upper section and Choc sockets on the lower section.
![socket](https://user-images.githubusercontent.com/6285554/57197682-3de1b580-6fa5-11e9-90b1-fca894e1e7d2.png)

For parts that require force, firmly solder both pads and check for freeness.
![2019-01-26 14 38 04](https://user-images.githubusercontent.com/6285554/51967230-2250a580-24b2-11e9-94ce-591746c49f50.jpg)


## Solder the TRRS connectors and rest switches.
Mount on the top of the PCB (the side with the sticker on the mark).
Attach the parts and fix them temporarily with masking tape. Turn over the board, solder it, making sure that the TRRS jack and reset switch do not float from the board.
![2019-01-26 14 39 53](https://user-images.githubusercontent.com/6285554/51967627-2c26d880-24b3-11e9-9764-aa51975c1eef.jpg)
![2019-01-26 14 43 23](https://user-images.githubusercontent.com/6285554/51967628-2cbf6f00-24b3-11e9-96e6-8f003c53d57b.jpg)


## Attach the OLEDS
Solder and jumper the four jumper terminals in the ProMicro section of the surface.
Attach the connector for OLED. Do not use a lot of solder, as it is easy for solder to flow into the connector.
![unadjustednonraw_thumb_2db2](https://user-images.githubusercontent.com/6285554/53293031-d45c6280-380f-11e9-8f1c-1c167b27cfd3.jpg)

Insert the OLED pins into the socket, place the OLED module on it, and solder the four pins.


## Install the Pro Micros  
The pin header enclosed in the bag of ProMicro is not used. In the case of a kit purchased at a playhouse studio, a spring pin header is included, so use that.  
![IMG_2662](https://user-images.githubusercontent.com/6285554/57210525-f5171480-7017-11e9-9d92-3a345d53db94.jpg)  
When attaching with a spring pin header (through hole), solder it according to the method described in the Helix build guide and then attach it to Lily 58 PCB [Helix Guide](https://github.com/MakotoKurauchi/helix/blob/master/Doc/buildguide_en.md)

**Check the outlined column of the PCB and insert the pins into the PCB.** Please be careful as the place to insert for the right and left sides is different. 

![ProMicro_PCB](https://user-images.githubusercontent.com/6285554/48819671-6a599a80-ed94-11e8-8e5d-6a6abca326a7.png)


## Attach the spacers
Attach four 10 mm round spacers to the holes near ProMicro.
It is easiest to insert a screw from the back of the board and attach the spacer from the top.
![2019-01-26 15 02 38](https://user-images.githubusercontent.com/6285554/51967859-c0913b00-24b3-11e9-966c-f3621ed398e5.jpg)

The masking tape for the front and back identification applied in the beginning should now be removed.

## Attach the swithces
Attach the top plate spacer for alignment. (MX: 7 mm Choc: 4 mm)
![2019-01-26 14 56 05](https://user-images.githubusercontent.com/6285554/51967395-912dfe80-24b2-11e9-9cc7-b4520063f36c.jpg)
![2019-01-26 14 56 24](https://user-images.githubusercontent.com/6285554/51967376-83787900-24b2-11e9-82a0-850556daccfc.jpg)  

Attach four key switches to the top plate. (In the case of Choc, 2 places may be easier to install)
![2019-01-26 14 58 48](https://user-images.githubusercontent.com/6285554/51967380-87a49680-24b2-11e9-80b9-a45564afc8cf.jpg)
  
Insert the switch into the board for alignment, and align it.
![2019-01-26 15 01 12](https://user-images.githubusercontent.com/6285554/51967478-c3d7f700-24b2-11e9-9f2f-4e75efc215a1.jpg)


After confirming that there are no bends in the switch pins, etc., you can attach it firmly from the middle row and attach it outward finally.
Be careful because the KailhBOX switch and Choc switch need some power for installation.
After installation, push the switch again to make sure that installation is complete.
![2019-01-26 15 10 06](https://user-images.githubusercontent.com/6285554/51967840-b66f3c80-24b3-11e9-8f50-6d8d31fe85e5.jpg)

## Install ProMicro Protective Acrylic
Peel off the acrylic protective paper for ProMicro upper part and attach it.
**Mount with the wider side outwards**. Screw the top.
![plate](https://user-images.githubusercontent.com/6285554/48837829-c4288780-edc9-11e8-8efb-6714d8e68e92.png)

![2019-01-26 15 21 15](https://user-images.githubusercontent.com/6285554/51967842-b8d19680-24b3-11e9-8402-85180ce10403.jpg)

## Write the Key Map
Set up qmk following the link here: [qmk](https://docs.qmk.fm/#/getting_started_build_tools) (WIndows:MSYS2 Mac,Linux:avrdude)

QMK ToolboxThere is no need to build an environment, and writing can be done using a GUI. (It is recommended to build the above writing environment when customizing)
[qmk/qmk_toolbox](https://github.com/qmk/qmk_toolbox/releases)  

 
Execute the following in qmk_firmware folder hierarchy to write default key map of the Lily58

    sudo make lily58:default:avrdude  


**Detecting USB port, reset your controller now...** と表示されたらキーボード上のリセットボタンを押すと書き込みが始まります。  
上記の要領でもう片方のキーボードにも同じように書き込みを行って下さい。 

Defaultキーマップは以下のようになっています。  
macOS/USキーボード 環境で使用する前提で作られているキーマップ配置なのでJIS配列に変更や英/かな切り替えなどのキーマップを追加するなど使用者の方に合わせたキーマップを作ってみてください。自作キーボードの醍醐味です。  
![lily58_default](https://user-images.githubusercontent.com/6285554/47273241-38ee8300-d5cc-11e8-9099-10c1b35e24fc.png)

## 動作確認
左右をTRRSケーブルで接続し左側のProMicro(デフォルトキーマップの場合)にMicroUSBケーブルを接続しキーが反応するかを確認して下さい。  
裏面にゴム足を4箇所取り付けて完成です。お疲れ様でした。
![2019-01-26 15 24 52](https://user-images.githubusercontent.com/6285554/51967992-24b3ff00-24b4-11e9-8cd3-1e679094682f.jpg)
![unadjustednonraw_thumb_2ddc](https://user-images.githubusercontent.com/6285554/53640050-6203dc00-3c6e-11e9-9434-5591ed3e414f.jpg)


## 困ったときは
### Q.1列(複数列)又は1行(複数行)キースイッチが反応しない
A.ProMicroのはんだ付け、取り付けしっかりとできてない場合があります。再度確認し、必要に応じて再度はんだ付け、取り付けを行ってください。

### Q.キースイッチが単体で反応しない
A.キースイッチの差し込み、ソケット又はダイオードのはんだ付けに問題がある可能性があります。

キースイッチの差し込みの場合  
1度キースイッチを抜いてからピンの曲がりなどが無いかを確認して再度強く押し込んで取り付けてください。

ソケットのはんだ付けの場合  
問題のソケットのはんだ付け箇所に再度はんだごてを当て必要に応じてはんだを流してください。  
  
ダイオードのはんだ付けの場合
問題のダイオードの向きを確認してください。間違っていた場合は外してはんだ付けし直してください。
はんだ付けが足りない場合は再度はんだ付けを行ってください。

### Q."@"や"["などで入力した記号と違う記号が入力される(Windows等)
OS上でキーボードの認識がJISキーボードとして認識されているためLily58(USキーボード扱い)で入力した際に別の記号が入力されてしまいます。  
OSのキーボード設定でLily58をUSキーボードとして設定してください。切り替え後、日本語入力への切り替えがUSキーボード用の切り替えキーになり、JISキーボードとは異なりますのでご注意ください(キーマップなどでカスタマイズ可能)。


**困った場合などはお気軽にDiscordサーバー([Self-Made Keyboards in Japan](https://discordapp.com/invite/NM7XtDW))の「#Lily58」チャンネルもしくはTwitter:@F_YUUCHIにメッセージをお送りください**

## キーマップ変更をする
自作キーボードは上記で使用したqmk firmwareを使用して動作をしています。  
qmk firmwareはカスタマイズ性が非常に高く、キーマップを編集するだけでも非常に高機能にカスタマイズすることができます。
### keymap.cを編集してカスタマイズする
キーマップをカスタマイズする場合はqmk_firmware/keyboards/lily58/keymaps/defaultのフォルダを任意の名前でコピーします。
内部にあるkeymap.cを適宜変更をします。  
キーコードは以下の[qmkの公式ドキュメント](https://docs.qmk.fm/#/keycodes)等を参考にしてください。

キーマップ変更後は

    sudo make lily58:(任意のフォルダ名):avrdude  

で書き込みを行います。エラーが出る場合は確認をしてください。  
  
### QMK Configuratorを使用してカスタマイズする方法(非推奨)
[QMK Configurator](https://config.qmk.fm/#/lily58/rev1/LAYOUT)を使用するとkeymap.cファイルを編集せずにブラウザ上でオリジナルのキーマップを作成可能です。  
作成後ダウンロードしたjsonファイルをQMK Toolboxに読み込み、書き込みを行います。

