# TouchDesigner 縦置きフルHD解像度 & Performモード & フルスクリーン起動設定


## アプリの解像度を、縦置きフルHD（1080 x 1920 px）に指定する
![縦置きフルHDの解像度に設定する](https://user-images.githubusercontent.com/1692957/122863750-574d4380-d35e-11eb-84e2-bb23dcebb7c9.jpg)


## フルスクリーン表示、タイトルバーを表示しないように設定する

メニューバー > Dialogs > Window Placement ダイアログを表示
![WindowPlacementダイアログを表示 1](https://user-images.githubusercontent.com/1692957/122867049-e872e900-d363-11eb-9a23-212f37cc8a57.jpg)

Window Placement ダイアログ が表示される
![WindowPlacementダイアログを表示 2](https://user-images.githubusercontent.com/1692957/122867345-4b648000-d364-11eb-9d58-51612eb4f99f.jpg)

P ボタンを押して、/perform ウィンドウ設定ダイアログを表示
![Pボタンを押してウィンドウ設定ダイアログを表示](https://user-images.githubusercontent.com/1692957/122878019-37277f80-d372-11eb-8b24-0f5c26c9d991.png)


① **DPI Scaling** を **Native** に
<br/>
※ **DPI Scaling** が **Use DPI Scale** であると、ディスプレイ設定 > 拡大縮小とレイアウトで、テキスト、アプリ、その他の項目のサイズを変更するが 100％でない場合、そのスケーリング比率を反映してしまうため、適切なウィンドウサイズでアプリが表示されないことがあります。

② **Borders** を **Off** にし、タイトルバーが表示されないようにする

③ **Always on Top** を **Off** にし、他のアプリのよりも優先して上のレイヤーに表示されるようにする。

![ウィンドウ設定ダイアログ](https://user-images.githubusercontent.com/1692957/122905716-6ba83500-d38c-11eb-8e6b-9a06b43a39b7.jpg)


## アプリ起動時に、**Performモード**で起動するようにする

**Start in Perform Mode** にチェックを入れ、TouchDesignerアプリ起動時に、Performモードで
![Performモードで起動](https://user-images.githubusercontent.com/1692957/122906809-8333ed80-d38d-11eb-83a9-1950ae87c322.jpg)


