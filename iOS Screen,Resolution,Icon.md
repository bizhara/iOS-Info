# iOS 画面，解像度，アイコン
<br>
## 画面サイズ
デバイス名|画面サイズ<br>(inch)|画素数<br>(w * h)|解像度<br>(ppi)
:--|--:|--:|--:
iPhone 3G / 3GS|3.5|320 * 480|163
iPhone 4 / 4S|3.5|640 * 960|326
iPhone 5 / 5s / 5c|4.0|640 * 1136|326
iPhone 6|4.7|750 * 1334|326
iPhone 6 Plus|5.5|1080 * 1920|401
|||
iPad / iPad 2|9.7|768 * 1024|132
iPad Retina|9.7|1536 * 2048|264
iPad Air|9.7|1536 * 2048|264
iPad mini|7.9|768 * 1024|163
iPad mini Retina|7.9|1536 * 2048|326
<br>
## 起動画面
画像名|サイズ<br>(w * h)|対象デバイス名|備考
:--|--:|:--|:--
Default.png|320 * 480|iPhone 3G / 3GS
Default@2x.png|640 * 960|iPhone 4 / 4S
Default-568h@2x.png|640 * 1136|iPhone 5 / 5s / 5c
Default-667h@2x.png|750 * 1334|iPhone 6|
Default-736h@3x.png|1242 * 2208|iPhone 6 Plus|
Default-736h-Landscape@3x.png|2208 * 1242|iPhone 6 Plus|
|||
Default-Portrait.png|768 * 1024|iPad / 2 / mini|
Default-Landscape.png|1024 * 768|iPad / 2 / mini|
Default-Portrait@2x.png|1536 * 2048|iPad Retina / Air / mini Retina|
Default-Landscape@2x.png|2048 * 1536|iPad Retina / Air / mini Retina|
※起動画面画像の管理には、Images.xcassets を使用するべき（ファイル名に縛られることが無くなる）
<br>
## アイコン
種別|画像名|サイズ<br>(w * h (角R))||iPhone|||iPad||
:--|:--|--:|:--:|:--:|:--:|:--:|:--:|:--:
||||iOS5,6|iOS7|iOS8|iOS5,6|iOS7|iOS8
アプリアイコン|Icon.png|57 * 57 (10)|◯|
 |Icon@2x.png|114 * 114 (20)|◯|
 |Icon-60@2x.png|120 * 120 (26)||◯|◯|
 |Icon-60@3x.png ?|180 * 180 (39)|||◯|
 |Icon-72.png|72 * 72 (12)||||◯|
 |Icon-72@2x.png|144 * 144 (24)||||◯|
 |Icon-76.png|76 * 76 (17)|||||◯|◯|
 |Icon-76@2x.png|152 * 152 (34)|||||◯|◯|
AppStore アイコン|iTunesArtwork (png)|512 * 512 (90)|◯|||◯||
 |iTunesArtwork@2x (png)|1024 * 1024 (180)|◯|◯|◯|◯|◯|◯
設定アイコン|Icon-Small.png|29 * 29 (5)|◯|◯|◯|◯|◯|◯
 |Icon-Small@2x.png|58 * 58 (10)|◯|◯|◯|◯|◯|◯
 |Icon-Small@3x.png ?|87 * 87 (15)|||◯|
Spotlight 検索結果アイコン|Icon-Small-40.png|40 * 40 (9)|||||◯|◯
 |Icon-Small-40@2x.png|80 * 80 (18)||◯|◯||◯|◯
 |Icon-Small-40@3x.png ?|120 * 120 (27)|||◯||||
 |Icon-Samll-50.png|50 * 50 (?)||||◯
 |Icon-Samll-50@2x.png|100 * 100 (?)||||◯
※アイコン画像の管理には、Images.xcassets を使用するべき（ファイル名に縛られることが無くなる）
