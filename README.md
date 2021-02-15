# VideoTrackReader_Demo

- Recording animation with Camera and Canvas, using 4 different features.
  - requestAnimationFrame()
  - setInterval()
  - VideoTrackReader
  - MediaStreamTrackProcessor
- カメラ映像とCanvasを使ったアニメーションを録画するデモ。4種類の方法でコマ画像を描画
  - requestAnimationFrame()
  - setInterval()
  - VideoTrackReader
  - MediaStreamTrackProcessor


# How to Use / 利用方法

## Environment/環境

- Chrome 88 or later
  - enable "Experimental Web Platform features" of chrome://flags
- Chrome 88以降
  - chrome://flags で「Experimental Web Platform features」を有効にする

## GitHub Pages で試す / try with GitHub Pages

[Japanese]

- Chromeで https://mganeko.github.io/videotrackreader_demo/ を開く
- 4種類の方法の内、1つをクリックする
- [Start] ボタンをクリック
  - カメラ映像が取得される
  - Canvasにカメラ映像と時刻を合成したアニメーションが表示される
  - 録画が開始
- 録画中に、Chromeのウィンドウを完全に隠したり、最小化してみる
- Chromeのウィンドウを元に戻す
- [Stop] ボタンをクリックkする
  - カメラ映像が停止
  - アニメーション停止
  - 録画停止
  - 録画した映像が再生される

requestAnimationFrame() / setInterval() を使った場合には、録画中にウィンドウが完全に隠れた場合、録画が止まったりコマ送りになっていることが確認できる

[Engligh]

- open https://mganeko.github.io/videotrackreader_demo/
- click 1 of 4 types.
- click [Start] button
  - Camera will start
  - Animation with timestamp will be drawn in Canvas
  - Recording of Canvas will start
- try hiding/minimizing the Chrome window
- restore the Chrome window
- click [Stop] button
  - Camera will stop
  - animation will stop
  - Recording will stop
  - playback of recorded animation will be shown

In case of using requestAnimationFrame() / setInterval(), animation will freeze while the window is hidden/minimized. 


# LICENSE / ライセンス

- MIT


